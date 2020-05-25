---
layout: post
title: Optimal Edge Loop Reduction Flows
date: '2017-08-01T12:05:18-04:00'
tags:
- blender
- guide
- 3dmodeling
- tutorial
- mesh flow
- step down
- edge loops
tumblr_url: https://topologyguides.com/post/163679954765/loop-reduction
---
 ![image](/assets/img/163679954765_0.png)  
 ![image](/assets/img/163679954765_1.png)  
Subdivided Result  

## **[Optimal Edge Loop Reduction Flows](http://topologyguides.com/2020/05/23/2017-08-01-loop-reduction.html)**

An essential skill of modeling is knowing how to properly reduce&nbsp;the number of edge loops from a high mesh density to a low density. This involves some tricky topology. So let’s have a look at how to best reduce the various flow types.

## 2-1 and 4-1

The 2-1 and 4-1 flows are the trickiest to handle. Most methods involve substantial distortion of topology and/or the addition of more loops to the left or right of the intersection.&nbsp;

So, after experimenting with different forms, the results above seem to offer the least mesh distortion despite containing Tris&nbsp;and N-gons.&nbsp;

I apologize to any quad purists out there for the lack of quads. ;)

## 3-1, 4-2, and 5-3

The three of these flows are very standard flows that involve&nbsp;redirecting the edge loops back towards their origin. This trick is very effective. and maintains almost perfect topology in most situations.&nbsp;

As you can see, the 4-2 and 5-3 flows follow the form of the 3-1 flow. With the only differing factor being the number of center loops. This shows just how adaptable&nbsp;this method of reduction&nbsp;can be.&nbsp;



* * *


Hope this helps! if so, be sure to hit one of those share buttons below!

Also, if you’re interested in supporting the content here on Topology Guides, please consider making a small donation [to my Patreon page](https://www.patreon.com/johnson)&nbsp;to help with the creation of new content!
