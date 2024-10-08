# InvaHealth database descriptors

last updated: 2024-10-08

## Column Names

-   [**InvaHealth_ID**](#invahealth_id)
-   [**Repository**](#repository)
-   [**Reference_ID**](#reference_id)
-   [**InvaCost_Reference_ID**](#invaCost_reference_id)
-   [**InvaPact_Reference_ID**](#invaPact_reference_id)
-   [**DOI_URL**](#doi_url)
-   [**Reference_title**](#reference_title)
-   [**Authors**](#authors)
-   [**Abstract**](#abstract)
-   [**Publication_year**](#publication_year)
-   [**Language**](#language)
-   [**Type_of_material**](#type_of_material)
-   [**Previous_materials**](#previous_materials)
-   [**Availability**](#availability)
-   [**Kingdom**](#kingdom)
-   [**Phylum**](#phylum)
-   [**Class**](#class)
-   [**Order**](#order)
-   [**Family**](#family)
-   [**Genus**](#genus)
-   [**Species**](#species)
-   [**Subspecies**](#subspecies)
-   [**Common_name**](#common_name)
-   [**Environment_IAS**](#environment_ias)
-   [**HabitatVerbatim**](#habitatverbatim)
-   [**Habitat**](#habitat)
-   [**urbanArea**](#urbanarea)
-   [**Island**](#island)
-   [**TDWG1**](#tdwg1)
-   [**TDWG2**](#tdwg2)
-   [**Official_country**](#official_country)
-   [**Region**](#region)
-   [**ISO_3166_1_alpha_3**](#iso_3166_1_alpha_3)
-   [**ISO_3166_2_alpha_3**](#iso_3166_2_alpha_3)
-   [**State_Province_AdministrativeArea**](#state_province_administrativeArea)
-   [**Location**](#location)
-   [**Spatial_scale**](#spatial_scale)
-   [**LAT**](#lat)
-   [**LON**](#lon)
-   [**Biome**](#biome)
-   [**Native_Introduced**](#native_Introduced)
-   [**Health_impact_mechanism**](#health_impact_mechanism)
-   [**Associated_biohazard**](#associated_biohazard)
-   [**Role**](#role)
-   [**Associated_vector**](#associated_vector)
-   [**Associated_reservoir**](#associated_reservoir)
-   [**Associated_facilitator**](#associated_facilitator)
-   [**Mode_transmission**](#mode_transmission)

## Descriptions
# **InvaHealth_ID**

Public unique identifier, which is formulated as follows: 'IC_x_y' with 'IC' meaning InvaCost, 'x' being the version number of the database, and 'y' being the sequential number attributed following the order of integration of costs in the database.

# **Repository**

Literature engine (<a href="https://access.clarivate.com/login?app=wos&alternative=true&shibShireURL=https:%2F%2Fwww.webofknowledge.com%2F%3Fauth%3DShibboleth&shibReturnURL=https:%2F%2Fwww.webofknowledge.com%2F%3Fmode%3DNextgen%26action%3Dtransfer%26path%3D%252Fwos%26DestApp%3DUA&referrer=mode%3DNextgen%26path%3D%252Fwos%26DestApp%3DUA%26action%3Dtransfer&roaming=true">Web of Science</a>, <a href="https://scholar.google.com">Google Scholar</a>, <a href="https://www.google.com">Google search engine</a>, <a href="https://pubmed.ncbi.nlm.nih.gov">Pubmed</a>, <a href="https://scielo.org/en/">Scielo</a>) or original source (targeted collection) from which the reference was collected (see <a href="https://doi.org/10.1038/s41597-020-00586-z">Diagne et al. 2020 <em>Scientific Data</em></a> for further details); cells are left empty when no repository was specified or the reference was shared by external users that did not give any information about this.

# **Reference_ID**

Identifier for the reference where the cost entry is reported; note that this field is currently being improved internally to have a consistent terminology across references within the database.

# **InvaCost_Reference_ID**

Identifier for the reference where a cost entry is reported In <a href="https://github.com/InvaCost"><em>InvaCost</em></a>; this field is currently being improved internally to have a consistent terminology across references within the database.

# **InvaPact_Reference_ID**

Identifier for the reference where the impact entry is reported in <a href="https://especes-exotiques-envahissantes.fr/invapact-un-projet-de-recherche-original-aborde-de-maniere-originale/"><em>InvaPact</em></a>; this field is currently being improved internally to have a consistent terminology across references within the database.

# **DOI_URL**

DOI (<a href="https://www.doi.org">digital object identifier</a>) in URL format (e.g., http://doi.org/10.1038/s41586-021-03405-6) or original URL when no DOI is available.

# **Reference_title**

Title of the reference where the cost entry is reported. As much as possible, this is the original source where the cost was first provided.

# **Authors**

Authors of the reference where the cost entry is reported.

# **Abstract**

If existing/accessible, the abstract of the reference where the cost entry is reported.

# **Publication_year**

Year of publication of the reference where the cost entry is reported.

# **Language**

Main language used in the original reference reporting the cost entry; 22 languages are currently recorded in the database: Catalan, Chinese, Croatian, Czech, Danish, Dutch, English, Finnish, French, Galician, German, Greek, Hindi, Icelandic, Italian, Japanese, Norwegian, Portuguese, Russian, Spanish, Swedish, Ukrainian.

# **Type_of_material**

Type of reference analszed (i.e., scientific peer-reviewed article or grey literature); for grey literature, the exact nature of the reference was indicated (e.g., official report, press release).

# **Previous_materials**

If any, the list of successive materials checked before reaching the original reference providing the cost entry.

# **Availability**

The accessibility of the original reference as a searchable document (yes/no).

# **Kingdom**

Taxonomic kingdom of the invasive species associated with the cost entry.

# **Phylum**

Taxonomic phylum of the invasive species associated with the cost entry.

# **Class**

Taxonomic class of the invasive species associated with the cost entry.

# **Order**

Taxonomic order of the invasive species associated with the cost entry.

# **Family**

Taxonomic family of the invasive species associated with the cost entry.

# **Genus**

Taxonomic genus of the invasive species associated with the cost entry.

# **Species**

Taxonomic species of the invasive species associated with the cost entry.

# **Subspecies**

Taxonomic subspecies of the invasive species associated with the cost entry.

# **Common_name**

Non-scientific (or vernacular) name(s) provided in the original reference, or by the <a href="http://iucn.org">International Union for Conservation of Nature</a> (IUCN) when not provided.

# **Environment_IAS**

Type of environment where the invasive species lives, independently of where the cost occurred: aquatic (species with a close association with aquatic systems at any life stage, including for reproduction, development and/or foraging), semi-aquatic (species with a looser association with aquatic systems) or terrestrial (otherwise); diverse/unspecified is used when there are multiple invasive species pertaining to different environments.

# **HabitatVerbatim**

Copy from the original reference of the sentence/paragraph indicating the habitat typology of the studied area

# **Habitat**

The type of habitat where the cost occurred 

1. <strong>forests</strong>: closed vegetation dominated by deciduous or evergreen trees;
2. <strong>open forests</strong>: woodland vegetation with canopy openings created by environmental stress or disturbance;
3. <strong>scrub</strong>: shrublands maintained by environmental stress (aridity) or disturbance;
4. <strong>grasslands</strong>: open graminoid-dominated habitats maintained either by climate (steppes, prairies, savannas) or land use (grazing, mowing) or combination of both – if possible, specified if it corresponds with
  4a. <em>natural grasslands</em> or
  4b. <em>human-maintained grasslands</em>;
5. <strong>sandy</strong>: dunes and other habitats on unstable sandy substrate, stressed by low nutrients, drought and disturbed by sand movement;
6. <strong>rocky</strong>: cliffs and rock outcrops with very shallow or no soil;
7. <strong>dryland</strong>: habitats in which drought stress limits vegetation development; 8.Saline: habitats stressed by high soil salinity;
9. <strong>riparian</strong>: a mosaic of wetlands, grasslands, tall-forb stands, scrub and woodlands in stream corridors;
10. <strong>wetland</strong>: sites with permanent or seasonal influence of moisture, ranging from oligotrophic to eutrophic;
11. <strong>aquatic: water bodies and streams with submerged and floating plant species;
12. <strong>human-made</strong>: habitats created by humans or where human factor is the main shaping force - if possible, specified if it corresponds with
  12a. <em>ruderal</em> (= urban) or
  12b. <em>agricultural</em> habitats

# **urbanArea**

Assessment of the geographical area where the cost occurred as being strictly urban if the cost occurred in an urban area only; other if the cost occurred in a non-urban area or in a large area where urban and non-urban areas cannot be distinguished; both if the study compares the cost between urban and non-urban areas (i.e. urban vs. suburban, or suburban vs. non-urban; the comparison must be explicit) or presents the cost across contrasted areas regarding their level of urbanization (e.g. urbanization gradient). Note that we consider the urban nature of study sites purely based on an 'habitat' perspective (i.e. city versus rural areas) rather than a demographic one (e.g. population size or human density)

# **Island**

Assessment of the geographical area where the cost occurred as an island (Y) or not (N); NA is used when the cost information is not clearly provided, unknown, or comprises both island and mainland together

# **TDWG1**

Botanical continent (level 1) from the TDWG

# **TDWG2**

Botanical subcontinental regions (level 2) from the TDWG

# **Official_country**

Country where the impact occurred; sometimes, this is not congruent with the geographic region as some territories (e.g., overseas areas) are located in another continent than their official country of attachment; we used information from www.naturalearthdata.com/ as a reference for country's name

# **Region**

Non-administrative name of a region where the impact was recorded, when more appropriate (e.g. for some islands)

# **ISO_3166_1_alpha_3**

Three-letter country codes defined in ISO 3166-1, part of the ISO 3166 standard published by the International Organization for Standardization (ISO), to represent countries, dependent territories, and special areas of geographical interest

# **ISO_3166_2_alpha_3**

Sub-levels of ISO 3166-2, part of the ISO 3166 standard published by the International Organization for Standardization (ISO). See e.g. https://en.wikipedia.org/wiki/ISO_3166-2:FR

# **State_Province_AdministrativeArea**

The second level of geographic division (state, province or territorial administrative area) for the official country where the cost occurred

# **Location**

When provided, the precise location (e.g., city, area) where the cost estimate occurred. Otherwise, we put (i) NA when such information was not provided and the cost entry was provided at a unit or site Spatial scale, or (ii) diverse/unspecified when such information was not provided and the cost entry was provided at global, intercontinental, continental, regional or country Spatial scale

# **Spatial_scale**

Order of magnitude of the extent, size of the land/water area where the costs incurred. Options include: global (worldwide-scale), intercontinental (areas from two or more geographic regions), continental ('Geographic region' level), regional (several countries within a single 'Geographic region'), country, site (area at intra-country level, including USA states) and unit (well-defined surface area or entity)

# **LAT**

Latitude where the impact occurred in decimal degrees

# **LON**

Longitude where the impact occurred in decimal degrees

# **Biome**

Biome where the impact occurred, based on Olson et al. (2001), using the 14 biomes - https://doi.org/10.1641/0006-3568(2001)051[0933:TEOTWA]2.0.CO;2 - Olson, D. M., Dinerstein, E., Wikramanayake, E. D., Burgess, N. D., Powell, G. V. N., Underwood, E. C., D'Amico, J. A., Itoua, I., Strand, H. E., Morrison, J. C., Loucks, C. J., Allnutt, T. F., Ricketts, T. H., Kura, Y., Lamoreux, J. F., Wettengel, W. W., Hedao, P., Kassem, K. R. 2001. Terrestrial ecoregions of the world: a new map of life on Earth. Bioscience 51(11):933-938.

# **Native_Introduced**

Indicates if the impact occurs in the native or introduced range of the species corresponding to the entry

# **Health_impact_mechanism**

General types of health impact - a fixed list of categorie (Pathogen, Toxin, Allergen, Direct physicial harm, Resource availability, Mental health, Behaviour changer)

# **Associated_biohazard**

The name of the substance affecting human health. Name of the pathogen, toxin or allergen

# **Role**

Vector, Reservoir or Facilitator. Sensu Vilà et al. (2021)

# **Associated_vector**

If a species is a reservoir or a facilitator, the species acting as a vector should be indicated

# **Associated_reservoir**

If a species is a vector or a facilitator, the species acting as a reservoir should be indicated if there is one

# **Associated_facilitator**

If a species is a vector or a reservoir, the species acting as a facilitator should be indicated if there is one

# **Mode_transmission**

Mode of transmission of the biohazard / impact (airborne, waterborne, direct contact, foodborne, vectorborne)
