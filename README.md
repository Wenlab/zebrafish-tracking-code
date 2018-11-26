Introduction
-------------------------------------------------------
This VI and associated scripts were used to track freely swimming larval zebrafish in a shallow chamber. The results were published in a paper entitled [Rapid whole brain imaging of neural activity in freely behaving larval zebrafish (*Danio rerio*)](https://doi.org/10.7554/eLife.28158.001). The code allows rapid estimate of fish movement and feedback control signals that drive a high-speed motorized x-y stage to retain the entire fish head within the field of view of a high NA objective. 


Authors
-------------------------------------------------------
The project is written by Yong Jiang, Quan Wen(qwen@ustc.edu.cn) and Wei Hang. <br>

License
-------------------------------------------------------
With the exception of commercial software and SDKs within, the project is released under the GNU Public License. This means you are free to copy, modify and redistribute this software.

Hardware used
-------------------------------------------------------
* Camera: Basler aca2000-340kmNIR
* Stage: PI M687 ultrasonic linear motor stage, C-867.1U PILine® Motion Controller

Software and SDKs
-------------------------------------------------------
* Labview 2014 and associated software(NI Vision, FlexRIO, NI FPGA Modules etc.)
* PI SDK for Labview
* Pylon Windows
* OpenCV 1.1 + Intel IPP6.1

Installation for Windows 7
-------------------------------------------------------
* Before installing, please read the manuals of these software and hardware.
* Install software as what the manuals say.
* You should make sure the hardware is working normally before using the project.

How to use
-------------------------------------------------------
* Open camera, stage and other essential devices.
* Open and run 10-Tap 8-Bit Camera with DRAM (Host).vi.
* Open the Pylon and configure the camera.
* Now you can click the "acquire" button on labview front panel, wait until fish appear on the screen. 
* When the "FISH_FOUND" indicator is on,you can click the "Track" button to track the fish.

How to cite
-------------------------------------------------------
* If you use part of the code for your own project, please cite our paper Cong. et. al., Rapid whole brain imaging of neural activity in freely behaving larval zebrafish (*Danio rerio*), eLIFE, Sep 20 2017. 
