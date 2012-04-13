#CodeBase of www.qcha.es 

##Hacking

####Setting Up the Envioroment

    virtualenv --no-site-packages env
    source env/bin/activate
    pip install -r REQUIREMENTS.txt

####Setting Up localdatabase
    mongod --dbpath testdb

To modify settings create a local\_settings.py and set the values you want to
override from settings.py

##How to Help
+ Suggest Features
+ Documentation in wikipages
+ Write Tests
+ Pull Requests

## ROADMAP

    + Backport new templates
    + ????
    + Profit

## REQUIREMENTS

+ __Flask__: A Web Microframewrok
+ __mongoengine__: A NoSQL database
+ __translitcodec__: A Unicode to 8-bit charset transliteration codec
+ __WTForms__: a forms validation and rendering library for python web development
+ __Flask-WTF__: Integration of WTForms with Flask
+ __wtforms-recaptcha__: is a convenient field for WTForms that transparently handles reCaptcha display and validation via corresponding widget and validator classes.

## Qcha Wiki
+ [Ver más en el Wiki](https://github.com/PuercoPop/qchaes/wiki/Qcha-Wiki)
***

#Authors
###MainMantainer
ivoscc@gmail.com

###Colaborator
PuercoPop pirata@gmail.com
