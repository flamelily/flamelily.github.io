---
layout: blog-page
category: Raspberry Pi
tags: car computer,carputer,raspberry pi,knight rider
permalink: /:year/:month/:title/
title: Raspberry Pi car computer
description: |
excerpt_separator: <!--more-->
---

I have always loved those old TV series with futuristic tech in those futuristic vehicles, like Knight Rider, Air Wolf, Street Hawk etc. So it got me thinking about how easy it would be to add a computer to a vehicle. Now I know its been done before and a quick Google search shows multiple websites and companies making very complex car and other vehicle computers, but at a large cost. <!--more--><br><img class="img-responsive center-block" src="/wp-content/uploads/2013/05/2013-05-01-18.52.37-1024x768.jpg" alt="raspbian running"><center><em>Raspberryi Pi in my Ford Focus running raspbian "wheezy"</em></center>

Well I thought my Raspberry Pi is the perfect device for this. 

  * Its cheap
  * its very small
  * small power requirements (runs off a micro USB car charger)
  * flexible video and audio outputs (HDMI and Composite RCA for video, HDMI and 3.5mm audio jack for audio)
  * and best of all you can change operating systems by simply switching out SD cards
Below is a photo of the Raspberry Pi running the excellent media centre type operating system [Raspbmc](http://www.raspbmc.com/) which is perfect for browsing and playing your media collection using a media centre remote or something similar, as shown in my 'shopping list' below.

<br><img class="img-responsive center-block" src="/wp-content/uploads/2013/05/2013-05-02-18.05.22-768x1024.jpg" alt="raspbmc"><center><em>Raspbmc running on a Raspberry Pi in the Car</em></center>

### What I did

Well firstly I had the Xtron car DVD player for the Ford already fitted and it can be found on this site here <http://www.xtrons.co.uk/> and there are DVD/Radio players for a number of car manufacturers. However you don't actually need one of these if you can place a TFT screen elsewhere. I also have one of these.. 
<br><img class="img-responsive center-block" src="/wp-content/uploads/2013/05/2013-05-02-11.21.04-300x225.jpg" alt="7inch TFT monitor"><center><em>7″ TFT monitor which can be used for the back seats</em></center>

Which can be found on Ebay for about £23 at this link. <http://stores.ebay.co.uk/SainSpeed> This 7" TFT can be placed in a headrest or on the dash somewhere as it comes with a stand. Both of these devices have a composite RCA video input and for audio I have a basic 3.5mm audio cable from the Raspberry Pi to the auxiliary port of the radio. So all audio is played via the car speakers which sounds really good and clear. I placed the Raspberry Pi in the centre console as shown below and routed all cables under the centre console so no cables are lying around.
<br><img class="img-responsive center-block" src="/wp-content/uploads/2013/05/console1-300x250.jpg" alt="centre console"><center><em>Console of my Ford Focus holding the Raspberry Pi</em></center>
<br><img class="img-responsive center-block" src="/wp-content/uploads/2013/05/console3-225x300.jpg" alt="centre console 2nd"><center><em>Centre Console Raspberry Pi with power from USB charger</em></center>

I used the brilliant little Xenta Wireless Keyboard with mouse touchpad built-in. This works perfectly with both Raspbian and Raspbmc. It even has an on/off button on the back to save batteries when not in use (it takes 2xAA batteries).
<br><img class="img-responsive center-block" src="/wp-content/uploads/2013/05/console2-209x300.jpg" alt="centre console 3rd"><center><em>Raspberry Pi and mini keyboard</em></center>

So this can now connect to any wireless network and I connect it to my mobile phone by using the portable wi-fi hotspot, giving my Raspberry Pi an internet connection even on the move (obviously don't try browse the internet or watch videos whilst driving). Materials Used : 

  1. Raspberry Pi (Obviously)
  2. Xtrons Car DVD player
  3. 7" TFT monitor (for back seats or main monitor)
  4. Extra composite video cable and 3.5mm audio cable
  5. Wireless N USB dongle from [Amazon](http://www.amazon.co.uk/gp/product/B008FZO1A2/ref=as_li_tf_tl?ie=UTF8&camp=1634&creative=6738&creativeASIN=B008FZO1A2&linkCode=as2&tag=flait-21)
  6. Xenta Wireless Mini Keyboard from [Ebuyer](http://www.ebuyer.com/250233-xenta-wireless-mini-keyboard-with-touchpad-and-multimedia-keys-usb-pkb-1720)(now out of stock) Try [this one](http://www.amazon.co.uk/gp/product/B004GAGM1Q/ref=as_li_tf_tl?ie=UTF8&camp=1634&creative=6738&creativeASIN=B004GAGM1Q&linkCode=as2&tag=flait-21) instead
  7. Micro USB car charger
Update pictures of headrest in next blogpost [here ](/2013/05/raspberry-pi-car-computer-update/)