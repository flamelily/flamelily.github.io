---
layout: blog-page
img:
link: 
category: Raspberry Pi
tags: car computer,carputer,raspberry pi,knight rider
permalink: /:year/:month/:title/
title: Raspberry Pi car computer
description: |
excerpt_separator: <!--more-->
---

I have always loved those old TV series with futuristic tech in those futuristic vehicles, like Knight Rider, Air Wolf, Street Hawk etc. So it got me thinking about how easy it would be to add a computer to a vehicle. Now I know its been done before and a quick Google search shows multiple websites and companies making very complex car and other vehicle computers, but at a large cost. <!--more-->[caption id="attachment_504" align="aligncenter" width="625"]![Raspberryi Pi running raspbian "wheezy"](/wp-content/uploads/2013/05/2013-05-01-18.52.37-1024x768.jpg) Raspberryi Pi in my Ford Focus running raspbian "wheezy"[/caption] Well I thought my Raspberry Pi is the perfect device for this. 

  * Its cheap
  * its very small
  * small power requirements (runs off a micro USB car charger)
  * flexible video and audio outputs (HDMI and Composite RCA for video, HDMI and 3.5mm audio jack for audio)
  * and best of all you can change operating systems by simply switching out SD cards
Below is a photo of the Raspberry Pi running the excellent media centre type operating system [Raspbmc](http://www.raspbmc.com/) which is perfect for browsing and playing your media collection using a media centre remote or something similar, as shown in my 'shopping list' below. [caption id="attachment_505" align="aligncenter" width="500"]![Raspbmc running on a Raspberry Pi](/wp-content/uploads/2013/05/2013-05-02-18.05.22-768x1024.jpg) Raspbmc running on a Raspberry Pi in the Car[/caption] **What I did** Well firstly I had the Xtron car DVD player for the Ford already fitted and it can be found on this site here <http://www.xtrons.co.uk/> and there are DVD/Radio players for a number of car manufacturers. However you don't actually need one of these if you can place a TFT screen elsewhere. I also have one of these.. [caption id="attachment_506" align="aligncenter" width="300"]![7" TFT monitor which can be used for the back seats](http://www.flamelily.co.uk/wp-content/uploads/2013/05/2013-05-02-11.21.04-300x225.jpg) 7" TFT monitor which can be used for the back seats[/caption] Which can be found on Ebay for about £23 at this link. <http://stores.ebay.co.uk/SainSpeed> This 7" TFT can be placed in a headrest or on the dash somewhere as it comes with a stand. Both of these devices have a composite RCA video input and for audio I have a basic 3.5mm audio cable from the Raspberry Pi to the auxiliary port of the radio. So all audio is played via the car speakers which sounds really good and clear. I placed the Raspberry Pi in the centre console as shown below and routed all cables under the centre console so no cables are lying around. [caption id="attachment_507" align="aligncenter" width="300"]![Centre Console of Ford Focus holding Raspberry Pi](http://www.flamelily.co.uk/wp-content/uploads/2013/05/console1-300x250.jpg) Console of my Ford Focus holding the Raspberry Pi[/caption] [caption id="attachment_508" align="aligncenter" width="225"]![Centre Console Raspberry Pi with power from USB charger](http://www.flamelily.co.uk/wp-content/uploads/2013/05/console3-225x300.jpg) Centre Console Raspberry Pi with power from USB charger[/caption] I used the brilliant little Xenta Wireless Keyboard with mouse touchpad built-in. This works perfectly with both Raspbian and Raspbmc. It even has an on/off button on the back to save batteries when not in use (it takes 2xAA batteries). [caption id="attachment_509" align="aligncenter" width="209"]![Raspberry Pi and mini keyboard](http://www.flamelily.co.uk/wp-content/uploads/2013/05/console2-209x300.jpg) Raspberry Pi and mini keyboard[/caption] So this can now connect to any wireless network and I connect it to my mobile phone by using the portable wi-fi hotspot, giving my Raspberry Pi an internet connection even on the move (obviously don't try browse the internet or watch videos whilst driving). Materials Used : 

  1. Raspberry Pi (Obviously)
  2. Xtrons Car DVD player
  3. 7" TFT monitor (for back seats or main monitor)
  4. Extra composite video cable and 3.5mm audio cable
  5. Wireless N USB dongle from [Amazon](http://www.amazon.co.uk/gp/product/B008FZO1A2/ref=as_li_tf_tl?ie=UTF8&camp=1634&creative=6738&creativeASIN=B008FZO1A2&linkCode=as2&tag=flait-21)
  6. Xenta Wireless Mini Keyboard from [Ebuyer](http://www.ebuyer.com/250233-xenta-wireless-mini-keyboard-with-touchpad-and-multimedia-keys-usb-pkb-1720)(out of stock now) Try [this one](http://www.amazon.co.uk/gp/product/B004GAGM1Q/ref=as_li_tf_tl?ie=UTF8&camp=1634&creative=6738&creativeASIN=B004GAGM1Q&linkCode=as2&tag=flait-21) instead
  7. Micro USB car charger
Update pictures of headrest in next blogpost here <http://wp.me/p2G9uP-8j>

## Comments

**[Vern](#704 "2013-05-26 19:08:08"):** Nice setup! Are you concerned at all about battery drain? The Pi pulls up to 700mA @ 5V (Or about 3.5W, which I think is about 291mA as seen by the battery on the 12V side of the USB adapter, not including loss due to the USB adapter itself or anything else plugged into the adapter). It certainly isn't a lot, but would add up over time. If the Pi isn't doing anything and is at idle it probably pulls less, but I don't know a good way to estimate that. I suppose that in instances where you expect the car to be sitting for a while you could simply shut down and unplug the Pi and/or the USB adapter. I was actually toying with the idea of putting a Pi in my own car to take advantage of the AirPlay functionality in RaspBMC. Audio-only, no video for my needs. I'll probably just stick with the bluetooth adapter until I can convince myself I need this sort of setup instead :) Another thought, if you want to get that far into it: you could rig up a 3V adapter for the wireless keyboard to do away with batteries. Again, great setup!

**[kevin](#693 "2013-05-26 01:56:23"):** Nice car! Focus rocks!

**[RedR](#680 "2013-05-24 13:13:20"):** I can not help wonder about heat issues. Any chance you could log temp values from the Pi and and post them for us? Thanks for the blog, and great job on this!

**[Tushar](#677 "2013-05-24 08:52:09"):** Nice work, Below mention url may be you liked to see. https://www.youtube.com/watch?v=LJevH5H5wHQ&autoplay=1

**[Anthony Kavassis](#676 "2013-05-24 08:51:36"):** If you're looking to get better audio quality I would recommend using a Texas instruments USB DAC (i.e. PCM 2704) which is compatible with OpenELEC and Raspbmc. You can get one easily off Ebay for near 15-20 dollars and that'll give you a nice clean sound from the Raspberry Pi. The one I'm using right now is a 2 channel with coaxial SPDIF output but you can get a version which also has optical SPDIF. If you combine it with an amplifier with SPDIF input (i.e. Audison amplifier which has also volume control) then the end result should be spectacular for your car. As far as power for your Raspberry Pi, it might not be necessary to shut down the Pi at all because you can run it off a USB power pack in line with your USB charger so when you take out the key from the ignition and the switched 12V is cut-off by the CAN BUS in your Ford it should leave only battery pack powering the Raspberry Pi. I tested mine with the Dension TripStick which also made it easier to get 3G access in the car and it ran a full HD video for over 2 hours and 20 minutes. I didn't do a stand-by test but in theory it should be at least eight hours and that'll mean that by the time you get back in your car it'll still be running so there wouldn't be a need to power off the Pi at all.

**[Jayson](#665 "2013-05-23 20:13:35"):** Looks great! Linked over here from the Raspberry Pi blog. I just had a couple of simple questions for you: Does the power in your center console have "always on" power, or does the power shut off when you turn the car off? If the power shuts off when you turn the ignition off, do you manually power down the RPi beforehand or just let it power down? I'm assuming now that since you replaced the stock unit, you can no longer listen to radio or manipulate balance/fader/EQ settings? Thanks for the great writeup!

**[admin](#666 "2013-05-23 20:38:35"):** Hi Jayson Basically the Pi runs off the console car charger (shown in the pic) and that happens to be constant power whether the car is off, running or on accessory. So yes I just power down the Pi using the excellent Xenta mini keyboard (also shown in a pic). Yes I can listen to radio and manipulate balance etc as the replacement radio has all that build in with an Aux input for the Raspberry Pi. It runs off Windows CE 6.0 and has Ipod connector, USB, SatNav etc. I just select Aux on the touch screen to see the Raspberry Pi. See the link for the Xtrons site for more details on this radio.

**[Jayson](#668 "2013-05-23 21:18:30"):** Ah, I get it. At first I was under the assumption that you replaced your stock stereo with a screen dedicated to the raspberry pi. I see now that Xtrons controls everything, with the raspi just acting as one of the inputs. Excellent!

**[Matthew](#723 "2013-05-27 23:00:16"):** Very well done; I am planning to do something similar in my Chevrolet Trailblazer, though I will probably mount the display somewhere out of sight if I don't end up replacing the current head unit.

**[admin](#733 "2013-05-28 08:59:16"):** Yes basically I shut down the pi when not in use and its not usually running when the car is stopped (as the kids watch things whilst I drive) so not really worried about battery drain.

**[Dan Y](#1427 "2013-07-18 21:59:59"):** A few weeks ago I setup my spare Raspberry Pi as a CarPC. I started by breaking open an old mobile phone car charger and removing the voltage regulator circuit, then I soldered the fuse directly to the voltage regulator live wire and soldered the live and ground from the voltage regulator to the back of my cigarette lighter socket, then I plugged my Pi into the voltage regulator so that its always got power (the car is a ford escort). I have left the Pi turned on with nothing playing for at least 2 days at a time with no drain on my battery. To be honest I think it would have to be left for a long time to drain a car battery so that would be the least of my worries. If you want to see my setup so far heres the link: http://www.feoc-uk.com/

**[Mike](#819 "2013-06-01 01:00:42"):** Hello, I was thinking of doing this exact thing in my focus ST. Just a quick question, where abouts did you route the phono cable to the back of the unit? and is it an easy task or fiddly as anything? Cheers

**[admin](#824 "2013-06-01 08:58:38"):** Well, very easily actually. At the back of the centre console are two holding bolts which I removed and it allowed me to lift the plastic console enough to route the cables underneath and down the side. With the radio out it is also easy to route the cables down the passenger side and then follow under the console. Hope this helps.

**[Phil](#866 "2013-06-03 21:16:57"):** Have you seen these? http://www.skpang.co.uk/catalog/pican-canbus-board-for-raspberry-pi-p-1196.html Haven't done anything serious with the idea yet, but this looks like a possible way to control a pi-based carputer from the steering wheel buttons. Needs quite a bit of reverse engineering to figure out all the codes for the Ford MS-CAN bus but could deliver some pretty impressive integration with other vehicle systems... Interested if anyone else is looking at this for recent Fords?? Brgds Phil

**[admin](#867 "2013-06-03 22:03:26"):** Yes thanks for that. Pretty interesting.

**[admin](#1136 "2013-06-18 21:53:21"):** No I can not use the radio's touch screen as there is no input to connect to the pi and besides I probably would not find a driver for this screen. I am working on getting a touch screen working with the pi for another project. Watch this space..

**[KJW](#1066 "2013-06-14 03:22:48"):** This is pretty cool. Can you operate the pi via the touch screen or do you need to use the keyboard/mouse? kjw

**[jeremy](#1063 "2013-06-14 01:59:01"):** I'll second the battery thing, but add in that you are using an O.S. that comes with one of the easiest programming languages to write. all you nee to do is write in a 'if power drops below X% run shutdown' obviously that's much more than a paraphrase but you get the general idea, that way you can have everything run even with keys off without worry of battery cutting out. I'm liking what the android guys are working on, and as you know if you don't like it simply pop out the drive, douse in gasoline, and see how far down if we'll burn.

**[In Car DVD Sat Nav Player](#2269 "2013-10-31 15:11:40"):** Very informative, I'm sure this could be achieved with other aftermarket stereos than xtrons. Nice work

**[Bill The Geek](#3238 "2014-05-14 04:43:25"):** I have just discovered this in my Raspberry Pi project meaqnderings. I am looking at setting up a carputer using the Pi. I was wondering if you had made any progress with the touch screen thing you mentioned above?

**[admin](#3239 "2014-05-14 09:55:48"):** Unfortunately my uni degree has left me with little time so I have not progressed in this. I have heard the Raspberry Pi foundation are looking at releasing a touch screen especially for the Pi so I might look into this in the future.

