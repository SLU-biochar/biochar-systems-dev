---
title: "Biochar Stability Dashboard"
description: "
<p>
<b>Part 1 / 3   -   Exploring the data</b>
<p/>
<p>
This first dashboard allows to explore the biochar incubation data and the associated metadata, which were collected from the litterature and compiled in a single consistent format. The result of many hours of work.
</p>

"
bg_image: "/img/lin-field.JPG"
draft: false

type : dashboard
layout : dashbord

menu:
  main:
    parent: "More"
    name: "Biochar stability dashboard"
    weight: 2

# Page-specific JavaScript & CSS, from static folder #ESA
js : ["bokehapp/bokeh-2.4.3.min", "bokehapp/bokeh-widgets-2.4.3.min", "bokehapp/bokeh-tables-2.4.3.min", "bokehapp/bokeh-gl-2.4.3.min", "bokehapp/bokeh-mathjax-2.4.3.min", ]
css : ["bokehapp/bokehapp-custom"]

---
<div class="col-md-12">
{{% notice warning %}}
Dashboard under construction 
{{% /notice %}}
</div>

<!-- MAIN DASHBOARD -->
<section class="">
  <div class="">
 
<div class="row">
  <div class="col-md-9 col-md-push-1">

## **First Bokeh Component in Hugo**
  
  </div>
</div>

<div class="row">
<div id="component_1" style="height:90vh; width:90vh; margin-left:10vh; margin-right:10vh;" >
    <div class="bk-root" id="f5d8847a-02e6-4871-8b84-ffbd20996cc3" data-root-id="907123"></div>    <br />
</div>
</div>

</div>
</section>

<!-- DATA DOWNLOAD  -->
<section class="section-sm section-dark">
<div class="container">
<div class="row">
  <div class="col-md-9 col-md-push-1">

## **Download all the data**

All the data shown above (and the code to deal with it) is available for download in various format:
* Get it from *GitHub* (data + code)
* Get it in *.xlsx* format (data only)
* Get it in *.json* format (data only)

## **Scroll down for more**

Below, more interactive figures and text analyses are provided. They reproduce the results from our pre-print article published here *insert link*.

  </div>
</div>
</div>
</section>

<!-- FURTHER FIGURES -->
<section class="">
<div class="container">

<div class="row">
  <div class="col-md-9 col-md-push-0">

## **Biomass types**

  </div>
</div>

<div class="row">
<div class="col-md-7">
<div id="component_2" style="height:90vh;" >
    <div class="bk-root" id="6316b263-df3d-4f12-816e-5e4f22ec1399" data-root-id="881578"></div>    <br />
</div>
</div>

<div class="col-md-5">
<div id="component_text_2>

## **TEXT FOR FIGURE 2**

</div>
</div>
</div>

</div>
</section>


<section>
</section>

<div id="bokeh_component_scripts">
<script type="text/javascript" src="../component_2.js"></script>
<script type="text/javascript" src="../component_1.js"></script>
</div>