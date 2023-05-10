# ChickenVision Mobile App

Welcome to the ChickenVision mobile app repository! This repository contains the source code for the mobile app developed for Android phones. The goal of this project is to use augmented reality to replace faces in a crowd with a chicken helmet.

## Overview

The ChickenVision mobile app is built using Kotlin, a modern and efficient programming language for Android app development. The app also uses Python for video processing, AWS for cloud computing and server hosting, and Amplify for backend development.

The app allows users to point their phone's camera at a crowd and replace all the faces with a chicken helmet using augmented reality technology. The app also includes features such as image recognition software and a server or cloud service to process the images.

## Planned UI/UX

<img src="https://user-images.githubusercontent.com/66517969/236678890-3d2b2dca-a2ee-4a27-8c46-a95694ac50dd.png" width="700px">

## Details on UI/UX Design

### Record Button Placement

Considering the size of modern mobile phones, placing the record button at the bottom can make it difficult for users to reach. A higher placement on the right edge of the screen provides better grip and accessibility for users with smaller hands, reducing the need to use both hands.

If you think about it, it is natural for human hands to be on the right edge of the phone, because the grip is better. Why move drag it so far down?

<img src="https://user-images.githubusercontent.com/66517969/236679372-cf77332c-34da-4389-b451-7cede588a4fd.jpg" width="400px">

> <details><summary>Why those specific positions for the buttons and the menu?</summary>
> <p>
> <img src="https://user-images.githubusercontent.com/66517969/236679654-c92d1c61-3b76-48ff-ac6d-7863a6ecd229.jpg" width="200px">
> <img src="https://user-images.githubusercontent.com/66517969/236679661-d9e4e5d2-aeaa-4931-998d-5bce86029e63.jpg" width="200px">
> </p>
> </details> 

## Button and Menu Positioning

The buttons and menu are positioned to maximize screen real estate and minimize interference with the primary video view. This design choice allows users to focus on capturing the scene with a comfortable grip.

<img src="https://user-images.githubusercontent.com/66517969/236679572-42824516-ae2a-4df9-bd64-6b2dca047173.png" width="400px">

> <details><summary>What if the record button was a bit higher?</summary>
> <p>
> Then alot of valuable space on the screen is taken up.<br>
> <img src="https://user-images.githubusercontent.com/66517969/236680450-13a40635-5f6e-44a8-89c8-2455a9ee811a.png" width="400px">
> </p>
> </details> 

### What about filming diagonally?

The app's UI is designed to accommodate diagonal filming, enabling users to capture footage at various angles while maintaining easy access to the record button and other functionalities.

<img src="https://user-images.githubusercontent.com/66517969/236681098-d3c652af-7af3-4bdc-a555-a908ffe66028.png" width="400px">

> <details><summary>Why those specific positions for the buttons and the menu?</summary>
> <p>
> <img src="https://user-images.githubusercontent.com/66517969/236680833-b6c9d0f5-5e9a-4d15-a2d6-9c1bb839b241.jpg" width="500px">
> </p>
> </details> 

### Later UI feature 

We plan to introduce a lock feature, enabling users to record without holding the record button, further enhancing user experience.

<img src="https://user-images.githubusercontent.com/66517969/236682134-dbc3d581-171a-4c45-9fc8-5172a6f065d6.png" width="250px">

## Codebase Visualization

<img src="./diagram.svg" width="500px">

## License

The ChickenVision mobile app project is licensed under the MIT License. See the `LICENSE` file for details.

<!-- ## Acknowledgements

We would like to thank GitHub and DEV for hosting the GitHub + DEV 2023 Hackathon, which provided the inspiration and motivation for this project. We would also like to thank our the Pavoculus team members and contributors for their hard work and dedication in developing the ChickenVision mobile app. -->
