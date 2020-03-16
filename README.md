# facebook-hackathon-submission
Submission for the 2020 Augmented Reality Hackathon

Built in Facebook's Spark AR Studio software. 


# How it works
Simply download the project files and open `directionfbhackV2.arproj` in Spark AR Studio. 

Please keep in mind that Spark AR recognizes flat surfaces, so it may be cut off in case there is a wall. Depending on whether you want to use it indoors or outdoors, you may want to adjust the values in the `multiply` patch in the comment box "Scale real world reference object" up or down, in order to make the effect scale more extremely or less extremely. The effect is now setup to work fine in an open-air environment. 

You can print the `AR Sign.png` to test it out at home, or use it without and focus on an imaginary point in the sky ;). Pinch to zoom in or out, and then tap to reveal the aerial map. In this example, I created an aerial map for an "emergency hospital" which may not have clear signs as to what can be found where. The pointers point to an emergency room, pharmacy, and waiting room. 

There is an extra effect included to animate the arrows, this needs to be enabled in the patch for those that like that, I prefer them unanimated.

# What is it for
There are various situations where one could be in a large crowded area, or a large area without clear signs, that may require some direction. Examples could be:
- Emergency bases
- Festivals (where are the toilets?!? where are the bars?!?)
- Temporary bases 
- Bases that may change in organization (e.g. moving one block somewhere else). 
- etc. 

This application of augmented reality is built on a couple of basic principles: 
1. There will be something identifiable that everyone can see. For example, the top of a church, a logo, a mountain, a house, a cross drawn somewhere, or maybe the printed AR sign from this repository. You can create any point of reference you like. 
2. The user is asked to find this point of reference, and focus the reference point of the AR effect on it and scale it accordingly. The scaling will help place the effect at the right location for the person to see. 
3. When done, the user taps, and the aerial map reveals itself. This aerial map is easy to adjust based on the circumstances. For example, let's say the emergency room is placed at the north of the base, but is then moved to the south, you can simply adjust that in this effect and push it online for everyone to use the adjusted effect. It eliminates the need for creating temporary direction signs for temporary bases. 

Additionally, this effect can be expanded in various ways. E.g. contextual information could be provided in the effect, in this example of an emergency hospital... perhaps the number of patients in the emergency room and available beds, the number of patients waiting in the waiting room, and whether the pharmacy has received new supplies. For a more fun example, imagine a festival, the festival could give some contextual information about happy hours, special performances at special stages, location of toilets, or other nice ideas. 

An aerial map is useful for many situations that cannot be handled with a regular navigational map, it is therefore not intended to replace a navigational map. It is intended to give local, temporary, directional and contextual information when it is needed on temporary/short-term bases. 

I hope you like my hackathon submission :) if you would like to contact me, email me at ibby@ibbybenali.com.
