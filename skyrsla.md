# Verkefni 4

1. Spurningar
    1. What is a “standalone” headset?

    A self-contained HMD that does not require external processors or power

    2. How would you best define augmented reality?

    An overlay of digital objects and information onto the real world

    3. Project Tango enabled...

    Smartphone-based AR

    4. How have AR apps showcasing furniture enhanced the home shopping experience?

    You can see a potential purchase digitally overlaid in your real-life space

    5. What is one way AR can currently enhance social media?

    It allows users to digitally augment and manipulate faces 

    1. What is a drawback of outside-in tracking?

    Less portable 

    2. With outside-in tracking, sensors are housed within the AR device itself.

    False

    3. Which of the following devices uses inside-out tracking?

    Google Pixel smartphone

    4. How does ARCore understand the phone’s position and orientation relative to the world around it? 

    Through Concurrent Odometry and Mapping (COM)

    5. Clusters of feature points on a surface are used to create:

    A plane

    6. As you walk around an AR experience with your phone, errors accumulate and a device’s position and orientation may shift. What is this called?

    Drift

    7. Which best describes feature points?

    Visually distinct features in your real world environment

    8. Which of the following is not a technical constraint facing current smartphone AR technology?

    Scope

    9. The benefit of inside-out tracking is…

    The user doesn’t need external sensors to track the AR device

    10. A computer mouse is an example of a User Interface Metaphor.

    True

    1. ARCore is available in China.

    True

    2. ARCore has a hard time detecting feature points on... 

    Smooth white surfaces 

    3. Who are team members you should consider hiring to build your ARCore experience?

    All of the above

    4. All Android phones on the market are compatible to run ARCore.

    False
    
    5. When considering UX/UI, one good rule of thumb to remember with AR is:

    Avoid cluttering the screen with too many buttons or elements that might be confusing to users

    6. It is a good idea to use as many photorealistic assets in your AR project as possible.

    False

    7. What might break immersion in an AR app?

    Assets that attempt photorealism and disappoint

    8. To create your own AR project it is imperative to learn 3D modelling tools like Maya, ZBrush, and 3ds max.

    False

    9. When it comes to UX and UI:

    They are complementary fields of product design, and generally speaking UX is the more technical of the two

    10. Drag and drop, Voice, Tap, Pinch and Zoom, Slide, and Tilting are all examples of what?

    Basic interaction options

    1. Hit-testing…

    A & C

    2. Is it possible to download assets into your game during runtime using Google Poly?

    Yes

    3. What is a popular game engine used for creating AR experiences 

    Unity

    4. Which file formats does Poly support?

    None of the above

    5. It is advisable to anchor a digital object to a dynamically moving real world object. 

    False

    6. Why is determining the pose of the virtual camera and the real world important for AR apps?

    All of the above

    7. Currently digital objects can only occlude, or block, other digital objects and not real world objects.

    False

    8. How does surface detection help produce AR experiences in ARCore?

    All of the above

    9. You can use VR creation tools like Tilt Brush and Blocks to build 3D assets and store them on Poly for use in AR apps.

    True

    10. Google Poly is an online library where people can browse, share, and remix 3D assets.

    True


2. [HelloAR kóði og comment](https://github.com/gudmunduroh/arcore-unity-sdk/blob/master/Assets/GoogleARCore/Examples/HelloAR/Scripts/HelloARController.cs)

    [Upptaka](https://vp.gudmunduro.com/?file=VID_20181107_124451.mp4)

3. 'np' er ekki definað og stendur ekkert um hvað það á að vera.  'file' var það heldur ekki en virkaði að breyta því bara í nafnið á filenum.
> Traceback (most recent call last):
  File "main.py", line 15, in <module>
    img = np.expand_dims(img, axis=0)
NameError: name 'np' is not defined

4. [Kóði og comment](https://github.com/gudmunduroh/arcore-unity-sdk/blob/master/Assets/GoogleARCore/Examples/AugmentedImage/Scripts/AugmentedImageExampleController.cs)

5. Breyttum þannig að andy kallin hoppar áfram.  [Kóði](https://github.com/gudmunduroh/arcore-unity-sdk/blob/master/Assets/GoogleARCore/Examples/HelloAR/Scripts/HelloARController.cs)
