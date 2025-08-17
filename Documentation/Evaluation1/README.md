# Evaluation 1 Documentation

This folder contains the evaluation results and feedback analysis for your first prototype. Document user testing results, technical assessments, and iteration plans here. 

## Testing plan for interactive prototype 1
### Immersive Interior Design: Planner 5D Reimagined

This project is Planner 5D but using XR for creating an immersive version of the Planner 5D where users can now scan their own surroundings and start using the app’s design features to plan out their layout. There is no need to manually measure out the dimensions of objects and how it sits in the room, enhancing productivity. This will make interior designing a lot faster, more peaceful, and less stressful.

### Testing Objective
From my above concept, I have identified gesture intuition, user interaction design testing, app features that needs testing. 
This test aims to discover user interaction and understanding of the initial design and functionality. It will be focusing on gestures and UI design.

### Testing Methodologies
This testing plan will use task-based testing to evaluate a digital prototype made in unity. 
- Task-based testing:
    - This will expose me to what is intuitive and what isn’t. By giving them tasks without a tutorial it will allow me to see the raw intuition of how users interact with the prototype. If they fail to do the task, I won’t intervene.
- There will be a post-test questionnaire that will be given. 

### Prototype description/requirements
The prototype was designed to do the three main interactions which are dragging and dropping an object, rotate an object, and removing an object. 
It will display some furniture objects inside a tab. The tab will exist in the space of the plane where a room will exist. The room will be simple with just one window. The features that will exist are the tab where users can pick the object to drop into the plane. There will be a wall with basic explanation with how to interact with the space. 
- Sketch:
  ![Sketch Prototype](./images/sketch.png)
 
### Data collection method
During the testing process, I will be observing the participants, seeing any pain points. I will also record the time completion and error rates to document the results of the process.
- I will have the users do three tasks:
    - Drag and drop the objects from selection to room
    - Rotate the objects
    - Discard the objects

### Testing Setup
[This is what I need to do to setup the test and be ready for participants.]
- Create a room with little to no furniture, just a window.
- Create a tab with options of furniture
- Create a 3D hand as your cursor to show interaction with XR in the future. 
- In C#, code these behaviours:
    - When selected (left button click), item can be movable in any direction, release when user let go of left button.
    - When selected (left button click) + shift (keyboard), user can now rotate in any direction.
    - When selected(left button click) and drag to the glowing red box next to user, object will disappear.

### Testing process: (also considering the schedule/time)
1.	Explain what the application does (30 seconds)
2.	Present and let participant read the task sheet of three tasks (1 min)
3.	Let user do the three tasks (5 mins)
4.	Post-test questionnaire (1 min)
