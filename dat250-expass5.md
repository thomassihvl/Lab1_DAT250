# dat250-expass5.md

# Technical problems
I encountered problems with an Apache Daemon running on port 8080. After some heavy googling I managed to identify what it was, and after more googling I found out where my Apache installation was. I found the config file, but couldn't edit it. Luckily, VSCode rode in on its white horse and saved me from the scary daemon, allowing me to edit in administrator mode (apparently not as easy on windows11 as it used to be on windows10). I changed the port and started coding. 

Another issue I encountered was that IntelliJ had reinstalled my Java SDK without adding to PATH or JAVA_HOME. I googled my way through this as well, and managed to change them. Also, the provided installation guide of Spring CLI didn't really help me, as the commands didn't work and I was missing packages required to run the recommended package installer... Another guide helped me install it manually.

Other than that things went pretty smoothly. However, the time estimates in the guides were highly underexaggerated in my case, it took me about 5 hours of work to read, complete and fix everything, not 15 minutes per task...

[Link to github repository here](https://github.com/thomassihvl/dat250-expass5)