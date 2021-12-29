---
layout: page
title: 3D Modeling Encyclopedia
permalink: /encyclopedia/
published: true
---

<div class="page" markdown="1">

{% include page/title.html title=page.title subtitle=page_subtitle %}

Ever wondered what’s an LOD is? Or a Boolean? Don’t worry, you’re not alone. Learning terminology is hard, that’s why I’ve created this list to give you a jump start in learning the terms and processes of 3d modeling.

##### **Vertex**

A vertex (or plural, vertices) is a point in 3d space used as the basis for creating edges and faces.

##### **Edge**

An edge is a line that joins two vertices and serves as the boundary between two faces.

##### **Face**

A face is the space between 3 or more edges that is visible and receives shading from light sources.

##### **Polygon**

Polygon is another term to describe a face. The filled space between 3 or more edges.

##### **Quad**

A Quad is a polygon that is rectangular or square polygon that contains exactly 4 edges.

##### **Triangle**

A triangle (or “tri” as commonly referred to) is a polygon with 3 edges.

##### **Ngon**

An Ngon (or N-gon) is a polygon with 5 or more edges. Anything that is not a tri or quad is considered an Ngon.

##### **Surface Normals**

Surface Normals (or simply Normals) are vectors that are perpendicular to the faces of a mesh. They are used when calculating the shading of a mesh.

##### **2-sided Face**

A 2-sided face (or double sided) is a face that has two surface normals, one for each side of the face, therefore is visible from both sides. To save on memory, faces can also be drawn with a single normal, in which the face is only visible from one side.

##### **Polycount**

The Polycount (or polygon count) is number of faces a 3d model contains. The term is also used by game artists to reference the triangle count, which can be very different to the face count depending on how many 4+ edge polygons you have.

##### **Base Mesh**

A base mesh is low resolution mesh used as a starting point for sculpting or detailing. Base meshes are often box modeled and designed to be as generic as possible to give artists maximum creative freedom during the sculpting phase.

##### **Low Poly**

Low Poly is a term used by game artists to state that a model is optimized for the lowest amount of polygons possible. The term is also an art style that mimics the “optimized” feel of game models for a minimalist style.

##### **High Poly**

The term High Poly is a term used by modelers to state that a model is not optimized, therefor having much more detail. High Poly models are often meant for use in pre-rendered projects such as film or stills. High poly models can also be used is the production of game models for reference and normal map baking.

##### **Rigid Body**

Rigid body is a physics term that means a mesh has an unchanging shape and is affected by physical forces such as gravity.

##### **Convex Hull**

Convex hull is a mathematical term that in essence means wrapping a mesh around another mesh to form a more simple and efficient mesh. Convex Hull algorithms are often used for creating optimised rigid body collision meshes for faster calculation.

##### **Flat/Smooth Shading**

Flat/Smooth shading reference to how a mesh’s surface normals are interpreted. Flat shading will interpret edges as being as the actually are, sharp. Smooth shading will calculate the normals in a way to mimic a smooth surface.

##### **3d Axis or Euler Angles**

The 3d axis is a visual representation of 3d space. each direction has an axis, much like a compass. There are 6 axises for up, down, left, right, forward and backward. The axises are named using the letters X, Y and Z and their opposites represented with a negative sign (-X, -Y, -z).

##### **Bevel**

Beveling is a method of smoothing sharp corners for a more realistic look. There are many beveling methods, but most involve divided a edge into a user specified amount of segments and rounding the edges to create a spherical corner.

##### **Chamfer**

A Chamfer is a type of bevel that uses only two edges. Mostly commonly creating a 45 degree angle from the right angle of a corner.

##### **Inset**

Insetting is when a face is extruded into itself to create an extra ring of faces around it.

##### **Outset**

Outsetting works the same way as insetting, but instead of extruding the face inward, the ring of faces is pushed outwards.

##### **Gizmo**

A Gizmo (or widget) is an interface tool in the 3d view. Such as the axis handles of an object or an animation rig controller.

##### **Level of Detail**

An Level of Detail (or LOD) refers to game models when the farther away the player is, the less detail an object has. For each LOD, a game artist must create the 3d models from the highest resolution down to the lowest.

##### **Real World Scale**

Real World Scale refers to creating objects that reflect real objects in their proportions and scaling. This can be achieved by using Metric or Imperial scaling units inside a 3d program to keep scale consistent and correct.

##### **Weld**

Welding (or merging) is when two vertices are merged together to form a single vertex.

##### **Edge Loop**

An edge loop is a continuous ring of edges within a mesh. Edge loops form edge flows which form the topology of the mesh.

##### **Edge Flow**

Edge flow refers to the contours of a mesh. Such as the flow from a person’s nose to down around their eye.

##### **Wireframe**

A wireframe is skeletal view of a mesh drawn without visible faces.

##### **Extrude**

Extruding is when a face is extended out from itself, giving a flat object depth, or extending an existing object.

##### **Bezier**

The most common type of vector curve. Often used for 2d graphics, but also for 3d surface models.

##### **Boolean**

Using two meshes to intersect one another in order to form a single mesh.

##### **Convex**

Relating to surfaces that are curved outwards.

##### **Concave**

Relating to surfaces that are curved inwards.

##### **Topology**

The flow, or form of the edges on a 3d model.

##### **Tessellation**

The process of filling a surface with random, even polygons, often triangles.

##### **Lattice**

A simple cubic shape used to deform or move a mesh.

##### Subdivision Surfaces (or sub-d)

Subdivision surface is a smoothing and subdivision algorithm which is used for a variety of modeling techniques. Formally known as catmull–clark subdivision surface, the algorithm is standard in almost all 3d software.

##### Box Modeling

A modeling method that relies on manipulating and extruding a cube or simple primitive into the desired form.

##### Poly Modeling (or edge modeling)

Poly modeling involves using edges to create the essentials “flows” in a mesh before filling in the less complex parts of a model. Poly modeling often involves extruding from one edge to build out a model and is most effective for organic modeling.

##### Subdivision Modeling

Subdivision Modeling is a subset of modeling that involves using subdivision Surfaces to add detail land smoothness to a model. Subdivision modeling requires specific techniques to complement the algorithms of subdivision smoothing.

##### NURBs Modeling

NURBs (or Non-uniform rational B-spline) modeling is a method of modeling often used be product engineers and designers to create smooth and precise lines without the complexity of traditional 3d modeling. The method relies heavily on mathematical models.

#####n CAD Modeling

Like NURBs, CAD modeling or Computer Aided Design, uses mathematical models to create exact models for use in product design, architecture, and engineering. The method is used extensively in engineering, but is rarely used in creative fields such as film or game design.

</div>
