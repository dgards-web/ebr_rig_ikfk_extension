# ebr_rig_ikfk_extension
EBR Rig IKFK Extension UI


EpicBendyRig Update 1.5

Documentation


Many thanks to @Dgards, @DvqJackson_2, @NJ Central


______________________________________________________

  Contents

 - About

 - New Feature List

 - How To Use

 - Animation

 - Copying To Different Files

 - Issues And Help




________________________________________________________________________________________________________________________________________________________________________________________________________________________




About


Ever since GoldenNinjaBen blessed us with the EpicBendyRig, we have sought to try and improve every aspect of the rig to liken it more towards the show. 

With this update of the EpicBendyRig, the rig has been completely overhauled, with over 60+ features added to make it easier to animate and use. A lot of time and effort has gone into this, so we hope you do appreciate the new features.



________________________________________________________________________________________________________________________________________________________________________________________________________________________


New Feature List


The amount of new features in the updated rig is huge, because of that, I have most likely missed a few here. Here is a list of them all.


Overhauled Face Rig
Bone controllers to animate every part of the face (Mouth, Eyes, Dimples, Eye Makeup (for P.I.X.A.L & Sora), Eyebrows, Eyelashes, Pupils)
Bone controller to hide parts of the eye
Different pupil shapes! Some scenes in Ninjago temporarily use different shapes for the pupil, so this has been included
Bone controller for eyelines
Lipstick toggle
Eye Makeup toggle
Eye glow
Eye switch (for ZANE or P.I.X.A.L)
Colour switches for Mouth, Eyes, Dimples, Eye Makeup, Eyelashes, Eyeline, Teeth, Lipstick, Tongue, Pupils, Outer Eye, Head… 
IK/FK controls for the arms and legs (eg. controls to switch from IK -> FK and from FK -> IK)
Controls to switch between the size of the rig (Between Adult, and child/smaller sizes) (And yes we will do the Avatar Long legs later 😊)
Mouth shapes flip between happy or sad expressions
Another Center of mass bone (why was this added…)
Bone controllers to rotate or scale nearly every part of the face
Alternative Eyelash and Eyeline shapes


________________________________________________________________________________________________________________________________________________________________________________________________________________________


How To Use


All the features are available in the Custom Properties panel of “Object Data Properties”. Or, they are also available in the script UI as shown above. (The script will need to be installed via Dgards github)

For any bone in the actual rig, select the bone, adjust it, then either right click and add a keyframe, or turn on auto-keying to add one.





To keyframe controls in the script or custom properties, adjust the property, right click to add a keyframe, and the following keyframes can be automatically added if you have auto-keying turned on.


________________________________________________________________________________________________________________________________________________________________________________________________________________________


Animation


All of these new features do slightly come at a cost, they can impact your viewport performance. We don’t really have a clear solution for that at the moment, but to help reduce the lag, in the viewport, you should ideally animate in this mode. 


For animating the facerig, use this mode. 
	


Turning on Max Viewport Subdivisions to 0 and Normals can slightly improve performance, although not a lot.


When syncing to audio, ideally choose Frame Dropping or Sync to Audio as Play Every Frame will be offsync. 


If you are on Blender 4.5, I recommend you change the Blender graphics API from OpenGL to Vulkan (You will need to 
restart for it to take effect). This should also improve
 the viewport performance.


If you have a decent GPU, please use it. (Won’t really help with viewport, but final render). I’m surprised by the amount of people who don’t.


________________________________________________________________________________________________________________________________________________________________________________________________________________________


Copying To Different Files



Ideally, sometimes you may want to copy the rig to your other blender files. For this, it is not necessary to append (although you can). For a faster method, press A to select everything, 
Then press CTRL C to copy, and go to your other Blender File and press CTRL V to paste, and it should work.


________________________________________________________________________________________________________________________________________________________________________________________________________________________


Issues And Help


Although I’ve tried my best to explain everything here, you may sometimes face issues. Feel free to ask @Dgards, @DvqJackson_2 or @NJ Central for any help.

That should be everything, many more features will be added soon, thank you for reading, and we hope you enjoy the rig!


________________________________________________________________________________________________________________________________________________________________________________________________________________________
