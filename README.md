<a href="https://juncture-digital.org"><img src="https://juncture-digital.org/images/ve-button.png"></a>

<param ve-config 
       title="Digital Humanities"
       author="Noah Bennett"
       banner="https://th.bing.com/th/id/R.004d0a247e2dc307e90e2becf4f53cea?rik=JXxa4FA2ARE1KQ&riu=http%3a%2f%2f4.bp.blogspot.com%2f-PqA0W74kYIo%2fUQfa9pvilJI%2fAAAAAAAAhmM%2fkv_zxczY9NI%2fs1600%2fWorld_Scotland_Aviemore_007809_.jpg&ehk=6hkMyReJlX6IwvzETnbkZjCGX%2bfIWLsLoQInjHvplGY%3d&risl=&pid=ImgRaw&r=0?url=https://upload.wikimedia.org/wikipedia/commons/4/47/Bartholomeus_Johannes_van_Hove%2C_Het_Mauritshuis_te_Den_Haag.jpg" 
       layout="vertical">

<!-- Entities discussed throughout the essay are typically defined before the essay text and
     are thus available in all text.  Entity identifiers (QIDs) can be found in either
     Wikipedia or Wikidata (https://www.wikidata.org)> -->
<param ve-entity eid="Q185372"> <!-- Girl with a Pearl Earring painting -->
<param ve-entity eid="Q41264"> <!-- Johannes Vermeer -->
<param ve-entity eid="Q221092"> <!-- Mauritshuis -->
<param ve-entity eid="Q36600"> <!-- The Hague -->

# Sample visual essay

# Basic usage

## Image

This is a silly cat that I thought was quite adorable. The cat is inside of a rolled up mat, which makes him look quite cute.[^1]
<param ve-image 
       label="Cat in Rolled Up Mat" 
       description="Silly Cat" 
       license="public domain" 
       url="https://www.hdwallpaper.nu/wp-content/uploads/2015/02/Funny-Cat-Hidden-1024x768.jpg">

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
