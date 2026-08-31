# OpenTactileAbacus

A 3D-printable abacus designed for visually impaired users.

[日本語版README](README_jp.md) | [Thingiverse](https://www.thingiverse.com/thing:7402750) | [MakerWorld](https://makerworld.com/ja/models/3242916-opentactileabacus-ver-2026#profileId-3674481)

## Product Images

### 23-Digit Abacus

<img src="image_for_readme/23digits.png" alt="Completed 23-digit abacus" width="400">
<img src="image_for_readme/23digits_print.png" alt="Printed 23-digit abacus" width="400">

## Features

- **Tactile-Optimized Design**: Beads and frame designed for fingertip operation by visually impaired users
- **Print-in-Place Model**: The frame and beads are printed together, so the beads do not need to be installed separately
- **Split Frame**: Print the left and right frame sections and join their dovetail connectors to complete the abacus
- **3D-Printable**: Compatible with standard 3D printers

## File Structure

```
├── README.md              # English README (this file)
├── README_jp.md           # Japanese README
├── 3mf/
│   └── 23digits_abacus.3mf          # 23-digit abacus (3MF format)
├── autodesk_fusion/
│   ├── 23digits_abacus.f3z          # Source file (Fusion 360)
│   └── 23digits_abacus.step         # Exchange CAD file (STEP format)
└── stl/
    ├── 23digits_abacus_left.stl     # Left section of the 23-digit abacus (STL format)
    └── 23digits_abacus_right.stl    # Right section of the 23-digit abacus (STL format)
```

## Available Models

### 23-Digit Abacus

- **3MF File (Recommended)**: `3mf/23digits_abacus.3mf`
- **STL Files**:
  - `stl/23digits_abacus_left.stl`
  - `stl/23digits_abacus_right.stl`

### Source Files

Fusion 360 source files are provided for customization and improvement:

- `autodesk_fusion/23digits_abacus.f3z`
- `autodesk_fusion/23digits_abacus.step`

## Print Specifications

### Tested Print Environment

- **3D Printer**: Bambu Lab X1 Carbon
- **Other Compatible Printers**:
  - Standard FDM 3D printers with a 0.4 mm nozzle
  - Printers with a sufficient build volume

### Recommended File Format

- **3MF File (Recommended)**: Includes print settings and supports optimized for Bambu Lab printers
  - The included profile uses **Bambu Support For PLA/PETG as filament 2 for the support interfaces** and sets the top Z distance to `0 mm`. Map filament 2 to the specified support material and use an AMS or an equivalent multi-material setup.
  - Do not map both filament slots to the same PLA spool without first adding a removable interface gap; the zero-gap interfaces may bond to the print-in-place parts.
- **STL Files**: For other printers or custom slicer settings
  - **Important (Bambu Studio)**: Set **Slice gap closing radius** (`slice_closing_radius`) to `0.02 mm` before slicing

### Recommended Settings

- **Layer Height**: 0.2 mm
- **Infill**: 15–20%
- **Supports**: May be required (refer to the layout and settings in the 3MF file)
- **Print Time**:
  - 23-digit version: Approximately 12 hours (one build plate)
- **Filament Usage**:
  - 23-digit version: Approximately 280 g
- **Material**: PLA recommended (ABS and PETG are also supported)

Print time and filament usage are estimates based on the Bambu Lab X1 Carbon.

### Post-Processing

1. Carefully remove the support material.
2. Insert a flat-head screwdriver with an approximately 3 mm-wide tip into the hole at the bottom of each bead. Move the bead back and forth several times to break the bonds formed during printing.

   <img src="image_for_readme/assembly.jpg" alt="Using a flat-head screwdriver in the hole at the bottom of a bead to release print bonds" width="400">

3. Check that each bead moves along its rod.
4. If a bead is tight, move it back and forth repeatedly to wear in the sliding surfaces. If it remains tight, lightly sand the rod.
5. Make sure all beads move smoothly and provide comfortable tactile operation for visually impaired users.

> **Caution**: Work carefully and do not apply excessive force, as the screwdriver could damage the printed parts or cause injury.

## Assembly Instructions

### Using the 3MF File (Recommended)

1. Open `3mf/23digits_abacus.3mf` in Bambu Studio and print the left and right sections.
2. Follow the post-processing instructions above to remove supports and release the beads.
3. Join the dovetail connectors on the left and right sections.
4. Confirm that every bead moves smoothly.

### Using the STL Files

1. Import `stl/23digits_abacus_left.stl` and `stl/23digits_abacus_right.stl` into your slicer.
2. If you use Bambu Studio, set **Slice gap closing radius** (`slice_closing_radius`) to `0.02 mm`.
3. Set an appropriate orientation and supports, then print both sections.
4. Follow the post-processing instructions above to remove supports and release the beads.
5. Join the dovetail connectors on the left and right sections.
6. Confirm that every bead moves smoothly and adjust as needed.

## Usage

### Basic Operation

1. Five-value bead (upper bead): Each bead represents 5.
2. One-value beads (lower beads): Each bead represents 1, with four beads per digit representing values up to 4.
3. Move the beads with your fingertips to represent numbers and perform calculations.

## Contributions and Improvements

Contributions to this project are welcome:

- **Issues**: Report bugs or suggest improvements
- **Pull Requests**: Submit design improvements or documentation updates
- **Discussions**: Share user feedback and examples of educational use

## Support and Contact

- **Issues**: Please use the GitHub Issues tab for questions and reports
  - Examples:
    - Requests for different size variations
    - Surface textures that improve tactile identification
    - Better assembly methods
    - Expanded educational guides

- **Discussions**: Exchange information through GitHub Discussions
- **Email**: takumi1988okamoto@gmail.com

## Credits

This project was created to support the education of visually impaired people and promote numeracy learning.

We hope it contributes to a more accessible society.

## Related Links

- [Thingiverse](https://www.thingiverse.com/thing:7402750)
- [MakerWorld](https://makerworld.com/ja/models/3242916-opentactileabacus-ver-2026#profileId-3674481)

## License

This work is licensed under the Creative Commons Attribution 4.0 International License (CC BY 4.0).

© 2025–2026 Takumi Okamoto

See the [LICENSE](LICENSE) file for details.
Please also read the [Disclaimer](DISCLAIMER.md) before use.

---

**We hope this project makes a meaningful contribution to the learning and daily lives of visually impaired people.**
