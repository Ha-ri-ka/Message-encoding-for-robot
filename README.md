# Message-encoding-for-robot
5th Semester Computer vision project

The project aims to create a safe and secure method to communicate with robots. 
Given input directions, an image representing the instruction in the form of colors is created. <br>
Input format must be of the form: direction [left/right/up/down] *-space-* distance <br>
ex:- left 20 right 10 <br>
![image](https://github.com/Ha-ri-ka/Message-encoding-for-robot/assets/118831413/8b68213f-483e-4131-b743-02f3edaf858d)

The same instruction produces a new image if given multiple times. <br>

The image is then decoded, the underlying instructions are communicated with the robot.<br>
we simulate a sample warehouse with a robot to visualize execution of instructions and to verify decoding.
![image](https://github.com/Ha-ri-ka/Message-encoding-for-robot/assets/118831413/a175eed6-b640-48b9-8d69-fe3abadf7a2c)
