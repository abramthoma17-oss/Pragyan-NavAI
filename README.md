# Pragyan-NavAI
A mobile app dashboard for high school robotics teams to eliminate match-critical math errors. Features a VEX speed calculator and an autonomous path scanner. Official entrant in the Congressional App Challenge &amp; IdeAction Global Pitch Competition.
# Pragyan-NavAI

**Pragyan-NavAI** is a mobile app dashboard engineered to support high school robotics teams during high-stakes, fast-paced competitions. By automating critical mechanical calculations and path safety scans, the app eliminates manual math errors in the pit lane such as wheel-to-gear ratio miscalculations—that can compromise competitive matches.

---

## Submissions & Recognition
* **Congressional App Challenge:** Official Entrant (2026).
* **IdeAction Global Pitch Competition:** Selected Global Competitor; pitched to the Leadership & Innovation Lab (LIL) venture evaluation committee.

---

## Core Features & Architecture

The working prototype features two primary technical modules:
* **VEX Speed Calculator:** An interactive tool where users input motor RPM and wheel dimensions to instantly compute theoretical and true robot velocity.
* **Autonomous Path Scanner & Rover Telemetry:** A mission-control-inspired interface designed to simulate path safety and obstacle assessments for autonomous rovers.

---

## Tech Stack & Engineering Practices

* **Frontend Layout:** Built using RapidNative framework components with dynamic box-model layout parameters to optimize cross-platform screen scaling.
* **Backend Logic & Integration:** Programmed using custom JavaScript/Python logic optimized alongside large language models (Google Gemini) for algorithmic efficiency.
* **Data Strategy:** Implements a local fallback state machine to seamlessly handle live-data simulation and API connectivity contingencies (such as 404 network timeouts), ensuring a reliable user experience during telemetry disruptions.

---

##  Technical Challenges Overcome

* **API & Telemetry Optimization:** Faced a persistent network connectivity bottleneck when attempting to fetch live Mars surface data from external NASA servers. Resolved this by architecting a secondary data-handling loop using a local backup matrix of authentic spatial imagery, maintaining functional integrity without downtime.
* **UI/UX Responsive Layouts:** Debugged visual truncation issues involving system status strings (`ACTIVE - STANDBY`). Mastered UI layout bounding boxes and structural padding constraints to ensure fluid, accessible data displays.

---

##  6-Month Roadmap & Future Milestones

1. **Hardware Integration:** Transition code from simulated environments onto physical microcontrollers (e.g., Arduino/Raspberry Pi boards) to test execution directly on robotic hardware.
2. **Astrodynamics Mapping:** Calibrate the autonomous path scanner metrics to map onto real coordinates matching upcoming NASA Lunar mission profiles.
3. **Beta Testing Deployment:** Package the software into a deployable toolkit and distribute it to 5 high school robotics teams across Texas to gather empirical feedback during active regional tournaments.
