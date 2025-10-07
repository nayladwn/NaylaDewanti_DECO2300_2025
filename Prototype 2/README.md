# Prototype 2 - Vertical Unity Prototype

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

## Method

I will be using a think-aloud protocol in XR, adapted for headset-based testing.

* Participants wear the XR headset and use hand controllers.
* They will be asked to perform repositioning tasks without detailed instructions, so their **intuitive gestures** can be observed.
* Throughout the test, participants are encouraged to verbalize their thought process.
* If they go silent, the facilitator will prompt with: *“Please describe what you’re thinking as you try that.”*

## Data Collection

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

# Testing Results!

5 people tested my XR prototype that lets users redesign a virtual bedroom. Each participant used the Meta Quest controllers to move and arrange furniture items around the room. The main goal was to see how intuitive the interactions felt and how easily users could move and place objects in a way that made sense to them.

## Quantitative Data

| Participant | Task Duration (min) | Errors (misgrabs, bugs, misplaced) | NASA TLX (Avg /100) | Moving Objects Easy (1–5) | Confident in Placement (1–5) | Satisfied with Prototype (1–5) |
| ----------- | ------------------- | ---------------------------------- | ------------------- | ------------------------- | ---------------------------- | ------------------------------ |
| P1          | 9.5                 | 7                                  | 68                  | 3                         | 2                            | 3                              |
| P2          | 11.2                | 10                                 | 74                  | 2                         | 2                            | 2                              |
| P3          | 8.8                 | 6                                  | 65                  | 3                         | 3                            | 3                              |
| P4          | 10.6                | 9                                  | 72                  | 2                         | 2                            | 3                              |
| P5          | 9.9                 | 8                                  | 70                  | 3                         | 3                            | 4                              |
| Average     | 10.0                | 8                                  | 70                  | 2.6                       | 2.4                          | 3.0                            |

Most participants took around 10 minutes to finish redesigning the room, which was a bit longer than expected because some of the features (like rotation) didn’t work as intended.
The ray-based grabbing was also inconsistent — sometimes it wouldn’t attach properly, which caused people to make more mistakes and retry actions.

Even with those issues, everyone mentioned that the environment looked really good visually, and that the layout and lighting made it feel realistic and comfortable to interact in.

## NASA-TLX Summary

| Dimension       | Mean Score (/100) | Notes                                                                        |
| --------------- | ----------------- | ---------------------------------------------------------------------------- |
| Mental Demand   | 72                | Users had to figure out how to grab and move things due to unclear feedback. |
| Physical Demand | 65                | Extra effort from repeatedly re-grabbing and adjusting furniture.            |
| Temporal Demand | 68                | Tasks took longer because of bugs and slow response.                         |
| Performance     | 58                | Users completed the room, but often not how they wanted.                     |
| Effort          | 76                | Needed to retry actions several times to get precision.                      |
| Frustration     | 80                | Highest rating — mostly from the non-working rotation and glitchy ray grabs. |

Overall workload averaged around 70/100, meaning the task felt fairly demanding and sometimes frustrating. People often said they knew what they wanted to do but struggled to make the prototype respond the way they expected.

## Participant Quotes

* Participant 1: “The room looks good, but grabbing was weird — sometimes it didn’t connect at all.”
* Participant 2: “I kept trying to rotate the bed with two hands like in other VR apps, but it just didn’t work.”
* Participant 3: “It was a bit buggy, but I eventually managed to move things, not exactly where I wanted to be honest. The visuals were nice though.”
* Participant 4: “Really liked the vibe of the bedroom, but I wasn’t sure when I actually grabbed something or not.”
* Participant 5: “It reminded me of The Sims in VR — I’d use it if the controls were smoother.”


Post-Test Observations

| Observation                          | Impact                                  | Recommendation                                    |
| ------------------------------------ | --------------------------------------- | ------------------------------------------------- |
| Ray-based grab didn’t always work    | Slowed progress and caused frustration  | Improve ray accuracy or add direct hand grabbing  |
| Rotation interaction missing         | Users couldn’t align furniture properly | Add two-hand rotation or a rotation tool          |
| Objects floated or got stuck mid-air | Reduced sense of realism                | Lock Y position to ground plane                   |
| Interface slightly cluttered         | Slowed discovery of controls            | Simplify menu layout and highlight main functions |
| Visual design praised                | Maintained engagement                   | Keep aesthetic style for future iterations        |


## Summary of Results
Overall, the testing showed that while the aesthetic side of the prototype worked really well, the interaction design needs improvement. Most users understood what they were supposed to do, but the bugs in grabbing and rotation made the process slower and less intuitive than expected.

Even though participants found it frustrating at times, they still enjoyed the concept and saw potential in the idea. They described it as something they’d actually use if the controls felt smoother and more natural.

For the next version, I’ll focus on fixing the ray grab accuracy, adding rotation functionality, and improving object grounding so items move more predictably.


