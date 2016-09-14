# Resources

#CSS
 * Grids
  * Masonry http://www.erikjohanssonphoto.com/
  * Masonry 2 http://desandro.com/
  * Column Layout http://www.w3schools.com/css/css3_multiple_columns.asp
  * http://elementqueries.com/ greater trigger ability than media queries
  * Box Shadow technique https://css-tricks.com/snippets/css/css-box-shadow/
  * Pretty awesome blog theme / cms

#Cool People 
 * David DeSandro -> Codepen/Pinterest dude
 * Eric Thomas -> Motivational Speaker 
 * Haseeb Qureshi -> Air b n b altruist dude ex pro poker player, really cool software engineering guy
 * Les Twins -> phenomenal dancers

#FrameWorks
 * Laravel
  * Plugins
   * Image Manipulator http://image.intervention.io/
  
 * Vue.js
  * Laracasts https://laracasts.com/series/learning-vue-step-by-step/episodes/1
  * Api docs https://vuejs.org/api/
  
#Methodologies
 * Bem focuses on frontend reusability http://getbem.com/introduction/

#Podcasts
 * Coding blocks -> 12 factor app http://www.codingblocks.net/  Lotta .net web stuff 
 * Software engineering daily -> http://softwareengineeringdaily.com/  "1% better with every podcast"

#Tools
 * Awesome form building site, probably best used with devs https://www.typeform.com/
 * Color chooser http://www.palettable.io/FCFEDE
 
#Javascript
 * Codepen of ES6 Features http://codepen.io/collection/XRRLQO/

#Front End Sites
 * http://pttrns.com/
 * http://www.useronboard.com/
 * http://tympanus.net/codrops/

#Deploying Laravel Apps
 * Step 1 Clone repository.  Step 2 Setup webserber to point at public dir.  Step 3 make sure all extensions are installed on linux/windows are enabled.  Step 4 run composer install Step 5 do a touch database/database.sqlite if using sqlite.  Step 6 php artisan migrate.  Step 7 give correct perms to the database stuff.  ex. sudo chmod 755 -R laravel_blog 
 * chmod -R o+w laravel_blog/storage
 * .dlls are only for windows(duh) uncommenting them does nothing for linux environments
 * If anything goes wrong can do a composer dump -autoload
 * Make sure to give o+r priveleges  http://stackoverflow.com/questions/31543175/getting-a-500-internal-server-error-on-laravel-5-ubuntu-14-04
