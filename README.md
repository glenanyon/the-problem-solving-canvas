# The Problem Solving Canvas: An Instructional Guide for Engineers
```
Glen Anyon, 
Solution Mill Pty Ltd, 2025
```

## Introduction & Overview
The Problem Solving Canvas is a structured visual tool designed to guide engineers, technicians, and teams through complex challenges. It provides a systematic, repeatable methodology to move from the initial confusion of a problem to a well-defined, actionable plan.

The canvas is built on the principle that a thorough understanding of the problem is the most critical prerequisite to finding an effective solution. Too often, teams jump to conclusions or fixate on symptoms, wasting time and resources on solutions that don't address the root cause. This canvas acts as a "cognitive forcing function," compelling you to slow down, think critically, and collaborate effectively before taking action.

This tool was inspired by the ['Business Model Canvas'](https://en.wikipedia.org/wiki/Business_model_canvas) created by Alexander Osterwalder in 2005. 

## The Three Problem Solving Spaces

The canvas is logically divided into three distinct spaces, each representing a key stage in the problem-solving journey:

#### The Problem Space (sections 1.1, 1.2, 1.3 & 1.4)
These sections (the central column & bottom) are the heart of the canvas . It forces you to precisely define the problem, understand its nature, and establish a clear vision for the "Current State" and the "Desired State." This is where you start.

#### The Analysis Space (section 2.1, 2.2, 2.3 & 2.4)
These sections (the right-hand columns) is about understanding the ecosystem around the problem . It prompts you to gather evidence, identify who is affected, manage communication, and assess risks.

#### The Solution Space (section 3.1, 3.2 & 3.3)
These sections (the left-hand columns) are where you formulate your response . It's about assembling the right team, gathering the necessary resources, and creating a concrete plan of attack. This is what you do last.

## A Guide for Engineers: How to Use the Canvas
As an engineer, your primary role is to bring rigor and structure to problem-solving. Follow this step-by-step guide to populate the canvas. It is designed to be filled out sequentially, starting with the Problem Space and moving through the sections in a logical order.

### The Problem Space (Start Here)

#### 1.1: Core Problem Definition

The Guiding Question: *What is the specific, measurable problem we are trying to solve?*

This is the most important box on the canvas. Your goal is to create a concise, data-driven statement that describes the problem without prescribing a solution.

What to write:

- Be Specific: Instead of "The main pump is failing," write "Pump P-101 has tripped on thermal overload 3 times in 24 hours."

- Be Measurable: Instead of "The system is slow," write "User login times have increased by 30% (from 2s to 2.6s) since the last update."

- Focus on the "What," not the "How": Describe what is wrong, not what you think the solution is.

Example: 
```
"The back-pressure control valve PCV001 is providing no position feedback signal and is unresponsive to a 100% open command, causing a full plant shutdown."
```

#### 1.2: Cynefin Category & Approach

The Guiding Question: *What is the nature of this problem?*

Before you can solve a problem, you must understand its type. This box uses the [Cynefin Framework](https://en.wikipedia.org/wiki/Cynefin_framework) to classify the problem, which dictates your entire strategy.

How to choose:

- Clear: The solution is obvious and follows a known best practice or checklist. (e.g., The printer is out of paper). The approach is Sense -> Categorize -> Respond.

- Complicated: The problem requires expert analysis to find a root cause. There is a right answer, but it's not obvious. (e.g., A complex engine failure). The approach is Sense -> Analyze -> Respond.

- Complex: There is no single root cause, but multiple interconnected factors. The outcome is unpredictable. (e.g., Low team morale, unpredictable market behavior). The approach is Probe -> Sense -> Respond.

- Chaotic: A genuine crisis. The situation is unstable, and you must act immediately to contain the damage. (e.g., A major safety incident). The approach is Act -> Sense -> Respond.

Example: 
```
For the PCV001 valve failure, you would check Complicated and write the approach: "1. Gather data from the field. 2. Analyze potential failure points (electrical, mechanical). 3. Formulate a repair plan based on findings."
```

#### 1.3: Current State (Constraints & Negative Impacts)

The Guiding Question: *What is the pain this problem is causing right now?*

This box defines the "as-is" world and builds the business case for solving the problem. It documents both the tangible costs and the boundaries you must work within.

What to write:
- Negative Impacts: Quantify the cost of inaction. Include financial costs (downtime, lost revenue), operational costs (wasted material), and human costs (low morale, safety risks).

- Constraints: List the hard limits. Include budget, deadlines, safety procedures (e.g., LOTO), and regulatory requirements.

Example: 
```
"Impacts: Plant shutdown is costing an estimated $50,000 per hour. Constraints: All work must be performed under LOTO permit #ENG-105. Any replacement parts must be certified for Class 1, Div 1 environments."
```

#### 1.4: Desired State (Outcomes & Success Metrics)

The Guiding Question: *What does the world look like after we've solved this, and how will we measure success?*

This box defines the "to-be" world and creates a clear finish line. It is a measurable vision of success.

What to write:

- Vision: A simple sentence describing the ideal future state.

- Success Metrics: Specific, measurable, and time-bound metrics that will change when the problem is solved. These should directly counter the negative impacts.

Example: 
```
"Vision: PCV001 operates reliably from the control system. Metrics: 1. Valve strokes from 0-100% from the DCS within 2 seconds. 2. Plant has been running stable for a minimum of 4 hours post-repair."
```

## The Analysis Space

#### 2.1: System Knowledge

The Guiding Question: *What evidence, data, and documentation do we have?*

This box is where you ground your analysis in facts. It’s a list of all the information sources that provide clues about the problem.

What to write: 
- List both quantitative and qualitative data. Include system logs, trend data, alarm histories, maintenance records, P&ID drawings, manuals, and notes from operator interviews.

Example: 
```
"DCS alarm history for PCV001. P&ID drawing #PID-105-02. Maintenance logs from the last 5 years. Interview notes from the control room operator."
```

#### 2.2: Affected Stakeholders

The Guiding Question: *Who is impacted by this problem, and who cares about its solution?*

This is where you map the human ecosystem. A stakeholder is anyone affected by the problem or its solution.

What to write: 
- List the people or groups involved. Include operators, technicians, engineers, managers, customers, and suppliers.

Example: 
```
"Control Room Operator, Field Technician, Shift Supervisor, Plant Manager."
```

#### 2.3: Communication & Alignment

The Guiding Question: *How will we keep everyone informed and engaged?*

This box defines your communication plan. It ensures information flows efficiently and prevents stakeholders from feeling left in the dark.

What to write: 
- Define the meeting rhythms (e.g., daily stand-ups), communication channels (e.g., email list, Slack channel), and decision-making protocols.

Example:
```
 "Daily 8 AM troubleshooting meeting. Hourly status updates to the Shift Supervisor. Final repair plan requires approval from the Plant Manager."
```

#### 2.4: Risk Assessment

The Guiding Question: *What could go wrong during our problem-solving process?*

This box forces proactive thinking about the risks involved in both the problem and its potential solutions.

What to write: 
- Identify potential safety hazards, operational risks (e.g., making the problem worse), financial risks (e.g., costly repairs that don't work), and project risks (e.g., delays).

Example: 
```
"Safety Risk: Stored pneumatic pressure (650 kPa) in the actuator. Operational Risk: Incorrect diagnosis could lead to ordering the wrong part, extending downtime. Financial Risk: A full valve replacement could cost over $25,000."
```

## The Solution Space (Fill this out last)

#### 3.1: Team

The Guiding Question: *Who do we need on the team to solve this?*

Based on your analysis, this is where you assemble the core team.

What to write: 
- List the names and roles of the key people required to execute the plan. This is a smaller, more focused list than the "Stakeholders" box.

Example: 
```
"Lead: [Your Name] (Engineer). Field Execution: Peter Clarke (Instrument Tech). Operations Interface: John Smith (Operator)."
```

#### 3.2: Resources

The Guiding Question: *What specific tools, skills, and knowledge do we need?*

This is your resource checklist for executing the solution.

What to write: 
- List the specific tools (e.g., multimeter, HART communicator), expertise (e.g., certified electrician), and information (e.g., valve maintenance manual) required.

Example: 
```
"HART communicator for positioner diagnostics, calibrated multimeter, replacement positioner (Part #XYZ-123) from stores, LOTO locks and tags."
```

#### 3.3: Solving Strategy / Plan

The Guiding Question: *What are the specific steps we will take?*

This is your final, actionable plan. It should be a clear, step-by-step list of tasks.

What to write: 
- Number the steps in the order they should be performed. The plan should be specific enough that anyone on the team can understand their role. Start with diagnostics and move to resolution.

Example:

```
"Apply LOTO to PCV001's electrical and pneumatic supply.

Operator to check for 24V DC at the positioner terminals.

"If voltage is present, replace the positioner unit.

"If no voltage, trace the circuit back to Junction Box JB-105.

"Once repaired, commission the new unit and perform a full stroke test from the DCS."
```
By following this structured process, the canvas transforms a chaotic situation into a manageable project, ensuring that your team's effort is focused, efficient, and effective.
