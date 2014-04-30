openshift-static-nodejs
=======================

Project can be deployed into openshift cloud and also can run grunt in local

###How to install it###

1. Clone the project
2. Use `npm install` in dev and openshift folder to download nodejs package
3. run `ln -s openshift/app ../dev/app" to link the app folder 
3. run `bower install` to download javascript library

###How to use it###

1. In dev mode: run grunt server under `dev` folder
2. Can push the openshift/app folder into openshift
