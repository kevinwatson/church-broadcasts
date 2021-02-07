# Church Broadcasts

Notes on broadcasting non-interactive church meetings

## Setup

### YouTube

We decided to use YouTube for the following reasons

* Accessible on almost any device
* Live streams can be scheduled in advance
* Live streams can be marked as unlisted
* Comments can be disabled
* It's free

There are disadvantages, though

* We need to remember to delete the recording after the live stream
* Advertisements show if the viewer is on a computer
* The URL is different every week

For specific YouTube studio settings, see [YouTube](YOUTUBE.md)

### Hardware

Various hardware will work for the broadcast. Use whatever is available. Here's the parts list with links for hardware we use in our broadcasts.

* [AmazonBasics 60-Inch Lightweight Tripod](https://www.amazon.com/dp/B005KP473Q)
* [Amcrest 1080P Webcam with Microphone](https://www.amazon.com/dp/B088TT8HVY)
* [USB 2.0 Digital Audio Capture Card](https://www.amazon.com/dp/B019T9KS04)
* Laptop
* Wired network connection (often the WiFi connection is saturated during the meeting because of all of the congragation's connected devices)

## Weekly Setup

Because our hardware isn't permanently mounted, I run through a checklist before starting the stream.

### Camera Location

* For cameras without a focus (like a webcam), place the tripod and camera in front of the podium
* Frame the speaker's mouth in the middle of the frame

### Software

#### Open Broadcaster Software

We've found that https://obsproject.com is a great option for broadcasting the meeting. It can stream directly to YouTube and other online services.

## Running the Meeting

#### Before the meeting starts

If you share the hardware and laptop with other congregations that attend in the same building, there are a number of items that need to be checked before starting the live stream. Here's a checklist of those items.

1. Set the YouTube stream key
1. Check that all of the cables are plugged in tight
1. Disable WiFi if an ethernet connection is available
1. Check video input
   1. If the video isn’t working, double click video capture device in the sources panel and choose the hd264 webcam USB option from the drop down
1. Check audio input
   1. Turn on the main sound system next to the bishop's chair
   1. Tap the microphone and if sound isn’t coming through the microphone, double click audio input capture in the sources panel and choose the usb audio source from the drop down
   1. Set the audio mixer slider almost all of the way to the right, so that when they’re speaking, it often goes in the yellow area but rarely in the red
1. Check video settings
   1. Base resolution: 1280x720 (anything higher will require more bandwidth and possibly cause dropped frames)
1. Start stream
1. Open link on separate device like your phone


#### After the meeting ends

Only when the laptop is shared among congregations

1. Open settings
   1. Remove the stream key
   1. Put the computer in sleep mode

And last but not least, delete the video. YouTube live streams are automatically recorded and should be deleted as soon as possible.

### Additional Features

There are things we can do to enhance the broadcast. One of these is to show information on the screen at specific times during the meeting.

#### Hymns

Showing the hymn numbers is a way to enhance the experience and help viewers stay engaged with the broadcast. The hymn numbers are visible in the top-right corner of our broadcasts, but on smaller screens the numbers are hard to read. By showing the hymn number near the bottom of the screen in a large font, we can help viewers participate from home.

##### Setup

Add text sources to the Sources dock. Adding a textbox for each hymn on the meeting agenda makes it easy to set both before the meeting starts.

1. Click the `+` button on the Sources dock
1. Click `Text (FreeType 2)`
1. Select `Create new` and in the text box, give it a name, something like `Hymn 1`
1. Click OK
1. Enter something like `Hymn 123` in the Text box
1. Check the Outline checkbox to make the text easier to read
1. Click OK
1. Repeat the steps above as many times as necessary, once for each hymn on the agenda
1. Click and drag the text sources so they are in the correct order (e.g. `Hymn 1` should be above `Hymn 2` and both should be above the `video capture device` source)

Set the position and size

1. Click the hymn source in the Sources dock
1. Set the position and size of the box by moving the highlighted text box
1. Click the 👁 (eyeball) icon on the hymn source to hide the text
1. Click on the second hymn source and move and resize until it is on top of the first hymn source
1. Repeat if needed

When setting up for a meeting, if the hymn sources are already set, you can click on the hymn source and change the hymn number in the Sources Toolbar (click View -> Sources Toolbar if it's not visible).

Before the meeting starts

1. Set the hymn numbers
1. Check the positioning
1. Hide the hymn numbers by clicking the 👁 icon

During the meeting

1. When each hymn starts, click the 👁 on the appropriate line to show the text
1. When the hymn ends, click the 👁 on the appropriate line to hide the text

## Frequently Asked Questions

**Q: Why not use the laptop camera?**

A: Laptop cameras are great for Zoom meetings where the camera is sitting at about eye level about a foot or two away. They're designed with a very small sensor and lens so that they will fit into a narrow and flat bezel. Here are a few reasons I wouldn't use the laptop camera:

1. These cameras are designed for close ups
1. It's difficult to position the camera correctly when the entire laptop needs to be pointed at the speaker
1. It's difficult to control the broadcast software when the laptop is facing the speaker

**Q: Why not use a smart phone? It has a built in camera and microphone.**

A: There are a few reasons:

1. You will get better audio by plugging into the building's sound system rather than using the phone's audio - the phone's microphone is also more likely to pick up ambient noise from the congregation
1. Stopping the stream at the end of the live broadcast means handling the camera, the movement of the camera can be disorienting for viewers at home
1. If you use YouTube, your channel must have at least 1,000 subscribers before you will be allowed to live stream

**Q: Why not attach the camera to the podium?**

A: While this is a simple solution and puts the camera in a close position, I've noticed that the person often moves the podium while they are speaking. This would make it disorienting for home viewers, as the background would appear to rock back and forth.

**Q: Why use a webcam?**

A: Ideally, a high-end camera with auto focus and zoom capabilities would be better than a webcam, but for the price, with good enough lighting a webcam can provide a good enough picture for viewers at home. A camera that is mounted on a tripod, separate from the laptop that is used to control the streaming software, is the best option to avoid bumping or accidentally moving the camera when managing the stream on a separate laptop. Any camera movement can be disorienting for home viewers.

**Q: How do I get better lighting?**

A: Most chapels weren't designed for broadcasting, for the following reasons (note that these issues apply to some but not all buildings). These items are not issues for in-person attendance, but definitely cause issues when trying to provide the best experience for home viewers.

1. Have a white or light colored wall behind the podium
1. Not enough light pointed at the podium
1. Windows behind the podium allow sunlight in behind the speaker

**Q: How do I balance the needs of those in person vs the needs of those in attendance?**

A: Here are a few ideas

For home viewers:

1. Minimize the number of times that you adjust the camera after the stream has started. Professional cameras have presets and can make smooth adjustments. Not so with most chapel setups. The movement can be disorienting for those watching at home.
1. Start the live stream a few minutes before the meeting start time to allow the home viewers to hear the prelude music and give yourself enough time to check the stream before the meeting starts
1. When the meeting ends, wait one or two seconds before stopping the stream - clicking the button too early can cut off the last words of the speaker
1. Frame the video so that the speaker is front and center
1. If there are windows behind the podium, frame the speaker so that the windows are not visible, otherwise you may be broadcasting a silhouette of the speaker
1. Broadcast the sound that comes from the building's sound system
1. Set the audio level so that the bar occasionally goes into the red, and often goes into the yellow

For in person viewers:

1. If the chapel has windows behind the podium, usually more natural sunlight is better for those in attendance
1. Minimize the number of times you make adjustments to the camera to avoid distracting members of the congregation

**Q: If I had to choose better sound or better video, which would I choose?**

A: Choose sound. The speaker rarely moves, and people viewing the broadcast notice choppy sound more than they notice dropped frames during a talk.

**Q: Why YouTube? Why not use Zoom?**

A: YouTube can be played on a number of devices, from smartphones to tablets to computers, even smart TVs. Zoom is restricted to mobile devices and computers, unless the user has the know how to plug their computer into their TV. Free Zoom accounts have a 40 minute restriction, which if you start the meeting a few minutes early, may not be enough time. A paid Zoom account will be needed to broadcast the stream in presentation mode (where users can't enable their microphones and cameras and interrupt other viewers).

**Q: Should I add a light to highlight the speaker's face?**

A: I've been asked if there's anything we can do to light up the user's face and get rid of the dark eye shadows, but so far I haven't been able to come up with a solution. The best solution would be to have brighter lights shining down from the ceiling. I could hang a light below the webcam on the tripod, but that would highlight the speaker's next and wash out their other facial features. Mounting a light above the tripod would help, but also block the congregation's view of the speaker. Another thing is that if there was a light right in front of them, I think it will be a distraction to the speaker and they will avoid looking straight ahead and would squint. 🤷‍♂️

Update: On 1/3/2021 we experimented with an small LED light in front of the tripod before the meeting started. I held it directly below the webcam. While watching the laptop screen, I turned the light on and noticed that it didn't help - I could barely see a difference when the light was turned on. The shadows remained. There was still too much light behind the speaker coming from the ceiling lights and the natural light from the windows on both sides of the rostrum. The person behind the podium said it was too bright and distracting. Conclusion: lights attached to the tripod aren't going to work. Much brighter lights need to be set up if we want to improve the lighting on the speaker's face.

**Q: Can you put the words to the hymns on the screen instead of the hymn number?**

A: Yes, it's possible. There isn't a scroll option for the text box, so each hymn, line by line, would need to be copied and pasted into the sources panel, organized, and hidden. During the hymn, the operator would need to unhide the line while staying in rhythm with the chorister. While this might be possible with enough setup time, there is another ward right before ours that only allows about 15 minutes of setup time before our organist starts playing and we start the stream. In other words, there isn't enough time to set this up before the meeting starts.

## Links

Here are a couple of links with additional info (and where I got some of my ideas)

* https://github.com/TechnoSwiss/broadcast_pi
* https://www.youtube.com/watch?v=VetZu8OwHOQ
