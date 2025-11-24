# Social Robotics and Human-Robot Interaction

## Evaluation methodology:
- Project: 55% (compulsory, minimum grade 8);
- 3 MAPs of 30 minutes: 45%  (compulsory, minimum grade 8);

## Map 1 - 24th of November
The evaluation is composed only of writing questions, and the materials covered are from week 1 and 2 classes.

[Week 1 - Features of Interaction; Design Methods->](summaries/week1.md)

### Features of interaction

- **Social Robot:** A physical entity in a social environment, empowered to achieve goals, capable of recognizing others, and engaging in social interactions.

- **Interaction:** The process of working together to accomplish a goal. It is conditioned by: Embodiment, Proximity, Task, Autonomy, and Group Structure.

- **Agent vs. Robot:**
    - **Robot:** Physical body, higher anthropomorphism. Users feel more engaged but disclose less personal info.
    - **Agent:** Disembodied (e.g., ChatGPT). Users disclose more info.

**8 Features of HRI**
- **F1: Physical Proximity**
    - **Remote**: Separated by space or time (e.g., Mars Rover).
    - **Proximate**: Co-located (e.g., Service robot in the same room).
    - Deep: **Robot + Human** = Unified entity (e.g., Exoskeleton).

- F2: Group Structure
    - **Definition (Turner):** Members define themselves as a group, recognized by at least one other.
    - **Configurations:** Individual (1:1), Dyadic (1 robot, 2 humans), Small Team, Multi-team, Crowds.

- **F3: Nature of the Task**
    - **Social-Oriented:** Goal is conversation/companionship.
    - **Task-Oriented:** Goal is specific performance/work.
    - **Mixed:** (Most common) Combination of both.

- **F4: Duratio**n
    - **Short-term:** Spontaneous, often one-time (e.g., Museum guide).
    - **Long-term:** Repeated, relationship-building (e.g., Autism therapy).

- **F5: Information Exchange**
    - **Modalities:** Visual (GUI/AR), Gestures, Speech/NLP, Non-speech audio, Haptics/Physical.

- **F6: Motivation**
    - What drives the interaction (social needs vs. practical needs).

- **F7: Autonomy**
    - Sheridan’s Scale: A continuum from Teleoperated (human controlled) to Fully Autonomous (no human input).

    Key Trade-off: Higher autonomy requires higher trust and oversight.

- **F8: Embodiment & Affordances**

    - Embodiment Types:
        - Functional: Form follows task (Roomba).
        - Artifact-shaped: Everyday objects with sensors (Smart furniture).
        - Bio-inspired (Animal): Replicating animal capabilities.
        - Bio-inspired (Human/Humanoid): Designed for social environments and tools.
    - Affordances: The physical properties of the robot that suggest how it should be used. (e.g., Legs afford walking; Eyes afford gazing).

**Psychological Concepts**
- **Anthropomorphism:** Attributing human traits to non-humans. It helps humans rationalize robot behavior and increases engagement.
- **The Uncanny Valley:** Affinity increases with human-likeness until a point where it becomes "creepy" (too close to human but imperfect), then rises again with perfect realism. Motion can worsen or improve this effect.

### Design Methods

**Robot Design vs. Interaction Design**

- **Robot Design:** Focuses on the Body/Hardware (Morphology, Sensors, Actuators, Degrees of Freedom).
- **Interaction Design:** Focuses on Behavior/Flow (Communication, Timing, Social Cues, Feedback).

>*Note:* The body (Robot Design) constrains the interaction possibilities.

**The 4Ws Framework (Scenario-Based Design)**

Used to characterize a scenario.
1. **WHO:** Actors, roles, experience levels, and expectations.
2. **WHY:** The activity, goals, and task analysis (interdependencies).
3. **WHERE:** Context, environment (noise, light), and physical space.
4. **WHEN**: Duration, frequency, rhythm, and repetition of the activity.

**User-Centered Design (UCD)**

ISO standard methodology placing the user at the center.

It is divided in 4 Stages: 
1. Unnderstand Context
2. Specify Requirements
3. Produce Solutions
4. Evaluate

>Outcome: A structured map of user tasks, steps, and expected results.

**Specific Research/Design Methods**


- **Ethnographic Studies:** Immersive observation in natural environments.
    - Goal: Understand real workflows, tacit knowledge, and social ecology.
    - Example: Roomba studies showed robots became "social products" and changed household cleaning routines.

- **Focus Groups:** Moderate discussion (5-10 people). Good for identifying concerns and opportunities.
- **Sketching & Storyboarding:** Visualizing interaction flow and temporal changes.
- **Improvisation & Puppeteering:** Acting out scenarios to find social cues.
- **Mock-Up Studies:** Analyzing human behavior in a scenario to model the robot's future behavior.
- **Wizard-of-Oz (WoZ):**
    - A human ("Wizard") remotely operates the robot, but the user thinks it is autonomous.
    - Use: To test interaction designs before the AI is fully built.
- **Low-Fidelity Prototypes:** Rapid, simple models to test feasibility.

[Week 2 - Experimental Design->](summaries/week2.md)

### Foundations of Experimental Design

To run a study (whether for data collection, investigating responses, or testing a new technique), you must define four core elements:
1. **Research Question (RQ)**:
    RQs emerge from literature gaps or specific interests.
    - Example: "Do specific features in robot faces (IV) increase trust (DV)?"
    - Goal: To solve something not yet understood in the literature.

2. **Hypotheses**:
    A **prediction** based on theory, not a guess. 
    - Must link an Independent Variable to a Dependent Variable.
    - Example: "Robots with large eyes (IV) are perceived as more trustworthy (DV) than robots with small eyes."

3. **Variables:** 
    Any measurable characteristic.
    - Types:
        - **Numeric:** Discrete (count) or Continuous (time, distance).
        - **Categorical:** Binary (yes/no), Ordinal (Likert scale), Nominal (robot type).

    - The "Golden Rule" of Variables:
        - **Independent Variable (IV):** The "Cause." You manipulate this (e.g., Robot makes errors vs. flawless).
        - **Dependent Variable (DV):** The "Effect." You measure this (e.g., User likeability rating).

### Types of Experimental Designs 

You generally need conditions to compare (Treatment vs. Control).
1. **Quasi-Experimental (Weakest)**
    - One-group post-test: No comparison, just testing one group.
    - Pre-test/Post-test: Measure before and after interaction.
    - Flaw: Lacks internal validity. You cannot rule out external factors or prove causality because there is no control group.

2. **Between-Subjects (Independent Measures)**
    - Structure: Each participant experiences only one condition (Random allocation).
    - Pros: No carryover effects (fatigue/learning); Simple.
    - Cons: Requires more participants; Individual personality differences can obscure results (noise).

3. **Within-Subjects (Repeated Measures)**
    - Structure: Each participant experiences all conditions.
    - Pros: High sensitivity (controls for individual differences); Requires fewer participants.
    - Cons: Carryover effects (learning from the first condition affects the second).
        - Solution: Counterbalancing (Group A: Cond 1->2; Group B: Cond 2->1).
4. **Mixed-Methods**
    - Combines Between and Within variables. Useful for complex HRI scenarios.

### Measures and Metrics

**Crucial Insight:** Attitudes (what people say) often do not match Behavior (what people do). Always combine Explicit and Implicit measures.
1. **Measurement Types**
    - **Explicit (Conscious):** Surveys, Interviews. (Subjective).
    - **Implicit (Unconscious):** Reaction times, engagement, behavioral analysis. (Objective).
    - **Task Metrics:** Efficiency, completion time, error rate.
    - **Physiological:** Heart rate, GSR, fMRI. (Hard to link directly to robot manipulation; noisy/expensive).

2. **Standardized Questionnaires**: Using validated scales ensures scientific rigor.
    - **Godspeed:** The classic HRI questionnaire. Measures: Anthropomorphism, Animacy, Likeability, Intelligence, Safety.
    - **Almere**: Technology Acceptance Model. Predicts Intention to Use (Anxiety, Enjoyment, Usefulness, etc.).
    - **RoSAS:** Robotic Social Attribute Scale. Measures: Warmth, Competence, Discomfort.
    - **MDMT:** Multidimensional Measure of Trust. Distinguishes between:
        - Performance Trust: Reliability, ability.
        - Moral Trust: Honesty, benevolence.

### Scientific Quality & Execution

**Validity & Reliability**
- **Reliability:** Consistency of results across trials.
- **Internal Validity:** Did the manipulation actually cause the result? (Threatened by poor design/confounding variables).
- **External Validity:** Can these results be generalized to the real world/humanity?

**Ethics & Safety**: Before running a study, you need Ethics Approval.
- **Protocol:** Must cover privacy (data protection), protection of vulnerable groups, and prevention of harm (physical or emotional).
- **Participants:** Must give informed consent.

**Minimizing Bias & Noise**
- **Experimenter Bias:** Do not tell participants the hypothesis beforehand. Use a script so every participant hears the exact same instructions.
- **Question Bias:** Ask neutral questions ("Rate your experience" vs "Did you enjoy it?").
- **Environment:** Keep lighting, noise, and setup constant.

**Online Experiments**
- **Prolific:** Higher quality data, research-focused.
- **MTurk:** Fast, cheap, but lower quality and ethical concerns regarding worker treatment.

## Map 2 - 5th of December
