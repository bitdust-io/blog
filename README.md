# BitDust

[bitdust.io](https://bitdust.io)


## About

Sources for blog.bitdust.io projecvt.
This is going to be a simple blog/news web-site about BitDust project.



## To Get Started


Make a fork of github repo : click "Fork" in top-right corner: https://github.com/bitdust-io/blog

This way you become owner of a copy of the source codes. This is fully independent from the source :-)


So you just "forked" some files from upstream, now clone your new repository from github to your local machine:

        git clone git@github.com:myusername/bitdust.blog.git bitdust.blog
        cd bitdust.blog


If you would like to get fresh updates from upstream later you can add "main" repo as well, but in read-only mode:

        git add remote upstream https://github.com/bitdust-io/blog.git 


4. Install hexo framework and other required libraries:

        npm install


5. Generate "LIVE" files for the web site:

        hexo gen


6. Run server on local host:

        hexo server


7. Navigate your web browser to: ``` http :// localhost : 4000 ```


