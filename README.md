# TrackBang
## Gesture-based macros designed with Trackballs, Touchpads and Trackpads in mind

Trackbang is a script for Windows written in **Autohotkey**.

It makes Trackballs, Touchpads and Trackpads much more versatile by adding a great many easily accesible gestures.

To do so, it capitalizes on an inherent advantage of Trackballs, Touchpads and Trackpads over conventional mice: You do not have to pick up and reposition the physical device once the pointer's position on the screen stops matching the position of the mouse on the desk surface. You will experience this with a mouse if you keep accelerating the cursor against the screen edge until you run out of space to move the mouse. To go back to normal operation, you will have to return it to the center of e. g. the mousepad. Not having to do this with a Trackball / Trackpad allows the script to freely reposition the mouse cursor on the screen, which makes TrackBang more efficient than other approaches to gestures for non-mouse devices.

Its core functionality is to turn the corners of your screen into hot zones to start scanning for gestures. I am aware that the 'hot corners' approach is nothing really new, but traditionally, people using screen corners to trigger macros only assign a single command or sequence of commands to them, rather than detection of a large number of gestures. Also, largely, I believe, due to the dominance of mice, screen corner macros have not become very popular because of the positioning problem I described above, which trackball users can ignore, however.

When TrackBang registers the cursor being present in a screen corner, it waits for the momentum of the pointer to settle, then transports the pointer back to the center of the screen and waits for a certain amount of time (this is configurable) for the user to perform a mouse gesture by sliding the pointer in one of the eight compass directions. These sliding gestures can be any of four types: short slides, longer slides, slides that reach all the way to the edge of the screen and drag-and-return type slides. Thus the number of available gestures per corner is four times eight, i. e. 32. Multiply this by four for the different corners and you get 128 easily accessible gestures that do not require any button presses at all.

Why use it? In my opinion, TrackBang can be very beneficial for four reasons:

1. Click-and-drag type gestures where you have to hold down a button while operating the trackball are not very comfortable on trackballs as opposed to mice. While this is a somewhat less pressing issue on thumb-operated trackballs, it is especially annoying in connection with the non-primary buttons on finger-operated trackballs where gestures often require crazy hand acrobatics. With the Slimblade, for example, I'd say all three non-thumb buttons make for pretty uncomfortable click-and-drag gestures. And you can't really use the comfortable primary button for gestures as it's generally reserved for drag and drop operations in the OS.
   
2. A number of (mostly old-school) trackballs only have 2 or 3 buttons. For these, TB adds endless options for executing more commands with your pointing device.

3. Trackpads and Touchpads have a limited number of gestures, mostly taken up by predefined default functionality, like scrolling or bringing up the desktop. Plus quite a few of the gestures done with multiple fingers take some effort to perform correctly. I think TrackBang can really shine for Trackpad / Laptop users who need to access more commands via their pointing device.

4. RSI-related issues or certain handicaps: With TrackBang, you can execute many actions without having to click any buttons at all. If you increase the period of time in which the script scans for gestures, you can complete these at your own pace, which may be helpful for anyone with special ergonomic requirements.
Now please explore the demo video. I just want to point out that, given the anatomy of our hands and lower arms, the bottom corners are the most accessible unless you reverse the Y axis on your device. I will be focusing on the bottom left corner in the demo.

https://github.com/Keyhabit/TrackBang/assets/56698156/d4188fd9-800f-48aa-9c72-1202c4f50551



