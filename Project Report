 

 

 

Final Project Report 

Kody Byrd 

Luis Mata Moreno 

Michael Stevenson 

CDA 3631 Section 1 

 

Introduction 

For our Final Project we designed, coded, and implemented a robotic arm system controlled by an STM32 Nucleo-F446RE board running FreeRTOS. The robot is then able to be directed through different tasks via buttons on the laptop connected to the circuit board. Other than the tasks stop and start, the main tasks the robot replicates before moving to position will always have the robot grab an object, and the next task will drop the object. The main tasks are left (L on the keyboard), the robot moves to the left, right (R on the keyboard), moves to the right, center (Space bar on the keyboard), the robot recenters itself, stop (E on the keyboard), emergency stop for the robot ending all tasks and stopping immediately, and start (S on the keyboard), reactivates the robotic arm ready to receive tasks after an emergency stop. These tasks are implemented using queues with the emergency stop function having priority whenever activated and removing all queues that were next to run.  

 

Materials 

The robotic arm was constructed using PLA plastic, and each part of the robot was designed using stl files provided to us through our professor, REDACTED.  

 

Methods 

BLOCK DIAGRAM/WIRE DIAGRAM 

 

Results & Discussion 

During the process of testing, the robotic arm successfully executed all the programmed tasks sequences under no load conditions with no issues. When going through the different motions it had no issues going left, right and other functions necessary. However, when a load (a small pack of Kleenex tissues) was introduced the arm encountered an unpredicted issue; while the grabber of the robotic arm would hold the object and attempt at grabbing it, the arm would fail to pick up the object stalling for a moment, and still attempt to move to the set position afterwards. This behavior shown indicated to us a possible mechanical design issue one reason being the motors where not strong enough to pick the object we presented. After analyzing and troubleshooting it was found that not enough current was entering the motors of the robot and because of this our issue occurred. After tweaking our robot, the robot worked successfully and proved everything had been working properly and this issue was called my human error of not providing enough current. Overall, the project went smoothly and was successfully completed by the end of the time allotted for this project. 

 

Conclusion 

In conclusion, the robotic arm preformed all the functions we wrote for it and with minor setbacks, including grabbing, lifting, moving, and releasing an object while responding accurately to user commands through the STM32 Nucleo-F446RE board running FreeRTOS. Although we encountered a temporary setback when the robot was unable to lift an object, the problem was solved quickly and the rbotic arm operated reliably and consistently, fulfilling all the necessary operations we gave it. Ultimitaly this project showed the effectiveness of our design, our knowledge of hardware/software integration, and demonstrate our real-world ability to adapt and overcome challenges that require a practical engineering skillset. 

 

GitHub Repo Link 

 

Acknowledgements 

We want to provide special thanks to our professor, REDACTED, for providing the stl files used to design the whole robot. 

References 

 
