+++
# A Demo section created with the Blank widget.
# Any elements can be added in the body: https://wowchemy.com/docs/writing-markdown-latex/
# Add more sections by duplicating this file and customizing to your requirements.

widget = "blank"  # See https://wowchemy.com/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 20  # Order that this section will appear.

title = "Tasks"
subtitle = ""

[design]
  # Choose how many columns the section has. Valid values: 1 or 2.
  columns = "1"

[design.background]
  # Apply a background color, gradient, or image.
  #   Uncomment (by removing `#`) an option to apply it.
  #   Choose a light or dark text color by setting `text_color_light`.
  #   Any HTML color name or Hex value is valid.

  # Background color.
  # color = "navy"
  
  # Background gradient.
  # gradient_start = "DarkGreen"
  # gradient_end = "ForestGreen"
  
  # Background image.
  # image = "banner_website.jpg"  # Name of image in `static/media/`.
  # image_darken = 0.6  # Darken the image? Range 0-1 where 0 is transparent and 1 is opaque.
  # image_size = "cover"  #  Options are `cover` (default), `contain`, or `actual` size.
  # image_position = "center"  # Options include `left`, `center` (default), or `right`.
  # image_parallax = true  # Use a fun parallax-like fixed background effect? true/false
  
  # Text color (true=light or false=dark).
  text_color_light = true

[design.spacing]
  # Customize the section spacing. Order is top, right, bottom, left.
  padding = ["30px", "30px", "30px", "30px"]

[advanced]
 # Custom CSS. 
 css_style = ""
 
 # CSS class.
 css_class = ""
+++
### Task 1: Vestibular schwannoma and cochlea segmentation

The goal of the segmentation task (**Task 1**) is to segment two key brain structures (tumour and cochlea) involved in the follow-up and treatment planning of vestibular schwannoma (VS). The segmentation of these two structures is required for radiosurgery, a standard VS treatment. Moreover, tumour volume measurement has also been shown to be the most accurate measurement for evaluating VS growth. The diagnosis and surveillance in patients with VS are commonly performed using contrast-enhanced T1 (ceT1) MR imaging. However, there is growing interest in using non-contrast imaging sequences such as high-resolution T2 (hrT2) imaging, as it mitigates the risks associated with gadolinium-containing contrast agents. Furthermore, in addition to improving patient safety, hrT2 imaging is 10 times more cost-efficient than ceT1 imaging.

For this reason, we proposed an unsupervised cross-modality segmentation benchmark (from ceT1 to hrT2) that aims to perform VS and cochlea segmentation on hrT2 scans automatically. The training source and target sets are respectively unpaired annotated ceT1 and non-annotated hrT2 scans from both pre-operative and post-operative time points. To validate the robustness of the proposed approaches on different hrT2 settings, multi-institutional scans from centres in London, UK and Tilburg, NL are used in this task.


<p style="float: left;  text-align: center; width: 48%; margin-right: 1%; margin-bottom: 0.5em;"><img src="media/T1_example.png" style="width: 100%">Source (contrast-enhanced T1)</p>
<p style="float: right;  text-align: center; width: 48%; margin-right: 1%; margin-bottom: 0.5em;"><img src="media/T2_example.png" style="width: 100%">Target (high resolution T2)</p>

### Task 2: Koos classification

The goal of the classification task (**Task 2**) is to automatically classify hrT2 images with VS according to the Koos grade. The Koos grading scale is a classification system for VS that characterises the tumour and its impact on adjacent brain structures (e.g., brain stem, cerebellum). The Koos classification is commonly determined to decide on the treatment plan (surveillance, radiosurgery, open surgery). Similarly to the VS segmentation, Koos grading is currently performed on ceT1 scans, but hrT2 could be used. For this reason, we propose an unsupervised cross-
modality classification benchmark (from ceT1 to hrT2) that aims to determine the Koos grade on hrT2 scans automatically. Only pre-operative data is used for this task. Again, multi-institutional scans from centres in London, UK and Tilburg, NL are used in this task.

<p style="float: left;  text-align: center; width: 100%; margin-right: 1%; margin-bottom: 0.5em;"><img src="media/figure1_koos-scale.svg" style="width: 100%"></p>

<!-- This challenge proposes the first medical imaging benchmark of unsupervised cross-modality Domain Adaptation approaches (from ceT1 to hrT2).   -->












<!-- The Wowchemy **Academic Resumé Template** for Hugo empowers you to create your job-winning online resumé and showcase your academic publications.

[Check out the latest demo](https://academic-demo.netlify.app) of what you'll get in less than 10 minutes, or [view the showcase](https://wowchemy.com/user-stories/).

[**Wowchemy**](https://wowchemy.com) makes it easy to create a beautiful website for free. Edit your site in Markdown, Jupyter, or RStudio (via Blogdown), generate it with Hugo, and deploy with GitHub or Netlify. Customize anything on your site with widgets, themes, and language packs.

- 👉 [**Get Started**](https://wowchemy.com/docs/install/)
- 📚 [View the **documentation**](https://wowchemy.com/docs/)
- 💬 [Chat with the **Wowchemy community**](https://discord.gg/z8wNYzb) or [**Hugo community**](https://discourse.gohugo.io)
- 🐦 Twitter: [@wowchemy](https://twitter.com/wowchemy) [@GeorgeCushen](https://twitter.com/GeorgeCushen) [#MadeWithWowchemy](https://twitter.com/search?q=(%23MadeWithWowchemy%20OR%20%23MadeWithAcademic)&src=typed_query)
- 💡 [Request a **feature** or report a **bug** for _Wowchemy_](https://github.com/wowchemy/wowchemy-hugo-modules/issues)
- ⬆️ **Updating Wowchemy?** View the [Update Guide](https://wowchemy.com/docs/update/) and [Release Notes](https://wowchemy.com/updates/)

## Crowd-funded open-source software

To help us develop this template and software sustainably under the MIT license, we ask all individuals and businesses that use it to help support its ongoing maintenance and development via sponsorship.

### [❤️ Click here to unlock rewards with sponsorship](https://wowchemy.com/plans/)

## You're looking at a Wowchemy _widget_

{{% callout note %}}
This homepage section is an example of adding [elements](https://sourcethemes.com/academic/docs/writing-markdown-latex/) to the [*Blank* widget](https://sourcethemes.com/academic/docs/widgets/).

Backgrounds can be applied to any section. Here, the *background* option is set give a *color gradient*.

**To remove this section, delete `content/home/demo.md`.**
{{% /callout %}}

## Get inspired

[Check out the Markdown files](https://github.com/wowchemy/starter-academic/tree/master/exampleSite) which power the [Academic Demo](https://academic-demo.netlify.app), or [view the showcase](https://wowchemy.com/user-stories/). -->
