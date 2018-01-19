# DIY-watering-system
DIY garden watering system


In this project I will show you what to do and what to code to achive automated garden watering system in your home controlled by app on your smartphone, from your computer or any other devices that you can connect to the network.

<h1>Steps</h1>

1. Visit webpage: http://mygarden.gardena.com/pl/ 
This is web application where you can design your garden. Follow the steps in the wizard and application will plan for you how much watering points you will need. It depends how big is your garden, do you have good enough water pressure in you valve etc. 
Application gives you list for the products that you need to buy (pipes, valves, etc) also controller, but you can forgive about this one :)

If you already have watering system in your garden you can simply go to step 2.

2. Depending on how many water cycles you have in your garden you will need electro valves. in my case I have 4. 
What you need to have:

- NodeMcu ESP8266 
- N electro-valves (with proper diamiter)
- N+1 relays
- 5V power supply 
- power transformer 230V AC to 24v DC
- breakfast vacuum box 
- some cables
- Wi-Fi network :)

On this stage you can choose, do you want to have independent system which you can just controll "on demand" or you want to make watering systema part of something bigger :) 

If you choose first option, upload to your ESPNodeMCU unit sketch "Independent System"
