University of Pennsylvania, ESE 5190: Intro to Embedded Systems, Lab 2A

    Yangbo Zhou
    Tested on: HP Envy 13, Windows 11

# Setup Guide for Environment
Before we want to run C on the board, we need to set up the environment with several softwares.

Step 1: Terminal

Downloading the Kali Linux system, I installed a terminal window that can show the contents of my text file, with "vi" and "cat" command.

![1c2fc62903aefb4708ebabea7f48054](https://user-images.githubusercontent.com/90922933/195964360-b2518689-4200-4fec-a779-14f5473a603c.png)

![c1b5ae13f9b6dd7da7dfa3f1e63cf05](https://user-images.githubusercontent.com/90922933/195964349-101de044-59d5-437d-b2a9-cebe48be5e67.jpg)

Step 2: Seiral Concole

I used Putty as my serial console.
![image](https://user-images.githubusercontent.com/90922933/195964522-1e780d52-0109-4e3a-8b31-f00dccd87357.png)

Step 3: Arm GNU Toolchain

https://developer.arm.com/downloads/-/arm-gnu-toolchain-downloads

![image](https://user-images.githubusercontent.com/90922933/195964756-15f64964-829a-43d9-b159-8bfb5f714d53.png)

![image](https://user-images.githubusercontent.com/90922933/195964665-605c147f-0f6a-454c-b7c5-1f62b63e0d87.png)

Step 4: CMake

https://cmake.org/download/

![image](https://user-images.githubusercontent.com/90922933/195964914-4eec6c56-945e-472c-8cd2-6831d9d31ce4.png)

![image](https://user-images.githubusercontent.com/90922933/195964936-f8e5067d-d068-40bb-abb5-d2da87af4a49.png)

Step 5: Build Tools for Visual Studio 2022

https://visualstudio.microsoft.com/zh-hans/downloads/

![image](https://user-images.githubusercontent.com/90922933/195964988-223c8895-8902-4ded-ac1b-ece48dac3592.png)

![image](https://user-images.githubusercontent.com/90922933/195965056-7b948ea8-f435-4153-b907-fd3208b90976.png)

Step 6: Python 3.10

https://www.python.org/downloads/windows/

![image](https://user-images.githubusercontent.com/90922933/195965105-9487046e-d72b-485d-9bcc-506a7f4cb508.png)

![image](https://user-images.githubusercontent.com/90922933/195965121-2f0c5029-02ce-4899-bf34-486ed7ba0135.png)

Step 7: Git

https://git-scm.com/download/win

![image](https://user-images.githubusercontent.com/90922933/195965161-2681194d-77d8-42f6-b369-cb3386819841.png)

![image](https://user-images.githubusercontent.com/90922933/195965169-9f57940d-5677-43ac-a5bb-c63b937c95f9.png)

Step 8: SDK and Example

![image](https://user-images.githubusercontent.com/90922933/195965256-18a1a368-7fd5-4cb7-85e1-7e3a38ac168f.png)

Step 9: Building "Hello World"

![image](https://user-images.githubusercontent.com/90922933/195965306-fafc9d54-8bbe-4792-bc7f-df91d36028aa.png)

![1665801905277](https://user-images.githubusercontent.com/90922933/195965397-cde7f1f9-4577-412d-b39d-095f69391f16.png)

![image](https://user-images.githubusercontent.com/90922933/195965320-b9143c59-d9c0-4c82-8858-d1f1dae10cc4.png)

![image](https://user-images.githubusercontent.com/90922933/195965546-11c6cc6c-363d-4111-8cdf-6653aeec964b.png)

Step 10: Flashing and Running "Hello World"

For this last step, I found that instead of Putty, the serial console in MObaXterm is way more easier and clear. And Bingo! We got the "Hello World" running!
![image](https://user-images.githubusercontent.com/90922933/195965887-7c6c4951-2a5c-4389-a19d-79e4e1d8105d.png)






















