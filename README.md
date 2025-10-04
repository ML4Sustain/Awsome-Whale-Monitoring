# A review of deep learning techniques for monitoring cetaceans in aerial and satellite images
[Work in progress]

## Global Distribution of Cetacean Species Reported in Monitoring Studies
<figure>
  <img width="5664" height="2369" alt="distribution" src="https://github.com/user-attachments/assets/843cbca7-92c4-4077-b556-520337f40279" />
  <figcaption>Global distribution of cetacean species reported in monitoring studies, showing the spatial coverage and diversity of observed whale and dolphin populations.</figcaption>
</figure>

Among the reviewed publications, **27 studies employed deep learning approaches**, while **10 studies adopted alternative methods**. A total of **83 observation sites** covering **17 cetacean species** have been documented across existing studies.

## Methodological Approaches in Cetacean Monitoring
<figure>
  <img width="2083" height="1262" alt="image" src="https://github.com/user-attachments/assets/d5c5dacd-f7c9-4e8c-bbbb-179c99a9f514" />
  <figcaption>Sankey diagram illustrating the relationships among species, ground sampling distance (GSD), and methodological approaches employed for cetacean monitoring.</figcaption>
</figure>

## Usage of Platforms and Spectral Bands in Deep Learning Studies
<figure>
  <img width="2000" height="900" alt="cetacean_piecharts" src="https://github.com/user-attachments/assets/ea8d82ae-d9c2-47e8-a4f9-3425a166d89a" />
  <figcaption>Comparison of the platforms and spectral bands utilized in deep learning–based cetacean monitoring studies.</figcaption>
</figure>





## Literature List
| Year | Title | Geolocation | Task |
|------|-------|-------------|------|
| 2013 | [The possibility of using high resolution satellite images for detection of marine mammals](10.1134/S1062359013020106) | (72.38, -175.70) - Chukchi Sea, Russia-bowhead whale<br>(71.38, -175.70) - Chukchi Sea, Russia-beluga whale | point detection |
| 2014 | [Whales from space: counting southern right whales by satellite](10.1371/journal.pone.0088655) | (-46.82, -74.67) - Gulf of Penas, Chile - sei whale | point detection |
| 2018 | [Shark Detection from Aerial Imagery Using Region-Based CNN, a Study](http://dx.doi.org/10.1007/978-3-030-03991-2_23) | unspecified | bounding box detection |
| 2019 | [Applying deep learning to right whale photo identification](http://dx.doi.org/10.1007/s42991-022-00253-3) | unspecified | biometric estimation,<br>individual identification |
| 2019 | [Drones and convolutional neural networks facilitate automated and accurate cetacean species identification and photogrammetry](https://doi.org/10.1111/2041-210X.13246) | (34.42, -119.70) - Santa Barbara, California, USA-Blue whale<br>(36.60, -121.90) - Monterey, California, USA - Humpback whale<br>(-64.77, -64.05) - Western Antarctic Peninsula, Antarctica-Minke whale<br>(-64.77, -64.05) - Western Antarctic Peninsula, Antarctica-Humpback whale | biometric estimation |
| 2019 | [Whale counting in satellite and aerial images with deep learning](https://doi.org/10.1038/s41598-019-50795-9) | (20.64, -156.46) - Hawaii - unknown whale<br>(26.77, -113.24) - Mexico - unknown whale<br>(-42.60, -64.81) - Argentina - unknown whale<br>(-34.39, 20.88) - South Africa-unknown<br>(-14.19, 40.69) - Mozambique - unknown whale<br>(-24.62, 153.29) - Australia - unknown whale<br>(-50.50, 166.28) - New Zealand - unknown whale | bounding box detection,<br>behaviour recognition |
| 2019 | [Aerial-trained deep learning networks for surveying cetaceans from satellite imagery](https://doi.org/10.1371/journal.pone.0212532) | (20.92, -156.69) - Hawaii - Humpback whale<br>(-42.57, -64.27) - Peninsula Valdés, Argentina - Southern right whale<br>(61.50, 1.02) - Northern Europe and UK - Minke whale | image classification |
| 2019 | [Whales from space: four mysticete species described using new vhr satellite imagery](https://doi.org/10.1111/mms.12544) | (20.86, -156.68) - Au'au Channel, Hawaii, USA - Humpback whale<br>(26.82, -113.17) - Laguna San Ignacio, Mexico - Gray whale<br>(43.30, 7.50) - Pelagos Sanctuary, Ligurian Sea (France/Monaco/Italy) - Fin whale<br>(-42.50, -64.25) - Golfo Nuevo, Peninsula Valdés, Argentina - Southern right whale | point detection |
| 2019 | [Using remote sensing to detect whale strandings in remote areas: the case of sei whales mass mortality in chilean patagonia](https://doi.org/10.1371/journal.pone.0222498) | (-46.82, -74.67) - Gulf of Penas, Chile - sei whale | point detection |
| 2020 | [A comparison of baleen whale density estimates derived from overlapping satellite imagery and a shipborne survey](https://doi.org/10.1038/s41598-020-69887-y) | (-64.5,-64) - Gerlache Strait - humpback whale<br>(-62,-61) - Gerlache Strait - humpback whale | point detection |
| 2021 | [Beluga whale detection in the Cumberland Sound Bay using convolutional neural networks](https://doi.org/10.1080/07038992.2021.1901221) | (66.15, -65.71) - Clearwater Fiord, Cumberland Sound, Canada - Beluga whale | image classification |
| 2021 | [Use of satellite imagery to identify southern right whales (Eubalaena australis) on a southwest atlantic ocean breeding ground](https://doi.org/10.1111/mms.12847) | (-28.10, -48.65) - Ribanceira/Ibiraquera Bay, Brazil - Southern right whale | point detection |
| 2021 | [Mapping arctic cetaceans from space: a case study for beluga and narwhal](https://doi.org/10.1371/journal.pone.0254380) | (66.57, -67.44) - Clearwater Fiord, Baffin Island, Canada - Beluga whale<br>(72.42, -80.99) - Tremblay Sound, Baffin Island, Canada - Narwhal | point detection |
| 2022 | [Weakly Supervised Detection of Marine Animals in High Resolution Aerial Images](nan) | (45.44, -0.89) - Gironde estuary and Pertuis sea Marine Nature Park - striped dolphin<br>(45.44, -0.89) - Gironde estuary and Pertuis sea Marine Nature Park - common dolphin<br>(45.44, -0.89) - Gironde estuary and Pertuis sea Marine Nature Park - common bottlenose dolphin | bounding box detection |
| 2022 | [Whales from space dataset, an annotated satellite image dataset of whales for training machine learning models](https://doi.org/10.1038/s41597-022-01377-4) | (-42.50, -64.00) - Peninsula Valdés, Argentina - Southern right whale<br>(-34.40, 20.85) - Witsand, South Africa - Southern right whale<br>(-50.50, 166.10) - Auckland Islands, New Zealand - Southern right whale<br>(20.80, -156.33) - Maui Nui, US - Humpback whale<br>(26.80, -113.15) - Laguna San Ignacio, Mexico - Gray whale<br>(43.30, 6.70) - Pelagos Sanctuary, Ligurian Sea - Fin whale | image classification |
| 2022 | [Lords of the rings: mud ring feeding by bottlenose dolphins in a caribbean estuary revealed from sea, air, and space](https://doi.org/10.1111/mms.12854) | (18.34, -88.20) - Chetumal Corozal Bay, Mexico/Belize - Common bottlenose dolphin<br>(25.15, -80.47) - Florida Bay, USA - Common bottlenose dolphin | behaviour recognition |
| 2022 | [Satellite surveys prove a reliable monitoring method for high latitude southern right whale habitat](IWC_internal_document) | (-50.53, 166.25) - Port Ross, Auckland Islands, New Zealand - Southern right whale<br>(-50.52, 166.28) - Ewing Island, Auckland Islands, New Zealand - Southern right whale | bounding box detection |
| 2022 | [Wildlife and marine mammal spatial observatory: observation and automated detection of southern right whales in multispectral satellite imagery](https://doi.org/10.1101/2022.01.20.477141) | (-34.45, 20.55) - Agulhas ecoregion - Southern right whale | image classification |
| 2023 | [OBJECT COUNTING FROM AERIAL REMOTE SENSING IMAGES: APPLICATION TO WILDLIFE AND MARINE MAMMALS](http://dx.doi.org/10.1109/IGARSS52108.2023.10282150) | (45.44, -0.89) - Gironde estuary and Pertuis sea Marine Nature Park - striped dolphin<br>(45.44, -0.89) - Gironde estuary and Pertuis sea Marine Nature Park - common dolphin<br>(45.44, -0.89) - Gironde estuary and Pertuis sea Marine Nature Park - common bottlenose dolphin | point detection |
| 2023 | [Utility of Spectral Filtering to Improve the Reliability of Marine Fauna Detections from Drone-Based Monitoring](http://dx.doi.org/10.3390/s23229193) | (-32.17, 152.52) - Tuncurry - unknown dolphin<br>(-52.01, 153.61) - Ballina - unknown dolphin | bounding box detection |
| 2023 | [The Influence of Input Image Scale on Deep Learning‑Based Beluga Whale Detection from Aerial Remote Sensing Imagery](https://doi.org/10.1109/06088550108.2023.10084604) | (66.56, -67.44)-Cumberland Sound Bay, Nunavut, Canada-beluga whale | bounding box detection |
| 2023 | [Scaling whale monitoring using deep learning: A human-in-the-loop solution for analyzing aerial datasets](10.3389/fmars.2023.1099479) | (66.57, -67.43) - Clearwater Fjord, Cumberland Sound, Canada - Beluga whale | semantic segmentation |
| 2023 | [Gray whale detection in satellite imagery using deep learning](10.1002/rse2.352) | (27.92, -114.50) - Laguna Ojo de Liebre (West), Baja California, Mexico - Gray whale<br>(27.95, -114.38) - Laguna Ojo de Liebre (East), Baja California, Mexico - Gray whale<br>(26.80, -113.15) - Laguna San Ignacio, Baja California, Mexico - Gray whale<br>(26.77, -113.18) - Mouth of Laguna San Ignacio, Baja California, Mexico - Gray whale | bounding box detection |
| 2023 | [Deep learning based whale detection from satellite imagery](https://doi.org/10.1016/j.suscom.2023.100858) | (20.64, -156.46) - Hawaiian Islands, USA - Humpback whale<br>(28.64, 153.61) - Byron Bay, Australia - Humpback whale<br>(26.77, -113.24) - Baja California, Mexico - Humpback whale<br>(23.63, -112.55) - Sea of Cortez, Mexico - Humpback whale<br>(42.60, -64.81) - Valdes Peninsula, Argentina - Southern right whale<br>(5.95, 80.47) - Mirissa Beach, Sri Lanka - Blue whale<br>(34.39, -20.88) - Witsand, South Africa - Southern right whale<br>(-14.19, 40.69) - Memba, Mozambique - Humpback whale<br>(-50.50, 166.28) - Enderby Island, New Zealand - Right whale<br>(-35.68, -71.54) - Chile - Blue whale | bounding box detection |
| 2024 | [Advanced Remote Sensing Techniques for Underwater Fin Whale Detection in the Indian Ocean](http://dx.doi.org/10.1109/CICN.2024.221) | (-27.27, 79.60) - Indian Ocean - fin whale | bounding box detection |
| 2024 | [Automated Detection and Recognition of Wild Dolphin Behaviors Using Deep Learning](http://dx.doi.org/10.1007/978-981-97-1277-9_16) | (22.09, 113.43) - Zhuhai, China - Chinese white dolphin | bounding box detection,<br>semantic segmentation,<br>biometric estimation,<br>behaviour recognition |
| 2024 | [Relation between beluga whale aggregations and sea temperature on climate change forecasts](https://doi.org/10.3389/fmars.2024.1359429) | (73.55, -90.97) - North Elwin River, Canada - beluga whale<br>(70.43, -68.45) - Cunningham Inlet, Canada - beluga whale<br>(64.50, -165.40) - Norton Sound, USA - beluga whale<br>(59.00, 151.50) - South Okhotsk Sea, Russia - beluga whale<br>(62.00, 149.00) - North Okhotsk Sea, Russia - beluga whale<br>(58.50, -78.00) - Hudson Bay, Canada - beluga whale | image classification,<br>bounding box detection |
| 2024 | [Automated body length and body condition measurements of whales from drone videos for rapid assessment of population health](https://doi.org/10.1111/mms.13137) | (44.64, -124.05) - Oregon Coast, USA - Gray whale<br> | biometric estimation |
| 2024 | [Localization and tracking of beluga whales in aerial video using deep learning](https://doi.org/10.3389/fmars.2024.1445698) | (72.70, -94.17) - Creswell Bay, Qikiqtaaluk Region, Nunavut, Canada - Beluga whale<br><br> | bounding box detection,<br>bounding box tracking |
| 2024 | [Whale Detection Enhancement Through Synthetic Satellite Images](https://doi.org/10.23919/OCEANS52994.2023.10337400) | - | semantic segmentation |
| 2024 | [Use of satellite imagery to estimate distribution and abundance of cumberland sound beluga whales reveals frequent use of a glacial river estuary](10.3389/fmars.2023.1305536) | (66.42, -67.33) - Cumberland Sound, Canada - Beluga whale | point detection |
| 2025 | [Deep learning‑based detection and tracking of fin whales using high‑resolution space‑borne remote sensing data](https://doi.org/10.1016/j.rsase.2025.101580) | unspecified- Indian Ocean - fin whale | bounding box detection,<br>bounding box tracking |
| 2025 | [Semi-Automated Detection of Right Whales (Eubalaena spp.) in Very High-Resolution Satellite Imagery](http://dx.doi.org/10.1111/mms.70024) | (27.80, -114.23) - El Vizcaino Reserve, Mexico - Gray whale<br>(-42.50, -64.00) - Peninsula Valdés, Argentina - Southern right whale<br>(-61.58,-63.92) - Palmer Archipelago, Antarctica - unknown<br>(131.211318,-31.64) - Head of Bight, Australia - Southern right whale<br>(43.30, 6.70) - Pelagos Sanctuary, Ligurian Sea - Fin whale<br>(42.04, -70.41) - Cape Cod Bay - North Atlantic right whale<br>(50.02, -64.58) - Gulf of St. Lawrence - North Atlantic right whale<br>(-34.40, 20.85) - Witsand, South Africa - Southern right whale | image classification,<br>bounding box detection |
| 2025 | [Automated extraction of right whale morphometric data from drone aerial photographs](http://dx.doi.org/10.1002/rse2.70001) | (-31.46, 131.10) - Head of Bight - Southern right whale | biometric estimation |
| 2025 | [Beluga Whale Detection from Satellite Imagery with Point Labels](https://doi.org/10.48550/arXiv.2505.12066) | (58.79, -94.22) - Beluga whale<br>(66.56, -67.46) - Beluga whale | bounding box detection |
| 2025 | [Enhancing marine wildlife observations: the application of tethered balloon systems and advanced imaging sensors for sustainable marine energy development](http://dx.doi.org/10.1007/s00227-025-04618-3) | (36.44, 121.92) - Granite Canyon - gray whale | video classification |








## Useful Tools for Automated Annotating Whales
Promptable detection and segmentation models:
- [T-Rex](https://trexlabel.com/)

- [SAM](https://github.com/facebookresearch/segment-anything)

## Contribution
This project is still work in progress. If you are interested in contributing to this project or collaborating on wildlife detection using remote sensing techniques, please contact zhengyijie23@mails.ucas.ac.cn.

## Acknowledgement
This project is supported by [4th IEEE GRSS Studeng Grand Challenge](https://www.grss-ieee.org/community/groups-initiatives/ieee-grss-student-grand-challenge/?tab=proposals-in-the-fourth-student-grand-challenge).
