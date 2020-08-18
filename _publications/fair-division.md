---
title: "An Asymptotic PTAS for a Special Case of Minimum Makespan Job Scheduling"
collection: publications
permalink: /publication/fair-division
date: 2019-08-16
venue: "Unpublished technical report"
paperurl: '/files/Scheduling algorithm writeup.pdf'
---
In this project, we developed an asymptotic polynomial-time approximation scheme (APTAS) for a special case of the minimum makespan job scheduling problem with job cost constraints motivated by applications to fair chore division problems.

### Background

Fairly distributing tasks among a set of agents based on their reported per-task costs is a computationally difficult problem. One common setup, the so-called minimum makespan job scheduling problem, has long been known to be NP-hard. In fact, it's NP-hard to compute a solution to this problem that's always "sufficiently close" to optimal.

However, it's often reasonable to assume that each agent ranks the tasks in the same way: They might all agree that one task is the worst, another is second-worst, and so on. In many settings, we'll also give each agent a budget for their costs to prevent them from "cheating" by reporting very high costs for every task.

Working under Prof. Adrian Vetta, I designed an efficient approximation scheme (an asymptotic polynomial-time approximation scheme) for an instance of this problem that satisfies the two assumptions I laid out above. This algorithm has potential applications to problems at the nexus of economics and computer science involving the fair division of tasks.

[Download paper here](/files/Scheduling algorithm writeup.pdf)
