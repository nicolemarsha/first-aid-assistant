# Requirements

## Functional requirements (what the system must DO)
1. The system shall allow users to capture images of limb injuries using a live camera and analyse the images using a computer vision model. 
2. The system shall allow users to select available first-aid materials from an interactive checklist, including materials that are missing. 
3. The system shall analyse visual injury features and the availability of first-aid materials to provide prioritised, step-by-step first-aid guidance based on recognised first-aid guidelines. 
4. The system shall check for possible alternative materials when standard first-aid materials are marked as unavailable, and recommend alternatives only when supported by reliable safety guidelines.
5. The system shall display clear safety warnings, usage instructions, and risk notices before users follow any recommended first-aid steps or use alternative materials.

## Non-functional requirements (how the system must PERFORM)
1. The system shall display injury assessment results and first-aid recommendations within 3 seconds after an image is submitted, under the defined test conditions..
2. The system shall process live camera video at a minimum of 15 frames per second (FPS) during real-time image analysis under the defined test conditions. 
3. The system shall display clear, high-contrast text, safety warnings, and step-by-step instructions, and shall aim for 99.5% system availability during its intended operating period. 
