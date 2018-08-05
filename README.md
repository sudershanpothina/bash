# bash
cmd - echo "string"
prints text on the console
Add text to a file
cmd - echo "string" > greetings.txt

cat is to display the file content
cmd - cat filename 


ctrl+L to clear console

cmd - less filename 
to scroll through the list 
q is to exit
less is useful for large files

cmd - ps -ef
to store output to a file
cmd: ps -ef > log.txt
cmd: less log.txt

Chains commands
use pipe to chains commands

ps -ef | less 

get back to home dir
cd ~
or cd

apt install tree
shows the graphical representation of the file structure

tree

tree>structure.txt


WHICH command - check where the package is installed
apt install curl


unzip command
apt install unzip


CURL 

curl -O https://bphogan.com/thatconf.zip
-O saves the file with the same name

unzip thatconf.zip

tree | structure.zip

ctrl+a to jump to the front of the line and ctrl+e to jump to the end

To run previous command with another command use ^prev^current 
ex - git diff test.txt
^diff^add 


run previous command adding something

ex - mkdir var/test
sudo !! - running this command as sudo user

Runnign previous commands
history
get the number 
!number of the command

ls -l to get the permissions listed

ls -al to get all of the files

ls -alh to get file sizes in readable format

ls -alh directory to get attributes of that fiel
ex - ls -alh /var/log/syslog
ls -alhd to get information of the directory

To get back to the previous directory
cd - 

pushd to create an array
pushd /usr/bin
pushd /var

popd to get something out of the command

popd /var

dirs to get the list in the array
dirs -v to list all the options in the list

~/Desktop to jump to the user root folder and goto Destop folder

Append content to the file
echo "content" >> filename 

Create a interactive session to add content
cat > filename
ctrl+d to add data



cat<< EOF > names.txt
ex- 
test1
test2
EOF

EOF will designate the end of the file and no need of pressing ctrl+d


cat real purpose is to concat files
cat file1 file 2 
This will print both the files

Create a new file concating two files

cat file1 file2 > file3


