# Lesson: Digital Storytelling

### First and Last Name: Daniele Charasanakis
### University Registration Number: dpsd18129
### GitHub Personal Profile: DaniXks
### Digital-Storytelling-Individual-Assignment: xxx

# Introduction
Hi, here I'm planning to make a short animation for the Digital-Storytelling lesson at my university.
The subject is probably going to be a car chase.

# 1st Deliverable
This is the 1st deliverable. Nothing special so far, just followed the tutorials, made a few customizations and added some animated cameras to create the dailys you will find in the folders.

For Unit 2 I created these simple custom buildings with "ProBuilder" in Unity:
![Screenshot](pictures/Capture_903.png)

For Unit 3, this is the traffic cone I modeled:
![Screenshot](pictures/Capture_904.png)

And here is a car model I modeled in Blender that will replace the taxi in the future:
![Screenshot](pictures/Capture_908.png)
![Screenshot](pictures/Capture_907.png)

For Unit 4, there are two dailies you can check. One is this one, with pedestrians.
![Screenshot](pictures/Capture_905.png)

And then the other one is this one where I tried to make a cool shot of the taxi for the last challenge.
![Screenshot](pictures/Capture_899.png)

The camera and car animation especially required a lot of work so that they came out smooth, with extra attention paid to the angle of the tangents on each keyframe.
![Screenshot](pictures/Capture_906.png)

This is all for now.

# 2nd Deliverable

Time to step up my game and move entirely to Blender. And Gaea.
And use some of my music again.
I chose the title Proto type.

I updated the car textures to match the environment. So I added dust and dirt. Then changed the colour to a dark blue.
![Screenshot](pictures/Capture_911.png)

Then I created a new desert environment inside a software for generating environments called "Gaea".
![Screenshot](pictures/Capture_912.png)

Exported it into a "16bit Tiff" and used the texture to displace a plane with the Displace modifier inside Blender.
![Screenshot](pictures/Capture_913.png)

Then created a highway with an array modifier, applied a highway texture, and flattened the dunes so that the road can pass through them.
Also applied a sky texture to light up everything in a cinematic way, with the sun close to the horizon.
![Screenshot](pictures/Capture_914.png)

Then added 2 skyscrapers, using a model I had modelled earlier, and damaged them a little by deleting a few pieces and bending others. Also added some dust.
![Screenshot](pictures/Capture_915.png)

Finally, imported the car model and did the most time consuming thing in this project which was...its animation.
The cameras and cars are all meticulously animated manually (if we ignore the noise/waves I used to make the smallest shakes for the wheels and the tiny camera shake for some shots).
![Screenshot](pictures/Capture_916.png)

For the fourth shot, when the car enters the frame, I simulated some smoke.
![Screenshot](pictures/Capture_917.png)

For the rendering I used the 2.37:1 ratio for a widescreen cinematic feel, with a resolution of 1920 x 810.
I used Cycles for maximum realism and tried to optimize it as much as I could to improve rendering times. No frame took more than 15 seconds to render in this video, some took only 4. Some shots are rendered with only 64 samples, others with 128. Some have denoising, some don't.

Lastly, I used DaVinci Resolve to assemble and edit all the rendered shots and color-correct everything. I also added the animated titles in the intro.
![Screenshot](pictures/Capture_919.png)

Here is a comparison.
This is a rendered frame straight out of Blender:
![Screenshot](pictures/358_Cam06_No-CC.png)

This is the same frame but color-corrected:
![Screenshot](pictures/358_Cam06_CC.png)

Lastly, the music was composed by me using FL Studio :)

Here is the final version! (for now) 

Enjoy!


https://user-images.githubusercontent.com/65423916/236704392-576b6455-d3d4-4b79-8861-3982f56410ef.mp4


Here is a YouTube link for better quality: https://www.youtube.com/watch?v=9yS4FdB8w9E



# 3rd Deliverable

Hi again,

to finalize this video I re-rendered a lot of the shots in higher quality, with more samples and better de-noising. I also re-animated a lot of the shots, re-baked the car dust in higher resolution and improved the road.
By improving the road I mean that I scattered some small rocks and sprites with vegetation across it's surface. Overall, a bit of everything has been improved.
Here is a before and after:
![Screenshot](pictures/358_Cam04_v01.png)
![Screenshot](pictures/358_Cam04_v02.png)


The airplane is another model I had done in my free time in the past.
![Screenshot](pictures/Capture_923.png)

Animating the car when it jumps on the airplane was tricky as it had to remain attached to the airplane. To do it I used an empty object parented to the airplane and then constrained the car to that object. I then animated the influence of the constraint from 0 to 1 when the car lands on the airplane.

Here is the final version for this lesson. I'm planning to improve the video and publish it on my YouTube channel in the future.

(I had to compress this a lot to make it smaller than 10 MB, please watch the YouTube version)

https://github.com/DaniXks/Digital-Storytelling-Individual-Assignment/assets/65423916/3c9b0168-53c3-4a4f-8074-1927dce32624

Here is the YouTube link for better quality, it goes up to 4K: https://www.youtube.com/watch?v=W0q_ac8RWXg


# Conclusions


# Sources


# Conclusions


# Sources
