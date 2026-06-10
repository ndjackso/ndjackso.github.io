---
permalink: /
title: "Extreme Weather · Infrastructure Resilience · Machine Learning"
excerpt: "Quantifying how extreme weather disrupts the systems we depend on and building the models to predict it."
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

*Quantifying how extreme weather disrupts the systems we depend on, and building the models to predict it.*

I am a Principal Member of the Technical Staff at [Sandia National Laboratories](https://www.sandia.gov). My research sits at the intersection of extreme weather and critical infrastructure. I quantify how extreme events (e.g., hurricanes, wildfires, droughts, and compound hazards) disrupt energy, water, and agricultural systems. I build the models that help planners and operators prepare for them.

### What I Do:
- Quantify extreme weather impacts on infrastructure using gridded climate data, station observations, and large operational datasets
- Develop machine learning and statistical methods for hazard and impact modeling, including reservoir computing for sub-seasonal drought forecasting
- Lead multi-institution research projects connecting government, industry, and academic partners
- Mentor postdocs, graduate students, and undergraduates in hazard modeling and data-driven risk analysis

### Research Impact & Recognition:
- 43 peer reviewed publications across the energy, water, and food sectors
- $3.9M in directly managed research funding
- Co-investigator on $15.7M+ in multi-institution projects
- Best Paper Award, 2025 IEEE Resilience Week
- Member of the National Academies committee on [Attribution of Extreme Weather and Climate Events and their Impacts](https://www.nationalacademies.org/our-work/attribution-of-extreme-weather-and-climate-events-and-their-impacts)
- Associate Editor, [Earth's Future](https://agupubs.onlinelibrary.wiley.com/journal/23284277) journal

### Research Applications:
*Extreme weather impacts* | *Sub-seasonal prediction* | *Renewable energy and grid resilience* | *Water management* | *Agricultural climate exposure* 

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
