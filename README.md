# rclone-heroku

> Forked to be safe from unintended changes in source repository and subsequent security issues at the deployment levels.

A Heroku buildpack for rclone that always downloads the latest static build.
Unlike other build packs, I never compile anything and remove this git.

Also the config provided in "RCLONE_CONFIG" Config Variable is automatically loaded.

## Usage

Add the following to your `.buildpacks`:

```
https://github.com/alberteinstein42/rclone-heroku.git
```

Or run the following from the heroku command line:

```
heroku buildpacks:add https://github.com/alberteinstein42/rclone-heroku.git
