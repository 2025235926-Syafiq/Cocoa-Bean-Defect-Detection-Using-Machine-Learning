# Requirements

## Functional requirements (what the system must DO)

1. The system shall capture digital images of dried cacao beans using an integrated camera setup.


2. The system shall preprocess input images through resizing, normalization, and augmentation to ensure suitability for model inference.


3. The system shall detect and classify individual dried cacao beans into seven distinct categories: good, moldy, cracked, insect-infected, flat, germinated, and clustered.


4. The system shall execute parallel decision-making to evaluate multiple quality parameters simultaneously and determine whether a bean is good or defective.


5. The system shall display real-time bounding boxes and class labels for each detected cacao bean on a user interface display.



## Non-functional requirements (how the system must PERFORM)

1. The system shall process and classify cacao bean images in real-time with minimal latency during live camera feed inference.


2. The system shall achieve a high level of classification accuracy, maintaining an overall real-time detection accuracy of at least 83%.


3. The system shall maintain consistent detection performance and stability under standard indoor lighting conditions.