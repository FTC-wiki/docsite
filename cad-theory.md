# CAD Theory

CAD is a digital design tool used to create parts before manufacturing them. While our documentation primarily covers FTC-specific CAD practices, understanding the foundational concepts is essential for getting started with Onshape.

## Starting with a Sketch <a href="#starting-with-a-sketch" id="starting-with-a-sketch"></a>

If you wanted to create a cube in Onshape, you would start by representing its profile in a 2D sketch. So, what would the sketch look like for a cube? If you take the section from the plane on top of the cube, which is called the “Top" plane in Onshape, you can see that this sketch is simply a square.

<div><figure><img src=".gitbook/assets/image (36).png" alt="" width="188"><figcaption><p>2D Sketch </p></figcaption></figure> <figure><img src=".gitbook/assets/image (34).png" alt="" width="188"><figcaption><p>Cube</p></figcaption></figure></div>

## Transitioning from Sketch to 3D

**Creating a Solid Shape**

When working in a sketch, you define the fundamental properties of a shape—its position and dimensions. For example, a circle’s location and diameter are determined within the sketching environment. Once you bring this sketch into 3D, these characteristics carry over, establishing the final placement and size of the cylindrical feature in the Part Studio. To ensure consistency and accuracy, it's crucial to fully define sketches. Otherwise, parts may end up with unintended dimensions or placements.

<div><figure><img src=".gitbook/assets/image (24).png" alt="" width="188"><figcaption><p>A circle's location and diameter shown in a sketch</p></figcaption></figure> <figure><img src=".gitbook/assets/image (25).png" alt="" width="188"><figcaption><p>The extruded circle having the same location and diameter</p></figcaption></figure></div>

**Extruding to Build Volume**

To turn a sketch into a three-dimensional object, you use features. One of the most common ways to do this is with the **extrude** function, which extends a sketch profile into 3D space. Similar to how you define a sketch, an extrude requires specific parameters. For instance, you must set a **depth** (or final height) to determine how far the shape extends. Adjusting these settings allows you to create precise geometry tailored to your design needs.

<div><figure><img src=".gitbook/assets/image (26).png" alt="" width="375"><figcaption><p>Extruding a hexagon with a depth of 40mm</p></figcaption></figure> <figure><img src=".gitbook/assets/image (23).png" alt="" width="343"><figcaption><p>Revolving around a complex shape to create a candlestick</p></figcaption></figure></div>

**Alternative Approaches**

Instead of extruding, you can use the revolve feature to create certain shapes, such as a candlestick. This method involves rotating a sketch profile around a central axis, forming a continuous shape. Different modeling techniques exist, and the choice depends on the design intent—whether prioritizing manufacturability, editability, or structural integrity.

Every 3D modeling approach has trade-offs, but understanding how features like extrude and revolve work helps you build designs efficiently and with greater control.\
Let me know if you want this adjusted further!
