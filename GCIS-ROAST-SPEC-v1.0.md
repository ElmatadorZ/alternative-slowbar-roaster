GCIS – Roast Specification v1.0
Global Coffee Intelligence Standard
1. Purpose
Define a machine-readable, reproducible roast profile model that removes ambiguity from human roast description.
This specification allows:
Cross-roaster comparison
AI roast optimization
Predictive extraction modeling
Roast defect detection
2. Roast Variables (First Principle Based)
Roasting = Controlled Heat Transfer Over Time
Core Variables:
Bean Temperature Curve (BT)
Rate of Rise (RoR)
Development Time Ratio (DTR)
End Temperature
Airflow Modulation
Heat Application Pattern
Total Roast Time
3. Roast Structural Layers
Layer 1 — Drying Phase
Layer 2 — Maillard Phase
Layer 3 — Development Phase
Each layer must include:
Start Time
End Time
ΔTemperature
RoR Stability Score
4. Roast Classification Model
Light Roast
Medium Roast
Medium-Dark Roast
Dark Roast
Classification is determined by:
Final Temperature + DTR + Color Index
Not subjective naming.
5. Roast Color Standardization
Must include:
Agtron Value (if available)
RGB camera calibration reference
Lighting condition metadata
Sensor type
6. Roast Quality Metrics
Thermal Stability Score
Development Consistency Index
Roast Variability Deviation
Defect Probability Estimation
7. AI Interoperability Clause
Any AI system claiming GCIS compatibility must:
Output structured roast data
Avoid subjective-only descriptors
Provide falsifiable roast variables
Include uncertainty margin
