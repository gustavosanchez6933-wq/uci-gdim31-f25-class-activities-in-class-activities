# in-class-activities
## Devlogs
### W1
When I move the camera out of the Cat Game Object, the camera no longers follows the cat anymore. This is because the camera is no longer connected to cat anymore so it doesn't know what to follow. So, the camera stands still. Itch Link: https://gamerfan1225.itch.io/in-class-activity-complete

### W2
1. The r, g, b variables are floats instead of intns, bools, or stings is becyase the colors go into the decimals which floats accommodate. Ints won't work because it has to be an exact number which the colors are never are, bools does not apply to the colors, and strings don't apply here either.

2. The _bounce variable variable is an int instead of a float, bool, or string because it counts the exact number of times that the ball bounces off the floor. Floats don't apply here because the ball can't bounce 1.5 times, bools uses true and false which doesn't affect the number of times the ball bounces, and string is just text and doesn't add anything the bounces.

3. The reason why the code was broken was because g wasn't a variable so it couldn't be assinged. So by adding g = g + 0.1, g is assinged and is added by 0.1. However, there was another error that was fixed by adding an f after the number which created a float for 0.1. This stopped the error and allowed the number to go into decimals.

### W3
Table 10 
Activity 1:
1. The output type would string because of the dialogue so it would be string GetResponse. The input would be the int friendship level and the bool flag for knowing the secret or not.

2. The output type would be void since there's no any output and the input would be a float sanity_level since the sanity level can go into decimals.

3. The output type would be boolean becuase it's true or false question and the input would be float time_hit since we need to determine the exact time the player hit the note.

Activity 2:
1. Classes and components are like a venn diagram, each circle has their own circustmensces or purpose but they all overlap each other to share how similar their purposes are to each other. The class is what gives the object the ability to change, the components is what gives the game obokect it's appearance, and the member variables is the settings of the game object.

Examples that I like:
A surfboard, class is the blueprint, components is building the surfboard itself, and the member variables is how it looks like (colors, shape, etc).
Baking a cake, a class is like a recipe, the components is baking cake, and the member varibles what frosting we use.

Activity 3:
1. The reason why the ball goes super bright because the brightness code kept increasing because every bounce cause the ball to becomce increasingly bright unitl it goes super sayian after many bounces.

## Open-Source Assets
### W1
- Animals: https://assetstore.unity.com/packages/3d/characters/animals/animals-free-animated-low-poly-3d-models-260727 
- Low-poly environment: https://assetstore.unity.com/packages/3d/environments/landscapes/low-poly-simple-nature-pack-162153 
