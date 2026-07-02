---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

<!-- Google tag (gtag.js) -->
<script async src="https://www.googletagmanager.com/gtag/js?id=G-VN4W0JXPV0"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());
  gtag('config', 'G-VN4W0JXPV0');
</script>

<style>
/* Journal Articles - J prefix, reverse numbering */
#journal-articles-list {
  counter-reset: journal-counter var(--journal-total, 14);
  list-style: none;
  padding-left: 0;
}
#journal-articles-list li {
  counter-increment: journal-counter -1;
  position: relative;
  padding-left: 40px;
  margin-bottom: 10px;
}
#journal-articles-list li::before {
  content: "J" counter(journal-counter) ". ";
  position: absolute;
  left: 0;
}

/* Conference Proceedings - C prefix, reverse numbering */
#conference-proceedings-list {
  counter-reset: conference-counter var(--conference-total, 14);
  list-style: none;
  padding-left: 0;
}
#conference-proceedings-list li {
  counter-increment: conference-counter -1;
  position: relative;
  padding-left: 40px;
  margin-bottom: 10px;
}
#conference-proceedings-list li::before {
  content: "C" counter(conference-counter) ". ";
  position: absolute;
  left: 0;
}

/* Technical Reports - R prefix, reverse numbering */
#technical-reports-list {
  counter-reset: reports-counter var(--reports-total, 17);
  list-style: none;
  padding-left: 0;
}
#technical-reports-list li {
  counter-increment: reports-counter -1;
  position: relative;
  padding-left: 40px;
  margin-bottom: 10px;
}
#technical-reports-list li::before {
  content: "R" counter(reports-counter) ". ";
  position: absolute;
  left: 0;
}
</style>

Over <span id="publication-count">40</span> publications establishing methodological foundations and quantifying hazards-related risk across the energy, water, and food sectors.  (<a href="https://scholar.google.com/citations?user=dOzcnYUAAAAJ&hl=en&oi=ao" style="color: blue">Google Scholar Page</a>)

<div style="text-align: center; margin: 20px 0; padding: 15px; background-color: #f5f5f5; border-radius: 5px;">
  <a href="#journal-articles" style="color: #0066cc; text-decoration: none; font-weight: bold; margin: 0 15px;">Journal Articles</a> | 
  <a href="#conference-proceedings" style="color: #0066cc; text-decoration: none; font-weight: bold; margin: 0 15px;">Conference Proceedings</a> | 
  <a href="#technical-reports" style="color: #0066cc; text-decoration: none; font-weight: bold; margin: 0 15px;">Technical Reports &amp; White Papers</a>
</div>

For publications without an open-access link, please feel free to contact me if you need a copy or author-accepted version where available. 

## <a id="journal-articles"></a>Journal Articles

<ol id="journal-articles-list">

  <li> K.L. Bonney, T. Gunda, S.B. Ferencz, and <b>N.D. Jackson</b>. (2026) <a href="https://doi.org/10.1088/2515-7620/ae4cf9" style="color: black">Emulation of Monthly Water Allocations Using LSTM Models: A Case Study of the Colorado River Basin in Texas</a>, <em>Environmental Research Communications</em>, Vol 8, Issue 5 pp 055040 <a href="https://doi.org/10.5281/zenodo.13870503"> code </a> and <a href="https://doi.org/10.57931/2441443"> data </a></li>

  <li>H.H. Bokhari, F. Corsi, A. Miara, B.M. Fekete, S. Gangrade, S. Kao, <b>N.D. Jackson</b>, and C.J. V&ouml;r&ouml;smarty. (2025) <a href="https://doi.org/10.1029/2025EF006203" style="color: black">An Integrated Hydroclimatic Assessment of Future Reservoir and Hydropower Operations in the U.S.</a>, <em>Earth's Future</em>, Vol 13, Issue 9 pp e2025EF006203 <a href="https://doi.org/10.5281/zenodo.14272679">code and data</a></li>

  <li>T. Gunda, A. Moore, <b>N.D. Jackson</b>, S. Dhulipala, and S. Awara. (2025) <a href="https://doi.org/10.1088/2753-3751/add465" style="color: black">A resource adequacy assessment of correlated wide-area outages in the power grid</a>, <em>Environmental Research: Energy</em>, Vol 2, Issue 2 pp 025009 <a href="https://doi.org/10.7799/2566792">data</a></li>

  <li>P.M. Johnson, <b>N.D. Jackson</b>, H. Baroud, and A. Staid. (2024) <a href="https://iopscience.iop.org/article/10.1088/1748-9326/ad3568" style="color: black">Can socio-economic indicators of vulnerability help predict spatial variations in the duration and severity of power outages due to tropical cyclones?</a>, <em>Environmental Research Letters</em>, Vol 19, Issue 4 pp 044048 <a href="https://doi.org/10.17605/OSF.IO/AK5J6">data</a> <a href="https://osf.io/ak5j6/?view_only=0a795a15856741dab2628c73efd52fc5">code</a></li>

  <li>K.L. Bonney, T. Gunda, M.W. Hopwood, H. Mendoza, and <b>N.D. Jackson</b>. (2023) <a href="https://joss.theoj.org/papers/10.21105/joss.05755" style="color: black">pvOps: a Python package for empirical analysis of photovoltaic field data</a>, <em>Journal of Open Source Software</em>, Vol 8, Issue 91 pp 5755</li>

  <li>S.D. Gilletly, <b>N.D. Jackson</b> and A. Staid. (2023) <a href="https://doi.org/10.1016/j.apenergy.2023.121303" style="color: black">Evaluating the impact of wildfire smoke on solar photovoltaic production</a>, <em>Applied Energy</em>, Vol 348, pp 121303 <a href="https://dx.doi.org/10.25984/1988650">data</a></li>

  <li><b>N.D. Jackson</b> and T. Gunda. (2021) <a href="https://doi.org/10.1016/j.apenergy.2021.117508" style="color: black">Evaluation of Extreme Weather Impacts on Utility-scale Photovoltaic Plant Performance in the United States</a>, <em>Applied Energy</em>, Vol 302, pp 117508 <a href="https://github.com/ndjackso/ndjackso.github.io/blob/fdf31830cb21c726a7a6f78347ef2156c6228370/files/7_Jackson_AppliedEnergy_2021.pdf">PDF</a> <a href="http://data.openei.org/submissions/4055">data</a></li>

  <li><b>N.D. Jackson</b>, M. Konar, P. Debaere, and J. Sheffield. (2021) <a href="https://doi.org/10.1088/1748-9326/abf8e0" style="color: black">Crop-specific Exposure to Extreme Temperature and Moisture for the Globe for the Last Half Century</a>, <em>Environmental Research Letters</em>, Vol 16, Issue 6, pp 064006 <a href="https://github.com/ndjackso/ndjackso.github.io/blob/a0d022667df1a8f94ce338b2a3043a9e33dfa0db/files/6_Jackson_ERL_2021.pdf">PDF</a> <a href="https://doi.org/10.13012/B2IDB-5457902_V1">data</a></li>

  <li>R. von Gnechten, J. Wang, M. Konar, K. Baylis, P. Anderson, S. Giroux, <b>N.D. Jackson</b>, and T. Evans. (2020) <a href="https://doi.org/10.1088/1748-9326/abbe44" style="color: black">A Gravity Model and Network Analysis of Household Food Sharing in Zambia</a>, <em>Environmental Research Letters</em>, Vol 15, Issue 11, pp 115010 <a href="https://github.com/ndjackso/ndjackso.github.io/blob/a0d022667df1a8f94ce338b2a3043a9e33dfa0db/files/5_von_Gnechten_ERL_2020.pdf">PDF</a></li>

  <li><b>N.D. Jackson</b>, M. Konar, P. Debaere, and L. Estes. (2019) <a href="https://iopscience.iop.org/article/10.1088/1748-9326/ab3b93" style="color: black">Probabilistic Global Maps of Crop-Specific Areas from 1961 to 2014</a>, <em>Environmental Research Letters</em>, Vol 14, Issue 9, pp 094023 <a href="https://github.com/ndjackso/ndjackso.github.io/blob/a0d022667df1a8f94ce338b2a3043a9e33dfa0db/files/4_Jackson_ERL_2019.pdf">PDF</a> <a href="https://doi.org/10.13012/B2IDB-7439710_V1">data</a></li>

  <li>M. Niazi, C. Nietch, M. Maghrebi, <b>N.D. Jackson</b>, B.R. Bennett, M. Tryby, and A. Massoudieh. (2017) <a href="http://dx.doi.org/10.1061/JSWBAY.0000817#sthash.RYvwX1S8.dpuf" style="color: black">Storm Water Management Model: Performance Review and Gap Analysis</a>, <em>Journal of Sustainable Water in the Built Environment</em>, Vol 3, Issue 2, pp 04017002 <a href="https://github.com/ndjackso/ndjackso.github.io/blob/a0d022667df1a8f94ce338b2a3043a9e33dfa0db/files/3_Niazi_JSWBE_2017.pdf">PDF</a></li>

  <li><b>N.D. Jackson</b>, M. Konar, and A.Y. Hoekstra. (2015) <a href="http://www.mdpi.com/2071-1050/7/6/6435" style="color: black">The Water Footprint of Food Aid</a>, <em>Sustainability</em>, Vol 7, Issue 6, pp 6435-6456 <a href="https://github.com/ndjackso/ndjackso.github.io/blob/a0d022667df1a8f94ce338b2a3043a9e33dfa0db/files/2_Jackson_Sustainability_2015.pdf">PDF</a></li>

  <li>J.S. Popovics, G.P. Cetrangolo, and <b>N.D. Jackson</b>. (2006) Experimental Investigation of Impact-Echo Method for Concrete Slab Thickness Measurement, <em>Journal of the Korean Society for Nondestructive Testing</em>, Vol 26, Issue 6, pp 427-439 <a href="https://github.com/ndjackso/ndjackso.github.io/blob/a0d022667df1a8f94ce338b2a3043a9e33dfa0db/files/1_Popovics_JKSNDT_2006.pdf">PDF</a></li>

</ol>

## <a id="conference-proceedings"></a>Conference Proceedings

<ol id="conference-proceedings-list">

  <li>W.G. Chapman, J.D. Smith, C. Teeter, and <b>N.D. Jackson</b> (2026) <a href="https://doi.org/10.1109/NICE69539.2026.11567497" style="color: black">Graph Reservoir Networks for Prediction of Spatiotemporal Systems</a>, <em>Proceedings of the 2026 Neuro Inspired Computational Elements Conference</em>, Atlanta, Georgia </li>
  
  <li><b>N.D. Jackson</b>, A. Sharma, and J.K. Skolfield (2025) <a href="https://doi.org/10.1109/RWS66711.2025.11304397" style="color: black">Spatio-Temporal Modeling of Compound Threats to Power Systems Using Markov Random Fields</a>, <em>2025 IEEE Resilience Week (RWS)</em>, National Harbor, Maryland</li>

  <li>R.M. Alfant, J.K. Skolfield, <b>N.D. Jackson</b>, and T.R. Edwards (2025) <a href="https://doi.org/10.1109/RWS66711.2025.11304451" style="color: black">Generation and Transmission Expansion Planning for Resilience to Compound Hazards</a>, <em>2025 IEEE Resilience Week (RWS)</em>, National Harbor, Maryland</li>

  <li>R.L. Valdez, T. Gunda, S.B. Ferencz, and <b>N.D. Jackson</b> (2025) <a href="https://doi.org/10.1109/RWS66711.2025.11304373" style="color: black">Integrated Metrics for System Performance, Attributes, and Critical Threats for Resilience Analysis</a>, <em>2025 IEEE Resilience Week (RWS)</em>, National Harbor, Maryland</li>

  <li>R.L. Valdez, A.G. Moore, <b>N.D. Jackson</b>, and T. Gunda (2025) <a href="https://doi.org/10.1109/RWS66711.2025.11304380" style="color: black">Evaluating Correlations between Risk Indices and Power Outages during Extreme Events</a>, <em>2025 IEEE Resilience Week (RWS)</em>, National Harbor, Maryland, National Harbor, Maryland</li>

  <li>A.G. Moore, T. Gunda, and <b>N.D. Jackson</b> (2025) <a href="https://doi.org/10.1109/RWS66711.2025.11304488" style="color: black">A Hazard-Informed Empirical Assessment of Floods and Snow Impacts to Utility-Scale Photovoltaic Systems</a>, <em>2025 IEEE Resilience Week (RWS)</em>, National Harbor, Maryland</li>

  <li>R. Piansky, D.K. Molzahn, <b>N.D. Jackson</b>, and J.K. Skolfield. (2025) <a href="https://doi.org/10.1109/PowerTech59965.2025.11180476" style="color: black">Evaluating Undergrounding Decisions for Wildfire Ignition Risk Mitigation across Multiple Hazards</a>, <em>2025 IEEE Kiel PowerTech Conference</em>, Kiel, Germany</li>

  <li>G. Zhao, X. Luo, S. Yoo, and <b>N.D. Jackson</b>. (2024) <a href="https://doi.org/10.1109/SmartGridComm60555.2024.10738070" style="color: black">GAN-based Extreme Conditional Distribution Estimation for Renewable Energy Systems</a>, <em>IEEE International Conference on Communications, Control, and Computing Technologies for Smart Grids (SmartGridComm)</em>, Oslo, Norway</li>

  <li>R.M. Reck, Y. Li, S. Thompson, <b>N.D. Jackson</b>, and S. Debetwar. (2023) <a href="https://peer.asee.org/preparing-women-in-stem-for-faculty-careers-through-a-job-search-workshop-series.pdf" style="color: black">Preparing Women in STEM for Faculty Careers through a Job Search Workshop Series</a>, <em>ASEE Annual Conference &amp; Exposition, Conference Proceedings</em>, Baltimore, Maryland</li>

  <li>S. Gilletly, <b>N.D. Jackson</b>, and A. Staid. (2021) <a href="https://doi.org/10.1109/PVSC43889.2021.9518514" style="color: black">Quantifying Wildfire-Induced Impacts to Photovoltaic Energy Production in the Western United States</a>, <em>48th IEEE Photovoltaic Specialists (PVSC)</em>, virtual</li>

  <li><b>N.D. Jackson</b>, K.I. Tyler, Y. Li, W. Chen, C. Liu and R. Bhargava. (2017) <a href="https://peer.asee.org/28598" style="color: black">Keeping Current: An Update on the Structure and Evaluation of a Program for Graduate Women Interested in Engineering Academia</a>, <em>ASEE Annual Conference &amp; Exposition, Conference Proceedings</em>, Dayton, Ohio</li>

  <li>K.I. Tyler, Y. Li, <b>N.D. Jackson</b>, W. Chen, C. Liu and R. Bhargava. (2017) <a href="https://peer.asee.org/28727" style="color: black">Overcoming Difficulties in Research Statement Preparation for the Academic Job Search: Expansion of a Peer-Focused Professional Development Program</a>, <em>ASEE Annual Conference &amp; Exposition, Conference Proceedings</em>, Dayton, Ohio</li>

  <li><b>N. Jackson</b>, Y. Malave, C.L. Roberts-Wollmann, S. Case, and J. Lesko. (2005) Reliability-based Uniform Flexural Resistance Factors for GFRP Reinforced Concrete Members, <em>Third International Conference for Composites in Construction</em>, Lyon, France</li>

</ol>

## <a id="technical-reports"></a>National Laboratory Reports and White Papers

<em>Note: National laboratory documents are subject to internal peer review before publication. Entries without links remain distribution-limited and are available only for official use.</em>

<ol id="technical-reports-list">

  <li><b>N.D. Jackson</b>, M. Brown, and N.S. Rao. (2025) <a href="https://ewr.openei.org/submissions/55" style="color:black">Reinforcement Learning for Water-Energy Infrastructure Resilience and Evolution</a>, SAND2025-13783O</li>

  <li><b>N.D. Jackson</b>, S. Conrad, and N.S. Rao. (2025) <a href="https://ewr.openei.org/submissions/54" style="color: black"> Operational Flexibility for Integrated Energy-Water Resilience</a>, SAND2025-13749O</li>

  <li>P. Bhowmik, K. Cafferty, K. Klise, J.K. Skolfield, and <b>N.D. Jackson</b>. (2025) <a href="https://ewr.openei.org/submissions/42" style="color: black">Water Energy Planning Strategies to Meet Emerging Load from Data Centers</a>, SAND2025-13692O</li>

  <li>R.L. Valdez, <b>N.D. Jackson</b>, S. Ferencz, and A. Wachtel. (2025) <a href="https://ewr.openei.org/submissions/68" style="color: black">Resilience by Design: Advanced Metrics and Comprehensive Methods for Energy-Water Systems Analysis</a>, SAND2025-13704O</li>

  <li>T. Gunda, <b>N.D. Jackson</b>, Z. Kilwein, K. Klise, and J.K. Skolfield. (2025) Opportunities to Address Gaps in Atmospheric Phenomena for Energy Operations and Planning, SAND2025-13655O</li>

  <li>J.K. Skolfield, T. Gunda, and <b>N.D. Jackson</b>. (2025) Flexible and Module Superstructure Optimization for Rapid Computational Advancements in Power Systems Expansion Planning, Sandia National Laboratories</li>

  <li>T. Gunda, R. Valdez, <b>N. Jackson</b>, R. Cooper, A. Sorensen, and E. Sproul. (2024) Historical and Future Extreme Weather Conditions: A Case Study of Southeast China Provinces, Sandia National Laboratories, SAND2024-15880</li>

  <li>T. Gunda, R. Valdez, <b>N. Jackson</b>, S. Price, and S. Goodnight. (2024) Potential Climate Change Impacts to Crop Production: Case Study of Rice and Winter Wheat in China, Sandia National Laboratories</li>

  <li>A. Walker, J. Desai, T. Gunda, and <b>N. Jackson</b>. (2023) <a href="https://www.nrel.gov/docs/fy24osti/85819.pdf" style="color: black">Operation and Maintenance of PV Systems: Data Science, Analysis, and Standards</a>, National Renewable Energy Laboratory, NREL/TP-5C00-85819</li>

  <li>T. Lowry, R. Garrett, T. Gunda, <b>N. Jackson</b>, K. Klise, C. Smallwood, K. Stamber, R. Taylor, S. Kuzio, and J. Zimmerman. (2023) Climate Impacts on National Critical Infrastructure Strategic Initiative: A White Paper, Sandia National Laboratories</li>

  <li><b>N. Jackson</b>, T. Gunda, N. Gayoso, J. Desai, and A. Walker. (2022) <a href="https://www.osti.gov/servlets/purl/1899420" style="color: black">Operations, maintenance, and cost considerations for PV+ Storage in the United States</a>, Sandia National Laboratories, SAND2022-16312</li>

  <li>A. Nelson, <b>N. Jackson</b>, J. Wingard, S. Paik, and T. Gunda. (2022) Resilience of Global Chemical Facilities to Climate Change, Sandia National Laboratories, SAND2022-14347R</li>

  <li><b>N. Jackson</b> and H. Mendoza. (2022) Predictive Modeling of Weather Impacts on Utility-scale Photovoltaic Systems, Sandia National Laboratories, SAND2022-14215R</li>

  <li>A. Staid, E.S. Fleming, T. Gunda, and <b>N.D. Jackson</b>. (2021) <a href="https://www.osti.gov/servlets/purl/1820518" style="color: black">Critical Infrastructure Decision-Making Under Long-Term Climate Hazard Uncertainty: The Need for an Integrated, Multidisciplinary Approach</a>, Sandia National Laboratories, SAND2021-11394R</li>

  <li>T. Gunda, <b>N.D. Jackson</b>, D. Sanchez, K. Klise, K. Ruehl, and S. Kuzio. (2021) Advanced Data Analytics in Renewable Energy: Review of Capabilities, Needs, and Opportunities, Sandia National Laboratories, SAND2021-6297R</li>

  <li>T. Gunda, A. Neal, P. Carlson, C. Richardson, J.A. Perez, M. Aamir, B. Anderson, and <b>N.D. Jackson</b>. (2020) TAOS: A Tool for Assisting Organization Selections for Security Integrated Assessments, Sandia National Laboratories, SAND2020-10751</li>

</ol>

<script>
function updatePublicationCount() {
  const journalCount = document.querySelectorAll('#journal-articles-list li').length;
  const conferenceCount = document.querySelectorAll('#conference-proceedings-list li').length;
  const reportsCount = document.querySelectorAll('#technical-reports-list li').length;
  const totalCount = journalCount + conferenceCount + reportsCount;

  // Update total count display
  const countEl = document.getElementById('publication-count');
  if (countEl) countEl.textContent = totalCount;

  // Set CSS custom properties for reverse numbering
  // IMPORTANT: set to the actual number of items (not +1) to avoid J0/C0 and negatives
  document.documentElement.style.setProperty('--journal-total', journalCount);
  document.documentElement.style.setProperty('--conference-total', conferenceCount);
  document.documentElement.style.setProperty('--reports-total', reportsCount);
}

document.addEventListener('DOMContentLoaded', updatePublicationCount);
</script>
