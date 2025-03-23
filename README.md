# solo 
solo is a light weight and simple version control system (vcs) 
for solo devs to use on tracking versions of their mini/small projects 

# how to setup 
termux: pkg update;pkg upgrade;pkg install p7zip;git clone https://github.com/eli010101/solo;cd solo;g++ solo.cxx -o solo;./solo -n test

# how to use 
branching 

solo -b <pathtobranch> <newbranchname>

compression/decompression for storage consumption 

solo -c true/false <pathtocompress>

new project creation 

solo -n <projectname> 

this will create a main inside the project directory.
