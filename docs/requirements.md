# Requirements

## Functional requirements (what the system must DO)
1. The system shall allow users to use a live camera feed to capture real-time frames and automatically analyze visual injury features using a computer vision model.
2. The system shall allow users to select currently available first aid materials from an interactive checklist to account for available and missing standard equipment.
3. The system shall process visual injury severity metrics alongside selected tool availability using a fuzzy logic inference engine to generate prioritized, step-by-step first aid instructions.
4. The system shall automatically trigger the computer vision object detection module to scan the live camera feed for safe household substitute tools when standard tools are marked as missing.
5. The system shall display prominent visual safety warnings, usage cautions, and risk disclaimers alongside any recommended improvised substitute tools before care is applied.

## Non-functional requirements (how the system must PERFORM)
1. The system shall generate visual injury assessment results and fuzzy logic recommendations within 3 seconds of image submission.
2. The system shall achieve a minimum processing speed of 15 frames per second (FPS) when running live camera scanning for substitute tool detection.
3. The system shall display clear, high-contrast visual cues and step-by-step instructions with a minimum system availability uptime of 99.5% during emergency usage scenarios.
