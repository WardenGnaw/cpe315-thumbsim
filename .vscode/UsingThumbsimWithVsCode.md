# ARM Thumb Simulator with VsCode

This is not required for this project, but it is a helpful way to debug this project if you don't wish to setup breakpoints constantly in your debugger.
VsCode is an IDE developed by Microsoft and is free to use on all OS platforms (Linux, OSX, and Windows).

Below are instructions on how to set it up for your machine.

## OSX or Linux

1. Install VSCode from [code.visualstudio.com](https://code.visualstudio.com).
2. Install C/C++ Extension by Microsoft
3. Reload
4. (Optional: Install VsVim Extension if you are a VIM user)
5. Set up a breakpoint by clicking to the left of the number line, and a red dot will appear. (execute.cpp line 175 is a great place to start)
6. Select configuration you want to run. Such as 'fib.sim Test' or 'shang.O0.sim test'. It has already been set up for you, and all you have to do is select a configuration and hit f5.
7. Using the watch window, you can see registers by placing values such as '(int)r[15]'. The int type casting is needed because registers are special union type that the watch window does not know how to display. A fix for this will come in a later version.

## Windows
This is a handful, but it will allow you to compile and run C/C++ programs on your computer.

1. Install [MinGW64](https://mingw-w64.org) to 'C:\MinGW'. And add its bin directory to your windows PATH. E.g. C:\MinGW\mingw64\bin
2. Install VSCode from [code.visualstudio.com](https://code.visualstudio.com).
3. Install C/C++ Extension by Microsoft
4. Reload
5. (Optional: Install VsVim Extension if you are a VIM user)
6. Set up a breakpoint by clicking to the left of the number line, and a red dot will appear. (execute.cpp line 175 is a great place to start)
7. Select configuration you want to run. Such as 'fib.sim Test' or 'shang.O0.sim test'. It has already been set up for you, and all you have to do is select a configuration and hit f5.
8. Using the watch window, you can see registers by placing values such as '(int)r[15]'. The int type casting is needed because registers are special union type that the watch window does not know how to display. A fix for this will come in a later version.