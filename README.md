# RailgateController
This is an arduino code, created for an electronic project "Automatic Railway Gate Controller" done by me & some of my classmates as our Project for a course.
The detail video is here : https://youtu.be/gEsIEVdwU7Q
Presentation slide : http://goo.gl/h8Y5Z4

Some Tips : 
1. Before writing code for your project, conncect the all circuits & define them clearly.

2. Don't think, don't think about the 2 ways 1st time. At first, only think that the train will always come from one direction.Just forget 
   the other direction.

3. Now, you have two sensors. one is for sensing that the train is coming & the other is for sensing that the train has passed the gate.

4. Let call the 1st & 2nd Sensors  S1 & S2 respectively. S1 will signal of the coming of the train, S2 will signal the passing of the     
   train.

5. Now, it's easier to think, right? And I hope you've almost design the logic for one way. If not, think more.

6. If you discovered the logic, congrats :) .  You're done with the one way implementation. Go for the 2 way implementation now.

7. Just look for the signal from S1 sensor, if you get it just colse the gate (turn on the motor for 250+ ms)& turn on the buzzer & when   
   you get signal from sensor S2, open the gate & turn of the buzzer. That's it for one way implementation.

==> Two way implementation.
8. Now, we have 2 sensors S1 & S2.
    => If you get signal from S1, check that if S2 is already been triggered. If so, the train is passing the gate, otherwise it's just 
       coming.
    => Follow the above logic for the reverse direction.
