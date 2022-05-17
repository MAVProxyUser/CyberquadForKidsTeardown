# Cyberquad For Kids Teardown
Tesla (Radio Flyer) Cyberquad For Kids Teardown notes.<br>

![Family](https://github.com/MAVProxyUser/CyberquadForKidsTeardown/blob/main/adpics/Family.jpg)

* [Marketing](#marketing)
   * [Radio Flyer Tesla Cyberquad for Kids](#radio-flyer-tesla-cyberquad-for-kids)
   * [Tesla Store](#tesla-store)
   * [Chief Designer Franz von Holzhausen Twitter account](#chief-designer-franz-von-holzhausen-twitter-account)
   * [Fan articles](#fan-articles)
* [Accessories seen in Marketing video](#accessories-seen-in-marketing-video)
   * [Cyberquad Bomber Jacket](#cyberquad-bomber-jacket)
   * [Fox Racing 2020 Youth V1 Matte Black Helmet](#fox-racing-2020-youth-v1-matte-black-helmet)
* [Official Repair](#official-repair)
   * [Radio Flyer Part Numbers](#radio-flyer-part-numbers)
* [Un-official Repair](#un-official-repair)
   * [Equivalent Parts](#equivalent-parts)
* [Wiring Diagram](#wiring-diagram)
   * [vehicle rear](#vehicle-rear)
   * [vehicle front](#vehicle-front)
* [PCB Photos](#pcb-photos)
* [Modifications](#modifications)

# Marketing
## Radio Flyer Tesla Cyberquad for Kids
https://www.radioflyer.com/cyberquad<br>
https://www.youtube.com/watch?v=Lg_0Rr02AH8<br>

## Tesla Store
https://shop.tesla.com/product/cyberquad-for-kids?sku=1714748-00-A<br>

## Chief Designer Franz von Holzhausen Twitter account
https://twitter.com/woodhaus2/status/1466273823011917825<br>
https://www.youtube.com/watch?v=vllfW3kTsGg<br>

## Fan articles
https://teslanorth.com/2021/12/01/tesla-launches-cyberquad-for-kids-for-1900-usd/<br>
https://teslanorth.com/2021/12/03/tesla-shows-off-cyberquad-next-to-its-cyberquad-for-kids/

# Accessories seen in Marketing video
## Cyberquad Bomber Jacket
https://shop.tesla.com/product/kids-cyberquad-bomber-jacket<br>
## Fox Racing 2020 Youth V1 Matte Black Helmet
https://www.foxracing.com/product/youth-v1-matte-black-helmet/27735.html<br>

# Official Repair
## Radio Flyer Part Numbers
310258 Battery: $364.43<br>
310241 Motor: $140.17 (Zhejiang Unite Motor Co., LTD - Electrical Vehicle Motor MY1016Z3 36VDC 500W)<br>

# Un-official Repair
## Equivalent Parts
Motor:<br>
Razor part number W25143060030(?) <br>
https://www.walmart.com/ip/Razor-W25143060030-Dirt-Quad-Electric-Motor-W-Screws-Genuine-Part/985193081<br>
https://razor.scooterc.com/w25143060030-dirt-quad-motor-with-screws-350w.html<br>

# Wiring Diagram
## vehicle rear
2 - wire         black, red -> black, red (14awg power in from battery)<br>
2 - wire                    -> black, red (14awg power out to motor)<br>

3 - wire         red, white, black -> red, white, black (tail light)<br>
2 - wire         white, black -> black, black (motor signal)<br> 
2 - wire         red, black -> red, black ( power switch)<br>
2 - wire         red, blue -> red, blue (speed mode 1 or II)<br>

## vehicle front
2 - wire         yellow, red -> yellow, red (fwd, reverse - relay control, not mandatory, default fwd)<br>
2 - wire         yellow, black -> yellow, black (front light)<br>
3 - wire         black, red, blue -> black, red, blue (brake - mandatory)<br>
3 - wire         green, red, blue -> green, red, blue (throttle)<br>

# PCB Photos

You've first got to remove the seat.<br>
![SeatAccessScrews.jpg](https://github.com/MAVProxyUser/CyberquadForKidsTeardown/blob/main/teardown/SeatAccessScrews.jpg)<br>
![SeatRemoved.jpg](https://github.com/MAVProxyUser/CyberquadForKidsTeardown/blob/main/teardown/SeatRemoved.jpg)<br>
![UnderSeatView.jpg](https://github.com/MAVProxyUser/CyberquadForKidsTeardown/blob/main/teardown/UnderSeatView.jpg)<br>

Following the wires is easy in most cases.<br>
![MotorWires.jpg](https://github.com/MAVProxyUser/CyberquadForKidsTeardown/blob/main/teardown/MotorWires.jpg)<br>

4 screws to remove the PCB, 4 more to open it.<br>
![PCBRemovalScrewsX4.jpg](https://github.com/MAVProxyUser/CyberquadForKidsTeardown/blob/main/teardown/PCBRemovalScrewsX4.jpg)<br>
![PCBRemoved.jpg](https://github.com/MAVProxyUser/CyberquadForKidsTeardown/blob/main/teardown/PCBRemoved.jpg)<br>
![PCBEntryTorx10.jpg](https://github.com/MAVProxyUser/CyberquadForKidsTeardown/blob/main/teardown/PCBEntryTorx10.jpg)<br>

WARNING: Geting in is hard! You have to pry until the silicon seals break. They are very tight! Stick with it, they will pop eventually.<br>

First thing you see is a debug header of some sort.<br>
![PCBOpened.jpg](https://github.com/MAVProxyUser/CyberquadForKidsTeardown/blob/main/teardown/PCBOpened.jpg)<br>
![DebugHeaderTopView.jpg](https://github.com/MAVProxyUser/CyberquadForKidsTeardown/blob/main/teardown/DebugHeaderTopView.jpg)<br>
![PCBRelays.jpg](https://github.com/MAVProxyUser/CyberquadForKidsTeardown/blob/main/teardown/PCBRelays.jpg)<br>

A few more screws hold the PCB to the bottom of it's case.<br>
![DebugHeaderBottomView.jpg](https://github.com/MAVProxyUser/CyberquadForKidsTeardown/blob/main/teardown/DebugHeaderBottomView.jpg)<br>
![PCBBottomView.jpg](https://github.com/MAVProxyUser/CyberquadForKidsTeardown/blob/main/teardown/PCBBottomView.jpg)<br>
![PCBBottomViewStraight.jpg](https://github.com/MAVProxyUser/CyberquadForKidsTeardown/blob/main/teardown/PCBBottomViewStraight.jpg)<br>

# Modifications

[![The World's FASTEST TESLA Cyberquad!](http://img.youtube.com/vi/Y5s0i21SOnI/0.jpg)](https://www.youtube.com/watch?v=Y5s0i21SOnI)<br>
Upgraded battery 72 volt, 63 amp hour<br>
[Vevor](https://www.vevor.com/brushless-dc-motor-c_11227/72v-3000w-bldc-motor-kit-with-brushless-controller-electric-bicycle-scooter-p_010187167720) 3000 watt 72 volt controller & motor<br>
[Zoom HB875](https://www.ebay.com/itm/224975123928) hydraulic disc brake "from ebay"<br>
["Burner" RCP 2](https://www.aliexpress.com/item/2251832547229897.html), Rear shock from [DNM](https://www.dnmshock.com/products.php?func=p_detail&p_id=22&pc_parent=12)<br>
