---
permalink: /research/
title: "Research"
author_profile: true
redirect_from: 
  - /research.html
---


 
## Publications

* **Portfolio-wide optimization of pharmaceutical R&D activities using mathematical programming**  
**H. Wang**,  S.  Viswanath,  S.  Guntz,  J.  Dieringer,  S.  Vaidyaraman,  and  C.  E.  Gounaris  
<span style="color:maroon"> *INFORMS Journal on Applied Analytics*</span>, 2021  
– <a href="#/" onclick="visib('IJAA21')">Abstract</a> \| [Published Version](https://pubsonline.informs.org/doi/abs/10.1287/inte.2021.1074)  

<div id="IJAA21" style="display: none; text-align: justify; line-height: 1.2; border: 1px solid black; margin-left: 8%; margin-right: 0; padding: 10px; font-style: italic;" ><small>
<b>Abstract:</b> The research and development (R&D) management in any major research pharmaceutical company is constantly faced with the need to make complicated activity scheduling and resource allocation decisions, as they carry out scientific work to develop new therapeutic products. This paper describes how we develop a decision support tool that allows practitioners to determine portfolio-wide optimal schedules in a systematic, quantitative, and largely automated fashion. Our tool is based on a novel mixed-integer linear optimization model that extends archetypal multimode resource-constrained project scheduling models in order to accommodate multiple rich features that are pertinent to the Chemistry, Manufacturing, and Controls (CMC) activities carried out within the pharmaceutical R&D setting. The tool addresses this problem at the operational level, determining schedules that are optimal in light of chosen business objectives under activity sequencing, resource availability, and deadline constraints. Applying the tool on current workload data demonstrates its tractability for practical adoption. We further illustrate how, by utilizing the tool under different input instances, one may conduct various tactical analyses to assess the system’s ability to cope with sudden changes or react to shifting management priorities.
</small></div>



* **An ontology to describe small molecule pharmaceutical product development and methodology for optimal activity scheduling**  
S. Viswanath, S. Guntz, J. Dieringer, S. Vaidyaraman, **H. Wang**, and C. E. Gounaris  
<span style="color:maroon"> *Journal of Pharmaceutical Innovation*</span>, pages 1–15, 2020  
– <a href="#/" onclick="visib('JPI20')">Abstract</a> \| [Published Version](https://link.springer.com/article/10.1007/s12247-020-09505-6)  

<div id="JPI20" style="display: none; text-align: justify; line-height: 1.2; border: 1px solid black; margin-left: 8%; margin-right: 0; padding: 10px; font-style: italic;" ><small>
<b>Purpose:</b>  
This contribution is the first example of a small molecule pharmaceutical product development ontology. This ontology allows the portfolio-wide visualization of the small molecule pharmaceutical development business as a network of decisions and activities. This ontology was built not only to digitalize, rapidly access, and gain insights from prior decision-making but also to deliver input data for dynamic resource allocation via optimal scheduling of research activities subject to resource, cost, and time constraints.  

<b>Methods:</b>  
This ontology can be understood as a generic wiring diagram for small molecule product development which outlines the predecessors and successors of activities and decisions, along with needed or allowed overlap between activities. Each activity has multiple modes with direct dollars, resource consumption, and time taken to complete each mode.

<b>Results:</b>  
This generic wiring diagram was instanced for 17 portfolio assets by creating 32 specific scenarios. These scenarios were stored in an ontology as instances and served as foundational digitalized data for a host of future applications. These specific scenarios across the multiple assets served as input to the optimal resource allocation model.

<b>Conclusion:</b>  
In summary, this work describing pharmaceutical Chemistry Manufacturing and Controls (CMC) development activities and decisions is a foundational transformative project that enables full digitization of pharmaceutical CMC data, not only for optimal scheduling but also to generate heuristics on selection of research activities given development risks, a topic which has received virtually no mention in literature.

</small></div>


* **Multi-mode resource constrained project scheduling with alternative prerequisites: New models and computational studies**  
**H. Wang**,  N.  H.  Lappas,  and  C.  E.  Gounaris  
<span style="color:maroon"> *Industrial& Engineering Chemistry Research*</span>, 58(39):18253–18266, 2019  
– <a href="#/" onclick="visib('IECR19')">Abstract</a> \| [Published Version](https://pubs.acs.org/doi/abs/10.1021/acs.iecr.9b02455)  

<div id="IECR19" style="display: none; text-align: justify; line-height: 1.2; border: 1px solid black; margin-left: 8%; margin-right: 0; padding: 10px; font-style: italic;" ><small>
<b>Abstract:</b> We study the multi-mode resource constrained project scheduling problem (MRCPSP), which we generalize to account for the case of alternative prerequisite activities (MRCPSP-AP). The MRCPSP-AP arises in many real-world applications when two or more activities can serve as the required precursor to some subsequent activity, and it aims to determine not only the optimal schedule but also the optimal activity network. We propose a total of seven discrete-time models and compare their numerical tractability through comprehensive computational studies on literature benchmarks. We also extend the well-known critical path method to handle the existence of alternative prerequisites, allowing us to precalculate tight time windows for each activity. Our computational study reveals that a formulation implementing the generalized precedence relationships in a time-aggregated fashion dominates the rest, in terms of solution quality and runtime.
</small></div>


* **Integrated framework for designing spatially explicit biofuel supply chains**  
R. T. Ng, D. Kurniawan, **H. Wang**, B. Mariska, W. Wu, and C. T. Maravelias  
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
