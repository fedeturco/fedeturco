- 👋 Hi, I’m Federico Turco
- 👀 I work with C#/WPF, Python and Embedded Systems in general. 
- 👀 I'm very interested in Domotic, I'm KNX Partner n.: 93370 with ETS5 Professional Licence
- 👀 I also like PLC Programming, with TC3 Beckhoff family mainly
<!--- - 📫 Contacts: --->

On my repository i published some clients helpful to debug and simulate ModBus Master/Slaves devices.

# C# Clients

## ModBus Client
This is a WPF client uset to poll ModBus slaves, it's helpful to debug slaves where there are many resources on different locations because it permits to bind labels and conversion (int32,float,string etc.) to different memory locations according to the ModBus protocol Reference.\
https://github.com/fedeturco/ModBus_Client

## ModBus Server Simulator
This is an appplication i developed to emulate multiple slvaes modbus, for example if you need to emulate a set of n power meters, or multiple ModBus sensors. In the App you can create different profiles and assign them to different heads which run on different processes. The App can be used standalone on a Windows Machine or you can use it as client to configure a Raspberry PI as a Mosbus Slave Simulator. The Raspberry result very handy if you need to test your ModBus Master application for many days leaving the Raspberry connected to your PLC Master (often happens that the customer provides me a single modbus slave to read and implement on the back development side but i need many ones to test the embedded system on the final configuration).\
https://github.com/fedeturco/ModBusServerConfigurator

## Client PING
C#/WPF client useful to keep track of network devices in your LAN\
https://github.com/fedeturco/Client_PING

## NetManager
This is a client used to switch ip-adddress configuration of network interfaces on a Windows PC, you can create different profile of ip classes and switch from one to another simply using the client instead of looking for the current form in the panel settings.\
[https://github.com/fedeturco/NetManager](https://github.com/Fedex1515/NetManager)

## ModBus Server
This WPF application emulates a single ModBus slave, TCP or RTU. With that you can change memory locations at runtime and view the logs of every query received by the App.\
https://github.com/fedeturco/ModBus_Server

# Other

## GW ModBus TCP <-> RTU
The GW Modbus is a C application i developed to share ModBus resourced behind a RS485 via TCP. With this on an embedded linux system equipped with an RS485 serial port (tty) you can share slaves on the 485 side and make them available using your embedded linux system (for example a Raspberry Pi3 with an USB485 converter) as a TCP server.\
https://github.com/fedeturco/Gw_Modbus_C


<!--- - 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...--->
<!---
Fedex1515/Fedex1515 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
