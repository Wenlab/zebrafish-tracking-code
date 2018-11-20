Introduction
-------------------------------------------------------
This VI and associated scripts accompany the paper” Rapid whole brain imaging of neural activity in freely behaving larval zebrafish (Danio rerio)”(eLife 2017), which is developed to track a freely swimming zebrafish in a shallow chamber for whole brain imaging of neural activity associate with different behaviour. The code allow rapid estimation of fish movement and feedback control signals drove a high-speed motorized x-y stage to retain the entire fish head within the field of view of a high numerical aperture objective. 


Authors
-------------------------------------------------------
The project is written by Yong Jiang, Quan Wen(qwen@ustc.edu.cn ) and Wei Hang. <br>

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
* open CV

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
* Now you can click the "acquire" button on labview front panel,then the images of the fish will be on the screen. 
* When the "FISH_FOUND" indicator is on,you can click the "Track" button to track the fish.
