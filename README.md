# Open Design and Technology  
## Final Project README

> **Project Weight:** 70%  
> **Team Size:** 2 students  
> **Project Duration:** 4 weeks  
> **Class Time Available:** 6 hours per class  
> **Total Time Available:** 48 effort-hours per team  
> **Project Type:** Playful, interactive, technology-based experience

---

# Before you begin

## Fork and rename this repository
After forking this repository, rename it using the format:

`ODT-2026-TeamName`

### Example
`ODT-2026-PixelWizards`

Do not keep the default repository name.

---

# How to use this README

This file is your team’s **working project document**.

You must keep updating it throughout the 4-week build period.  
By the final review, this README should clearly show:
- your idea,
- your planning,
- your design decisions,
- your technical process,
- your build progress,
- your testing,
- your failures and changes,
- your final outcome.

## Rules
- Fill every section.
- Do not delete headings.
- If something does not apply, write `Not applicable` and explain why.
- Add images, screenshots, sketches, links, and videos wherever useful.
- Update task status and weekly logs regularly.
- Use this file as evidence of process, not only as a final report.

---

# 1. Team Identity

## 1.1 Studio / Group Name
`[Enter your group name]`

## 1.2 Team Members

| Name | Primary Role | Secondary Role | Strengths Brought to the Project |
|---|---|---|---|
| `Devshi Barman` | `[Electronics / Coding / App / Fabrication / Mechanics]` | `[Role]` | `[Write here]` |
| `Samarth Saluja` | `[Electronics / Coding / App / Fabrication / Mechanics]` | `[Role]` | `[Write here]` |

## 1.3 Project Title
`Connect 4`

## 1.4 One-Line Pitch
`A responsive, light-based Connect 4 where glowing pixels fall, react, and celebrate each move, turning a classic game into an interactive visual experience.`

## 1.5 Expanded Project Idea
In 1–2 paragraphs, explain:
- what your project is,
- what kind of playful experience it creates,
- what makes it fun, curious, engaging, strange, satisfying, competitive, or delightful,
- what technologies are involved.

**Response:**  
`This project is an interactive, light-based reimagining of Connect 4, built as a physical installation using an ESP32-controlled LED grid. Instead of static tokens, each move is visualized through glowing pixels that animate as they “fall” into place, creating a dynamic and responsive board. Players take turns from the same side, selecting columns via buttons, while the system updates in real time with color-coded feedback for each player. The board itself is designed as a diffused light surface, making each cell appear soft and luminous rather than harsh or digital.
The experience is playful and engaging because it transforms a familiar game into something more alive and sensory. The falling animation builds anticipation, the shifting colors make each turn visually distinct, and the moment of winning is amplified through light highlights and sound/music feedback.The project combines simple game logic with embedded electronics, using an ESP32, WS2812 LED strips, push-button inputs, and a buzzer, integrating code, material, and interaction design into a cohesive, responsive model.`

---

# 2. Philosophy Fit

## 2.1 Experience, Not Social Problem
This module does **not** require your project to solve a large social problem.

You are allowed to build:
- toys,
- games,
- interactive objects,
- playful machines,
- kinetic artifacts,
- humorous devices,
- strange but delightful experiences,
- things that are entertaining to use or watch.

## 2.2 What kind of experience are you creating?
Answer the following:
- What is the experience?
- What do you want the player or participant to feel?
- Why would someone want to try it again?

**Response:**  
`The experience is a tactile, light-driven reinterpretation of Connect 4, where players interact with a responsive surface instead of physical tokens. By touching a column, they trigger a glowing piece that “falls” through the grid, creating a real-time visual animation.
Each move builds tension in the players' mind as the light descends, while the soft glow and color shifts create a sense of immersion. There is also a subtle satisfaction in seeing cause and effect unfold instantly, touch leading to motion—making the interaction feel intuitive and responsive.
The experience invites repetition through its balance of familiarity and variation.The immediacy of interaction and the visual reward system encourage players to replay, experiment with moves, and engage both competitively and playfully.`

## 2.3 Design Persona
Complete the sentence below:

> We are designing this project as if we are a small creative studio making a **[toy / game / playable object / interactive experience]** for **[children / teens / adults / classmates / exhibition visitors / mixed audience]**.

**Response:**  
`We are designing this project as if we are a small creative studio making a **playable object / interactive light-based game** for a **mixed audience of classmates and exhibition visitors.`

---

# 3. Inspiration

## 3.1 References
List what inspired the project.

| Source Type | Title / Link | What Inspired You |
|---|---|---|
| `[Toy / Board game / App / Video / Website / Object]` | `[Link or title]` | `[What did you learn or borrow?]` |
| `[Toy / Board game / App / Video / Website / Object]` | `[Link or title]` | `[What did you learn or borrow?]` |
| `[Toy / Board game / App / Video / Website / Object]` | `[Link or title]` | `[What did you learn or borrow?]` |

## 3.2 Original Twist
What makes your project original?

**Response:**  
`What makes our project original is the translation of a familiar, static board game into a dynamic, physical-digital experience. 
Instead of static pieces, moves are expressed through LED animations, touch input, and sound, making each action dynamic and engaging. The use of paired LEDs as “light pixels” and the falling animation adds a unique visual language. It shifts the game from something you simply play to something you physically interact with and experience.
To put it together, the originality lies not in reinventing the rules of the game, but in redesigning how the game is felt, seen, and experienced through interaction.`

---

# 4. Project Intent

## 4.1 Core Interaction Loop
Describe the main loop of interaction.

Examples:
- press → launch → score → reset
- connect → control → observe → repeat
- turn → trigger → react → repeat
- move object → sensor detects → sound/light response → player reacts

**Response:**  
`user input (touch) → system response (animated LED drop) → visual state update → turn transition → next input`

## 4.2 Intended Player / Audience

| Question | Response |
|---|---|
| Who is this for? | `Anyone who enjoys playful, interactive games and engaging with light-based experiences` |
| Age range | `10+ (teens to adults)` |
| Solo or multiplayer | `Multiplayer (2 players)` |
| Expected duration of one round | `2-5 Minutes` |
| What should the player feel? | `Focused, engaged, and responsive to the rhythm of play` |
| Is explanation required before use? | `Minimal but basic game rules may need a quick explanation` |

## 4.3 Player Journey
Describe exactly how a player will use the project.

1. **Approach:** `The player notices a  glowing grid that invites interaction through light rather than physical pieces.`
2. **Start:** `The system is already active; players understand they can begin by interacting with the surface.`
3. **First Action:** `The player touches one of the coloumn to make their move.`
4. **Main Interaction:** `Players take turns selecting columns, building their positions while observing the evolving pattern of lights.`
5. **System Response:** `The board responds instantly, lighting up a colored piece that animates as it “falls” into place, with subtle sound feedback reinforcing each move.`
6. **Win / Lose / End Condition:** `A round ends when a player connects four pieces, highlighted through a distinct light animation and sound, or when the board fills up.`
7. **Reset:** `After a short end animation, the board clears itself and returns to its initial state, ready for the next round.`

## 4.4 Rules of Play
If your project is a game, list the rules clearly.

- `A player can select only one column per turn; multiple inputs are not allowed, and the turn passes after a single move is made.`
- `Once a move is made and the piece is placed, it cannot be undone or changed.`
- `The win only counts if the four pieces of the same color are connected in a row, either horizontally, vertically, or diagonally.`
  

---

# 5. Definition of Success

## 5.1 Definition of “Playable”
Your project will be considered complete only if these conditions are met.

- [ ] `[Condition 1]`
- [ ] `[Condition 2]`
- [ ] `[Condition 3]`
- [ ] `[Condition 4]`
- [ ] `[Condition 5]`

## 5.2 Minimum Viable Version
What is the smallest version of this project that still delivers the core experience?

**Response:**  
`The smallest version of this project that still preserves the core experience is a 3 × 3 grid (Connect 3) with three input columns, simple LED feedback, two-player turn-taking, and basic win detection. 
This scaled-down version retains the essential interaction; players choose a column, a piece drops, the system updates, and a win condition is checked, creating a clear loop of action and response`

## 5.3 Stretch Features
What features are nice to have but not essential?

- `Sound feedback using a buzzer for piece drops and win events`
- `Animated LED fall transitions instead of instant lighting`
- `Reset animation or visual play when the game restarts`

---

# 6. System Overview

## 6.1 Project Type
Check all that apply.

- [check] Electronics-based
- [ ] Mechanical
- [check] Sensor-based
- [ ] App-connected
- [ ] Motorized
- [check] Sound-based
- [check] Light-based
- [ ] Screen/UI-based
- [check] Fabricated structure
- [check] Game logic based
- [check] Installation / tabletop experience
- [ ] Other: `[Write here]`

## 6.2 High-Level System Description
Explain how the system works in simple terms.

Include:
- input,
- processing,
- output,
- physical structure,
- app interaction if any.

**Response:**  
`The system is a compact, self-contained physical game built around touch input, simple game logic, and responsive feedback. Players interact using capacitive touch sensors mapped to each column of the grid. Each touch acts as a clear input, allowing the player to choose where their piece should be placed. The interaction is designed to feel immediate and intuitive, requiring no additional interface or instructions.
Once an input is received, the microcontroller processes it in real time. It handles turn-taking between two players, determines how the piece “falls” within the column, updates the internal game state, and continuously checks for win conditions. 
This layer of logic ensures that the game flows smoothly and enforces the rules without any manual intervention.
The output is delivered through an LED grid that visualizes the falling pieces and game state, along with a buzzer for basic sound feedback.
All components are integrated into a fabricated tabletop structure that holds the LED grid, sensors, and circuitry in a stable and accessible form. The system does not rely on any external app or screen, the entire experience is physical, direct, and designed to be understood through interaction alone.`

## 6.3 Input / Output Map

| System Part | Type | What It Does |
|---|---|---|
| `Capacitive Touch Sensors (6 columns)` | Input | `Detect player touch and map it to a specific column selection` |
| `ESP32 Microcontroller` | Processing | `Handles turn logic, piece placement, game state updates, and win detection` |
| `LED Grid` | Output | `Visually represents the board, player moves, and game progression using color` |
| `Buzzer` | Output | `Provides sound feedback for actions like piece drop and win events` |
| `Fabricated Game Structure` | Physical Action | `Holds and organizes all components into a stable, playable tabletop form` |

---

# 7. Sketches and Visual Planning

## 7.1 Concept Sketch
Add an early sketch of the full idea.

**Insert image below:**  
`[Upload image and link here]`

Example:
```md

```

## 7.2 Labeled Build Sketch
Add a sketch with labels showing:
- structure,
- electronics placement,
- user touch points,
- moving parts,
- output elements.

**Insert image below:**  
`[Upload image and link here]`

## 7.3 Approximate Dimensions

| Dimension | Value |
|---|---|
| Length | `[Write here]` |
| Width | `[Write here]` |
| Height | `[Write here]` |
| Estimated weight | `[Write here]` |

---

# 8. Mechanical Planning

## 8.1 Mechanical Features
Check all that apply.

- [ ] Gears
- [ ] Pulleys
- [ ] Belt drives
- [ ] Linkages
- [ ] Hinges
- [ ] Shafts
- [ ] Springs
- [ ] Bearings
- [ ] Wheels
- [ ] Sliders
- [ ] Levers
- [check] Not applicable

## 8.2 Mechanical Description
Describe the mechanism and what it is meant to do.

**Response:**  
`The system does not rely on any active mechanical mechanisms for movement or transformation. Instead, it is built as a static fabricated structure designed to support and organize the electronic components.
Rather, the physical build organizes the LED grid for clear readability and places the touch sensors for easy access. It maintains stability, spacing, and alignment so the interaction feels precise and consistent. Any “movement,” like pieces falling, is simulated through LEDs rather than physical mechanisms.`

## 8.3 Motion Planning
If something moves, explain:
- what moves,
- what causes the movement,
- how far it moves,
- how fast it moves,
- what could go wrong.

**Response:**  
`There is no physical movement in the system; all motion is simulated through LED behavior.
Led Motions includes the “moving” element is the visual representation of a game piece falling down a column. This is triggered by a player’s touch input, after which the microcontroller updates the LEDs sequentially to mimic downward motion.
Since the motion is digital, potential issues include delayed input detection, inconsistent LED updates, or timing glitches that may disrupt the illusion of smooth movement.`

## 8.4 Simulation / CAD / Animation Before Making
If your project includes mechanical motion, document the digital planning before fabrication.

| Tool Used | File / Link | What Was Tested |
|---|---|---|
| `N/A` | `N/A` | `N/A` |
| `N/A` | `N/A` | `N/A` |

## 8.5 Changes After Digital Testing
What changed after the CAD, animation, or simulation stage?

**Response:**  
`N/A`

---

# 9. Electronics Planning

## 9.1 Electronics Used

| Component | Quantity | Purpose |
|---|---:|---|
| `[ESP32]` | `1` | `Main controller handling input, logic, and output` |
| `LED Strip` | `1` | `Creates the visual game grid and displays player moves` |
| `Capacitive Touch Sensors (GPIO touch pins)` | `6` | `Detect player input for each colum` |
| `Buzzer` | `1` | `Provides sound feedback for actions and win events` |
| `Resistors / Connecting Wires` | `Around 40` | `Ensure stable connections and circuit integrity` |
| `Power Supply` | `1` | `Powers the entire system` |

## 9.2 Wiring Plan
Describe the main electrical connections.

**Response:**  
`Power Distribution
The ESP32 is powered via a 5V USB supply. The same power source is used to drive the LED strip, ensuring consistent brightness across the grid. A common ground is maintained between all components (ESP32, LEDs, buzzer, and touch inputs) to ensure stable signal flow and prevent noise issues.
LED Connections
The NeoPixel LED strip is connected to a single digital output pin on the ESP32. This pin sends data signals that control the color and state of each LED in the grid. The strip receives 5V power and ground directly, while the data line is optionally passed through a resistor to stabilize the signal.
Touch Input Connections
Each column is mapped to a dedicated capacitive touch pin on the ESP32. No external wiring is required beyond connecting conductive pads or wires to the touch pins, making the input system minimal
Buzzer Connection
The buzzer is connected to a digital output pin on the ESP32. The buzzer shares the common ground with the rest of the system.
All components are wired back to the ESP32, which acts as the central hub.`

## 9.3 Circuit Diagram
Insert a hand-drawn or software-made circuit diagram.

**Insert image below:**  
`[Upload image and link here]`

## 9.4 Power Plan

| Question | Response |
|---|---|
| Power source | `[USB / battery / adapter / other]` |
| Voltage required | `[Write here]` |
| Current concerns | `[Write here]` |
| Safety concerns | `[Write here]` |

---

# 10. Software Planning

## 10.1 Software Tools

| Tool / Platform | Purpose |
|---|---|
| `[MicroPython / Arduino / MIT App Inventor / CAD tool / other]` | `[Purpose]` |
| `[Tool]` | `[Purpose]` |

## 10.2 Software Logic
Describe what the code must do.

Include:
- startup behavior,
- input handling,
- sensor reading,
- decision logic,
- output behavior,
- communication logic,
- reset behavior.

**Response:**  
`[Write here]`

## 10.3 Code Flowchart
Insert a flowchart showing your code logic.

Suggested sequence:
- start,
- initialize,
- wait for input,
- read input,
- decision,
- trigger output,
- repeat or reset,
- error handling.

**Insert image below:**  
`[Upload image and link here]`

## 10.4 Pseudocode

```text
[Write your pseudocode here]
```

---

# 11. MIT App Inventor Plan

## 11.1 Is an app part of this project?
- [ ] Yes
- [ ] No

If yes, complete this section.

## 11.2 Why is the app needed?
Explain what the app adds to the experience.

Examples:
- remote control,
- score tracking,
- mode selection,
- personalization,
- triggering effects,
- displaying data.

**Response:**  
`[Write here]`

## 11.3 App Features

| Feature | Purpose |
|---|---|
| `[Bluetooth connect button]` | `[Purpose]` |
| `[Score display]` | `[Purpose]` |
| `[Control button / slider / label]` | `[Purpose]` |

## 11.4 UI Mockup
Insert a sketch or screenshot of the app interface.

**Insert image below:**  
`[Upload image and link here]`

## 11.5 App Screen Flow

1. `[Step 1]`
2. `[Step 2]`
3. `[Step 3]`
4. `[Step 4]`

---

# 12. Bill of Materials

## 12.1 Full BOM

| Item | Quantity | In Kit? | Need to Buy? | Estimated Cost | Material / Spec | Why This Choice? |
|---|---:|---|---|---:|---|---|
| `[ESP32]` | `1` | `Yes` | `No` | `0` | `[Spec]` | `[Reason]` |
| `[Item]` | `[Qty]` | `[Yes/No]` | `[Yes/No]` | `[Cost]` | `[Spec]` | `[Reason]` |
| `[Item]` | `[Qty]` | `[Yes/No]` | `[Yes/No]` | `[Cost]` | `[Spec]` | `[Reason]` |

## 12.2 Material Justification
Explain why you selected your main materials and components.

Examples:
- Why acrylic instead of cardboard?
- Why MDF instead of 3D print?
- Why servo instead of DC motor?
- Why bearing instead of a plain shaft hole?

**Response:**  
`[Write here]`

## 12.3 Items to Purchase Separately

| Item | Why Needed | Purchase Link | Latest Safe Date to Procure | Status |
|---|---|---|---|---|
| `[Item]` | `[Reason]` | `[Link]` | `[Date]` | `[Pending / Ordered / Received]` |
| `[Item]` | `[Reason]` | `[Link]` | `[Date]` | `[Pending / Ordered / Received]` |

## 12.4 Budget Summary

| Budget Item | Estimated Cost |
|---|---:|
| Electronics | `[Cost]` |
| Mechanical parts | `[Cost]` |
| Fabrication materials | `[Cost]` |
| Purchased extras | `[Cost]` |
| Contingency | `[Cost]` |
| **Total** | `[Cost]` |

## 12.5 Budget Reflection
If your cost is too high, what can be simplified, removed, substituted, or shared?

**Response:**  
`[Write here]`

---

# 13. Planning the Work

## 13.1 Team Working Agreement
Write how your team will work together.

Include:
- how tasks are divided,
- how decisions are made,
- how progress will be checked,
- what happens if a task is delayed,
- how documentation will be maintained.

**Response:**  
`[Write here]`

## 13.2 Task Breakdown

| Task ID | Task | Owner | Estimated Hours | Deadline | Dependency | Status |
|---|---|---|---:|---|---|---|
| T1 | `[Finalize concept]` | `[Name]` | `2` | `[Date]` | `None` | `To Do` |
| T2 | `[Complete BOM]` | `[Name]` | `1` | `[Date]` | `T1` | `To Do` |
| T3 | `[Test electronics]` | `[Name]` | `2` | `[Date]` | `T1` | `To Do` |
| T4 | `[Build structure]` | `[Name]` | `4` | `[Date]` | `T1` | `To Do` |
| T5 | `[Write control code]` | `[Name]` | `4` | `[Date]` | `T3` | `To Do` |
| T6 | `[Integrate system]` | `[Name]` | `4` | `[Date]` | `T4, T5` | `To Do` |
| T7 | `[Playtest]` | `[Name]` | `2` | `[Date]` | `T6` | `To Do` |
| T8 | `[Refine and document]` | `[Name]` | `3` | `[Date]` | `T7` | `To Do` |

## 13.3 Responsibility Split

| Area | Main Owner | Support Owner |
|---|---|---|
| Concept and gameplay | `[Name]` | `[Name]` |
| Electronics | `[Name]` | `[Name]` |
| Coding | `[Name]` | `[Name]` |
| App | `[Name]` | `[Name]` |
| Mechanical build | `[Name]` | `[Name]` |
| Testing | `[Name]` | `[Name]` |
| Documentation | `[Name]` | `[Name]` |

---

# 14. Weekly Milestones

## 14.1 Four-Week Plan

### Week 1 — Plan and De-risk
Expected outcomes:
- [ ] Idea finalized
- [ ] Core interaction decided
- [ ] Sketches made
- [ ] BOM completed
- [ ] Purchase needs identified
- [ ] Key uncertainty identified
- [ ] Basic feasibility tested

### Week 2 — Build Subsystems
Expected outcomes:
- [ ] Electronics tests completed
- [ ] CAD / structure planning completed
- [ ] App UI started if needed
- [ ] Mechanical concept tested
- [ ] Main subsystems partially working

### Week 3 — Integrate
Expected outcomes:
- [ ] Physical body built
- [ ] Electronics integrated
- [ ] Code connected to hardware
- [ ] App connected if required
- [ ] First playable version exists

### Week 4 — Refine and Finish
Expected outcomes:
- [ ] Technical bugs reduced
- [ ] Playtesting completed
- [ ] Improvements made
- [ ] Documentation completed
- [ ] Final build ready

## 14.2 Weekly Update Log

| Week | Planned Goal | What Actually Happened | What Changed | Next Steps |
|---|---|---|---|---|
| Week 1 | `[Write here]` | `[Write here]` | `[Write here]` | `[Write here]` |
| Week 2 | `[Write here]` | `[Write here]` | `[Write here]` | `[Write here]` |
| Week 3 | `[Write here]` | `[Write here]` | `[Write here]` | `[Write here]` |
| Week 4 | `[Write here]` | `[Write here]` | `[Write here]` | `[Write here]` |

---

# 15. Risks and Unknowns

## 15.1 Risk Register

| Risk | Type | Likelihood | Impact | Mitigation Plan | Owner |
|---|---|---|---|---|---|
| `[Example: Bluetooth disconnects]` | `Technical` | `Medium` | `High` | `[Fallback interaction / simplify connection flow]` | `[Name]` |
| `[Example: Structure breaks during play]` | `Mechanical` | `Medium` | `High` | `[Reinforce joints / change material]` | `[Name]` |
| `[Risk]` | `[Technical / Material / Time / Gameplay]` | `[Low/Medium/High]` | `[Low/Medium/High]` | `[Plan]` | `[Name]` |
| `[Risk]` | `[Type]` | `[Low/Medium/High]` | `[Low/Medium/High]` | `[Plan]` | `[Name]` |

## 15.2 Biggest Unknown Right Now
What is the single biggest uncertainty in your project at this stage?

**Response:**  
`[Write here]`

---

# 16. Testing and Playtesting

## 16.1 Technical Testing Plan

| What Needs Testing | How You Will Test It | Success Condition |
|---|---|---|
| `[Bluetooth connection]` | `[Method]` | `[What counts as success?]` |
| `[Mechanism movement]` | `[Method]` | `[What counts as success?]` |
| `[Sensor behavior]` | `[Method]` | `[What counts as success?]` |
| `[App communication]` | `[Method]` | `[What counts as success?]` |

## 16.2 Playtesting Plan

| Question | How You Will Check |
|---|---|
| Do players understand what to do? | `[Method]` |
| Is the interaction satisfying? | `[Method]` |
| Do players want another turn? | `[Method]` |
| Is the challenge balanced? | `[Method]` |
| Is the response clear and immediate? | `[Method]` |

## 16.3 Testing and Debugging Log

| Date | Problem Found | Type | What You Tried | Result | Next Action |
|---|---|---|---|---|---|
| `[Date]` | `[Describe issue]` | `[Technical / Mechanical / UI / Gameplay]` | `[What you did]` | `[Worked / Partly / Failed]` | `[Next step]` |
| `[Date]` | `[Describe issue]` | `[Type]` | `[What you did]` | `[Result]` | `[Next step]` |

## 16.4 Playtesting Notes

| Tester | What They Did | What Confused Them | What They Enjoyed | What You Will Change |
|---|---|---|---|---|
| `[Peer / friend / classmate]` | `[Observation]` | `[Observation]` | `[Observation]` | `[Action]` |
| `[Peer / friend / classmate]` | `[Observation]` | `[Observation]` | `[Observation]` | `[Action]` |

---

# 17. Build Documentation

## 17.1 Fabrication Process
Describe how the project was physically made.

Include:
- cutting,
- 3D printing,
- assembly,
- fastening,
- wiring,
- finishing,
- revisions.

**Response:**  
`[Write here]`

## 17.2 Build Photos
Add photos throughout the project.

Suggested images:
- early sketch,
- prototype,
- electronics testing,
- mechanism test,
- app screenshot,
- final build.

Example:
```md



```

## 17.3 Version History

| Version | Date | What Changed | Why |
|---|---|---|---|
| `v1` | `[Date]` | `[Describe]` | `[Reason]` |
| `v2` | `[Date]` | `[Describe]` | `[Reason]` |
| `v3` | `[Date]` | `[Describe]` | `[Reason]` |

---

# 18. Final Outcome

## 18.1 Final Description
Describe the final version of your project.

**Response:**  
`[Write here]`

## 18.2 What Works Well
- `[Point 1]`
- `[Point 2]`
- `[Point 3]`

## 18.3 What Still Needs Improvement
- `[Point 1]`
- `[Point 2]`
- `[Point 3]`

## 18.4 What Changed From the Original Plan
How did the project change from the initial idea?

**Response:**  
`[Write here]`

---

# 19. Reflection

## 19.1 Team Reflection
What did your team do well?  
What slowed you down?  
How well did you manage time, tasks, and responsibilities?

**Response:**  
`[Write here]`

## 19.2 Technical Reflection
What did you learn about:
- electronics,
- coding,
- mechanisms,
- fabrication,
- integration?

**Response:**  
`[Write here]`

## 19.3 Design Reflection
What did you learn about:
- designing for play,
- delight,
- clarity,
- physical interaction,
- player understanding,
- iteration?

**Response:**  
`[Write here]`

## 19.4 If You Had One More Week
What would you improve next?

**Response:**  
`[Write here]`

---

# 20. Final Submission Checklist

Before submission, confirm that:
- [ ] Team details are complete
- [ ] Project description is complete
- [ ] Inspiration sources are included
- [ ] Player journey is written
- [ ] Sketches are added
- [ ] BOM is complete
- [ ] Purchase list is complete
- [ ] Budget summary is complete
- [ ] Mechanical planning is documented if applicable
- [ ] App planning is documented if applicable
- [ ] Code flowchart is added
- [ ] Task breakdown is complete
- [ ] Weekly logs are updated
- [ ] Risk register is complete
- [ ] Testing log is updated
- [ ] Playtesting notes are included
- [ ] Build photos are included
- [ ] Final reflection is written

---

# 21. Suggested Repository Structure

```text
project-repo/
├── README.md
├── images/
│   ├── concept-sketch.jpg
│   ├── labeled-sketch.jpg
│   ├── circuit-diagram.jpg
│   ├── ui-mockup.jpg
│   ├── prototype-1.jpg
│   └── final-build.jpg
├── code/
│   ├── main.py
│   ├── test_code.py
│   └── notes.md
├── cad/
│   ├── models/
│   └── screenshots/
└── docs/
    ├── references.md
    └── extra-notes.md
```

---

# 22. Instructor Review

## 22.1 Proposal Approval
- [ ] Approved to proceed
- [ ] Approved with changes
- [ ] Rework required before proceeding

**Instructor comments:**  
`[Instructor fills this section]`

## 22.2 Midpoint Review
`[Instructor fills this section]`

## 22.3 Final Review Notes
`[Instructor fills this section]`
