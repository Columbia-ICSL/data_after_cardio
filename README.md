# Reading and Speech Data from a Pilot Study

## Overview
Talking or reading after exercise differs from regular, daily communication. People may struggle to control their breath, making it difficult to pause sentences appropriately. The breathing patterns during post-exercise talking and reading can lead to different semantic breaks and breath pauses. Therefore, we conducted this pilot study where participants read and spoke after a cardio workout.

### Experiment Procedure

Every participant will wear a sport watch and a respiration belt. Each subject were asked to complete a few separate running sessions at constant speeds of 5, 6, 7, 8, 9, and/or 10 miles per hour (mph)based on their running expertise. Each running session lasts for 5 minutes to reach different exertion level. We will provide the following physical exertion scale to participants and inform them that they are not required higher physical exertion than the “moderate” range. After each running session, the participants are asked to read a paragraph and spontaneosly describe *their feeling afrer running* or *how's their day*. The reading and speaking audio is collected.

*Exertion Level Definition*:
- Very light: Anything other than complete rest.
- Light: Feels like you can maintain for hours, easy to breathe and carry on a conversation.
- Moderate: Feels like you can exercise for long periods of time, able to talk, and hold short conversations.
- Vigorous: On the verge of becoming uncomfortable, short of breath, can speak a sentence.
- Very hard: Difficult to maintain exercise intensity, hard to speak more than a single word.
- Max effort: Feels impossible to continue, completely out of breath, unable to talk.

**No Personally Identifiable Information (PII) information is collected in this study. All participants are assigned with a random SESSION_ID in each experiment session. Same participant will have different SESSION_IDs in differenct experiemnt session.**

### Other Details

**Participants**: Adult (ages from 19-37) lab memembers, study investigators, and their friends who are interested in this study.
**Device Usage in Different Modules**:

Module | Device
--- | ---
Audio | Voice Memos App on iPhone 
Respiration | Vernier Go Direct respiration belt (https://www.vernier.com/product/go-direct-respiration-belt/) 
Heart Rate | Garmin/Coros watch in Yoga Mode


## Files
*NOTE*: files in **audio**, **watch**, and **respiration_belt** are synced by human annotators (starting at the same time). 


### audio
Readig, talking, and deep breath audio.

### watch 
Timestamped heart rate.

### respiration_belt 
Timestamped Force(N) and Respiration Rate(bpm).

### general_information.csv
The content in general_information.csv includes:
1. **Session Name**: naming in the format of "SESSION_ID\_SPEED\_SESSION NUMBER\_clip\_TASK". SPEED is in [5, 6, 7, 8, 9, 10] (mph). TASK is in [1: read a paragraph; 2: deep breath; 3: spontaneous speech].
2. **Demographic**: Age, Gender, Weight (kg), Height (cm)
3. **Running Related Questions**:
- Are you a professional or semi-professional athlete?
- How often do you exercise a week?
- How many hours in total do you exercise during a week?
- What kind of sports do you usually do?,Do you have any expertise in running?
- How many times do you run during a week?
- How many kilometers on average do you run in total each week? (in km, a rough estimate would be fine)
- What is the longest distance you ran (in km)? (If you don't know, please put N.A..)
- And how long did your longest distance take (in minutes)? (If you don't know, please put N.A..)


### Contact
Please contact jn2551@columbia.edu if you have further questions about this pilot study data.