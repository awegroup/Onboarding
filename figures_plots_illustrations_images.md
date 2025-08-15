# General rules

- Use vector graphics wherever possible for resolution independence and easy later edits (fonts, lines, sizes).
- Use bitmap editing only for photographic or rendered images.

# Workflow

### Step 1 — In Python (if you have code)
Export diagrams as PDF (vector format).

Only export as PNG when necessary (e.g., large contour/streamline plots that would make PDF files huge).

### Step 2 — In GIMP (if you have pictures)

Prepare and edit all bitmap content (photos, rendered images).
Tasks include:
- Adjust orientation
- Crop
- Correct perspective
- Shear
- Flip or rotate
Use GIMP only for bitmap manipulation, not for final figure assembly.

### Step 3 — In Inkscape

Import GIMP-processed bitmaps and Python-exported PDFs.
Assemble the final figure:
- Arrange elements
- Align and scale
- Rotate if needed
- Add arrows or annotations
- Use guides, snapping, and vector editing tools.

Save working file as SVG (preserves guides and layers).
Export final version as PDF for LaTeX or presentations.

# Why use Inkscape for Assembly?

Using vector graphics as much as possible is the best option because you a) are resolution independent and b) can recycle such graphics later, e.g. to change font, don't sizes, lines etc. You can not do this in bitmap format. There will be a moment when this becomes important, either for you, or for another researcher. E.g. when you make slides or incorporate this in a journal publication. Use Gimp only for photo or rendering content, Inkscape for line art, diagrams, etc and to assemble the graphics. Inkscape also has very cool guides and snapping functionality that speeds up your work. In Gimp you don't really have this.
