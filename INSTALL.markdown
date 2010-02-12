# Setup Instructions

This example is set up to run from any HTTP file server running on port 8000. If you already have a webserver on your machine, it may be easiest to simply drop all of these files into the public folder of this webserver. If you don't, you can install "httphere", a mini http server that simply serves static files from a directory:

    sudo gem install -r httphere shared-mime-info

You may need to install shared-mime-info via ports as well:

    sudo port install -b shared-mime-info

If you don't already have this repo on your system, [download it](http://github.com/dyn/remix_world-API-iframe-uploader-example/zipball/master) or git clone it:

    git clone git://github.com/dyn/remix_world-API-iframe-uploader-example.git remix_uploader
    cd remix_uploader

To run httphere on port 8000, chdir to this directory and run:

    httphere -p 8000

Now, open your browser to [http://localhost:8000/](http://localhost:8000/), and you're off!

Read through the [Uploading a Video to Remix](http://rw.staging.iremix.org/docs/guides/uploading_videos) guide to help you understand how the pieces connect as you walk through the code.
