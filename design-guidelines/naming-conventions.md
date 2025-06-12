# Naming Conventions

CAD files can become a mess faster than your pit table if you don’t stay organized. Clean file structure and naming make it easier for multiple people to collaborate and modify the design as it evolves.

#### Naming Conventions

Good names are:

* **Descriptive** (e.g., `right_drive_motor_mount` vs. `part3`)
* **Consistent** (stick to lower\_case\_with\_underscores or CamelCase—not both)
* **Structured** by category: `drive_`, `intake_`, `arm_`, etc.

#### Folder and Feature Management

* Organize parts into folders by subsystem
* Name sketches, features, and planes clearly (`sketch_belt_profile`, `plane_mount_face`)
* Use labels or custom colors to differentiate moving vs. fixed parts

#### Version Control

* Use `V1`, `V2`, etc. in part names or folders when iterating
* Archive old versions instead of deleting
* Record design decisions in comments or a changelog

#### Onshape Tips

* Use Part Studios to group related geometry
* Use Assembly tabs to simulate movement and fit
* Use variable naming for constants like extrusion length, spacing, or hole offsets
