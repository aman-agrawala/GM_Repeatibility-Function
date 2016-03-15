# GM_Repeatibility-Function
Repeatibility Function written for HIL Benches using A&amp;D model files. This module will allow you to create complex test schedules that allow repeating and jumping back and forth in tests depending on user predefined conditions.

The following code is for installing the repeatability function to HIL benches. In order to load the code, it is expected that you are
familiar with python and Matlab/Simulink. Please see https://www.python.org/ for more information on installing and setting up python by yourself. Please see https://www.mathworks.com/support/learn-with-matlab-tutorials.html?requestedDomain=www.mathworks.com for more information on using Matlab/Simulink.

## Instructions

To get this code up and running:

1. Open the HIL Bench test application.

2. Load the test setup and simulated vehicle dashboard. These should be autodetected if placed in the default folder otherwise specify the location in the settings menu.

3. Open up your Simulink controller logic algorithms in the HIL Bench test application.

4. Now switch to the python console tab in that HIL Bench test application.

5. Type `python moduleLoader.py` and then specify the location of the HIL_Testing_SW.mdl. Loading the module may take 10 minutes. Wait for the confimation message to indicate the loading is completed.

6. Finally, load up the desired drive profile/test setup and wait for the test to finish. 
