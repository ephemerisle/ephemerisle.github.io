---
layout: default
title: Subshine
---

Subshine: Underwater programmable illumination system
-----------------------------------------------------

This is my idea page for the Subshine system.

Who is me?

Clive

What is subshine?

A collection of multicolored lights floating a few feet below the
surface of the water. They can be arranged any way, but probably a grid,
and they can be addressed via a control box, midi, beat detector, ipad,
etc.

At night, it will make the water around the flotilla glow any color.

Technical details
-----------------

Subshine will be composed of modules Each module will have between 3-4
high brightness LEDs. Either 10 watt each or 100 watt each. Red Blue
Green or Red Blue Green White, or possibly RGB UV.

10 watt:

<http://www.youtube.com/watch?v=BkUGNtYKasU>

100 watt: <http://www.youtube.com/user/LedFoxShop#p/a/u/1/jCf0rgkqOQA>

Another option:

<http://www.amazon.com/MOTORCYCLE-BRIGHT-ACCENT-FLEXIBLE-Aquarium/dp/B002SG9J6K/ref=sr_1_15?ie=UTF8&qid=1308789640&sr=8-15>

They're cheap and already waterproof. It would greatly simplify the
project. But the controls would have to be above water. -- Adam

Each module will be sealed to to IP68 standards, good for continuous
immersion. Each module will contain the LED devices themselves, driver
electronics and control electronics. The housings will be made out of
Aluminum with small heat dissipation fins. They will look pretty retro.

- I'd like to note that things don't really store or dissipate heat the
same when they're immersed in water. -Christie

Modules will be balanced to be just slightly over neutrally buoyant.

- I'm assuming you're planning on having some sort of fixed rail to keep
them all at a relatively fixed depth, and not rise to the surface? --
Christie

Control.. not sure how to handle this yet. BlinkMs are pretty close to
what we need: <http://thingm.com/products/blinkm>

so I might just copy the design (I know the guy, he is one of the
founders of CrashSpace)

What we used to control lights on
[Syzygryd](http://www.youtube.com/watch?v=PZV7xeeXpqQ) involved a [DMX
controller](http://www.celestialaudio.com/dmx_led/index.html), which can
easily be sequenced if you have the hardware to work with it. --
Christie

Hell, might be cheap enough to give each guy an IP address.

Can you get an arduino shield for that? -- Christie

What I can do
-------------

Overall systems design

Manufacturing

Electronics design

basic layout

simple control code

What I need help with
---------------------

PCB layout

Higher level control software, IE ipad etc.

Deep embedded programming

Potential Problems
------------------

-Cost. LEDS cost money. IP68 connectors cost money

-Power: These things are going to suck a LOT of power.

Let's say we have 100 100 watt LEDS If they are all firing at once, we
can easily draw 300 amps.

300 amps.

How much are marine batteries rated for?

they can drop 1000 amps out but.. they are rated for like 68 AH

Meaning one battery would die in 15 minutes. And for hundred watts, we
need 36v so.. that would be three in series

Now, if we use 10 watt LEDS, we can run it for 45 minutes off of one
battery So for 10 watt LEDS, a battery farm of about a dozen or so 12v
should do us.

Now, to charge it.. Crashspace can lend us some solar but they only put
out 500 watts or something.. so much to think about

- An interesting thought about using solar for lighting... you never
have it when you need it. Solar during the day and lights at night...
you'll need a pile of batteries. Count joules (\~amp-hours) not watts.
-- Christie

- Collisions, tangled lines

If anything is going to be floating just under the surface, there is a
real potential for problems with collisions with other craft, and with
them getting tangled in various lines. Matt's floating reeds from this
year were quickly destroyed because of these issues. -- Adam
