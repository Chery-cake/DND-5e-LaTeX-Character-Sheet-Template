# DND 5e LaTeX Character Sheet Template

> LaTeX template to typeset Dungeons and Dragons 5th edition character sheets.

## Features

* Character and Spell sheets
* High degree of customisation available
* Works with XeLaTeX locally

<img src=https://github.com/Chery-cake/DND-5e-LaTeX-Character-Sheet-Template/raw/main/bard-druid_character_sheet.png/>


## Usage

### Building a character sheet

It is reccomended to look at pre-existing character sheets in the `characters` directory when using this repository for the first time, each text input area of the character sheet is fillable with functions defined in the template, however it may require some trial and error to have the sheet looking as you intend.

### Compliation

The example or specific character sheets can be compiled using the following `make` commands:

``` console
make example              # Will complile the example "unnamed" character

make character_name.pdf   # Will compile a character by name from the character directory
```

### Customisation

There are a large number of character sheet customisation options available in [`dndtemplate.sty`](https://github.com/matsavage/DND-5e-LaTeX-Character-Sheet-Template/blob/main/dndtemplate.sty) which acts a central location to modify colour and opacity for a number of character sheet elements. There are some commands in `sheet-calculations` that were made to auto calculate the modifiers and proficiencies, and auto complete a few inputs.

## Dependencies

This package requires LaTeX and the [DnD 5e LaTeX Template](https://github.com/rpgtex/DND-5e-LaTeX-Template). I reccomend using the [instructions](https://github.com/rpgtex/DND-5e-LaTeX-Template/tree/355b9ced1b42324574c2c4e28f9783f29c760a20#dependencies) provided with this package to set up your environment if not using the included GitHub action.

## Credits

* This package was generated from the standard Wizards of the Coast [PDF character sheet](https://media.wizards.com/2016/dnd/downloads/5E_CharacterSheet_Fillable.pdf) template
