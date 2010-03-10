CCK password field

Provides a password field for CCK

The field can be added like any other cck field, and can stored hashed using
md5-ed, salted (if using salt module), or plain text. Other modules
may add other methods if they so desire. 


Hooks Invoked
-------------

hook_password_methods()
  Returns a keyed array of types of password storage methods a user can store
  passwords as. For each keyed array, a title and functions can be provided.
  Functions currently only include 'presave'. Please see cck_password_methods
  for an example.

