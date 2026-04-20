# FreeCAD Models Repository

This repository contains a collection of FreeCAD projects, printable part designs, prototypes, and archived iterations for various personal hardware and 3D modeling experiments.

The workspace is organized as a practical design archive rather than a single product. Individual folders typically represent separate projects, assemblies, or component families.

## Repository Contents

You will find a mix of:

- `*.FCStd` FreeCAD source files
- `*.stl` exported meshes for slicing or printing
- `*.3mf` exported print-ready files
- project folders containing related parts, revisions, and support geometry

Examples of project areas in this repository include holders, brackets, display parts, hinges, Raspberry Pi related enclosures, docking accessories, and VESA-mounted components.

## Folder Structure

There is no strict single-project layout. In general:

- the repository root may contain standalone FreeCAD files
- subfolders usually group parts belonging to one assembly or use case
- older iterations are often preserved as backup files instead of being deleted

This makes the repository suitable both as a working design space and as a history of past revisions.

## Recommended Tools

To work with the source models, use:

- FreeCAD
- a slicer application for `*.stl` or `*.3mf` exports when preparing prints

Version compatibility in FreeCAD can vary. When possible, open files with the same or a newer FreeCAD version than the one originally used to save them.

## Working With The Files

1. Open the relevant `*.FCStd` file in FreeCAD.
2. Review the model tree and spreadsheet parameters, if present.
3. Update geometry as needed.
4. Re-export meshes to `*.stl` or `*.3mf` for manufacturing or printing.
5. Keep previous versions when they provide useful design history.

## Naming And Revisions

This repository includes timestamped backups and variant filenames. That is intentional and helps preserve design evolution during iterative CAD work.

Common patterns include:

- numbered variants such as `holder_1`, `holder_2`, or similar
- separate files for supports, screws, adapters, or printable sub-parts

## Notes

- Not every file is guaranteed to be a finished production model.
- Some folders may contain experiments, temporary variants, or export artifacts.
- Backup files are useful for rollback and comparison, but are usually not meant to be edited directly unless needed.

## License

Unless noted otherwise, the models and source files in this repository are licensed under the Creative Commons Attribution 4.0 International license (CC BY 4.0).

This allows copying, redistribution, modification, and commercial use, provided that appropriate credit is given to the original author.

For the full license text, see the [LICENSE](LICENSE) file or visit https://creativecommons.org/licenses/by/4.0/.