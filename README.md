# Hello World!!!

Módul de prova

##Composer+++++++++++++++++++++++++++++++++++++++++++

## Install
Insert in the composer.json file of the Magento 2 project, new repository: 

"alb3rts": {
    "type": "vcs",                                                                  
    "url": "https://github.com/alb3rts/HelloWorld/"                                      
}   

composer require alb3rts/HelloWorld:dev-master

### Run the “setup:upgrade” command
Running this command makes your new module active, notifying Magento of its presence.

php bin/magento setup:upgrade

## Update

composer update alb3rts/HelloWorld

##GitHub+++++++++++++++++++++++++++++++++++++++++++++++

## Clone (desde github)
cd app/code/Mageplaza

git clone https://github.com/alb3rts/HelloWorld.git

## Update last version GitHub (GitHUb->Local)

git pull master

## Info GIT ------------------------------------

###TAGS

git tag v2.0 -m "Segunda versió"

git push --tags

