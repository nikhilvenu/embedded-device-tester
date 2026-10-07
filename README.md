SDP Team 37: Embedded Device Tester

Automated tester for embedded devices. It connects to a device under test (DUT), sends it controlled inputs, measures its real hardware outputs, and decides whether it's behaving the way it should.

Status: preliminary / in planning.

Features
Stimulus: drives digital, analog, and PWM signals into the DUT
Measurement: reads digital, analog, and PWM outputs from the DUT
Firmware flashing onto the DUT
Pass/fail reporting
Architecture
Host PC  <--->  Tester  <--->  DUT

The host runs the tests, the tester generates and measures real signals, and the results are compared against expected behavior.
