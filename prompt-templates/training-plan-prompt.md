You are an expert personal trainer and exercise physiologist. Create a comprehensive gym training plan based on the following parameters:

**Training Parameters:**
- Training Type: {training_type} (strength/conditioning/endurance/cardio/powerlifting/functional)
- Session Length: {session_length} minutes
- Focus Areas (scale 1-10, where 10 = highest priority):
  * Back: {back_focus}/10
  * Chest: {chest_focus}/10  
  * Shoulders: {shoulders_focus}/10
  * Legs: {legs_focus}/10
- Additional Comments: {additional_comments}

**Instructions:**
1. Design a complete workout session that fits within the specified time limit
2. Structure the workout according to the training type:
   - **Strength**: Focus on compound movements, 3-5 reps, heavy weights, longer rest periods
   - **Conditioning**: Circuit-style training, minimal rest, functional movements
   - **Endurance**: Higher rep ranges (12-20+), shorter rest periods, sustained effort
   - **Cardio**: Heart rate focused, interval training, minimal strength components
   - **Powerlifting**: Focus on squat/bench/deadlift variations, low reps, maximum weight
   - **Functional**: Real-world movement patterns, stability, mobility integration
3. Prioritize exercises based on the focus area ratings (higher numbers = more exercises/sets/emphasis)
4. Include proper exercise progression appropriate for the training type
5. Consider the additional comments and modify the plan accordingly
6. Ensure the workout is balanced and safe
7. Include plank exercise into the cool-down of every training

**Required Output Format:**
```
TRAINING PLAN SUMMARY
Training Type: {training_type}
Duration: [X] minutes
Primary Focus: [Highest rated area(s)]

WARM-UP (5-10 minutes)
- [List 2-3 warm-up exercises with duration, appropriate for training type]

MAIN WORKOUT
[For each focus area with rating ≥3, include:]

[FOCUS AREA NAME] (Priority: X/10)
1. Exercise Name
   - Sets: X | Reps: X | Rest: X seconds | Load: [% of 1RM or intensity level]
   - Notes: [Form cues, modifications if needed]

2. Exercise Name
   - Sets: X | Reps: X | Rest: X seconds | Load: [% of 1RM or intensity level]
   - Notes: [Form cues, modifications if needed]

COOL-DOWN (5 minutes)
- [List 2-3 cool-down/stretching exercises appropriate for training type]

WORKOUT NOTES:
- [Training type specific instructions]
- [Any specific instructions based on additional comments]
- [Safety considerations]
- [Progression suggestions for this training type]
```

**Guidelines:**
- Structure the entire workout according to the specified training type
- Allocate time proportionally based on focus ratings
- Include 2-4 exercises per focus area (depending on priority, time, and training type)
- Focus areas rated 1-2: Skip or include 1 light exercise
- Focus areas rated 3-5: Include 1-2 exercises
- Focus areas rated 6-8: Include 2-3 exercises  
- Focus areas rated 9-10: Include 3-4 exercises
- **Training Type Specific Guidelines:**
  - **Strength/Powerlifting**: Prioritize compound movements, lower rep ranges (1-5), longer rest (3-5 min)
  - **Hypertrophy**: Balance compound and isolation, moderate reps (6-12), moderate rest (60-120s)
  - **Endurance**: Higher reps (12-20+), shorter rest (30-60s), circuit potential
  - **Conditioning**: Functional movements, minimal rest, time-based or AMRAP format
  - **Cardio**: Heart rate zones, interval structure, minimal strength components
  - **Functional**: Movement quality over load, stability challenges, real-world patterns
- Adjust exercise selection, intensity, and volume based on training type and session length
- Consider muscle group interactions and recovery needs for the specific training type
- Exclude excersice 
   - Landmine Row
   - Single-Arm Landmine Row

Generate the training plan now.