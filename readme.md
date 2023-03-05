
# What is this?

This is a simple passive device to allow you to turn off the devices connected to a switched outlet in your home from the general vicinity of the outlet, whilst also allowing you to remotely turn them back on.

# Why?

The motivation for this project is simple: I hate getting out of my bed and walking across the room to turn the lights off after I'm done reading at night. Similarly, I find it very frustrating that I need to remember to turn the switches of my lights back on to have them work at the light switch again.

# Okay, so why not just install smart bulbs/switches/outlets?

While that is certainly another solution to this problem, this solution has the following benefits compared to those solutions:

- Works with any load. Depending on relay, could be made to support the full 1500w of a standard 15a circuit. This could also be used for fans, for example.
- No electrician required! It is completely plug and play. Ideal for places like apartments where modifying the wiring is not feasible.
- Doesn't require a smartphone/Wi-Fi to operate.
- When it's not latched, it is completely passive. When it is latched, it's just like unplugging the device at the outlet.
- No phantom power draw when it's not latched. This is dependent on the relay used, and could be significantly reduced with solid state switching, if so desired.
- This entire project costs about $15 per unit to produce at extremely low volumes. Entry level smart switches start at $20.


# Alright, I can see the appeal. How does this thing work?

Great! Here's how it works:

    1. Plug the device in between the switched outlet and your load. (typically lights)
    2. Turn on the lights from the switched outlet like normal.
    3. Get cozy in bed with your favorite book.
    4. Once it's time for bed, simply press the switch on the device. The lights will turn off.
    5. In order to turn the lights back on in the morning, simply toggle the light switch off and on and the lights will work normally again.

# What if I turn the lights off too early and need to turn them back on?

Don't do that. However, if this is typically a problem for you, it would be fairly simple to add another switch to un-latch the relay.