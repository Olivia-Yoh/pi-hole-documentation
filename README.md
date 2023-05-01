# **Network-Wide Personal Adblocker Using Pi-Hole and a Raspberry Pi**

### *Overview*

This project is designed to provide a network-wide adblocking solution using Pi-hole, a popular open-source software that runs on a Raspberry Pi. By installing Pi-hole on your Raspberry Pi and configuring your network settings to use it as the default DNS server, you can block ads and other unwanted online distractions at the network level, providing a faster and more secure browsing experience for all devices on your network.

Link to Pi-Hole website: https://pi-hole.net

### *Prerequisites*

To get started with this project, you will need:

- A Raspberry Pi (any model should work, but a Pi 3 or later is recommended)
	- I bought mine here: https://www.amazon.com/gp/product/B0B5KXJD9N/ref=ppx_yo_dt_b_asin_title_o06_s03?ie=UTF8&psc=1
	- I also bought this starter kit, but I didn't really use it for this: https://www.amazon.com/gp/product/B09ZXNL2WH/ref=ppx_yo_dt_b_asin_title_o06_s00?ie=UTF8&psc=1
- A microSD card (8 GB or larger) to store the operating system and Pi-hole software
	- This should come with your Raspberry Pi
- An Ethernet cable to connect your Raspberry Pi to your router or modem
- A basic understanding of networking concepts and how to configure your network settings

### *Installation and Setup*

I mainly followed the Pi-Hole documentation for setup, which is here: https://github.com/pi-hole/pi-hole, but there are plenty of other resources to help!

## *End Result*

Here is the Raspberry Pi itself. * Don't mind the dust :P *

<img width="500" alt="image" src="https://user-images.githubusercontent.com/129352199/235517332-f6cf7826-a2ea-4697-9ad3-ac08813193f3.png">

The actual computer sits in a protective case, but I can remove the top so you can see it!

<img width="498" alt="image" src="https://user-images.githubusercontent.com/129352199/235517431-5dc2de76-7d91-4382-941f-6acdfb75e104.png">



This is what the Pi-Hole admin page after setup looks like!

<img width="1267" alt="image" src="https://user-images.githubusercontent.com/129352199/235513128-761a5c79-ee26-48dc-9c43-e42ae81ca454.png">

As you can see, the total amount of queries (in this case, ads blocked) in a six month span is almost 300,000!
