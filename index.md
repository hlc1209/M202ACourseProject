## M202A Course Project

# Abstract

Image recognition is an emerging field with varieties of applications spanning from disease diagnosis, facial recognition, monitoring systems, to simply entertainment and human machine interface. Years ago, machine learning algorithms were computation-demanding, which is a major roadblock for the delivery of image recognition service with lower-cost and low-power embedded system. As the performance, robustness, and the resouce-efficent techniques for machine learnings have been significantly improved over the years, the application of low-cost and high-performance device for human-device interaction becomes possible.

The purpose of this project is to build a small-size and low-power real-time optical character recognition system based on Arduino Nano 33 BLE Sense and a touch screen, which is capable of recognizing characters written on the touch screen in real-time and send recognized characters to BLE enabled laptop/desktop as keyboard strokes. Inference of written characters is done on Arduino Nano 33 BLE Sense to enable the extendability of the whole system where recognized written characters are not limited to be used as keyboard strokes but rather any BLE-enable external devices. 


# About & Contribution

# Project Timeline

## Week 1-2 (Oct. 4-17)

* Research for project ideas with focus on human interface device (HID)
* Form a team of 2 considering the scope and difficulty of the project.
  
## Week 3 (Oct. 18-24)

* Create project website on Github and finish the section of abstract.
* Discuss project idea and validate the feasibility.
* Place order for necessary components.
* Research into the user Manual and tutorial of the purchased components.

## Week 4 (Oct. 25-31)

* Finalize detailed project ideas and create timeline for the project. 
* Analyze applications and review literatures that are similar to this project.
* Start wiring and testing of the touchscreen.
* Start collecting datasets for DL model training and building the model architecture using PC.

## Week 5 (Nov. 1-7)

* Finish wiring and interfacing the touchscreen with Arduino Nano 33 BLE Sense.
* Train the DL model using GPU and keep adjusting the architecture to obtain better performance with smaller model sizes.

## Week 6 (Nov. 8-14)

* Finish BLE connection between Arduino Nano 33 BLE Sense and PC with HID keystroke input.
* Attempt to run trained models on Arduino Nano 33 BLE Sense and profiling the performance to adjust the architecture.

## Week 7-8 (Nov. 15-21)

* Finish pruning, digitization, and model compression on ML model.
* Implement the compressed ML model in Arduino Nano 33 BLE Sense. 
* Achieve real-time DL model inference on Arduino Nano 33 BLE Sense with decent recognition accuracy.
* Achieve a basic graphical user interface, including handwriting input area and candidate words area.
* Resolve issues on timing and ensure the system meets the minimum requirement of real-time response.
* Prepare a demo video and report as a progress update.

## Week 9-10 (Nov. 22- Dec. 5)

* Tune the and further compress the ML model to improve the performance on both accuracy and timing.
* Add more functions to the GUI to enable more interesting interactions.
* Debug issues found through testing.
* Consider to make a 3D-printed case to package the system.

## Week 11 (Dec. 6-11)
* Evaluate the performance of the furnished system and compose the final report.
* Update the project website with detail testing results, source code, and thorough documentation.
* Prepare Zoom presentation. 

# References

D. Núñez Fernández and S. Hosseini, "Real-Time Handwritten Letters Recognition on an Embedded Computer Using ConvNets," 2018 IEEE Sciences and Humanities International Research Conference (SHIRCON), 2018, pp. 1-4, doi: 10.1109/SHIRCON.2018.8592981.
