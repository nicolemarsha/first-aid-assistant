# Technology Explanation Outline

## Basic Working Principle
- **Working Pipeline:**
  1. Capture live camera feed of injured limb or household items.
  2. Pre-processing and normalization (adjusting resolution and contrast).
  3. CNN feature extraction through convolutional layers.
  4. Object detection and feature classification such as open wounds and swelling.
  5. Logical rule mapping to trigger first-aid guidance and safety warnings.

## Frameworks, Models, Methods and Tools
1. **YOLOv8:** Single-stage real-time object detection model used for fast bounding box feature detection and probability classification in a single forward pass.
2. **OpenCV:** Open-source library providing image processing algorithms, camera stream handling, and matrix operations for real-time display output.
3. **PyTorch Mobile / ONNX Runtime:** Machine learning deployment frameworks that optimize and quantize neural network models for execution on mobile edge devices without cloud dependence.

## C3: Fit to Problem, Benefits, Limitations and Comparison
- **Fit to Problem:** Solves non-expert bystanders' hesitation and lack of visual assessment skills during emergencies by providing automated visual injury detection and household substitute scanning.
- **Benefits:** Instant objective visual identification and automated material scanning to reduce unsafe improvised choices.
- **Limitations:** Environmental lighting and occlusion sensitivity; surface-level scope only (cannot detect internal fractures without X-rays).
- **Alternative & Comparison:** Compared to manual text-based questionnaires (which rely on panicked subjective judgment), Computer Vision provides automated, objective visual detection directly from live camera feeds, significantly reducing human error.