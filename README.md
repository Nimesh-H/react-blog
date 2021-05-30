Installing
Make sure you have these installed
node.js
git
Create React App
Clone this repository into your local machine using the terminal (mac) or Gitbash (PC) > git clone CLONEURL
CD to the folder cd FOLDERNAME
Run npm install to install the project dependencies
Run npm start to start live preview server
Downloading All Branches
For more advanced users, you can also download all of the branches for this repository.

mkdir NAME
cd NAME
git clone --bare CLONEURL .git (make sure you add extra .git)
git config --bool core.bare false
git reset --hard
Run npm install to install the project dependencies
Run npm start to start live preview server
