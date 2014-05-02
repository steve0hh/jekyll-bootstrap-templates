#Jekyll + twitter bootstrap combo

##Bootstrap components for Jekyll

[Twitter bootstrap](http://getbootstrap.com/) is awesome!

So is [Jekyll](http://jekyllrb.com/)!

Hence I am giving you guys my twitter bootstrap components in Jekyll! :)

##Install

Just move the components to your jekyll project respectively!

##Components & usage

###layouts

There are 2 different kinds of layouts for this project

#### default

This is the default layout for the whole site.

Preview :

![default layout preview](http://i.imgur.com/Y1psZLb.png)

#### defaultwform

This layout compromises of the default layout with a form attached to the content page.

Preview :

![default with form preview](http://i.imgur.com/GwneGnm.png)


###includes

####Gallery

Add the following in your YML Front maker

    gallery_images :
    - url: http://bartleyridgecondos.com/img/Bartley_Ridge_Slider_01.jpg
    - url: http://bartleyridgecondos.com/img/Bartley_Ridge_Slider_05.jpg

Then add the following in the place you want the gallery to be.

    {% include gallery %}

Result:

![gallery example result](http://i.imgur.com/DkgVQP9.png)


####Thumbnails

There are 3 parameters you can specifiy:

- url (Mandatory)
- label (Optional)
- caption (Optional)

To use, add the following in your YML Front maker

    thumbnail_gallery :
    - url: http://bartleyridgecondos.com/img/Bartley_Ridge_02_BedRoom.jpg
      label: testing testing
      caption: something
    - url: http://bartleyridgecondos.com/img/Bartley_Ridge_02_BedRoom.jpg
      label: testing testing
      caption: something

Then add the following in the place you want the thumbnails to be.

    {% include thumbnails %}

Result :

![thumbnails example result](http://i.imgur.com/z50FnF2.png)

####Contact cards

There are 4 parameters you can provide:

- name
- appt
- contact
- regno


To use, add the following in your YML Front maker

    contactcards:
    - name: Sean Tan
      imgurl: http://bartleyridgecondos.com/img/Sean_Pro_Photo.jpg
      appt: ERA Senior Marketing Executive
      contact: 97292925
      regno: 355656456
    - name: Sean
      imgurl: http://bartleyridgecondos.com/img/Sean_Pro_Photo.jpg
      appt: ERA Senior Marketing Executive
      contact: 97292925
      regno: 355656456

Then add the following in the place you want the contact cards to be.

    {% include contactcards %}

Result :

![contact cards result](http://i.imgur.com/yJTus8O.png)


##TODOs

- colorbox plugin
- find a better workaround for #awip in default layout
