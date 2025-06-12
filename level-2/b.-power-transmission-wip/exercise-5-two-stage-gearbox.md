# Exercise #5 Two-Stage Gearbox

### Exercise 5: Two-Stage Gearbox

In this exercise, you'll be CADing and assembling a **two-stage gearbox**. The goal is to build experience with more advanced gearbox designs. Additionally, you'll learn how to use the[ **Part Lighten Featurescript**](../../featurescripts.md#part-lighten) to optimize and reduce weight in your components.

{% tabs %}
{% tab title="Part Studio Instructions" %}
**Navigate to the "Exercise #5 Two-Stage Gearbox" tab** in the copied document and follow the instructions to complete the part studio.



{% stepper %}
{% step %}
### Create a Layout Sketch

<figure><img src="../../.gitbook/assets/image (43).png" alt=""><figcaption></figcaption></figure>

Draw pitch diameter circles for the 60-tooth and 20-tooth gears. Make them tangent to define the center-to-center distance between the gears. Then, constrain the gear centers so they align vertically and horizontally.
{% endstep %}

{% step %}
### Create a new sketch for the motor plate. <a href="#create-a-new-sketch-for-the-motor-plate" id="create-a-new-sketch-for-the-motor-plate"></a>

<div><figure><img src="../../.gitbook/assets/image (46).png" alt="" width="375"><figcaption></figcaption></figure> <figure><img src="../../.gitbook/assets/image (45).png" alt="" width="375"><figcaption></figcaption></figure></div>

Using the layout as the reference, draw 14mm holes for the bearings. Note that depending on your manufacturing processes and tolerances, you may need to draw your bearing holes slightly larger or smaller.

Add four mounting holes for connecting the motor plates, and begin adding circles to create the geometry of the plate.
{% endstep %}

{% step %}
### Finishing Top Plate <a href="#finishing-bottom-plate" id="finishing-bottom-plate"></a>

<div><figure><img src="../../.gitbook/assets/image (47).png" alt=""><figcaption></figcaption></figure> <figure><img src="../../.gitbook/assets/image (48).png" alt=""><figcaption></figcaption></figure></div>

Using center lines, sketch fillets, 3-point arcs, and the mirror tool, finish sketching the geometry of the top plate.

Extrude the motor plate to be 4mm thick.
{% endstep %}

{% step %}
### Creating Spacers

<div><figure><img src="../../.gitbook/assets/image (49).png" alt="" width="375"><figcaption></figcaption></figure> <figure><img src="../../.gitbook/assets/image (50).png" alt="" width="375"><figcaption></figcaption></figure></div>

Create spacers by making the inner diameter 4mm and making the outer diameter the same as the sketch fillet.

Then, extrude the spacer by 12 mm.
{% endstep %}

{% step %}
### Creating Bottom Plate <a href="#creating-top-plate" id="creating-top-plate"></a>

<div><figure><img src="../../.gitbook/assets/image (51).png" alt="" width="375"><figcaption></figcaption></figure> <figure><img src="../../.gitbook/assets/image (52).png" alt="" width="375"><figcaption></figcaption></figure></div>

By using the "Use" tool (the cube), you can copy the geometry and holes of the top motor plate. Then add a 16x16mm center point rectangle for the motor mount and mirror it to the other side.

Then, extrude by 4mm.
{% endstep %}

{% step %}
### Countersinking Screw Mounts <a href="#countersinking-screw-mounts" id="countersinking-screw-mounts"></a>

<div><figure><img src="../../.gitbook/assets/image (54).png" alt=""><figcaption></figcaption></figure> <figure><img src="../../.gitbook/assets/image (53).png" alt=""><figcaption></figcaption></figure></div>

Now create holes for the screws by making circle with a diameter 8mm, extruding them by 2mm, and fillet them by 0.5mm.
{% endstep %}

{% step %}
### Creating the gears

<div><figure><img src="../../.gitbook/assets/image (55).png" alt=""><figcaption></figcaption></figure> <figure><img src="../../.gitbook/assets/image (56).png" alt=""><figcaption></figcaption></figure></div>

Make the gear have 60 teeth, make it 5mm deep, and make its module 0.8. You can also hide the top plate for a better view of the gear.

Make a second gear with 20 teeth, and 5mm deep, and make its module 0.8 as well.
{% endstep %}

{% step %}
### Pocketing the Top Plate

<div><figure><img src="../../.gitbook/assets/image (59).png" alt=""><figcaption></figcaption></figure> <figure><img src="../../.gitbook/assets/image (61).png" alt=""><figcaption></figcaption></figure></div>

In order to pocket the plates, make sure to make a new sketch and create rib lines. Now use the "Part Lighten" Feature Scripts and click on the top plate and the new sketch you created for the rib lines.
{% endstep %}

{% step %}
### Pocket Bottom Plate

<div><figure><img src="../../.gitbook/assets/image (62).png" alt=""><figcaption></figcaption></figure> <figure><img src="../../.gitbook/assets/image (63).png" alt=""><figcaption></figcaption></figure></div>

To pocket the other plate, click the face of the bottom plate, and use the same rip line sketch for the bottom plate's rib lines.
{% endstep %}

{% step %}
### Gear Spacer and Finished Part Studio

<div><figure><img src="../../.gitbook/assets/image (69).png" alt=""><figcaption></figcaption></figure> <figure><img src="../../.gitbook/assets/image (70).png" alt=""><figcaption></figcaption></figure></div>

Create a new sketch, draw a 10mm circle, and using the circumscribed polygon tool and make a 6-sided shape with a diameter of 8mm.

Extrude by 5mm, and you can start the [assembly](exercise-5-two-stage-gearbox.md#assembly-instructions).
{% endstep %}
{% endstepper %}
{% endtab %}

{% tab title="Assembly Instructions" %}
**Navigate to the "Exercise #5 Two-Stage Gearbox" assembly tab** in the copied document and follow the instructions to complete the assembly studio.





{% stepper %}
{% step %}
### Starting the assembly <a href="#starting-the-assembly" id="starting-the-assembly"></a>

<div><figure><img src="../../.gitbook/assets/image (65).png" alt=""><figcaption></figcaption></figure> <figure><img src="../../.gitbook/assets/image (66).png" alt=""><figcaption></figcaption></figure></div>

Import the top plates, bottom plates, spacer, and the gears. Mate the spacer to the bottom plate, and use the "replicate" tool to copy the spacers. Then mate the top plate to the spacers.
{% endstep %}

{% step %}
### Import Parts using the FTC Insert Tool <a href="#import-parts-using-the-ftc-insert-tool" id="import-parts-using-the-ftc-insert-tool"></a>

<div><figure><img src="../../.gitbook/assets/image (67).png" alt="" width="375"><figcaption></figcaption></figure> <figure><img src="../../.gitbook/assets/image (71).png" alt="" width="173"><figcaption></figcaption></figure></div>

Import the bearings, an 8mm standoff, and a 58mm axle. Once mated to the bottom plate, add the gears, the gear spacer, and the final bearings.
{% endstep %}

{% step %}
### Import the remaining Parts

<div><figure><img src="../../.gitbook/assets/image (74).png" alt=""><figcaption></figcaption></figure> <figure><img src="../../.gitbook/assets/image (76).png" alt=""><figcaption></figcaption></figure></div>

Import the rest of the parts, and mate the 20-tooth gears onto the rotating shaft. Then mate the screws and use the replicate tool to replicate the screw mates.

Don't forget to add screws to the standoff to hold it in place.
{% endstep %}

{% step %}
### Gear Relation

<div><figure><img src="../../.gitbook/assets/image (77).png" alt="" width="375"><figcaption></figcaption></figure> <figure><img src="../../.gitbook/assets/Recording2025-06-12130545-ezgif.com-video-to-gif-converter.gif" alt="" width="375"><figcaption></figcaption></figure></div>

Now, create 3 different gear relations by choosing the two revolute mates that are mated to your gears. You can do this by clicking on the motor and the bearing dropdowns and going to mates, where you click the revolute mate. Now, calculate the [gear ratio](https://www.ftcwiki.org/transmitting-power/gears/gear-ratios) and reverse the direction.
{% endstep %}
{% endstepper %}
{% endtab %}
{% endtabs %}



