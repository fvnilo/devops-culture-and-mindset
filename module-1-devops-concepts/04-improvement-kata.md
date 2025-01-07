# DevOps Principles: Improvement Kata

Originates from Toyota production system. It is a process of **continuous improvement**.

## Steps

1. Understand the **vision** and **direction** of the project.
2. Analyze to understand the current condition.
3. Establish target condition.
4. Plan > Do > Check > Act (or Adjust) (PDCA) toward the target.

_Example_: If the vision is to have 0 defects and every release has 20, aim for 10 because 0 isn't going to be achievable right away. Iterate towards 10. Use automated test scripts. Establish a checkpoint. Work toward the target.

## Real World Example at Nordstrom

- Release frequency went from twice a year to on-demand using improvement kata
- Business stakeholders decided that monthly release was the sweet spot
- Decision was made for the remaining customer-facing engineering teams to aim to reduce cycle time by 20% with the vision to have on-demand releases.
- The next steps were:
  - Each team had to grasp the current condition
  - Set target (cycle time from 5 to 4 weeks)
  - Pick experiments to **iterate** toward target
    - First step was to remove an approval process in the hardening phase (was intended to be a 2 week period for stabilization and all tests had to be done by then.)
      - Developers were asking for exceptions because they didn't have their tests done in time
      - The team could pause all effort and wait for the approval of a VP
      - The real issue, that was masked, was that quality had to be shifted to the left.
      - The team saved a day in the process
    - Next target was to reduce exceptions in the hardening phase
      - Implementing automation shaved 2 days from cycle time
      - It was also expected to reduce rework
    - Next target was to focus on the deployment process
      - Aim to automate tasks and improve quality
      - Result: release took fewer days
      - The 4 week process goal was reached
    - There were weekly check-ins
    - PDCA check were done every 3 weeks

## Summary

- People assume they know what problems they need to solve
- They jump to conclusions about how to solved assumed problems
- Leveraging improvement kata requires leaders to direct problem-solving
