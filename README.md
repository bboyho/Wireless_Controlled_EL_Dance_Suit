Wireless Controlled EL Dance Suits
-------------------

This code will be used to wirelessly control 2x 3 meters of EL Wire attached to a dancer's hoodie and pants
for a performance with Streetside Studio's bboys/bgirls. In less than 3 months with my usual day job, teaching, and training. 42 meters (~1,653.5 inches) of manual hand sewing white EL wire to hoodies and pants, custom connectors, soldering, a little coding with Arduino, 8x XBees configured as point-to-multipoint network, 7x enclosures attached to everyone's hip, straps, a wireless glove, choreographing, and editing parts of a track together.

<table class="table table-hover table-striped table-bordered">
  <tr align="center">
    <td><a href="https://www.instagram.com/p/BUD_RaelsrU/"><img src="https://scontent-dfw5-1.cdninstagram.com/vp/cde7f502083572fb79a0f58e41017548/5AF32FBC/t51.2885-15/e15/18443739_1350679458342870_2834682031722463232_n.jpg" title="Bboys w/ Wireless EL Dance Suit"></a></td>
  </tr>
  <tr align="center">
    <td><a href="https://www.instagram.com/p/BUD_RaelsrU/">Instagram: bobbybrownrice Demo Video</a></td>
  </tr>
</table>

<table class="table table-hover table-striped table-bordered">
  <tr align="center">
    <td><a href="https://www.instagram.com/p/BUDzBpvFZDb/"><img src="https://scontent-dfw5-1.cdninstagram.com/vp/28a5f4f04c873f485a024326433abdaa/5B7F5139/t51.2885-15/e35/18382519_315574212206941_7170378167582982144_n.jpg" title="Enclosure"></a></td>
   <td><a href="https://www.instagram.com/p/BUDzvJ5Fu8r/"><img src="https://scontent-dfw5-1.cdninstagram.com/vp/e1496e55b091dd51ccbbd3539f6e24a3/5B83A2D9/t51.2885-15/e35/18512435_305927599828273_8613088069203001344_n.jpg" title="Performance Day" width="75%"></a></td>
  <td><a href="https://www.instagram.com/p/BUiiFTGFC9k/"><img src="https://scontent-dfw5-1.cdninstagram.com/vp/3c4eadc3a45df3cc4a10e5ed6a22a9d6/5B9BDB78/t51.2885-15/e35/18645562_1706667162973094_4302184967066091520_n.jpg" title="Light Painting"></a></td>
  </tr>
  <tr align="center">
    <td><a href="https://www.instagram.com/p/BUDzBpvFZDb/">Instagram: bobbybrownrice Demo Image</a></td>
    <td><a href="https://www.instagram.com/p/BUDzvJ5Fu8r/">Instagram: bobbybrownrice Demo Image</a></td>
    <td><a href="https://www.instagram.com/p/BUiiFTGFC9k/">Instagram: bobbybrownrice Demo Image</a></td>
  </tr>
</table>

Repository Contents
-------------------
**<> Code**
- /[XBee_ELSequencer](https://github.com/bboyho/ELDanceSuit/tree/master/Arduino/EL_XBeeWirelessControl/XBee_ELSequencer)
- /[XBee_ELSequencer_Controller](https://github.com/bboyho/ELDanceSuit/tree/master/Arduino/EL_XBeeWirelessControl/XBee_ELSequencer_Controller)

Documentation
-------------------

* [SparkFun EL Sequencer Hookup Guide](https://learn.sparkfun.com/tutorials/el-sequencerescudo-dos-hookup-guide)
* [GitHub Repository for EL Sequencer](https://github.com/sparkfun/EL_Sequencer/tree/master)
* Instagram: bobbybrownrice
  * [Test 1 - Wireless Test](https://www.instagram.com/p/BT502rzF0ND/)
  * [Test 2 - Wireless Test in the Dark](https://www.instagram.com/p/BT51mbBFOCs/)
  * [Test 3 - Wireless Glove Test ](https://www.instagram.com/p/BT-tP7RFKn8/)
  * [Test 4 - Wireless Glove Test Prammed to the Beat](https://www.instagram.com/p/BUDyLCmlEUp/)
  * [Enclosure](https://www.instagram.com/p/BUDzBpvFZDb/)
  * [Performance Day](https://www.instagram.com/p/BUDzvJ5Fu8r/)
  * [Light Painting](https://www.instagram.com/p/BUiiFTGFC9k/)
  * [Demo Video](https://www.instagram.com/p/BUD_RaelsrU/)

XBee Series 1, Pro:  Point to Multipoint Configuration
-------------------

[Digi Tutorial: XBee 802.15.4 (i.e. Wireless Serial)](http://examples.digi.com/get-started/basic-xbee-802-15-4-chat/ )

* Master XBee
  * CH = C
  * ID = 3333
  * DH = 0
  * DL = FFFF (2)
  * MY = 1

* Slave XBee
  * CH = C
  * ID = 3333
  * DH = 0
  * DL = 1 <- point to Master "MY"
  * MY = 2 <- Slave "MY", make it unique in the network.

License Information
-------------------

This project is _**open source**_! 

Please review the [LICENSE.md file](https://github.com/bboyho/ELSuit/blob/master/LICENSE.md) for license information. 

Distributed as-is; no warranty is given.
