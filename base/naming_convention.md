# Naming Convention

## Rules

1. ASCII only! 🦅
2. “No gaps, no caps”
	1. Do not use any spaces
		1. And if needed for readability, use an _ (underscore) instead
	2. Do not use any capital letters
		1. The sole exception to this rule are the `README.md` files describing our folders
3. Identify files hierarchically — in segments separated by ~ (tilde)
	- A bit like how `/` denotes child folders, but within a file name!
	2. Beginning with the most general root
        1. It needs to uniquely identify the file within the current folder, and none higher
            1. If a file is moved after creation, edit the name if so required
		1. Folders in apps with strict hierarchical organization qualify for this rule
			- Like Krita, but unlike Blender with its taglike collections!
	3. Then successively more specific segments
		- For example, a characters model, then the section of the model, etc.
5. Optionally, suffix segments if they’re variants — separated by . (period)
	- For example, an apple prop begins as an red apple, but down the line we might need a version of it that’s green, or one that has been partially eaten; all of these are variants
	1. There can be zero or more such variant suffixes
		1. The order does not matter
		1. But try to be consistent

## Example 

`draft/char/jhinge_pisi.chef.winter~model.lowpoly.blend`
- `draft/char` are the folders this file is under
- `jhinge_pisi.chef.winter` is the first segment
	- `jhinge_pisi` is the unique identity of this character
	- But `chef` and `winter` are variants that specify this particular version of her
- `model.lowpoly` is the next child segment
- `.blend` is the actual file-extension
	- It’s always last, so unambiguous from variants
	- But even if we were to think of it as a variant, it still makes sense!