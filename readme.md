# V1 to V2 Zone Converter

This **C# console tool** reads old (v1) JSON files containing `CustomZones` (circle) or `PolygonZones` (polygons) from EMM configurations and **converts** them into a new (v2) JSON format for [NinjinsPvPPvE].

## How It Works
1. **Compile** the C# project into an `.exe`.
2. **Drag & Drop** your old `.json` files onto the `.exe`.
3. The tool detects whether the file has `CustomZones` or `PolygonZones` (or both).
4. It outputs a new file named `<original_filename>_v2.json` in the **same directory**.

## Notes
- Boolean values are turned into **0** or **1**.
- Missing properties (like `notificationColor`) default to **red**.
- Any old custom icon paths such as `"EMM/gui/information.edds"` are updated to a new base path.
- You can modify the code to map additional properties or tweak default behaviors.
