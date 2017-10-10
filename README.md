# Application Development on Watson Conversation 
## A. List of wechat
|Source code | Description                       | Reference |
|:------------|:---------------------------------|:---------|
|tuling.py | wechat robot, w/ Tuling backend API | http://www.tuling123.com|
|tuling-specUser.py | chat service, restricted for specific wechat-usergroup| https://github.com/littlecodersh/ItChat|
|watson-console.py | console-based example for waston-conversation|
|watson-wechat.py | wechat as client | https://github.com/watson-developer-cloud/python-sdk|
|watson-tuling-wechat.py | wechat client + 2*backends ( # for Tuling, #IBM for Watson )|

### how to run
1. install python runtime
2. install itchat: pip install itchat
3. apply service from Tuling ( www.tuling123.com )
4. apply service & create conversation from IBM Bluemix ( bluemix.net )
5. install watson SDK: $ sudo -H pip install --ignore-installed six watson-developer-cloud
6. modify credentials
7. python xx.py 

## B. List of console
|Source code | Description                       | reference |
|:-----------|:----------------------------------|:---------|
|example1.js | | |
|example2.js | | |
|example3.js | | |
|example4.js | | |

### how to run
npm install
modify credentials
nodejs exampleX.js

## C. List of Nodered
|Source code | Description                       | reference |
|:-----------|:----------------------------------|:---------|
|watson-debugMode.json |waston-conversation, running in debug mode | |
|watson-sockets.json |run in web mode, socket communication | |

### how to run
1. create node-red application in IBM Bluemix
2. create service watson conversion
3. launch node-red application -- web designer
4. import flow from above json
5. modifiy 'conversation' node property in these flow

debug: 
- click flow (left input node)
- https://nodered-jon001.eu-gb.mybluemix.net/testing

web: 
- https://nodered-jon001.eu-gb.mybluemix.net/testing

