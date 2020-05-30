## New technologies used in this project
#### curently only Firefox browser supports all of them

### clamp()
##### The clamp() CSS function clamps a value between an upper and lower bound. clamp() enables selecting a middle value within a range of values between a defined minimum and maximum. It takes three parameters: a minimum value, a preferred value, and a maximum allowed value.
##### The clamp() function takes three comma separated expressions as its parameter, in the order of minimum value, preferred value, maximum value.
##### clamp(MIN, VAL, MAX) is resolved as max(MIN, min(VAL, MAX))
##### font-size: clamp(1rem, 10vw, 2rem); 
##### Note that using clamp() for font sizes, allows you to set a font-size that grows with the size of the viewport, but doesn't go below a minimum font-size or above a maximum font-size.