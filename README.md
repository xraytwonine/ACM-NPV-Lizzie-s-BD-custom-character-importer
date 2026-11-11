# ACM-NPV-Lizzie-s-BD-custom-character-importer
THIS IS NOT A MOD This vibe coded soft takes the new 2.5 compat ACM generated NPV into Lizzie's BD mod as a custom character.

Lizze's BD Custom Character ConverterConvert ACM-created NPVs into custom characters for Lizzie’s Braindances.
LBD CC Converter is a standalone Windows tool that takes an Appearance Creator Mod (ACM) NPV export ZIP and creates a package for Lizzie’s Braindances’ Custom Characters catalog.
Choose your character’s body frame, select the appearances for normal and explicit scenes, and export a Vortex-compatible ZIP.

Features
Reads character names and available appearances from ACM exports.
Separate appearance selections for normal and explicit scenes.
Creates a dedicated Lizzie’s entity with a defined starting appearance.
Preserves the original ACM character assets, including animation and deformation resources.
Uses character-specific filenames for generated archives, scripts, and conversion reports.
Checks the compiled entity’s appearance references and the completed ZIP’s integrity.
Leaves the source ZIP unchanged.

How to use
Extract LBD CC Converter into a writable folder.
Run LBD-CC-Converter.exe.
Select an ACM-exported NPV ZIP containing one character.
Select the character’s Female or Male body frame.
Choose an appearance for normal scenes and another for explicit scenes.
Select an output folder and convert.
Install the generated ZIP through Vortex, deploy, and restart the game.
Find your character in Lizzie’s Custom Characters catalog.
When updating a converted character, replace its previous converted package.

Requirements
For conversion:
Windows
An ACM-created NPV export ZIP
Python, Blender, and NPV Studio do not need to be installed.

In game:
Lizzie’s Braindances and its requirements
Any additional requirements needed by the original ACM character

Current limitations
The converter uses appearances already included in the ACM export. It does not create nude appearances, remove clothing, or edit character meshes.
The complete ACM asset archive is retained. Selecting two appearances does not currently remove the other outfits or reduce their texture footprint.
Compatibility testing is ongoing. Package validation confirms the generated files’ structure and references; each character still requires an in-game test.
