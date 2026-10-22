# User Stories

1. As a first responder, I want to use a live camera feed to capture and detect injuries, so that the computer vision model can automatically analyze visual injuries features such as fractures swelling or open wounds). (FR1)
   - Acceptance Criteria:
     1. Activating the live camera feed allows the system to capture real-time frames of the affected injuries.
     2. The computer vision model successfully processes the video frame to detect and classify the injury features.

2. As a non-expert community, I want to select currently available first aid materials from a checklist, so that the system can account for missing standard equipment. (FR2)
   - Acceptance Criteria:
     1. Checking available items dynamically updates the resource list passed to the fuzzy logic engine.
     2. Unchecking standard medical tools such as triangular bandages enables suggestions for safe household substitutes like belt and jackets.

3. As a non-expert community, I want the system to generate step-by-step first aid and improvised substitute instructions, so that I can provide safe initial care based on the injury severity and available tools. (FR3)
   - Acceptance Criteria:
     1. The fuzzy logic inference engine combines visual injury severity with tool availability to display prioritized, step-by-step care guidelines.
     2. Clear visual safety warnings are displayed if selected substitute materials carry high contamination or injury risks.

4. As a non-expert community, I want the system to automatically trigger the computer vision scanner when standard tools are missing, so that I can scan my surroundings for household substitute tools. (FR4)
   - Acceptance Criteria:
     1. Unchecking required standard tools in the checklist automatically activates the camera feed for object detection.
     2. The computer vision model identifies safe household items in real-time.

5. As a first responder, I want to review visual safety warnings and substitute usage disclaimers before applying improvised tools, so that I do not cause secondary harm to the victim. (FR5)
   - Acceptance Criteria:
     1. Prominent safety disclaimers and usage cautions are displayed alongside any recommended substitute item.
     2. The system requires confirmation or provides clear warning indicators if a substitute item poses potential contamination or instability risks.
