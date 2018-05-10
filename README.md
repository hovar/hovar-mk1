<a href="https://www.youtube.com/embed/zWix-1nG0uk"><img src="images/hovar_hero.png" title="Check out our demo reel on YouTube!"></a>
# HovAR MK1
Hardware designs for first-generation HovAR image-projecting AR drone. **NOTE: This page is currently a WIP, and contains incomplete information. *Please star this repo*, and check back in a few days.**

## PARTS
Here's what you'll need to build your own HovAR MK1.
### CAD files
All of the CAD files can be found in the [/CAD](CAD) directory. Workable versions of the parts are in the [/step](CAD/step) sub-directory, and .stl files are in the [/stl](CAD/stl) sub-directory. All .stl files are in mm, and should play nice with most CAM software and slicers. *Warning: The .stp files may use different units, so be cautious if you're trying to edit a part. We'll try to fix this in an upcoming rebuild.*
### Original BOM
Here's what we used to build the MK1.
- 1 x [M3x20 Screws & Locknuts Pack](https://store.flitetest.com/m3-x-20mm-stainless-screw-pack/)
- 1 x [KK2 Flight Control Board](https://hobbyking.com/en_us/hobbyking-kk2-0-multi-rotor-lcd-flight-control-board.html)
- 1 x [4s Turnigy 3000mAh LiPo Battery](https://hobbyking.com/en_us/turnigy-battery-3000mah-4s-20c-lipo-pack-xt-60.html)
- 1 x [Mini Projector](https://www.amazon.com/gp/product/B075N25DS7/ref=oh_aui_detailpage_o03_s00?ie=UTF8&psc=1)
- 1 x [Raspberry Pi 3 B](https://www.amazon.com/Raspberry-Pi-RASPBERRYPI3-MODB-1GB-Model-Motherboard/dp/B01CD5VC92/ref=sr_1_3?s=electronics&ie=UTF8&qid=1523895859&sr=1-3&keywords=raspberry+pi+3);
- 1 x [micro-SD Card](https://www.amazon.com/16GB-Sandisk-microSD-Memory-Adapter/dp/B00FZVQPBC/ref=sr_1_6?s=pc&ie=UTF8&qid=1523895964&sr=1-6&keywords=sd+card&refinements=p_n_feature_two_browse-bin%3A6518303011) (We used a 16GB card)
- 1 x [HDMI to Mini-HDMI Cable](https://www.amazon.com/dp/B014I8UAPE/ref=twister_B0199TGZFQ?_encoding=UTF8&psc=1) (to connect the Pi to the Projector)
- 1 x [Battery Strap](https://hobbyking.com/en_us/scorpion-lipoly-lock-strap-205mm-small-x-3.html)
- 1 x [Power Breakout Cable](https://hobbyking.com/en_us/hxt-4mm-to-4-x-3-5mm-bullet-multistar-esc-power-breakout-cable.html)
- 1 x [External Battery w/ Cable](https://www.amazon.com/dp/B01CU1EC6Y/) (Although we used this to power the Pi in our original design, `we'd recommend using a power distribution board and running everything off of the main LiPo battery` instead to simplify to a central power source. See the optional parts section for recommendations.)
- 1 x [4-Piece Propeller Set](https://hobbyking.com/en_us/hobbykingtm-slowfly-propeller-9x4-7-black-ccw-4pcs.html)
- 1 x [Digital Servo](https://hobbyking.com/en_us/bms-385dmax-digital-servo-metal-gear-4-2kg-15sec-16-5g.html)
- 3 x [DT750 Brushless Motors](https://hobbyking.com/en_us/hextronik-dt750-brushless-outrunner-750kv.html)
- 3 x [F20A Motor Controllers](https://hobbyking.com/en_us/hobby-king-20a-esc-3a-ubec.html)
### Optional Parts
Since the original build, we've made some optional adjustments to the designs to experiment and address issues we've found. The following are optional parts that should still fit well into the MK1 build. We'll list the differences between the substitute part and the original. *Note: These parts are merely recommendations, and may not have been tested on an actual build*

## BUILD
Put things together
*Some engineering and stuff*
You made a cool drone!
## PROGRAMMING
Whoo! You've completed your HovAR drone! Head on over to our code repository to get the latest libraries and learn how to start working with the drone and start programming applications.
