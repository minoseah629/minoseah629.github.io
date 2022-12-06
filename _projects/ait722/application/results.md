---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
title: "Analysis of Public Safety and Funding"

---
## Results

Below is a group of visualizations of analysis. The tab menu provides navigation between the visualization analysis. There will be a brief description on each visualization.



<div class='tableauPlaceholder' id='viz1670289078626' style='position: relative'>
    <noscript>
        <a href='#'>
            <img alt=' ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;NY&#47;NYCPoliceBudget-2006to2021&#47;NYCPoliceBudget&#47;1_rss.png' style='border: none' />
        </a>
    </noscript>
    <object class='tableauViz'  style='display:none;'>
        <param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> 
        <param name='embed_code_version' value='3' /> 
        <param name='site_root' value='' />
        <param name='name' value='NYCPoliceBudget-2006to2021&#47;NYCPoliceBudget' />
        <param name='tabs' value='yes' /><param name='toolbar' value='yes' />
        <param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;NY&#47;NYCPoliceBudget-2006to2021&#47;NYCPoliceBudget&#47;1.png' />
        <param name='animate_transition' value='yes' />
        <param name='display_static_image' value='yes' />
        <param name='display_spinner' value='yes' />
        <param name='display_overlay' value='yes' />
        <param name='display_count' value='yes' />
        <param name='language' value='en-US' />
    </object>
</div>
<script type='text/javascript'>
    var divElement = document.getElementById('viz1670289078626');
    var vizElement = divElement.getElementsByTagName('object')[0];
    vizElement.style.width='100%';
    vizElement.style.height=(divElement.offsetWidth*0.75)+'px';
    var scriptElement = document.createElement('script');
    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';
    vizElement.parentNode.insertBefore(scriptElement, vizElement);
</script>

<div id="navigationSide">
    <a href="/">Introduction</a>
    <br>
    <a href="/projects/ait722/Current_Events">Current Events</a>
    <br>
    <a href="/projects/ait722/application/">NYC Community Application</a>
    <br>
    <a href="/projects/ait722/application/analysis">Data Analysis</a>
    <br>    
    <a disabled> -> Results</a>
    <br>
    <a href="/projects/ait722/application/discussion">Discussion</a>
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
        <li>
            <a href="https://www.investopedia.com/terms/h/hhi.asp">HHI Explanation</a>
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