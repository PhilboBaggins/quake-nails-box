# Quake nails box

......

## Making one

1. Laser cut [box.svg](box.svg) out of 3mm material (e.g. MDF) and glue it into a box shape
2. Print [cover.pdf](cover.pdf), cut it out and glue it to the box
3. Optional: Glue some felt to the bottom of the box, so that the box doesn't scratch whatever you put it on

## Design history

This is the process I followed to design the assets in this repository:

* Decide on the size - I picked 160mm x 160mm x 160mm because:
    * The nail box in Quake looks like a cube
    * I want it to fit inside a IKEA Kallax but a full size would be too big, so lets make it half width:
        * 32cm x 32cm x 32cm - <https://www.ikea.com/au/en/p/kuggis-storage-box-with-lid-white-80526876/>
        * 33cm x 38cm x 33cm - <https://www.ikea.com/au/en/p/droena-box-dark-grey-20443978/>
* Box design
    * Use <http://makercase.com/basicBox> to make a simple box with no lid and 160mm x 160mm x 160mm outer dimensions
    * [Screenshot of box design here](box-makercase.png)
    * I used 3mm material but that can easily be changed without affecting the overall design - Just keep the outer dimensions of the box at 160mm x 160mm x 160mm so that they match with the cover
* Cover:
    * Download [Nail0sid.webp](Nail0sid.webp) from the [Quake](https://quake.fandom.com/wiki/Nail_(Q1)) [Wiki](https://quake.fandom.com/wiki/Nail_(Q1)?file=Nail0sid.png)
    * Imported it into [Inkscape](https://inkscape.org/):
        * State with an A4 page
        * Cropped image to just the part I need, rounding off to a square size
        * Scale it to 160mm by 160mm
        * Rethink things and scale it up to 162mm by 162mm, so that there is an extra 1mm around all sides, to account for errors when cutting it out
        * Centre it on the page
        * Add cutting guide marks near all corners
        * Save as [cover.svg](cover.svg)
