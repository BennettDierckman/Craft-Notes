<h1>Local Hosting</h1>

<h2>Craft Valet</h2>
- Dev environment for mac minimalists
- webserver that runs engineX handles all host files and dns locally on your machine
- php mysql and all that neeeds installed
- Homebrew > Composer > Valet
  - install php - brew install php
  - install mysql - brew install mysql
  - install valet - composer global require laravel/valet

<h2>Now make project and link valet</h2>
~~~
    mkdir 'mysite'
    cd mysite/
    vim index.html       (<h1>welcome to my site</h1>)
    valet link mysite    (links cwd to mysite.test)
    valet links          (displays Site, SSL, URL, & Path)
    valet secure mysite  (obtains SSL)
    valet links          (SSL now checked)
    valet domain dev     (valet domain from .test to .dev)
~~~

<h2You are now ready to install craft!</h2>
 - Go to Up-and-Running-with-Craft.md   
   - installing craft with composer

