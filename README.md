# Baseball-Biomechanics-Data-Analytics

### Biomechanics Data Analysis Task
## Overview
This repository contains the analysis and solutions to a biomechanics data exercise involving kinematic and kinetic data from a pitcher. The dataset provided includes both full-signal continuous data and discrete metrics, covering pitches from the 1st and 7th innings. The task required statistical analysis, visualization, and evaluation of various biomechanical metrics to assess performance and potential areas for improvement.

### Task Details
## Dataset Description
Signal File: Continuous data normalized from the peak leg lift to the follow-through phase of each pitch. Each frame corresponds to specific angular positions during the pitch cycle.

Metrics File: Discrete data for individual pitches, including pitch characteristics and angular positions at key event markers. Each row represents one pitch.

### Key Objectives
1. Statistical Analysis: Calculate averages and standard deviations for each inning and pitch type for the following metrics:

Pitch velocity

Maximum shoulder external rotation

Maximum elbow varus torque

Peak pelvis rotational velocity

Peak trunk rotational velocity

Peak elbow extension velocity

Peak shoulder internal rotation velocity

Results were tabulated programmatically for clarity.

2. Visualization: Generate kinematic sequencing velocity plots for fastballs. Separate plots were created for the 1st and 7th innings, using averages and ±1 standard deviation for the sequencing velocities.

3. Statistical Assessment: Evaluate the statistical differences between the 1st and 7th innings to identify potential red flags for performance or injury risk.

4. Metric Development: Propose new or additional metrics that could provide valuable insights into the pitcher’s performance or injury risk.

5. Performance Improvement Suggestions: Identify target metrics for the pitcher’s development, referencing published research to explain how these improvements could enhance performance or mitigate injury risks.

6. Insights and Future Directions: Highlight observations from the dataset and suggest potential research avenues or analyses with additional resources and time.

7. Mechanical Breakdown: Perform a mechanical analysis of a selected pitcher or hitter, summarizing strengths and opportunities for improvement using relevant video evidence.

## Glossary of Metrics and Conventions

### Pitch Data
Release Speed: Pitch velocity in mph.

Spin Rate: Spin rate in rpm.

Pitch Release Coordinates X: Horizontal release point in feet (1B (+) / 3B (-)).

Pitch Release Coordinates Z: Vertical release point in feet (height from the ground).

Extension: Distance from the pitching rubber in feet.

Horizontal Break: Horizontal movement of the pitch in inches (Glove Side (+) / Arm Side (-)).

Induced Vertical Break: Vertical movement of the pitch in inches.

### Positional Data

## Elbow X: Flexion (+) / Hyperextension (-):

0°: Fully extended.

90°: Field goal post position.

Negative values: Process of extending.

## Foot Position (FootPos_In): Open stride (+) / Closed stride (-) in inches.

Front Knee X: Hyperextension (+) / Flexion (-):

0°: Fully extended.

-90°: Lunge position.

Positive values: Process of extending.

## Pelvis Z: Orientation of the pelvis in degrees (0° perpendicular to the rubber, 90° parallel to the rubber).

## Shoulder X: Horizontal adduction (+) / Horizontal abduction (-) in degrees.

## Shoulder Y: Arm position relative to the body:

0°: Arm down at the side.

90°: Arm parallel to the ground.

## Shoulder Z: Internal rotation (+) / External rotation (-) in degrees.

## Stride Length (StrideLength100): Stride length as a percentage of height.

## Trunk X: Extension (+) / Flexion (-) of the trunk in degrees.

## Trunk Y: Lateral tilt of the trunk (Glove Side (+) / Arm Side (-)) in degrees.

## Trunk Z: Orientation of the trunk in degrees (0° perpendicular to the rubber, 90° parallel to the rubber).

## Back Hip Z: Internal rotation (+) / External rotation (-) of the back hip.

## Back Knee X: Same as Front Knee X.

## Center of Gravity (Model_COG_LAB_X): Lateral position of the center of gravity (3B (+) / 1B (-)).

## Center of Gravity (Model_COG_LAB_Y): Forward-backward position of the center of gravity (Home Plate (+) / 2B (-)).

## Center of Gravity (Model_COG_LAB_Z): Vertical position of the center of gravity (Sky (+) / Ground (-)).

## Elbow Force X: Lateral (+) / Medial (-) force at the elbow.

## Elbow Moment Y: Varus (+) / Valgus (-) torque at the elbow.

### Events

## BR (Ball Release): The moment the ball leaves the hand.

## MER (Max External Rotation): Maximum external rotation of the shoulder.

## FP (Foot Plant): The moment the lead foot makes contact with the ground.
