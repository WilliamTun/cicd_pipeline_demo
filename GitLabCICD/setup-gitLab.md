
1. Sign up and login to Gitlab account
2. Click on profile pic on top right, and on the drop down, click settings
3. Go to SSH keys on left hand panel
4. On local terminal create a key:
	`ssh-keygen -t rsa -b 4096 -c <key-name>`
5. `cat ~/.ssh/id_rsa.pub`
6. Take the output from above and paste it into the appropriate box on Gitlab

  
