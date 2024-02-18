Situations in different simulation are as follows. Statistics is in the file "statistics.txt"

---FRFTC---
1_error_saturation_only：
saturation is set at [45,10;-45,-10];

2_100s_error_saturation_fault_1:
saturation is set at [45,10;-45,-10];
fault with fault rate of [0.1,0;0,0.1] is set at T=20s;
switching topology from line-connected to all-connected is set at T=10s;
simulation time is 100s;

2_error_saturation_fault_1:
saturation is set at [45,10;-45,-10];
fault with fault rate of [0.1,0;0,0.1] is set at T=20s;
switching topology from line-connected to all-connected is set at T=10s;

3_error_saturation_fault_2：
saturation is set at [45,10;-45,-10];
fault with fault rate of [0.9cos(\pi/20),0;0,0.9cos(\pi/20)] is set at T=20s;
switching topology from line-connected to all-connected is set at T=10s;

4_error_fault_1_only:
fault with fault rate of [0.1,0;0,0.1] is set at T=20s;
switching topology from line-connected to all-connected is set at T=10s;

5_error_fault_2_only:
fault with fault rate of [0.9cos(\pi/20),0;0,0.9cos(\pi/20)] is set at T=20s;
switching topology from line-connected to all-connected is set at T=10s;

---FLQR---
FLQR_1_error_saturation_only:
saturation is set at [45,10;-45,-10];

FLQR_2_error_saturation_fault_1:
saturation is set at [45,10;-45,-10];
fault with fault rate of [0.1,0;0,0.1] is set at T=20s;
switching topology from line-connected to all-connected is set at T=10s;

FLQR_3_error_saturation_fault_2：
saturation is set at [45,10;-45,-10];
fault with fault rate of [0.9cos(\pi/20),0;0,0.9cos(\pi/20)] is set at T=20s;
switching topology from line-connected to all-connected is set at T=10s;

FLQR_4_error_fault_1_only:
fault with fault rate of [0.1,0;0,0.1] is set at T=20s;
switching topology from line-connected to all-connected is set at T=10s;

FLQR_5_error_fault_2_only:
fault with fault rate of [0.9cos(\pi/20),0;0,0.9cos(\pi/20)] is set at T=20s;
switching topology from line-connected to all-connected is set at T=10s;
