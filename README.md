# kaushur-gawun

This repository contains songs I've collected over time from Bazaz and Koul family events. There may be inconsistencies. I encourage the community to contribute:

## TODO
- Have standardized Roman (tse/cze/cho seem to be the same letters) / authentic Kashmiri script (instead of Urduish / Arabicish script)
- Provide accurate translations with each
- Add dholki patterns / recommendations in a simple way
- Turn them into a standard music-sheet format which is easy to consume for dholki performers (family and friends) - Can consider an international standard like MusicXML, and then parse those files into this mega TEX Sheet.

## How to make changes

To make edits in the document, I recommend simply making changes in the [TEX file](./music-sheet.tex) (it's easy to write, if you just use GPT to help you out.)

### Generating the PDF
- First install the [Gulmarg Nastaleeq](./GulmargNastaleeq8112013.ttf) font file. This is the font for the Kashmiri side of the lyrics.
- Ensure you have LaTeX installed in your computer. Follow instructions [here](https://www.latex-project.org/get/) if you need to.
- To compile the TEX file, run the following in your terminal program:
```
xelatex music-sheet.tex
```
(if you get any errors, install the relevant packages and make an update in this README to help more people)
- If successful, [music-sheet.pdf](./music-sheet.pdf) will be updated.

## Credits
- Saleem Shafi Koul
- Dr Salman Shafi Koul
- Dr Ghazala Akram
- Nasreen Shahid
- Alya Bazaz
- Saad Bazaz (me, lol)
- Sohaib Bazaz (@SohaibBazaz)

Would love to add more here who can contribute to relatively unknown lyrics, and improve this sheet.