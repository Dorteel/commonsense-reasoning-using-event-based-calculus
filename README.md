# Commonsense Reasoning: An Event Calculus Based Approach

This repository contains my notes, exercise solutions and practice codes based on the contents of the book Commonsense Reasoning: An Event Calculus Based Approach by Erik T. Mueller.

**Fundamental entities:**
- Objects (and object identity)
- Properties that change over time (such as location)
- Events or actions (we must also be able to represent the effects of events on the properties, and events that are nondeterministic or context-sensitive)
- Time
- Space
- Preconditions (if the robot put the book on the table, it had to be holding it beforehand)
- Law of inertia (things do not move by themselves): If something (non-living object) has moved, then it has been moved by someone or something.
- Delayed effects and continuous change (the tap is left open and the sink fills up with water and overflows)
- Reasoning: It takes a representation as an input, and outputs a representation

**Default reasoning**: We assume a default (or normal) state of the world. Even though several exceptions might occur, the most usual (or most probable) state is considered to be the default state used for the *default reasoning*. The default assumption is that unexpected events do not occur.

**Mental States**: Common sense assumes that if an agent has an unsatisfied goal, it will come up with a plan to achieve the goal.

**Types of Reasoning**
- *Prediction* (also called temporal projection): reasoning about states resulting from events
- *Abduction* Given an initial state and a final state, the reasoning is done by forming a path of events.
- *Postdiction*: Given events that lead to another state, we have to reason about the state prior to the events.

### History of Commonsense Reasoning