# OSProject Running Containers for Application Development

Group Name: anis and friends

Section: 2

Team Mates:
1. __ANIS NAZIRA BINTI ABD GHANI__ and __2219732__
2. __NURAMIRATUL AISYAH BINTI RUZAIDI__ and __2212736__


***Questions:***

1. What is the link of the fork OSProject in your repository. ***(1 mark)*** <br> __https://github.com/anisnazira/OSProject__.
2. How many files and folders are in this repository. ***(1 mark)***
 <br>  __- 1 readme.md file__
 <br>  __- 1 images folder__


## Exploring github codespaces


***Questions:***

1. What is default OS used to run the virtual environment for codespaces. ***(1 mark)*** <br> __Ubuntu Linux__.
2. What are the two options of ram, disk and vcpu configuration you can have in running codespaces . ***(1 mark)*** <br> <img src="Q2MachineType.png" width="70%"> <br> __1. VCPU 2-CORE: RAM = 8GB DISK = 32GB <br> 2. VCPU 4-CORE: RAM = 16GB DISK = 32GB__.

3. Why must we commit and sync our current work on source control? ***(1 mark)*** <br> __To saves changes to local repository, pulls changes from the remote to sync with local changes, and then pushes changes to the remote repository__.

## Exploring the Terminal




***Questions:***

Look at the TERMINAL tab. Run the following commands and provide the output here. 

1. Run the command **pwd** . ***(1 mark)*** 
<br><img src="Cmd1.png" width="70%">

2. Run the command **cat /etc/passwd** . ***(1 mark)***
 <br><img src="Cmd2.png" width="70%">

3. Run the command **df** . ***(1 mark)***
<br><img src="Cmd3.png" width="70%">

4. Run the command **du** . ***(1 mark)***
<br><img src="Cmd4.png" width="70%">
<br><img src="Cmd4(2).png" width="70%">
<br><img src="Cmd4(3).png" width="70%">
<br><img src="Cmd4(4).png" width="70%">

5. Run the command **ls** . ***(1 mark)***
<br><img src="Cmd5.png" width="70%">

6. Run the command **ls -asl** . ***(1 mark)***
<br><img src="Cmd6.png" width="70%">

7. Run the command **free -h** . ***(1 mark)***
<br><img src="Cmd7.png" width="70%">

8. Run the command **cat /proc/cpuinfo** . ***(1 mark)***
<br><img src="Cmd8.png" width="70%">
<br><img src="Cmd8(2).png" width="70%">
<br><img src="Cmd8(3).png" width="70%">

9. Run the command **top** and type **q** to quit. ***(1 mark)***
<br><img src="Cmd9.png" width="70%">

10. Run the command **uname -a**. ***(1 mark)***
<br><img src="Cmd10.png" width="70%">

11. What is the available free memory in the system. ***(1 mark)*** <br> __182Mi__.
12. What is the available disk space mounted on /workspace. ***(1 mark)*** <br> __17514292__.
13. Name the version and hardware architecture of the linux Virtual environment. ***(1 mark)*** <br> __Linux codespaces-ff4128 6.2.0-1018-azure #18~22.04.1-Ubuntu SMP Tue Nov 21 19:25:02 UTC 2023 x86_64 x86_64 x86_64 GNU/Linux__.
14. What is the difference between **ls** vs **ls -asl**. ***(1 mark)*** <br> __The ls command lists files and directories in the current directory. The ls -asl command lists all files and directories in the current directory with detailed information, including hidden files, sizes, permissions, and ownership__.
15. What is the TLB size of the Virtual CPU. ***(1 mark)*** <br> __2560 4K pages__.
16. What is the CPU speed of the Virtual CPU. ***(1 mark)*** <br> __3006.680 MHz__.
17. What is the top running process that consumes the most CPU cycles. ***(1 mark)*** <br> __top - 18:15:38 up  2:39,  0 users,  load average: 0.19, 0.22, 0.25__.

    

## Running your own container instance.

***Questions:***

1. Are files in the container persistent. Why not?. ***(1 mark)*** <br> __Files in a container are not persistent because containers are designed to be temporary and easily disposaable. When a container is deleted, its filesystem and any files inside it are also deleted__.
2. Can we run two, or three instances of debian linux? . ***(1 mark)*** <br> __Yes, because each container acts like a separate debian linux system, allowing running multiple instances at once__.

## Running your own container with persistent storage

***Questions:***

1. Check the permission of the files created in myroot, what user and group is the files created in docker container on the host virtual machine? . ***(2 mark)*** <br>__User: codespace <br> Group: codespace__.
2. Can you change the permission of the files to user codespace.  You will need this to be able to commit and get points for this question. ***(2 mark)***
```bash
//use sudo and chown
sudo chown -R codespace:codespace myroot

```
<br><img src="ChangePermission.png" width="70%">

## You are on your own, create your own static webpage



***Questions:***

1. What is the permission of folder /usr/local/apache/htdocs and what user and group owns the folder? . ***(2 mark)*** <br><img src="WebpagePermission.png" width="70%"> <br>__User: 1000 <br>Group: 1000__
2. What port is the apache web server running. ***(1 mark)*** <br> __8080__.
3. What port is open for http protocol on the host machine? ***(1 mark)*** <br> __8080__.<br><img src="Port.png" width="70%">

<br><img src="OurWebpage.png" width="70%">

## What to submit

1. Make sure to commit all changes on your source control, and make sure your source control is sync to the repository. 
2. Check your repository link, to see if all the files and answers are included in the repository. 
3. Submit through italeem, by providing the link to your repository.
4. Due by ***31 January, 2024***
