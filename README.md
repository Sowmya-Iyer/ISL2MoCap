# ISL2MoCap
ISL Mocap dataset is built and rendered in blender to give a speech to ISL translation medium.


Using supervised learning, the 2D pose file obtained using OpenPose in JSON format which is further post-processed for missing joints and occlusions and transformed into 3D data using a fully connected depth-regressor to obtain the depth information in the frames. This skeletal information is obtained in the form of a.bvh file which makes the rendering of the motion capture data easier on any external animation software. The proposed architecture provides a stellar performance rate even in the CPU processor. This paves way for the creation of an Indian Sign Language motion capture database that can be used for animation in the future which aids applications such as text to sign language or further speech to sign language which would benefit the deaf community largely.

Code for sample pose data collection for ISL has been included. The report for the methodology used for the depth-regressor using an hourglass model is given. Email sowmya.iyer2010@gmail.com for further help with code.

