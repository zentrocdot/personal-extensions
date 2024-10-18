# Personal AUTOMATIC1111 Extension

## Preface

<p align="justify">After working with the web UI <i>Easy Diffusion</i>, I switched to the web UI <i>AUTOMATIC1111</i>. It remains to be seen whether I will remain loyal to it in the long term. Unfortunately, one have to assume that the days of <i>AUTOMATIC1111</i> are numbered, as there is no adaptation to the current versions of <i>Gradio</i>, for example. Various <i>Python</i> modules are already in conflict with each other if you keep the systems in use up to date. More problematic are the bugs of the <i>Gradio</i> version, which is in use by <i>AUTOMATIC1111</i>. These make programming the simplest <i>Extension</i> next to other reasons very laborious.
</p>

## Extension I Wrote So Far

### Current Extensions

The following list are the <i>Extensions</i>, which I am using in my daily work:

* sd-webui-aspect_ratios-dd

  + Extensions which is adding predefined aspect ratio selectable via a dropdown menu to the web UI   

* sd-webui-aspect_ratio2width_height

  + Calculates Width and Hight from a given aspect ratio and allows taking them over to the web UI
  
* sd-webui-aspect_ratio_calc

  + Calculates the aspect ratio from given Width and Hight or from the given values by the web UI

* sd-webui-lora_metadata_viewer

  + Adds a tab in which the LoRA metadata can be displayed, downloaded and copied.
 
### Deprecated Extensions

<p align="justify">I have learnt some basic things from the following outdated extensions. These experiences have been incorporated into the extensions mentioned above. The extensions are sexist and work. I will no longer maintain them.</p>

* sd-webui-predefined_aspect_ratios

  + Extensions which is adding predefined aspect ratio buttons to the web UI

* sd-webui-calc_aspect_ratio

  + Calculates the aspect ratio from Width and Hight of the web UI 

## Usage

<p align="justify">It is not desired and not allowed to add the extensions that I have painstakingly written the last week over to the AUTOMATIC1111 Extension Repository.</p>

# References

https://github.com/zentrocdot/sd-webui-predefined_aspect_ratios

https://github.com/zentrocdot/sd-webui-aspect_ratios-dd

https://github.com/zentrocdot/sd-webui-aspect_ratio2width_height

https://github.com/zentrocdot/sd-webui-aspect_ratio_calc

https://github.com/zentrocdot/sd-webui-calc_aspect_ratio

https://github.com/zentrocdot/sd-webui-lora_metadata_viewer
