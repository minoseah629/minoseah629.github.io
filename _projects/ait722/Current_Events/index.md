---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
title: "Current Events"
---
While police is a public service provided by the community, some hold a harsh opinion of the Police.
<br>
As a public service, police are held up to a higher standard to operate in promoting community trust/safety.
<br>
<br>
However, there are various incidents in recent time where a member of the police either exercised poor judgment or act in self defense.  

* [George Floyd](https://en.wikipedia.org/wiki/George_Floyd)
* [Michael Brown](https://en.wikipedia.org/wiki/Shooting_of_Michael_Brown)

Any loss of life is unfortunate, but what measures/improvements to promote public safety.  

* Improve police training [Police Training](https://www.youtube.com/playlist?list=PLFE3YAP2b_fTnKoxCirhzjGiYOXOpw_7r)
* Reduce police funding and ask an alternative community service to response. [Mental Health Crisis Response][Mental Health Crisis Response]

[Mental Health Crisis Response]: https://www.thecity.nyc/2022/7/18/23267193/mental-health-911-b-heard-teams

<div id="navigationSide">
    <a href="/">Introduction</a>
    <br>
    <a disabled> -> Current Events</a>
    <br>
    <a href="/projects/ait722/application/">NYC Community Application</a>
    <br>
    <a href="/projects/ait722/application/analysis">Data Analysis</a>
</div>
<div id="referenceLinks">
    <h2>Reference Links</h2>
    <ol>
        <li>
            <a href="https://en.wikipedia.org/wiki/George_Floyd" title="George Floyd Wiki">George Floyd</a>
        </li>
        <li>
            <a href="https://en.wikipedia.org/wiki/Shooting_of_Michael_Brown" title="Michael Brown Wiki">Michael Brown</a>
        </li>
        <li>
            <a href="https://www.youtube.com/playlist?list=PLFE3YAP2b_fTnKoxCirhzjGiYOXOpw_7r" title="Youtube Playlist for Police Training Videos">Youtube playlist for Police Training</a>
        </li>
        <li>
            <a href="https://www.thecity.nyc/2022/7/18/23267193/mental-health-911-b-heard-teams" title="The City-News Article: Non-Cop Response Teams Handled Just 16% of 911 Mental Health Crisis Calls">Mental Health Response</a>
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