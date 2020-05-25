---
layout: post
title: Cutting Circular Holes in Curved Surfaces
date: '2016-11-08T13:58:26-05:00'
tags:
- blender
- b3d
- topology
- guide
tumblr_url: https://topologyguides.com/post/152907366360/cutting-circular-holes-in-curved-surfaces
---
I’m back! At least for now. Today i’m answering a question about cutting circular holes in curved surfaces. I learned this technique from the great [Chris Kuhn](https://www.facebook.com/Kuhn-Industries-345392525548878/) a few years ago and have used it ever since.

## 1.

Start with even quads and an even mesh density.

## 2.

Add a Circle with an amount of sides relative to the density of the surface.

## 3.

Add a Shrinkwrap modifier to the circle, and set to project onto the surface area. (Be sure to set the direction and axis of projection.)

## 4.

Cut necessary areas in surface and merge vertexes along the edge of the hole with the circle. (Be sure to merge to the circle to maintain the circular shape.)

## 5.

Finish by checking geometry for errors or improper curvature.

![](/assets/img/155917438770_0.png)
