📊 Training Analytics System – Excel Prototype

This project is a modular Excel-based analytical system for strength training programming.

It is not a static workout template, but a rule-based decision engine that:

evaluates user strength level (relative strength index),

detects structural imbalances (L/R asymmetry analysis),

assigns global structural status (OK / MEDIUM / CRITICAL),

calculates structural risk score (0–100),

generates training priority based on risk hierarchy,

dynamically adjusts training volume and intensity,

calculates %1RM progression with load rounding (2.5 kg),

estimates projected 1RM using Epley formula,

visualizes imbalance via radar chart,

presents results in a dashboard-style UI.

🧠 Architecture

The workbook is structured into logical layers:

Input Layer – user data (bodyweight, 1RM, goal)

Analysis Engine – imbalance detection & risk scoring

Program Generator – progression & volume adaptation

Dashboard UI – visualization & decision output

The system demonstrates how Excel can be used as a lightweight expert system prototype before transitioning to a full application (e.g., Python backend).

🎯 Purpose

This project serves as:

a proof of concept for a commercial training system,

a demonstration of rule-based decision logic in Excel,

a prototype for future SaaS implementation.
