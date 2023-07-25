# SolarisDongleMultiInverters

This is a very simple application. Thanks to PJPullinger for providing the sketch.
In RS485 the dongle is the "master" and the Solis is the "slave".
First you need to check the slave addresses in each inverter which is under settings "set address" and you need to set them to different values.
Now make up a lead using one male and one female back to back to act as an extender for your dongle. Colours and pins as shown in my eBay https://www.ebay.co.uk/itm/195668989940 with all pins wired and test it against both inverters.
If that is successful you can add a second female plug with the pin3 yellow and all the pin4 blue only connected to the pin3 and pin4 on either of the "extender's" plugs. It doesn't matter which and depends only on where your inverters and dongle are. The key point is that the this is a parallel connection.
Now you can test it with both inverters. If you're using screened cable be careful only to ground it at the power-slave inverter.
