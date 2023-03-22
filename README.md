# Welcome to mysmartblinds - let the sun wake you up

Almost everyone is using window blinds / rollos at the insides of windows. The default method to move blinds like that up and down is via a pearl chain. That can be annoying in everyday use, especially if there are curtains, beds or tables close to the window. I created a system, which can automate your blinds or rollos, easy manually control is of course possible as well.

The system is a plug&play replacement for the existing pearl chain drive. Installation takes just a minute and the configuration is done super easy via web browser. The wireless connection is standard wifi and IP based, thus one can use any end device like smartphone, PC... After installation and configuration one can use a klick in any browser, any voice assistent like Siri or daily time based setting to move the blinds up or down.

While running, the system is virtually silent.

## Software images

<pre><img src="images/controlcenter.png" width="190px">&#9;<img src="images/timer.png" width="190x">&#9;<img src="images/setup.png" width="190px">&#9;<img src="images/network.png" width="190px"></pre>

## Device images

<pre><img src="images/device_mounted.png" width="800px"></pre>
<pre><img src="images/dev1.jpeg" width="300px">&#9;&#9;<img src="images/dev2.jpeg" width="300px"></pre>

## Key features

- Intuitive web frontend
- System works without any internet connection, but you need a NTP server in order to have the right time
- Plug&Play installation
- System is 5 Volt based
- Micro USB connector used for power connection
- Low power mode (great when powered with batteries)
- whisper quiet while running
- Left/Right mounting mode (Software switch)
- Precise prositioning
- Standard hardware
- Easy to integrate in voice assistents

## Communication

- Standard wireless LAN connection based on 802.11
- Simple wifi setup via web frontend (DHCP or fixed IP)
- Internet independent, NO connection needed
- Only a ntp server is needed for time sync, this can be your local router, then the system never leaves your LAN

## Functions

- Easy setup for all functions
- Everything is controlable via integrated web frontend
- Timer for up/down movement for every weekday
- Sleep Mode for ultra low energy consumption (only timer function is active)
- Updates via web frontend
- Factory reset via web frontend or hardware button

## Control

- Via web interface
- Easy integration in any home automation system (http links)
- Voice assistents like Siri

## Extras

- Easy to adapt with any blind system


## Whats needed?

- For each blind a ESP-32 micro controler board, a 28BYJ-48 5vdc stepper motor with controller, some dupond cables and a 5v power supply with micro usb connector are needed

- ESP-32: https://amzn.to/3uuozcW
- Stepper motor with controller: https://amzn.to/3FgGmcW
- OPTIONAL - Mini stepper motor controller: https://amzn.to/3Bu9mfZ
- Any 5v power supply with micro usb connector

**You can also buy plug&play solution which includes a 3d printed drive enclosure, mini stepper driver inclusive ESP-32 adapter.**
[Drive enclosure with stepper driver and ESP-32 adapter](https://www.etsy.com/de/listing/1120088196/wifi-wlan-rollo-innenrollo-doppelrollo?ga_order=most_relevant&ga_search_type=all&ga_view_type=gallery&ga_search_query=rollo+antrieb&ref=sr_gallery-1-1&edd=1&organic_search_click=1)

## Connection schematic

The following pictures shows the wireing diagram for the basic controller, which mostly comes with the stepper motor.

<pre><img src="schematics/schematic.png" width="400px"></pre>

## Installation and setup

[Installation guide](https://github.com/danieldownload/mysmartrollo/wiki/Installation-guide)





## Donate
If you would like to support the developer with a cup of coffee you can do that via [Paypal](https://www.paypal.com/donate/?hosted_button_id=XN85B8YSH7KBL)
