## Ghost Bus Data Backend

###Intro

This is the data backend part of a semester long project called "Ghost Bus" - an augmented reality experience for the MTA B54 bus route. The project involves augmenting the bus' real-time location for riders to be able to visualise how close/far the bus is from their stop. 

This simple web app will interact with the MTA SIRI API to grab B54 bus data. It will then parse the data and communicate with the Unity3D project in order to reflect the moving bus.

###Deploy

```
python app.py
```

You'll probably need [https://www.python.org/](python) and [https://github.com/pypa/pip](pip) 

###Usage

You can use this for any GTFS feed from the [http://bustime.mta.info/wiki/Developers/SIRIVehicleMonitoring](SIRI API)
```
response = urllib2.urlopen('the-API-call-URL')
```

