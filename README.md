# bias_vr

## !!! Add sample video to sample unity project
We have had problems with putting in a 3D video onto unity, so we would like some guidance as to how to do that. Please (in two separate unity projects) create a file with a short (approx. 30 seconds) and a long (approx 3 min) 360° video shot by a RICOH Theta S.

## 1. Sign to pop up 

Once the user puts on the headset and enters the coffee shop, there is a window that pops up. The window has a description of the project. **We have this written out, we just need to put it on the document** After the user reads whatever is in the window, there is a button on the bottom right portion of the box that says "OK". The user is able to click any button on the controller to interact with the sign. When they click on the button in the corner, the window goes away, and the user remains in the coffee room. We've included screenshots of similar examples of what we're looking for in case useful. 

## 2. Button that activates the video

In the coffee shop room there needs to be a button near to the user that has a play symbol on it. Floating above the button is text that says "click me" with an arrow pointing to the button. When the user clicks on the button, it will redirect them to the video. However, before the video is played, a window, similar to the one above, is shown. The window will have this content: 

"We would like to add that this material may be sensitive to some viewers. If at any point you would like to exit, there will be a button on top of your head. Just look up, point your controller at it, and pull the trigger to be removed from the experience."

There are two buttons on the screen in which the user may point their controller at, and press any button to select. One button is a "Cancel" in which the video will not play, the window will close, and the user will see the coffee shop. If the user clicks "Continue", the screen will fade to black, and the 3D video will begin to play. 

This task also requires importing the video into unity. The video was shot on a 3D RICOH THETA camera, and the user should be able to look around, in VR at what is happening in the video. 

Picture is on github

## 3. Emergency Exit Button

As mentioned above, we have defined a red "Emergency Exit Button", that can be used by the user while in the middle of the VR video. If they want to use the button, a user will look up, point the controller at the button, and click any button on their controller to be returned to the coffee shop. This button should not be visible to the user when they look straight ahead at the scene in front of them. 

## 4. Pop-up window after video is finished 

After the video is finished, another window should pop up. This should also have two options. At the top of the window there needs to be text that says "The reenactment has ended." Underneath this line of text there needs to be two rounded rectangular buttons (we have an example picture, but ideally the buttons would be spaced farther apart and more centrally). The button on the bottom left will say "Watch again", and the button on the bottom right will say "Continue to next incident". When the use clicks "Watch again." the screen will fade black and the video will play from the beginning. When the user clicks "Continue to next incident." the screen will fade black and the user will be transported to the 'second room'.

## 5. Button that activates video in the second room

Use the same button script from above but in the second room.

## 6. Motion Capture

Add full body motion capture to user while in the coffee room and 'second room'. The reason we're thinking about using motion capture is to put a digital mirror in VR that allows the user to see themselves in the room before watching the video. For this we're curious what kind of full body motion capture would be possible using only the headset and the two hand controlers, or what degree of motion capture could be achieved with one or two additional sensors. 
