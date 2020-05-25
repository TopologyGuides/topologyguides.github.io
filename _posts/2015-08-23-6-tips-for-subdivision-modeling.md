---
layout: post
title: 6 tips for Subdivision Modeling
date: '2015-08-23T17:47:30-04:00'
tags:
- article
- 3D Modelling
- tips
tumblr_url: https://topologyguides.com/post/127424456675/6-tips-for-subdivision-modeling
---
Here’s a few tips to keep in mind when Sub-d modeling. I hope you like this written format. If not, let me know.

## 1. Always start with an accurate Blocking

Blocking is one of the most important stages of modeling. It’s where you define the scale, style, and look of your model. That’s why you should always start with an accurate base shape. Because once you start adding lots of details and holding edges it’s hard to change a shape without getting a big headache.

## 2. Use as few Polygons as possible

When sub-d modeling you don’t need to worry about keeping curved surfaces smooth because once you apply a few levels of sub-surf (subdivision surface) you won’t be able to see how “low poly” your model really is. Why should you use a 32 sided cylinder if you can use a 6 sided one and apply some non-destructive sub-surf instead? So keep your models as simple as possible. If a polygon doesn’t perform a specific task, then most likely it should be deleted.

## 3. Tris and N-gons aren’t always Bad

Tris and n-gons have a pretty hideous reputation of ruining topology, but if used in the right circumstances, they can be useful. And in the end, they will be turned into quads anyways. Don’t take this as a green light to use non-quads all you want, but don’t freak out if you have one or two that aren’t ruining your topology flows.

## 4. Keep your Quads Square

I know you’ve probably heard this one a zillion times. But I still see lots of models with very rectangular quads. This is one of the most basic things you can do to your model to improve it. Keeping your quads square will help keep your model looking even and smooth. As well as helping other tasks like UV mapping.

## 5. Model using Modifiers

Modifiers are non-destructive. Meaning you can turn their effects on or off at any point in your modeling process. Different 3d modeling apps have different tools. But whichever app you’re using, find out which modifiers could help you when modeling. They can save hours of work.

## 6. Creases for small or distant Objects

Instead of adding holding edges to keep your corners sharp, crease your edge instead. It will keep your polygon count down and will look perfectly adequate for small or distant objects.

