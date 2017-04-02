# learning-lua
Learning Lua Programming Language

1. Building Lua in macOSX: open a terminal and cd to the lua top directory and run the following command. This will build lua.

make macosx

2. Run the following command in the top level lua directory to test lua that was just build. This will print lua version if the build was successful.

make test

3. Install lua: To install lua locally - run the following command. This will create a directory named "install" which contains lua language binaries.

make local


The resultant directory will look like this:

>lua-x.x.x
  > Makefile	
  > README		
  > doc		
  > install		
  > src
