# in-class-activities
## Devlogs
### W1
When I move the camera out of the Cat Game Object, the camera no longers follows the cat anymore. This is because the camera is no longer connected to cat anymore so it doesn't know what to follow. So, the camera stands still. Itch Link: https://gamerfan1225.itch.io/in-class-activity-complete

### W2
The r, g, b variables are floats instead of intns, bools, or stings is becyase the colors go into the decimals which floats accommodate. Ints won't work because it has to be an exact number which the colors are never are, bools does not apply to the colors, and strings don't apply here either. The _bounce variable variable is an int instead of a float, bool, or stirng because it counts the exact number of times that the ball bounces off the floor. Floats don't apply here because the ball can't bounce 1.5 times, bools uses true and false which doesn't affect the number of times the ball bounces, and string is just text and doesn't add anything the bounces. The reason why the code was broken was because g wasn't a variable so it couldn't be assinged. So by adding g = g + 0.1, g is assinged and is added by 0.1. However, there was another error that was fixed by adding an f after the number which created a float for 0.1. This stopped the error and allowed the number to go into decimals.



## Open-Source Assets
### W1
- Animals: https://assetstore.unity.com/packages/3d/characters/animals/animals-free-animated-low-poly-3d-models-260727 
- Low-poly environment: https://assetstore.unity.com/packages/3d/environments/landscapes/low-poly-simple-nature-pack-162153 
