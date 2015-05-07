# Capstone Project

## Setting up origin for Windows users

#### Git Client
Go to https://github.com/NCC-Capstone-2015/The-Alumbook<br>
On the far right, click Fork and fork to personal GitHub account<br>
Go to https://www.sourcetreeapp.com/ to download and install SourceTree<br>
Run SourceTree<br>
Login with your GitHub account<br>
In the list of repositories, select The-Alumbook where you are listed as owner<br>
Choose a destination path and click Clone<br>
In the top right corner click Settings, then Add<br>
Make sure Default remote is NOT checked<br>
Enter upstream for the Remote name field<br>
Enter https://github.com/NCC-Capstone-2015/The-Alumbook.git in the URL / Path field<br>
Click OK<br>


#### Using Pull
Click the Pull button on the top of the SourceTree application<br>
Select NCC-Capstone-2015 in the Pull from remote dropdown<br>
Select master from the Remote branch to pull dropdown<br>
Click OK<br>

#### Commit Changes
Click the Commit button on the top of the SourceTree application<br>
Select the files to commit<br>
Enter comments of changes in the bottom text box<br>
Optional: Under Commit Options in the bottom right, you can select Create Pull Request instead of using GitHub.com<br>
Click Commit in the bottom right<br>

#### Using Push
Click the Push button on the top of the SourceTree application<br>
Click OK<br>

#### Creating Pull Request via Browser
Go to GitHub.com<br>
Select your The-Alumbook repository<br>
Click the green button on the left side of the page<br>
Click the green Create Pull Request button<br>


### Changing mysql password
*** if your username is different from root run this command***<br>
<code>
RENAME USER 'root'@'localhost' TO 'root'@'localhost';
</code>
use the manger in the rubystack file <br>
click on phpmyadmin <br>
click on the console on the bottom <br>
run this command <br>
<code>
SET PASSWORD FOR root@localhost = PASSWORD('password');
</code>
this will change whatever your password was previously to password


