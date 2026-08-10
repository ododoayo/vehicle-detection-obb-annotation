# Annotation Guidelines

## Project

Multi-Class Vehicle Detection Annotation

## Objective

Identify and localize vehicles in the provided images using bounding box annotation.

## Classes

The following vehicle classes were used:

- Car
- Bus
- Truck

## Standard Bounding Boxes (AABB)

Standard axis-aligned bounding boxes were used to enclose vehicles using horizontal and vertical edges.

Annotators should:

1. Draw the bounding box as tightly as possible around the visible vehicle.
2. Include the complete visible portion of the vehicle.
3. Avoid including unnecessary background.
4. Create separate bounding boxes for separate vehicles.
5. Assign the correct class to each vehicle.

## Oriented Bounding Boxes (OBB)

Oriented bounding boxes were used when the annotation required the box to follow the orientation of the vehicle.

Annotators should:

1. Rotate the bounding box to follow the dominant orientation of the vehicle.
2. Keep the box as tight as reasonably possible around the vehicle.
3. Maintain the correct vehicle class.
4. Avoid excessive background within the bounding box.

## Occluded Vehicles

Partially visible vehicles should be annotated when enough of the vehicle is visible to identify its class and location.

The annotation should follow the visible extent of the vehicle according to the selected bounding-box type.

## Multiple Vehicles

When multiple vehicles appear in the same image:

- Each vehicle receives its own bounding box.
- Each vehicle must receive the appropriate class label.
- Overlapping vehicles should be annotated separately where their boundaries can reasonably be identified.

## Quality Standards

Annotations should be:

- Accurate
- Consistent
- Clearly localized
- Correctly classified
- As tightly bounded as reasonably possible

## Annotation Tool

Label Studio
