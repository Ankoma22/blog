---
author: "Andrej Malyhin"
title: "Styling UI components"
date: 2018-02-17T15:50:33+03:00
---

Making beautiful user interface is an important part of a job for every iOS developer. We are spending considerable amount of time changing colors, enlarging fonts or adding blurring effects. And the tricky part is that this process never stops. One of my good friends who works as a graphical designer for a decade told me that "Design is more of process rather than a result". For us, developers it means that all these small and let's be hones sometimes annoying tasks won't go away.

## Regular way of dealing with styling UI components

```
  let button = UIButton()
  button.backgroudColor = .green
  button.textLabel.font = UIFont.systemFont(ofSize: 10)
```
