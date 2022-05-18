# Fahrplan

Eine kleine Webanwendung, die live die nächsten Events in verschiedenen Räumen anzeigt. 

## Install
```
docker build -t fahrplan_img .
docker run -d -p 80:80 --name fahrplan fahrplan_img
```
