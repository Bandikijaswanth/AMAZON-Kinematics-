# AMAZON-Kinematics-
AIM

To determine the motion type of a differential-drive robot based on wheel velocities.

PROCEDURE
Initialize left and right wheel speeds
Compare both wheel velocities
If both speeds are equal, angular velocity becomes zero
Robot moves in a straight line
Display the motion type
CODE
# Wheel speeds
left_wheel = 3
right_wheel = 3

# Motion determination
if left_wheel == right_wheel:
    motion = "Straight Motion"
else:
    motion = "Turning Motion"

# Output
print(motion)
OUTPUT

Straight Motion

RESULT

Since both wheel speeds are equal, the robot moves in a straight line with zero angular velocity.
