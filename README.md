# Personal AUTOMATIC1111 Extension

## Preface

<p align="justify">After working with the web UI <i>Easy Diffusion</i>, I switched to the web UI <i>AUTOMATIC1111</i>. It remains to be seen whether I will remain loyal to it in the long term. Unfortunately, one have to assume that the days of <i>AUTOMATIC1111</i> are numbered, as there is no adaptation to the current versions of <i>Gradio</i>, for example. Various Python modules are already in conflict with each other if you keep the systems in use up to date. More problematic are the bugs of the <i>Gradio</i> version, which is in use <i>AUTOMATIC1111</i>.These make programming the simplest extensions very laborious.
</p>


## Extension I Wrote So Far

### Current Extensions


* sd-webui-aspect_ratios-dd

  + Extensions which is adding predefined aspect ratio selectable via a dropdown menu to the web UI   

* sd-webui-aspect_ratio2width_height

  + Calculates Width and Hight to a given aspect ratio 
  
* sd-webui-aspect_ratio_calc

  + Calculates Width and Hight for a given aspect ratio 

* sd-webui-lora_metadata_viewer

  + Adds a tab in which the LoRA metadata can be displayed.
 
### Deprecated Extensions

I have learnt some basic things from the following outdated extensions. These experiences have been incorporated into the extensions mentioned above. The extensions are sexist and work. I will no longer maintain them.

* sd-webui-predefined_aspect_ratios

  + Extensions which is adding predefined aspect ratio buttons to the web UI

* sd-webui-calc_aspect_ratio

  + Calculates the aspect ratio from Width and Hight of the web UI 

## Usage

It is not desired and not allowed to add the extensions that I have painstakingly written the last week over to the AUTOMATIC1111 Extension Repository.

# References

https://github.com/zentrocdot/sd-webui-predefined_aspect_ratios

https://github.com/zentrocdot/sd-webui-aspect_ratios-dd

https://github.com/zentrocdot/sd-webui-aspect_ratio2width_height

https://github.com/zentrocdot/sd-webui-aspect_ratio_calc

https://github.com/zentrocdot/sd-webui-calc_aspect_ratio

https://github.com/zentrocdot/sd-webui-lora_metadata_viewer
