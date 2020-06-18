# Chantilly

Chantilly is an free and open Drupal theme from QBurst Team

* Install the **chantilly** theme and set is as default.

### Creating view modes ###

* Create new view_modes. Go to structure->display_modes->view_modes.
* Under content click on add_new_content_view_mode and name the new view_mode as Hover. (Machine name should be node.hover)
* Similarly create more view_modes with name hover-grid (Machine name: node.hover-grid) and trending (Machine name: node.trending).
* Set view to display contents and display a specific number of items set to one.

### Edit article content type ###

* Go to structure->content_types. Click on manage_fields for the article content type.
* Add a new field name by clicking on add new field and selecting text(plain). (Machine name: field_name). Set allowed number values to 1.

### Managing view modes ###

* Manage fields from the manage_display. Click on Custom Display Settings and enable full_content, hover, hover-grid, teaser and trending view modes.
* Enable the name field in all the view modes and hide all the labels by selecting the hidden option in the dropdown menu under the label column. 
* In the teaser, hover, hover-grid and trending view mode set the format of the body field as trimmed (word limit 80 for example).

### Footer menu ###

* Create a new menu. Go to structure->menu->add_menu. Name it footer-menu (Machine name: footer-menu). 
* In the newly created footer-menu click on add link. In the name field type “Facebook” and enter the appropriate link in the other fields and click on save.
* Add the footer-menu to the Footer Menu region. Go to  structure->block_layout. In the Footer Menu section click on add block and select footer_menu. On the home page, in the footer region you would see the facebook link along with the facebook logo. Similar logos for pinterest, facebook, twitter and instagram are provided.
* To change or add the logos open the drupal folder in the file manager and go to themes->blog->images. Save the logo image in this folder and rename it with the same name as the name of the link eg. in case of facebook logo “Facebook.png”.

### Footer Text Region ###

* Go to structure->block_layout->custom_block_library. Click on add custom block and name it as footertextblock and add required footer text in the body. Once the block has been created go to structure->block_layout and add the block in the Footer Text region.

### Pager ###

* Select mini pager to get the arrow as pager buttons.

Add content of article content type and create a custom view. Add blocks in the view with the custom viewing modes created earlier and place the blocks in the desired regions. 
As per the design:

* hover view mode is used in left-top, left-bottom and main-right regions.
* Trending view mode in right-top.
* Hover-grid is used in regions one-one, one-two, one-three…three-three regions.
* Teaser view mode is used in the main-left region.
