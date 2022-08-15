---
layout: project
type: project
image: img/CTTR.jpg
title: "Catch The Turtle: Redux"
date: 2018
published: true
labels:
  - Visual JavaScript
  - Code.org
  - Mobile Game
summary: "My first game project, designed in High School as a two week assignment. It was an expansion on an earlier test game made that year."
---

<div class="text-center p-4">
  <img width="200px" src="../img/micromouse/micromouse-robot.png" class="img-thumbnail" >
  <img width="200px" src="../img/micromouse/micromouse-robot-2.jpg" class="img-thumbnail" >
  <img width="200px" src="../img/micromouse/micromouse-circuit.png" class="img-thumbnail" >
</div>

Catch the Turtle: Redux is a clicker based mobile phone game designed in Code.org for AP Programming in High School. It was a 5 level game featuring one miniboss, a two regular bosses, and a final boss. Alongside an endless arcade mode, and a debug mode. There is a storymode with an overworld, and levels that unlocked as you "caught" the turtle in the previous level. Each level has a unique turtle/tortoise with its own mechanic that makes gameplay different and progressively more challenging. Arcade mode is an endless experience where you start with the first turtle, and progressively have the rest of the turtles put into the level the more you click them. This goes on forever, adding every turtle until the user runs out of lives.

For this project, I was quite proud of myself. Given the short deadline and very short class structure of 45 minute periods, I had a tight time constraint, but I feel I had the most well developed project out of the class. Many of which only had lightly modified test-games, while mine was fully fledged, and could have been an actual mobile app if given enough polish. I plan to make a successor to this game one day, one that is highly experimental and will push through all genres.

Here is some code that illustrates how we read values from the line sensors:

```cpp
byte ADCRead(byte ch)
{
    word value;
    ADC1SC1 = ch;
    while (ADC1SC1_COCO != 1)
    {   // wait until ADC conversion is completed   
    }
    return ADC1RL;  // lower 8-bit value out of 10-bit data from the ADC
}
```

You can learn more at the [UH Micromouse News Announcement](https://manoa.hawaii.edu/news/article.php?aId=2857).
