Installed git and signed up to GitHub.
Check working directory, Created MarketPeak_Ecommerce, changed directory to MarketPeak_Ecommerce and initalized repository on Git.
Download Ecommerce HTML template and save inside MarketPeak_Ecommerce Folder.
Add Pixie file to git repository, stage and commit it.
Create a repository on Github and cloned it to create a local copy on my computer.
Generated a GitHub token and used it to link to Git by running Git command on SSH terminal.
     git remote add origin https://ghp_tHYIVE5JkxOXOcfDwtTds6AfJFMJNu0uzm@github.com/chinonyenwoko/MarketPeak_Ecommerce.git.
Run Push command to upload local repository to GitHub.
Change directory to location of Pem Key, Launch AWS EC2 Ubuntu instance and connect is to SSH termainal with below command.
     ssh -i "key.pem" ubuntu@ec2-16-171-37-97.eu-north-1.compute.amazonaws.com .
Clone the GitHub repository on AWS EC2 Ubuntu Instance with the HTTP URL below, input User name and password to Authenticate.
     git clone https://github.com/chinonynwoko/MarketPeak_Ecommerce.git .
Install Apache2 Web server on AWS EC2 instance and configure commans below.
      sudo apt update
      sudo apt install Apache2
      sudo systemctl start apache2
      sudo systemctl status apache2
      sudo systemctl stop apache2
      sudo rm -rf /var/www/html/*
      sudo cp -r ~/MarketPeak_Ecommerce/* /var/www/html/
      ls -l /var/www/html
Enable port 80 on the AWS EC2 Instance security to allow HTTP traffic .
Launch the Ecommerce website on internet browser using the public iP address .
       16.171.146.94/2114_pixie 
Create a new Git branch and name it development. Add a new html feature, stage and commit it and push to remote repository.
create a pull request on GitHub to see changes on both branches and merger to main branch, the push changes to remote repository.
Then Test changes.
      
