![alt text](https://hackster.imgix.net/uploads/attachments/1452202/image_gtg3pui50c.png?auto=compress%2Cformat&w=740&h=555&fit=max)

For all the IoT makers and newbies, we very well know and understand the Blynk IoT Platform and how to use the Blynk 1.0 (Legacy version). But as Blynk has upgraded to Blynk 2.0 there were many changes made in the new documentation which are not yet noted or maybe missed out.This article points to understanding and implementing not only the Dashboard usage of both Blynk 1.0 and 2.0 but also all the API endpoints that make its usage of it functional. Blynk is a full suite of software required to prototype, deploy, and remotely manage connected electronic devices at any scale: from personal IoT projects to millions of commercial connected products.
The above text is an official statement/description of what Blynk really is, and what it serves as a solution for the General Public as a tool.

Think about a Plug-and-Play IoT Platform for the IoT Developers, to build and develop IoT applications on-the-go. Blynk is exactly the same, with easy-to-make buttons, visualization charts, and many more from it.The ability to use drag-and-drop widgets has made the IoT Platform grow even more. In only a matter of seconds, we can control our Wireless Board from the Web Dashboard, as well as Mobile App.

![alt text](https://hackster.imgix.net/uploads/attachments/1508803/image_HXj0dhYKkz.png?auto=compress%2Cformat&w=740&h=555&fit=max)

Back in 2016, when Blynk introduced multiple features like the ability to use the Library file and directly connect any WiFi-enabled board to the Blynk Cloud. Since then the Cloud was LIVE and had a pretty decent latency. Which caught the attention of many IoT developers or learners. It was this period of time when people started building many projects on this platform and the world of IoT became a thing for people.

Since then Blynk started documenting all the procedures, and steps required to use their platform.From this App, with each new project, we are provided with an Auth Token which we can use to access the Blynk Cloud and its services. Either we can use the App to control/monitor our Wireless devices, or use the Auth Token to access the LIVE data using API requests.


![alt text](https://hackster.imgix.net/uploads/attachments/1508970/image_6hzC8KvDSQ.png?auto=compress%2Cformat&w=740&h=555&fit=max)

With Blynk 2.0, which includes many features as listed. Another feature is also present, which allows for reduction in uploading code when change in network is observed frequently. Uploading a new code to the Board without having to reconnect to a PC, using the Edgent OTA feature. We can directly get started with the Example provided by them. In the Arduino IDE, navigate to Files > Examples > Blynk > Blynk.Edgent > Edgent_ESP32 - It will open default code.

Here, only make the changes in the Edgent_ESP32.h file, like adding Virtual Pins to be controlled or monitored, widget properties, timers, etc

![alt text](https://hackster.imgix.net/uploads/attachments/1518136/8_tJuwoRM3dI.JPG?auto=compress%2Cformat&w=740&h=555&fit=max)

You must check out [PCBWAY](https://www.pcbway.com/) for ordering PCBs online for cheap!

You get 10 good-quality PCBs manufactured and shipped to your doorstep for cheap. You will also get a discount on shipping on your first order. Upload your Gerber files onto PCBWAY to get them manufactured with good quality and quick turnaround time. [PCBWay](https://www.pcbway.com/) now could provide a complete product solution, from design to enclosure production. Check out their online Gerber viewer function. With reward points, you can get free stuff from their gift shop.
