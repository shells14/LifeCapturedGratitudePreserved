---
layout: page    # Use your page layout (usually default or page)
title: "About the Project"
permalink: /about-project/   # URL path for this page
page-class: about-project
about_project: true #. chnaging logo for only one page
---

<!--# About the Project (alraedy used) -->

This website is a collaborative effort, inviting people featured in the photos to reflect on the meaning associated with the images, or offer internal insight into that moment. Their reflections appear alongside mine, offering a layered perspective of a single moment. 

> My aim for this project is that even in a large-scale global archive, each photograph still functions as part of an individual story. While photos may appear visually similar, each one carries a unique emotional and narrative weight. This helps us see the differences in lived experiences as part of a multi-narrative archive, rather than a single, uniform one. 

<!--![Project Image](/assets/images/mariasunset.JPG) -->
<!--![Project Image]({{ site.baseurl }}/assets/images/morningSunrise.jpeg) -->

![Project Image]({{ '/assets/images/morningSunrise.jpeg' | relative_url }})

## Flipbook Gallery
<iframe src="{{ site.baseurl }}/assets/pdf/gallery.pdf"
        width="100%" height="600px" style="border:none;">
</iframe>

***

## Proper Flipbook Gallery

<!--<div id="flipbookViewer" style="width: 100%; height: 600px;"></div>

<script>
  FlowPaperViewer(
    "flipbookViewer",
    {
      config: {
        //DOC: "{{ site.baseurl }}/assets/pdf/gallery2.pdf",
        DOC: "/affiliates-jekyll-theme-master/assets/pdf/gallery2.pdf",
        Scale: 1.0,
        ZoomTransition: 'ease',
        ZoomTime: 0.5,
        ZoomInterval: 0.1,
        FitPageOnLoad: true,
        FitWidthOnLoad: false,
        FullScreenAsMaxWindow: false,
        ProgressiveLoading: true,
        MinZoomSize: 0.2,
        MaxZoomSize: 5,
        SearchMatchAll: false,
        InitViewMode: 'Portrait',
        RenderingOrder: 'html5',
        ViewModeToolsVisible: true,
        ZoomToolsVisible: true,
        NavToolsVisible: true,
        CursorToolsVisible: true,
        SearchToolsVisible: true
      }
    }
  );
</script> -->

## Proper Flipbook Gallery

<div id="flipbookViewer" style="width: 100%; height: 600px;"></div>

{% raw %}
<script>
  FlowPaperViewer(
    "flipbookViewer",
    {
      config: {
        DOC: "{{ '/assets/pdf/gallery2.pdf' | relative_url }}",
        Scale: 1.0,
        ZoomTransition: 'ease',
        ZoomTime: 0.5,
        ZoomInterval: 0.1,
        FitPageOnLoad: true,
        FitWidthOnLoad: false,
        FullScreenAsMaxWindow: false,
        ProgressiveLoading: true,
        MinZoomSize: 0.2,
        MaxZoomSize: 5,
        SearchMatchAll: false,
        InitViewMode: 'Portrait',
        RenderingOrder: 'html5',
        ViewModeToolsVisible: true,
        ZoomToolsVisible: true,
        NavToolsVisible: true,
        CursorToolsVisible: true,
        SearchToolsVisible: true
      }
    }
  );
</script>
{% endraw %}



Inspired by readings in my Culture and Technology Studies summer workshop course (CTS3030), I attempt to show how photographs work as tools for memory-making and shaping reality—and how history is framed differently depending on how both the individual and the photographer view what’s valuable in a moment. 

> Participant reflections are submitted through digital forms or in-person interviews. Text is only edited for grammar, and permission is always asked before posting names or images. 

This project tends to take on a positive framing, with the **goal of helping people foster appreciation for life by remembering good things or lessons taken from a moment—even in difficult or trying seasons.** However, asking people to reframe their memories might not fully capture the complexity of their experiences. So, their first reflection on the memory is posted as-is, followed by any lessons or insights they chose to share in response to the final reflective prompt. 


<div style="text-align: center; margin-top: 20px;">
  <a href="{{ site.baseurl }}/assets/pdf/gallery.pdf" download class="btn-custom-download">
    Download Project Documentation PDF
  </a>
</div>

<!--learned that Every page/post needs YAML front matter at the top to tell Jekyll how to process it.-->


<!--TO DO:
-add image gallery here: https://biati-digital.github.io/glightbox/
-write up emmas interview
-fix web image size
-text? add my reflections
-host website-->

