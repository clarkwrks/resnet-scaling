---
weight: 2 # the order to render
name: "case_study" # must be unique within section and not include special characters
visible: true # whether to include this panel in the output, useful for testing
title: "Case study"
layout: "panel_float_card" # template to use
opacity: 1 # lower values show more of the underlying map
width: 40 # translates to % of browser window
align: "left" # align the entire panel
# background_media : "images/BackgroundTitleSlide1.jpg"  # background image rendered behind the panel, covering map
# splash: true # display the title and subtitle above the panel
layers: "google_satellite,pollinationsupplydemandmismatch,mrc_vr_border" # basemap and overlaying layers
zoom: 11
lat: 45.6
lng:  -73.5
---
### Case study

{{< figure src="images/fig1.png" title="The three types of mismatches" class="w-100 p-3">}}
<!--- Make image larger, possibly lightbox --->

We'll explore some examples of when demand and supply don't line up using the ecosystem service of pollination as an example. This mismatch 
can happen in three main ways:

<!-- #45.582, -73.315

1) **Spatial mismatch**: If we look at different landscapes, even when there's the same amount of space for pollinators, some farmlands may have 
more pollinators simply because their crops are closer to nesting sites. The location and the configuration of nesting sites can influence the 
availability of pollinators inside fields. For example, studies in crop fields show that the abundance of pollinators tends to be higher in 
smaller crop fields (e.g. 2 ha) than in large ones (e.g. 100 ha). If crop fields' edges have suitable places for pollinators to nest, then 
pollinators will find it easier to fly to the center of the field and pollinate smaller fields compared to larger fields. The plants in the 
center of a large field might be out of reach for some pollinators, given their limited flying range.

2) **Temporal mismatch**: Not all pollinators are active at the same time nor during all seasons of crop blooming. Crops may bloom at times that 
do not always coincide with all insects’s periods of high activity. As the climate changes, the periods of time when crops bloom and the periods 
of time when bees have high activity may no longer align, which may result in greater temporal mismatches.

3) **Scale mismatch**: The entire process of pollination needs a specific size and arrangement of the land. One farmer might not have enough land to 
establish a nice hedgerow or a flower strip to support the pollinators, or arrange it in the best way for them. But if many farmers work together, 
they might be able to create the right conditions for pollinators. This means that encouraging cooperation between farmers might be more successful 
than asking one farmer to increase bee-friendly habitats. This is because the size of a single farm might be too small to match the large-scale needs 
of the pollination process, and this is an example of scale mismatch.
-->

1. **Spatial mismatch**: Let's think of bees, as an example of pollinators. Bees fly from their nests to flowering crops, which are a good source of pollen or nectar. In the process of feeding, bees pollinate crops by transporting pollen among flowers. In this example, bees can be regarded as the "supply" of pollination, whereas the crops that are pollinated represent the "demand" for pollination. Empirical studies in crop fields show that the abundance of pollinators tends to be higher in smaller crop fields (e.g., 2 ha) than in large ones (e.g., 100 ha). Why is that? One explanation is that if bees' nesting habitat is located relatively close to crop fields (including plants located in the center of the field), then they will find it easier to fly and pollinate all plants present in the field. In that case, there is a spatial match between the supply of pollination (bees) and the demand (crops). Now imagine a very large crop, where plants located in the middle of the field are far from bees' nesting habitat, so far that bees won't fly there. In that case, there is a spatial mismatch between pollination supply and demand.

2. **Temporal mismatch**: Not all pollinators are active at the same time nor during all seasons of crop blooming. Crops may bloom at times that do not always coincide with all pollinators’ periods of high activity. This represents a temporal mismatch between pollination supply (insect pollinators) and demand (crops). As the climate changes, the periods of time when crops bloom and the periods of time when pollinators have high activity may no longer align, which may result in greater temporal mismatches.

3. **Scale mismatch**: Now let's move from a single farm to a whole agricultural region (many farms). Securing pollination supply for the whole region implies a specific arrangement of pollinators' habitat around crop fields. For instance, one farmer might not have enough land to establish a nice hedgerow or a flower strip to support the pollinators or arrange it in the best way for them. Or maybe the farmer can create one nice habitat for bees, but if the field is too big, it might not be enough (because of the spatial mismatch!). However, if many farmers work together, they might be able to create a network of habitat with the right conditions for pollinators. This means that encouraging cooperation between farmers might be more successful than asking one farmer alone to increase pollinator-friendly habitats. In this example, the difference between one farm versus many farms represents a case of scale mismatch.


Researchers from ResNet are investigating the mismatches between supply and demand of pollination in the agricultural fields of the county of La Vallée-du-Richelieu (map at the right), and how restoration of wild-bee habitat could enhance crop pollination (Torchio et al. Submitted) <a href="../references/">[6]</a>.

<!--- Torchio, G. M.; Cimon-Morin, J.; Mendes, P.; Goyette, J-O.; Schwantes, A.M.; Arias-Patino, M.; Bennett, E.M.; Destrempes, C.; Pellerin, S.  and Poulin, M. From Marginal Croplands to Natural Habitats: A Framework for Assessing the Restoration Potential to Enhance Wild-Bee Pollination in Agricultural Landscapes. Submitted for publication. --->

{{< figure src="images/matrixForLegend.png" title="The three types of mismatches" caption="The coloring scheme above makes it easier to visualize the potential spatial matches and mismatches between pollination supply and demand, shown in the map on the right." class="mx-auto w-50 d-block" >}}

