# Quality Control

## Purpose

Quality control was performed after completing the annotation process to identify and correct inconsistencies, missing annotations, incorrect labels, and poorly positioned bounding boxes.

## QA Checklist

Each annotated image was reviewed for the following:

### 1. Object Coverage
- All identifiable cars, buses, and trucks within the annotation scope were reviewed.
- No relevant vehicle was intentionally omitted.

### 2. Classification Accuracy
Each annotation was checked to ensure that the assigned class matched the vehicle:

- `Car`
- `Bus`
- `Truck`

### 3. Bounding Box Accuracy
Bounding boxes were reviewed to ensure that:

- They enclosed the intended vehicle.
- They were reasonably tight around the visible object.
- Excessive background was avoided.
- Separate vehicles received separate annotations.

### 4. Orientation
For oriented bounding box annotations:

- The box orientation was checked against the dominant orientation of the vehicle.
- The rotated box was kept as close as reasonably possible to the vehicle's visible boundaries.

### 5. Duplicate Annotations
Annotations were reviewed for accidental duplicate boxes around the same vehicle.

### 6. Consistency
The completed dataset was reviewed for consistent application of labels and annotation rules across the image set.

## QA Process

The quality-control process consisted of a manual review of the completed annotations before export.

Following the review, the annotations were exported from Label Studio into multiple formats for use in computer vision workflows.

## QA Outcome

The completed annotation batch was reviewed and prepared for export in:

- Label Studio JSON
- COCO
- YOLO
- YOLOv8 OBB
