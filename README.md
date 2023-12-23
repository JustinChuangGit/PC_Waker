# Portfolio Project: PC Waker 
![image](https://github.com/JustinChuangGit/PCwaker/assets/80928888/281fc42c-797d-4211-8318-f6b6bafa31be)

   

## Project Description 
My primary computing device is a Mac, yet the engineering programs utilized in school were predominantly designed for Windows. To address this discrepancy, I assembled a robust PC. However, accessing it remotely required leaving it powered on continuously. Consequently, I developed a PC waker to awaken the computer from sleep remotely, eliminating the need to keep it operational around the clock.

## My Contributions
I employed a Raspberry Pi as a server to introduce an additional layer between the external network and my PC. I developed a Python program that, when executed, initiates a secure shell connection with the Raspberry Pi. Subsequently, the Raspberry Pi sends magic packets to my PC, activating it through the wake-on-LAN protocol. Once woken, I can then Remote Desktop into the PC from my Mac.

