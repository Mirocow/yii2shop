yii2shop
======

Tables
=====

* catalog (NestedSet)
  * catalog_x_product

Product
=====

* product
  * product_x_attribute
  * product_x_stock
  * product_x_file
  * product_x_action
  * product_x_order
  * product_x_comment
  * product_x_field
  * product_x_property
* property (hit, week, day)
* attribute
 * attribute_x_field
* stock
* file (Image, Zip, Doc)
* action (begin_date, end_date)
* order

Field
=====

* field
 * field_x_type
* field_type

Comment
=====

* comment
 * comment_x_field

User
=====

* user
  * user_x_role
  * user_x_file
  * user_x_field
* role
  * role_x_permission
* permission

Other
=====

* event (module, controller, action, begin_date)
* page
* config
