# Shell_C-Cpp
Shell script to compile C/C++ files | Linux | bash

You are testing codes and programming using 'simple' text editors like: vim, nano, vscode, sublime etc. Come with me!

Tired of using IDE's that are heavy, slow or that keep generating unnecessary files in your projects?

Using these text editors, I was running two commands in the terminal, for each code modification.
This is work, and during development you waste time writing boydplat code.
With that I developed a shellScript that runs these two commands automatically and also some extra commands like: clear the terminal and skip the line...


1°) Install GCC on the machine:
~~~
apt-get install gcc
~~~
Or see if GCC is already installed:
~~~
gcc --version
~~~
2°) Enter the folder where the C/C++ project is located

3°) Copy the script in .sh file inside the project folder!
**[shellc.sh] for C | [shellcpp.sh] for C++**

4°) Then give execute permission to the file:
~~~
chmod +x arquivo.sh
~~~
5°) Ready, just run the shell by typing:
~~~
./arquivo.sh
~~~
