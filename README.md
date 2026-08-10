<!--
**a-t-0/a-t-0** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.
-->

Hi there✨, feel free to read my prioritization🐣! Currently I work on:

<img width="1536" height="1024" alt="image" src="https://github.com/user-attachments/assets/c35a5857-22e2-4254-b43b-d6a86576c29b" />

### A. SelfPrivacy
- Making SelfPrivacy [self-hostable, for free over tor](https://github.com/orgs/selfprivacy-over-alternative-nets/repositories) (and https on your own domain).

### B. Hledger wrapper for self-hosted privacy friendly receipt parsing AIs
- Ensuring the [visualisation](https://hledger-flow-receipt-parsing-ai.github.io/hledger-preprocessor/) of the open source bookkeeping TUI that is built around hledger makes sense, is fully auto-generated and can be self-hosted on a `.git` of the above SelfPrivacy setup/onion.
- Setting up self-hosted, privacy, friendly AI's to parse receipt images so that they get embedded into your hledger setup.
- Ideally, I would like to set up collective training and/or inference of those receipt-image-parsing-AI modules using FHE.


<img width="1536" height="1024" alt="paralel" src="https://github.com/user-attachments/assets/28655082-84de-4e96-a9ac-e38143c4bf10" />

### A. CNC
- Using a tactile-sensing glove to train an open source humanoid/robot arm to build [the CNC](https://ergonomic-keyboard.github.io/DIY-3-axis-CNC-machine/) that is able to build itself (with that humanoid/robot).
- I am aware the open source CNC will probably not be able to build the hardware of the open source humanoid/robot.
- Note, I had a short scare of reinventing the wheel when I found [this](https://www.thehardwareguy.co.uk/diy-cnc-machine) open source cnc which already has a solid design. The main advantage of the [inspired](https://www.youtube.com/watch?v=RDnGvhdGFEY) cnc design is (material) cost/strength. Instead of having an aluminum gantry I expect a beamed-gantry with truss (albeit with (steel) wiring) could have the same strength at lower cost or increased strength at equal cost. However, for the cnc performance metrics I:
- Disregard:
  - speed [m/s] per materialtype as I aim at bootstrapping cnc creation, parallelization would come at cnc material costs if more speed is required, I doubt I will reach demand for volumes that require that.
  - Mean Time Between Failures [hours]
  - Mean Time To Repair [hours]
  - Availability [%]
  - Energy consumption [kWh]
 as I do not yet have enough experience in operating cnc's to form an opinion about the effort/reward.
- Value:
  - Axis travel / work envelope — mm (X × Y × Z travel)
  - Position Accuracy [mm]
  - Repeatability [mm]
  - Surface roughness [Ra in µm]
- Ideally I would like to see if I can mod/use the [Open Source](https://github.com/0x23/MicroManipulatorStepper) Motorized [XYZ Micro-Manipulator](https://www.youtube.com/watch?v=MgQbPdiuUTw) to increase the number of components that can be bootstrapped in the above cnc endeavor (thanks to the increased accuracy).

## B. Ergonomic Keyboard
- [High-quality](https://ergonomic-keyboard.github.io/wip/req-tracker.html), auto-generated and fabricated (with above CNC humanoid/robot arm combo), based on your own hand shape/[finger positioning](https://ergonomic-keyboard.github.io/wip/wizard.html). Just so I can do the above work with a proper keyboard 🤔

## C. [TruCol](https://trucol.io/protocol/)
- Out of principle I still like to build and deploy the TruCol protocol.

## D. [Decentralised Investment Protocol](https://github.com/TruCol/Decentralised-Venture-Capital-Protocol)
- To gain more experience with deployment and production ready fund management in adversarial environments.

Feel free to have a look or pick up a small subtask💫
