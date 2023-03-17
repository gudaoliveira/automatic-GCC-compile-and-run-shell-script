# Automatic GCC Compile and Run

## This is a shell script intended to be used along the GCC compiler in linux

Hi! This is my first shell project, and despite being very simple, i decided to post anyway to show my progress learning Linux and Shell scripting.

I'm learning C Programming right now, and typing more than to lines of code to compile and run my projects everytime was stressing me out. So i thought, what would a _Senior Software Engineer_ would do in my place?

He would automate this process, of course!

### So, what does this script do?
* It takes two arguments
    * The first one is the name of your C script
    * The second one is the name of your output file
    * Ex: _(./ccompiler.sh **HelloWorld.c HelloWorld.out**)_
* If there is any error on the code it won't do anything besides showing the error, otherwise...
* Creates a folder called "executables"
* Enters the folder, executes the program and return to the input script folder

## SEE IT WORKING
<video width="100%" height="240" controls>
  <source src="./demonstration.mp4" type="video/mp4">
</video>

## HOW TO INSTALL
First off all make sure that you have the latest version of GCC installed