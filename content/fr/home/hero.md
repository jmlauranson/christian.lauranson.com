+++
# Hero widget.
widget = "hero"  # See https://wowchemy.com/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 10  # Order that this section will appear.

title = "Christian Lauranson-Rosaz"

# Hero image (optional). Enter filename of an image in the `static/media/` folder.
hero_media = "clr-photo.jpg"

[design.background]
  # Apply a background color, gradient, or image.
  #   Uncomment (by removing `#`) an option to apply it.
  #   Choose a light or dark text color by setting `text_color_light`.
  #   Any HTML color name or Hex value is valid.

  # Background color.
  # color = "white"
  
  # Background gradient.
  gradient_start = "RoyalBlue"
  gradient_end = "#000"
  
  # Background image.
  #image = "clr-photo.jpg"  # Name of image in `static/media/`.
  image_darken = 0.7  # Darken the image? Range 0-1 where 0 is transparent and 1 is opaque.
  image_size = "cover"  #  Options are `cover` (default), `contain`, or `actual` size.
  image_position = "center"  # Options include `left`, `center` (default), or `right`.
  image_parallax = true  # Use a fun parallax-like fixed background effect? true/false
  
  # Text color (true=light or false=dark).
  text_color_light = true

# Call to action links (optional).
#   Display link(s) by specifying a URL and label below. Icon is optional for `[cta]`.
#   Remove a link/note by deleting a cta/note block.
# Note. An optional note to show underneath the links. 

+++ 

## 1952-2016

### Historien du Haut Moyen Age

{{< icon name="info" pack="fas" >}}  {{< staticref "/#about">}}Biographie{{< /staticref >}}

{{< icon name="road" pack="fas" >}}  {{< staticref "/#experience">}}Parcours{{< /staticref >}}

{{< icon name="search" pack="fas" >}}  {{< staticref "/#tags">}}Thématiques{{< /staticref >}}

{{< icon name="book" pack="fas" >}}  {{< staticref "/#publications">}}Publications{{< /staticref >}}

{{< icon name="paper-plane" pack="fas" >}}  {{< staticref "/#contact">}}Contact{{< /staticref >}}
