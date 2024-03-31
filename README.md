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




# Go into the cloned repo directory.
cd ~/workspace/jayarajito-ME_QKART_FRONTEND_V2/

# Setup the remote repository & pull the code stubs for this module.
git remote add ME_QKART_FRONTEND_V2_MODULE_CART_STUB git@gitlab.crio.do:ME_QKART_FRONTEND_V2_STUBS/ME_QKART_FRONTEND_V2_MODULE_CART_STUB.git
git pull ME_QKART_FRONTEND_V2_MODULE_CART_STUB master --allow-unrelated-histories --no-edit



From gitlab.crio.do:ME_QKART_FRONTEND_V2_STUBS/ME_QKART_FRONTEND_V2_MODULE_CART_STUB
 * branch            master     -> FETCH_HEAD
 * [new branch]      master     -> ME_QKART_FRONTEND_V2_MODULE_CART_STUB/master
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
Auto-merging src/components/Products.css
CONFLICT (add/add): Merge conflict in src/components/Products.css
Auto-merging src/components/ProductCard.js
CONFLICT (add/add): Merge conflict in src/components/ProductCard.js
Auto-merging src/components/Login.js
CONFLICT (add/add): Merge conflict in src/components/Login.js
Auto-merging src/components/Header.js
CONFLICT (add/add): Merge conflict in src/components/Header.js
Auto-merging src/components/Cart.js
CONFLICT (add/add): Merge conflict in src/components/Cart.js
Auto-merging src/App.js
CONFLICT (add/add): Merge conflict in src/App.js
Auto-merging setup.sh
CONFLICT (add/add): Merge conflict in setup.sh
Auto-merging __CRIO__/metadata.json
Automatic merge failed; fix conflicts and then commit the result.



On branch master
Your branch is up to date with 'origin/master'.

You have unmerged paths.
  (fix conflicts and run "git commit")
  (use "git merge --abort" to abort the merge)

Changes to be committed:

        modified:   __CRIO__/metadata.json
        new file:   src/__tests__/Cart.test.js
        new file:   src/components/Checkout.css
        new file:   src/components/Checkout.js

Unmerged paths:
  (use "git add <file>..." to mark resolution)

        both added:      setup.sh
        both added:      src/App.js
        both added:      src/components/Cart.js
        both added:      src/components/Header.js
        both added:      src/components/Login.js
        both added:      src/components/ProductCard.js
        both added:      src/components/Products.css
        both added:      src/components/Products.js
        both added:      src/components/Register.css
        both added:      src/components/Register.js
        both added:      src/index.js
        both added:      src/ipConfig.json



        
curl 'http://localhost:8082/api/v1/cart' 



curl 'http://localhost:8082/api/v1/cart' \
  -H 'Authorization: Bearer <token>'



  
curl 'http://localhost:8082/api/v1/cart' \
  -H 'Authorization: Bearer <token>' \
  -H 'Content-Type: application/json' \
  --data-raw '{"productId":"BW0jAAeDJmlZCF8i","qty":1}' \


  curl 'http://localhost:8082/api/v1/cart' \
  -H 'Authorization: Bearer tteyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1c2VybmFtZSI6ImpheWFyYWppdG9AZ21haWwuY29tIiwiaWF0IjoxNzExOTE1OTMxLCJleHAiOjE3MTE5Mzc1MzF9.CThlNQGyUPNRosXNVckCrw4bKVe8evsb_PfvfOLTBYg' \
  -H 'Content-Type: application/json' \
  --data-raw '{"productId":"BW0jAAeDJmlZCF8i","qty":1}' \

  

  curl 'http://localhost:8082/api/v1/cart' \
  -H 'Authorization: Bearer eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1c2VybmFtZSI6ImpheWFyYWppdG9AZ21haWwuY29tIiwiaWF0IjoxNzExOTE1OTMxLCJleHAiOjE3MTE5Mzc1MzF9.CThlNQGyUPNRosXNVckCrw4bKVe8evsb_PfvfOLTBYg' \
  -H 'Content-Type: application/json' \
  --data-raw '{"productId":"BW0jAAeDJmlZCF8i","qty":1}' \


    curl 'http://localhost:8082/api/v1/cart' \
  -H 'Authorization: Bearer eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1c2VybmFtZSI6ImpheWFyYWppdG9AZ21haWwuY29tIiwiaWF0IjoxNzExOTE1OTMxLCJleHAiOjE3MTE5Mzc1MzF9.CThlNQGyUPNRosXNVckCrw4bKVe8evsb_PfvfOLTBYg' \
  -H 'Content-Type: application/json' \
  --data-raw '{"productId":"BW0jAAeDJmlZCF8i","qty":5}' \

      curl 'http://localhost:8082/api/v1/cart' \
  -H 'Authorization: Bearer eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1c2VybmFtZSI6ImpheWFyYWppdG9AZ21haWwuY29tIiwiaWF0IjoxNzExOTE1OTMxLCJleHAiOjE3MTE5Mzc1MzF9.CThlNQGyUPNRosXNVckCrw4bKVe8evsb_PfvfOLTBYg' \
  -H 'Content-Type: application/json' \
  --data-raw '{"productId":"BW0jAAeDJmlZCF8i","qty":0}' \


[{"productId":"BW0jAAeDJmlZCF8i","qty":1}]
  

How to generate and use bearer token for authentication?
https://www.youtube.com/watch?v=n-IFlWGX1t4

curl -d '{"username":"crio.do", "password":"learnbydoing"}' -H "Content-Type: application/json" -X POST http://15.206.158.163:8082/api/v1/auth/login

Post: http://3.111.215.64:8082/api/v1/auth/login

{"username":"jayarajito@gmail.com", "password":"123456"}

{
    "success": true,
    "token": "eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1c2VybmFtZSI6ImpheWFyYWppdG9AZ21haWwuY29tIiwiaWF0IjoxNzExOTE1OTMxLCJleHAiOjE3MTE5Mzc1MzF9.CThlNQGyUPNRosXNVckCrw4bKVe8evsb_PfvfOLTBYg",
    "username": "jayarajito@gmail.com",
    "balance": 5000
}




cd ~/workspace/jayarajito-ME_QKART_FRONTEND_V2
git add .
git commit -m “ME_QKART_FRONTEND_V2_MODULE_CART”
git push -u origin master

# Ensure you have no pending commits
git status

Note
If all the tests are passing locally but the assessment fails, pull the latest stubs using below commands and ensure all the tests are passing locally



cd ~/workspace/jayarajito-ME_QKART_FRONTEND_V2/
git pull ME_QKART_FRONTEND_V2_MODULE_CART_STUB master --allow-unrelated-histories --no-edit





# Go into the cloned repo directory.
cd ~/workspace/jayarajito-ME_QKART_FRONTEND_V2/

# Setup the remote repository & pull the code stubs for this module.
git remote add ME_QKART_FRONTEND_V2_MODULE_CHECKOUT_STUB git@gitlab.crio.do:ME_QKART_FRONTEND_V2_STUBS/ME_QKART_FRONTEND_V2_MODULE_CHECKOUT_STUB.git
git pull ME_QKART_FRONTEND_V2_MODULE_CHECKOUT_STUB master --allow-unrelated-histories --no-edit



From gitlab.crio.do:ME_QKART_FRONTEND_V2_STUBS/ME_QKART_FRONTEND_V2_MODULE_CHECKOUT_STUB
 * branch            master     -> FETCH_HEAD
 * [new branch]      master     -> ME_QKART_FRONTEND_V2_MODULE_CHECKOUT_STUB/master
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
Auto-merging src/components/Products.css
CONFLICT (add/add): Merge conflict in src/components/Products.css
Auto-merging src/components/ProductCard.js
CONFLICT (add/add): Merge conflict in src/components/ProductCard.js
Auto-merging src/components/Login.js
CONFLICT (add/add): Merge conflict in src/components/Login.js
Auto-merging src/components/Header.js
CONFLICT (add/add): Merge conflict in src/components/Header.js
Auto-merging src/components/Checkout.js
CONFLICT (add/add): Merge conflict in src/components/Checkout.js
Auto-merging src/components/Cart.js
CONFLICT (add/add): Merge conflict in src/components/Cart.js
Auto-merging src/App.js
CONFLICT (add/add): Merge conflict in src/App.js
Auto-merging setup.sh
CONFLICT (add/add): Merge conflict in setup.sh
Auto-merging __CRIO__/metadata.json
Automatic merge failed; fix conflicts and then commit the result.




cd ~/workspace/jayarajito-ME_QKART_FRONTEND_V2
git add .
git commit -m “ME_QKART_FRONTEND_V2_MODULE_CHECKOUT”
git push -u origin master

# Ensure you have no pending commits
git status



Note
If all the tests are passing locally but the assessment fails, pull the latest stubs using below commands and ensure all the tests are passing locally



cd ~/workspace/jayarajito-ME_QKART_FRONTEND_V2/
git pull ME_QKART_FRONTEND_V2_MODULE_CHECKOUT_STUB master --allow-unrelated-histories --no-edit


After you have pushed your changes, you can check this link to confirm if the remote Git repo has received your code.

https://gitlab.crio.do/COHORT_ME_QKART_FRONTEND_V2_ENROLL_1684925308327/jayarajito-ME_QKART_FRONTEND_V2




Render is the platform where you’ll deploy your backend and Vercel is the platform where you’ll deploy your frontend.


Set up project for assessment
Replace your "CRIO/metadata.json" file contents with the below one




{

    "module_id": "ME_QKART_FRONTEND_V2_MODULE_DEPLOYMENT",

    "me_id": "ME_QKART_FRONTEND_V2"

}



Start by signing in to Render with Google Sign-in here.

https://dashboard.render.com/

In the dashboard, click "New +" button then select the second option which is Web Services.

In the Create a new Web Service, click on Connect GitHub, here you will select your GitHub repository which contains your project.

You will be redirected to the below page, here just give the name for your web service i.e "Name" = qkart-frontend, “Root Directory” = backend and “Start Command” = npm start

"Name" = myqkart-frontend, “Root Directory” = backend and “Start Command” = npm start

             Then click on "Create Web Service"

             ==> Your service is live 🎉
QKart Backend running at port 10000

https://myqkart-frontend.onrender.com

https://myqkart-frontend.onrender.com/api/v1/products


To Fork the repository from the Crio GitLab account into your personal GitHub account our Crio team has to push your codes, for this kindly raise a new chat to the Platform team.



Set up GitHub Copilot
Use GitHub's AI pair programmer to autocomplete suggestions as you code.

Add collaborators to this repository
Search for people using their GitHub username or email address.

Quick setup — if you’ve done this kind of thing before
or	
https://github.com/jayarajito/QKART.git
Get started by creating a new file or uploading an existing file. We recommend every repository include a README, LICENSE, and .gitignore.

…or create a new repository on the command line
echo "# QKART" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/jayarajito/QKART.git
git push -u origin main
…or push an existing repository from the command line
git remote add origin https://github.com/jayarajito/QKART.git
git branch -M main
git push -u origin main
…or import code from another repository
You can initialize this repository with code from a Subversion, Mercurial, or TFS project.



git clone https://github.com/jayarajito/QKART.git

git add .

git commit -m "first commit"

git remote add originqkart https://github.com/jayarajito/QKART.git

git branch -M main

git push -u originqkart main



