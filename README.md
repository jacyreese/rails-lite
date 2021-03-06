# Welcome to Rails Lite!
This is a functional, lightweight version of Rails. In the root directory, you can create new projects with `ruby new_rails_lite_project.rb` followed by the project name. This will set up a new directory in the `projects` folder with all the files you need to create a functional web application.

# Example project
There's a simple example project in the `projects` folder that stores the names of ninja turtles and their ninja masters.

# Functionality
- SQLite3 database storage
- *Very* basic migration functionality is included
  - `up` with string and integer data types
- Object relational mapping
  - Querying through Ruby (e.g. `where`, `includes`)
    - Including lazy evaluation
  - Associations (e.g. `belongs_to`, `has_many_through`)
- Session stored in cookies
  - Including `flash`/`flash.now`
- CSRF protection by default
- Integration with Webrick
