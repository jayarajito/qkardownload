curl -d '{"username":"crio.do", "password":"learnbydoing"}' -H "Content-Type: application/json" -X POST http://65.1.113.119:8082/api/v1/auth/register


Use the commands from the code block below to commit your changes and push them to the remote Git repository for assessment.

cd ~/workspace/jayarajito-ME_QKART_FRONTEND_V2
git add .
git commit -m “ME_QKART_FRONTEND_V2_MODULE_REGISTER”
git push -u origin master

# Ensure you have no pending commits
git status




# Go into the cloned repo directory.
cd ~/workspace/jayarajito-ME_QKART_FRONTEND_V2/

# Setup the remote repository & pull the code stubs for this module.
git remote add ME_QKART_FRONTEND_V2_MODULE_LOGIN_STUB git@gitlab.crio.do:ME_QKART_FRONTEND_V2_STUBS/ME_QKART_FRONTEND_V2_MODULE_LOGIN_STUB.git
git pull ME_QKART_FRONTEND_V2_MODULE_LOGIN_STUB master --allow-unrelated-histories --no-edit




cd /home/crio-user/workspace/jayarajito-ME_QKART_FRONTEND_V2/
chmod +x setup.sh
./setup.sh




curl -d '{"username":"crio.do", "password":"learnbydoing"}' -H "Content-Type: application/json" -X POST http://15.206.158.163:8082/api/v1/auth/login
