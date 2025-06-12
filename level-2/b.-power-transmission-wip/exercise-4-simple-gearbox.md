# Exercise #4 Simple Gearbox

### Practice Exercises <a href="#practice-exercises" id="practice-exercises"></a>

Get ready to practice! Begin by copying the Stage 2B Exercises Document using the button below, just as you did with the Stage 2A Exercises Document. Each exercise is organized into a folder and includes a **"reference" tab**—a preview of the final model—as well as one or two tabs for completing the exercise.&#x20;

{% hint style="info" %}
[**COPY THIS DOCUMENT**](https://cad.onshape.com/documents/590c0f6b2a80e0dca120c280/w/f3da0f6ce53211134a745ecb/e/f1734caa16f56215c1e2e04f?renderMode=0\&uiState=6849b55e83d04e65c31e0516)
{% endhint %}

### Exercise 4: Simple Gearbox <a href="#exercise-1-simple-gearbox" id="exercise-1-simple-gearbox"></a>

In this exercise, you'll be CADing and assembling a **single-stage gearbox**. The aim is to introduce the basics of designing a simple gear transmission. Along the way, you'll also get hands-on experience with [gears](https://app.gitbook.com/s/D2GXZ5NUEk64Zn6lJiL2/gears), [motors](https://app.gitbook.com/s/D2GXZ5NUEk64Zn6lJiL2/motors), [bearings](https://app.gitbook.com/s/D2GXZ5NUEk64Zn6lJiL2/introduction-to-motion/bearings), c2c, [gear relation](https://app.gitbook.com/s/D2GXZ5NUEk64Zn6lJiL2/gears/gear-ratios), and the [FTC Insert Tool](../../onshape-setup/ftc-insert-tool.md).

#### Layout Sketches <a href="#layout-sketches" id="layout-sketches"></a>

A **layout sketch** captures the fundamental geometry of a design without locking in precise details. By keeping key dimensions flexible, layout sketches facilitate easy adjustments as the design evolves. Moving forward, we'll rely on layout sketches for nearly all designs.

{% tabs %}
{% tab title="Part Studio Instructions" %}
**Navigate to the "Exercise #4 Simple Gearbox" part studio tab** in the copied document and follow the instructions to complete the part studio.



{% stepper %}
{% step %}
### Create a Layout Sketch for the Gearbox

<figure><img src="../../.gitbook/assets/image (42).png" alt=""><figcaption></figcaption></figure>

Draw pitch diameter circles for the 60-tooth and 20-tooth gears. Make them tangent to define the center-to-center distance between the gears. Then, constrain the gear centers so they align vertically.
{% endstep %}

{% step %}
### Create a new sketch for the motor plate.&#x20;

<div><figure><img src="../../.gitbook/assets/image (4).png" alt="" width="325"><figcaption><p> </p></figcaption></figure> <figure><img src="../../.gitbook/assets/image (2) (1).png" alt="" width="375"><figcaption></figcaption></figure></div>

Using the layout as the reference, draw an 8mm hole for the bearing and a 14mm hole for the axle that sticks out from the motor. Note that depending on your manufacturing processes and tolerances, you may need to draw your bearing holes slightly larger or smaller.

Add four mounting holes for the motor and four bolt holes for connecting the two plates using center point rectangles. The circular pattern can also be used to duplicate the circles around the square. Make sure that these rectangles are using construction lines, so it doesn't interfere when we extrude (press q on lines to turn them into construction lines).
{% endstep %}

{% step %}
### Finishing Bottom Plate

<div><figure><img src="../../.gitbook/assets/image (3) (1).png" alt="" width="375"><figcaption></figcaption></figure> <figure><img src="../../.gitbook/assets/image (4) (1).png" alt="" width="375"><figcaption></figcaption></figure></div>

Using center point rectangles, sketch fillets, and 3-point arcs, outline the plate around the holes and the motor outline.

Extrude the motor plate to be 4mm thick.
{% endstep %}

{% step %}
### Creating Spacers

<div><figure><img src="../../.gitbook/assets/image (6).png" alt="" width="375"><figcaption></figcaption></figure> <figure><img src="../../.gitbook/assets/image (7).png" alt="" width="331"><figcaption></figcaption></figure></div>

Create spacers by making the inner diameter 4mm and making the outer diameter the same as the sketch fillet.

Then, extrude the spacer by 7mm.
{% endstep %}

{% step %}
### Creating Top Plate

<div><figure><img src="../../.gitbook/assets/image (11).png" alt="" width="375"><figcaption></figcaption></figure> <figure><img src="../../.gitbook/assets/image (9).png" alt="" width="369"><figcaption></figcaption></figure></div>

By using the Use tool (the cube), you can copy the geometry and holes of the motor plate. Then add a 20mm diameter circle, a line connecting both of the top mounting holes to the circle, and sketch fillets.

Then extrude by 4mm, and fillet the edges of the semi-circle by 5mm.
{% endstep %}

{% step %}
### Countersinking Screw Mounts

<div><figure><img src="../../.gitbook/assets/image (12).png" alt="" width="375"><figcaption></figcaption></figure> <figure><img src="../../.gitbook/assets/image (13).png" alt="" width="375"><figcaption></figcaption></figure></div>

Now create holes for the screws by making circle with a diameter 8mm, extruding them by 2mm, and fillet them by 0.5mm.
{% endstep %}

{% step %}
### Creating a Gear

<div><figure><img src="../../.gitbook/assets/image (14).png" alt=""><figcaption></figcaption></figure> <figure><img src="../../.gitbook/assets/image (15).png" alt=""><figcaption></figcaption></figure></div>

You can create a gear by looking up "Spur Gear" in the "Search tools" search bar. Make the gear have 60 teeth, make it 5mm deep, and make its module 0.8. You can also hide the top plate for a better view of the gear.

{% hint style="info" %}
All GoBILDA gears have a module of 0.8mm
{% endhint %}

Then create the center REX bore by using the circumscribed polygon tool and making a 6-sided shape with a diameter of 8mm.
{% endstep %}

{% step %}
### Finished Part Studio

<figure><img src="../../.gitbook/assets/image (16).png" alt="" width="563"><figcaption></figcaption></figure>

Now the part studio is finished, and you can move on to the assembly.
{% endstep %}
{% endstepper %}
{% endtab %}

{% tab title="Assembly Instructions" %}
**Navigate to the "Exercise #4 Simple Gearbox" assembly tab** in the copied document and follow the instructions to complete the assembly studio.



{% stepper %}
{% step %}
### Starting the assembly

<div><figure><img src="../../.gitbook/assets/image (39).png" alt="" width="353"><figcaption></figcaption></figure> <figure><img src="../../.gitbook/assets/image (38).png" alt="" width="270"><figcaption></figcaption></figure></div>

Import the top and bottom plates as well as the spacer. Mate the spacer to the bottom plate, and use the "replicate" tool to copy the spacers. Then mate the top plate to the spacers.
{% endstep %}

{% step %}
### Import Parts using the FTC Insert Tool

<div><figure><img src="../../.gitbook/assets/image (40).png" alt="" width="275"><figcaption></figcaption></figure> <figure><img src="../../.gitbook/assets/image (41).png" alt="" width="282"><figcaption></figcaption></figure></div>

Insert the Bearings and the axle from the FTC Insert tool, as well as the gear from the part studio. Then, mate the bearing to the bottom plate, and mate the gear to the rotating part of the bearing. Mate the other bearing to the top plate and then mate it to one of the spacers.
{% endstep %}

{% step %}
### Import the rest of the Parts

<div><figure><img src="../../.gitbook/assets/image (2).png" alt="" width="375"><figcaption></figcaption></figure> <figure><img src="../../.gitbook/assets/image.png" alt="" width="375"><figcaption></figcaption></figure></div>

Import the rest of the parts, and mate the 20-tooth gear onto the rotating shaft. Then mate the screws and use the replicate tool to replicate the screw mates.
{% endstep %}

{% step %}
### Gear Relation

<div><figure><img src="../../.gitbook/assets/image (3).png" alt="" width="563"><figcaption></figcaption></figure> <figure><img src="../../.gitbook/assets/Recording2025-06-12085143-ezgif.com-video-to-gif-converter.gif" alt="" width="375"><figcaption></figcaption></figure></div>

Create a gear relation by choosing the two revolute mates that are mated to your gears. You can do this by clicking on the motor and the bearing dropdowns and going to mates, where you click the revolute mate. Now, calculate the [gear ratio](https://app.gitbook.com/s/D2GXZ5NUEk64Zn6lJiL2/gears/gear-ratios) and reverse the direction.
{% endstep %}
{% endstepper %}
{% endtab %}
{% endtabs %}
