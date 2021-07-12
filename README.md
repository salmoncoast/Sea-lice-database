# Sea-louse parasites on juvenile wild salmon in the Broughton Archipelago, British Columbia, Canada

This repository contains data from long-term monitoring of juvenile salmon for sea lice, by the [Salmon Coast Field Station](www.salmoncoast.org). Questions should be directed to Stephanie Peacock (stephanie.j.peacock@gmail.com).

**Last update:** July 12, 2021; data current through July 2, 2021 (last sampling day for 2021 season)
 
## Using the data
* **Before** using the data, please read the associated metadata (below)!
* To download the entire repository, including the data and metadata, click "Download ZIP" under the green "Clone or download" button near the top-right of this page
* The fish and site data can be accessed at the following URLs:

> [https://raw.githubusercontent.com/sjpeacock/Sea-lice-database/master/Data/BroughtonSeaLice_fishData.csv](https://raw.githubusercontent.com/sjpeacock/Sea-lice-database/master/Data/BroughtonSeaLice_fishData.csv)

> [https://raw.githubusercontent.com/sjpeacock/Sea-lice-database/master/Data/BroughtonSeaLice_siteData.csv](https://raw.githubusercontent.com/sjpeacock/Sea-lice-database/master/Data/BroughtonSeaLice_siteData.csv)

* To import import the fish and site data directly into R simply use the `source_data` function in the `repmis` package:

```
FishData <- repmis::source_data(url = "https://raw.githubusercontent.com/sjpeacock/Sea-lice-database/master/Data/BroughtonSeaLice_fishData.csv")
SiteData <- repmis::source_data(url = "https://raw.githubusercontent.com/sjpeacock/Sea-lice-database/master/Data/BroughtonSeaLice_siteData.csv")
```

## Authors

Stephanie J Peacock (1,†), Andrew W Bateman (1,2,3,†), Martin Krkosek (2,3), Brendan Connors (4), Scott Rogers (3,5), Lauren Portner (3), Zephyr Polk (3), Coady Webb (3), Alexandra Morton (3,6)

1. Department of Biological Sciences, University of Alberta, Edmonton, AB T6G 1E9
2. Ecology and Evolutionary Biology, University of Toronto, Toronto, ON M5S 3B2 
3. Salmon Coast Field Station, Simoom Sound, BC V0P 1S0 
4. ESSA Technologies Ltd., Vancouver, BC V6H 3H4
5. Raincoast Conservation Foundation, Sidney, BC V8L 3Y3
6. Raincoast Research Society, Sointula, BC V0N 3E0

† Joint first authors

## Abstract

The global expansion of aquaculture has changed the structure of fish populations in coastal environments, with implications for disease dynamics. In Pacific Canada, farmed salmon act as reservoir hosts for parasites and pathogens, including sea lice (*Lepeophtheirus salmonis* and *Caligus clemensi*) that can transmit to migrating wild salmon.  Assessing the impact of salmon farms on wild salmon requires regular monitoring of sea-louse infections on both farmed and wild fish. Since 2001, we have collected juvenile pink (*Oncorhynchus gorbuscha*) and chum (*O. keta*) salmon annually at three sites in the Broughton Archipelago in British Columbia, Canada, during the annual juvenile-salmon migration from freshwater to the open ocean.  From sampled fish, we recorded counts of parasitic copepodid-, chalimus-, and motile-stage sea lice.  We report louse abundances as well as supplementary observations of fish size, development, and health.

**Keywords:** aquaculture, conservation, parasite, salmon, sea lice

## Introduction

Increased salmon aquaculture production over the past several decades (Goldburg and Naylor 2005) has been associated with the decline of wild salmonid stocks around the world (Ford and Myers 2008).  On the west coast of Canada, the expansion of Atlantic salmon (*Salmo salar*) aquaculture has raised concerns about impacts to wild salmon as a result of the amplification of naturally occurring parasitic sea lice (*Lepeophtheirus salmonis* and *Caligus clemensi*).  In certain areas of coastal British Columbia (BC), sea-louse infestations on salmon farms have been implicated in wild-salmon population declines (Krkosek et al. 2011b).  

For some populations of pink salmon (*Oncorhynchus gorbuscha*) and chum salmon (*Oncorhynchus keta*), juveniles must migrate directly past open-net salmon farms anchored near to shore as they migrate from their natal streams and rivers to open-ocean habitats.   Along these routes, sea lice can disperse from farmed salmon and infect juvenile wild salmon, often before the wild salmon develop protective scales, leading to increased predation susceptibility an reduced survival (Krkosek et al. 2006, 2011a).  Pink salmon populations have shown significantly reduced productivity when louse levels are high (Krkosek et al. 2011b), however, chum salmon have not (Peacock et al. 2014). Recent farm-management practices appear to have halted earlier declines in pink salmon productivity (Peacock et al. 2013), although sea louse infestation levels were once again elevated in 2015 (Bateman et al., in review).

Since 2001, we have carried out monitoring of sea-louse infestation levels on wild-caught juvenile pink and chum salmon in the Broughton Archipelago, BC, an area of active salmon aquaculture. The data we have collected have been used to quantify temporal trends in parasites burdens to inform questions of ecological, conservation, management and policy relevance. Here, we make these data that have resulted from this long term monitoring program available.

## Contents of this repository:

### Metadata files:
* fish_variableDescriptions.csv - describes columns in BroughtonSeaLice_fishData.csv
* site_variableDescriptions.csv - describes columns in BroughtonSeaLice_siteData.csv
* Figures - subfolder containing all figures.

### Data files:
* BroughtonSeaLice_fishData.csv - contains the individual fish health and sea louse counts from 2001 to present.
* BroughtonSeaLice_siteData.csv - contains the site data (location, temperature, salinity etc.) for each sampling location/date combination.


# METADATA

## Class I. Data set descriptors

### A. Data set identity

Sea-louse parasites on juvenile wild salmon in the Broughton Archipelago, British Columbia, Canada

### B. Data set identification code

1. Site data: BroughtonSeaLice_siteData.csv
2. Fish data: BroughtonSeaLice_fishData.csv

### C. Data set description

#### 1. Originator

Alexandra Morton
Raincoast Research, Sointula, BC V0N 3E0
Salmon Coast Field Station, Simoom Sound, BC V0P 1S0

#### 2. Abstract

Since 2001, we have collected juvenile pink (*Oncorhynchus gorbuscha*) and chum (*O. keta*) salmon annually at three sites in the Broughton Archipelago in British Columbia, Canada, during the annual juvenile-salmon migration from freshwater to the open ocean.  From sampled fish, we recorded counts of parasitic copepodid, chalimus, and motile stage sea lice (*Lepeophtheirus salmonis* and *Caligus clemensi*).  We report louse abundances as well as supplementary observations of fish size, development, and health.

### D. Key words

Broughton Archipelago, British Columbia, 2001 through 2015, sea lice, *Lepeophtheirus salmonis*, *Caligus clemensi*, salmon, *Oncorhynchus gorbuscha*, *Oncorhynchus keta*, migration, aquaculture

## Class II. Research origin descriptors

### A. "Overall project" description
The sea lice monitoring does not represent part of a larger "overall" project. Therefore, the project details can be found below under B. "Specific subproject" description, with the exception of 6. Source(s) of funding, which we provide below.

#### 6. Source(s) of funding
* Raincoast Research Society, Box 399, Sointula, BC V0N 3E0
* Salmon Coast Field Station Society, General Delivery, Simoom Sound, BC V0P 1S0 (including small grants from the Pacific Salmon Foundation, channeled through the Salmon Coast Field Station Society)
* In-kind contributions of volunteers, equipment, and boat time from University of Alberta (Dr. Mark Lewis), University of Victoria (Dr. John Volpe) and University of Toronto (Dr. Martin Krkosek)

### B. "Specific subproject" description

#### 1. Site description

##### a. Site type

Sampling occurred in the coastal marine environment within ~10 m of shoreline.

##### b. Geography

The Broughton Archipelago lies within the regional district of Mount Waddington in British Columbia, Canada. Sample locations were between 50 46.237' N to 50 57.267' N and 126 17.035' W to 126 41.522' W (Fig. 1).  The area is Musgamagw Dzawada’enuxw Territory and has a rich history of use by indigenous people. The inlets and channels are home to abundant wildlife, and provide nursery habitat for marine and anadromous fishes.  Sampling locations were situated along juvenile pink and chum migration routes, as they swim from natal streams and rivers towards the open ocean (Fig. 1).


![Fig1](https://github.com/sjpeacock/Sea-lice-database/blob/master/Metadata/Figures/Fig1.png)
**Fig. 1.**  Map of the study area showing the three locations (Glacier, Burdwood, and Wicklow) where juvenile salmon were monitored for sea louse parasites, as well as the locations of all salmon farms that were active at some point during monitoring from 2001-2015.

##### c. Habitat

Juvenile salmon were usually found close to shore, in water depths from one to five metres below surface, in bays sheltered from strong tidal currents and waves. Tides range from one to four metres, and the shoreline habitat is often dependent on tide height, ranging from rocky intertidal to shell beaches to forest edge. Because sampling occurred on a regular weekly basis during daylight hours, tide height could not be controlled for when sampling. Towards the end of the annual sampling period, in June, beds of bull kelp (*Nereocystis luetkeana*) developed in which the salmon could be found at low tide, and occasionally we sampled in these beds. As the season progressed, and juvenile salmon grew, they would occur at greater depths and further offshore, but never more than ~10 metres (as we made collections by beach seine, we limited our search zone to the near-shore environment; Fig. 2).


![Fig2](https://github.com/sjpeacock/Sea-lice-database/blob/master/Metadata/Figures/Fig2.png)
**Fig. 2.** Setting a beach seine on Denham Island at high tide near the Burdwood location. This image illustrates the typical shoreline and landscape of the Broughton Archipelago. Photo credit: Stephanie Peacock


##### d. Geology, landform

The inlets of the Broughton Archipelago are bounded by steep hillsides, forested primarily with western hemlock (*Tsuga heterophylla*), Douglas fir (*Pseudotsuga menziesii*), and Pacific red cedar (*Thuja plicata*). Underlying these dense forests is granitic bedrock that is often exposed by landslides in the wet winter months (Fig. 2). The area has been subject to logging over the past hundred years, which has intensified landslides in the area. Much of the shorelines are steep granite cliffs offering little opportunity for beach seining, but the specific sampling sites for our data consist of rocky sloping points and bays (e.g., Fig. 2). Sampling occasionally occurs off shell beaches closer to high tide. The seafloor generally drops off steeply towards the middle of the channels, although depths may remain shallow within bays.

##### e. Watersheds, hydrology

The hydrology of the Broughton Archipelago is comprised of a network of inter-island marine channels, leading from deep glacial inlets.  Other than tides, the main determinants of hydrological flow are freshwater inputs from riverine and glacial runoff and surface currents generated by strong winds (Foreman et al. 2006).  From west to east, the main rivers feeding into the Archipelago are the Embley, Wakeman, Kingcome, Ahta, Kakweiken, Glendale, Ahnuhati, and Klinaklini.  Detailed description of the estuarine and tidal currents can be found in Foreman et al. (2006).

#### 2. Sampling design

##### a. Design characteristics

We designed the sea lice monitoring program to generate a long-term abundance time series of sea louse parasites on wild juvenile salmon at three sampling locations (Fig. 1).  While parallel studies have sought to characterize sea-louse abundance as a function of farm proximity (e.g., Krkosek et al. 2005a, 2006), the data we present here were collected to assess temporal patterns related to salmon-farm development, stocking, and changes to sea lice management including the timing of treatments with chemotherapeutants (Peacock et al. 2013).

The distribution of sea lice among hosts tends to be clustered (Murray 2002), requiring a relatively large sample size to accurately describe the distribution of parasites.  Thus, we aimed to sample 50 pink and 50 chum salmon at each sample site, although we were often limited by salmon availability and did not always achieve this. In early years (2001-2006), there were usually no more than 50 salmon total sampled at each site, while in later years (2007-2015) we regularly achieved a sample size of 100 salmon (Fig. 3; also summarized in site data). Pink salmon were usually more abundant than chum salmon.  From 2007 to 2012, if we did not obtain our sample goal of 50 chum salmon at a given site, we examined  additional pink salmon (if available) to reach the 100-salmon target.  From 2013-2015, we aimed for 50 pink salmon and 50 chum salmon, but we did not supplement the sample when either species was limiting (Fig. 3). 


![Fig3](https://github.com/sjpeacock/Sea-lice-database/blob/master/Metadata/Figures/Fig3.png)
**Fig. 3.** The number of pink salmon (grey) and chum salmon (black) sampled at three locations: (a) Glacier, (b) Burdwood and (c) Wicklow, from 2001 to 2015.

##### b. Permanent plots

We carried out sampling at three locations referred to as Glacier, Burdwood, and Wicklow, in reference to their geographic locations near "Glacier Falls" in Tribune Channel, within the Burdwood Group, and in Wicklow Bay of Fife Sound, respectively (Fig. 1).  Exact sampling sites within an approximate one-kilometre radius of our three sampling locations varied from day to day, in accordance with weather conditions and availability of juvenile salmon schools.  We took GPS coordinates of sample sites sporadically from 2011 to 2012, and more consistently since 2013. When available, we provide latitude and longitude (decimal degrees) with each site location (Glacier, Burdwood, or Wicklow) in the site data file. These sites were selected because of their location along a major migration route of juvenile salmon and proximity to salmon farms (Fig. 1).  The status of salmon farm tenures at each site varied from year to year between fallow and stocked with smolt or adult Atlantic salmon (for farm stocking and sea lice, see supplemental data to Marty et al. 2010). 

##### c. Data collection period, frequency, etc.

The frequency of monitoring has been variable, particularly in the early years of monitoring (Fig. 4).  More recently, we have aimed to monitor all three sites on a weekly basis from April 1st to June 30th.  In some years, we did not monitor Wicklow, the site furthest from the wild-salmon spawning rivers, at the beginning of the season, because there were no juvenile salmon to be found there.  Similarly, later in some years, we did not monitor Glacier, the site closest to the spawning rivers, for lack of fish (e.g., 2001, 2009; Fig. 4). 


![Fig4](https://github.com/sjpeacock/Sea-lice-database/blob/master/Metadata/Figures/Fig4.png)
**Fig. 4.** The sampling window from 2001-2015, showing dates within each year that the three monitoring sites were sampled for juvenile salmon. In recent years, we have aimed to sample weekly for April through May, inclusive (cyan band) to coincide with the period of greatest juvenile pink and salmon outmigration.


#### 3. Research methods

##### a. Field/laboratory

###### Salmon collection

In all years, we began juvenile-salmon collection at a site by visually searching near-shore waters (~2-5m from shore) from an open boat (~7m in length) at low speed, looking for schools of juvenile salmon near the surface of the water.  Once we observed a school, we used a net to live-collect constituent juvenile salmon (Fig. 2; for net details, see section b. Instrumentation). At the location of capture, we recorded the sea surface temperature and salinity, as well as GPS location (2013-2015).  We noted any incidental catch of other fish species (Table 1) and released non-salmonids. This information is available in the site data.

After capture, we transferred juvenile salmon into seawater-filled buckets either directly from the dip net (2001 through 2003) or from the bunt of the beach seine net using small dip nets.  From 2001 through 2004, we transferred juvenile salmon from the buckets into individual sample bags, placed them on ice, and later froze them for subsequent laboratory analysis. In the lab, we analyzed frozen samples under a dissecting microscope at 30x magnification.  From 2005 through 2015, we analyzed juvenile salmon non-lethally on site, using a 16x magnification hand lens to visually assay individual fish in clear plastic envelopes made from Ziploc® bags (detailed methods and assessment in Krkosek et al. 2005b).  

For each juvenile salmon sampled, we recorded species (pink, *O. gorbuscha*, or chum, *O. keta*).  Occasionally, we encountered other salmon species (e.g., *O. kisutch* and *O. nerka*), Pacific herring (*Clupea pallasii*), or threespine stickleback (*Gasterosteus aculeatus*) and examined these for sea lice, but the corresponding data are not part of this dataset. 

We recorded fork length (from the "fork" in the tail, the most anterior portion of the tails posterior edge, to the anterior tip of the snout) and, in years 2003, 2004, 2006, and 2010 through 2015, body depth (the greatest dorsal-ventral measurement of a juvenile’s body, not including its fins) to the nearest millimetre by measuring the salmon against 1 mm graph paper (Fig. 5A). In 2004 and 2005, some fish were measured with digital calipers and so the fork lengths are given to one decimal place in mm.


![Fig5](https://github.com/sjpeacock/Sea-lice-database/blob/master/Metadata/Figures/Fig5.png)
**Fig. 5.** A. Measurements of fork length and, in some years, body depth to the nearest mm were recorded for each salmon. B. We noted damage from, for example, predators. Highlighted with an arrow is a semi-circular scar from a fish predator. C. Pinched belly (PB) occurred when a chalimus-stage louse attached to the ventral surface causing the epidermis to scar and pinch as the fish grows. D. Copepodid- and chalimus-stage lice were identifiable under a 16x hand lens.  Shown here are a copepodid-stage L. salmonis (C, black arrow), and several chalimus-stage lice (species unknown; H, white arrows). The upper two chalimus stage lice have accompanying chalimus scars that would be noted. E. An example of a chalimus scar (CS) from the attachment of chalimus-stage louse (H). Blue blotches can be seen on the dorsal surface. F. An eroded gill (EG) was noted, and if a louse was attached nearby this was accompanied by a comment of a grazed gill place (GGP).  Shown also is a chalimus scar beneath the dorsal fin (CS).

###### Louse identification

We categorized the species (*L. salmonis* or *C. clemensi*) and stages of attached sea lice according to published descriptions (Kabata 1972, Johnson and Albright 1991, Hamre et al. 2013).  A hand lens revealed sufficient detail to differentiate copepodid, chalimus, and motile stages of sea lice (Krkosek et al. 2005b).  For 2001, we do not have information on the species of sea lice, but C. clemensi was relatively uncommon (Morton and Williams 2003); all sea lice in 2001 were recorded as unidentified species (data columns unid_cope, unid_PA, unid_adult; Fig. 6).  For 2002-2004, we only distinguished between L. salmonis and C. clemensi for motile sea lice. From 2002 onwards, we further distinguished L. salmonis as pre-adult, adult males, non-gravid adult females, and gravid adult females (Fig. 6). For years 2004-2007, pre-adult L. salmonis were not identified to sex, but for years 2002-2003 and 2008 onwards, we identified pre-adult L. salmonis as male or female (Table 2). We did not distinguish pre-adult I and pre-adult II stages, as this is difficult to do accurately using a hand lens.  For motile C. clemensi, we distinguished adults (male and female) from gravid females, but did not distinguish non-gravid females from males or adults from pre-adults. Starting in 2005, we distinguished *L. salmonis* and *C. clemensi* at the copepodid stage (Fig. 5D). Given the similarity between *L. salmonis* and *C. clemensi* at the chalimus stage, we did not distinguish the two louse species at that stage.  We did, however, distinguish "chalimus A" and "chalimus B" stages, based on size and development (Hamre et al. 2013). The number of observed sea lice in each category, including instances of zeroes and missing data, are summarized in Table 2.

Occasionally, we observed adult male sea lice firmly attaching to the posterior end of pre-adult female sea lice.  We noted this behaviour as "mate guarding" on the datasheet, as it may be of interest in studies of dispersal and mate limitation (e.g., Connors et al. 2011).  Sometimes we were unable to definitively identify the sex of the louse on the bottom of the mateguarding pair as it was partially concealed, and in such cases we assumed it to be a pre-adult female.

![Fig6](https://github.com/sjpeacock/Sea-lice-database/blob/master/Metadata/Figures/Fig6.png)
**Fig. 6.** The relationships among unique columns in the dataset: italic grey words are the unique stages/sex/species that are differentiated in the dataset.  In early years (2001-2006) not all stages/species were distinguished; see text for details.


###### Fish health observations

We recorded louse-induced damage including chalimus scars from where a chalimus-stage louse had been attached and motile scars from feeding behaviour of motile-stage lice. Chalimus scars were identified as dark indents with a radius of grazed skin (Fig. 5E,F).  A chalimus-stage louse often, but not always, accompanied the scar. We recorded the number of chalimus scars because chalimus-stage sea lice are attached by a tether, and therefore each scar can be attributed to the development of a single louse on the host fish.  Motile scars were identified as smaller dark pin pricks, usually on the flank of the fish.  As for chalimus scars, the responsible motile louse was often, but not always, present. We note presence/absence of motile scars, since a single louse could inflict multiple motile scars on its host.

In addition to louse counts, we recorded any evidence of predation and noted whether it appeared to be from avian predators (linear slash marks) or fish predators (semi-circular arrays of tooth marks; Fig. 5B). We also recorded any haemorrhaging, identified as red spots on skin or fins, and noted the location of haemorrhaging in the comments. Common locations on the fish to which we refer in the comments include the adipose fin (ADF), anal fin (ANF), caudal fin (CDF), pectoral fins (PCF), pelvic fins (PVF), dorsal fin (DF), snout, flank, caudal peduncle, "gill plate" (operculum), and eye. We noted erosion of the gill plate (Fig. 5F), and in the Comments we clarified whether the eroded gill appeared to be due to grazing from sea lice (i.e., grazed gill plate, GGP). It was noted that salmon seemed to darken in colour when under stress (A. Morton, personal observation), and beginning in 2006 we noted significant dark blue coloration of salmon as "blue blotches" (Fig. 5E). We recorded if the salmon had a "pinched belly" where the skin had tightened, which was often associated with a chalimus scar on the flank (Fig. 5C). We noted in the Comments any substantial damage to fins, as well as other opportunistic fish-health observations that did not conform to the already mentioned categories.  Finally, we noted if the salmon had begun to develop scales, as scales can confer protection against sea lice and mark a development threshold for impacts to host fish (Brauner et al. 2012).

Beginning in 2018, we also recorded the presence of opaque sections in the eyes of juvenile salmon. It is unknown what the causes or consequences of this "white eye" are, but it is anecdotally increasing in frequency and also present among farmed salmon. Observations are noted as "1" if there is any presence of white opaque sections in a fish's eye (Fig. 7).

After non-lethal examination, we allowed fish to recover in a 20 litre seawater-filled bucket and then released them at the location of capture. We noted any mortalities of salmon that had been examined and (separately) any mortalities of salmon held in the net or buckets but not examined. Before releasing all salmon captured, we also estimated and recorder the total number of pink and chum salmon captured and the ratio of pink to chum salmon in the school.  This information is available with the site data. 

![Fig7](https://github.com/sjpeacock/Sea-lice-database/blob/master/Metadata/Figures/Fig7.png)
**Fig. 7.**  Pictures of three juvenile salmon showing the presence of "white eye" with a small, cloudy spot in the centre of the eye (a), a larger opaque section (b), and a more severe case where the opaque section covers most of the eye (c). All of these cases would be scored as "1" indicating the presence of white eye.

##### b. Instrumentation

Once we observed a salmon school in the near-shore environment, we collected salmon either by dip net (45 cm diameter with 5 mm knotless mesh on a 2.45 m pole from a 7.5 m boat; 2001 through 2003) or using a beach seine net (from a 5-6 m boat; 2004 through 2015).  The physical specifications of the seine net changed through time, from a small net: 15.2 m long by 1.8 m deep with 4 mm knotless mesh bunt (2004-2007) to a larger net: 40 m long by 2.5 m deep with 4 mm knotless mesh bunt (2008-2015).  Dip nets used to transfer fish out of the beach-seine bunt (2004 through 2015) were 10 cm2 to 15 cm2 on a 30 cm handle with 2 mm knotless mesh.

Hand lenses used to identify sea lice were 16x magnification (Ruper). Sea surface temperature was recorded using a red-spirit-filled pocket thermometer with a range of -5° degrees C to 45 degrees C in increments of 0.5 degrees C.  Salinity was recorded using a handheld Vee-Gee STX-3 Salinity Scale Optical Refractometer, designed to accurately measure salinities from 0-100 ppt. Refractometers were calibrated on a weekly basis using fresh water. From 2013 through 2015, both temperature and salinity were measured 0.2 m under the surface using a YSI Pro30 meter (Yellow Springs, Ohio; www.ysi.com/). YSI meters were calibrated monthly using a NIST-traceable conductivity solution (#3169, 50,000 uS/cm + 1.0% tolerance).

##### c. Taxonomy and systematics

Table 1. Species listed in dataset, either as host species, incidental catch, or recorded parasites*. Those included in the fish data are bolded, while only pink and chum salmon were targeted.

Latin name |  Common name(s)
---|---
*Oncorhynchus gorbuscha* | pink salmon, humpback salmon
*Oncorhynchus keta* |chum salmon, dog salmon, Keta  salmon
*Oncorhynchus nerka* | sockeye salmon, red salmon
*Oncorhynchus kisutch* |coho salmon
*Oncorhynchus tsawytscha* |Chinook salmon, spring salmon, king salmon
*Oncorhynchus clarkii clarkii*	|(coastal) cutthroat trout 
*Clupea pallasii pallasii* | Pacific herring
*Ammodytes hexapterus* | Pacific sand lance
*Aulorhynchus flavidus* | tube-snout
*Gasterosteus aculeatus* | three-spined stickleback, threespine stickletback
*Nautichthys oculofasciatus* | sailfin sculpin
*Apodichthys fucorum* | rockweed gunnel
*Sebastes* spp. | Rockfish (juvenile)
*Lepeophtheirus salmonis* | salmon louse
*Caligus clemensi* | herring louse

*Species and common names are as recorded at www.marinespecies.org.


##### d. Permit history

Each year, a Scientific Fishing Permit from Fisheries and Oceans Canada was issued to Alexandra Morton to cover the collection of pink and chum salmon. The non-lethal salmon collection and sea-louse identification protocol described above received ethics approval from the Animal Care & Use Committee at the University of Alberta (Protocol #00000031) and the University of Toronto (Protocol #2000), both under the Canadian Council for Animal Care.

#### 4. Project personnel

Alexandra Morton conceived and initiated the monitoring program. Martin Krkosek, Brendan Connors, Scott Rogers and Lauren Portner facilitated the evolution of the monitoring protocol, particularly with regards to sea louse identification. Stephanie Peacock and Andrew Bateman initiated and undertook the cleaning of the data and writing of these metadata, in addition to their monitoring contributions over the years. Throughout the years, the managers of the Salmon Coast Field Station - Scott Rogers, Zephyr Polk and Coady Webb - played a significant role in organizing and facilitating the monitoring. 

A small army of people have beach seined and "sea liced," including (but not limited to, in no particular order): Amy McConnell, Claudia Maas and Oline Luninberg (The RubberMaids), Dane Stabel, Caitlin Currey, Helen Page (née Ford), Kersti Vaino, Ashley Powell (née Park), Megan Adams, Marie-Josée Gagnon, Jordan Flanagan, Sean Godwin, Leah Walker, Mack Bartlett, Julia Simmerling, Alex Spicer, Christina Weir, Alex Reiss, and Anna Crandall. 

## Class III. Data set status and accessibility

### A. Status

#### 1. Latest update

History of updates of data:

August 31, 2016: SJP added data from 2016 monitoring season.

March 28, 2017: SJP added missing data from June 2010 sent by Scott Rogers. 

October 8, 2017: SJP added data from 2017 monitoring season.

August 10, 2018: SJP added data from 2018 monitoring season, updated fish data to include observations of "white eye" (see Fig. 7).

Febraury 27, 2020: SJP added data from 2019 monitoring season.

December 7, 2020: SJP added data from 2020 monitoring season.

April 30, 2021: SJP added data for April 2021 for in-season update.

May 26, 2021: SJP added data for May 2021 in-season update.

July 12, 2021: SJP added remainder of data for 2021 field season.

#### 3. Metadata status

December 2015: metadata compiled.

March 24, 2016: revised based on comments from two anonymous reviewers at Ecology. Main revisions were (1) removal of paper summaries and (2) addition of Table 2 distinguishing true zeroes from missing data.

#### 4. Data verification

December 2015: Verified up to and including 2015.
August 31, 2016: 2016 data checked and added to database by SJP.
October 8, 2017: 2017 data checked and added to database by SJP.
August 10, 2018: 2018 data checked and added to database by SJP.
February 27, 2020: 2019 data checked by Emma Atkinson and added to database by SJP.
December 7, 2020: 2020 data checked by SJP and Rob Hummeny (SCFS).
April 30, 2021: SJP wrote a short script to check and add data from G-Sheet for in-season updates.
July 12, 2021: 2021 data run by checks in dataUpdate.R


### B. Accessibility

#### 1. Storage location and medium

These metadata and associated data files have been submitted to the Ecology. The data and metadata are also accessible on GitHub (https://github.com/sjpeacock/Sea-lice-database), where they will be continually updated and added to in future monitoring years. 

#### 2. Contact person

Main contact:
Alexandra Morton
Salmon Coast Field Station
General Delivery, Simoom Sound, BC, Canada V0P 1S0
Email: info@salmoncoast.org
Phone: 1 (250) 974-7177

Queries regarding accessing data via GitHub should be directed to corresponding author, Stephanie Peacock (stephanie.j.peacock@gmail.com).

#### 3. Copyright restrictions

These data are distributed under the Attribution 4.0 International (CC BY 4.0; http://creativecommons.org/licenses/by/4.0/legalcode). Users are free to share and adapt/analyse the data for any purpose, even commercially, providing there is attribution to the original data and any changes are detailed. 

#### 4. Proprietary restrictions

##### a. Release date

February 15, 2016 at https://github.com/sjpeacock/Sea-lice-database

##### b. Citation

Peacock, SJ, AW Bateman, M Krkosek, B Connors, S Rogers, L Portner, Z Polk, C Webb, and A Morton. 2016. Sea-louse parasites on juvenile wild salmon in the Broughton Archipelago, British Columbia, Canada. Available at https://github.com/sjpeacock/Sea-lice-database [Accessed dd-mm-yyyy].

##### c. Disclaimer(s)

#### 5. Costs

There are no costs associated with acquiring and using these data, but we require that users cite this data paper in any resulting publication or report, as per section 3. Copyright restrictions.

## Class IV. Data structural descriptors

### A. Data set file

#### 1. Identity

BroughtonSeaLice_siteData.csv
BroughtonSeaLice_fishData.csv

#### 2. Size (at time of initial publication in 2015)

BroughtonSeaLice_siteData.csv: 492 sites, 28 KB 
BroughtonSeaLice_fishData.csv: 31 200 fish, 2.2 MB

#### 3. Format and storage mode

The data are downloadable as two .csv files from Ecology (Wiley Online Library) or the GitHub repository cited above. The two files contain (1) details of the sampling sites and (2) the individual fish health information. 

#### 4. Header information

See B. Variable information.

#### 5. Alphanumeric attributes

Mixed upper and lowercase. See B. Variable information for further details.

#### 6. Special characters/fields

All missing data are blank fields in the .csv files. We did not distinguish instances where data were not collected from instances where a data error was found and so that entry was removed. We also do not distinguish zeroes from missing data for the louse information in the fish data. Refer to section Louse identification in 3. Research methods for details on how the classification of sea lice changed from 2001 to 2015. For example, in 2001, sea lice were not identified to species and so all recorded observations of lice are in columns unid_cope, unid_PA, unid_adult and the blanks in other columns are missing data (not recorded; Table 2). We have summarized instances of zero observations by year in Table 2, and attempted to classify these zeros as missing data (i.e., not recorded) or true zeroes based on our knowledge of the methods employed that year. 


Table 2. Summary of the number of fish examined and the total numbers of lice of each stage/species recorded, as well as the number of fish health observations of each type. Zeroes are color coded to indicate those that are likely missing data (i.e., not recorded for that year; red), true zeroes (green) and unknown (yellow).
![Table2](https://github.com/sjpeacock/Sea-lice-database/blob/master/Metadata/Figures/Table2.png)


#### 7. Authentication procedures

None.

### B. Variable information

Variable identities, descriptions, data types, the range of values, allowable values, and other information are given in the tables "fish_variableDescriptions.csv" and "site_variableDescriptions.csv".

### C. Data anomalies

See 6. Special characters/fields. We removed data that seemed impossible (e.g., body depth < 3 mm and fork lengths < 20 mm) and set those fields to blank.  This included fork length and body depth measurements that were impossible given the range of data observed (e.g., 1 mm height with a fork length of 56 mm) or errors in data entry such as characters (e.g., `, -) instead of numbers or species codes. 

The fish data include 95 observations of sockeye salmon captured between 2012 and 2015.  We did not target sockeye, with the exception of sampling on June 20, 2010, but they were included on our scientific fishing permit, and we examined them for sea lice when they were captured. The sockeye captured on June 20, 2010 were sent to DFO for genetic stock ID and found to have originated from the Nimpkish River on Vancouver Island.

## Class V: Supplemental descriptors

### A. Data acquisition

An example of the data entry form from 2014/2015 is given in Fig. 8.  This data entry form has varied over the years.

![Fig8](https://github.com/sjpeacock/Sea-lice-database/blob/master/Metadata/Figures/Fig8.png)
**Fig. 8.** Example of completed data sheet for sea louse monitoring.  Upon returning to the field station, these data sheets were scanned, and later transcribed into digital format. The cop column has L or C for Lepeoptheirus or Caligus. ChalA and ChalB columns are hash marks for the number of chalimus A and chalimus B stages (no species).  All motile lice are noted in the motile column: pre-adult Lepeoptheirus (PAL), adult Lepeoptheirus (L), gravid Lepeoptheirus (GL), Caligus (C) or gravid Caligus (GC). The notes column has codes for motile scars (MS), predation scars (PS), hemorrhaging (H), eroded gill plate (EG), blue blotches (BB), and scales (SC). Any other information, including the type of predator scar and location of hemorrhaging, is written in the Comments column.

#### 1. Data forms or acquisition methods

#### 2. Location of completed data forms

Physical raw data sheets from 2001-2009 are stored with Alexandra Morton (Raincoast Research, Malcolm Island, BC) and raw data sheets from 2010-2016 are stored at the Salmon Coast Field Station (Simoom Sound, BC).

#### 3. Data entry verification procedures

A technician entered raw data into a spreadsheet during the week following sampling. Immediately subsequent to the data entry step, each technician entering data performed a random check of several rows (salmon) to ensure that the data entered were correct and there were no mismatches with or omissions from the original data sheet (e.g. fork length and number of lice erroneously drawn from different lines in the sheet). 

When preparing this data paper, we checked that all data were consistent with credible ranges, and removed outliers (see C. Data anomalies).

### B. Quality assurance/quality control procedures

We plotted fork length vs. height and checked any obvious anomalies against the raw data sheets.  If we were unable to verify the validity of obvious data errors, we set those fields to blanks. 

### C. Related materials

Not applicable.

### D. Computer programs and data-processing algorithms

Data were entered from raw data sheets into Microsoft Excel, and exported as a .csv file. We used the open-source statistical software R (R Development Core Team 2014) when performing quality control using plots and summary statistics (see Quality assurance/quality control procedures).

### E. Archiving

#### 1. Archival procedures

These data are being submitted to the Ecology for long-term storage and access.

#### 2. Redundant archival sites

Researchers who continue to be involved in the sea louse monitoring and analyses of these data also have copies of the data set.  The data set archived with the ESA will be the most up to date and verified copy, and we encourage all users to refer to these data in future analyses.

#### F. Publications and results

The sea lice monitoring data have been used in the following publications:

1. Morton, A.B., and Williams, R. 2003. First Report of a Sea Louse, Lepeophtheirus salmonis, Infestation on Juvenile Pink Salmon, Oncorhynchus gorbuscha, in Nearshore Habitat. Can. Field-Naturalist 117: 634–641.
2. Morton, A., Routledge, R., Peet, C., and Ladwig, A. 2004. Sea lice (Lepeophtheirus salmonis) infection rates on juvenile pink (Oncorhynchus gorbuscha) and chum (Oncorhynchus keta) salmon in the nearshore marine environment of British Columbia, Canada. Can. J. Fish. Aquat. Sci. 61: 147–157. doi: 10.1139/f04-016.
3. Morton, A., Routledge, R.D., and Williams, R. 2005. Temporal Patterns of Sea Louse Infestation on Wild Pacific Salmon in Relation to the Fallowing of Atlantic Salmon Farms. North Am. J. Fish. Manag. 25: 811–821. doi: 10.1577/M04-149.1.
4. Morton, A., and Routledge, R. 2005. Mortality rates for juvenile pink (Oncorhynchus gorbuscha) and chum (O. keta) salmon infested with sea lice (Lepeophtheirus salmonis) in the Broughton Archipelago. Alaska Fish. Res. Bull. 11: 146–152. Available from http://www.adfg.alaska.gov/static-f/home/library/PDFs/afrb/mortv11n2.pdf. 
5. Morton, A., and Routledge, R. 2006. Fulton’s Condition Factor: Is It a Valid Measure of Sea Lice Impact on Juvenile Salmon? North Amer. J. Fish. Mgmt 26: 56–62. doi: 10.1577/M05-068.1. 
6. Krkosek, M., Ford, J., Morton, A., Lele, S., Myers, R.A., and Lewis, M. 2007. Declining wild salmon populations in relation to parasites from farm salmon. Science 318, 1772-1775.
7. Peacock, S.J., Krkosek, M., Proboszcz, S., Orr, C., and Lewis, M.A. 2013. Cessation of a salmon decline with control of parasites. Ecol. Appl. 23: 606–620. doi: 10.1890/12-0519.1.
8. Peacock, S.J., Connors, B.M., Krkosek, M., Irvine, J.R., and Lewis, M.A. 2014. Can reduced predation offset negative effects of sea louse parasites on chum salmon? Proc. R. Soc. B Biol. Sci. 281: 20132913. doi: 10.1098/rspb.2013.2913. 

### G. History of data set usage

#### 1. Data request history

To be updated as data requests are made. 

#### 2. Data set update history

To be updated as the data set is added to and revised. We plan to update the data set on an annual basis as long as monitoring continues. See the GitHub repository for updates and history.

March 27, 2017
* Added missing data for June 18 (Burdwood, Wicklow and Glacier) and 20 (Wicklow only) 2010 that were provided by Scott Rogers. These are labelled as site_id 313.1-313.4
* Data from June 20, 2010 are sockeye only, and were sent to the Pacific Biological Station (DFO) for genetic stock ID.  They were found to have originated from the Nimpkish River on Vancouver Island.
* Added a column named ```sockeye_examined``` to the site data, indicating the number of sockeye salmon that were sampled (if any).

#### 3. Review history

Reviewed by Stephanie Peacock on December 15, 2015.

#### 4. Questions and comments from secondary users

This section will be completed as questions are posed.



## Acknowledgements
Many individuals helped in data collection and supported those who spent countless hours in the field. In particular, we would like to thank members of the Echo Bay community including Eric Nelson, Billy Proctor, Chris and Hannah Bennett, Yvonne and Al Maximchuck, and Pierre Landry. Thanks to Glenna Garramone for meals and music and John Taylor for providing a home for sea lousers in transit.



## Literature Cited 

* Brauner, C.J., Sackville, M., Gallagher, Z., Tang, S., Nendick, L., and Farrell, A.P. 2012. Physiological consequences of the salmon louse (*Lepeophtheirus salmonis*) on juvenile pink salmon (*Oncorhynchus gorbuscha*): implications for wild salmon ecology and management, and for salmon aquaculture. Philos. Trans. R. Soc. Lond. B. Biol. Sci. 367: 1770-9. doi: 10.1098/rstb.2011.0423.
* Connors, B.M., Lagasse, C., and Dill, L.M. 2011. What's love got to do with it? Ontogenetic changes in drivers of dispersal in a marine ectoparasite. Behav. Ecol. 22: 588–593. doi: 10.1093/beheco/arr024.
* Ford, J.S.S., and Myers, R.A.A. 2008. A global assessment of salmon aquaculture impacts on wild salmonids. PLoS Biol 6: e33. doi: 10.1371/journal.pbio.0060033.
* Foreman, M.G.G., Stucchi, D.J., Zhang, Y., and Baptista, A.M. 2006. Estuarine and tidal currents in the Broughton Archipelago. Atmosphere-Ocean 44: 47–63. CMOS.
* Goldburg, R., and Naylor, R. 2005. Future Seascapes, Fishing, and Fish Farming. Front. Ecol. Environ. 3: pp. 21–28. Ecological Society of America. Available from http://www.jstor.org/stable/3868441.
* Hamre, L.A., Eichner, C., Caipang, C.M.A., Dalvin, S.T., Bron, J.E., Nilsen, F., Boxshall, G., and Skern-Mauritzen, R. 2013. The Salmon Louse *Lepeophtheirus salmonis* (Copepoda: Caligidae) Life Cycle Has Only Two Chalimus Stages. PLoS One 8: e73539. Public Library of Science. doi: 10.1371/journal.pone.0073539.
* Johnson, S., and Albright, L. 1991. The developmental stages of *Lepeophtheirus salmonis* (Krøyer, 1837)(Copepoda: Caligidae). Can. J. Zool.
* Kabata, Z. 1972. Developmental stages of *Caligus clemensi* (Copepoda: Caligidae). J. Fish. Board Canada.
* Krkosek, M., Connors, B.M., Ford, H., Peacock, S., Mages, P., Ford, J.S., Morton, A., Volpe, J.P., Hilborn, R., Dill, L.M., and Lewis, M.A. 2011a. Fish farms, parasites, and predators: implications for salmon population dynamics. Ecol. Appl. 21: 897–914. doi: 10.1890/09-1861.1.
* Krkosek, M., Connors, B.M., Morton, A., Lewis, M.A., Dill, L.M., and Hilborn, R. 2011b. Effects of parasites from salmon farms on productivity of wild salmon. Proc. Natl. Acad. Sci. 108: 14700–14704. doi: 10.1073/pnas.1101845108.
* Krkosek, M., Ford, J.S., Morton, A., Lele, S., Myers, R.A., and Lewis, M.A. 2007. Declining wild salmon populations in relation to parasites from farm salmon. Science (80-. ). 318: 1772. doi: 10.1126/science.1148744.
* Krkosek, M., Lewis, M.A., Morton, A., Frazer, L.N., and Volpe, J.P. 2006. Epizootics of wild fish induced by farm fish. Proc. Natl. Acad. Sci. 103: 15506–15510. doi: 10.1073/pnas.0603525103.
* Krkosek, M., Lewis, M.A., Volpe, J.P., and Krkosek, M. 2005a. Transmission dynamics of parasitic sea lice from farm to wild salmon. Proc. R. Soc. B 272: 689–696. doi: 10.1098/rspb.2004.3027.
* Krkosek, M., Morton, A., and Volpe, J.P. 2005b. Nonlethal assessment of juvenile pink and chum salmon for parasitic sea lice Infections and fish health. Trans. Am. Fish. Soc. 134: 711–716. doi: 10.1577/T04-133.1.
* Marty, G.D., Saksida, S.M., and Quinn, T.J. 2010. Relationship of farm salmon, sea lice, and wild salmon populations. Proc. Natl. Acad. Sci. 107: 22599–22604. doi: 10.1073/pnas.1009573108.
* Morton, A., and Routledge, R. 2005. Mortality rates for juvenile pink (*Oncorhynchus gorbuscha*) and chum (*O. keta*) salmon infested with sea lice (*Lepeophtheirus salmonis*) in the Broughton Archipelago. Alaska Fish. Res. Bull. 11: 146–152. Available from http://www.adfg.alaska.gov/static-f/home/library/PDFs/afrb/mortv11n2.pdf.
* Morton, A., and Routledge, R. 2006. Fulton's Condition Factor: Is It a Valid Measure of Sea Lice Impact on Juvenile Salmon? North Amer. J. Fish. Mgmt 26: 56–62. doi: 10.1577/M05-068.1.
* Morton, A., Routledge, R., Peet, C., and Ladwig, A. 2004. Sea lice (*Lepeophtheirus salmonis*) infection rates on juvenile pink (*Oncorhynchus gorbuscha*) and chum (*Oncorhynchus keta*) salmon in the nearshore marine environment of British Columbia, Canada. Can. J. Fish. Aquat. Sci. 61: 147–157. doi: 10.1139/f04-016.
* Morton, A., Routledge, R.D., and Williams, R. 2005. Temporal Patterns of Sea Louse Infestation on Wild Pacific Salmon in Relation to the Fallowing of Atlantic Salmon Farms. North Am. J. Fish. Manag. 25: 811–821. doi: 10.1577/M04-149.1.
* Morton, A.B., and Williams, R. 2003. First Report of a Sea Louse, *Lepeophtheirus salmonis*, Infestation on Juvenile Pink Salmon, *Oncorhynchus gorbuscha*, in Nearshore Habitat. Can. Field-Naturalist 117: 634–641.
* Murray, A.G. 2002. Using observed load distributions with a simple model to analyse the epidemiology of sea lice (*Lepeophtheirus salmonis*) on sea trout (*Salmo trutta*). Pest Manag. Sci. 58: 585–594. John Wiley and Sons, Ltd. doi: 10.1002/ps.470.
* Peacock, S.J., Connors, B.M., Krkosek, M., Irvine, J.R., and Lewis, M.A. 2014. Can reduced predation offset negative effects of sea louse parasites on chum salmon? Proc. R. Soc. B Biol. Sci. 281: 20132913. doi: 10.1098/rspb.2013.2913.
* Peacock, S.J., Krkosek, M., Proboszcz, S., Orr, C., and Lewis, M.A. 2013. Cessation of a salmon decline with control of parasites. Ecol. Appl. 23: 606–620. doi: 10.1890/12-0519.1.
* R Development Core Team. 2014. R: A Language and Environment for Statistical Computing. Vienna, Austria. http://www.r-project.org/. Available from http://www.r-project.org/.
