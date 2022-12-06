---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
title: "Analysis of Public Safety and Funding"

---
## Discussion 

From the data, NYC crime rate has an overall crime rate trending downward between 2006 to 2021. 

NYPD's budget was only reduced in 2021 by a 9% decrease.  New York City provide proposed budgets for next few years.  

With 77 police precincts operating in NYC, an equal division of NYPD budget is approximately 1.3%.  
Precincts with higher crime rate are required to respond to the increased crime thereby using more of the budget.
Overall, the police precincts' crime percentages range from 3.02 to 0.052.  
The police precincts operating budgets can be rebalanced to shift funds to precincts responding to higher crime rate. 

## Future Research 

In using the proposed budgets, future research can evaluated the relationship between police precincts and their respective budget allocation.

Current dataset could be used to support a Machine Learning predictive analysis model.

## Limitations

The NYPD budget was not broken down by Police Precinct.  Without a precincts breakdown, the analysis only provides partial insights to the effects of
decreasing budgetary fundings for the overall NYPD. 

Using QGIS on 7M records was possible with setup. Mapping crimes to one zip code was fine to create a geospatial dataset.
Migrating data back to clean file for data analysis was a problem. This likely pushed my computer to its limits.

I attempted to capture demographic data from Census, but the new data did not match up with other Census data for zip code for total population and demographic numbers or percentages.
I also tried to use percentages but got similar result where percentage was not close to 100%.

<div id="navigationSide">
    <a href="/">Introduction</a>
    <br>
    <a href="/projects/ait722/Current_Events">Current Events</a>
    <br>
    <a href="/projects/ait722/application/">NYC Community Application</a>
    <br>
    <a href="/projects/ait722/application/analysis">Data Analysis</a>
    <br>
    <a href="/projects/ait722/application/results">Results</a>
    <br>    
    <a disabled> -> Discussion</a>
</div>
<div id="referenceLinks">
    <h2>Reference Links</h2>
    <ol>        
        <li>
            <a href="https://www1.nyc.gov/assets/omb/downloads/pdf/adopt21-fp.pdf">NYC Financial Plan 2021-2025</a>
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