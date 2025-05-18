---
title: Week 9 session 1
published_at: 2025-05-12
snippet: week 9 session 1
disable_html_sanitization: true
allow_math: true
---
# Feedback from friends
https://docs.google.com/forms/d/1mMgdW7-zAOIKWMaboBwEszD1KUu8iQ61Azl8n7qNpW4/edit#responses

This week, I asked some of my friends and family members to playtest my environment. I gave them a fixed amount of time to explore the space freely, without giving any instructions. I also recorded their playthroughs so I could review their experiences and gather helpful feedback.

**Tester Feedback**

Most of my friends noticed that they often fell off platforms or objects while moving, which disrupted their experience. They suggested that I should add colliders to all the objects and platforms to prevent unexpected falls and improve navigation.

From my family members, I received feedback about the sound and music levels. They felt that the volume was too loud in some areas, which made it harder to focus or feel immersed. Based on this, I will go back and adjust the audio levels for a more balanced experience.

Lastly, a few players mentioned that in Encounter 3, the teleportation box didn’t work properly. It sometimes required the player to walk through it several times before it would trigger the teleport. This issue was frustrating and broke the flow of the game. As a result, I will review the teleportation script and make sure it functions consistently.

# Video testing
<iframe width="560" height="315" src="https://www.youtube.com/embed/onU1j-BTeQ4?si=ZOxmBtmMUV-zdVDw&amp;start=5" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

# Fixing my problems in Unity
![fix](fix.png)
![fix](fix2.png)
![cube](cube.png)
![box](box.png) ![code](code.png) 

After receiving feedback from my friends and family during the playtesting session, I took time to address the issues they encountered and improve the overall experience of the game.

First, I fixed the falling and collision problems by adding Mesh Colliders and Box Colliders to the necessary objects in the environment. This change ensures that the player can no longer fall through platforms or walk through solid objects, making movement much more stable and realistic.

Next, I reduced the volume of the background sound and music to create a more balanced and immersive soundscape. The previous audio levels were too loud and distracting for some players, so now the sound blends better with the environment and doesn’t overpower the experience.

Lastly, I fixed the issue with the teleportation box in Encounter 3. Previously, players had to walk through it several times before it worked. I rewrote it using a C# script to make sure the teleport mechanic is now smooth, responsive, and works immediately when triggered.

These improvements have made the environment feel more polished and player-friendly, and I look forward to getting more feedback as I continue to develop the project.


