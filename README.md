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
-   [**Number_people_exposed_per_year**](#number_people_exposed_per_year)
-   [**Number_people_affected**](#number_people_affected)
-   [**Number_people_affected_per_year**](#number_people_affected_per_year)
-   [**Mortality_num**](#mortality_num)
-   [**Mortality_num_per_year**](#mortality_num_per_year)
-   [**Mortality_prob_specific**](#mortality_prob_specific)
-   [**Mortality_prob_global**](#mortality_prob_global)
-   [**Hospitalisation_num**](#hospitalisation_num)
-   [**Hospitalisation_num_per_year**](#hospitalisation_num_per_year)
-   [**Avg_hospitalisation_days**](#avg_hospitalisation_days)
-   [**Min_hospitalisation_days**](#min_hospitalisation_days)
-   [**Max_hospitalisation_days**](#max_hospitalisation_days)
-   [**Avg_debilitation_days**](#avg_debilitation_days)
-   [**Min_debilitation_days**](#min_debilitation_days)
-   [**Max_debilitation_days**](#max_debilitation_days)
-   [**DALY**](#daly)
-   [**Social_category**](#social_category)
-   [**Age_category**](#age_category)
-   [**Gender**](#Gender)
-   [**Other**](#other)
-   [**Implementation_social**](#implementation_social)
-   [**Acquisition_method_social**](#acquisition_method_social)
-   [**Method_used_paper_social**](#method_used_paper_social)
-   [**Method_reliability_social**](#method_reliability_social)
-   [**Method_reliability_refined_social**](#method_reliability_refined_social)
-   [**Method_reliability_Explanation_social**](#method_reliability_Explanation_social)
-   [**Method_reliability_Expert_Name_social**](#method_reliability_Expert_Name_social)
-   [**Type_Stakeholder**](#type_stakeholder)
-   [**Stakeholder**](#stakeholder)
-   [**Type_1_of_cost**](#type_1_of_cost)
-   [**Type_2_of_cost**](#type_2_of_cost)
-   [**Type_3_of_cost**](#type_3_of_cost)
-   [**Unspecified_cost**](#unspecified_cost)
-   [**Verbatim_evidence**](#verbatim_evidence)
-   [**Fixed_variable**](#fixed_variable)
-   [**Period_of_estimation**](#period_of_estimation)
-   [**Time_range**](#time_range)
-   [**Probable_starting_year**](#probable_starting_year)
-   [**Probable_ending_year**](#probable_ending_year)
-   [**Probable_starting_year_adjusted**](#probable_starting_year_adjusted)
-   [**Probable_ending_year_adjusted**](#probable_ending_year_adjusted)
-   [**Occurrence**](#occurrence)
-   [**Raw_cost_estimate_original_currency**](#raw_cost_estimate_original_currency)
-   [**Min_Raw_cost_estimate_original_currency**](#min_raw_cost_estimate_original_currency)
-   [**Max_Raw_cost_estimate_original_currency**](#max_raw_cost_estimate_original_currency)
-   [**Raw_cost_estimate_2023_USD_exchange_rate**](#raw_cost_estimate_2023_usd_exchange_rate)
-   [**Raw_cost_estimate_2023_USD_PPP**](#raw_cost_estimate_2023_usd_ppp)
-   [**Cost_estimate_per_year_original_currency**](#cost_estimate_per_year_original_currency)
-   [**Cost_estimate_per_year_2023_USD_exchange_rate**](#cost_estimate_per_year_2023_usd_exchange_rate)
-   [**Cost_estimate_per_year_2023_USD_PPP**](#cost_estimate_per_year_2023_usd_ppp)
-   [**Currency**](#currency)
-   [**Applicable_year**](#applicable_year)
-   [**Type_of_applicable_year**](#type_of_applicable_year)
-   [**Implementation**](#implementation)
-   [**Acquisition_method**](#acquisition_method)
-   [**Management_type**](#management_type)
-   [**Method_used_paper**](#method_used_paper)
-   [**Method_reliability**](#method_reliability)
-   [**Method_reliability_refined**](#method_reliability_refined)
-   [**Method_reliability_Explanation**](#method_reliability_explanation)
-   [**Method_reliability_Expert_Name**](#method_reliability_expert_Name)
-   [**Overlap**](#overlap)
-   [**Benefit_value**](#benefit_value)
-   [**Details**](#details)
-   [**Initial_contributors_names**](#initial_contributors_names)
-   [**Double_checking**](#double_checking)

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

Copy from the original reference of the sentence/paragraph indicating the habitat typology of the studied area.

# **Habitat**

The type of habitat where the cost occurred: 

1. <strong>forests</strong>: closed vegetation dominated by deciduous or evergreen trees;
2. <strong>open forests</strong>: woodland vegetation with canopy openings created by environmental stress or disturbance;
3. <strong>scrub</strong>: shrublands maintained by environmental stress (aridity) or disturbance;
4. <strong>grasslands</strong>: open graminoid-dominated habitats maintained either by climate (steppes, prairies, savannas) or land use (grazing, mowing) or combination of both – if possible, specified if it corresponds with<br>
  4a. <em>natural grasslands</em> or<br>
  4b. <em>human-maintained grasslands</em>;
5. <strong>sandy</strong>: dunes and other habitats on unstable sandy substrate, stressed by low nutrients, drought and disturbed by sand movement;
6. <strong>rocky</strong>: cliffs and rock outcrops with very shallow or no soil;
7. <strong>dryland</strong>: habitats in which drought stress limits vegetation development; 8.Saline: habitats stressed by high soil salinity;
9. <strong>riparian</strong>: a mosaic of wetlands, grasslands, tall-forb stands, scrub and woodlands in stream corridors;
10. <strong>wetland</strong>: sites with permanent or seasonal influence of moisture, ranging from oligotrophic to eutrophic;
11. <strong>aquatic</strong>: water bodies and streams with submerged and floating plant species;
12. <strong>human-made</strong>: habitats created by humans or where human factor is the main shaping force - if possible, specified if it corresponds with<br>
  12a. <em>ruderal</em> (= urban) or<br>
  12b. <em>agricultural</em> habitats

# **urbanArea**

Assessment of the geographical area where the cost occurred as being strictly urban if the cost occurred in an urban area only; other if the cost occurred in a non-urban area or in a large area where urban and non-urban areas cannot be distinguished; both if the study compares the cost between urban and non-urban areas (i.e. urban vs. suburban, or suburban vs. non-urban; the comparison must be explicit) or presents the cost across contrasted areas regarding their level of urbanization (e.g., urbanisation gradient). We consider the urban nature of study sites purely based on an 'habitat' perspective (i.e., city <em>versus</em> rural areas) rather than a demographic one (e.g., population size or human density).

# **Island**

Assessment of the geographical area where the cost occurred as an island (Y) or not (N); NA is used when the cost information is not clearly provided, unknown, or comprises both island and mainland together.

# **TDWG1**

Botanical continent (<a href="https://github.com/tdwg/wgsrpd/blob/master/109-488-1-ED/2nd%20Edition/tblLevel1.txt">level 1</a>) from the <a href="https://www.tdwg.org/">Biodiversity Information Standards</a> (TDWG).

# **TDWG2**

Botanical subcontinental regions (<a href="https://github.com/tdwg/wgsrpd/blob/master/109-488-1-ED/2nd%20Edition/tblLevel2.txt">level 2</a>) from the <a href="https://www.tdwg.org/">Biodiversity Information Standards</a> (TDWG).

# **Official_country**

Country where the impact occurred; sometimes this is not congruent with the geographic region as some territories (e.g., overseas areas) are located in another continent than their official country of attachment; we used information from <a href="http://www.naturalearthdata.com/">here</a> as a reference for country names.

# **Region**

Non-administrative name of a region where the impact was recorded, when more appropriate (e.g., for some islands).

# **ISO_3166_1_alpha_3**

Three-letter country codes defined in <a href="https://www.iso.org/obp/ui/#search">ISO 3166-1</a>, part of the ISO 3166 standard published by the International Organization for Standardization (ISO), to represent countries, dependent territories, and special areas of geographical interest

# **ISO_3166_2_alpha_3**

Sub-levels of <a href="https://en.wikipedia.org/wiki/ISO_3166-2#Subdivisions_included_in_ISO_3166-1">ISO 3166-2</a>, part of the ISO 3166 standard published by the International Organization for Standardization (ISO).

# **State_Province_AdministrativeArea**

The second level of geographic division (state, province, or territorial administrative area) for the official country where the cost occurred.

# **Location**

When provided, the precise location (e.g., city, area) where the cost estimate occurred. Otherwise, we put (<em>i</em>) 'NA' when such information was not provided and the cost entry was provided at a unit or site Spatial scale, or (<em>ii</em>) diverse/unspecified when such information was not provided and the cost entry was provided at global, intercontinental, continental, regional or country Spatial scale

# **Spatial_scale**

Order of magnitude of the extent, size of the land/water area where the costs incurred. Options include:
- global (worldwide-scale),
- intercontinental (areas from two or more geographic regions),
- continental ('geographic region' level),
- regional (several countries within a single 'geographic region'),
- country,
- site (area at intra-country level, including USA states), or
- unit (well-defined surface area or entity)

# **LAT**

Latitude (decimal degrees) where the impact occurred.

# **LON**

Longitude (decimal degrees) where the impact occurred.

# **Biome**

Biome where the impact occurred, based on <a href="https://doi.org/10.1641/0006-3568(2001)051[0933:TEOTWA]2.0.CO;2">Olson et al. (2001)</a>, using the 14 biomes. See associated repository '<a href="https://github.com/InvaHealth/WWFbioregions">WWFbioregions</a>' for the GIS shapefiles and R code necessary to obtain the biome category. Categories included:
- Tropical & Subtropical Moist Broadleaf Forests
- Tropical & Subtropical Dry Broadleaf Forests
- Tropical & Subtropical Coniferous Forests
- Temperate Broadleaf & Mixed Forests
- Temperate Conifer Forests
- Boreal Forests/Taiga
- Tropical & Subtropical Grasslands, Savannas & Shrublands
- Temperate Grasslands, Savannas & Shrublands
- Flooded Grasslands & Savannas
- Montane Grasslands & Shrublands
- Tundra
- Mediterranean Forests, Woodlands & Scrub
- Deserts & Xeric Shrublands
- Mangroves

# **Native_Introduced**

Indicates if the impact occurs in the native or introduced range of the species corresponding to the entry.

# **Health_impact_mechanism**

General types of health impact — a fixed list of categories:
- pathogen
- toxin
- allergen
- direct physicial harm
- resource availability
- mental health
- behaviour changer

# **Associated_biohazard**

The name of the substance affecting human health. Name of the pathogen, toxin, or allergen.

# **Role**

Vector, Reservoir, or Facilitator (sensu <a href="https://doi.org/10.1093/biosci/biab047">Vilà et al. 2021</a>).

# **Associated_vector**

If a species is a reservoir or a facilitator, the species acting as a vector should be indicated.

# **Associated_reservoir**

If a species is a vector or a facilitator, the species acting as a reservoir should be indicated if there is one.

# **Associated_facilitator**

If a species is a vector or a reservoir, the species acting as a facilitator should be indicated if there is one.

# **Mode_transmission**

Mode of transmission of the biohazard/impact:
- air-borne
- water-borne
- direct contact
- food-borne
- vector-borne

# **Number_people_exposed**

Number of people exposed to the biohazard / health issue.

# **Number_people_exposed_per_year**

Number of people exposed to the biohazard / health issue per year.

# **Number_people_affected**

Number of people with health impacts due to the biohazard / health issue.

# **Number_people_affected_per_year**

Number of people with health impacts due to the biohazard / health issue per year.

# **Mortality_num**

Number of people having died due to the biohazard / health issue.

# **Mortality_num_per_year**

Number of people having died due to the biohazard / health issue per year.

# **Mortality_prob_specific**

Probability that a person affected by the biohazard will die, specific to the study (reported in the study or proportion from the above).

# **Mortality_prob_global**

Global estimate of the probability that a person affected by the biohazard will die (as reported in the study).

# **Hospitalisation_num**

Number of people hospitalised because of the biohazard / health issue.

# **Hospitalisation_num_per_year**

Number of people hospitalised because of the biohazard / health issue per year.

# **Avg_hospitalisation_days**

Average number of days a person is hospitalised (when hospitalised).

# **Min_hospitalisation_days**

Minimum number of days a person is hospitalised (when hospitalised).

# **Max_hospitalisation_days**

Maximum number of days a person is hospitalised (when hospitalised).

# **Avg_debilitation_days**

Average number of days a person has to stop working or perform their normal activities.

# **Min_debilitation_days**

Minimum number of days a person has to stop working or perform their normal activities.

# **Max_debilitation_days**

Maximum number of days a person has to stop working or perform their normal activities.

# **DALY**

<a href="https://www.who.int/data/gho/indicator-metadata-registry/imr-details/158#:~:text=Definition%3A-,One%20DALY%20represents%20the%20loss%20of%20the%20equivalent%20of%20one,health%20condition%20in%20a%20population.">Disability-adjusted life years</a>.

# **Social_category**

Social category of the people impacted, when clearly identified.

# **Age_category**

Age category of the people impacted, when clearly identified.

# **Gender**

(Main) gender of the people impacted, when clearly identified.

# **Other**

Temporary column for other types of impacts we might have forgotten - each will become a separate column in the end.

# **Implementation_social**

This states — at the time of the estimation — whether the reported cost was actually <strong>observed</strong> (i.e., cost actually incurred) or <strong>potential</strong> (i.e., not incurred but expected cost).

# **Acquisition_method_social**

Method used to obtain the cost estimate:
- report/estimation directly obtained or
- derived (using inference methods) from field-based information or
- extrapolation (cost predicted beyond the original spatial and/or temporal observation range from computational modelling).

# **Method_used_paper_social**

Method used to assess the social variables above as described in the paper.

# **Method_reliability_social**

Assessment of the methodological approach used to assess the social variables above as of:
- (<em>i</em>) <strong>high</strong> reliability if either provided by officially pre-assessed materials (peer-reviewed articles and official reports) or the estimation method was documented, repeatable and/or traceable if provided by other grey literature, or
- (<em>ii</em>) <strong>low</strong> reliability if not.

# **Method_reliability_refined_social**

Assessment of the methodological approach used to assess the social variables above as of high or low reliability based on the evaluation of the estimation methodology by expert contributors.

# **Method_reliability_Explanation_social**

Detailed explanation why a particular methodological approach used to assess the social variables above was deemed as of high or low reliability based on expert opinion.

# **Method_reliability_Expert_Name_social**

Complete name and contact details of the expert had deemed the reliability of the entry for the social variables above.

# **Type_Stakeholder**

The general type of stakeholder - a fixed list (e.g., Health provider, Individual, Community) from <a href="https://doi.org/10.1016/j.scitotenv.2024.173054">Roiz et al. (2024)</a>.

# **Stakeholder**

The actual stakeholder, e.g. the state or a company, the boundaries of the community (country, city, friends, ...).

# **Type_1_of_cost**

The two main types of costs:
- <strong>Damage/Loss</strong>, or
- <strong>Management</strong>, or
- <strong>Mixed</strong> when impossible to separate)

# **Type_2_of_cost**

The sub-categories of Type 1, roughly divided into <strong>direct</strong> and <strong>indirect</strong> costs, with some specificities depending on Type 1.

# **Type_3_of_cost**

The specific thing that cost money (e.g., medicines, TV campaign, name of eradication programme, etc.).

# **Unspecified_cost**

Temporary column for other types of costs we may have forgotten - each will become a separate column in the end.

# **Verbatim_evidence**

Extract from the article evidencing from where the information comes.

# **Fixed_variable**

Indicates if the costs are:
- <strong>fixed</strong> (constant cost - independent of the abundance of the invasive species or the disease) or
- <strong>variable</strong> (depends on the abundance of the invasive species or the disease).

# **Period_of_estimation**

If provided, the exact period of time covered by the cost, otherwise the raw formulation provided in the reference analysed (e.g., late 1990s, during 5 years)

# **Time_range**

Two options: 
- <strong>period</strong> if the cost is given for a period exceeding a year; or
- <strong>year</strong> if the cost is given yearly or for a period up to one year. 
- <strong>unspecified</strong>: if no information is given or guessable from the source

# **Probable_starting_year**

Year in which the cost is known or assumed to have started to occurred. When not explicitly provided by the authors, indicate <strong>unspecified</strong>; in the case of a cost estimate provided for a one-year period straddling two calendar years, use the latest year of the cost occurrence.

# **Probable_ending_year**

Year in which the cost is known or assumed to have ended. When not explicitly provided by the authors, indicate <strong>unspecified</strong>; in the case of a cost estimate provided for a one-year period straddling two calendar years, use the latest year of the cost occurrence.

# **Probable_starting_year_adjusted**

<em>Probable_starting_year</em> and <em>Probable_ending_year</em> columns where the cells with unspecified information are replaced, as much as possible, by a specific year from educated guesses based on the duration time provided in the original reference (see <em>Period_of_estimation</em> column). When relevant (e.g., the authors provide a cost that occurs "... since/for a well-defined number of years"), we considered the <em>Publication_year</em> as a reference for the probable starting/ending year from which we added or subtracted the number of years provided. When vague formulations were used (e.g., early 1990s), we still translated them in probable ending/starting year (e.g., 1990–1995). When annual costs were provided, but without clear information on the temporal range, we conservatively considered the year of the cost occurrence (or the <em>Publication_year</em>, if not provided) in both columns. When no relevant approximation is feasible, we leave blank in one and/or the other column(s). These columns are those used for obtaining the number of years by which the raw cost estimates are divided to get the cot estimates per year.

# **Probable_ending_year_adjusted**

<em>Probable_starting_year</em> and <em>Probable_ending_year</em> columns where the cells with unspecified information are replaced, as much as possible, by a specific year from educated guesses based on the duration time provided in the original reference (see <em>Period_of_estimation</em> column). When relevant (e.g., the authors provide a cost that occurs "... since/for a well-defined number of years"), we considered the <em>Publication_year</em> as a reference for the probable starting/ending year from which we added or subtracted the number of years provided. When vague formulations were used (e.g., early 1990s), we still translated them in probable ending/starting year (e.g., 1990–1995). When annual costs were provided, but without clear information on the temporal range, we conservatively considered the year of the cost occurrence (or the <em>Publication_year</em>, if not provided) in both columns. When no relevant approximation is feasible, we leave blank in one and/or the other column(s). These columns are those used for obtaining the number of years by which the raw cost estimates are divided to get the cot estimates per year.

# **Occurrence**

Status of the cost estimate as potentially <strong>ongoing</strong> (if the cost can be expected to continue over time) or <strong>one-time</strong> (if the cost was deemed as unlikely to continue).

# **Raw_cost_estimate_original_currency**

Cost estimate directly retrieved from the analysed reference.

# **Min_Raw_cost_estimate_original_currency**

# **Lower boundary of the <em>Raw_cost_estimate_original_currency</em> (if a range of estimates was provided by the authors).

# **Max_Raw_cost_estimate_original_currency**

Upper boundary of the <em>Raw_cost_estimate_original_currency</em> (if a range of estimates was provided by the authors).

# **Raw_cost_estimate_2023_USD_exchange_rate**

Raw cost estimate in the original currency standardised from original <em>Currency</em> and <em>Applicable_year</em> to 2023 US$ based on the official market exchange rate (original currency unit per US$) provided by the <a href="https://data.worldbank.org/indicator/PA.NUS.FCRF?end=2017&start=1960">World Bank Open Data</a>.

# **Raw_cost_estimate_2023_USD_PPP**

Raw cost estimate in the original currency standardised to 2023 US$ based on the official Purchase Power Parity (PPP; original currency unit per US$) provided by the <a href="https://data.worldbank.org/indicator/PA.NUS.PPP?end=2017&start=1990)">World Bank Open Data</a> and the <a href="https://data.oecd.org/conversion/purchasing-powerparities-ppp.htm">Organisation for Economic Cooperation and Development</a>.

# **Cost_estimate_per_year_original_currency**

Raw cost estimate transformed to a cost estimate per year of the <em>Period_of_estimation</em>, obtained by dividing the <em>Raw_cost_estimate_original_currency</em> by the number of years between the <em>Probable_starting_year_completed</em> and <em>Probable_ending_year_completed</em>. Blank cells are those that have no information in at least one of these two previous columns.

# **Cost_estimate_per_year_2023_USD_exchange_rate**

Cost estimate per year standardised from original <em>Currency</em> and <em>Applicable_year</em> to 2023 USD based on the official market exchange rate (original currency unit per US$) provided by the <a href="https://data.worldbank.org/indicator/PA.NUS.FCRF?end=2017&start=1960">World Bank Open Data</a>. Blank cells are those that have no information in at least one of these two previous columns.

# **Cost_estimate_per_year_2023_USD_PPP**

Cost estimate per year original currency standardised from original <em>Currency</em> and <em>Applicable_year</em> to 2023 USD based on purchase power parity (PPP; original currency unit per US$) provided by the <a href="https://data.worldbank.org/indicator/PA.NUS.PPP?end=2017&start=1990">World Bank Open Data</a> and the <a href="https://data.oecd.org/conversion/purchasing-powerparities-ppp.htm">Organisation for Economic Cooperation and Development</a>. Blank cells are those that have no information in at least one of these two previous column.

# **Currency**

Original currency of the <em>Raw_cost</em> estimate as extracted in the original reference and standardised (when possible) using internationally recognized <a href="https://www.iso.org/fr/iso-4217-currency-codes.html">ISO 4217</a> codes.

Fifty currencies are currently recorded in <em>InvaCost</em>:
- ARS (Argentine peso), 
- AUD (Australian Dollars),
- CAD (Canadian Dollars),
- CHF (Swiss Fanc),
- CLP (Chilean Peso),
- COL (Colombian Peso)
- CUP (Cuban Peso)
- CZK (Czech Crown)
- DEM (Deutsche Mark)
- DKK (Danish Krone)
- ESP (Spanish Peseta)
- EUR (Euro)
- FJD (Fijian Dollar)
- FRF (French Franc)
- GBP (Pound Sterling)
- HKD (Hong Kong Dollars)
- HRK (Croatian Kuna)
- INR (Indian Rupee)
- ISK (Icelandic Crown)
- JPY (Yen)
- KES (Kenyan Shilling)
- LKR (Sri Lankan Rupee)
- LTL (Lithuanian Litas)
- MAD (Moroccan Dirhams)
- MGA (Malagasy Ariary)
- MXN (Mexican Peso)
- NGN (Naira)
- NLG (Dutch Guilder)
- NOK (Norwegian Krone)
- NZD (New Zealand Dollar)
- PKR (Pakistani Rupee)
- PLN (Polish Zoty)
- REA (Brazilian Real)
- CNY (Yuan Renminbi)
- RUB (Russian Ruble)
- SEK (Swedish Krona)
- SGD (Singapore Dollar)
- SOL (Peruvian Sol)
- TND (Tunisian Dinar)
- TRY (Turkish Lira)
- TWD (New Taiwan Dollar)
- UAH (Ukrainian Hryvnia)
- USD (United States Dollars)
- UYU (Uruguay New Peso)
- XAF (CFA Franc BEAC)
- XOF (CFA Franc BCEAO)
- XPF (Pacific Franc)
- ZAR (South African Rand)
- ZWL (Zimbabwean Dollar)

# **Applicable_year**

Year of the <em>Currency</em> value (not the year of the cost occurrence) considered for the conversion/standardization of the cost estimate.

# **Type_of_applicable_year**

Assessment of the applicable year as effective if explicitly stated by the authors or publication year if no explicit information was provided in the reference analysed.

# **Implementation**

At the time of the estimation, whether the reported cost was actually observed (i.e., cost <strong>actually</strong> incurred) or <strong>potential</strong> (i.e., not incurred but expected cost)

# **Acquisition_method**

Method used to obtain the cost estimate:
- <strong>report/estimation</strong> directly obtained or derived (using inference methods) from field-based information or
- <strong>extrapolation</strong> (cost predicted beyond the original spatial and/or temporal observation range from computational modelling)

# **Management_type**

- <strong>pre-emergence_management</strong>: monetary investments for preventing health issues in an area - including quarantine or border inspection, risk analyses, biosecurity management, etc.),
- <strong>post-emergence_management</strong>: money spent for managing health issues in invaded areas - including control, eradication, containment), knowledge funding (money allocated to all actions and operations that could be of interest at all steps of management at pre- and post-emergence stages - including administration, communication, education, research, etc.), or
- <strong>mixed</strong>: when costs include at least (and without possibility to disentangle the specific proportion of) two of the previous categories;
- <strong>unspecified</strong>: every management cost (in the <em>Type_of_cost</em> column) for which the exact nature of cost was not clearly defined 
- <strong>NA</strong>: every entry that has partly or fully associated with damage costs

# **Method_used_paper**

Method used as described in the paper.

# **Method_reliability**

Assessment of the methodological approach used for cost estimation as:
- <strong>high</strong> reliability, if either provided by officially pre-assessed materials (peer-reviewed articles and official reports) or the estimation method was documented, repeatable and/or traceable if provided by other grey literature, or
- <strong>low</strong> reliability if not.

# **Method_reliability_refined**

Assessment of the methodological approach used for cost estimation as of high or low reliability based on the evaluation of the estimation methodology by expert contributors.

# **Method_reliability_Explanation**

Detailed explanation why a particular methodological approach used for cost estimation was deemed as of high or low reliability based on expert opinion.

# **Method_reliability_Expert_Name**

Complete name and contact details of the expert had deemed the reliability of the cost entry.

# **Overlap**

List of cost entries (using the <em>Cost_ID</em> column) that might overlap with other cost entry(s) — this is noted as follows:
- <strong>Z(V/W)</strong>: when the overlap is known and one or more cost IDs (V,W) are included in another cost ID (Z)
- <strong>Z/V/W</strong>: when the overlap is not clear
- <strong>Z(V)</strong>: when the overlap is known and one cost ID (V) is included in another cost ID (Z)
- <strong>Z/W</strong>: when the overlap is not clear

# **Benefit_value**

Mention (if any) of the benefit value in the analysed material (<strong>yes</strong> or <strong>no</strong>). 'Benefit' refers here to a monetary estimate associated with profitable activities based on invasive species. This definition therefore excludes any economic gain based on avoided or mitigated effects of the invasive species (e.g., due to efficient management actions over time that might result in apparent benefits from avoidance of damage) - the latter is considered as an “avoided cost” in the <a href="https://github.com/InvaHealth/invacost"><em>InvaCost</em></a> database. The benefit figure was not recorded or described as being out of the scope of InvaCost. See <a href="https://doi.org/10.1093/biosci/biae010">Carneiro et al. (2024)</a> for a more elaborate discussion of benefits <em>versus</em> costs of invasive species.

# **Details**

When necessary, narrative elements deemed important either to understand the cost estimate or to support choices made for completing the database; this column was left unchanged from the original entries in order to allow trace-back investigations.

# **Initial_contributors_names**

Name of contributor(s) having collated the cost entry.

# **Double_checking**

Assessment of cost information collated (by at least) two contributors;
- <strong>yes</strong> if it has been double checked,
- <strong>no</strong> if it has not.
The names/contacts of each contributor are provided in the <em>Initial_contributors_names</em> column.
