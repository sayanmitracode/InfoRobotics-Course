# Project

The term project is 40% of the grade. Choose a task and a platform budget, derive a lower bound with one of the course's techniques, implement an algorithm in simulation or on data, and report the gap between the two.

## Milestones

| Milestone | Date |
|:--|:--|
| Proposal | to be announced |
| Presentations | last three lectures |
| Written report | to be announced |

## Questions to answer in the proposal

**A. The task and the platform.**

1. What must the robot do, and in what environment? State the task as a specification that a trajectory either meets or fails.
2. What is the platform budget: memory, sensor resolution, link rate, model size? Give numbers from a datasheet or a log.

**B. The bound.**

1. Which technique from the course applies: a quotient, a Hankel rank, a covering or entropy argument, a rate-distortion or directed-information converse?
2. Is the bound worst case or average case, and what does it quantify over?

**C. The algorithm and the gap.**

1. What algorithm will you implement, and on what simulator or data set?
2. How will you measure the gap between its performance and the bound?

## Directions

The case studies in Part III suggest projects:

- **Gate racing without coordinates.** For a given track, how much memory, sensing and link rate does a drone with a coarse bearing sensor need? How do the worst-case floor and the average-case failure bound compare, and how far is a trained policy from both?
- **Hover and corridor keeping over a radio link.** What rate keeps every trajectory inside a box, what rate keeps the mean-square error below a target, and how many extra bits per step does the guarantee cost over the average?
- **Sensor resolution on a nano-drone.** What is the coarsest resolution and bit depth that still permit hover or gate passing, and which measurements does an optimal sensor design keep?
- **Onboard adaptation.** What must a last-layer adaptation routine store about its flight data, and does it fit in a microcontroller's memory?
- **Model size and generalization.** How large must a quantized policy network be for a given failure rate at deployment?
- **Training with compressed gradients.** How many bits per step are needed to converge at a given linear rate, and how close does error-feedback compression come?
- **Pretrained policies and onboard computation.** How much state does a pretrained vision-language-action policy use on a given task, and which parts of the loop must run onboard given the link rate?

## Report

A proposal template and a report template will be posted here. The report follows the outline: introduction, problem statement, related work, the bound, the algorithm, results and the gap.
