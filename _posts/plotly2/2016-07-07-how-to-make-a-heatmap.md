---
layout: excel-tutorial-single_layout
title: How to Make a Heat Map in Plotly 2.0
subtitle: A graphical representation of data where the individual values contained in a matrix are represented as colors.
permalink: /make-a-heatmap/
imageurl: ../static/images/heat-map/heat-thumb.png
state: active
tags: scientific
section: Scientific Charts
meta_description: A tutorial on how to make a heatmap in Plotly 2.0.
popularity: featured
carouselimageurl: 
actioncall: How to Make a Heatmap in Plotly 2.0

otherlang: Know how to program? See how to create this in [Python](https://plot.ly/python/heatmaps/) or [R](https://plot.ly/r/heatmaps/).

live-graph: <iframe width="900" height="800" frameborder="0" scrolling="no" src="https://plot.ly/~plotly2_demo/11.embed"></iframe>
live-graph-image:

steps: 
 - title: Try an Example
   sub-steps:
    - copy: "Heatmaps are one of the best visualization tools for dense point data."
    - copy: "After selecting 'Bar chart' under 'Chart Type', you can check out an example before adding your own data. Clicking the 'try an example' button will show what a sample chart looks like after adding data and playing with the style. You'll also see what values were selected for this specific heatmap, as well as the end result."
      img: "![Example after](../static/images/heat-map/heat-try-example.png)"

 - title: Add Your Data to Plotly
   sub-steps:
    - copy: "Head to Plotly’s new online [workspace](https://plot.ly/alpha/workspace/) and add your data. You have the option of typing directly in the grid, uploading your file, or entering a URL of an online dataset. Plotly accepts .xls, .xlsx, or .csv files. For more information on how to enter your data, see [this](http://help.plot.ly/add-data-to-the-plotly-grid/) tutorial."
      img: "![Import data main](../static/images/heat-map/heat-import-main.png)"

 - title: Create a Chart
   sub-steps:
    - copy: "After adding your own data, choose your 'Chart Type' in the GRAPH section on the left-hand side and select 'Heatmap'."
      img: "![Choose chart main](../static/images/heat-map/heat-choose-chart.png)"
    - copy: "Click on GRAPH on the left-hand side to add your axes to your heatmap. After selecting ‘Heatmap', you're then presented the z-axis, x-axis, and y-axis as shown in the figure below to create the plot."
      img: "![Adding axes](../static/images/heat-map/heat-add-axes.png)"
    - copy: "This will create a raw heatmap, as seen below."
      img: "![Raw heatmap](../static/images/heat-map/raw-heatmap.png)"

 - title: Style a Chart
   sub-steps:
    - copy: "You can choose your colourscale, text position, or typeface. Click on STYLE on the left-hand side to play around with the style of your chart."
    - copy: "To change the colour gradients of your heatmap, select ‘Traces’ under the same STYLE tab, and choose the colourscale you want."
      img: "![Colourscale](../static/images/heat-map/heat-colourscale.png)"
    - copy: "After you've chosen your colourscale, you have the option to smooth your heatmap. So far, we've had it with the 'Smoothing' option off."
      img: "![Smoothing before](../static/images/heat-map/heat-smoothing-before.png)"
    - copy: "This is when the 'Smoothing' option is selected."
      img: "![Smoothing after](../static/images/heat-map/heat-smoothing-after.png)"
    - copy: "To add a title to your plot, you can type it directly on the title by double-clicking it." 
      img: "![Type directly title](../static/images/heat-map/heat-type-title.png)" 
    - copy: "The same can be done for the axis labels and legend."
      img: "![Type directly axis](../static/images/heat-map/heat-type-axis.png)"
    - copy: "Another option is to visit the 'Traces' section under STYLE, click on 'Text' and enter your title in the box, as shown below. Note that certain typeface are available only on PRO. Click [here](https://plot.ly/products/cloud/) to upgrade!"
      img: "![Type in layout panel](../static/images/heat-map/heat-type-title-panel.png)"

 - title: Save and Share
   sub-steps:
    - copy: "Your heatmap is now done! Click SAVE on the left-hand side, and give your file a name."
      img: "![Save main](../static/images/heat-map/heat-save.png)"
    - copy: "Select your PLOT and DATA as 'Public' or 'Private'."
      img: "![Save pop-up](../static/images/heat-map/heat-save-popup.png)"
    - copy: "For more information on how to save, export, and share, visit [this](http://help.plot.ly/save-share-and-export-in-plotly/) page!"
---

