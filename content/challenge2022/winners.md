+++
# A Demo section created with the Blank widget.
# Any elements can be added in the body: https://wowchemy.com/docs/writing-markdown-latex/
# Add more sections by duplicating this file and customizing to your requirements.

widget = "blank"  # See https://wowchemy.com/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 85  # Order that this section will appear.

title = "Winners of crossMoDA-2022 challenge "
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
  # image = "banner_website.jpg"  # Name of image in `static/media_2022/`.
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

Methods of the top-performing 2022 teams are described [here](/results_2022).

## Task 1: Segmentation
<table style="width:100%" class="table"> 
<tbody><tr class="active"> <th>#</th> 
  <th>Team Name</th> 
  <th>Affiliation</th> 
  <th>DSC</th> 
  <th>Technical report</th>
</tr> 
<tr> 
  <td>1</td> 
  <td>ne2e</td> 
  <td>Peking University, Beijing, China</td> 
  <td>86.9​ </td> 
  <td><a href="/media_2022/papers_2022/ne2e.pdf">Unsupervised Domain Adaptation in Semantic Segmentation Based on Pixel Alignment and Self-Training (PAST)</a></td> 
</tr>
<tr> 
  <td> 2 </td> 
  <td>MAI</td> 
  <td>Korea University, Korea</td> 
  <td>86.8​</td> 
  <td><a href="/media_2022/papers_2022/mai.pdf">Multi-view Cross-Modality MR Image Translation for Vestibular Schwannoma and Cochlea Segmentation
</a></td> 
</tr> 
  <tr> 
  <td> 3 </td> 
  <td>LaTIM​</td> 
  <td>Inserm, France</td>
   <td>85.9​</td>
   <td><a href="/media_2022/papers_2022/latim.pdf">Tumor blending augmentation using one-shot generative learning for vestibular schwannoma and cochlea cross-modal segmentation</a></td> 
</tr> 
</tr> 
</tbody></table>

## Task 2: Koos Classification
<table style="width:100%" class="table"> 
<tbody><tr class="active"> <th>#</th> 
  <th>Team Name</th> 
  <th>Affiliation</th> 
  <th>MA-MAE</th> 
  <th>Technical report</th>
</tr> 
<tr> 
  <td>1</td> 
  <td>SJTU_EIEE_2</td> 
  <td>Shanghai Jiao Tong University, China</td> 
  <td>0.26 </td> 
  <td><a href="/media_2022/papers_2022/SJTU_EIEE.pdf">Koos Classification of Vestibular Schwannoma via Image
Translation-Based Unsupervised Cross-Modality Domain
Adaptation</a></td> 
</tr>
<tr> 
  <td> 2 </td> 
  <td>Super Polymerization </td> 
  <td>Radboud University, the Netherlands</td> 
  <td>0.37​</td> 
  <td><a href="/media_2022/papers_2022/superpolymerization.pdf">Unsupervised Cross-Modality Domain Adaptation for Vestibular Schwannoma Segmentation and Koos Grade Prediction based on Semi-Supervised Contrastive Learning
</a></td> 
</tr> 
  <tr> 
  <td> 3 </td> 
  <td>skjp</td> 
  <td>Muroran Institute of Technology, Japan</td>
   <td>0.84​</td>
   <td><a href="/media_2022/papers_2022/skjp.pdf">Unsupervised Domain Adaptation for MRI Volume Segmentation and Classification Using Image-to-Image Translation</a></td> 
</tr> 
</tr> 
</tbody></table>



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
