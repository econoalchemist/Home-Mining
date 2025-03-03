# Electrical
Any serious Bitcoin mining equipment will require 240v AC electricity. So make sure you understand the specifications of the equipment you're buying and ensure that your home can handle the load. My home definitely was not capable of handling the load. The Whatsminer that I bought is rated for 3,600 Watts which calls for 15 amps at 240 volts. Hopefully your home is already capable of handling this kind of load. If not, take into careful consideration the rating of your main circuit breaker, the rating of the circuit breaker on your miner's specific circuit, the wire gauge on that circuit, the rating of the outlet socket, the rating of the connecting cable plug, the wire gauge of the connecting cable, and the rating of the connector plugging into your miner. If there are any weak links in that chain you may find out the hard way, which could result in damage to your ASIC or an electrical fire. It is better to ensure the entire circuit is over-rated. 

Consider contacting your electrical utility provider to inquire about alternate meter rates. Upon request, many providers will give you a meter that charges less during off-peak hours to incentivize you to use your high consumption accessories during times of low grid demand. Each provider is different and has different rates but for example, the programs often look something like: $0.11/kWh from 14:00 - 18:00, $0.05/kWh 18:01 - 13:59. This could potentially help you reduce the average cost. Based on this example the reduced rate would lower the daily operating cost at 3,500 Watts and $0.12/kWh for 24 hours from $10.08 to $5.04

![](assets/IMG_4896.JPG)

This is a picture of the original electrical panel on the back of my house. I mean original like installed in the 1960's when the house was built. Aside from wanting to mine Bitcoin, my wife and I knew that we would need to upgrade this panel when we bought this house less than a year ago. We had actually taken some money left over from the home purchase, put it into bitcoin with the intention of selling it later specifically for these electrical upgrades. We wanted to update this panel and run a sub panel to the garage so my wife could create her art work and so that I could get a nice welder and some other tools. When we had the electrician bidding the job I asked how much extra it would be to run an additional 240v line to the basement to provide a single outlet 30 amp service. It was going to cost an extra $200 so we decided to include that addition to our project specifically for the mining equipment. 

If you already have 240v available in your home, then you are ahead of the game. If you don't, you will need it and hiring a professional electrician to do the job may not be as expensive as you think. Or if you are a DIY'er, it may not be as difficult as you think, as you will soon see. If you do hire an electrician just know that scammers are not unique to the cryptocurrency space, scammers are everywhere so try to use the same kinds of precautions and street-smarts in dealing with people in real life as you would when dealing with people online. If any of the content in these images of the electrical panels looks foreign to you or it doesn't make sense, then do not attempt this at home, you will die, call a professional. Just make sure they are not a scammer.

This is how my hired electrician left my panel for me. Now, you may not be an electrician, neither am I, but I know enough to tell when something isn't right. Actually, I've worked with heavy equipment like hi-voltage diesel generators for longer than I'd like to admit so house wiring is pretty straight forward to me, I just don't have the certifications to call myself an electrician. In any case, everything in these pictures is wrong.

![](assets/IMG_4947.JPG)
![](assets/IMG_4942.JPG)
![](assets/IMG_4941.JPG)

Here is what I found behind the meter, which explains why my lights would flicker and fade when running the washing machine and other appliances:

![](assets/IMG_5062.JPG)

Your eyes do not deceive you, that is indeed a main neutral wire left disconnected by the hired electrician. When a house doesn't have a neutral, the accessories that run on 120v start causing an imbalance in the electrical system. This will typically result in dimming or flashing lights when running other appliances. But with enough imbalance this can cause damage to appliances, electrical fires, or worse. All the work that had been done on my electrical system needed to be re-done and it was left in a hazardous condition. Needless to say, things were not going very well between the electrician and I, so I decided to re-do and finish the work myself. The danger my family was put in and the top-dollar I was paying for amateur results was beyond unacceptable no matter the circumstances. 

![](assets/IMG_5064.JPG)

Here is the panel after I was finished with it, I'm not an electrician but it is better than before and safe. With the main panel properly put back together, I was able to safely run the new 240v line down to the basement room for the outlet.

![](assets/outlet.jpg)

I used a 30 amp circuit breaker to feed the circuit for the miner. This circuit was ran with 8 gauge wire from the main panel to the outlet. The outlet was terminated with a Nema 6-20L socket.

The miner is equipped with an IEC C19 plug, this means that it would be necessary to make a cable with a Nema 6-20L plug on one end and an IEC C19 socket on the other end. Finding a cable with thick enough wire gauge as to not create an electrical bottle-neck in this configuration was difficult. So I made my own cable with 3 conductor 14 AWG wire rated to 90°C, which should be able to handle enough amperage according to the chart below. [This](https://www.amazon.com/Interpower-83011380-Rewireable-Connector-Socket/dp/B00917YQOO/ref=sr_1_9) rewireable C-19 plug works great on the Whatsminers.

![](assets/Amp-Code.png)

<p align="center">
<img width="330" src="assets/IMG_5227.JPG">
<img width="330" src="assets/IMG_5228.JPG">
<img width="330" src="assets/IMG_5226.JPG">
</p>

![](assets/plug.png)
![](assets/IMG_5259.JPG)

With the connecting cable made, I was ready to fire up the miner for the first time. But before plugging your ASIC, there are a few things you should looks for. Your ASIC will have had a long journey to get to you, during this journey it was probably rattled, shaken, and jolted quit a bit in transit. This means that things may have come loose or shifted. So you want to check and make sure the grills on the fans are not bent. Make sure the bus bars on the power supply are not touching. Shake the whole machine and listen for any rattles or loose sounding components. Remove the fans and look down the tube to make sure it looks clear. Check that the circuit boards and other harness connections are secured and oriented the right way. It may seem kind of weird to dissassemble a brand new machine that you just spent a lot of money on and waited a long time for. But if you find even one thing wrong, then you will be thanking yourself for taking the time to check. These machines are not complicated so fear not.

<p align="center">
<img width="330" src="assets/IMG_5103.JPG">
<img width="330" src="assets/IMG_5104.JPG">
<img width="330" src="assets/IMG_5102.JPG">
</p>

Here is a video of firing my machine up for the first time:
[![Initial Startup Video](/assets/Initial-Startup-Thumbnail.png)](https://bitcointv.com/w/31WJaHYMFuCTYzoJEP9EWS "Initial Startup Video")

The first thing I noticed is that this miner runs hot and loud. This thing can produce 148°F at the output fan and screaming up to 100 dB. Immediately I knew that I was going to have to do something to address the noise and the heat. After about an hour in my room with the ASIC running I had gone deaf and the ambient temperature in the room was ~80°F.

<p align="center">
<img width="330" src="assets/IMG_5115.JPG">
<img width="330" src="assets/IMG_5113.JPG">
</p>

I hope this section made you aware of what goes into this type of electrical infrastructure. If your home is equipped with the properly rated circuit to handle running an ASIC then you are ahead of the game. If you need to make electrical upgrades, consult a licensed professional. But don't let that stop you from reaching your goals.
