This module will allow users to register an account for multiple stores, which will have validation on a per-store basis
instead of a per-site basis which Drupal currently is.

This allows for the following:

A Commerce site has Store A, Store B, Store C. These are all seperate stores and they aren't aware each other actually exist.

User Foobar signs up for Store A using username as ```foobar```, email as ```foobar@example.com``` and password as ```foo123```.

Now they also want to signup for an account at Store B, which they find exists - which will be a very confusing usecase for end users as well as Store Administrators - what if the Store A wants to see only their users, they shouldn't be able to see Store B's users as well.

This is what this module will solve.