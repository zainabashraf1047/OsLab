# Linux Ubuntu Installation By Virtualization

## Virtualization

This involves running Linux as a guest operating system inside a virtual
machine (VM) hosted by your primary OS (Windows, macOS).

Popular VM programs include VirtualBox, VMware, and Hyper-V.

This method allows you to run Linux alongside your existing OS without
making permanent changes to your device.

It's good for experimentation, learning Linux, and running software
incompatible with your main OS.

1. **Download** Ubuntu  <https://ubuntu.com/download> .

   Press Download Ubuntu Desktop According to your Operating System 

![image-20240128162455345](C:/Users/Ahmad BILAL/AppData/Roaming/Typora/typora-user-images/image-20240128162455345.png)



2. Now download <https://www.virtualbox.org/wiki/Downloads> VirtualBox or VMWare https://www.vmware.com/products/workstation-player/workstation-player-evaluation.html  .

!![image-20240128162503034](C:/Users/Ahmad BILAL/AppData/Roaming/Typora/typora-user-images/image-20240128162503034.png)



3. Place it in a drive

   

   ![image-20240128162512138](C:/Users/Ahmad BILAL/AppData/Roaming/Typora/typora-user-images/image-20240128162512138.png)

   

   4. Now its time to create a virtual machine on virtual box or either on Vmware. Click on New Keyword to create a new virtual machine.

   

   ![image-20240128162520990](C:/Users/Ahmad BILAL/AppData/Roaming/Typora/typora-user-images/image-20240128162520990.png)

   

   5.  Choose a unique name for your Virtual Machine then a folder for its placement then choose ISO image which in our case is ubuntu then mark the checkbox skip Unattended Installation for smoothly running terminal in linux. Click next.

   ![image-20240128162526384](C:/Users/Ahmad BILAL/AppData/Roaming/Typora/typora-user-images/image-20240128162526384.png)

   

   6. Now choose Base Memory and processors for virtual machine.

      

![image-20240128084903061](C:/Users/Ahmad BILAL/AppData/Roaming/Typora/typora-user-images/image-20240128084903061.png)

7. Create a virtual hard drive for virtual Machine.

![image-20240128085006262](C:/Users/Ahmad BILAL/AppData/Roaming/Typora/typora-user-images/image-20240128085006262.png)

8.  Click **Finish** to finish the setup.

![image-20240128085103687](C:/Users/Ahmad BILAL/AppData/Roaming/Typora/typora-user-images/image-20240128085103687.png)

9. Now click on your virtual machine .

![image-20240128085418315](C:/Users/Ahmad BILAL/AppData/Roaming/Typora/typora-user-images/image-20240128085418315.png)

10.  This Screen will be shown and it will take few minutes . Hold down.

![Oracle VM VirtualBox Manager 1_28_2024 8_59_37 AM](C:/Users/Ahmad BILAL/Videos/Captures/Oracle VM VirtualBox Manager 1_28_2024 8_59_37 AM.png)

11. This screen will be shown. Now there are only few steps to do.

![vm [Running] - Oracle VM VirtualBox 1_26_2024 8_22_46 PM](C:/Users/Ahmad BILAL/Videos/Captures/vm [Running] - Oracle VM VirtualBox 1_26_2024 8_22_46 PM.png)

12. Click on install ubuntu and also set the language.

![vm [Running] - Oracle VM VirtualBox 1_26_2024 8_22_55 PM](C:/Users/Ahmad BILAL/Videos/Captures/vm [Running] - Oracle VM VirtualBox 1_26_2024 8_22_55 PM.png)

13. Select your keyboard layout.

![vm [Running] - Oracle VM VirtualBox 1_26_2024 8_23_03 PM](C:/Users/Ahmad BILAL/Videos/Captures/vm [Running] - Oracle VM VirtualBox 1_26_2024 8_23_03 PM.png)

14. Click on normal Installation and radio button download updates while installing ubuntu.

![vm [Running] - Oracle VM VirtualBox 1_26_2024 8_23_11 PM](C:/Users/Ahmad BILAL/Videos/Captures/vm [Running] - Oracle VM VirtualBox 1_26_2024 8_23_11 PM.png)

15. Mark the radio button "Erase Disk and Install Ubuntu".

![vm [Running] - Oracle VM VirtualBox 1_26_2024 8_24_35 PM](C:/Users/Ahmad BILAL/Videos/Captures/vm [Running] - Oracle VM VirtualBox 1_26_2024 8_24_35 PM.png)

16.  Fill in all the form inputs. Then click Continue.

![vm [Running] - Oracle VM VirtualBox 1_26_2024 8_26_09 PM](C:/Users/Ahmad BILAL/Videos/Captures/vm [Running] - Oracle VM VirtualBox 1_26_2024 8_26_09 PM.png)

17. Now it is copying file and it will take few minutes hold down.

![vm [Running] - Oracle VM VirtualBox 1_26_2024 8_27_13 PM](C:/Users/Ahmad BILAL/Videos/Captures/vm [Running] - Oracle VM VirtualBox 1_26_2024 8_27_13 PM.png)

18.  Your Virtual Machine is ready.

![vmachine [Running] - Oracle VM VirtualBox 1_28_2024 9_12_03 AM](C:/Users/Ahmad BILAL/Videos/Captures/vmachine [Running] - Oracle VM VirtualBox 1_28_2024 9_12_03 AM.png)

------

#  														Thank You!



> [!NOTE]
>
> Task 2

# Task 2



1. Install C++ Compiler by writing this Command . **sudo apt-get install g++**

![vm [Running] - Oracle VM VirtualBox 1_28_2024 9_29_21 AM](C:/Users/Ahmad BILAL/Videos/Captures/vm [Running] - Oracle VM VirtualBox 1_28_2024 9_29_21 AM.png)

2. Intsall C language Compiler by writing this command in terminal  **sudo apt-get install gcc**

![vm [Running] - Oracle VM VirtualBox 1_28_2024 9_29_05 AM](C:/Users/Ahmad BILAL/Videos/Captures/vm [Running] - Oracle VM VirtualBox 1_28_2024 9_29_05 AM.png)



![vm [Running] - Oracle VM VirtualBox 1_26_2024 9_07_42 PM](C:/Users/Ahmad BILAL/Videos/Captures/vm [Running] - Oracle VM VirtualBox 1_26_2024 9_07_42 PM.png)

3. Write this C++ Code in text Editor.

![vm [Running] - Oracle VM VirtualBox 1_28_2024 9_40_39 AM](C:/Users/Ahmad BILAL/Videos/Captures/vm [Running] - Oracle VM VirtualBox 1_28_2024 9_40_39 AM.png)

4. Write this code in C language in text Editor.

![vm [Running] - Oracle VM VirtualBox 1_26_2024 9_22_41 PM](C:/Users/Ahmad BILAL/Videos/Captures/vm [Running] - Oracle VM VirtualBox 1_26_2024 9_22_41 PM.png)

5. Check these Codes by Compiling and running in Terminal.

   * For C++ language

     To compile: g++ -o obj test.cpp

     To run: ./obj

   * For C Language

     To compile: gcc -o obj test.c

     To run: ./obj

![vm [Running] - Oracle VM VirtualBox 1_26_2024 9_23_09 PM](C:/Users/Ahmad BILAL/Videos/Captures/vm [Running] - Oracle VM VirtualBox 1_26_2024 9_23_09 PM.png)



> [!NOTE]
>
> Task 3

# Task 3

### Github Repo Link

<https://github.com/zainabashraf1047/OsLab>
