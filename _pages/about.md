---
permalink: /
title: "Physical Climate Risk · Extreme Weather · Infrastructure Resilience"
excerpt: "Quantifying how extreme weather disrupts critical infrastructure, and translating physical climate risk into decision-ready models."
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

*Quantifying how extreme weather disrupts critical infrastructure, and translating physical climate risk into decision-ready models.*

I am a Principal Member of the Technical Staff at [Sandia National Laboratories](https://www.sandia.gov), working at the intersection of extreme weather, physical climate risk, and critical infrastructure. I quantify how extreme events (e.g., hurricanes, wildfires, drought, heat, flooding, and compound hazards) disrupt energy, water, and agricultural systems. I build models that help planners, operators, asset owners, and risk decision-makers prepare for those risks.



### What I Do:
- Quantify extreme weather impacts on utility-scale solar, power systems, and water infrastructure
- Apply extreme value theory, spatiotemporal statistical modeling, and interpretable machine learning to gridded climate and operational data
- Develop reservoir computing methods for sub-seasonal drought forecasting
- Lead multi-institution projects across government, industry, and academic partners
- Translate hazard and climate data into planning, operations, resilience, and risk-management decisions
- Mentor postdocs, graduate students, and undergraduates in hazard modeling and climate risk analysis

### Research Impact & Recognition:
- 44 peer-reviewed publications, including 11 first-authored papers, across the energy, water, and food sectors
- $3.9M in directly managed research funding
- Patent pending on Graph Reservoir Networks
- Best Paper Award, 2025 IEEE Resilience Week
- Member of the National Academies committee on [Attribution of Extreme Weather and Climate Events and their Impacts](https://www.nationalacademies.org/our-work/attribution-of-extreme-weather-and-climate-events-and-their-impacts)
- Associate Editor, [Earth's Future](https://agupubs.onlinelibrary.wiley.com/journal/23284277) journal

### Research Applications:
*Physical climate risk* | *Extreme value theory* | *Catastrophe risk analytics* | *Extreme weather impacts* | *Infrastructure resilience* | *Grid and energy resilience* | *Water systems* | *Sub-seasonal prediction* | *Decision-relevant risk modeling*

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
        console.log('Could not fetch publication count, keeping default of 40');
    }
}

// Run when page loads
document.addEventListener('DOMContentLoaded', updateHomepagePublicationCount);
</script>
