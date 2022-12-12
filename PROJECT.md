 ---
title: "TkkrLab wham-gun: A terrible invention for sure"
date: 2022-12-12
thumbnail: "https://raw.githubusercontent.com/TkkrLab/Wham-Gun/master/images/wham1.jpg"
---

# Index
- [Index](#index)
- [Introduction](#introduction)
- [So what did i made](#so-what-did-i-made)
- [Presenting the Wham Gun](#presenting-the-wham-gun)
- [Future improvements](#future-improvements)

# <a name="intro"></a>Introduction

I was given this thing with the idea “I’t would be cool to have a flashlight build into it”, like a Flash gun.
![kit pistol](https://raw.githubusercontent.com/TkkrLab/Wham-Gun/master/images/kitpistal.jpg)

Its a Kit gun wich you can hook up to a compressor.
I had a different plan, as these are the things people tent play with, everytime they see one. Like bbq tongs, you gott test a cip them atleast once.
   
# <a name="MakingOf"></a>So what did i made
I had these [sound recorder module](https://nl.aliexpress.com/item/1005003658927111.html?spm=a2g0o.productlist.0.0.3478248fXX7tzK&algo_pvid=21bb5fcf-3228-4794-ac88-0e74952682be&algo_exp_id=21bb5fcf-3228-4794-ac88-0e74952682be-10&pdp_ext_f=%7B%22sku_id%22%3A%2212000026686214784%22%7D&pdp_npi=2%40dis%21EUR%212.86%212.01%21%21%211.58%21%21%402100bdd516708726743348067ece30%2112000026686214784%21sea&curPageLogUid=U1VgFa8LMkEk) laying around from alie express.

![kit pistol](https://raw.githubusercontent.com/TkkrLab/Wham-Gun/master/images/soundmodule.png)


They are easy to modify, and even come pre-soldered with different component depending on whichever you needed.

The one of my left has a Light sensor, but can be replaced with a button behavior. (bottom left)
![kit pistol](https://raw.githubusercontent.com/TkkrLab/Wham-Gun/master/images/button.png)

So I unscrewed the kit gun, and clued in a piece of a pcb behind the trigger with a push button and attached a wire between the button and the sound recorder.

It was working, but needed some better sound, the speaker wasnt big enough to impress.

![kit pistol](https://raw.githubusercontent.com/TkkrLab/Wham-Gun/master/images/speaker.jpg)
*img for reference only

After taking appart a desktop speaker(trash aswell), replacing the tiny inferior speaker with the superior larger one was easy enough with some soldering. 

This did caused some issues… mainly power. The three internal the batteries had to be replaced with 3 larger aa battery’s. The chip starts playing when powered, which meant it started playing the first note, causing a voltage drop, which killed the chip.
Then the battery’s would return to the usual voltage, and the chip would attempt to start playing again.
Thi is a usefull feature if i ever want it to play when pressed, just have to rewire to power the chip through the button. Now it just plays the full 30 seconds without any way of turning it off. #Features

Ive attached a warning label which says "dont trigger me". although i am faily sure everyone is going to ignore it or do the exact oposite.

# <a name="Wham-gun"></a>Presenting the Wham Gun
![wham2 pistol](https://raw.githubusercontent.com/TkkrLab/Wham-Gun/master/images/wham2.jpg)
[see here on youtube](https://www.youtube.com/watch?v=3B-GtniuGxI)
Duck tape, and a few cauting of paint later in the colours of the north pole pole and.. WHAM.. the Wham gun was created.
This thing you can just lay about the office and people will pick it up, “trigger it” and automatically lose the whamageddon.

There is also no shutting it off and its extremely noisy. Can hear it from a next few rooms over.

# <a name="improvements"></a>Future improvements
A cone might be nice  to increase gun – aim functionality. But for now I like it as is.

I could pray paint it in different colours and record different melody’s. Like rick roll, or phaser blast after december.

When going for the phase blast id suggest not attaching the button to the sensor area, but instead break the power. (the module plays when its powered). This way you can cut of phaser blasts and actually piew piew with it.

Maybe 3d print a holder for the speaker, the duck tape is very ghetto.

![wham3 pistol](https://raw.githubusercontent.com/TkkrLab/Wham-Gun/master/images/wham3.jpg)
