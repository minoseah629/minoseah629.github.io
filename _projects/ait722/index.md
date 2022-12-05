---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
title: "Analysis of Public Safety and Funding"
permalink: /
---

# Introduction

This page is to provide the motivations behind this project's application.  With the political climate around crime, racial discrepancies, policing, and gun violence, this project provided me some direction to explore this topic in detail.  

To explore this topic, I picked the New York City Police Department (NYPD)  and their crime statistics.  I picked New York City and their Police because the largest populated city with diverse population and has a well organized Police.  As with any major urban metropolitan police department, the NYPD provides two applications that provide crime statistics.  

[NYPD CompStat2.0][NYPD CompStat2.0] and [NYC Crime Map][NYC Crime Map]  

<div class="row">
    <div class="col-md-6">
        <img src="/projects/AIT722/img_0374.png" title="NYPD CompStat2.0 mobile view" width=300 height=200>
    </div>
    <div class="col-md-6">
        <iframe id="NYC-Crime-Map-iframe"
            title="NYC Crime Map"
            width="300"
            height="200"
            src="https://maps.nyc.gov/crime/">
        </iframe>
    </div>
</div>

I acknowledge that these applications are sufficient for public use, but these applications are lacking capability.

* Using historical data beyond 2021.
* Police precincts may provide some information to user, but a common user might prefer to see zip code over precincts.  

New York City provides public access to various data.  [NYPD Complaint Data Historic][NYPD Complaint Data Historic] 

The application provides the user to explore the data from both zip code and precinct

<div id="navigationSide">
    <a disabled > -> Introduction</a>
    <br>
    <a href="/projects/ait722/Current_Events">Current Events</a>
    <br>  
    <a href="/projects/ait722/application/">NYC Community Application</a>
    <br>
    <a href="/projects/ait722/application/analysis">Data Analysis</a>
</div>
<div id="referenceLinks">
    <h2>Reference Links</h2>
    <ol>
        <li>
            <a href="https://maps.nyc.gov/crime/">NYC Crime Map</a>
        </li>
        <li>
            <a href="https://opendata.cityofnewyork.us">NYC Open Data</a>
        </li>
        <li>
            <a href="https://compstat.nypdonline.org/">NYPD CompStat 2.0</a>
        </li>
        <li>
            <a href="https://data.cityofnewyork.us/Public-Safety/NYPD-Complaint-Data-Historic/qgea-i56i">NYPD Complaint Data Historic</a>
        </li>
    </ol>
</div>

<script>
    $(document).ready(() => {
        var toc = $("#navigationSide");
        if (toc != null)
        {
            var nav = $("div.col-md-2");
            toc.prependTo(nav);
        }

        var ref = $("#referenceLinks");
        if (ref != null)
        {
            var nav = $("div.col-md-2");
            ref.appendTo(nav);
        }        
        return;
    });

</script>

[Current Events]: /projects/ait722/Current_Events
[NYPD CompStat2.0]: https://compstat.nypdonline.org/
[NYC Crime Map]: https://maps.nyc.gov/crime/
[NYPD Complaint Data Historic]: https://data.cityofnewyork.us/Public-Safety/NYPD-Complaint-Data-Historic/qgea-i56i