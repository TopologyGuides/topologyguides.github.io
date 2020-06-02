---
layout: post
title: Cutting Custom Shapes
date: '2016-03-04T21:46:00-05:00'
tags:
- blender
- topology
- 3d
- holes
tumblr_url: https://topologyguides.com/post/140479921825/cutting-custom-shapes
alias: /post/140479921825/cutting-custom-shapes
---
Recently, I received a question in regards to cutting a custom hole onto a surface. Instead of addressing a unique situation, I thought I would give some guidelines for cutting holes. So here it goes.

**The Shape**

Start by modeling the shape you would like to cut, make it as minimal in vertices as possible. Then place it onto the area you would like to cut it onto.

**Basic Form**

Delete the major areas needed to make the hole. Again, be minimal in what you delete, only what is necessary.

**Shaping the Hole**

Shape the vertices to fit around the shape. Don’t move them in too close, make sure there will be room for an edge loop with faces that are consistent in size with the rest of the mesh.

**Counting the Loops**

Count the vertices around the hole and the shape. Most likely they are uneven. If so, add and remove loops from both the shape and the rest of the mesh. This will be difficult, it may require you to retopologize parts of the mesh in order to make match.

**Filling the Gap**

Start filling the faces in. Rearrange the varices to make sure the faces are even is size as much as possible.

**Mesh Check**

After you’re done, check over the model to make sure you didn’t mess up other parts of the model while deleting or adding edge loops. Especially if you’re doing sub-d modeling.

![](/assets/img/140479921825_0.png)
