# Braille Variable Font Starter v2

This version matches this model:

- Regular: draw filled dots only at active Braille dot positions.
- Outline 6 Dots / Outline 8 Dots: draw normal filled dots at active positions, and hollow outline dots at inactive positions.
  - The outline hint dot follows `wght`.
- Pinpoint 6 Dots / Pinpoint 8 Dots: draw normal filled dots at active positions, and smaller fixed-size filled dots at inactive positions.
  - The pinpoint hint dot does **not** follow `wght`.

## Axes

- `wght`: active dot diameter
- `CELL`: advance width / cell width only; dot coordinates do not move
- `DDX_`: horizontal distance between left and right dot columns
- `DDY_`: vertical distance between dot rows
