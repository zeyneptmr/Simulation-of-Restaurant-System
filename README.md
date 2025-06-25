Restaurant Operations Simulation (Arena - INE332 Project)

This repository contains a discrete-event simulation model of a full-service restaurant developed using Arena Simulation Software as part of the INE332 Simulation Modeling course.

Project Overview

A detailed simulation model was developed to analyze and optimize restaurant operations, focusing on customer service processes, resource utilization, and system performance.

Key Features

Full workflow simulation: customer arrivals, seating allocation (indoor/outdoor), order taking, meal preparation, dining, and table cleaning.
Customer arrival rates modeled with exponential distributions for peak and off-peak periods.
Service times fitted using Arena’s Input Analyzer (triangular and normal distributions).
Queue management and resource constraints for waiters, chefs, and cleaning staff.
30 independent simulation replications with warm-up period to ensure statistical validity.
Input Analyzer

Distribution fitting was performed using Arena’s Input Analyzer tool. The repository includes .dft files documenting statistical fitting for:

Chef Meal Preparation Time
Customer Dining Time
Waiter Order Taking Time
Results Summary

Bottlenecks identified in waiter availability and indoor seating capacity.
Improvement scenarios developed: additional waiter allocation and indoor seating expansion.
Enhanced overall system throughput and reduced customer waiting times.
