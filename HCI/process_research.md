**Emotion-Led Level Design**
- Objective:
The research aims to design levels in a 2D platformer that evoke specific emotions (e.g., frustration, excitement, calmness) through level design mechanics. The goal is to validate the effectiveness of these designs using player feedback and behavior and explore how these insights could benefit generative AI technologies in game design to improve player experience.

1. **Evoking Emotions in a 2D Platformer**
In a 2D platformer, emotions can be evoked through the combination of mechanics, level design, and visual/audio cues.

**a-  Frustration**
- Triggers:
Precise jumps (narrow or moving platforms).
Punitive mechanics (e.g., falling restarts the level).
Time limits or ticking timers.
*Examples:*
Disappearing platforms that reappear randomly.
Long gaps that require perfect timing.

**b- Excitement**
- Triggers:
Fast-paced sequences requiring quick reflexes.
Rewarding mechanics (e.g., coins, bonuses) for risky actions.
Chase sequences (e.g., a moving hazard forcing the player to hurry).
*Examples:*
Platforms that collapse after a few seconds.
A level-ending reward after narrowly escaping a hazard.
**c- Calmness**
Triggers:
Slower, easier mechanics.
Open, visually soothing spaces with minimal hazards.
Repetitive, predictable patterns.
Examples:
Large, stationary platforms with no time limit.
Scenic backgrounds and calming music.

2. **Capturing Emotions**
To capture players' emotional responses, you can use a combination of in-game metrics, self-reported feedback, and external tools.

a. **In-Game Metrics**
Retries: Count the number of times a player restarts a level.
Time Spent: Measure the time taken to complete a level.
Idle Time: Log time spent without movement (indicating hesitation or confusion).
Erratic Inputs: Detect rapid or inconsistent key presses (often frustration signals).
b. **Self-Reported Feedback**
After each level, players rate their emotions using a simple scale (e.g., 1-5 for frustration, excitement, calmness).
Optionally, use surveys or interviews for more qualitative insights.
c. **External Tools**
Facial Expression Analysis:
Use a camera with emotion detection tools (e.g., OpenCV or Mediapipe) to capture facial expressions.
Map expressions (e.g., furrowed brows = frustration) to specific moments in the game.
Physiological Sensors (Optional):
If resources allow, use tools like heart rate monitors to measure excitement or stress.
3. **Contributions of This Research**
This research contributes to:

- Game Design Methodology:
A systematic approach to designing levels that evoke specific emotions.
Practical guidelines for emotion-focused level design.

- Affective Computing in Games:
Demonstrates how emotional responses can guide game development.
Validates low-cost tools (e.g., in-game metrics, surveys) for capturing emotions.

- Generative AI Integration:
Insights into emotion-triggering mechanics can train generative AI systems to:
Automatically design levels targeting specific emotional responses.
Adapt gameplay dynamically to maintain desired emotional states (e.g., balancing frustration and excitement).

- Player Personalization:
Lays groundwork for tailoring games to individual players based on their emotional preferences.

4. **Feasibility in One Year**
Level Design: Focus on creating 3-5 levels, each targeting a specific emotion.
Data Collection: Use in-game metrics and optional self-reported feedback.
Analysis: Correlate metrics and feedback to validate whether levels evoke the intended emotions.
Tools: Keep external tools lightweight (e.g., OpenCV for emotion detection).

5. **Steps to Get Started**
- Design Levels:
Start with sketches or mockups for levels targeting frustration, excitement, and calmness.
Implement the mechanics and test their playability.
Game elements to target emotional state: 
Coins: number
Power ups: number, type (bonus, malus)
enemies: number (average, high low, no), type number
gaps: number, width (long, short)
platform: disappear/reappear, collapsable
music: type(calming, stressful)
background: soothing, clustered..
Time: constraints, penalties..
Lives: number, reward(+1 if..)
checkpoints: number (low, high, 0)

- Integrate Metrics:
Add code to log retries, time spent, and idle time.
- Set Up Emotion Capture:
Integrate facial expression detection if using a camera.
Design a short survey for self-reported feedback.

- Test and Refine:
Conduct small-scale tests with friends or colleagues.
Refine levels based on feedback and captured data.

1. **Contributions to Generative AI:**
This research would greatly benefit generative AI by:
- Training AI Models: Providing datasets on how specific mechanics evoke emotions, helping AI design emotion-driven content.
- Adaptive Gameplay: Enabling AI to dynamically generate levels or mechanics tailored to a player’s real-time emotional state.
- Broader Applications: Beyond games, insights could inform other interactive systems like educational apps or therapeutic tools.