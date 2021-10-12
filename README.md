# Visual-Essay-Quick-Start
<a href="https://juncture-digital.org"><img src="https://preview.redd.it/n2xp6dxxj9x31.jpg?auto=webp&s=d207b9a3bedac17fb1071119388be0d3e8346b47"></a>

<param ve-config 
       title="girl with very nice clam spit"
       author=" "
       banner="https://preview.redd.it/n2xp6dxxj9x31.jpg?auto=webp&s=d207b9a3bedac17fb1071119388be0d3e8346b47" 
       layout="horizontal">

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

_Girl with a Pearl Earring_ (Dutch: Meisje met de parel) is an oil painting by Dutch Golden Age painter Johannes Vermeer, 
dated c. 1665. Going by various names over the centuries, it became known by its present title towards the end of the 
20th century after the earring worn by the girl portrayed there.[^1]
<param ve-image 
       label="Girl with a Pearl Earring" 
       description="painting by Johannes Vermeer" 
       license="public domain" 
       url="https://upload.wikimedia.org/wikipedia/commons/0/0f/1665_Girl_with_a_Pearl_Earring.jpg">

## Image

_Jan Vermeer_ (Dutch: De jonge Vermeer) is an oil painting by Dutch Golden Age painter Johannes Vermeer, 
dated c. 1656. Supposedly the only existing portrait of Johannes Vermeer. This is a faithful photographic reproduction.[^1]
<param ve-image 
       label="Johannes Vermeer" 
       description="self-portrait by Johannes Vermeer" 
       license="public domain" 
       url="https://en.wikipedia.org/wiki/Johannes_Vermeer#/media/File:Cropped_version_of_Jan_Vermeer_van_Delft_002.jpg">

## Map

The work has been in the collection of the Mauritshuis in The Hague since 1902 and has been the subject of various 
literary treatments. In 2006, the Dutch public selected it as the most beautiful painting in the Netherlands.
<param ve-map center="Q36600" zoom="11" prefer-geojson>

## Multiple viewers

Multiple viewers may be defined for a single paragraph of text.  The first viewer defined is displayed as the default viewer.  
Others are selectable using icons displayed in the top right margin of the paragraph.
<param ve-image 
       manifest="https://iiif.juncture-digital.org/manifest/6dd738aed85597cac540ad31dd5818e86ef7f2918c7b43a9eb3123d5538e6e4c">
<param ve-map center="Q36600" zoom="11">

# References

[^1]: [Wikipedia: Girl with a Pearl Earring](https://en.wikipedia.org/wiki/Girl_with_a_Pearl_Earring)

