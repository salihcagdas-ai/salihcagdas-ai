# Computer Vision & Applied AI

Computer engineer working on computer vision, deep learning and applied AI.
I build Python tools that connect model training, evaluation and video inference.

## Technical focus

- Computer vision and object detection.
- Custom neural networks and baseline comparisons in PyTorch.
- Bounding-box evaluation, error analysis and reproducible experiments.
- Python tooling for local image and video processing.

## Featured projects

### [Face Detection with PyTorch](https://github.com/salihcagdas-ai/Deep-Learning-Face-Project)

A course project exploring a custom CSP-style backbone and a ResNet18 baseline
for face localization.

- Shared training and inference commands for both architectures.
- Multi-scale predictions, non-maximum suppression and IoU-based box evaluation.
- Checkpoints that record the model architecture and input size.
- Offline tests covering data validation, training, checkpoint loading and video output.

The README documents the architecture, setup and limitations. Synthetic tests
check the pipeline; they do not establish accuracy on real-world faces.

### [Traffic Vision Lab](https://github.com/salihcagdas-ai/traffic-vision-lab)

A maintained portfolio edition of a shared graduation project for traffic-video
analysis, with [project origin and attribution](https://github.com/salihcagdas-ai/traffic-vision-lab/blob/main/NOTICE.md).

- Calibrated homography and elapsed-frame timing for speed estimation.
- Directed crossings of a finite stop line, with HSV-based traffic-light checks.
- Local SQLite metadata, with personal fields discarded by default.
- A deterministic synthetic demo and offline tests for geometry and event logic.

Synthetic checks verify the pipeline; real-world detection, OCR and speed
accuracy have not been measured for this edition.

### [Edge Camera Lab](https://github.com/salihcagdas-ai/edge-camera-lab)

A local camera analytics prototype built around replaceable adapters.

- Local face embeddings and open-set gallery matching.
- A FastAPI dashboard and SQLite event storage.
- Signed cookie sessions, upload limits and configurable event retention.
- A synthetic workflow demo with generated scenes and fake inference.

Synthetic checks exercise software behavior; real-world recognition accuracy
and Pi/Hailo performance have not been benchmarked for this edition.

## Tools

Python · PyTorch · OpenCV · NumPy · FastAPI · SQLite · Git · pytest

I value clear implementations, testable behavior and results that can be checked.
