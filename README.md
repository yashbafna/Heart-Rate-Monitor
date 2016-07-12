# Heart-Rate-Monitor
##Installation
Import [Jar](https://goo.gl/aQrA8q) in your project.
##Usage
Use the following code in MainActivity.java to call out monitor.
```
HeartRateMonitor heartratemonitor= new HeartRateMonitor(MainActivity.this);
```
To get the beats in bpm use
```
String value= HeartMonitorBeats.GetValue();
```
##Note
Call GetValue() after 10 seconds as it takes 10 seconds to scan and count beats.
##Sample app
Visit [Heart Rate Monitor](https://goo.gl/TirCYQ)
