# The Debriefer Game

A voiced, game-style trainer for healthcare simulation educators. You play the facilitator after a simulation. You choose what to say, see how the team reacts, and Coach Nadia scores every move.

**Play:** open `index.html`, or the GitHub Pages link for this repository.

## What is inside

- Two debriefing frameworks, with 9 levels from low to high emotional intensity:
  - **PEARLS** (Promoting Excellence And Reflective Learning in Simulation): The Quiet Slide, The Tenfold Dose, No Return, The Last Word
  - **GAS** (Gather, Analyze, Summarize): The Sleepy Patient, Silent Chest, The Hidden Cause, Visiting Hours, Small Hands
- Advanced levels with a simulated participant (SP) in the room:
  - **The Last Word** (PEARLS 4): debriefing a death notification. SPIKES, GRIEV_ING, NURSE statements, structured SP feedback, facilitator self-care.
  - **Visiting Hours** (GAS 4): debriefing an angry family member. De-escalation, when to call security, the system gap behind the anger, disclosure and apology.
  - **Small Hands** (GAS 5): debriefing infant septic shock with the mother present. IO access, fluid and antibiotic timing, family presence during resuscitation.
- A video intro for each framework
- A demo mode (Level 1 of each framework, nothing saved) and free local accounts
- Score 90 or more on a level to unlock the next one
- Four facilitator vitals: psychological safety, strategy fit, learning depth, cognitive load management
- A report card after each level, phase by phase, in PEARLS or GAS terms
- Strategy Sprint: a timed drill that matches debrief moments to the right strategy
- Recorded neural voices for every character, plus sound effects

## For instructors

Students press **Send results to instructor** to download a signed results file (`.json`). They email or upload it to you. Import the files into the Debriefer Instructor Dashboard to see class progress and print PDF reports.

Accounts and progress are saved in each student's own browser. The results file also restores a student's progress on another device.

## Files

| File | Purpose |
| --- | --- |
| `index.html` | The whole game: styles, cases, engine |
| `voice-*.mp3` | Recorded voice lines, one file per level plus shared lines |
| `pearls-intro.*`, `gas-intro.*` | Framework intro videos (WebM and MP4) |
| `.nojekyll` | Tells GitHub Pages to serve files as they are |

## Credits

- Structure: PEARLS Healthcare Debriefing Tool (Bajaj, Meguerdichian, Thoma, Huang, Eppich, Cheng. Acad Med 2018) and Eppich and Cheng, Simul Healthc 2015. GAS debriefing model from WISER and the American Heart Association.
- Micro-skills informed by The Debriefing Academy InfoQuips.
- Advanced case evidence:
  - SPIKES (Baile et al., Oncologist 2000)
  - GRIEV_ING (Hobgood et al., Acad Emerg Med 2005)
  - VitalTalk NURSE statements
  - Canadian Disclosure Guidelines and the BC Apology Act
  - ENA Family Presence clinical practice guideline
  - Surviving Sepsis Campaign paediatric guidelines 2020
  - AHA PALS
  - ASPE Standards of Best Practice 2017
  - INACSL Healthcare Simulation Standards (Prebriefing, Debriefing)
- Voices: Kokoro-82M text-to-speech (Apache-2.0).
- Portraits: AI-generated fictional people. All cases and characters are fictional.

Created by Ferooz Sekandarpoor, BrainNet Consulting Inc. (simadvice.com).
