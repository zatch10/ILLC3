# ILLC3 

ILLC3 is a Visual Studio code extention that adds native support to Visual Studio Code for lc3 assembly. 
LC3 is a popular educational assembly language used to teach the fundamentals of computer engineering at various universities such as UIUC, UT Austin, UPenn and many more.

## Installation

### Final Product Installation (via Marketplace)
* Simply look for **ILLC3** and hit **install** and you're good to go!

### Repo install with Source Code
* **Clone** this repo and unzip the .zip file.
* Open VSCode and navigate **File** &rarr; **Open** &rarr; **Choose the extension folder**
* Press **F5** to use the extension in a simulated environment.
* You're ready to go now!!!
* We expect to have the extension available on the VS Code Extensions marketplace very soon!

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

* Debugging requires LC3 tools to be installed in your unix terminal (supported only with linux/mac or a linux subsystem for windows): https://github.com/haplesshero13/lc3tools

## Future Additions
* Native support for debugging LC3 is in the works! If you think you can help us out, feel free to submit a PR!

## Release Notes
NOW LIVE IN THE VS CODE MARKETPLACE!!!

### 1.0.6

#### Initial release of ILLC3

-----------------------------------------------------------------------------------------------------------

Made with <3 @ HackIllinois 2019

