[![Travis](https://img.shields.io/travis/rust-lang/rust.svg)]()
[![Codecov](https://img.shields.io/codecov/c/github/codecov/example-python.svg)]()
## Facebook Messenger Bot
This module is a chatbot developed using python and tensorflow backend. The original concept is adapted from here: https://blog.hartleybrody.com/fb-messenger-bot/. The module can be integrated with facebook messenging api by deploying onto Heroku app server. Training of the intents is done offline and later deployed into Heroku cloud.

##### Dependencies
- Flask v0.11.1
- Jinja2 v2.8
- MarkupSafe v0.23
- Werkzeug v0.11.10
- click v6.6
- gunicorn v19.6.0
- itsdangerous v0.24
- requests v2.10.0
- nltk v3.2.4
- tensorflow v1.2.0
- numpy v1.13.1
- tflearn v0.3.2
- h5py v2.7.1
- python v3.5.2

##### Usage Detail
Modify the intents.json file to add or remove your response for the bot, To train:
 ```sh
    $ python3 train.py
 ```
For evaluation:
 ```sh
    $ python3 eval.py
 ```

##### For Deployment onto facebook messenger
follow the instructions at: https://blog.hartleybrody.com/fb-messenger-bot/


##### Demo Video on YouTube
[![IMAGE ALT TEXT](http://img.youtube.com/vi/ZW0B2wk8dPA/0.jpg)](http://www.youtube.com/watch?v=ZW0B2wk8dPA "Yolo Road Obstacle Detector")
