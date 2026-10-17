# gadgets-colorwells

ColorWells for the gadgets of [polpo](https://github.com/polpo-system/polpo): a gadget that shows a
colour; drag the colour (middle and right mouse button) onto another well or onto a gadget with a
Color attribute.

```
portia.Install gadgets-colorwells
```

## Using

    Gadgets.Insert ColorWells.NewColorWell ~    a colour well at the caret

## What is here

    src/ColorWells.Mod        the colour well
    tools/ColorWells.Tool
    test/ColorWellsTest.Mod

ColorWells is by Erich Oswald. The source comes from ETH Linux Oberon (OLR, 2017-06-18), converted from an Oberon text to plain
text; the first commit has it unchanged. It compiles unchanged with all five of polpo's compilers
(x86, ARM, ARMv7, RISC-V, MIPS).

## Tests

    ColorWellsTest.Run      1 check: a colour well made; it needs the desktop's display

The license is GPL-3 (`LICENSE`); the code comes from ETH Oberon, whose license (`LICENSE.ETH`)
asks to keep its copyright notice and conditions, which `LICENSE.ETH` does.
