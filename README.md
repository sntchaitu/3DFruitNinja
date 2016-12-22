# 3DFruitNinja
Due to space constraints all files are uploaded on Google Drive
To download 
game files please click (https://drive.google.com/open?id=0B9yB6NpJIvKsREFIZDdRT0IxWmc) 
voice files please click (https://drive.google.com/open?id=0B9yB6NpJIvKsb211M1dBOG1pYkU)

Fruit Ninja 3d game is a first person controller game can be played with gestures .In this game, player navigate the scene using gestures, eat the donut and cakes and kill fruits. Game has 5 types of different fruits. Pineapple will pop up from the underground. Orange will punch the player. Watermelon will fly in the air and throw bullets. Lemon will move randomly in the air .Pineapple and Watermelon will need mode slices for killing them. Orange, Lemon and Coconut will need 1 slice to cut. Also Player will have star, Hook and katana to destroy the fruits.
Software Requirements:
Kinect V2 SDK
Hardware Requirements
Kinect V2, RAM greater than 4 GB, Windows 8.1
Work Done:
1) Implemented Player navigation gestures by 2 ways.
a) By taking static pose of the avatar.
b) By taking speed of different parts like movement of legs.
2) Implemented Fruits attack of 5 different fruits. 
3) Player sword will slice the fruit into 2 pieces. Also he can stab the enemies with sword.
4) Stopping fruits momentarily using sound.
5) Fruits slicing effect.
6) Player can select nearest 3 enemies and throw the hook.
7) Player can replenish his health by eating cakes and cookies.
8) Health Bar UI.

Works not included
 Fruits will not become moldy.
 User will not die even though the energy level become zero.





Known Issues:
When user raises both hands when current motion is standing, it will make a huge jump, which
Are not intended.
 Gesture recognition codes are written based on relative distances, so occasionally it will 
Recognize undesired gestures.

Work Done by Myungho Lee
Composed the Scene (virtual world)
 Added visual effects 
o Sword tail /attack
o Explosion when destroying fruits/star 
o Visual effect for Lava / Pineapple
 Implemented/modified energy bar and energy control logic
 Implemented logic for Player/Fruits/Star/Hook/Lava Motion behavior
 Implemented collision detection logics for Player/Fruits/Hook
 Implemented gesture/pose recognition for
o Walk, Duck, Jump, Navigation, Fly
o Slice, Stab, Throwing a Star, Hook/Selection/Throw
 Implemented speech recognition
Work Done by Santhosh Chaitanya
Initially build player navigation gestures using Visual Gesture builder software. But due to more latency we stick to gesture estimation using hard coded values.
Implemented Health bar UI
Integrating Kinect code with game scene.
Made sound and slicing effect for fruits.
Sword motion of slicing from left and right and stab in the scene
Implemented all Player navigation gestures using static poses. But finally we found out better way than this so we left this out.
Improvised fruit selection technique.

