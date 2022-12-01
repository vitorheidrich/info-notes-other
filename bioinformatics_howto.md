# HOW TO

A small recopilation of general processes performed on a daily basis 
and necessary in the bioinformatic life. 

## How to know where a program is installed 

- The program `which` allows you to check it out for many cases. 

```
which python
```

This will output the specific path to which it was installed. It is useful 
if you want to call this specific program from some other program or yout want 
to evaluate if the installed version of a program is the one you are calling. 

## How to copy files from remote to local

This was one of the main problems I found during the PhD, and I still find from time to 
time. 

Everytime I talk it out with people I discover that during the PhD I was doing rather rudimentary 
approaches to this. But well, it was what I was thaught by you people, the internet! 

Initially I had an alias to `scp` (secure copy protocol) which copied files in a directory called tunnel 
both in local and remote. 

To copy files, now I mostly use a program with this specific purpose:

- In Linux, I used `FileZilla` https://filezilla-project.org/ 
- In MACOS, I used `cyberduck`  https://cyberduck.io/

Once you use these, you cannot get back to the old ways. 

In Linux, you can also configure in Nautilus (the program that shows the directories and so on) to connect to the server
and simply copy and drag as usually the files of interest. 

- Click to `Other Locations`. In my Ubuntu version, it is left slightly below. 
- Add the server address below, in `Connect to Server` this:
    - `sftp://<your.name>@<your.server.ip>/`
- This I am sure it works with servers presenting FTP (file transfer protocol). With 
other types of servers I don't know. 

## How to work in remote directly 

### Work remotely on R 

RStudio has RStudio server which is amazingly good and easy to use. 

I felt stupid when I discovered how to install it. 

It opens an R console for you in the server, and it is the common editor you know with all the same 
configurations and shortcuts. 

To install it: 

- Follow all the installation instructions from [this webpage](https://posit.co/download/rstudio-server/)
- Try to connect following [this page](https://support.posit.co/hc/en-us/articles/200552306-Getting-Started)
- In my case, after doing that I was not able to open the connection through Mozilla. It was because I did not have opened the specific
port through which the server was trying to emmit. 

- With this: `sudo ufw allow 8787` you open the channel. 

Obviously for this last step you need root privileges, which in many servers it won't be the case. You 
will have to talk to your admin to allow it. 

Additionally, in some server organizations this won't be possible for large calculations. Because if everyone connected to the `main` node and 
performed its calculations there the CPU usage would make it unfeasible. All this largley depends on the structure designed in 
each case. 

### Work remotely on any-language

My guess is that I can do the same with other IDES, such as Visual Studio. 

TBL

## How to change user ownership for a file/directory 

You have a folder created by someone else or you want to pass some data to someone else. 

```
# change the owner
sudo chown <owner> <file> 

# change the group, the group of users that can modify it 
sudo chgrp <group> <file>
```




























