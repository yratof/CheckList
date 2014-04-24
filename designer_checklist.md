# Designer Checklist

### So you think you've finished your design? Well, that might be the case, but just run through this list to make sure you've covered everything. And I mean everything.

---

## Responsive Design

---

### Is there a Desktop Layout?

		Desktop view is roughly 1040px and higher in width

### Is there a Tablet Layout?

		Tablet view is roughly 500px and higher in width

### Is there a Mobile Layout?

		Mobile view is everything below 500px in width

---

## Assets and elements

---

### Style Guides

	Style guides can be useful if you have an idea 
	of the style of the website you're creating, 
	but don't have the exact layout. You design each 
	element separately, which can then be used in 
	a modular way later, much like lego.

[Style Guide Example](http://brettjankord.com/projects/style-guide-boilerplate/) and [Another Style guide](http://barebones.paulrobertlloyd.com/) are examples of this.

### Brand Colours

	You've used colours in your design, most likely you've used a subset of colours. These colours will need to be defined in the code. If you've used a navigation bar that has a different colour in each link, put the HEX code for that colour in the readme.md file.
	
ie:

- FF4050 - Red - Main brand colour
- EFC050 - Orange - Secondary brand colour

### What Fonts have been used?

	If you use more than one font in your design, 
	it's always nice to know what they are. Write
	down a list of the fonts used in a readme.md file,
	and include the fonts themselves if they are not
	standard fonts. That way, they can be converted
	to web fonts if they're not too heavy.

	<div class="alert-info">Note: If you're using OpenType Fonts, make sure you've turned off all alternatives. Most browsers handle OpenType fonts differently.</div>
		
### Collate Icons and vectors into a resources folder

	Think of this like InDesign, you wouldn't just
	paste all your things into there. You'd make a
	resources folder and 'place' them in. If you're
	using Photoshop, you can do the same thing by 
	going to FILE > PLACE LINKED. That way, you can
	keep all your elements separate and together at
	the same time.
		
### Images linked and places into a resources folder

	Similar to vectors and icons, if you've used
	images that will be used in the final website,
	it's nice to have the original file used in a
	resources folder.
	
---