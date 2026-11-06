## Demo

<video src="https://github.com/ojas-ba/metro-station-crowd-evacuation/raw/refs/heads/main/Screen-Recording-Final.mp4" controls width="100%" preload="metadata">
  <a href="Screen-Recording-Final.mp4">Watch the demo (MP4)</a>
</video>

# Metro Station Crowd Evacuation Simulation Using Unity and Virtual Reality

**Case study author:** Ojas B A  
**USN:** 1RVU23CSE321  
**Course:** CS4104 - Computer Graphics and Virtual Reality  
**Institution:** RV University, Bengaluru  
**Academic year:** 2026-27

## Overview

This case study explores how autonomous passengers could evacuate a metro station using Unity. It explains agent behaviour, route planning, local obstacle avoidance and responses to a blocked exit, with a proposed virtual reality extension for training.

The repository includes an existing Unity crowd simulation, a demo recording and the case study report. The metro station layout, explicit exit selection and closure handling, VR interactions and evaluation metrics described in the report are proposed extensions, rather than verified features of the demo. No new execution or measured performance results are claimed.

## Simulation approach

- Reusable agents combine movement, behaviour management and sensing.
- NavMesh navigation provides routes through walkable areas.
- JSON files configure agent behaviour.
- The proposed metro scenario uses two exits, varied passenger responses and replanning when an exit becomes unavailable.
- The proposed VR extension adds a tracked headset view, spatial audio and controller feedback.

## Project files

- `Assets/` - scripts, models, prefabs and scenes, including `Assets/Scenes/Evacuation/evac.unity`.
- `Packages/` and `ProjectSettings/` - Unity configuration.
- [Project report](CS4104_Metro_Crowd_Evacuation_Report_Updated.docx) - full case study, design and evaluation plan.
- [Demo recording](Screen-Recording-Final.mp4) - the video shown above.

**Unity version:** 2020.3.30f1, as recorded in the project settings.

## Source and license

The included Unity example is based on the [Generic Crowd Simulation Engine](https://github.com/ashmoreinc/Generic-Crowd-Simulation-Engine). See the existing [GNU GPL v3 license](LICENSE).
