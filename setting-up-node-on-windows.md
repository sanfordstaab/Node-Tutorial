# Installing node
This tutorial assumes:
 - You are running Windows 7.

Install nodejs by going to http://nodejs.org and upload the latest mature and dependable version and 
run the install.

Once you have done this, open a cmd window and type in the following:
```sh
set node
```

You should see:
```
NODE_PATH=%AppData%\npm\node_modules
```
This is pointing to the root of where global node modules are placed.
Now see what version you have installed:
```sh
node --version
```
You should see something like this:
```
v5.2.0
```
If you check your path:
```sh
path
```
In the output you should see among other things the path to node.exe:
```
C:\Program Files\nodejs\
```


[//]: # (link map)

[nodejs]: http://nodejs.org
