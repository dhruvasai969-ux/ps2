# Smart Delivery Dispatch System

## Team Information
- **Team Name**: [SPIRIT]
- **Year**: [1ST Year]
- **All-Female Team**: [No]

## Architecture Overview

#### Describe your approach here. Keep it short and clear.

    - What is your dispatch strategy?
    Real-time greedy assignment — for each order, choose the best available agent immediately based on score.
    - How do you score agents for incoming orders?
    Score = distance (closer is better) + load (less busy preferred) + priority boost
→ Highest score gets the order.
    - How do you manage SLA deadlines, priority orders, and agent capacity?
    SLA: tracked using deadlines (used for performance check)
Priority: HIGH orders get preference (sorting + score boost)
Capacity: max 2 orders per agent (strict limit)
    - What are the main steps in your pipeline?
    Order → prioritize → filter agents → score → assign → deliver → update system

If you say this cleanly, judges will understand fast 👍


**Note:** Please do not change the format or spelling of anything in this README. The fields are extracted using a script, so any changes to the structure or formatting may break the extraction process.
