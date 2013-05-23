Here is version 1.5 with roll/pitch camera stabilization.

Roll servo goes to output 7 and pitch servo to output 8.

Turn it on by going to "Cam Stab Settings" screen and set the gains to a non-zero value. Start with 500. A negative value reverses servo direction. Adjust value until camera is steady.

Use the offset values to trim servo position, but keep the values close to 50% by adjusting servo linkage first.

Now I have to say that I have not tested this with an actual camera, but it should work.

This version will reset all settings to default due to changes in EEPROM usage.