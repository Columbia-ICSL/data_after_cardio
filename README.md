# Multi-Modal Dataset Across Exertion Levels: Capturing Post-Exercise Speech, Breathing, and Phonocardiogram

## Overview

Cardio exercise elevates heart and respiration rates, leading to physiological changes that affect speech patterns, breathing sounds, and heart sounds. A comprehensive dataset is needed to capture these variations, including speech disfluencies, altered breathing patterns, and variable heart sound intensities, which are crucial for improving model generalizability to post-exercise conditions.

We collected a dataset from 59 subjects performing cardio exercise, specifically running, at varied exertion levels. The dataset comprises 250 sessions, including 143 minutes of structured reading, 47 minutes of spontaneous speech, 71 minutes of breathing sounds, and 62.5 minutes of phonocardiogram (PCG) recordings. This dataset serves as a foundational resource for speech and cardiorespiratory monitoring, enabling advancements in natural language processing (NLP), mobile health, and wearable sensing technologies.

### Experiment Procedure

Every participant will wear a sport watch and a respiration belt. Each subject were asked to complete a few separate running sessions at constant speeds of 5, 6, 7, 8, 9, and/or 10 miles per hour (mph)based on their running expertise. Each running session lasts for 5 minutes to reach different exertion level. We will provide the following physical exertion scale to participants and inform them that they are not required higher physical exertion than the “moderate” range. After each running session, the participants are asked to read a paragraph and spontaneosly describe _their feeling afrer running_ or _how's their day_. The reading, speaking, and breathing audio is collected.

_Exertion Level Definition_:

- Very light: Anything other than complete rest.
- Light: Feels like you can maintain for hours, easy to breathe and carry on a conversation.
- Moderate: Feels like you can exercise for long periods of time, able to talk, and hold short conversations.
- Vigorous: On the verge of becoming uncomfortable, short of breath, can speak a sentence.
- Very hard: Difficult to maintain exercise intensity, hard to speak more than a single word.
- Max effort: Feels impossible to continue, completely out of breath, unable to talk.

**No Personally Identifiable Information (PII) information is collected in this study. All participants are assigned with a random PARTICIPANT_ID (e.g., P01). Experiment sessions are encoded with a random SESSION_ID (e.g., d01). Same participant will have the same PARTICIPANT_ID in differenct experiemnt session.**

### Other Details

**Participants**: 59 adult (ages from 19-65) subjects recruited from diverse demographic distributions. This research
received approval from the Institutional Review Board (IRB). Informed consent was obtained from all participants
before their involvement in the study.

**Device Usage in Different Modules**:

| Module                | Device                                                                                           |
| --------------------- | ------------------------------------------------------------------------------------------------ |
| Audio                 | Voice Memos App on iPhone                                                                        |
| Respiration           | Vernier Go Direct respiration belt (https://www.vernier.com/product/go-direct-respiration-belt/) |
| Heart Rate            | Garmin/Coros watch in Yoga Mode                                                                  |
| Phonocardiogram (PCG) | 3M Littmann CORE Digital Stethoscope                                                             |

## Files

_NOTE_: files in **audio**, **watch**, and **respiration_belt** are synced by human annotators (starting at the same time).

### audio

Readig, talking, and deep breath audio.

### watch

Timestamped heart rate.

### respiration_belt

Timestamped Force(N) and Respiration Rate(bpm).

### pcg

15 second PCG audio directly after exercise.

_Note that a running session is linked to a single PCG file but may have one or more associated audio, watch, or respiration belt files, depending on the tasks._

### general_information.csv

The content in general_information.csv includes:

1. **Session Name**: naming in the format of "SESSION_ID_PARTICIPANT_ID_SPEED_SESSION NUMBER_clip_TASK". SPEED is in [5, 6, 7, 8, 9, 10] (mph). TASK is in [1: read a paragraph; 2: deep breath; 3: spontaneous speech].
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

## Citation

```
@inproceedings{nie2025multi,
  title={Multi-Modal Dataset Across Exertion Levels: Capturing Post-Exercise Speech, Breathing, and Phonocardiogram},
  author={Nie, Jingping and Fan, Yuang and Zhao, Minghui and Wan, Runxi and Xuan, Ziyi and Preindl, Matthias and Jiang, Xiaofan},
  booktitle={Proc. Proceedings of ACM Conference on Embedded Networked Sensor Systems (SenSys'25)},
  year={2025}
}
```

### Contact

Please contact jn2551@columbia.edu if you have further questions about this pilot study data.
