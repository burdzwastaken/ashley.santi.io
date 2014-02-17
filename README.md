[![Build Status](https://travis-ci.org/santiycr/ashley.santi.io.png?branch=master)](https://travis-ci.org/santiycr/ashley.santi.io)

## Isn't this the nerdiest wedding website?

A simple [Flask](http://flask.pocoo.org) website running on [Google App
Engine](https://github.com/GoogleCloudPlatform).

## Run Locally
1. Install the [App Engine Python SDK](https://developers.google.com/appengine/downloads).
See the README file for directions. You'll need python 2.7 and [pip 1.4 or later](http://www.pip-installer.org/en/latest/installing.html) installed too.

2. Clone this repo with

   ```
   git clone https://github.com/santiycr/ashley.santi.io
   ```
3. Install dependencies in the project's lib directory.
   Note: App Engine can only import libraries from inside your project directory.

   ```
   cd ashley.santi.io
   pip install -r requirements.txt -t lib
   ```
4. Run this project locally from the command line:

   ```
   dev_appserver.py .
   ```
5. Test

   ```
   python test_main.py
   ```

Visit the application [http://localhost:8080](http://localhost:8080)

See [the development server documentation](https://developers.google.com/appengine/docs/python/tools/devserver)
for options when running dev_appserver.

## Contributing changes
See [CONTRIB.md](CONTRIB.md)

## Licensing
See [LICENSE](LICENSE)

## Author
Ashley Wilson and Santiago Suarez Ordoñez
