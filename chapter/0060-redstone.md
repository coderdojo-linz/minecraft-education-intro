# Redstone

![Redstone GIF](https://bugs.mojang.com/secure/attachment/290464/6528ea70a79a7eebedfe0e692965e813.gif) <!-- .element: class="hero-smaller"-->


## What is Redstone?

* Like <!-- .element: class="fragment" --> "electricity" built into Minecraft
* You <!-- .element: class="fragment" --> can automate tasks with it
* Requires <!-- .element: class="fragment" --> logical thinking, similar to programming or electronics
  * Start with simple, basic parts
  * Combine these parts to get ever more complex circuits
* (for a quick introduction click [here](https://learn.microsoft.com/en-us/minecraft/creator/documents/redstoneguide)) <!-- .element: class="fragment" -->


## What can you do with Redstone?

* Music <!-- .element: class="fragment" --> ([example](https://youtu.be/yf2TpwC1BXE))
* Automate <!-- .element: class="fragment" --> farms ([example](https://youtu.be/4c_n5hTnjLA))
* Create <!-- .element: class="fragment" --> hidden doors ([example](https://youtu.be/XOLuOmAkK8U))
* Build <!-- .element: class="fragment" --> traps for other players ([examples](https://youtu.be/CAl8okM3LCE))
* Create <!-- .element: class="fragment" --> advanced circuits
  * Logic Gates (OR, AND, XOR, ...)
  * Binary adders
  * Computers ([examples](https://youtu.be/-BP7DhHTU-I))


## Redstone Wire

![Redstone Dust1](images/0060-redstone-dust1.png) <!-- .element: class="main-img"-->
![Redstone Dust2](images/0060-redstone-dust2.png) <!-- .element: class="main-img"-->
![Redstone Dust3](images/0060-redstone-dust3.png) <!-- .element: class="main-img"-->

* Can <!-- .element: class="fragment" --> have a strenght from 0-15
  * Looses one strength for each block travelled
* There <!-- .element: class="fragment" --> are 20 [Game Ticks](https://minecraft.fandom.com/wiki/Tick) per second, but only 10 Redstone Ticks, so Redstone only updates every 100ms
* Read <!-- .element: class="fragment" --> more about [Redstone Dust](https://minecraft.fandom.com/wiki/Redstone_Dust)


## Redstone Inputs

![Button](images/0060-redstone-button.png)
![Lever](images/0060-redstone-lever.png)
![Pressure Plate](images/0060-redstone-pressureplate.png)
![Tripwire Hook](images/0060-redstone-tripwirehook.png) <!-- .element: class="wide-img"-->
![Daylight Detector](images/0060-redstone-daylightdetector.png)

* [Button](https://minecraft.fandom.com/wiki/Button)
  * Click it to emit a temporary signal
* [Lever](https://minecraft.fandom.com/wiki/Lever)
  * Flip it to activate it and send a signal
* [Pressure Plate](https://minecraft.fandom.com/wiki/Pressure_Plate)
  * Sends a signal when someone stands on top
* [Tripwire Hook](https://minecraft.fandom.com/wiki/Tripwire_Hook)
  * Sends a signal if someone walks throught the string
* [Daylight Detector](https://minecraft.fandom.com/wiki/Daylight_Detector)
  * Sends out a signal which gets stronger the brigher the sun is
  * Can be right-clicked to turn into a Nightlight Detector


## Redstone Components

![Redstone Block](images/0060-redstone-redstoneblock.png)
![Redstone Torch1](images/0060-redstone-redstonetorch1.png)
![Redstone Torch2](images/0060-redstone-redstonetorch2.png)
![Repeater](images/0060-redstone-repeater.png)
![Comparator](images/0060-redstone-comparator.png)

* [Redstone Block](https://minecraft.fandom.com/wiki/Block_of_Redstone)
  * Always emits signal
* [Redstone Torch](https://minecraft.fandom.com/wiki/Redstone_Torch)
  * Emits signal, especially up
  * Will be turned off when you power the block it is attached to
  * Redstone Torches can also be plaved on the side of a block
* [Repeater](https://minecraft.fandom.com/wiki/Redstone_Repeater)
  * Strengthens a signal to full strength
* [Comparator](https://minecraft.fandom.com/wiki/Redstone_Comparator)
  * Can compare input from the side to input from behind and only emits signal of signal from behind is stronger
  * Can also read from various sources (see slide #howtolinktoslide?)


## Redstone Devices Part 1

![Lamp](images/0060-redstone-redstonelamp.png)
![Hopper](images/0060-redstone-hopper.png)
![Piston](images/0060-redstone-piston.png)
![Sticky Piston](images/0060-redstone-stickypiston.png)
![Observer](images/0060-redstone-observer.png)

* [Redstone Lamp](https://minecraft.fandom.com/wiki/Redstone_Lamp)
  * Emits light while receiving power
* [Hopper](https://minecraft.fandom.com/wiki/Hopper)
  * Collects items which are thrown on top of it and puts it into inventory below
* [Piston](https://minecraft.fandom.com/wiki/Piston)
  * Pushed up to 12 blocks in front of it on receiving signal
  * Sticky Pistons: Also pulls back a single block in front of it on signal lost
* [Observer](https://minecraft.fandom.com/wiki/Observer)
  * Outputs a signal on the back if the block in front changes


## Redstone Devices Part 2

![Dropper](images/0060-redstone-dropper.png)
![Dispenser](images/0060-redstone-dispenser.png)
![Notenblock](images/0060-redstone-noteblock.png)

* [Dropper](https://minecraft.fandom.com/wiki/Dropper)
  * Drops an item from inventory when receiving a signal
* [Dispenser](https://minecraft.fandom.com/wiki/Dispenser)
  * Same as Dropper, but...
    * if the item can be shot it will shoot it instead of dropping (f.E. Arrows and Snowballs)
	* if the item can be activated or created it will this instead (f.E. TNT, Minecrafts, Boats
* [Noteblock](https://minecraft.fandom.com/wiki/Note_Block)
  * Sounds note if signal is received
  * Note can be tuned by right-clicking it
  * Note depends on block beneath it


## Comaparator sources

![Chest](images/0060-redstone-chest.png)
![Composter](images/0060-redstone-composter.png)
![Cauldron](images/0060-redstone-cauldron.png)
![Item Frame](images/0060-redstone-itemframe.png)

* [Chest](https://minecraft.fandom.com/wiki/Chest)
  * Signal strength read depends on how full the chest is
* [Composter](https://minecraft.fandom.com/wiki/Composter)
  * Signal strength read depends on how full the Composter is
* [Cauldron](https://minecraft.fandom.com/wiki/Cauldron)
  * Signal strength read depends on how full the Cauldron is
  * Cauldron can be filled by rain water
* [Item Frame](https://minecraft.fandom.com/wiki/Item_Frame)
  * If there is no item in the Item Frame the signal is 0
  * Otherwise the signal depends on how far the item is rotated
    * You can rotate it 8 times by right-clicking it


## Minecarts

![Minecart](images/0060-redstone-minecarts.png) <!-- .element: class="wide-img"-->

* [Minecart](https://minecraft.fandom.com/wiki/Minecart)
  * You can drive in them!
* [Rail](https://minecraft.fandom.com/wiki/Rail)
  * Normal rail to transport a Minecart
* [Detector Rail](https://minecraft.fandom.com/wiki/Detector_Rail)
  * Will send out a signal if a Minecart passes over it
* [Booster Rail](https://minecraft.fandom.com/wiki/Booster_Rail)
  * If given a signal, it will boost a Minecart driven over it
  * If not given a signal it will stop a Minecart


## Exercise

![Redstone Road](images/0060-redstone-road.png) <!-- .element: class="hero"-->

[Redstone Road](https://education.minecraft.net/de-de/lessons/redstone-road)


## Download Redstone Road

![Download Redstone Road](images/0060-redstone-road-download.png) <!-- .element: class="hero"-->


## Import Redstone Road

![Import Redstone Road](images/0060-redstone-road-import.png) <!-- .element: class="hero"-->

