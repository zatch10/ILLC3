# ILLC3 

ILLC3 is a Visual Studio code extention that adds native support to Visual Studio Code for lc3 assembly. 
LC3 is a popular educational assembly language used to teach the fundamentals of computer engineering at various universities such as UIUC, UT Austin, UPenn and many more.

## Installation

Currently this repo needs to be cloned and launched from Visual Studio Code although we expect to have it available in the VS Code Extensions marketplace very soon!

## Features

* Syntax highlighting for LC3 including differentiation between operands, registers, comments, pseudo-ops, and data types

* Auto complete support in the form of RTL statements for operands and pseudo-ops  

* Shortcuts implemented for various operands:
    1. shift + enter + a     --> inserts ADD
    2. shift + enter + d     --> inserts AND
    3. shift + enter + b     --> inserts BR
    4. shift + enter + q     --> inserts JMP
    5. shift + enter + j     --> inserts JSR
    6. shift + enter + y     --> inserts JSRR
    7. shift + enter + right --> inserts LD
    8. shift + enter + i     --> inserts LDI 
    9. shift + enter + r     --> inserts LDR
   10. shift + enter + e     --> inserts LEA
   11. shift + enter + n     --> inserts NOT
   12. shift + enter + left  --> inserts ST
   13. shift + enter + t     --> inserts STI
   14. shift + enter + =     --> inserts STR
> Tip: The auto complete code pastes a template for registers that can be edited in succession using the Tab button <br>
> Note: When entering shortcuts press shift + enter together, then press the necessary key
## Requirements

* Debugging requires lc3 simulator to be installed in your unix terminal (supported only with linux/mac or a linux subsystem for windows): https://github.com/haplesshero13/lc3tools

## Known Issues

* Debugging bash script needs to be updated

## Future Additions
* Native support for debugging LC3 is in the works! If you think you can help us out, feel free to submit a PR!

## Release Notes

### 1.0.0

#### Initial release of ILLC3

-----------------------------------------------------------------------------------------------------------

Made with <3 @ HackIllinois 2019

