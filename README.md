# Multi-Class Vehicle Detection Annotation

A computer vision data annotation project demonstrating multi-class vehicle detection using both standard axis-aligned bounding boxes (AABB) and oriented bounding boxes (OBB).

## Project Overview

This project was created as a practical data annotation exercise using Label Studio. The objective was to identify and localize vehicles in real-world images and produce structured annotations suitable for computer vision workflows.

### Classes Annotated

- Car
- Bus
- Truck

### Annotation Types

- Axis-Aligned Bounding Boxes (AABB)
- Oriented Bounding Boxes (OBB)

### Dataset

The source images were obtained from the [HumynLabs Car Images Dataset](https://huggingface.co/datasets/HumynLabs/car-images), which contains 538 images and is licensed under CC BY 4.0.

For this portfolio project, a subset of 24 images was independently annotated.

### Annotation Tool

**Label Studio**

## Annotation Workflow

1. Imported raw images into Label Studio.
2. Defined vehicle classes.
3. Annotated vehicles using bounding boxes.
4. Applied oriented bounding boxes where appropriate.
5. Performed a manual quality-control review.
6. Exported annotations into multiple formats.

## Export Formats

The completed annotations were exported in:

- Label Studio JSON
- COCO
- YOLO
- YOLOv8 OBB

## Quality Control

A manual review was performed after annotation to check:

- Correct vehicle classification
- Missing objects
- Duplicate annotations
- Bounding-box placement
- Bounding-box tightness
- Consistency between annotations

## Dataset Attribution

Source dataset: **HumynLabs Car Images Dataset**

License: **CC BY 4.0**

The original images are not claimed as original work. The annotation, labeling decisions, quality-control process, and dataset organization in this repository represent the portfolio contributor's work.

## Project Status

Completed initial 24-image annotation batch.
