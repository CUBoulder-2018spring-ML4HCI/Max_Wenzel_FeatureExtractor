# Maxwell Wenzel Face Velocity

This input helper is to be used with the VideoInput_FaceDetection_Processing_3Inputs.

This input helper takes the position of your face and then finds the first order difference to find an approximation of the velocity of your face. This could be used in a project where you are trying to use the movement of your face as a control feature.

All that is needed for this input helper to get it to work is to set wekinator to take two inputs which are the x and y velocity of your face listening on port 6449 and then run this input helper and the VideoInput_FaceDetection_Processing_3Inputs and then it should be working.
