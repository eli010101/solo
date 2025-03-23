# solo 
solo is a light weight and simple version control system (vcs) 
for solo devs to use on tracking versions of their mini/small projects 

# how to setup 
termux: pkg update;pkg upgrade;pkg install p7zip;git clone https://github.com/eli010101/solo;cd solo;g++ solo.cxx -o solo;./solo -n test

# how to use 

# branching 
````
solo -b pathtobranch newbranchname
````
# compression/decompression
```
solo -c true/false pathtocompress
```
this will compress paths for saving storage 

# new project creation 
```
solo -n projectname
```
this will create a main inside the project directory.
