# T-WATCH-V2-Set-Time
A simple sketch to set time with the Touch Screen to the T-Watch. Including Battery info and setting the Brightness.


- Set hour: Touch the lower-right area of the screen.
- Set Brightness: Touch the lower-left area of the screen.
    Brightness begins in 20 and increments by 50 until 170, then goes to 0 (Brightnes Off) and again to 20. But you can edit these values.
    When it´s 0, skips the principal loop´s code.
    When brightness at 0 (screen Off), touch the screen for 1 second until screen lights on again.
    Although brightness is at 0, code is running. If you want to switch off the watch, press the lateral button for 6 seconds.

NOTICE:
- This sketch requires TTGO TWatch Library.
- Remember select at the beginning, the correct version of your TWATCH (line 2).
- I´m an amateur, and I´m sure the code can be improved a lot. These are my first steps with the T-WATCH, but it runs.
