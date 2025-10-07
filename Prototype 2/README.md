# Immersive Interior Design XR: User Testing Plan

## Overview

This project is an **extended reality (XR) prototype** inspired by Planner 5D. The goal is to create an immersive version of a room planning app where users can interact directly with 3D furniture in a virtual environment. Instead of manually measuring or guessing layouts, users can reposition items naturally in XR to visualize their designs.

The XR experience is designed to make interior design faster, more intuitive, and less stressful.


## Testing Objective

The purpose of this test is to evaluate how users **intuitively reposition items** in the XR environment. Specifically, we want to investigate:

1. Gesture intuition: How do participants expect to grab, move, and adjust objects in XR?
2. Interaction design: Do users understand how to interact with furniture without explicit instruction?
3. Problem-solving behaviour: When objects are “out of place,” how do users naturally attempt to fix their position?

Assumptions:

* Users will expect a grab-and-drag gesture to move items.
* Users may attempt to rotate objects while repositioning.
* Users will apply real-world analogies (e.g., pushing, pulling, sliding).


## Prototype Description

The XR prototype contains:

* A room environment (plane with walls).
* One of each furniture objects (sofa, chair, table).
* The ability to grab and reposition objects along the floor plane.
* Objects are constrained to remain on the ground for realism.

Key Interaction Supported:

* Repositioning furniture** using natural XR gestures.


## Testing Methodology

### Method

I will be using a think-aloud protocol in XR, adapted for headset-based testing.

* Participants wear the XR headset and use hand controllers.
* They will be asked to perform repositioning tasks without detailed instructions, so their **intuitive gestures** can be observed.
* Throughout the test, participants are encouraged to verbalize their thought process.
* If they go silent, the facilitator will prompt with: *“Please describe what you’re thinking as you try that.”*

### Data Collection

* Screen capture & audio recording** of the XR session.
* Observation notes:
  * Gestures attempted (grab, drag, push, rotate, etc.).
  * Hesitation, confusion, or repeated attempts.
  * Frustration or satisfaction indicators.

* Task success rate: Did the object end up where intended?
* Completion time for each repositioning task.
* Post-test questionnaire:

  * Ease of use (1–5 scale).
  * Intuitiveness of repositioning.
  * Satisfaction with interaction.
  
* Short interview Questions:
  * Which gestures felt natural?
  * What was confusing or unexpected?
  * How would they expect repositioning to work in XR?


## Testing Setup

* Equipment: Unity XR prototype running on Meta Quest 2 (or PC VR setup), with screen + audio recording.
* Environment: Quiet room with space for safe XR interaction.
* Prototype features:

  * A room environment with furniture placed in “incorrect” or awkward positions.
  * Users can grab furniture and reposition it along the floor plane.


## Testing Procedure

1. Introduction (30 sec): Briefly explain the purpose of the app (room layout in XR).
2. Task instructions (1 min): Give participants a task sheet with repositioning goals, e.g.:

   * Move the sofa so it faces the TV.
   * Place the chair next to the table.
   * Reposition the table so it is centered in the room.
3. Think-aloud test (5–7 min): Observe natural gestures and strategies as participants attempt repositioning.
4. Post-test questionnaire + interview (2–3 min).
5. Debrief (30 sec): Thank participants and explain purpose.

Total Time: ~10 minutes per participant.
