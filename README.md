[![DOI](https://zenodo.org/badge/37726766.svg)](https://zenodo.org/badge/latestdoi/37726766)

# Plant-Pollinator-Web

Plant and insect data that will be available through Global Biotic Interactions (GloBI, http://globalbioticinteractions.org).

Includes the following studies:

Arroyo, M. T. K., R. B. Primack, and J. J. Armesto. 1982. Community studies in pollination ecology in the high temperate Andes of Central Chile. I. Pollination mechanisms and altitudinal variation. American Journal of Botany 69:82-97.

Barrett, S. C. H., and K. Helenurm. 1987. The Reproductive-Biology of Boreal Forest Herbs.1. Breeding Systems and Pollination. Canadian Journal of Botany 65:2036-2046.

Bartomeus, I., Vilà, M. & Santamaria, L., 2008. Contrasting effects of invasive plants in plant-pollinator networks. Oecologia 155: 761-770.

Bezerra, E. L. S, I. C. Machado & M. A. R. Mello (2009). Pollination networks of oil-flowers: a tiny world within the smallest of all worlds. Journal of Animal Ecology 78: 1096-1101.

Dupont YL, Hansen DM and Olesen JM (2003) Structure of a plant-flower-visitor network in the high-altitude sub-alpine desert of Tenerife, Canary Islands. Ecography 26:301-310

Elberling, H., and J. M. Olesen. 1999. The structure of a high latitude plant-flower visitor system: the dominance of flies. Ecography 22:314-323.

Hocking, B. 1968. Insect-flower associations in the high Arctic with special reference to nectar. Oikos 19:359-388.

Inouye, D. W., and G. H. Pyke. 1988. Pollination biology in the Snowy Mountains of Australia: comparisons with montane Colorado, USA. Australian Journal of Ecology 13:191-210.

Kaiser-Bunbury, C. N., Memmott J. & Müller C. B., 2009. Community structure of pollination webs of Mauritian heathland habitats. Perspectives in Plant Ecology, Evolution and Systematics 11: 241–254

Kato, M., T. Makutani, T. Inoue, and T. Itino. 1990. Insect-flower relationship in the primary beech forest of Ashu, Kyoto: an overview of the flowering phenology and seasonal pattern of insect visits. Contr. Biol. Lab. Kyoto Univ. 27:309-375.

Kevan, P. G. 1970. High arctic insect-flower visitor relations: the inter-relationships of arthropods and flowers at Lake Hazen, Ellesmere Island, Northwest Territories, Canada. Ph.D. thesis thesis, University of Alberta.

McCullen, C. K. 1993. Flower-visiting insects of the Galapagos Islands. Pan-Pacific Entomologist 69:95-106.

Medan, D., N. H. Montaldo, M. Devoto, A. Mantese, V. Vasellati, and N. H. Bartoloni. 2002. Plant-pollinator relationships at two altitudes in the Andes of Mendoza, Argentina. Arctic Antarctic and Alpine Research 34:233-241.

Mosquin, T., and J. E. H. Martin. 1967. Observations on the pollination biology of plants on Melville Island, N.W.T., Canada. Canadian Field Naturalist 81:201-205.

Motten, A. F. 1982. Pollination Ecology of the Spring Wildflower Community in the Deciduous Forests of Piedmont North Carolina. Doctoral Dissertation thesis, Duke University, Duhram, North Carolina, USA.

Olesen, J. M., L. I. Eskildsen, and S. Venkatasamy. 2002. Invasion of pollination networks on oceanic islands: importance of invader complexes and endemic super generalists. Diversity and Distributions 8:181-192.

Ramirez, N., and Y. Brito. 1992. Pollination Biology in a Palm Swamp Community in the Venezuelan Central Plains. Botanical Journal of the Linnean Society 110:277-302.

Santos, G. M M, C. M. L. Aguiar & M. A. R. Mello (2010) Flower-visiting guild associated with the Caatinga flora: trophic interaction networks formed by social bees and social wasps with plants. Apidologie 41: 466-475.

Schemske, D. W., M. F. Willson, M. N. Melampy, L. J. Miller, L. Verner, K. M. Schemske, and L. B. Best. 1978. Flowering Ecology of Some Spring Woodland Herbs. Ecology 59:351-366.

Small, E. 1976. Insect pollinators of the Mer Bleue peat bog of Ottawa. Canadian Field Naturalist 90:22-28.

Vázquez, D. P. 2002. Interactions among Introduced Ungulates, Plants, and Pollinators: A Field Study in the Temperate Forest of the Southern Andes. Doctoral Dissertation thesis, University of Tennessee, Knoxville, Tennessee, USA.

## Data Format Explanation
The file [interactions.tsv](./interactions.tsv) is a suggestion on how to encode your interaction data using a tab separated file format (tsv) in combination with columns described below. This provides an example on how to capture your data in a human and machine friendly way and keep it relatively doable to update the file using a basic text editor. Other formats are supported, just let us know about the syntax, and we'll make it work.

term | example | description | 
--- | --- | ---
 sourceTaxonId | EOL:328583 | taxon classification id of originating organism in some taxon name authority
 sourceTaxonName | Enhydra lutris  | scientific name of taxon classification of originating organism 
 interactionTypeId | RO:0002470 | id of interaction as described by the [OBO Relations Ontology](https://code.google.com/p/obo-relations/)
 interactionTypeName | eats | human readable description of interactions
 targetTaxonId |  EOL:1971 | taxon classification id of originating organisms 
 targetTaxonName | Echinoidea | scientific name of taxon classification of target organism of interaction
 LocationinhostName| On tube feet | The location of the host where the parasite is found
 localityId | GEONAMES:5391961 | reference to geo classification like geonames.org, gazetteer or other.
 localityName | San Francisco Bay, California, USA | human readable description of locale
 decimalLatitude | -41.0983423 | latitude of geographic center of interaction observation location http://rs.tdwg.org/dwc/terms/index.htm#decimalLatitude
 decimalLongitude | -121.1761111 | longtide of geographic center of interaction observation location http://rs.tdwg.org/dwc/terms/index.htm#decimalLongitude
 observationDateTime | 2014-11-18T06:37:04Z | [ISO 8601](https://en.wikipedia.org/wiki/ISO_8601) formatted date time string 
 referenceDoi | doi:10.3354/dao002147 | Digital Object Id (DOI, http://doi.org) is commonly used to give papers, datasets or other digital object a permanent id
 referenceCitation| Jangoux, M. 1986 Diseases of Echinodermata. I. Agents microorganisms and protistans Diseases of Aquatic Organisms (Impact Factor: 1.59) 2:147-162. doi:10.3354/dao002147 | human readable reference 
