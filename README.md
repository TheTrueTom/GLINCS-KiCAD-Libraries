# GLINCS-KiCAD-Libraries
KiCAD Libraries used by GLINCS

# Installing
- Clone repository in selected folder (e.g. ~/Documents)
- Add following path (Preferences > Configure Paths):
  - MY3DMOD - '(Chosen folder)/GLINCS-KiCAD-Libraries/3D' (e.g. ~/Documents/GLINCS-KiCAD-Libraries/3D)
- Open Symbol Library Editor
- Open Symbol Libraries Manager (Preferences > Manage Symbol Libraries)
- Browse Libraries and add all files ending in .lib
- Open Footprint Editor
- Open Footprint Libraries Manager (Preferences > Manage Footprint Libraries)
- Browse Libraries and add all folders ending in .pretty

# Requirements
KiCAD 5.0+

# Contribution rules
- One symbol should be associated with one footprint
- Symbol and footprint should share the same name
- Symbols names should be descriptive whenever possible
- Symbols description / keywords and documentation should be filled
- Whenever possible Symbol field be all filled out and should include in addition:
  - Fournisseur 1: 1st supplier's name
  - Ref Fournisseur 1: Reference from the 1st supplier's catalog
  - Fournisseur 2: 2nd supplier's name
  - Ref Fournisseur 2: Reference from the 2nd supplier's catalog
  - Fabricant: Manufacturer's name
  - Ref Fabricant: Reference from the manufacturer's catalog

# Authors
2018 - GLINCS-AXINT, see AUTHORS for more details

# Licence
Proprietary and confidential, see LICENSE for more details
