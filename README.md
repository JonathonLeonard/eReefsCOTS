# Relationship of low-salinity plumes on crown-of-thorn starfish outbreaks
*ENVI5809 Group 1 Project*
*by Beatriz Bogliani, MD Gazi, Lachlan Perris, Jonathon Leonard*

## Project overview
The aim of this project is to track ocean current particles to and from large Crown-of-Thorn Starfish (COTS). We track the salinity of the surface water while tracking the ocean aprticles. The aim of this is to assess the Run-Off hypothesis that suggests COTS outbreaks occur when large rainfall events such as cyclones generate an abundance of nutrients that can lead to outbreaks. This hypothesis was challenged by Clements et al, who studied COTS resistance to salinity and suggest that the low-salinity plumes that accompany large run-off events are deleterious to COTS larvae. 

Through consultation with Matthew Clements and Dr Maria Byrne, as well as our own research, we made the assumption that COTS larvae are spawned at reefs north of Cairns and take approximately 14-22 days to develop into starfish where they settle and move relatively little. Before this date, we assume that COTS lavae follow the ocean current close to the ocean surface. 

With these assumptions we analysed the salinity conditions of possible origins or large COTS outbreaks. Through statistical analysis, we identified a large COTS outbreak centred around Rib Reef and Taylor Reef WSW of Cairns in late February 2018 (20th-27th). As a proof of concept, we decided to study the possible salinity conditions of the COTS larvae that lead to the Feb 2018 outbreak. 

To understand the possible origin of the Feb 2018 COTS outbreak, we tracked ocean parcels both forward and back in time. The forward modelling starts at a broad selection of reefs North of Cairns and tracks ocean parcels starting at a series of days from Dec 2017 to early Feb 2018. We assess the start dates that lead to COTS being deposited over the Rib and Taylor Reefs, and then make an observation of the surface salinity conditions at the possible sources. For backward tracking, we start the parcel tracking at a series of days from 20th Feb to 27th Feb and track back 22 days, to see if there were any low salinity conditions North of Cairns that may have lead to the outbreak. 

## Notebook overview
This repository contains jupyter notebooks and dataset that allow the user to replicate our findings. The complete workflow is set out in **group1_envi5809.ipynb**. To run the notebook, the user requires python 3.10 and a number of libraries. The most difficult library to work with is Ocean Parcels. We suggest using setting up a virtual environment for parcels and all its dependencies (see the Ocean Parcels webpage). Keep in mind, on the M1 Macbook Pro, there were issues with the default C compiler. To get around this, before opening the notebook in terminal, we ran the command 'export CC=gcc'.

**group1_envi5809.ipynb** does a series of things including:
- Identifying COTS outbreaks from manta-tow COTS data from the Australian Institute of Marine Science (AIMS).
- Plots ocean salinity evolution from eReefs 
- Forward modelling of ocean parcels
- Backward modelling of ocean parcels

We also provide the noteboook **clements_et_al_plots.ipynb** that plots some of the COTS data from Matthew Clements et al 2022.