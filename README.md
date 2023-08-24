# meta_course
this is a repo for meta course
This read me file is four front-end development course from META

The different hosting methods are :

=> Shared Hosting : the best host four small web site
=> Virtual Private Hosting : this use a real hardware server
=> Dedicated Hosting : this is a personal web server
=> Cloud Hosting : physical server + virtual server

HTTP => Hyper Text Transport Protocol
HTTPS => Hyper Text Transport Protocol Secure

The Most used HTTP method are : 
=> GET : Retrieve
=> POST : Send
=> PUT : Update
=> DELETE => Remove

HTTP Status Code are :
=> Informational : 100-199
=> Successful : 200-299
=> Redirection : 300-399
=> Client Error : 400-499
=> Server Error : 500-599

API => Application Programming Interface
=> And API's type are :
=> Browser API
=> Rest API
=> Sensor-Based API
To keep you program runs even you face any problem you must to use try catch an throw new ReferenceError
ex: 
try {
    console.log(a+1);
    throw new ReferenceError;
} catch(error) {
    console.log(error);
}
Types of testing =>
e to e testing like to make your self as a normal user and make interact with the page
Unit testing like you are testing a function or a method
Integration testing like to test your components work together or not

JS Framework
1\_ Jest :
Code Coverage => show the percentage of coverage
Mocking => separating your code from related dependencies during testing
Snapshot testing => verify that there are no regression in the DOM

TDD => Test Driven Development

step one => check if the function exist (failed) 🔴 RED
step tow => declare the function (passed) 🟢 GREEN
step three => check if the function exist (passed) ✅ REFACTOR

to install jest => npm init -y
=> npm install --save-dev jest


Version Control With GIT AND GITHUB =>
Advantages of Version Control :
1\_ Keep track of changes
2\_ Provide access to history
3\_ Revert and roll back

word to search fro it => agile

Version Control name examples =>
Subversion
Perforce
AWS Code Commit
Mercurial
Git

the types of version control => 1\_ centralize version control,2\_Distributed version control

Commend line operators : 
cd => change directory
cd .. or cd / => move out from the current directory
touch index.html => to create a file
mkdir => make directory == create a folder
mkdir -p dir1/dir2 => using the -p flag to create the parent directories if they do not exist. In this case it will create the dir2 directory and then create the dir3 directory inside of dir2.
history => to show the history of the commend line
rm => remove file
code index.js => to open index.js file in vs code
dir => show the files on directory (on commend prompt on windows)
ls => list of files of directory (on linux bash)
ls => ls -l => show the directory files like a list /ls -a/ls -t/ls -r/ls -h
less => show the content of the files part by part and show you the end of the file
man => manual
pwd => print working directory path
cp => copy files or folders 
mv => move files or folders
mv => rename files or folders 
cat file.txt => display the content of an txt files
redirection input and output =>
cat > file.txt => if the file exist your next line is input ,else create the file and take the input
cat < file.txt => display the content of the file
wc => counting how many words are in the file
Pipes :
use pipes to combine commands together. Example: ls file1.txt | wc-w  
think of it like i pass the ls command as input the the wc command
Grep => global regular expression print
ex:
grep ou test1.txt => grep all the content contain ou in there
grep -i ou test1.txt => grep all the content contain ou in the start meddle and final
Git Command =>
git clone "https://githubRepoUrl" : download the file in your local Machine
git init . : check if the .git folder is exist or not
git status : check if there is any change in your branch
git add file.extension : to add the file to the tracked stat
git restore --stage file.extension : to back one step before use git add file.extension
git commit -m "your message" : to commit your change with a message
git push -u origin main : to push you committed files to your branch
git checkout -B feature/lesson : to create a new branch
git checkout main => to change to the main branch
feature => name given to the default remote repository
lesson => the name of a branch in the Git repository
git branch => to check in which branch you are
git pull =>  used to fetch and integrate changes from a remote repository into your local repository
git remote =>
git remote -v =>