# Setup Instructions

This example is set up to run from any HTTP file server running on port 8000. If you already have a webserver on your machine, it may be easiest to simply drop all of these files into the public folder of this webserver. If you don't, you can install "httphere", a mini http server that simply serves static files from a directory:

    sudo gem install httphere

To run httphere on port 8000, chdir to this directory and run:

    httphere -p 8000

Now, open your browser to [http://localhost:8000/](http://localhost:8000/), and you're off!

Read through the [Uploading a Video to Remix](http://rw.staging.iremix.org/docs/guides/uploading_videos) guide to help you understand how the pieces connect as you walk through the code.
