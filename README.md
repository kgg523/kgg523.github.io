# For all things Goose Patrol

## Links to files and github repository

Requirements PDF - [Req1](https://docs.google.com/document/d/14OyWe7z1T0Mk9ChHI8xJAw5MS-srqUc1-sbdwmjzoQc/edit?usp=drive_link)

Architecture PDF - [Arch1](https://docs.google.com/document/d/1AS9eH5VDcQhFSVhT94bQW-wHgc1HU9hi5MFUkiYivBY/edit?usp=sharing)

Method selection and planning PDF - [Plan1](https://docs.google.com/document/d/1Tu0mC4olFzQgibE1aiSJpzjV5gYDVBz_N7tEoprRNsw/edit?usp=drive_link)

Risk assessment and mitigation PDF - [Risk1](https://docs.google.com/document/d/12TI9g0QHh3UjEtPbT781L3SLBNtTHg7W0GbYu0amQ8Q/edit?usp=drive_link)

Implementation PDF - [Impl1](https://docs.google.com/document/d/1ivzTPWMHj5q0VJQ-duRCI07OhEJG65Q_8HolGU7hhJw/edit?usp=drive_link)

The executable JAR of the game - Coming Soon

Your team's version-control repository - [Goose Patrol Project](https://github.com/kgg523/goose-patrol-project)

## Class Diagram Evolution

First Draft of class diagram (9/10/26)
![classDiagramUploadError](classDiagrams/classDiagramDraft1.png)

Second Draft of class diagram (16/10/26)
![classDiagramUploadError](classDiagrams/classDiagramDraft2.png)

Third Draft of class diagram (23/10/26)
![classDiagramUploadError](classDiagrams/classDiagramDraft3.png)

## State Diagrams 

Peck player and Med kit state diagrams

![StateDiagramUploadError](stateDiagrams/stateDiagramJS.png)

These state diagrams display the functionality of when a player is pecked and when a player uses the medkit item:

The peck player diagram -  the goose begins chasing the player. When the player enters the specific radius of the goose, the goose is close enough to peck the player. When the player is pecked,  10 damage is then dealt to the player’s health variable. The peck is then completed, and the goose’s despawns. This functionality applies to each individual goose allowing them to attack in flocks.
The medkit state diagram - If the player has the medkit in their inventory, then the available boolean for medkit is set to true. When the player attempts to use the medkit, if the player already has full health then the medkit effect is not applied. Otherwise, the player’s health is restored to full and the medkit is removed from the inventory.

