About
=====
Repo create a PushNotification Server

Requirements
============
1. Python3.4, pip3 and nodeJS
2. Python modules : tornado, json, requests
3. Node modules   : rectify

Instructions
============
1. Clone mutoPush repo to local system
2. In Terminal run 'python3 pushServer.py`
 
Input/Output
============
1. Input is Json Object with Key: Value pair as {"platform" : platform, "deviceID" : deviceID } to serverUrl:8000/push
2. Output response is "{"iOS" : "OK"}, {"Android" : "OK"} or {"Status" : "FAILED" } based on the request.
 
