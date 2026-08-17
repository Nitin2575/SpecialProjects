# Strength in Deficit

> How can connected health, nutrition, and strength-training data help a lifter maintain or improve strength during a calorie deficit?

**Strength in Deficit** is a personal N-of-1 product analytics case study using 30 days of my own health and training data.

The project explores how sleep, nutrition, body weight, activity, recovery, and workout performance interact during a calorie deficit, and how those signals could support better training decisions.

---

## Observation

Lifters often track their workouts, nutrition, sleep, activity, and body weight across separate tools.

The data exists, but it rarely answers the question that matters most during a cut:

> Should I progress, maintain, or adjust today’s training?

---

## Project Goal

Use connected personal data to explore a product feature that helps lifters:

- Maintain strength while losing weight
- Recognize when recovery or fueling is limiting performance
- Make better progression decisions
- Avoid unnecessary reductions in training load
- Adjust volume before performance meaningfully declines

---

## Data Sources

- Apple Health
- Strength-training logs
- Nutrition records
- Daily body weight
- Sleep data
- Activity and step data
- Personal session notes

---

## Approach

```mermaid
flowchart LR
    A[Collect Data] --> B[Clean and Relate]
    B --> C[Define Metrics]
    C --> D[Analyze Patterns]
    D --> E[Generate Insights]
    E --> F[Design Product Feature]
