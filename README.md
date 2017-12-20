# heroku-buildpack-ffmpeg-latest

[![CircleCI](https://circleci.com/gh/jonathanong/heroku-buildpack-ffmpeg-latest/tree/master.svg?style=svg)](https://circleci.com/gh/jonathanong/heroku-buildpack-ffmpeg-latest/tree/master)

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
