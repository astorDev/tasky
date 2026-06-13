# Roadmap Concept

Virtually any Significant Project will have **a lot** of tasks. Scoping of the work becomes essential. This module proposes a naming convention for the problem. Main use case for the convention is folder names inside a project folder, but it might as well be used for screens in a UI-based tools. The convention tries to be as universal as possible, while also 

- `roadmap`: name of the grouping itself
    - `iteration`: Describes what team does **now**.
    - `milestone`: Describes current **long-to-middle-term goals** of the team. 
    - `future`: Describes what the team will pick from **after** completing current milestone.

As you might seems the folders describe **current** state of what we have. Those folders are **not** adjusted to hold historical information. History management is supposed to be done by a dedicated technique, being that **git** or a feature of a task tracker.

## Universality

The convension supposed to be as universal as possible. For the goal, the convention allows the following flexibility:

The set of scopes supposed to be **extensive**, but not **required**. This means that there should be no need to **add** a "folder", but you may want to "**delete**" a "folder". In other words, You **can** (and should) omit folders which are irrelevant to your project. For example a team, that does weekly releases and immediately does whatever comes to mind, don't have to maintain a `milestone`s folder. A solo-developer of a small open-source tool may have neither `iteration`s nor `milestone`s or on the contrary have only `iteration`, but not `milestone` or `future`.