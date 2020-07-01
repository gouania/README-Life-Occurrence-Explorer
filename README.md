# Life Occurrence Explorer

[gouania.shinyapps.io/occurrenceexplorer/](https://gouania.shinyapps.io/occurrenceexplorer/)

*Author: Daniel Cahen*

## Find what living organisms occur at any given place in the world
  
Life Occurrence Explorer enables users to search for occurrences of any group of biological organisms at any locality. 

Examples of questions Life Occurrence Explorer can help answer:

* What are the kinds of birds found in my local park?
* When was this animal last reported in my area?
* When was this beetle last seen in this forest?
* What is this plant?
* What are all the plants belonging to a certain family that occur in my county?
* Where in the world can I find this type of frog?

And many more...

This tool can help anyone trying to identify an organism or see where it has been recorded.
It can therefore be used to learn and teach about nature, for citizen science and for research.

### Example: Birds occurring in Hyde Park
![Example: Birds occurring in Hyde Park](/images/BirdsHydePark.jpg "Birds Hyde Park")

### List of birds occurring in Hyde Park
![List of birds occurring in Hyde Park](/images/SummaryHydePark.jpg "List Hyde Park")

Life Occurrence Explorer brings together data from the biggest database of biological occurrence records [(GBIF)](https://www.gbif.org/what-is-gbif) and from the biggest collaborative geographical information project [(OpenStreetMap)](https://www.openstreetmap.org/). This enables users to explore the occurrence of living organisms on Earth in more detail and more interactively than ever before. 

* An interactive map shows where the organisms occur
* Species are listed by most to less frequent at the specified locality to facilitate identifications
* Users can filter results to quickly find specific types of organisms
* Details about each occurrence are displayed
* Images help users identify organisms


------

## How to use

1. Visit [gouania.shinyapps.io/occurrenceexplorer/](https://gouania.shinyapps.io/occurrenceexplorer/)
2. Enter the name of a locality. This can be broad (e.g. "Europe", "Oregon") or local ("London", "Hampstead Heath"). 
3. Enter the scientific name of an organism. Again this can be broad ("Animalia", "Mammalia", "Plantae", Aves", "Coleoptera") or more specific ("Nymphalidae", "Asteraceae", "Asplenium trichomanes subsp. quadrivalens")

* A vernacular to scientific name search tool is included at the bottom of the main panel for users who do not know the scientific name of the organisms they would like to search for
* A scientific to vernacular name search tool is also included. Vernacular/scientific searches query the [Encyclopedia of Life's](https://eol.org/) database of names
* Searching a locality returns all occurrences within the smallest rectangle containing the entire locality. The size of the rectangle can be adjusted in "Options"
* Individual records can be selected on the map for more information
* The Summary table gives the list of species with their number of occurrences and a link to images to help with identifications
* The "Records" tab provides information for each individual record and a link to the full occurrence details on GBIF
* By clicking on a record in the table, the map automatically zooms to that observation 
* Both Summary and Records data can be downloaded as a CSV file
* Name and Locality search results are listed below the Summary and Record table to help in case there are no occurrence results


### Example
##### Plants of the nightshade family (Solanaceae) occurring on the island of Corsica
![Solanaceae in Corsica](/images/LifeOccurrenceExample.gif "Solanaceae in Corsica")

[A 2-minute video](https://youtu.be/ivQGk6uAwfk) presenting the tool is also available on YouTube

------

## Terms of Use

License: [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/)
You are free to share and adapt the material, provided you give appropriate credit, do not use the material for commercial purposes and distribute your contributions under the same license as the original.

Life Occurrence Explorer stands on the shoulders of the thousands of people who have recorded biological occurrences, such as biologists making natural history collections and naturalists sharing observations on citizen science platforms. It does not bring in any new occurrence data that is not available on GBIF. All data available on GBIF is associated with one of the three following Creative Commons licenses: CC0, CC BY or CC BY-NC. 

[GBIF Terms of use](https://www.gbif.org/terms)

------

## Acknowledgements

Special thanks to Scott Chamberlain, co-founder of [rOpenSci](https://ropensci.org/), who created the [rgbif](https://cran.r-project.org/web/packages/rgbif/index.html) and [taxize](https://cran.r-project.org/web/packages/taxize/index.html), two very helpful packages that make this app work, and to Martijn Tennekes, creator of [tmaptools](https://cran.r-project.org/web/packages/tmaptools/index.html).

------

## Participate

Life Occurrence Explorer is a free tool for the benefit of all nature lovers, students and teachers, and scientists. Help to add features that would improve it would be greatly appreciated.

Please send any feedback to occurrenceexplorer@gmail.com
