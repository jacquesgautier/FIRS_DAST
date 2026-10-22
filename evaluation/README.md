# FIRS - DATA ANALYSIS AND STORYTELLING

## Evaluation - Part II

In this second part of evaluation, you will be asked to produce an analysis in order to explore a problematic on a specified dataset, and to communicate on the results using visualizations.

### Objectives

From a designated dataset, you will have to
- define a problematic analysis problem;
- propose and implement several analysis approaches, using one or several models to explore the problematic;
- propose and implement several visualizations displaying the results of your analysis;
- present the resultats of your investigation, using your visualizations, in a narrative document;
- in an text join in the annexes of this narrative document, justify why you chose the corresponding analysis approaches, visualization approaches (type of chart, visual channels, ...), and narrative tactics.

### Deadline

You will have to send us your for for the XX.

### Data and constraints

You will be assigned individually a specific dataset concerning the relationships between climate and tree mortality for a specific tree specie.
You are free to enrich your analysis by integrating any additionnal dataset you looked for.
Additionnal to this dataset, you will be provided geospatial contours (french departments and sylvoecoregions) in the following formats: geopackage, geojson, topojson (for the use of altair). 
The data are available in WGS84 and RGF93, except the data in topojson format which are only in WGS84 coordinates (being created for altair).
If you need to project dat in other coordinates systems, use [this example](https://docs.qgis.org/3.44/en/docs/training_manual/vector_analysis/reproject_transform.html#:~:text=By%20default%2C%20QGIS%20reprojects%20data%20%E2%80%9Con%20the%20fly%E2%80%9D.,button%20in%20the%20bottom%20right%20corner%20of%20QGIS) "6.1.3. Follow Along: Saving a Dataset to Another CRS".


### Expectations

We have the following expectations:
- the narrative document can be a report in a pdf format, a notebook, an infographic document, or even a webpage. 
- if the narrative document is not a notebook, we are expected to receive any scripts you used for analyzing data and creating visualizations.
- every provided script should be well commented.
- the narrative document can include some interactive functionalities to propose to the readers some controled exploration of the dataset.
- the narrative document must present the results of your investigation, demonstrating a logical progression between the various analyses applied to your dataset. The visualizations showing your results, and what can be observed within them, must be explained.
- every choice in term of analysis approach, visualization approach or narrative strcuture, has to be justified in the annexes of your narrative document. The justification has to make it clear why you choose one method instead of another, according to the data nature and structure, the question you want to explore, the component you want to highlight, what you want your end-user to understead from the data.
- you are free to use R or python scripts. You can use other languages if you feel more comfortable. You are free to use Altair or any other visualization library/package/module. You are free to use QGIS.
- the use of scripts to create visualizations, or the incorporation of interactive features, is not mandatory. However, the evaluation will look more favorably upon the use of more technical solutions, as opposed to no-code alternatives, and the inclusion of interactive elements.
- in case you use no-code solutions to create visualization, the annexes has to contain screenshots of the used solutions.
- you are free to enrich your analysis by integrating any additionnal dataset you looked for.
- any use of generative AI must be explicitly disclosed. The use of generative AI is permitted solely for the purpose of language polishing.

### Expected results

You will produce a narrative document presenting the results of your investigation in a narrative way.
In case your document is not a notebook, you will join the different scripts you use to produce analysis and visualizations.
You will join annexes justifying your choice in terms of analysis, visualization, and narrative structures.

### Datasets

#### Individual datasets

[Bessard](bessard)
[Corbeaux](corbeaux)
[Cremier](cremier)
[Debeaupuis](debeaupuis)
[Etrillard](etrillard)
[Gouget](gouget)
[Lopez](lopez)
[Maufreron](maufreron)
[Petard](petard)
[Stona](stona)
[Taisne](taisne)
[Valmenier](valmenier)

#### Common datasets: geographical contours

[Geographical contours](geographic_contours)

### Interesting ressources

#### Modules/packages to create visualizations

##### Python
https://altair-viz.github.io/
https://matplotlib.org/
https://plotly.com/python/

##### R
https://ggplot2.tidyverse.org/
https://github.com/riatelab/mapsf
https://github.com/riatelab/geovizr

#### no-code solutions to create visualizations

https://magrit.cnrs.fr/
https://www.rawgraphs.io/

## Any questions

Feel free to contact us for any questions regarding this evaluation.