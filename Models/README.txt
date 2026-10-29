Bundled NAM model
=================

preset.NAM is the bundled copy of the user-provided LA-2A Leveling – Light.nam
(Neural Amp Modeler JSON format, version 0.7.0, architecture SlimmableContainer).

In the plugin, click "load NAM model" and select Models/preset.NAM.
The model is not automatically loaded: this keeps model activation explicit and
avoids hard-coded paths that break when a VST3 is moved to another computer.

NAM Core v0.5.4 is fetched by CMake during configure/build. The plugin expects a
mono-in / mono-out NAM model and creates independent model instances for L/R.
