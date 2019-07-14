# Introduction / business problem

Today, more than 55% of human beings are leaving in an urban area. Based on current predictions, by 2050 about 64% of the developing world and 86% of the developed world will be urbanized. 

Environmental issues are crucial in cities. Indeed, population well-being depends on the quality of their environment. 
The urban environment is subject to many pollutions and has few natural and environmental benefits. As a result, the well-being produced by the environment varies greatly from one neighbourhood to another in the same city.

For example, if you live near a park, you might have better air quality during the year and freshness in summer.
Some indicators, publications and articles evaluate the quality of a district according to different criteria. Usually, it does not take the quality of the environment into account. However, highlighting this quality might be a way to reveal a “green district value” in property transaction. Revealing this type a value is a way to internalize the environmental externality and develop investments in this business.

To this end, we will create an indicator of « environmental well-being » to help people who are looking for housing to evaluate their district. This indicator will aggregate information find on Foursquare and other sources of geographical data.
People seem to be more and more concerned about environment but I think they do not consider it when looking for housing because they lack of information. Creating an indicator will facilitate awareness about the importance of this criterion.

## The measurement will be made according to two criteria:

**Avoidance of pollution:** Major forms of pollution include air pollution, light pollution, littering, noise pollution, plastic pollution, soil contamination, radioactive contamination, thermal pollution, visual pollution and water pollution.

**Access to environmental facilities:** Green areas, squares areas, Water facilities, number of trees (tree planting is one strategy that city planners can use to mitigate heat and air pollution).

*We will apply this analysis to the city of Paris.* Some work already showed that Paris is not one of the greenest city in the world even if the municipality try to improve it. Only 4 out of 10 Parisians have an access to a green area while green areas are considered an important criterion for housing for 85% of people. 

# Data 

## Details of the analysed elements:

Some of the pollutions and facilities described above are not relevant in the city of Paris. Some others might not be measurable with available datas. 
We will not take into account types of pollution that are not relevant at the neighborhood scale: 
- Light pollution which is a global city issue ; 
- Visual pollution which depends on the viewpoint ; 
- Plastic pollution, a global and very local issue but akin to littering in this context ; 
- Littering : Depends on the practices of the passersby and the inhabitants more than on the environment.
- Thermal pollution (elevation of water temperature) for which there is no data ;
- Soil contamination which is not relevant in a mostly urban ground ;
- Water pollution : The quality of water is controlled to respect the legislation. However, water pollution can come from private equipment (lead pipe). It would be more relevant to measure the quality of water at the taps of the apartment.

## Available data includes :

- Air pollution : Airparif
- Noise pollution : BruitParif mais il faut convertir les données
- Radioactive pollution : Base de mesure de la radiation OpenRadiation (+ explication concernant l’intérêt :Sites radioactifs de Paris + paragraphe sur le radon dont le niveau est faible sur tout Paris (avec explication))


- Green areas : surface d'espaces verts rapportée à la surface totale du quartier et rapportée à la population
- Squares areas : surface de square rapportée à la surface totale du quartier et rapporté à la population
- Number of trees : densité d’arbre
- Water facilities : nombre de fontaines et jets d'eaux


