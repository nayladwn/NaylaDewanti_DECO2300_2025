# Prototype 1 - Horizontal Unity Prototype

This folder contains your first Unity prototype project files and documentation. 

Immersive Interior Design: Planner 5D Reimagined
Testing plan for interactive prototype 1

This project is Planner 5D but using XR for creating an immersive version of the Planner 5D where users can now scan their own surroundings and start using the app’s design features to plan out their layout. There is no need to manually measure out the dimensions of objects and how it sits in the room, enhancing productivity. This will make interior designing a lot faster, more peaceful, and less stressful.

## Testing Objective
From my concept, I want to test:
1. gesture intuition
2. user interaction design
3. app features that exist in the prototype

The test aims to discover how users interact with and understand the initial design and functionality. Main focus is on gestures.

I am assuming:
1. Users will expect drag and drop to place furniture.
2. Users will use mouse + keyboard shortcuts (like shift + drag) for rotation.
3. Users will find a trash bin intuitive for removing items.

## Testing Methodologies
I will be using think-aloud protocol to evaluate the prototype (made in Unity).

**Think aloud protocol:**
- Participants will say what they are thinking as they do tasks.
- If they go silent, I will prompt: "Please keep talking, tell me what you're thinking."
- I will not give help unless they are stuck.
- After the test, there will be a short questionnaire and interview.

**Data collection method:**
During the testing process, I will be observing the participants, seeing any pain points. I will also record the time completion and error rates to document the results of the process.
- Screen and voice recording during the test.
- Observation notes (hesitations, confusion, frustration points).
- Completion time for each task.
- Error count (wrong gesture, accidental deletion, misplaced object).
- Questionnaire: ease of use, intuitiveness, satisfaction.
- Short interview: what felt natural, what was confusing.

## Prototype description/requirements
The prototype was designed to do the three main interactions which are dragging and dropping an object, rotate an object, and removing an object.

It will display some furniture objects inside a tab. The tab will exist in the space of the plane where a room will exist. The plane features walls to mimic a room. The features that will exist are the tab where users can pick the object to drop into the plane.

**The prototype supports three main interactions:**
- Drag and drop an object into the room.
- Rotate the object.
- Discard/remove the object.
- There will be a furniture tab inside the scene.
- The plane will mimic a room with walls.
- Features include the tab for selecting furniture, drag & drop, rotation, and discard into trash bin.

**Behaviours coded in Unity (C#):**
- Left mouse click + drag = move object, release to drop.
- Left mouse click + drag + shift = rotate object.
- Left mouse click + drag to glowing red box = object is deleted.

## Testing Setup
This is what I need to do to setup the test and be ready for participants:
- Unity prototype on a PC (screen + audio recording).
- Quiet space, participant seated at computer.
- Prototype has:
  - empty room (plane with walls)
  - furniture tab with a few options
  - trash bin for discarding
  - 3D hand cursor to mimic XR interactions

## Testing process (also considering the schedule/time)
1. Explain what the application does (30 sec)
2. Give task sheet (1 min)
3. Run think-aloud test with 3 tasks (5–7 min)
4. Post-test questionnaire + short interview (2–3 min)
5. Debrief and thank participant

**Total time:** Around 10 minutes
