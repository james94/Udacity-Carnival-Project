# Udacity Carnival Starter Project

This project is part of [Udacity](https://www.udacity.com "Udacity - Be in demand")'s [VR Developer Nanodegree](https://www.udacity.com/course/vr-developer-nanodegree--nd017).

## Summary

The Udacity Carnival consists of 3 Mini-Games: Plinko, Wheel of Fortune, and Coin Toss. With each game, you earn points. When you earn 2000 points, you will receive a virtual classic Carnival prize!

![carnival_scene_pc](carnival_scene_pc.jpg)

## Transferring the App to your Android Device

1\. Download **Udacity-Carnival-Project** via **Clone or download**. Then unzip
it.

2\. Unzip the **Build.zip** file inside the **Udacity-Carnival-Project** folder,
which contains an apk for Android called **FirstBuild.apk** from the Unity
Project.

3\. Plug in Phone to Computer. Your phone may be prompted to allow the Computer
access to your phone data. Click Allow.

4\. On PC, open the Windows Explorer or Finder. Click on your Android phone.

5\. On PC, open the "SD Card" or it may be called "Card" folder, then open "download"
folder. Drag and drop the **FirstBuild.apk** file into that folder.

6\. Eject your phone from the computer. On your phone, open an app, such as
on Samsung Galaxy S8 "My Files", that will allow you to see your downloads.

7\. Tap on **FirstBuild.apk**, a window may appear prompting you that your
phone is set to block installation of apps obtained from unkown sources, if you
want to test out the VR App on your phone, then go into **settings**.

8\. You will see **Unknown Sources** or something similar, feel free to click
**OK** to **Allow this installation only**. You will taken back to the
installation of **FirstBuild.apk**, click **Install**.

9\. You should receive message: **App installed**. Open the VR App and if you
have a Google Cardboard or similar mobile headset feel free to slide your Phone
into it and put on the headset. Else you can still try out the app even
without the headset.

## Unity App Running on Samsung Galaxy S8 Phone
  - Once the App is open, you should be in the carnival.
  - Feel free to try out the games in the carnival.
  - If you score 2000 points in any of the games, you'll win a Teddy Bear prize.

![carnival_on_s8](carnival_mobile_view.jpg)

## Tips on Playing the Games

- **How to Play Wheel of Fortune**
  - Hover the circle in the center of the
    wheel, you'll notice the circle becomes big, then tap the screen and the
    wheel will spin and then land on one of the wedges.

- **How to Play Coin Toss Game**
  - Hover the circle on the coins, the circle will grow, then tap your screen,
    aim the coin at the center of the CoinToss booth and tap your screen to
    launch the coin

- **How to Play Plinko**
  - Hover the circle to the Plinko booth, the circle will grow, you'll notice a
    ball is oscillating left and right, tap the screen when you want to release
    the ball.

## Versions
- [Unity 2017.2.0f3](https://unity3d.com/unity/whats-new/unity-2017.2.0)
- [GVR Unity SDK v1.70.0](https://github.com/googlevr/gvr-unity-sdk/releases/tag/1.70.0)

## Open Project In Unity

- Open Unity, then press Unity's **Open** button, select the
**Udacity-Carnival**.

## Customized Pre-existing Udacity Carnival Project

- **Personalized Scoreboard text:**
  - Title set to `James Medel's Scores` instead of the original
  `Udacity's Scores`

- **Aligned Scoreboard text:**
  - `Font size set to 2`
  - So, no part of the text appears outside of the black area of the Scoreboard

- **Customized Coin Toss Game:**
  - `Min Toss Power set to 10`
  - `Max Toss Power set to 13`
    - (Recommended in the answer from the Navigation Quiz)
  - So, now the player can actually score points instead of the coin
  just falling to the ground

- **Customized Wheel of Fortune Game:**
  - Point values are higher for `smaller wedges (Ex: 750, 500)`
  - Point values are lower for `larger wedges (Ex: 100, 250)`
  - Point values fit within the edges of the wedge

- **Customized Plinko Game:**
  - `Oscillation Distance set to 0.7`
    - (Recommended in the answer from the Wiring Up Quiz)

- **Positioned the Teddy Bear:**
  - `Position set to X = 0.01, Y = 4.5, Z = 10.14`
  - So, now Teddy Bear doesn't land on player when it's dropped as a reward
  - The Teddy Bear appears in the Carnival once you win 2000 points in any game,
  it will land in front of the Wheel of Fortune
