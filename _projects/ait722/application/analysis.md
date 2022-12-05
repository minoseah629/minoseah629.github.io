---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
title: "Analysis of Public Safety and Funding"

---

## Data Analysis

Datasets 
* NYPD Complaint Data History (Reference Link 1)
* NYPD Budget (Not shown in Application)
* Census data for NYC Zip Codes

Fields
* Precinct 
* Offense (and type – misdemeanor, felony, violation)
* Demographics (Sex, Race, Age Group)
* Suspect / Victim

Tools used: 
* macOS (2 computers – 6cores, 32gb/64gb ram)
* Python
* Databricks / Apache Spark (pyspark)
* QGIS (geospatial analysis)
* Tableau (visualization)


<div id="navigationSide">
    <a href="/">Introduction</a>
    <br>
    <a href="/projects/ait722/Current_Events">Current Events</a>
    <br>
    <a href="/projects/ait722/application/">NYC Community Application</a>
    <br>
    <a disabled> -> Data Analysis</a>
</div>
<div id="referenceLinks">
    <h2>Reference Links</h2>
    <ol>        
        <li>
            <a href="https://data.cityofnewyork.us/Public-Safety/NYPD-Complaint-Data-Historic/qgea-i56i">NYPD Complaint Data Historic</a>
        </li>
        <li>
            <a href="https://ibo.nyc.ny.us/RevenueSpending/nypd.html">NYC Independent Budget Office</a>
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