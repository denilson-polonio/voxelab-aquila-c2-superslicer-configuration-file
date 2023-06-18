#### **_Configuration based on Ender-3 v2_**
**SuperSlicer Version:** *_2.5.59.2_*
**File:** [Download](https://github.com/denilson-polonio/voxelab-aquila-c2-superslicer-configuration-file/blob/main/SuperSlicer_config_bundle.ini)

## Basic settings
- **Temperature of the print bed:** 60°C
- **Height of the first layer:** 0.2mm
- **Base layer height:** 0.15mm
- **Maximum print height:** 200mm
- **Nozzle diameter:** 0.4mm
- **Max printing speed:** 70mm/s
- **Displacement speed:** 130mm/s

## Fill and layers
- **Fill pattern:** gyroid
- **Density of filling:** 5%
- **Top solid layers:** 5
- **Bottom solid layers:** 5
- **Bottom Fill Pattern:** monotonic
- **Minimum solid layer thickness:** 0.2mm
- **Minimum upper solid layer thickness:** 0mm

## Perimeters
- **Number of perimeters:** 3
- **External perimeter extrusion thickness:** 0.42mm
- **External perimeter speed:** 60mm/s
- **Lower perimeter speeds:** 50% of maximum print speed

## Supports
- **Supports Enabled:** Yes
- **Bridge angle:** 0°
- **Distance between supports and objects:** 0.2mm
- **Support Interface Layer Thickness:** 0.35mm
- **Number of Media Interface Layers:** 3
- **Media fill pattern:** rectilinear
- **Mount Spacing:** 2.5mm
- **Media Print Speed:** 60mm/s

## Other
- **Gcode Flavor:** marlin
- **Printer model:** ENDER3V2
- **Default filament profile:** "Generic PLA @CREALITY"
- **Default print profile:** 0.16mm OPTIMAL @CREALITY
- **Filament diameter:** 1.75mm
- **Filament color:** #FFFFFF
- **Filament Material:** PLA
- **Filament Density:** 1.24g/cm³
- **Retraction speed:** 25mm/s
- **Color change gcode:** M600
- **Bridge fan speed:** 100%
- **Gcode to pause printing:** Not specified
