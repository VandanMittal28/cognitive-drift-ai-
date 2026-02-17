Cognitive Drift AI – MVP
Overview

Cognitive Drift AI is a real-time behavioral analytics system that detects cognitive fatigue using sequential match event data.

This MVP demonstrates how micro-level behavioral drift — including decision latency, execution errors, and action diversity — can be transformed into a Cognitive Fatigue Index (0–100).

Problem

Athletes often experience cognitive fatigue before visible performance decline.
Current systems rely on wearable sensors or post-match analysis.

This project estimates fatigue directly from in-game behavioral event data.

Methodology

Extract sequential player actions from match dataset

Compute rolling behavioral metrics:

Decision Latency

Error Rate

Action Entropy

Establish early-match cognitive baseline

Detect behavioral drift

Generate Cognitive Fatigue Index (CFI)

Cognitive Fatigue Index Formula

CFI =
0.4 × Latency Drift

0.4 × Error Drift

0.2 × Entropy Shift

Score normalized between 0–100.

Output

Real-time fatigue score

Fatigue trend visualization

High fatigue risk alert

Example Output:

Dataset

Soccer Match Event Dataset
https://www.kaggle.com/datasets/aleespinosa/soccer-match-event-dataset

🛠 Tech Stack

Python

Pandas

NumPy

Matplotlib



Future Work

Real-time streaming integration

Multi-player fatigue comparison

Predictive substitution recommendations

Cloud deployment for live matches

License

MIT License
