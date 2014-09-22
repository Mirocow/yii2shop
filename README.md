yii2shop
======

Tables
=====

* catalog (NestedSet)
  * catalog_product

Product
=====

* product
  * product_attribute
  * product_stock
  * product_file
  * product_action
  * product_order
  * product_comment
* attribute
* stock
* file (Image, Zip, Doc)
* action (begin_date, end_date)
* order

Comment
=====

* comment

User
=====

* user
  * user_role
  * user_file
* role
  * role_permission
* permission

Other
=====

* event (module, controller, action, begin_date)
* page
* config
