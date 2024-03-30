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



cd ~/workspace/jayarajito-ME_QKART_FRONTEND_V2
git add .
git commit -m “ME_QKART_FRONTEND_V2_MODULE_LOGIN”
git push -u origin master

# Ensure you have no pending commits
git status




If all the tests are passing locally but the assessment fails, pull the latest stubs using below commands and ensure all the tests are passing locally



cd ~/workspace/jayarajito-ME_QKART_FRONTEND_V2/
git pull ME_QKART_FRONTEND_V2_MODULE_LOGIN_STUB master --allow-unrelated-histories --no-edit



After you have pushed your changes, you can check this link to confirm if the remote Git repo has received your code.



# Go into the cloned repo directory.
cd ~/workspace/jayarajito-ME_QKART_FRONTEND_V2/

# Setup the remote repository & pull the code stubs for this module.
git remote add ME_QKART_FRONTEND_V2_MODULE_PRODUCTS_STUB git@gitlab.crio.do:ME_QKART_FRONTEND_V2_STUBS/ME_QKART_FRONTEND_V2_MODULE_PRODUCTS_STUB.git
git pull ME_QKART_FRONTEND_V2_MODULE_PRODUCTS_STUB master --allow-unrelated-histories --no-edit

From gitlab.crio.do:ME_QKART_FRONTEND_V2_STUBS/ME_QKART_FRONTEND_V2_MODULE_PRODUCTS_STUB
 * branch            master     -> FETCH_HEAD
 * [new branch]      master     -> ME_QKART_FRONTEND_V2_MODULE_PRODUCTS_STUB/master
Auto-merging src/ipConfig.json
CONFLICT (add/add): Merge conflict in src/ipConfig.json
Auto-merging src/index.js
CONFLICT (add/add): Merge conflict in src/index.js
Auto-merging src/components/Register.js
CONFLICT (add/add): Merge conflict in src/components/Register.js
Auto-merging src/components/Register.css
CONFLICT (add/add): Merge conflict in src/components/Register.css
Auto-merging src/components/Products.js
CONFLICT (add/add): Merge conflict in src/components/Products.js
Auto-merging src/components/Login.js
CONFLICT (add/add): Merge conflict in src/components/Login.js
Auto-merging src/components/Header.js
CONFLICT (add/add): Merge conflict in src/components/Header.js
Auto-merging src/__tests__/Products.test.js
Auto-merging src/App.js
CONFLICT (add/add): Merge conflict in src/App.js
Auto-merging setup.sh
CONFLICT (add/add): Merge conflict in setup.sh
Auto-merging __CRIO__/metadata.json
Automatic merge failed; fix conflicts and then commit the result.



Unmerged paths:
  (use "git add <file>..." to mark resolution)

        both added:      setup.sh
        both added:      src/App.js
        both added:      src/components/Header.js
        both added:      src/components/Login.js
        both added:      src/components/Products.js
        both added:      src/components/Register.css
        both added:      src/components/Register.js
        both added:      src/index.js
        both added:      src/ipConfig.json


        

cd ~/workspace/jayarajito-ME_QKART_FRONTEND_V2
git add .
git commit -m “ME_QKART_FRONTEND_V2_MODULE_PRODUCTS”
git push -u origin master

# Ensure you have no pending commits
git status



If all the tests are passing locally but the assessment fails, pull the latest stubs using below commands and ensure all the tests are passing locally



cd ~/workspace/jayarajito-ME_QKART_FRONTEND_V2/
git pull ME_QKART_FRONTEND_V2_MODULE_PRODUCTS_STUB master --allow-unrelated-histories --no-edit




# Go into the cloned repo directory.
cd ~/workspace/jayarajito-ME_QKART_FRONTEND_V2/

# Setup the remote repository & pull the code stubs for this module.
git remote add ME_QKART_FRONTEND_V2_MODULE_CART_STUB git@gitlab.crio.do:ME_QKART_FRONTEND_V2_STUBS/ME_QKART_FRONTEND_V2_MODULE_CART_STUB.git
git pull ME_QKART_FRONTEND_V2_MODULE_CART_STUB master --allow-unrelated-histories --no-edit


