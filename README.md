# _HEART-TO-HEART-TALK---Puso-sa-Puso-PH
_HEART TO HEART TALK - Puso sa Puso PH
# _ $ pkg update && pkg upgrade -y
pkg install nodejs-lts ollama nano -y
Checking availability of current mirror:
[*] https://packages-cf.termux.dev/apt/termux-main: ok
Hit:1 https://packages-cf.termux.dev/apt/termux-main stable InRelease
Reading package lists... Done
Building dependency tree... Done
Reading state information... Done
All packages are up to date.
Checking availability of current mirror:
[*] https://packages-cf.termux.dev/apt/termux-main: ok
Hit:1 https://packages-cf.termux.dev/apt/termux-main stable InRelease
Reading package lists... Done
Building dependency tree... Done
Reading state information... Done
All packages are up to date.
Reading package lists... Done
Building dependency tree... Done
Reading state information... Done
Calculating upgrade... Done
0 upgraded, 0 newly installed, 0 to remove and 0 not upgraded.
Checking availability of current mirror:
[*] https://packages-cf.termux.dev/apt/termux-main: ok
Reading package lists... Done
Building dependency tree... Done
Reading state information... Done
ollama is already the newest version (0.31.1).
nano is already the newest version (9.2-1).
The following packages will be REMOVED:
  nodejs
The following NEW packages will be installed:
  nodejs-lts
0 upgraded, 1 newly installed, 1 to remove and 0 not upgraded.
Need to get 9744 kB of archives.
After this operation, 3654 kB disk space will be freed.
Get:1 https://packages-cf.termux.dev/apt/termux-main stable/main aarch64 nodejs-lts aarch64 24.18.0-1 [9744 kB]
Fetched 9744 kB in 3s (3337 kB/s)
dpkg: nodejs: dependency problems, but removing anyway as you requested:
 npm depends on nodejs | nodejs-lts; however:
  Package nodejs is to be removed.
  Package nodejs-lts is not installed.

(Reading database ... 86233 files and directories currently installed.)
Removing nodejs (26.4.0-1) ...
Selecting previously unselected package nodejs-lts.
(Reading database ... 86099 files and directories currently installed.)
Preparing to unpack .../nodejs-lts_24.18.0-1_aarch64.deb ...
Unpacking nodejs-lts (24.18.0-1) ...
Setting up nodejs-lts (24.18.0-1) ...
Processing triggers for mandoc (1.14.6-7) ...
~ $ ollama run deepseek-r1:1.5b
Error: could not connect to ollama server, run 'ollama serve' to start it
~ $ pkg update && pkg upgrade -y
pkg install nodejs-lts ollama nano -y
Checking availability of current mirror:
[*] https://packages-cf.termux.dev/apt/termux-main: ok
Hit:1 https://packages-cf.termux.dev/apt/termux-main stable InRelease
Reading package lists... Done
Building dependency tree... Done
Reading state information... Done
All packages are up to date.
Checking availability of current mirror:
[*] https://packages-cf.termux.dev/apt/termux-main: ok
Hit:1 https://packages-cf.termux.dev/apt/termux-main stable InRelease
Reading package lists... Done
Building dependency tree... Done
Reading state information... Done
All packages are up to date.
Reading package lists... Done
Building dependency tree... Done
Reading state information... Done
Calculating upgrade... Done
0 upgraded, 0 newly installed, 0 to remove and 0 not upgraded.
Checking availability of current mirror:
[*] https://packages-cf.termux.dev/apt/termux-main: ok
Reading package lists... Done
Building dependency tree... Done
Reading state information... Done
ollama is already the newest version (0.31.1).
nano is already the newest version (9.2-1).
The following packages will be REMOVED:
  nodejs
The following NEW packages will be installed:
  nodejs-lts
0 upgraded, 1 newly installed, 1 to remove and 0 not upgraded.
Need to get 9744 kB of archives.
After this operation, 3654 kB disk space will be freed.
Get:1 https://packages-cf.termux.dev/apt/termux-main stable/main aarch64 nodejs-lts aarch64 24.18.0-1 [9744 kB]
Fetched 9744 kB in 3s (3337 kB/s)
dpkg: nodejs: dependency problems, but removing anyway as you requested:
 npm depends on nodejs | nodejs-lts; however:
  Package nodejs is to be removed.
  Package nodejs-lts is not installed.

(Reading database ... 86233 files and directories currently installed.)
Removing nodejs (26.4.0-1) ...
Selecting previously unselected package nodejs-lts.
(Reading database ... 86099 files and directories currently installed.)
Preparing to unpack .../nodejs-lts_24.18.0-1_aarch64.deb ...
Unpacking nodejs-lts (24.18.0-1) ...
Setting up nodejs-lts (24.18.0-1) ...
Processing triggers for mandoc (1.14.6-7) ...
~ $ ollama run deepseek-r1:1.5b
Error: could not connect to ollama server, run 'ollama serve' to start it
~ $
