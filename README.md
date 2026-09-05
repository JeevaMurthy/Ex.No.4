# EXPERIMENT 4 – ADVANCED PROMPTING TECHNIQUES

## Generate the Prompt and Evaluate for the Following Prompt Patterns

- Zero-shot Prompting
- Few-shot Prompting
- Chain of Thought Prompting
- Persona Pattern
- Reverse Prompting
- Graph Prompting
- Active Prompting

---

### NAME : Jeeva K

### REGISTER NUMBER : 212223230090



---

# AIM

To write prompts for the following prompt types and compare the generated
responses using different AI tools and evaluate them using a rubric-based
evaluation method.

---

# USE CASE

## IoT-Based Smart Manufacturing Automation

The manufacturing industry is looking to reduce manual monitoring and
increase efficiency through automation. The system will utilize IoT devices
and embedded controllers to automate equipment, monitor performance, and
enable predictive maintenance.

The goal is to streamline the production process, minimize downtime, and
enhance energy efficiency.

---

# TARGET AUDIENCE

- Manufacturing companies
- Automotive industries
- Electronics industries
- Food processing industries
- Industrial automation engineers
- IoT engineers
- Embedded system developers
- Researchers

---

# MAIN OBJECTIVES

- Improve production efficiency by 30%.
- Minimize machinery downtime with predictive maintenance.
- Enable real-time monitoring and remote control.
- Reduce energy consumption by optimizing processes.
- Improve machine reliability and operational safety.

---

# PROMPT PATTERNS

## 1. ZERO-SHOT PROMPTING

### Definition

Zero-shot prompting generates a response without providing examples to the
AI model.

### Prompt

```text
Explain how an IoT-based smart manufacturing system can monitor machines
in real time, detect possible failures, and improve production efficiency
without providing any examples.
```
### Expected AI Output

An IoT-based smart manufacturing system uses sensors connected to machines
to continuously collect data such as temperature, vibration, pressure,
speed, and energy consumption.

Embedded controllers process the sensor information and transmit it to a
central monitoring platform. AI algorithms analyze the collected data to
identify abnormal machine behavior and predict potential failures.

Operators can monitor machine conditions in real time and take corrective
action before a breakdown occurs.

This reduces machine downtime, improves production efficiency, and helps
optimize energy consumption.

### Observation

The AI generates a complete response without requiring any examples.

## 2. FEW-SHOT PROMPTING

### Definition

Few-shot prompting provides examples to the AI model so that it can
understand the expected response pattern.

### Prompt

Example 1:

Input:
Machine temperature increases beyond the normal limit.

Output:
Generate an alert and inspect the machine for possible overheating.


Example 2:

Input:
Machine vibration increases continuously.

Output:
Predict possible equipment failure and schedule preventive maintenance.


Now answer:

Input:
Machine energy consumption suddenly increases.

### Expected AI Output

Output:

Generate an energy consumption alert, analyze the machine operating
conditions, and optimize the process or schedule maintenance if abnormal
energy consumption continues.

### Observation

Providing examples helps the AI understand the expected input-output
format and improves consistency.

## 3. CHAIN OF THOUGHT PROMPTING

### Definition

Chain of Thought prompting asks the AI to solve a problem through a logical
sequence of steps.

### Prompt

A manufacturing plant wants to reduce machine downtime using IoT and AI.
Explain step by step how the system can collect machine data, detect
abnormal behavior, predict failures, and schedule maintenance.

### Expected AI Output

Step 1:
Install IoT sensors on manufacturing machines.

Step 2:
Collect temperature, vibration, pressure, speed, and energy data.

Step 3:
Send the sensor data to an IoT gateway or monitoring platform.

Step 4:
Process and analyze the collected machine data.

Step 5:
Identify abnormal machine behavior.

Step 6:
Predict possible equipment failures.

Step 7:
Generate maintenance alerts.

Step 8:
Schedule preventive maintenance before machine failure.

Step 9:
Monitor the machine after maintenance.

Step 10:
Continuously improve the prediction system using new machine data.

### Observation

The response follows a logical sequence, making the solution easier to
understand and implement.

## 4. PERSONA PATTERN

### Definition

Persona prompting instructs the AI to respond from the perspective of a
specific person, professional, or expert.

### Prompt

You are an experienced Industrial IoT and automation engineer.

Explain how IoT, embedded controllers, and AI can be integrated to improve
manufacturing efficiency and predictive maintenance.

### Expected AI Output

As an experienced Industrial IoT engineer, I would integrate sensors,
embedded controllers, communication networks, and AI-based analytics into
the manufacturing environment.

Sensors collect real-time machine data such as temperature, vibration,
pressure, and energy consumption.

Embedded controllers process the data locally and communicate it to the
monitoring platform.

AI algorithms analyze historical and real-time data to detect abnormal
conditions and predict equipment failures.

This approach allows manufacturers to perform predictive maintenance,
reduce downtime, improve production efficiency, and optimize energy usage.

### Observation

The response reflects the perspective and expertise of an Industrial IoT
and automation professional.

## 5. REVERSE PROMPTING

### Prompt

The AI-generated response is:

"The system collects machine data through IoT sensors, analyzes vibration
and temperature patterns using AI, predicts possible equipment failures,
generates maintenance alerts, and allows engineers to monitor machines
remotely."

Generate the original prompt that could have produced this response.

### Expected AI Output

Design an IoT-based predictive maintenance system for a manufacturing
plant that uses sensors to collect machine data, AI to analyze vibration
and temperature patterns, and a remote monitoring platform to predict
equipment failures and generate maintenance alerts.

### Observation

Reverse prompting works backward from the desired output to generate
a suitable original prompt.

## 6. Graph Prompting

### Prompt

Represent the workflow of an IoT-based smart manufacturing system as
a flow diagram showing sensor data collection, processing, machine
monitoring, predictive maintenance, and production optimization.

### Expected AI Output
```Diagram
START
  |
  v
Install IoT Sensors
  |
  v
Collect Machine Data
  |
  v
Embedded Controller
  |
  v
Process Sensor Data
  |
  v
Analyze Machine Status
  |
  +----------------------+
  |                      |
  v                      v
Normal Status        Abnormal Status
  |                      |
  v                      v
Continue Production  Predict Failure
                         |
                         v
                  Generate Alert
                         |
                         v
                Schedule Maintenance
                         |
                         v
                  Optimize Production
                         |
                         v
                  Monitor Continuously
                         |
                         v
                        END

```


### Observation

Graph prompting represents the workflow visually and makes complex
processes easier to understand.


## 7. Active Prompting

### Prompt

Determine whether a manufacturing machine should continue operating
when abnormal vibration and high temperature are detected.

Ask relevant questions for any missing information before making
the final recommendation.

### Expected AI Output

Before making a recommendation, I need the following information:

1. What is the current machine temperature?
2. How high is the vibration compared with the normal range?
3. How long have the abnormal conditions been detected?
4. What type of machine is being monitored?
5. Is there any previous maintenance or failure history?
6. Is the machine currently performing a critical production operation?

Based on the answers, determine whether to continue operation,
reduce the machine load, generate a maintenance alert, or stop
the machine safely.

### Observation
Active prompting allows the AI to identify missing information and
ask questions before making a final decision.


<img width="840" height="457" alt="image" src="https://github.com/user-attachments/assets/240197c6-9f75-4c45-a5c0-07ea5a2adbdf" />

<img width="905" height="623" alt="image" src="https://github.com/user-attachments/assets/fcdb40f3-1079-477c-9eb0-c9fb11b46005" />

## Result Analysis

ChatGPT generated logical, accurate, and concise responses across the
different prompting techniques.

Google Gemini generated technically correct responses with good reasoning
and consistency.

Microsoft Copilot generated shorter responses suitable for quick
understanding but provided comparatively less detailed reasoning.


## Result

Thus, the various types of prompts were successfully executed, compared
across different AI tools, and evaluated using a rubric-based method.

The experiment demonstrated that selecting an appropriate prompting
technique can improve the quality, consistency, reasoning, and
effectiveness of AI-generated responses.

