# Badri-CLI_dill_1
#!/bin/bash

mkdir hello

cd hello
mkdir five one

cd five 
mkdir six

cd six
touch c.txt

mkdir seven

cd seven 
touch error.log

cd ~/Desktop/hello/one
touch a.txt b.txt

mkdir two

cd two
touch d.txt

mkdir three

cd three
touch e.txt

mkdir four

cd four
touch access.log

cd ~/Desktop/hello/five/six/seven
rm error.log

cd ~/Desktop/hello/one/two/three/four
rm access.log

cd ~/Desktop/hello/one
echo 'Unix is a family of multitasking, multiuser computer operating 
systems that derive from the original AT&T Unix, development 
starting in the 1970s at the Bell Labs research center by Ken 
Thompson, Dennis Ritchie, and others.' > a.txt

cd ~/Desktop/hello
rm -r five

mv one uno

cd uno
mv a.txt ~/Desktop/hello/uno/two
