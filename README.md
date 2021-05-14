<!--
*** Thanks for checking out the Best-README-Template. If you have a suggestion
*** that would make this better, please fork the repo and create a pull request
*** or simply open an issue with the tag "enhancement".
*** Thanks again! Now go create something AMAZING! :D
***
***
***
*** To avoid retyping too much info. Do a search and replace for the following:
*** github_username, repo_name, twitter_handle, email, project_title, project_description
-->



<!-- PROJECT SHIELDS -->
<!--
*** I'm using markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** See the bottom of this document for the declaration of the reference variables
*** for contributors-url, forks-url, etc. This is an optional, concise syntax you may use.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->


<!-- PROJECT LOGO -->
<br />
<p align="center">

  </a>

# Human-in-the-loop in teleoperation with Mixed-Reality 

  <p align="center">
    Guanhao (Dean) Fu 
    <br />
    Email: gfu3@jhu.edu
    <br />
    Mentor: Ehsan Azimi
    <br />
    <a href="https://youtu.be/l8XXNfp2w94">View Demo</a>


  </p>
</p>



<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary><h2 style="display: inline-block">Table of Contents</h2></summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#scripts">Scripts</a></li>
    <li><a href="#acknowledgements">Acknowledgements</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

![Device overview](./Assets/Pictures/Proposed_robot.png)
This is a mixed-reality enhanced teleoperation system that ensures human-in-the-loop operation while conducting path planning surgeries and other robotics applications.




### Built With

* [Unity](https://unity.com/)


<!-- GETTING STARTED -->
## Getting Started

To get a local copy up and running follow these simple steps.

### Prerequisites

* Download unity from [Unity](https://store.unity.com/#plans-individual) website, make sure to use 2019.4.x.
 

### Installation

1. Clone the repo
   ```sh
   git clone https://github.com/deanfu1997/AR_Dean_2021.git
   ```
2. Open an example scene
   ```
   .\AR_Bluetooth.unity
   ```
3. Enjoy!


<!-- USAGE EXAMPLES -->
## Usage

This is a standard Unity project, where the main scripts are stored in the "Scripts" folder.

## Scripts

AR_Main: The main script where everything happens.

Counter: A public class that stores static variables for different scripts to access.

end_trigger_AR: The trigger for collider of the stop buttton.

jsonFloat: Json helper class for UDP communication.

JsonHelper: Another json helper class for UDP communication.

MyButton: A public class for button variables. 

praser: Praser function that prases received UDP inputs.

startTrigger: The trigger for collider of the start buttton.

Trigger: The collision detection script for the wires and obstacles.

UdpConnection, UDPReceive, UDPSend: all UDP functions that ensures communication between the unity program and HoloLens.


<!-- ACKNOWLEDGEMENTS -->
## Acknowledgements

* [OpenZen](https://bitbucket.org/lpresearch/openzen/src/master/) IMU plugin that runs in unity.
* [Uduino](https://marcteyssier.com/uduino/) Arduino plugin that runs in unity.



