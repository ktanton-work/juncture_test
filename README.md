# juncture_test
testing juncture
<a href="https://juncture-digital.org"><img src="https://juncture-digital.org/images/ve-button.png"></a>

<param ve-config 
       title="Biblical Commentaries"
       author="My test"
       banner="https://iiif.juncture-digital.org/banner/?url=https://upload.wikimedia.org/wikipedia/commons/f/f2/20141024_HildesheimCathedral_Niedersachsen_BernwardsTuer_DSCN0138_PtrQs.jpg" 
       layout="vertical">

<!-- Entities discussed throughout the essay are typically defined before the essay text and
     are thus available in all text.  Entity identifiers (QIDs) can be found in either
     Wikipedia or Wikidata (https://www.wikidata.org)> -->
<param ve-entity eid="Q185372"> <!-- Girl with a Pearl Earring painting -->
<param ve-entity eid="Q41264"> <!-- Johannes Vermeer -->
<param ve-entity eid="Q221092"> <!-- Mauritshuis -->
<param ve-entity eid="Q36600"> <!-- The Hague -->

# Sample visual essay

This is a sample visual essay demonstrating a few key features of a Visual Essay. Additional [Documentation](https://github.com/JSTOR-Labs/juncture/wiki) and [examples](https://jstor-labs.github.io/juncture-examples) are available for reference.
<param ve-image 
       manifest="https://iiif.juncture-digital.org/manifest/6dd738aed85597cac540ad31dd5818e86ef7f2918c7b43a9eb3123d5538e6e4c">

# Basic usage

## Image

_Saint Gregory's Commentary on Job_, or Moralia, sive Expositio in Job, sometimes called Moralia in Job or Magna Moralia, was written between 578 and 595, begun when Gregory was at the court of Tiberius II at Constantinople, but finished only after he had already been in Rome for several years.[^1] This manuscript was originally the second volume of a two-volume set containing the book of Job and Gregory the Great's Moralia in Job. The first volume of this set was probably Royal MS 13 C IV, which includes the Moralia in Job, books 1-16 but which was written by a different hand. A part of a later copy of the book of Job (ff. 1r-5v), written by an early 13th-century hand, has been associated with the original volume at an early period, as the 14th-century ownership inscription on f. 1r testifies (see Provenance). Lanfranc's (b. c. 1010, d. 1089) notes have been added at the end in the second half of the 12th century (f. 259r).
<param ve-image 
       label="British Library Royal MS 6 C VI The Book of Job (24-42); Gregory the Great, Moralia in Job (books 17-35); Lanfranc's notes on Moralia in Job" 
       description="fol. 4v" 
       license="https://www.bl.uk/help/how-to-reuse-images-of-unpublished-manuscripts" 
       url="https://api.bl.uk/metadata/iiif/ark:/81055/vdc_100059911875.0x000001/manifest.json">

## Map

The work has been in the collection of the Mauritshuis in The Hague since 1902 and has been the subject of various 
literary treatments. In 2006, the Dutch public selected it as the most beautiful painting in the Netherlands.
<param ve-map center="Q36600" zoom="11" prefer-geojson>

## Multiple viewers

Multiple viewers may be defined for a single paragraph of text.  The first viewer defined is displayed as the default viewer.  
Others are selectable using icons displayed in the top right margin of the paragraph.
<param ve-image 
       manifest="https://api.bl.uk/metadata/iiif/ark:/81055/vdc_100059911875.0x000001/manifest.json">
<param ve-map center="Q36600" zoom="11">

# References

[^1]: [Wikipedia: Commentary on Job](https://en.wikipedia.org/wiki/Commentary_on_Job)
