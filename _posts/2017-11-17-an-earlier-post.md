---
layout: single
title: Frequently Asked Questions
sidebar:
  title: "Sample Title"
  nav: docs
---

This post has a custom navigation list set in the post's YAML Front Matter .

```yaml
sidebar:
  title: "Sample Title"
  nav: sidebar-sample
```


<p class="meta">18 Oct 2008 - San Francisco</p>

2008 is a leap year. That means that three hundred and sixty six days ago,
almost to the minute, I was sitting alone in a booth at Zeke's Sports Bar and
Grill on 3rd Street in San Francisco. I wouldn't normally hang out at a sports
bar, let alone a sports bar in SOMA, but back then Thursday was "I Can Has Ruby"
night. I guess back then "I can has _______" was also a reasonable moniker to
attach to pretty much anything. ICHR was a semi-private meeting of like minded
Ruby Hackers that generally and willingly devolved into late night drinking
sessions. Normally these nights would fade away like my hangover the next
morning, but this night was different. This was the night that
[GitHub](http://github.com/) was born.


Along with navigation elements set in `_data/navigation.yml`.

```yaml
sidebar-sample:
  - title: "Parent Page A"
    children:
      - title: "Child Page A1"
        url: /
      - title: "Child Page A2"
        url: /
      - title: "Child Page A3"
        url: /
      - title: "Child Page A4"
        url: /
  - title: "Parent Page B"
    children:
      - title: "Child Page B1"
        url: /
      - title: "Child Page B2"
        url: /
      - title: "Child Page B3"
        url: /
      - title: "Child Page B4"
        url: /
      - title: "Child Page B5"
        url: /
  - title: "Parent Page C"
    children:
      - title: "Child Page C1"
        url: /
      - title: "Child Page C2"
        url: /
      - title: "Child Page C3"
        url: /
      - title: "Child Page C4"
        url: /
      - title: "Child Page C5"
        url: /
  - title: "Parent Page D"
    children:
      - title: "Child Page D1"
        url: /
      - title: "Child Page D2"
        url: /
```
