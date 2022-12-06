---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
title: "Analysis of Public Safety and Funding"

---

# NYC Community Application

<div class='tableauPlaceholder' id='viz1670220973071' style='position: relative'>
<noscript>
    <a href='#'>
        <img alt=' ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;NY&#47;NYCMapsPopulationCrime&#47;MainPage&#47;1_rss.png' style='border: none' />
    </a>
</noscript>
<object class='tableauViz'  style='display:none;'>
<param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> 
<param name='embed_code_version' value='3' /> 
<param name='site_root' value='' />
<param name='name' value='NYCMapsPopulationCrime&#47;MainPage' />
<param name='tabs' value='no' />
<param name='toolbar' value='yes' />
<param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;NY&#47;NYCMapsPopulationCrime&#47;MainPage&#47;1.png' /> 
<param name='animate_transition' value='yes' />
<param name='display_static_image' value='yes' />
<param name='display_spinner' value='yes' />
<param name='display_overlay' value='yes' />
<param name='display_count' value='yes' />
<param name='language' value='en-US' />
<param name='filter' value='publish=yes' />
</object></div>
<script type='text/javascript'>
    var divElement = document.getElementById('viz1670220973071');
    var vizElement = divElement.getElementsByTagName('object')[0];
    if (divElement.offsetWidth > 800) {
        vizElement.style.width = '800px'; 
        vizElement.style.height = '850px';
    }
    else if (divElement.offsetWidth > 500) {
        vizElement.style.width = '800px';
        vizElement.style.height = '850px';
    }
    else {
        vizElement.style.width = '100%';
        vizElement.style.height = '900px';
    }
    var scriptElement = document.createElement('script');
    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';
    vizElement.parentNode.insertBefore(scriptElement, vizElement);
</script>
<div id="navigationSide">
    <a href="/">Introduction</a>
    <br>
    <a href="/projects/ait722/Current_Events">Current Events</a>
    <br>
    <a disabled> -> NYC Community Application</a>
    <br>
    <a href="/projects/ait722/application/analysis"> Data Analysis</a>
    <br>
    <a href="/projects/ait722/application/results">Results</a>
    <br>
    <a href="/projects/ait722/application/discussion">Discussion</a>
</div>
<div id="referenceLinks">
    <h2>Reference Links</h2>
    <ol>        
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