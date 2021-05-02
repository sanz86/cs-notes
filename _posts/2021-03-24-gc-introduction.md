---
layout: post
title: Introduction to General Coding
author: Sanjib
date: 2021-04-20 12:00
category: gc
color: body-red
category-desc: General Coding
menu: Introduction
menu-desc: Introduction
---

**How to Calculate Square till 2^30 with bitwise operator**

 For calculating Square of i, 1 << i


**How to Calculate the closest square of 2 less than the number n **

log[n]

log[1] = 0;

for(int i = 2; i <= n; i++)
{
    log[i] = log[i/2] + 1;
}