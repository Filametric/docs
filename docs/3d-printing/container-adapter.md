---
comments: true
---
# Container adapter

![Container adapter](../images/3d-printing/container-adapter.webp)

The container adapter connects the drybox container to the heating unit. The 3MF file is pre-configured for a Bambu Lab H2S printer with the settings below already applied. If you are using a different printer, use the settings below as a reference.

A STEP file is also included for users who wish to slice the model independently or adapt it for a different printer.

| | |
|---|---|
| **Dimensions** | 60 x 60 x 16 mm |
| **Estimated print time** | ~32 minutes |
| **Recommended material** | ABS |

---

## Before you print

!!! warning "ABS requires proper ventilation"
    ABS produces fumes during printing. Make sure your printer is enclosed and the room is well ventilated.

!!! warning "Pre-drying is required"
    ABS is sensitive to moisture and **must** be dried before printing. Follow the filament manufacturer's drying instructions.

---

## Filament settings

The .3mf file uses the generic Bambu Lab ABS profile. No parameters were changed from the default profile.

It is recommended to use **ABS**, as this part has been tested and validated with Bambu Lab ABS. Other ABS brands should work as well.

!!! warning "Other materials"
    Other materials may work but have not been officially tested or validated. Using alternative materials is at your own risk and may affect dimensional accuracy and fit.

---

## Workspace settings

The following workspace settings were changed from the default settings:

| Setting | Value |
|---|---|
| Layer height | **0.2 mm** |
| Build plate | **Engineering plate** |
| Sparse infill pattern | **Gyroid** |
| Supports | **disabled** |

!!! note "No adhesives needed"
    No glue or other adhesives are required on the engineering plate for this print.

### Modifiers

Two (yellow) modifiers were added to the model to apply 100% infill around the screw hole areas to ensure a strong, reliable connection during assembly. **Do not remove or modify them.**

![Modifiers](../images/3d-printing/container-adapter-modifiers.webp)

---

## License & Disclaimer

!!! note "CC BY-NC 4.0"
    All files on this page are licensed under [CC BY-NC 4.0](https://creativecommons.org/licenses/by-nc/4.0/){:target="_blank"}. You are free to download, print, share and adapt them, as long as you credit Filametric and do not use them for commercial purposes. Printing parts for your own personal or business use is permitted. Selling the files or using them to build competing products is not.

!!! warning "Disclaimer"
    These files are provided as-is. Modifications to the model, print settings or orientation may affect fit and function and are at your own risk. See our [Terms of Use](https://filametric.com/terms-of-use){:target="_blank"} for more information.

---

## Downloads

- [:material-download: Container Adapter (.step)](../downloads/Filametric_Container_Adapter_STEP.step)


