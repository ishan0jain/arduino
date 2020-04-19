# arduino
Can you simulate a McDonalds drive through?
Everybody loves eating at McDonalds! Since there is a lockdown in the country
due to the coronavirus outbreak, none of us can enjoy eating our favourite
burgers and French Fries. Keeping this in mind, the McDonalds team of your
city is planning to establish a new drive through ordering system. This will
ensure minimum contact while eating so that we can follow social distancing
even after lockdown ends.
Here is what a Drive Through means- You can take your car to the first window
where you can place your order. Then you move on to the next window to pay
for your meal. The final and third window is where you collect your order. All
these windows are situated on the circumference of the restaurant. While
following the windows, you encircle the restaurant and after collecting your
order, you can continue driving on the road.
PROBLEM STATEMENT:
Simulate a similar drive through which has the following characteristics.
• There is an ultrasonic sensor that senses if there is a vehicle coming. If
there is a vehicle detected, it sends signal to a servo motor in order to
open a barricade so that the vehicle may pass. After a particular delay, it
should close again. (1 ultrasonic sensor, 1 servo motor)
• Then the vehicle goes at window-1 where order can be placed. There are
four icons for four menu items and there is an IR sensor placed beneath
each icon. The customer waves in front of the sensor respective to the
menu item and thus the order for that item is placed. Here wave refers
to moving the hand in front of the sensor. (4 IR sensors)
• On the output side, (window-2) we will have four LEDs corresponding to
the same menu items. If a particular item is delivered, its LED will glow.
(4 LEDs)
• When a vehicle is detected at the final window, another ultrasonic
sensor sends signal to another servo to open the barricade so that the
vehicle may leave. After a particular delay, it should close again. (1
ultrasonic sensor, 1 servo)
DETAILS:
• Menu items are: A (Red LED), B (Blue LED), C (Green LED) and D (Yellow
LED)
• Assume that payment is taken care of.
• Servos should rotate 90 degrees to open/close barricades.
• Sensors should be named with appropriate variables as mentioned here:
us_1, us_2, ir_1, ir_2, ir_3, ir_4, led_r, led_b, led_g, led_y, servo_1,
servo_2.
• Assume appropriate distance of vehicle from ultrasonic sensor for its
detection.
• Take similar assumptions for IR sensors as well.
• Please comment all through the code to let us know about how you
have written your code.
