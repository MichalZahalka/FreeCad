# Dell SD25TB5 Under-Desk Mount

FreeCAD project files and print exports for an under-desk mount for the Dell SD25TB5 Docking Station (Dell Pro Thunderbolt 5).

## Parts

- `under_desk_mount` is the main holder fixed to the underside of the desk.
- `clearance_spacer` is a small spacer block that is glued on top of the holder to remove the gap between the holder and the desk surface.
- `m4_alignment_bushing` is a small plastic sleeve/bushing that slips over an M4 screw and locates in the mounting holes of the holder while the dock is being screwed in place.

## Print Set

- Print `1x under_desk_mount`
- Print `3x clearance_spacer`
- Print `m4_alignment_bushing` as needed for the number of screws used to attach the dock

## Files

- `under_desk_mount.FCStd` and `under_desk_mount.stl` are the main current holder files.
- `clearance_spacer.FCStd` and `clearance_spacer.stl` are the current spacer files.
- `m4_alignment_bushing.FCStd` and `m4_alignment_bushing.stl` are the current screw sleeve files.
- `m4_alignment_bushing_v1.*` is an older variant kept for reference.
- `under_desk_mount_legacy_export.stl` is an older mesh export kept for reference.
- `under_desk_mount_print_plate.3mf` is a prepared print file.

## Assembly Notes

1. Attach the main holder to the underside of the desk.
2. Glue the three spacer blocks on top of the holder where needed to eliminate play against the desk.
3. Slide an `m4_alignment_bushing` over each M4 screw used for mounting the dock.
4. Insert the dock into the holder and tighten the screws into the docking station.

## Notes

- Backup `*.FCBak` files are intentionally ignored by Git.
- The bushing part is named after its function here; in practice it works as a locating sleeve around the M4 screw.