# Front-End-Architecture
Front End Developement Architecture

Deployment Link Generate : https://joyalshaji135.github.io/Front-End-Clean-Architecture/build/
==> build/index.html


<h6>build</h6>
|   |
|   |_____asset
|   |         |_____style-css
|   |         |             |_____sassmain.cssmain.css
|   |         |
|   |         |_____script-js          
|   |                       |_____main.js
|   |
|   |_____font-lib
|   |            |_____lib-1
|   |            |_____lib-2
|   |            |_____lib-3
|   |            |_____lib-n
|   |
|   |_____image-path
|   |              |_____image-use-1
|   |              |_____image-use-2
|   |              |_____image-use-3
|   |              |_____image-use-n
|   |
|   |_____mobile-image-type
|   |                     |_____m-image-type-1
|   |                     |_____m-image-type-2
|   |                     |_____m-image-type-3
|   |                     |_____m-image-type-n
|   |
|   |_____script-lib
|   |              |_____library-1.js
|   |              |_____library-2.js
|   |              |_____library-3.js
|   |              |_____library-n.js
|   |
|   |_____style-lib
|   |             |_____library-1.css
|   |             |_____library-2.css
|   |             |_____library-3.css
|   |             |_____library-n.css
|   |
|   |_____video-path
|   |              |_____video-1
|   |              |_____video-2 
|   |              |_____video-3
|   |              |_____video-n
|   |
|   |_____index.html
|   |
|   |_____page-1.html
|   |
|   |_____page-2.html
|   |
|   |_____page-3.html
|   |
|   |_____page-n.html
|   |
|   |
<h6>source</h6>
    |
    |_____scripts
    |           |_____vendors
    |           |            |_____vendor-1.js
    |           |            |_____vendor-2.js
    |           |            |_____vendor-3.js
    |           |            |_____vendor-n.js
    |           |
    |           |_____javascriptmain.js
    |
    |_____styles
               |_____0-plugins
               |             |_____plugin.sass
               |
               |_____0-content-style
               |                   |_____content-style-sass 
               |
               |_____1-content-style
               |                   |_____content-style-sass
               |
               |_____2-content-style
               |                   |_____content-style-sass
               |
               |_____3-content-style
               |                   |_____content-style-sass
               |
               |_____4-content-style
               |                   |_____content-style-sass
               |
               |_____5-content-style
               |                   |_____content-style-sass
               |
               |_____n-content-style
               |                   |_____content-style-sass
               |
               |
               |_____style-cache
               |               |_____cache.txt
               |
               |
               |
               |_____sassmain.sass