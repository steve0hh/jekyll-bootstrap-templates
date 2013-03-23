#Steve's Jekyll marketing site template


#How to use

##_layouts

There are 2 different kinds of layouts for this project

### default

This is the default layout for the whole site.

### defaultwform

This layout compromises of the default layout with a form attached to the content page.


##_includes

###Gallery

Add the following in your YML Front maker

    gallery_images :
    - url: http://bartleyridgecondos.com/img/Bartley_Ridge_Slider_01.jpg
    - url: http://bartleyridgecondos.com/img/Bartley_Ridge_Slider_05.jpg

Then type

    {% include gallery %}

in the place you want the gallery to be.


##TODOs

- include images for `README.md`
- thumbnail includes
- find a better workaround for #awip in default layout
