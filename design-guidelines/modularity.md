---
icon: puzzle
---

# Modularity

Building your robot with modular subsystems saves hours during testing and events. Modularity means each mechanism can be treated like a black box—built, tested, and repaired independently. Standardization ensures that parts and tools are consistent across your design.

#### What Is Modularity?

A modular subsystem is self-contained:

* It bolts on with a few screws or brackets
* Has a single set of wires or cables going in/out
* Can be removed without disturbing unrelated systems

**Examples:** A fully removable arm module, drivetrain pods, intake trays, or even pre-wired electronics boards.

#### Benefits of Modularity

* **Faster Repairs:** Replace a broken part without taking apart the whole robot.
* **Parallel Development:** Mechanical and electrical team members can work on different modules simultaneously.
* **Easier Iteration:** Test different versions of a mechanism without redesigning the whole robot.
* **Consistent Mounting:** Use standard hole spacings and brackets (e.g., 16mm grid, extrusion mounts).

#### Standardization Tips

* Use common motor types (e.g., all GoBILDA 312 RPM)
* Stick to one bolt size per use-case (M4 for structure, M3 for electronics)
* Use keyed motor shafts or set screw flats consistently
* Design 2D brackets and spacers around common thicknesses (3mm, 6mm, etc.)
