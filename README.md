# 1-D-Quadcopter-motion
This is a quadcopter simulation on simulink, MATLAB that stabilizes at a particular height.

1)Download all the files into a single folder for e.g say "Quad_Folder". Go to Quad_folder, right click "Necessary Files.zip" and select extract here. Note that the folders present in "necessary files.zip" must be placed in "Quad_Folder" along with the other files.

2)Uncomment/Comment the real_time_pacer block to slow/fasten the simulation respectively.

3)Open the Quadcopter.slx file. Go to the virtual simulation block (by double clicking it) and double click the VR sink block (the block with pink sphere and blue cube on it) to see the animation.

4)Go to the "Quadcopter model" block (by double clicking it) and double click the PID(s) block to tune the PID parameters. This can be done manually by entering the values or by clicking the Tune.. option to auto tune the PID block. This opens an interactive GUI showing the response for various values that you select for the parameters on top.(Slide the cursor towards the behaviour of the model)

5)You can also see the response of the output by double-clicking the "scope" block in the file.

6)Enjoy!

