+++
# A Projects section created with the Portfolio widget.
widget = "portfolio"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 20  # Order that this section will appear.

title = "Research"
subtitle = ""

[content]
  # Page type to display. E.g. project.
  page_type = "research"
  
  # Filter toolbar (optional).
  # Add or remove as many filters (`[[content.filter_button]]` instances) as you like.
  # To show all items, set `tag` to "*".
  # To filter by a specific tag, set `tag` to an existing tag name.
  # To remove toolbar, delete/comment all instances of `[[content.filter_button]]` below.
  
  # Default filter index (e.g. 0 corresponds to the first `[[filter_button]]` instance below).
  filter_default = 0
  
  # [[content.filter_button]]
  #   name = "All"
  #   tag = "*"
  
  # [[content.filter_button]]
  #   name = "Deep Learning"
  #   tag = "Deep Learning"
  
  # [[content.filter_button]]
  #   name = "Other"
  #   tag = "Demo"

[design]
  # Choose how many columns the section has. Valid values: 1 or 2.
  columns = "2"

  # Toggle between the various page layout types.
  #   1 = List
  #   2 = Compact
  #   3 = Card
  #   5 = Showcase
  view = 3

  # For Showcase view, flip alternate rows?
  flip_alt_rows = false

[design.background]
  # Apply a background color, gradient, or image.
  #   Uncomment (by removing `#`) an option to apply it.
  #   Choose a light or dark text color by setting `text_color_light`.
  #   Any HTML color name or Hex value is valid.
  
  # Background color.
  # color = "navy"
  
  # Background gradient.
  # gradient_start = "DeepSkyBlue"
  # gradient_end = "SkyBlue"
  
  # Background image.
  # image = "background.jpg"  # Name of image in `static/img/`.
  # image_darken = 0.6  # Darken the image? Range 0-1 where 0 is transparent and 1 is opaque.

  # Text color (true=light or false=dark).
  # text_color_light = true  
  
[advanced]
 # Custom CSS. 
 css_style = ""
 
 # CSS class.
 css_class = ""
+++

**High frame rate CMOS image sensor**: A CMOS image sensor with column-parallel cyclic ADC is designed and fabricated in AMS 350 nm CMOS process. All the associated circuits including pixel array, ADC, vertical scanners, reference generation, clock circuitry etc are integrated on the same integrated circuit. The camera results in a frame rate of 1300 fps. The layout and the raw images captured from the designed camera are shown.
{{< figure library="true" src="Camera1.png" title="Layout of high frame rate CMOS image sensor" lightbox="true" >}}
{{< figure library="true" src="11.jpg" title="Raw images captured from my own designed high speed camera" lightbox="true" >}}

**A power efficient CMOS image sensor**: The CMOS image sensor with column-parallel hybrid ADC is designed and fabricated in AMS 350 nm CMOS process. 
{{< figure library="true" src="Camera2.png" title="Layout of low power CMOS image sensor" lightbox="true" >}}
{{< figure library="true" src="12.jpg" title="Raw images captured from my own designed power efficient camera" lightbox="true" >}}

**A two-stage cyclic ADC**: The two-stage cyclic ADC with a 2.5-bit/phase architecture is designed and fabricated in UMC 180 nm CMOS process. The pipelined operation of the two stages along with the relaxed design constraints of the second stage resulted in a competitive performance as compared to the state-of-the-art. The microchip photograph and the measured non linearities are shown.
{{< figure library="true" src="Two_stage.png" title="Microchip photograph of two-stage cyclic ADC" lightbox="true" >}}
{{< figure library="true" src="DNL_INL_2stage.png" title="Measured DNL and INL" lightbox="true" >}}

**A single stage cyclic ADC**: An area efficient and low power single stage cyclic ADC using 2.5-bits in 1.5-bit framework is designed and fabricated in UMC 180 nm CMOS technology. In natural images, the neighbouring pixels contain almost similar information. Instead of reading the entire pixel values, only the difference between the pixels is read. The ADC resolves the delta difference, which reduces the number of clock cycles and hence the readout power. These ADCs are also preferred for biomedical applications.
{{< figure library="true" src="single_stage.png" title="Microchip photograph of single-stage cyclic ADC" lightbox="true" >}}
{{< figure library="true" src="DNL_INL_1stage.png" title="Measured DNL and INL" lightbox="true" >}}
{{< figure library="true" src="EEG.png" title="Measurement results" lightbox="true" >}}
**Low latency and low power comparator**: An adaptive sampling based low latency and a low power comparator is designed and fabricated in UMC 180 nm CMOS process. Circuit consumes total power of 4.289 microW while operating at the clock frequency of 20 MHz. Measurement results shows the reduction in comparator latency by 75% compared to the state of the art comparators.
{{< figure library="true" src="Microchip2.png" title="Measurement results and Microchip photograph of comparator" lightbox="true" >}}
