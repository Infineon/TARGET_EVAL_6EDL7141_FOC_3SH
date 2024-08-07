# EVAL_6EDL7141_FOC_3SH BSP Release Notes
The EVAL_6EDL7141_FOC_3SH houses the 6EDL7141 three-phase smart motor driver IC with on board debugger     
**Note:**
Programming this kit requires installing 
[SEGGER J-Link software](https://www.segger.com/downloads/jlink/#J-LinkSoftwareAndDocumentationPack)

NOTE: BSPs are versioned by family. This means that version 1.2.0 of any BSP in a family (eg: PSoC™ 6) will have the same software maturity level. However, not all updates are necessarily applicable for each BSP in the family so not all version numbers will exist for each board. Additionally, new BSPs may not start at version 1.0.0. In the event of adding a common feature across all BSPs, the libraries are assigned the same version number. For example if BSP_A is at v1.3.0 and BSP_B is at v1.2.0, the event will trigger a version update to v1.4.0 for both BSP_A and BSP_B. This allows the common feature to be tracked in a consistent way.

### What's Included?
The EVAL_6EDL7141_FOC_3SH library includes the following:
* BSP specific makefile to configure the build process for the board
* cybsp.c/h files to initialize the board and any system peripherals
* cybsp_types.h file describing basic board setup
* Linker script & startup code for GCC and ARM toolchains
* Configurator design files (and generated code) to setup board specific peripherals
* .lib file references for all dependent libraries
* API documentation

### What Changed?
#### v2.2.1
* Added memory-analyzer configuration support for KIT_XMC11_BOOT_001, KIT_XMC12_BOOT_001, KIT_XMC13_BOOT_001, KIT_XMC14_BOOT_001, KIT_XMC45_RELAX_V1, KIT_XMC_PLT2GO_XMC4200, and KIT_XMC_PLT2GO_XMC4400.
#### v2.2.0
* Added functionality to enable BSP Assistant chip flow
* Added capabilities to match BSPS created by BSP Assistant chip flow
#### v2.1.0
* Add macro `CYBSP_USER_BTN_DRIVE` indicating the drive mode that should be used for user buttons
#### v2.0.0
Note: This revision is only compatible with ModusToolbox Tools 3.0 and newer.
* Updated recipe-make, core-make, and XMClib to new major versions
* Regenerated code with Configurators from ModusToolbox™ v3.0.0
* Renamed top level board makefile to bsp.mk
* Removed version.xml file in favor of new props.json
#### v1.0.0
* Initial production release
#### v0.5.0
* Initial pre-production release

### Supported Software and Tools
This version of the EVAL_6EDL7141_FOC_3SH BSP was validated for compatibility with the following Software and Tools:

| Software and Tools                        | Version |
| :---                                      | :----:  |
| ModusToolbox™ Software Environment        | 3.1.0   |
| GCC Compiler                              | 11.3.1  |

Minimum required ModusToolbox™ Software Environment: v3.0.0

### More information
* [EVAL_6EDL7141_FOC_3SH BSP API Reference Manual][api]
* [EVAL_6EDL7141_FOC_3SH Documentation](https://www.infineon.com/cms/en/product/evaluation-boards/eval_6edl7141_foc_3sh/)
* [Cypress Semiconductor, an Infineon Technologies Company](http://www.cypress.com)
* [Infineon GitHub](https://github.com/infineon)
* [ModusToolbox™](https://www.cypress.com/products/modustoolbox-software-environment)

[api]: https://infineon.github.io/TARGET_EVAL_6EDL7141_FOC_3SH/html/modules.html

---
© Cypress Semiconductor Corporation (an Infineon company) or an affiliate of Cypress Semiconductor Corporation, 2019-2022.