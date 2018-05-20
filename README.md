# noob-config-reminder
reminder list for folders structure and sass/compass configuration for student web project

## sass compilation

 #### ruby installation 
    
  - http://rubyinstaller.org/ for Microsoft OS 
  - or sudo apt-get install ruby-full for Debian distrib
  - already integrated for MacOS
   
  
  #### for installing Sass and Compass open CLI and type 
     
  - gem install sass
  - gem install compass
  
 ## project configuration
 
 #### create the folder tree
  
    -assets
      -css
        -scss
         main.scss
     index.html
     
 #### generating config.rb
  
  always on CLI run 
   - compass config
   
 #### In your Vscode or ST or .... edit the config.rb file (depending on your project)
  
  ```HTML
require 'compass/import-once/activate'

http_path ="/"
css_dir   ="assets/css"
sass_dir  ="assets/css/scss"

output_style = :compressed

line_comments = false

cache = false 
 ```
   
 #### compilation initialization
 
 run on your CLI
 - compass compile
 - compass watch
 
 YOU MUST NOT CLOSE YOUR CLI WHEN WATCHING PROCESS IS RUNNING 
 
     
   
 
    





