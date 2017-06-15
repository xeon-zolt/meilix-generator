# meilix-generator
------------------------------
https://melix-generator.herokuapp.com/


to run it locally

```
sudo pip install virtualenv
git clone https://github.com/Meilix-Generator/meilix-generator.git
cd meilix-generator
virtualenv venv
source venv/bin/activate
sudo pip install -r requirements.txt 
export FLASK_DEBUG=1 FLASK_APP=app.py 
flask run
```
the application will greet you on
         http://localhost:5000/

Setting up Travis With meilix (the repo used for generation of ISO)

* Travis Env Variables

![travis env variable](https://github.com/xeon-zolt/meilix-generator/blob/update-Readme/ScreenShots/travis-Env-Variables.png?raw=true)

Adding Env Variables in Travis 

*

Adding Env Variables In Heroku

*

###### for building OS using meilix scripts with the help of a web app
