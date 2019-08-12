# Tokens and markers
Experiments with a bunch of different small tokens, "base huggers", and markers. Tokens of a specific size (25mm diameter rounds) are kerf-offset by `0.003"` to account for laser thickness.

![](Levels%20+%20Activated.svg)

---

### Materials
  * 1 sheet Proofgrade Medium Cherry Plywood (Finished)

### First Attempt (Walnut)
  1. Proofgrade settings for Medium Walnut
      * SCORE:
        * Speed: `125`
        * Power: `11`
        * \# of Passes: `1`
        * Focus Height: `0.118`
      * ENGRAVE:
        * Speed: `550`
         * Power: `40`
        * \# of Passes: `1`
        * LPI: `340`
        * Focus Height: `0.118`
      * CUT:
        * Speed: `189`
        * Power: `FULL`
        * \# of Passes: `1`
        * Focus Height: `0.118`
  2. First print:
      1. ENGRAVE the text and shaded background areas first
      2. SCORE the monoline patterned areas
      3. CUT the outlines last
  2. Second print:
      1. Carefully flip over each token without disturbing the position of the board
      2. Repeat the ENGRAVE and SCORE
      3. IGNORE the outlines

### Second Attempt (Cherry)
    1. Proofgrade Medium Cherry Hardwood
      * SCORE:
        * Speed: `125`
        * Power: `8`
        * \# of Passes: `1`
        * Focus Height: `0.125`
    * ENGRAVE:
        * Speed: `300`
        * Power: `16`
        * \# of Passes: `1`
        * Lines Per Inch: `340`
        * Focus Height: `0.125`
    * CUT:
        * Speed: `189`
        * Power: `FULL`
        * \# of Passes: `1`
        * Focus Height: `0.125`




### Notes
    * First attempt using scored lines as a pattern (rather than engraving). The lines came out too close together and too dark, which resulted in effectively a heavy engrave. In Illustrator my lines were `0.25 pt` at `.0125 inch` spacing. For mockups, I think going to .75pt lines will show a better preview. Second attempt, I dropped the power on the score down to `7`. The walnut cuts well but it is very low contrast.
    * To give the scores a little more spacing, I'm giving a `0.05` margin to the ends of the lines.
    * On the Cherry, I had one token cut through the Proofgrade QR sticker. The engrave came out thin here and lost some detail. Definitely need some more power on these areas.
    * On the Monster Spawn proxies, I tried two different SCORE settings to vary the line darkness. The "compass" marks were POW `11` and the interior swirl was POW `5`...Aaaaand the paths for the interior swirl double-printed :facepalm: - so those need to be de-duplicated.
    * TO DO: Probably would be nice to reverse out a number in the center of the Monster spawn pits, for easier randomization.
