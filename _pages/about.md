---
permalink: /
title: "Infrastructure Risk & Resilience Expert"
excerpt: "Advancing understanding of climate impacts on critical infrastructure"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<!-- Google tag (gtag.js) -->
<script async src="https://www.googletagmanager.com/gtag/js?id=G-VN4W0JXPV0"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());

  gtag('config', 'G-VN4W0JXPV0');
</script>

*Advancing understanding of climate impacts on critical infrastructure through rigorous research and industry partnerships*

I develop analytical frameworks that help organizations and decision makers understand infrastructure risks in our changing climate. As Principal Member of Technical Staff at [Sandia National Laboratories](https://www.sandia.gov), I manage $3.9M in direct research funding to create methodologies that bridge academic research with real-world applications across energy, water, and food sectors.

### What I Do:
- **Risk Assessment Research**: Develop probabilistic models that advance understanding of how extreme weather affects critical infrastructure
- **Industry Partnerships**: Work with energy companies under confidentiality agreements to validate research against operational realities
- **Methodological Innovation**: Create analytical frameworks that establish new quantitative approaches for conducting climate risk assessments
- **Research Leadership**: Principal Investigator managing research projects that connect government, industry, and academic stakeholders

### Research Impact & Recognition:
- $3.9M in direct research funding management as Principal Investigator
- Co-investigator on $15.7M+ in multi-institution research projects
- <span id="homepage-pub-count">29</span> publications establishing methodological foundations and quantifying hazards-related risk across the energy, water, and food sectors
- Associate Editor, [Earth's Future](https://agupubs.onlinelibrary.wiley.com/journal/23284277) journal
- Member of the National Academies committee on [Attribution of Extreme Weather and Climate Events and their Impacts](https://www.nationalacademies.org/our-work/attribution-of-extreme-weather-and-climate-events-and-their-impacts)

### Research Applications:
*Climate Risk Assessment* | *Renewable Energy Analysis* | *Infrastructure Planning* | *Industry Data Analytics* 

<script>
async function updateHomepagePublicationCount() {
    try {
        // Fetch the publications page
        const response = await fetch('/publications/');
        const html = await response.text();
        
        // Create a temporary DOM to parse the content
        const parser = new DOMParser();
        const doc = parser.parseFromString(html, 'text/html');
        
        // Count publications in each section
        const journalCount = doc.querySelectorAll('#journal-articles-list li').length;
        const conferenceCount = doc.querySelectorAll('#conference-proceedings-list li').length;
        const reportsCount = doc.querySelectorAll('#technical-reports-list li').length;
        const totalCount = journalCount + conferenceCount + reportsCount;
        
        // Update the homepage display
        const pubElement = document.querySelector('#homepage-pub-count');
        if (pubElement && totalCount > 0) {
            pubElement.textContent = totalCount;
        }
    } catch (error) {
        console.log('Could not fetch publication count, keeping default of 29');
    }
}

// Run when page loads
document.addEventListener('DOMContentLoaded', updateHomepagePublicationCount);
</script>

<!-- COMMENTED OUT ORIGINAL CONTENT - REMOVE THESE COMMENTS AFTER CONFIRMING NEW VERSION WORKS

I am currently a staff researcher in the [Energy-Water Systems Integration](https://energy.sandia.gov/programs/energy-water/) department at within the Climate Security Center at [Sandia National Laboratories](https://www.sandia.gov/); I also completed my postdoc here. My current work focuses on hazard impacts to energy, water, and food systems. Previously, I completed my Ph.D. in civil engineering under the mentorship of [Megan Konar](http://mkonar.cee.illinois.edu/) at the University of Illinois at Urbana-Champaign. There, my work focused on understanding the interaction and response of agricultural trade to extreme weather events such as temperature extrema, heavy rain, and drought.

My overarching research goal is to advance the security, reliability, and resilience of critical infrastructure to extreme events, spanning both physical- (i.e., weather and natural hazards) and cyber-related threats. In particular, my research seeks to:

<ol>
<li> understand the context under which event events occur </li>
<li> improve the characterization of these events both historically and under future scenarios </li>
<li> quantify  impacts to critical infrastructure from hazards via integrated assessments </li> 
</ol>

To do so, my work blends data science, climate science, econometrics, and risk management to develop new analytical and systems-based approaches.

-->

