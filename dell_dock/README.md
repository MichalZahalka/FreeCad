# Dell SD25TB5 Under-Desk Mount

FreeCAD project files and print exports for an under-desk mount for the Dell SD25TB5 Docking Station (Dell Pro Thunderbolt 5).

## Parts

- `under_desk_mount` is the main holder fixed to the underside of the desk.
- `clearance_spacer` is a small spacer block that is glued on top of the holder to remove the gap between the holder and the desk surface.
- `m4_alignment_bushing_v1` is the retained screw-locating sleeve that slips over an M4 screw and helps center the dock in the holder during installation.

## Print Set

- Print `1x under_desk_mount`
- Print `3x clearance_spacer`
- Print `2x m4_alignment_bushing_v1`
- Material: `PETG`

## Hardware

- Screw size: `M4`
- Tested screw thread length: `8 mm`

## Files

- `under_desk_mount.FCStd` is the main editable holder source.
- `clearance_spacer.FCStd` is the editable spacer source.
- `m4_alignment_bushing_v1.FCStd` is the retained source file for the M4 locating sleeve.
- `exports/under_desk_mount.stl` is the main current mesh export for the holder.
- `exports/clearance_spacer.stl` is the main current mesh export for the spacer.
- `exports/m4_alignment_bushing_v1.stl` is the retained mesh export for the M4 locating sleeve.
- `exports/under_desk_mount_legacy_export.stl` is an older mesh export kept for reference.
- `exports/under_desk_mount_print_plate.3mf` is a prepared print file.

## Assembly Notes

1. Attach the main holder to the underside of the desk.
2. Glue the three spacer blocks on top of the holder where needed to eliminate play against the desk.
3. Slide `m4_alignment_bushing_v1` onto each M4 screw.
4. Insert the dock into the holder.
5. Fasten the dock using M4 screws with an 8 mm thread length.

## Notes

- Printable outputs are stored in the `exports/` directory to keep source models separate from generated files.
- Backup `*.FCBak` files are intentionally ignored by Git.