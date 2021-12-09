# Radeonfan
This is a fan control script for amdgpu.
Allows for setting a zero rpm threshold ,setting how aggressive the fan curve is, a pwm offset, and the update interval

The curve is calculated via a quadratic, rather than a table with steps, this ensures that the fan doesn't ramp up and down suddenly in an audible way(annoying)

Should work with all cards using amdgpu. 

must be run as root
 
