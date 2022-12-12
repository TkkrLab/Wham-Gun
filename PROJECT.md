 ---
title: "TkkrLab wham-gun: A terrible invention for sure"
date: 2022-12-12
thumbnail: "https://raw.githubusercontent.com/TkkrLab/Wham-Gun/master/images/wham1.jpg"
---

# Index
- [Index](#index)
- [Introduction](#introduction)
- [So what did i make](#so-what-did-i-make)
- [Presenting the Wham Gun](#presenting-the-wham-gun)
- [Future improvements](#future-improvements)

# <a name="intro"></a>Introduction

I was given this thing with the idea “I’t would be cool to have a flashlight build into it”, like a Flash gun.
![kit pistol](https://raw.githubusercontent.com/TkkrLab/Wham-Gun/master/images/kitpistal.jpg)

Its a Kit gun wich you can hook up to a compressor.
I had a different plan, as these are the things people tent play with, everytime they see one. Like bbq tongs, you gott test a cip them atleast once.
   
# <a name="So what did i make"></a>So what did i make
I had these [sound recorder modules](https://nl.aliexpress.com/item/1005003658927111.html?spm=a2g0o.productlist.0.0.3478248fXX7tzK&algo_pvid=21bb5fcf-3228-4794-ac88-0e74952682be&algo_exp_id=21bb5fcf-3228-4794-ac88-0e74952682be-10&pdp_ext_f=%7B%22sku_id%22%3A%2212000026686214784%22%7D&pdp_npi=2%40dis%21EUR%212.86%212.01%21%21%211.58%21%21%402100bdd516708726743348067ece30%2112000026686214784%21sea&curPageLogUid=U1VgFa8LMkEk) laying around from Alie Express.

![kit pistol](https://raw.githubusercontent.com/TkkrLab/Wham-Gun/master/images/soundmodule.png)


These modules are easy to modify, and even come pre-soldered with different components depending on whichever you needed.

The one i used had a light sensor, but the light sensor was replaced with a button. (bottom left)
![kit pistol](https://raw.githubusercontent.com/TkkrLab/Wham-Gun/master/images/button.png)

So I unscrewed the kit gun, and glued in a piece of prototyping board behind the trigger with a push button and attached a wire between the button and the sound recorder.

This yielded a working device however the speaker wasnt big enough to impress.

![kit pistol](https://raw.githubusercontent.com/TkkrLab/Wham-Gun/master/images/speaker.jpg)
*img for reference only

After disasembling a old desktop speaker, replacing the tiny inferior speaker with the superior larger one was easy enough with some soldering. 

This did caused some issues… mainly power. The three Lr1130/Ag10 internal the batteries had to be replaced with 3 larger aa battery’s. The chip starts playing when powered, which meant it started playing the first note, causing a voltage drop, which killed the chip.
Then the battery’s would return to the usual voltage, and the chip would attempt to start playing again.
Thi is a usefull feature if i ever want it to play when pressed, just have to rewire to power the chip through the button. Now it just plays the full 30 seconds without any way of turning it off. #Features

Ive attached a warning label which says "dont trigger me". although i am fairly certain everyone is going to ignore it or do the exact oposite.

# <a name="Presenting the Wham Gun"></a>Presenting the Wham Gun
![wham2 pistol](https://raw.githubusercontent.com/TkkrLab/Wham-Gun/master/images/wham2.jpg)
[see here on youtube](https://www.youtube.com/watch?v=3B-GtniuGxI)
{{< youtubenc 3B-GtniuGxI >}}
Ducttape and a few coats of paint later in the colours of a candy cane and.. WHAM.. the Wham gun was created.
The perfect trolling device you can just leave unattented around the office and people will pick it up, “trigger it” and automatically lose the whamageddon.

There is also no shutting it off and its extremely noisy. Can hear it from a next few rooms over.

# <a name="Future improvements"></a>Future improvements
A cone might be nice  to increase gun – aim functionality. But for now I like it as is.

I could pray paint it in different colours and record different songs. Like "never gonna give you up", or use it for sound effects like phaser blasts after december.

When used for the sound effects attaching the button to cutt off the power to the board will cutt off the sound aswell when the trigger is released. (the module plays when its powered). This way you can cut of phaser blasts and actually piew piew with it.

Maybe 3d print a holder for the speaker, the duck tape is very ghetto.

![wham3 pistol](https://raw.githubusercontent.com/TkkrLab/Wham-Gun/master/images/wham3.jpg)
