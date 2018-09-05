# heroku-buildpack-ffmpeg-latest

> This Heroku buildpack repository is forked from https://github.com/jonathanong/heroku-buildpack-ffmpeg-latest

A Heroku buildpack for ffmpeg that always downloads the latest [static build](http://johnvansickle.com/ffmpeg/).
Unlike other build packs, I never compile anything.

## Usage

Add the following to your `.buildpacks`:

```
https://github.com/hinterview/heroku-buildpack-ffmpeg-latest.git
```

Or run the following from the heroku command line:

```
heroku buildpacks:add https://github.com/hinterview/heroku-buildpack-ffmpeg-latest.git
```
