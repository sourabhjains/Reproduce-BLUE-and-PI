# Steps to reproduce ns-3 results of PI paper

Step 1: Install ns-3.26 (Clone it from: http://code.nsnam.org/ns-3.26)

Step 2: Copy `pi-queue-disc.h` and `pi-queue-disc.cc` from this directory and paste them in `ns-3.26/src/traffic-control/model`

Step 3: Copy `wscript` from this directory and paste it in `ns-3.26/src/traffic-control/` (it will overwrite the existing one)

Step 4: Recompile ns-3

Step 5: Run programs given in this directory to reproduce the results.

Details about the programs are as follows:

`first-bulksend.cc` - simulates light TCP traffic

`second-bulksend.cc` - simulates heavy TCP traffic

`third-mix.cc` - simulates mix TCP and UDP traffic
