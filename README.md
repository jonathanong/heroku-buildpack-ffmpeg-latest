# heroku-buildpack-ffmpeg-latest

Push: [![Test](https://github.com/jonathanong/heroku-buildpack-ffmpeg-latest/workflows/Test/badge.svg?branch=master&event=push)](https://github.com/jonathanong/heroku-buildpack-ffmpeg-latest/actions?query=workflow%3ATest+event%3Apush+branch%3Amaster)  
Scheduled: [![Test](https://github.com/jonathanong/heroku-buildpack-ffmpeg-latest/workflows/Test/badge.svg?branch=master&event=schedule)](https://github.com/jonathanong/heroku-buildpack-ffmpeg-latest/actions?query=workflow%3ATest+event%3Aschedule+branch%3Amaster)

> If you'd like to maintain this repository, let me know!

A Heroku buildpack for ffmpeg that always downloads the latest [static build](http://johnvansickle.com/ffmpeg/).
Unlike other build packs, I never compile anything.

## Usage

Add the following to your `.buildpacks`:

```
https://github.com/jonathanong/heroku-buildpack-ffmpeg-latest.git
```

Or run the following from the heroku command line:

```
heroku buildpacks:add https://github.com/jonathanong/heroku-buildpack-ffmpeg-latest.git
```
