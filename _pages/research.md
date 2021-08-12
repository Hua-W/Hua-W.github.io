---
permalink: /research/
title: "Research"
author_profile: true
redirect_from: 
  - /research.html
---


 
## Publications

* **Integrated framework for designing spatially explicit biofuel supply chains**  
R. T. Ng, D. Kurniawan, **H. Wang**, B. Mariska, W. Wu, and C. T. Maravelias.  
<span style="color:maroon"> *Applied Energy*</span>, 216:116–131,2018  
– <a href="#/" onclick="visib('ae2018')">Abstract</a> \| [Published Version](https://www.sciencedirect.com/science/article/pii/S0306261918302022)  

<div id="ae2018" style="display: none; text-align: justify; line-height: 1.2; border: 1px solid black; margin-left: 8%; margin-right: 0; padding: 10px; font-style: italic;" ><small>
<b>Abstract:</b> We present a framework that allows us to utilize high-resolution spatial data to design biomass-to-fuel supply chains. Specifically, we first present how to extract crop data from the Agricultural Model Intercomparison and Improvement Project packages, and then develop a method to combine these data with a historical cropland data layer, to generate spatial data with user-specified resolution. Next, we develop a general approach to determine the potential depot and biorefinery locations, and calculate the actual flow path distance between facilities using Geographic Information Systems methods. Since spatially explicit data lead to large-scale supply chain networks, we develop preprocessing algorithms that allow us to remove arcs that will never be used in an optimal solution, thereby reducing the size of the network under consideration. We then present a multi-period mixed-integer linear programming model that accounts for the selection of depot and biorefinery locations and their capacities, shipping and inventory planning, as well as the selection of pretreatment and conversion technologies, and transportation modes. Finally, we demonstrate the application of our framework using a case study of corn stover-to-ethanol supply chain in Wisconsin.
</small></div>




[//]: This java script is the button to show abstract
<script>
 function visib(id) {
  var x = document.getElementById(id);
  if (x.style.display === "block") {
    x.style.display = "none";
  } else {
    x.style.display = "block";
  }
}
</script>

[//]:&emsp;<button onclick="visib('polariz')" class="btn btn--inverse btn--small">Abstract</button>
