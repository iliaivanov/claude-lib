## KETTLEBELL TRAINING PROMPT

You are an expert personal trainer and exercise physiologist. Create a comprehensive **kettlebell-only gym training plan** based on the following parameters:

---

### Training Parameters
- **Training Type:** `{training_type}`  
  *(Strength / Conditioning / HIIT)*
- **Session Length:** `{session_length}` minutes
- **Focus Areas (scale 1–10, where 10 = highest priority):**
  - Back: `{back_focus}`/10
  - Chest: `{chest_focus}`/10
  - Shoulders: `{shoulders_focus}`/10
  - Legs: `{legs_focus}`/10
- **Additional Comments:** `{additional_comments}`

---

### Allowed Exercise Pool

#### Main Kettlebell Exercises
- Goblet Squat
- Snatch
- Clean
- Clean & Jerk
- Press
- Jerk
- Pendulum Swing
- Deadlift-Style Swing
- Half-Snatch
- Deadlift
- Thruster
- Row

#### Support Exercises
- Windmill
- Lunge
- Suitcase Carry

#### Exercise Blacklist (DO NOT USE)
- Atlas Swing
- Around the World
- Bent Press
- Turkish Get-Up

---

### Instructions

1. Design a **complete kettlebell-only workout session** that fits within the specified time limit
2. Structure the workout according to the **training type**:
   - **Strength**
     - Low to moderate reps (3–6)
     - Heavier kettlebells
     - Longer rest periods (2–4 min)
     - Emphasis on clean, press, squat, deadlift patterns
   - **Conditioning**
     - Moderate to high reps (8–15)
     - Circuits or complexes
     - Short rest (30–90 sec)
     - Emphasis on swings, cleans, snatches, carries
   - **HIIT**
     - Time-based intervals (EMOM, AMRAP, Tabata, rounds for time)
     - Explosive movements
     - Minimal rest
     - High heart-rate focus
3. Prioritize exercises based on the **focus area ratings**
4. Use **only exercises from the allowed lists**
5. Include appropriate **progression strategies**
6. Ensure the workout is **balanced and joint-safe**
7. Include a **plank variation in the cool-down** of every session

---

### Required Output Format

```
TRAINING PLAN SUMMARY
Training Type: {training_type}
Duration: [X] minutes
Primary Focus: [Highest rated area(s)]

WARM-UP (5–10 minutes)
- [Warm-up exercises]

MAIN WORKOUT
[FOCUS AREA NAME] (Priority: X/10)
1. Exercise Name
   - Sets: X | Reps/Time: X | Rest: X sec
   - Load: Light / Moderate / Heavy
   - Notes: Technique cues

COOL-DOWN (5 minutes)
- Plank variation
- Mobility work

WORKOUT NOTES:
- Training-specific guidance
- Safety considerations
- Progression suggestions
```

---

**Generate the kettlebell training plan now.**
