# Image Rendering Checks

When updating page images, verify:

- asset paths and filename casing,
- expected aspect ratio,
- behavior at narrow viewport widths,
- useful alternative text,
- layout stability while loading,
- fallback behavior when an asset is missing.

Inspect the rendered page after changes; do not assume a path is valid because it works on a case-insensitive filesystem.