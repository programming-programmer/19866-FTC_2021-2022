# About
This is the programming repository of FTC Team #19866. This repository contains all Autonomous and TeleOp Opmodes. 
Owner of repository is @programming-programmer. 

# How to clone this repository
❗***If you want to push to the master branch, contact @programming-programmer to add you as a collaborator. Only then can you proceed with the following.***

  - **If Android Studio is not installed, install it [here](https://developer.android.com/studio)**
  
  - <details>
    <summary><b>If you have a Github account and git is set up:</b></summary>
        <li>Open the terminal (depends on your OS)</li>
        <img src = "https://github.com/programming-programmer/ftc_new/blob/master/open-terminal-gif.gif" width = "700">
        <br>
        <li>Navigate to StudioProjects folder, where all Anroid Studio Projects are located (type "cd ~/StudioProjects" in most instances)</li>
        <pre>$ cd ~/StudioProjects</pre>
      
      <b>No SSH Key is set up / You don't know what that is:</b> <ul>
        <li>In terminal, type "git clone https://github.com/programming-programmer/ftc_new.git" (this selects https if you have an ssh key set up follow directions under SSH key)</li>
        <pre>$ git clone https://github.com/programming-programmer/ftc_new.git</pre>
        <li>In Android Studio, select open project, locate "ftc_new", and then open it</li>
        <li>Now you can start coding! :+1:</li>
      </ul>
      
      <b>SSH Key set up:</b><ul>
        <li>In terminal, type "git clone git@github.com:programming-programmer/ftc_new.git" (this selects ssh if you don't have a ssh key set up follow directions under "No SSH Key set up")</li>
        <pre>$ git clone git@github.com:programming-programmer/ftc_new.git</pre>
        <li>In Android Studio, select open project, locate "ftc_new", and then open it</li>
        <li>Now you can start coding! :+1:</li>
      </ul>
  </details>



  - <details>
    <summary><b>If you <i>do not</i> have a GitHub account:</b></summary><ul>
      <li>Go to Code</li>
      <img src = "https://github.com/programming-programmer/ftc_new/blob/master/enter.png" width = "800">
      
      <li>download ZIP folder</li>
      <img src = "https://github.com/programming-programmer/ftc_new/blob/master/zip.png" width = "800">
      
      <li>Open the terminal (depends on your OS)</li>
      <img src = "https://github.com/programming-programmer/ftc_new/blob/master/open-terminal-gif.gif" width = "700">
      
      <li>In terminal, type "mv ftc_new-master.zip ~/StudioProjects" (this moves the zip file to Studio Projects)</li>
      <pre>$ mv ftc_new-master.zip ~/StudioProjects</pre>
      
      <li>In terminal, type "cd ~/StudioProjects" (this navigates to StudioProjects)</li>
      <pre>$ cd ~/StudioProjects</pre>
      
      <li>type "unzip ftc_new-master.zip" (pretty self-explanatory)</li>
      <pre>$ unzip ftc_new-master.zip</pre>
      
      <li>In Android Studio, select open project, locate "ftc_new", and then open it</li>
      <li>Now you can start coding! :+1:</li>
    </ul>
</details>

## Additional Notes
- New Season Coming up - Plan to Update
- Common Errors:
  - When building the project via Gradle, the computer has to be connected to the actual internet. (This should not be a common error and I hate that it is)
- To reach the actual code go to the TeamCode Folder > src > main > java > org > firstinspires > ftc > teamcode
- If anyone wants to learn programming, learn Java (main language used in FTC) and learn FTC software. It's not that hard to find tutorials.

## Miscellanous
- [FTC Robot Controller GitHub Page](https://github.com/FIRST-Tech-Challenge/FtcRobotController/wiki)
- [FTC Dashboard](https://acmerobotics.github.io/ftc-dashboard/gettingstarted)
  - When connected to Control Hub's Wifi go to: "192.168.43.1:8080/dash"
- [Connect to Robot Controller](https://docs.revrobotics.com/duo-control/control-hub-gs/connect-to-the-control-hub-robot-control-console#web-browser)
  - When connected to Control Hub's Wifi go to: "192.168.43.1:8080" in a web browser

- [Markdown Cheatsheet](https://github.com/tchapi/markdown-cheatsheet/blob/master/README.md#TOP) | 
[Advanced Markdown Cheatsheet](https://gist.github.com/apaskulin/1ad686e42c7165cb9c22f9fe1e389558) | 
[Emoji Cheatsheet](https://www.webfx.com/tools/emoji-cheat-sheet/)

- <details>
  <summary>Connect to Control Hub in Android Studio via wifi</summary>
    <ul>
    <li><b>Go to Settings > External Tools > Tools > Press "+" button:</b></li>
    </ul>
      <ul>
        <li>Name: "Control Hub"</li>
        <li>Group: "External tools"</li>
        <li>Description: "N/A"</li>
        <li>Program: "$ModuleSdkPath$/platform-tools/adb"</li>
        <li>Arguments: "connect 192.168.43.1:5555"</li>
        <li>Working Directory: "$ProjectFileDir$"</li>
      </ul>
</details>
