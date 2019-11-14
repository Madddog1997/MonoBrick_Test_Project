# MonoBrick Test Project
Just open the solution and then choose Program.cs
Either comment :
  - using MonoBrick.EV3
  - using MonoBrick.NXT

To use between these 2 types.

For communication with Bluetooth rename "connection" in
```
new Brick<Sensor, Sensor, Sensor, Sensor>("connection");
```
to either:
  - COM(number) for bluetooth (Specified in bluetooth setting for outgoing communication)
  - USB for usb connection
  - WIFI for WiFi connection (Only EV3)
