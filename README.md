# PID_Clamping_AntiWindup
This is a simple model that shows the effect of a staurtion block on the gain of a PID controller

The saturation block essentially was used to limit the gain to the rated voltage of a DC motor

The PID gain shoots up to very large numbers after using the saturation block and this happens due to integration windup

A very simple soultion is to use clamping or back calucaltion

Clamping is the name of the anti-windup technique used here (stupid name for the technique cos literally clamping is what the saturation block do, so idk why they named it like that)
