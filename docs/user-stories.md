# User Stories

1. As a first responder, I want to use a live camera to capture images of limb injuries, so that the computer vision model can analyse visible injury features such as fractures and open wounds. (FR1) 
   - Acceptance Criteria:
     1. Activating the live camera allows the system to capture images of the affected limb. 
     2. The computer vision model processes the captured image and identifies visible injury features within its supported categories.

2. As a community volunteer, I want to select the first-aid materials that are available from a checklist, so that the system can consider missing supplies when providing first-aid guidance. (FR2)
   - Acceptance Criteria:
     1. Selecting available items updates the list of materials used by the system to prepare its recommendations
     2. Marking standard first-aid materials as unavailable allows the system to check whether suitable alternatives are supported by reliable safety guidelines 

3. As a non-expert user, I want the system to provide step-by-step first-aid instructions based on the visible injury features and available materials, so that I can provide suitable initial care. (FR3)
   - Acceptance Criteria:
     1. The system uses the injury assessment results and available materials to display relevant first-aid guidance based on recognised guidelines.
     2. The system displays clear safety warnings when a recommended action or alternative material may carry a risk.

4. As a non-expert user, I want the system to check for possible alternative materials when standard first-aid supplies are missing, so that I understand what options may be suitable. (FR4)
   - Acceptance Criteria:
     1. Marking a required standard material as unavailable activates the alternative-material checking process.
     2. The computer vision model analyses the camera image for visible objects matching supported categories without assuming safety based on appearance alone.

5. As a first responder, I want to review safety warnings and usage instructions before using a recommended alternative material, so that I can reduce the risk of causing further harm. (FR5)
   - Acceptance Criteria:
     1. The system displays safety warnings and usage instructions alongside any recommended alternative material.
     2. The system clearly warns users when a material may be unsuitable or when its safety cannot be confirmed, and advises them to follow recognised first-aid guidance.
