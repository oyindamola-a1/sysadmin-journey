**STANDARD INPUT**

If a file is not, the "grep" command will read from standard input, which normally comes from the keyboard with input provided by the user who runs the command.

**SHUTTING DOWN**

The "shutdown" command arranges for the system to be brought down in a safe way, unlike other commands used to bring the system down, the "shutdown"command requires a time argument specifying when the shutdown should begin.

**NETWORK CONFIGURATION**

The "ifconfig" command stands for [ interface configuration ] and it's used to display network configuration information.

**NOTE**; The "iwconfig" command is similar to the "ifconfig" command, but it is dedicated to wireless network interfaces.

- The "lo" device is referred to the loopback device, it is a special network device used by the system when sending network based data to itself.
- The "ifconfig" command can be used to temporarily work settings. The "ping" command is used to verify connectivity between two computers, it does this by sending packets to another machine on a network.


- **VIEWING PROCESSES**

- Running a command in something called a PROCESS. In the linux operating system, processes are executed with the privileges of the user who executes the command.

  The "ps" command will display the processes that are running in the current terminal by default. Some of the output includes;

  - **PID**;The process identifier, which is unique to the process.
  - **TTY**;The name of the terminal where the process is running.
  - **TIME**;The total amount of processor time used by the process.
  - **CMD**; The command that started the process.
 
  Instead of viewing just the process running in the current terminal, user may want to view every process running on the system. The [ -e ] option will display every process.

  **PACKAGE MANAGEMENT**

  Package maangement is a system by whivh software can be installed, updated, quieriedor removed from a filesystem. In linux, there are many system software package management systems,but the two most popular are those from Debian and Red Hat. The virtual machines for this courses uses ubuntu, a derivation od debian. At the lowest level of the debian package management system is the "dpkg" command.

  **INSTALLING PACKAGES**

  Package files are commonly installed by downloading them directly from repositories located on internet servers.

  To search for keywords within this packages you can use the "apt-cache search" command. The keyword that is used should match part of the name or description of the package that's to be located.

  **UPDATING PACKAGES**

  The [apt-get install] command can also update a package, if that package is installed and a newer version is installed. Updating all packages of the system should be done in two step, First, update the cache of all package available with the [apt-get update]. Secondly, execte the {apt-get update] command and all packages and dependencies will be updated.

  **REMOVING PACKAGES**

  Thw [apt-get] command is able to either remove or purge a package. The difference between the two is that purging deletes al package files, while removing deletes all but the configuration files for the package. An administrator can exexute the [apt-get remove] command to remove a package or the [apt-get purge] command to purge a package completely from the system.
    
