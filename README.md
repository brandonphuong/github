# Github - How To 
A documentation of git command lines, principles, workflow and implementation.
#### Guides  
* [Git Guide by Roger Dudler](http://rogerdudler.github.io/git-guide/)
* [Github Guides](https://guides.github.com/)
* [Portfolio from Scratch with Github Pages by Dan Nguyen](http://dannguyen.github.io/github-for-portfolios/)
* [Intro to Git for Web Designers](http://www.webdesignerdepot.com/2009/03/intro-to-git-for-web-designers/)
* [Code Visually - Web Developer Tools & Resources](http://codevisually.com/)

####Example Portfolios
* [[1]](http://timmyomahony.com/) [[2]](http://www.exomel.com/en) [[3]](http://denisechandler.com/) [[4]](http://matthewlettini.com/) [[5]](http://hautmonde.ca/) [[6]](http://www.baylesdev.com/)

#### Installation & Setup   
##### Installation  
In terminal, type 
~~~~  
$ sudo apt install git  
$ git config --global user.name "brandonphuong"  
$ git config --global user.email "brandonphuong@gmail.com"
~~~~
#### Setup   
###### This is how to create a git repository using command line first, then linking it to Github.   
~~~~
$ git init [directory] 
$ cd [directory]  
$ echo "# comments" >> README.md  
$ git add -A  
$ git commit -m "first commit"  
$ git remote add origin [url.git]  
$ git push -u origin master
~~~~
