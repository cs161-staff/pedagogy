---
title: Student Support Flowchart
tags: [student support]
description: Student Support Flowchart
author:
    name: Vron Vance
---

> Currently in draft form.

<script src="https://cdn.jsdelivr.net/npm/mermaid/dist/mermaid.min.js"></script>

<div class="mermaid">
graph TD;
    A(<b>Academic Distress</b><br>Sudden Decline in Work and Grades<br>Repeated Absences<br>Disorganized Performance<br>Multiple Extension Requests<br>Bizarre content in writings or presentations);
    A--> B{Check In};
    B --> |Just Academics| C{What are <br>academic barriers};
    B-->|Overly demanding of faculty or staff time and attention| G{Refer};
    B-->|You find yourself providing more personal than academic support| G;
    C -->|Format of Material| D{What formats work best};
    D--> H;
    H(<b>Share study materials in applicable formats</b><br>If you don't have something on hand, follow up <br>with the student later. Reach out to campus orgs and <br>course staff about available study matierals);
    C -->|Two| E[iPhone];
    C -->|Three| F[fa:fa-car Car];
</div>
