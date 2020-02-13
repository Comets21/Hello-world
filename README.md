# Hello-world
The lego bot initial/beginner code

#include <kipr/botball.h>

int main()
{
    enable_servos();
    //up
    set_servo_position(0,0);
    msleep(500);
   //closed
    set_servo_position(1,1930);
    msleep(1500);
    //down
    set_servo_position(0,1100);
    msleep(500);
    //open
    set_servo_position(1,1000);
    msleep(1500);
    motor(0, -90);
    motor(1,90);
    msleep(2000);
    ao();
    enable_servos();
    set_servo_position(1,2000);
    msleep(1000);
    set_servo_position(0,800);
    msleep(1500);
    motor(0,-80);
    motor(1,-80);
    msleep(1600);
    ao();
    msleep(500);
     //down
    set_servo_position(0,1100);
    msleep(1000);
    //open
    set_servo_position(1,1000);
    msleep(1500);
    return 0;
}
   





