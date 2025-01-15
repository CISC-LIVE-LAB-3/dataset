# Human-in-the-Loop Decision Support in Process Control Rooms Dataset

## Overview
This repository contains a comprehensive dataset to assess cognitive states, workload, situational awareness, stress, and performance in human-in-the-loop process control rooms. The dataset includes objective and subjective measures from various data collection tools such as NASA-TLX, SART, eye tracking, EEG, Health Monitoring Watch, surveys, and think-aloud situational awareness assessments. It is based on an experimental study of a formaldehyde production plant based on participants' interactions in a controlled control room experimental setting.

## Purpose
The study compared three different setups of human system interfaces in four human-in-the-loop (HITL) configurations, incorporating two alarm design formats (Prioritised vs non-prioritised) and three procedural guidance setups (e.g. one presenting paper procedures, one offering digitised screen-based procedures, and lastly an AI-based procedural guidance system). 

## Key Features
- **Subject Area:** Chemical Engineering, Control and Safety Engineering, Human Factors and Ergonomics, Human-Computer Interaction, and Artificial Intelligence
- **Data Format:** Raw, Analyzed, Filtered
- **Type of Data:** CSV File (.csv), Matlab File (.mat), Excel (.xlsx), Table
- **Data Collection:** The dataset contains behavioural, cognitive, and performance data from 92 participants, including system data under each participant from three scenarios, each simulating a typical control room monitoring, alarm handling, planning, and intervention tasks and subtasks. The participants consented to participate on the test day, after which the researchers trained them. They performed tasks under three scenarios, each lasting 15 - 18 minutes. During these tests, the participant wore a watch for health monitoring, including an eye tracker. They were asked situational awareness questions based on the SPAM methodology at specific periods within 15 minutes, especially at the 6th, 8th, and 12th minutes. These questions assessed the three levels of situational awareness: perception, comprehension, and projection. This feedback collection process on situational awareness differed for one of the groups that used an AI-based decision support system. The question for this group was asked right after specific actions. Therefore, for the overall study, the following performance-shaping factors are considered: type of decision support system (alarm display design, procedure format, AI support, interface design), communication, situational awareness, cognitive workload, experience/training, task complexity, and stress. In both cases, communication was excluded as a factor considered in the first and second scenarios based on this absence. The data collected was normalized using the Min-Max normalization.

## Potential Applications
The dataset provides an opportunity for various applications, including:
- Developing human performance models and process safety models
- Developing a digital twin simulating human-machine interaction in process control rooms
- Optimizing human-AI interaction in safety-critical industries
- Qualifying and quantifying the performance and effectiveness of AI-enhanced decision support systems incorporating Deep Reinforcement Learning (DRL) using a Specialized Reinforcement Learning Agent (SRLA) framework
- Validating proposed solutions for the industry

## Usage
The dataset is instrumental for researchers, decision-makers, system engineers, human factor engineers, and teams developing guidelines and standards. It is also applicable for validating proposed solutions for the industry and for researchers in similar or close domains.

# Data Structure
The concatenated Excel file for the dataset may include the following detailed data:

1. **Demographic and Educational Background Data:**
   - Participant Identifier: A unique alphanumeric code assigned to each participant.
   - Age: The age of each participant at the time of the experiment.
   - Gender: The gender of each participant, typically categorized as male, female, or other.
   - Educational Background: Details of participants' academic qualifications, including degree type (e.g., Masters, PhD), year of study, and field of study (e.g., Chemical Engineering, IT).
   - Dominant Hand: Information on whether participants are right or left-handed, which could influence their interaction with the simulation interface.
   - Familiarity with Industry and Control Room: Self-reported familiarity levels with the industry in general and control room environments specifically, on a scale from 1 to 5.

2. **SPAM Metrics:**
   - Participant Identifier: Unique codes for participants (e.g., P04, P06).
   - Group Assignment: Indicates the experimental group (e.g., G4, G3, G2, G1) to which participants belonged, reflecting different levels of decision support in the simulation.
   - Scenario Engagement: Identifies the specific scenarios (e.g., S1, S2, S3) each participant encountered, representing diverse challenges within the control room simulation.
   - SPAM Metrics: Participant ratings across three dimensions of the SPAM questionnaire - Perception, Understanding, and Projection, on a scale typically from 1 to 5.
   - SPAM Index: Composite scores derived from the SPAM, indicating overall situation awareness levels experienced by participants. Calculated as the average of the score on perception, understanding and projection.

3. **NASA-TLX Responses:**
   - Participant Identifier: A unique alphanumeric code assigned to each participant.
   - Group Assignment: Indicates the experimental group (e.g., G1) to which participants were assigned, reflecting different levels of decision support in the simulation.
   - TLX Ratings: Participants' responses utilizing the NASA Task Load Index (NASA TLX) questionnaire, providing insights into the cognitive, physical, and emotional workload experienced by operators in simulated control room scenarios.
   - TLX Index: Composite scores derived from the NASA TLX, representing the overall workload experienced by the participant, calculated as an average of the ratings across the six dimensions.

4. **SART Data:**
   - Participant Identifier: Unique codes for participants (e.g., P04, P06).
   - Group Assignment: Indicates the experimental group (e.g., G1) to which participants belonged, reflecting different levels of decision support in the simulation.
   - SART Metrics: Participants' responses to the Situation Awareness Rating Technique (SART) questionnaire, capturing metrics reflecting the participants' situation awareness. It is calculated using the equation U - (D - S). Situation Understanding (U) comprises 
     Information Quantity, Information Quality, and Familiarity. Situation demand (D) includes the situation's Instability, Complexity, and Variability. At the same time, the Supply of attentional resources (S) comprises Arousal, Concentration, Division of Attention, 
     and Spare Capacity.

5. **AI Decision Support System Feedback:**
   - Participant Identifier: A unique alphanumeric code assigned to each participant.
   - AI System Ratings: Participants' feedback and ratings across different aspects of the AI decision support system, such as support, explainability, and trust, providing insights into the system's perceived strengths and areas for improvement.
   - Workload Impact Data: Information on the workload impact and the balance between AI benefits and additional workload, offering valuable perspectives on the practicality and efficiency of integrating AI systems in control room operations.
   - DRL (Deep Reinforcement Learning) Role: Emphasis on the importance of validating AI recommendations and the role of Deep Reinforcement Learning (DRL) in enhancing trust.

6. **Performance Metrics:**
   - Participant Identifier: A unique alphanumeric code assigned to each participant.
   - Scenario Engagement: Details of the specific scenario (e.g., S1, S2, S3) each participant encountered, representing various challenges in the control room environment.
   - Task-Specific Performance Measures: Data capturing the participants' experiences and performance across different scenarios in a control room simulation, including task-specific performance measures and outcomes related to decision-making processes in safety- 
     critical environments.

This detailed breakdown provides a comprehensive view of the specific data elements that could be included in the concatenated Excel file, allowing for thorough analysis and exploration of the participants' experiences, cognitive states, workload, and decision-making processes in control room environments.

## Citation
Please cite the article if you use this dataset in your research or publication.
