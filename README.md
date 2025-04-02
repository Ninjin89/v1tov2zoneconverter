# V1 to V2 Zone Converter

This **C# console tool** reads old (v1) JSON files containing `CustomZones` (circle) or `PolygonZones` (polygons) from EMM configurations and **converts** them into a new (v2) JSON format for [NinjinsPvPPvE].

## How It Works
1. **Drag & Drop** your old `.json` files onto the `.exe`.
2. The tool detects whether the file has `CustomZones` or `PolygonZones` (or both).
3. It outputs a new file named `<original_filename>_v2.json` in the **same directory**.
