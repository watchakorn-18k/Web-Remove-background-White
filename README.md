# Web-Remove-background-White
📙 Web-Remove-background-White



# Example 
- test in replit : https://replit.com/join/exxfwuozad-watchakorn18k
- website : http://wk18k.zapto.org:5000/


<p align="center">
<img src="https://github.com/watchakorn-18k/Web-Remove-background-White/blob/master/Image-Test.jpg" width="200">
<img src="https://github.com/watchakorn-18k/Web-Remove-background-White/blob/master/static/test12.png" width="200">
</p>

# Setup
```
git clone https://github.com/watchakorn-18k/Web-Remove-background-White.git
cd Web-Remove-background-White
```



# Install Package 
## UBUNTU
```
virtualenv env
source env/bin/activate
pip install -r requirements.txt
```
## WINDOWS
```
virtualenv env
.\env\Scripts\activate
pip install -r requirements.txt
```

# Start Server
```
python app.py
```

# File Settings
```
start.sh        # service on run startup in ubuntu
.replit         # file run on replit
```

# Add Service in Ubuntu

## Add PATH service
```
/etc/systemd/system/RemoveStartUp.service
```

## RemoveStartUp.service
```
[Unit]
Description = Remove BG White

[Service]
ExecStart = bash /usr/local/sbin/start.sh


[Install]
WantedBy = multi-user.target
```

# Credits
UI website File Upload & Image Preview : https://codepen.io/gaitho/pen/mjBBLP 
how to remove background of images in python : https://stackoverflow.com/questions/63001988/how-to-remove-background-of-images-in-python?answertab=active
# Contributions
If you want to contribute to a project and make it better, your help is very welcome. Contributing is also a great way to learn more about social coding on Github, new technologies and and their ecosystems and how to make constructive, helpful bug reports, feature requests and the noblest of all contributions: a good, clean pull request.
Click : https://github.com/watchakorn-18k/Web-Remove-background-White/pulls
