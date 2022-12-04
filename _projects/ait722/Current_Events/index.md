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

* George Floyd
* Michael Brown

Any loss of life is unfortunate, but what measures/improvements to promote public safety.  

* Improve police training 
* Reduce police funding and ask an alternative community service to response. [Mental Health Crisis Response][def]

<div id="navigationSide">    
    <a href="/">Introduction</a>
    <br>
    <a disabled> -> Current Events</a>
    <br>
    <a href=""></a>
</div>
<div id="referenceLinks">
    <h2>Reference Links</h2>    
    <a href="https://www.thecity.nyc/2022/7/18/23267193/mental-health-911-b-heard-teams">Mental Health Response Team</a>
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


[def]: https://www.thecity.nyc/2022/7/18/23267193/mental-health-911-b-heard-teams
