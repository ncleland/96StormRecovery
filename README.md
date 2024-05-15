{
 "cells": [
  {
   "cell_type": "markdown",
   "id": "abfe0293-604f-4377-a882-aa1c12c8e74c",
   "metadata": {},
   "source": [
    "# Recovery of Landslide Intiation \n",
    "## Franki Phelan and Nicole Cleland\n",
    "### Summary\n",
    "The goal of the project is to evaluate how intense rainfall and root stability variance affects landslide susceptibility and hollow/deposit vegetation recovery.\n",
    "\n",
    "### Questions and Objectives\n",
    "How do logging practices affect landscape stability during significant storm events? What impact does the regrowth stage have in a clear-cut area on the likelihood of a landslide and the post-storm NDVI recovery? Which factor has a more significant effect: saturation or logging intensity (root stability)?\n",
    "\n",
    "### Datasets\n",
    "- forest_stand_age\n",
    "- hollow_initiation_sites\n",
    "- soil_degree_of_saturation\n",
    "- colluvium_fans\n",
    "\n",
    "### Python packages\n",
    "- api: landsatxplore\n",
    "- matplotlib\n",
    "- json\n",
    "- rasterio\n",
    "- folium\n",
    "- geopandas\n",
    "- numpy\n",
    "- os\n",
    "- shapely.geometry\n",
    "\n",
    "### Methods\n",
    "Render shapefiles of hollows and colluvium fans\n",
    "Render tif of degree of saturation\n",
    "Render shapefiles of forest stand age\n",
    "Calculate NDVI before storm, directly after, and present from Landsat imagery\n",
    "\n",
    "Compare the influence of saturation vs root stability. Compare vegetation recovery in hollows and deposits.\n",
    "\n",
    "### Expected Outcomes\n",
    "We hypothesize that areas with equal saturation will have lower failure rates in old-growth areas than recently clearcut areas. We also predict that colluvium fans will have greater vegetation recovery than hollows due to slope and infilling rates. \n",
    "\n",
    "### References/Resources\n",
    "https://www.researchgate.net/publication/251511871_Shallow_landsliding_root_reinforcement_and_the_spatial_distribution_of_trees_in_the_Oregon_Coast_Range\n",
    "\n",
    "https://agupubs.onlinelibrary.wiley.com/doi/10.1029/2002WR001595\n",
    "\n",
    "https://www.sciencedirect.com/science/article/pii/S0169555X21003974#:~:text=The%20NDVI%20ratio%20rapidly%20increases,effects%20of%20grass%20vegetation%20recovery.\n",
    "\n",
    "https://www.fs.usda.gov/pnw/pubs/journals/pnw_2000_johnson001.pdf"
   ]
  }
 ],
 "metadata": {
  "kernelspec": {
   "display_name": "Python 3 (ipykernel)",
   "language": "python",
   "name": "python3"
  },
  "language_info": {
   "codemirror_mode": {
    "name": "ipython",
    "version": 3
   },
   "file_extension": ".py",
   "mimetype": "text/x-python",
   "name": "python",
   "nbconvert_exporter": "python",
   "pygments_lexer": "ipython3",
   "version": "3.11.7"
  }
 },
 "nbformat": 4,
 "nbformat_minor": 5
}
