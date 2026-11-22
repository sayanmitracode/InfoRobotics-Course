# Administrivia

## Course description

Modeling and analysis of what a robot must remember, sense, and communicate to complete a task: proving lower bounds that hold for every policy, and designing algorithms that approach them. Minimal state machines and information spaces, linear realization, worst-case information rates, minimal Bayesian filters, rate-distortion, and directed information. Applications to small drones, memory in learned policies, learning while acting, and interfaces between large AI models and fast controllers. Theoretical treatment with programming projects on simulated and logged robot data.

Part I develops worst-case, set-valued techniques: quotients by indistinguishability (the Myhill-Nerode theorem, minimal sufficient information spaces), Hankel factorization, and covering and topological entropy arguments. These determine the smallest budget at which a task can be guaranteed. Part II develops average-case, measure-theoretic techniques: the minimal dimension of a Bayesian filter, one-shot rate-distortion theory, and directed information with sequential rate-distortion. These give trade-off curves between budget and performance, together with algorithms for optimal coder-controllers.

## Learning outcomes

Students will be able to:

- compute the minimal state a task requires, exactly (as a quotient or Hankel rank) or approximately (from singular values);
- prove lower bounds on memory, sensing and communication with quotient, Hankel, covering-and-entropy, and rate-distortion or directed-information arguments;
- construct matching algorithms: minimal machines, realizations from data, coder-controllers, optimal encoders (Blahut-Arimoto) and sensor designs (semidefinite programming);
- evaluate an implemented policy against these bounds under explicit memory, sensing and communication budgets, in simulation and on logged data.

## Prerequisites

**Required:** graduate-level probability (ECE 534 or equivalent) and linear algebra; comfort reading and writing proofs; programming in Python.

**Recommended:** an introductory course in control or dynamical systems (ECE 515 or equivalent). ECE 563 (Information Theory) is useful background. ECE 484 (Principles of Safe Autonomy) is a natural predecessor for students without a control background.

## Lectures

- **Time:** Tuesday and Thursday, 2:30 to 4:00 pm.
- **Place:** to be announced.
- **Format:** blackboard lectures. Each lecture proves one main theorem and connects it to a programming exercise or an experiment.
- **Recordings:** to be announced.

## Staff and office hours

| | Office hours | Location |
|:--|:--|:--|
| Sayan Mitra (instructor) | to be announced | CSL 266 |

## Text

S. Mitra, *Information Bottlenecks in Robotics*, lecture notes, 2027. Chapters are posted on the [Schedule](schedule.md) as the lectures reach them. Research papers for each topic are listed under [Resources](resources.md).

## Grading

- **Programming exercises, 40%.** About eight exercises, each tied to a lecture's theorem. Each exercise reports the bound, the achieved performance and the gap. See [Exercises](exercises.md).
- **Term project, 40%.** Proposal, presentation and written report. See [Project](project.md).
- **Examination, 20%.** One in-class examination (80 minutes) on proofs and calculations from Parts I and II.

## Policies

**Late work.** To be announced.

**Collaboration.** To be announced.

**Use of AI tools.** To be announced.

**Absences.** Absences for medical or personal emergencies are handled through a letter from the Office of the Dean of Students.
