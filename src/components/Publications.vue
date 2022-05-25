<script setup>
// Import AgnosticUI global common & component CSS
import "agnostic-vue/dist/common.min.css";
import "agnostic-vue/dist/index.css";
import { Disclose } from "agnostic-vue";
</script>
<template>
<ul role="list" class="link-card-list">
	<li class="link-card">
      <h2>My Publications</h2>
      <ul role="list" class="publication-list">
          <li class="publication-item">
            <p>
              <h4>A novel Internet-of-Things infrastructure to support self-healing distribution systems</h4>  
                <h6>2018 International Conference on Smart Energy Systems and Technologies (SEST)</h6>
                      <Disclose style="font-size:smaller" title="Abstract">
                    In this paper, we present a novel distributed software infrastructure to foster new services in smart grids with particular emphasis on supporting self-healing distribution systems. This infrastructure exploits the rising Internet-of-Things paradigms to build and manage an interoperable peer-to-peer network of our prototype smart meters, also presented in this paper. The proposed three-phase smart meter, called 3-SMA, is a low cost and open-source Internet-connected device that provides features for self-configuration. In addition, it selectively run on-board-algorithms for smart grid management depending on its deployment on the distribution network. Finally, we present the experimental results of Hardware-In-the-Loop simulations we performed.
                  </Disclose>
            </p>
          </li>
          <li class="publication-item">
            <p>
              <h4>Optimal configuration and placement of PV systems in building roofs with cost analysis</h4>  
                <h6>2020 IEEE 44th Annual Computers, Software, and Applications Conference (COMPSAC)</h6>
                      <Disclose style="font-size:smaller" title="Abstract">
                    Following the Smart Grid view, current energy generation systems based on fossil fuels will be replaced with renewable energy sources. Photovoltaic (PV) is currently considered the most promising technology, due to decreasing costs of the devices and to the limited invasiveness in existing infrastructures, that make PV installations quite common urban buildings' roofs. To maximise both power production and Return Of Investment (ROI) of PV installations, new techniques and methodologies should be applied to limit sources of inefficiencies, like shading and power losses due to an incorrect installation. In this paper, we propose a novel solution for an optimal configuration and placement of PV systems in buildings' roofs. Given a number of alternative configurations and a roof of interest, it combines detailed geographic and irradiance information to determine the optimal PV installation, by maximizing both power production and ROI. Our simulation results on two real-world roofs demonstrate an improvement on power generation up to 23% w.r.t. standard compact installations. These results also highlight that a cost analysis, often ignored by standard installation strategies, is nonetheless necessary to guarantee optimal results in terms of PV production and revenue.
                  </Disclose>
            </p>
          </li>
          <li class="publication-item">
            <p>
              <h4>Design of District-level Photovoltaic Installations for Optimal Power Production and Economic Benefit</h4>  
                <h6>2021 IEEE 45th Annual Computers, Software, and Applications Conference (COMPSAC)</h6>
                      <Disclose style="font-size:smaller" title="Abstract">
                    PhotoVoltaic (PV) installations are a widespread source of renewable energy, and are quite common urban buildings’ roofs. To soften both the initial investment and the recurrent maintenance costs, the current market trends delegate the construction of PV installations to Energy Aggregators, i.e., grouping of consumers and producers that act as a single entity to satisfy local energy demand and to sell the surplus energy to the grid. In this perspective, PV installations can be designed with a larger perspective, i.e., at district level, to maximize power production not of a single building but rather of a number of blocks of a city. This implies new challenges, including efficient data management (the covered area can be squared kilometers wide) and optimal PV installation (the number of PV modules can be in the order of hundreds or even thousands). This paper proposes a framework to combine detailed geographic and irradiance information to determine an optimal PV installation over a district, by maximizing both power production and economic convenience. Our simulation results run on a real-world district prove that the framework allows an advanced evaluation of costs and benefit, that can be used by Energy Aggregators to design a new PV installation, and demonstrate an improvement on power generation up to 20% w.r.t. standard installations.
                  </Disclose>
            </p>
          </li>
          <li class="publication-item">
            <p>
              <h4>A Smart Meter Infrastructure for Smart Grid IoT Applications</h4>  
                <h6>IEEE Internet of Things Journal</h6>
                      <Disclose style="font-size:smaller" title="Abstract">
                    Electric infrastructures have been pushed forward to handle tasks they were not originally designed to perform. To improve reliability and efficiency, state-of-the-art power grids include improved security, reduced peak loads, increased integration of renewable sources, and lower operational costs. In this framework“, smart grids” are built around bidirectional communication technologies, where “smart meters” communicate with all other entities and collect data from the power grid, offering specific features to each actor playing in the energy marketplace. In this paper, to overcome some of the challenges raised by smart grids and smart meters, we propose a distributed metering infrastructure which provides bidirectional communication, self-configuration, and auto-update capabilities. Our 3-phase smart meters follow the basics Internet-of-Things principles and have the ability to run, either on-board or distributed on the network, multiple algorithms for smart grid management. These algorithms can be freely added, updated, or removed on-the-fly thanks to the auto-update feature of the system. Moreover, to reduce costs and improve scalability, we prove that it is possible to implement our smart meters using only off-the-shelf and inexpensive hardware devices. A digital real-time simulator (i.e., Opal-RT) has been used to assess the capabilities of both the infrastructure and the meter. Our experimental analysis shows that the latency introduced by the data transmission over the Internet is compliant with the limits imposed by the IEC 61850 standard. As a consequence, our architecture does not affect the operational status of the smart grid, making it a viable solution to support the deployment of novel services.
                  </Disclose>
            </p>
          </li>
          <li class="publication-item">
            <p>
              <h4>Engaging Users in Resource Ecosystem Building for Local Heritage-Led Knowledge</h4>  
                <h6>Sustainability-MDPI</h6>
                      <Disclose style="font-size:smaller" title="Abstract">
                    The aim of this paper is to form an analytical and critical framework to consider the uses of digital platforms in heritage field and practices and to provide methodologies for user profiling based on the identification of local stakeholders and their needs. Within the context of the EU H2020 research project RURITAGE, a resource ecosystem (RRE) of various integrated tools was created for shaping and addressing heritage-led knowledge and bottom-up strategies of local regeneration. More specifically, the RRE was conceived to provide local stakeholders with new methodologies and user-friendly tools based on bottom-up processes for identifying and actioning heritage and territorial features and turning these cultural natural values—as well as the gaps—into opportunities. This paper undertakes a comparative analysis of the integration of tools in other digital platforms for heritage practices and/or regeneration processes to explore the holistic approach to heritage knowledge and the effectiveness in engaging local stakeholders. In addition, it frames methodologies for local stakeholder and related needs identification. Through this comparative analysis among digital heritage platforms and through user profiling to target the needs of users by using the RRE as a case study, the paper explores the challenge of helping communities to shape a local heritage-led collaborative knowledge supported by integrated and user-friendly digital tools and to activate them in preserving and exploiting their territories and building shared and plural cultural heritage understandings, considering cultural heritage as a social need.
                  </Disclose>
            </p>
          </li>
      </ul>
    </li>
	</ul>
</template>
<style>
:root {
  --color-border: #a1c8e9;
  --astro-gradient: linear-gradient(0deg, #4f39fa, #da62c4);
  --link-gradient: linear-gradient(
    45deg,
    #4f39fa,
    #da62c4 30%,
    var(--color-border) 60%
  );
  --night-sky-gradient: linear-gradient(
    0deg,
    #392362 -33%,
    #431f69 10%,
    #30216b 50%,
    #1f1638 100%
  );
  --matteo-gradient: linear-gradient(
    0deg,
    #26a1c0 0%,
    #2b9efd 33%,
    #26a1c0 66%,
    #2b9efd 99%
  );
  --bkg-gradient: linear-gradient(
    45deg,
    #26a1c0 0%,
    #a1c8e9 30%,
    var(--color-border) 60%
  );
}
h2 {
  margin: 0;
  transition: color 0.6s cubic-bezier(0.22, 1, 0.36, 1);
}
.link-card {
  margin-top: 1rem;
  margin-bottom: 1rem;
  margin-left: 0rem;
  margin-right: 0rem;
  display: block;
  padding: 1rem;
  background-image: var(--bkg-gradient);
  background-size: 400%;
  border-radius: 0.5rem;
  background-position: 100%;
  transition: background-position 0.6s cubic-bezier(0.22, 1, 0.36, 1);
}

.link-card > p {
  width: 100%;
  text-decoration: none;
  line-height: 1.4;
  padding: 1em 1.3em;
  border-radius: 0.35rem;
  color: var(--text-color);
  background-color: white;
  opacity: 0.8;
}

.link-card:is(:hover, :focus-within) {
  background-position: 0;
}

.link-card:is(:hover, :focus-within) h2 {
  color: #fff;
}

.link-card:is(:hover, :focus-within) h2 span {
  transform: translateX(2px);
}

.link-card:is(:hover, :focus-within) h2 span {
  transform: translateX(2px);
}

.publication-list {
  display: block;
}
.publication-item {
  width: 100%;
  text-decoration: none;
  line-height: 1.4;
  padding: 1em 1.3em;
  border-radius: 0.35rem;
  color: var(--text-color);
  background-color: white;
  opacity: 0.8;
  margin-top: 1rem;
}
.publication-item > h6 {
  color: grey;
}
.publication-item:is(:hover, :focus-within) h4 {
  color: #26a1c0;
}
.publication-item:is(:hover, :focus-within) h6 {
  color: #a1c8e9;
}
.publication-item:hover {
  box-shadow: 0 5px 15px rgba(0, 0, 0, 0.74);
}
Disclose {
  font-size: smaller;
}
</style>
