# learning-lua
Learning Lua Programming Language

1. Building Lua in macOSX: open a terminal and cd to the lua top directory and run the following command. This will build lua.

make macosx

2. Run the following command in the top level lua directory to test lua that was just build. This will print lua version if the build was successful.

make test

3. Install lua: To install lua locally - run the following command. This will create a directory named "install" which contains lua language binaries.

make local


The resultant directory looks like this:

&gt;lua-5.3.4<br />
&nbsp;&nbsp;&nbsp;&gt;Makefile<br />
&nbsp;&nbsp;&nbsp;&gt;README<br />
&nbsp;&nbsp;&nbsp;&gt;doc<br />
&nbsp;&nbsp;&nbsp;&gt;install<br />
&nbsp;&nbsp;&nbsp;&gt;src


4. Running Lua - run lua using command line.

&gt;./install/bin/lua

This brings up a prompt to write lua code.

Lua 5.3.4  Copyright (C) 1994-2017 Lua.org, PUC-Rio<br/>
&gt; 


5. Print "Hello World"

Lua 5.3.4  Copyright (C) 1994-2017 Lua.org, PUC-Rio<br />
&gt;print("Hello World")<br />
Hello World
