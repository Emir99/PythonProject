# Puppie adoption REST-Api
This is a REST API build with Flask.
Its about adding new puppies to the system and owners than you can attach a puppy to an owner.
For Db it uses SqLite. 

# Tools, and dependencies

-All tools are in the frozen-requirements.txt

# Database

-SqlLite
-Method
  flask migrate.

# Endpoints

-In the root is the welcome page.

-For Puppies

`http://127.0.0.1:5000/puppies/list` (GET) a list of all puppies and their owners.

`http://127.0.0.1:5000/puppies/add` (POST) add a new puppy.

`http://127.0.0.1:5000/puppies/delete` (DELETE) to delete a puppy.

-For Owners

`http://127.0.0.1:5000/owners/add` (POST) add a new owner and attach him to a puppy.




