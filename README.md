# GCodetoSTLBlender

Based on iraytrace's BlenderGcodeImport (https://github.com/iraytrace/BlenderGcodeImport)

Added ability to create watertight parts from GCode, useful for ray tracing analysis in pvTrace.

Added smoothed cross section profile to more closely mimic real-world parts.

Separate files for importing cylic and non-cyclic GCodes, due to open surfaces created at ends of non-cyclic parts.
