# Basic-Linux-File-Management-Commands

### Stage 1: Displaying only the first and last lines of a log

Before we do anything we first want to switch into a user whos log we want to view. In this case we will view "user1"s logs.

Run:
su - user1  (switches you to user1)
whoami      (shows what user you currently are)

![Pt 1](https://github.com/Magee3/Basic-Linux-File-Management-Commands/assets/134301259/10c98ec2-6ba5-49ce-97bf-73a480b2d0c3)

We will read the dnf.log file located in  /var/log. The dnf.log contains package information, timestamps. repository information, error messages and more. This file
contains a long list of logs, to long to just read and find what you want with just your eyes. We can view the first few lines of any files with the "head" command.

Run: head /var/log/dnf.log
![Pt 2](https://github.com/Magee3/Basic-Linux-File-Management-Commands/assets/134301259/3f6ae3f7-0c65-4f5d-8488-918baf09be1b)

As you see we get a few lines of logs, mainly just debugging information. We can also review the most recent logs or logs at the end by using the "tail" command.

Run: tail /var/log/dnf.log

![Pt 3](https://github.com/Magee3/Basic-Linux-File-Management-Commands/assets/134301259/2c418b0f-f001-4cba-909e-2e7ccad04b9c)

At the end of user1's logs we see that the debugging proccess has completed.
![Pt 4](https://github.com/Magee3/Basic-Linux-File-Management-Commands/assets/134301259/8898a23d-0d52-441a-a5eb-210cc7bb2984)
![Pt 5](https://github.com/Magee3/Basic-Linux-File-Management-Commands/assets/134301259/5553828f-46a3-4ec6-97d0-a7bb850372d1)
![Pt 6](https://github.com/Magee3/Basic-Linux-File-Management-Commands/assets/134301259/2f9c7b2b-aed2-48e3-8026-3bb077179e3d)
![Pt 7](https://github.com/Magee3/Basic-Linux-File-Management-Commands/assets/134301259/717e9a5a-7797-4cd4-a949-02573fce8e74)
![Pt 8](https://github.com/Magee3/Basic-Linux-File-Management-Commands/assets/134301259/0aa17f7a-2284-4520-87b7-132b2651afed)
