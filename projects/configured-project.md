---
layout: project
type: project
image: img/micromouse/micromouse-square.jpg
title: "Lets get this configured"
date: 2023
published: true
labels:
  - Not robotics
  - Ardu D2
  - C w/2 pluses
summary: "Currently learning about Github and using this time to "engrave" my progress... or something like that. My intention is to look back in a couple months at this and realize how far I have come. "
---

Configured project's goal is to become a configured project. There is nothing special about me completing this work aside from the amount of time I will have spent working on this. The completion of this E0 portfolio is not an insight into my ability, it is an insight into the workload and consistency that is to come.


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
