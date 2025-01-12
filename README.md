# E n h a n c i n g  A u t o n o m o u s  C a r s  I n t e l l i g e n c e  U s i n g  D e e p  R e i n f o r c e m e n t  L e a r n i n g

## About the project
This work introduces a method for safely navigating a Self-driving vehicle to avoid obstacles and reach its destination in highway scenarios using a combination of deep Q Networks (DQN) and neural networks (NN). DQN is trained in simulation to serve as a
central decision-making unit using Q value functions for actions estimating future rewards and then finding the optimal solution that proposes targets for a trajectory planner. As the
self-driving car task involves making decisions based on sensor inputs and navigating through a complex environment, NN allows the Agent (virtual car) to learn a mapping from
raw sensor inputs to action outputs facilitating effective decision-making. After continuous training through exploration and exploitation, the self-driving car was able
to reach its destination successfully without hitting any obstacles, demonstrating that the suggested method is capable of safe and efficient driving.

[View the PDF](Abdulkadir_阿_i202321026Final_Report_SelfDrivingCar_DRL.pdf) for better understanding and documentation.

###Technologies: 
Python, Pytorch, Kivy, Numpy, Matplotlib
## Videos for Demo

![Video Demo](Result_videos/Video_1.mp4)
![Video Demo](Result_videos/Video_2.mp4)
