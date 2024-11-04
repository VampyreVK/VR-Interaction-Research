# VR Interaction Research

*Picking Up a Cube*

*Viviana Jenkins*

## Interaction Description

*I will implement 4 ways to interact with and pick up a cube:*

1. Red - Picking it up using direct hand interaction utilizing raw physics, allowing the user to cup the cube with their hands and balance it, or pick it up by going from under it. This interaction has no methods of friction, so it is designed to show the baseline for hand interaction without assistance in VR.

2. Green - Using hand snapping to allow the user to grab the cube by having the users fingers snap to the edges of the cube, allowing them to easily grip the cube with one hand.

3. Blue - Pulling the cube to the users hand by closing the hand while nearby the cube, the cube then flys to the users hand and can then be held as long as the user keeps their hand closed.

4. White - Using either the users hand or a controller to pick up and manipulate the cube from a distance. The cube will maintain its original distance and angle relative to the users initial hand position and rotation, allowing them to manpulate the cube more freely instead of limiting their range of motion to that of their arms.

## Storyboards

**This diagram is currently slightly out of date with my final interactions, so I will update it soon to better reflect the nature of my final interactions.**
![Example Diagram](IMG_0086.PNG)

## Project Video Demo

![Interaction Demo](InteractionDemo.mp4)

# User Testing Research

## Pre-Test Questions

1. Have you previously used hand tracking in VR? What was your experience with that in the past?

2. Do you prefer physical / hand-based interaction or controller-based interaction in VR?

3. Do you prefer interactions in VR to be more immersive and true to life, or more intuitive?

## Post-Test Questions

1. Which interaction felt the most intuitive to you?

2. Which interaction felt the most immersive or engaging to you?

3. Do you prever more precision, better ease-of-use, or more immersion when manipulating the objects? Do you think this depends on the type of application you are using?

## User Interaction Notes & Questions

### User 1

**Pre-Test Questions:**

1. No hand tracking experience
2. In vr, they would prefer controllers.
3. Prefers a more intuitive experience at first, and then more immersive over time. Wants it to ease-in as they learn more about the application.

**Testing Notes:**

Had trouble with getting the interactions at first, could not tell the difference between the hand pulling(Blue) and distance manipulation(white) methods of interacting with the cubes at first.

**Post-Test Questions:**

1. The green one felt the most natural.
2. Red one felt the most immersive
3. Ease of use is prefered, since they don't game a lot, more intuitive gives a better experience for them.

### User 2

**Pre-Test Questions:**

1. Yes
2. Hand based
3. Intuitive makes more sense

**Testing Notes:**

Had a little trouble at first with the grab gesture, but figured it out after some tinkering.

**Post-Test Questions:**

1. Since VR is inheretly non-physical, there is going to be some learning in all of them. The move at a distance(white) made the most sense.
2. The red block felt the best because it behaved like real physics. The lack of haptics made it tough. 
3. Depends a lot on application, if precision is needed(drawing or modeling), assistance would be helpful. For a more immersive experience, more natural physicality is better.

### User 3

**Pre-Test Questions:**

1. No previous experience
2. Using a controller as that is what they are familliar with
3. Intuitive is more important

**Testing Notes:**

Had a hard time figuring out the gestures, they often tried to reach out to something with almost a squid like gesture rather than a closed fist, and that resulted in the hand tracking not picking up their intentions properly.

**Post-Test Questions:**

1. The green felt the most intuitive to them
2. The red one where he could scoop it felt the most interactive and solid.
3. Ease of use is the best, the most immersive option doesn't always make for the best gameplay experience. 

### User 4

**Pre-Test Questions:**

1. No VR use before class, and no hand tracking experience
2. Hand based would be prefered. Controllers aren't bad, but there is a worry about dropping things
3. More intuitive is better, since being too real to live doesn't always translate to a great gameplay experience

**Testing Notes:**

Picked things up very quickly, immedeatly was able to interact with most of the objects. Juggled the cube around in their hands relatively effortlessly.

**Post-Test Questions:**

1. The blue one felt really easy to work with, the snapping was nice.
2. The green felt the most immersive, it struck a good balance of helping the user but not giving too much help.
3. It depends on what the user is trying to do, ease / immersion is the most important for them.

### User 5

**Pre-Test Questions:**

1. No hand tracking experience
2. Used to controllers, but it wouldn't be too much of a change to use hands
3. Intuitive matters more than immersion, a good balance is required. Intuitive first then true-to-life later.

**Testing Notes:**

Had a lot of fun during the interaction. Really enjoyed playing around with the different methods of interaction, especially bouncing around the red and blue ones, while sthey seemed to grasp how to pick up the green one the quickest.

**Post-Test Questions:**

1. The most intuitive was probably the green one where the hand automatically snaps around the object
2. The blue one felt the most engaging, they thought it was really cool.
3. It depends on what they are trying to do, even the type of game matters. The different aspects can be fun, a puzzle game with weird ways to pick things up would be very engaging.

### User 6

**Pre-Test Questions:**

1. A little bit of hand tracking experience, no personal VR headset, but they have tried it - Quest hand tracking demo on Quest 1
2. It depends on the interaction, physical is cool and works well, and feels intuitive, but controllers offer a lot more control. Superhot gun makes sense with controller, natural / playful interactions make sense to have hand tracking.
3. They would like to think they prefer true-to-life, but in reality they need a system that works first and foremost. Intuitive but real-to-life can be intuitive too if implemented well.

**Testing Notes:**

Had fun with the red cube, though, it did fall through their hands. Had a lot of trouble figuring out the correct hand closing gesture to use (Maybe an in-app tutorial on how to interact with objects would be helpful for new users). Because of the sensitivity of the at-a-distance interaction, they immedeatly threw the white cube into the air and off the map.

**Post-Test Questions:**

1. Green felt the most intuitive, the red was fun, but it also fell through their hands, too finicky to be usable. The snapping on the green was great, the blue one would feel great if it worked more consistently.
2. The red felt the most immersive because the physics made it feel a lot more real. It was cool cupping it and have it feel physical isntead of magnatized to their hand.
3. It depends on the type of application a lot. If they are expecting immersion going in, they are fine with it being more difficult. Once it starts breaking physically then it becomes a lot more frustrating than immersive. It has to be consistent. For some applications where the focus is on the gameplay, it should be as easy to use as possible, the interaction should get out of the way and let the world itself be the immersive part.


### User 7 - Teacher

**Testing Notes:**

Different interactions make sense for different scenarios. In 3D modeling it makes sense to use the white cube's interaction, liked how you could kinda pull it slowly towards themselves. They thought it would be cool to be able to scale the cube in size while both hands are interacting with at once. The green cube makes sense for something like Job Simulator, where thre is a lot of direct interaction with close by objects. The blue one is good for games that are more fast paced, for example, if there is a gun on the ground and the user needs to pick it up, having it snap to their hand makes sense. The red one is fun, and the juggling aspect is very enjoyable, but it is not as practical, would work really well in a cat simulator, where knocking things off the table and playing with the physics of things is the main goal.
