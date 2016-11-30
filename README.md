# capi-checkman

Clone this repo and link to the repo from your home directory
ln -s ~/workspace/capi-checkman ~/Checkman

## Running Checkman on monitors

This repository is updated automatically by the CAPI pipeline to reflect
the projects that we care about. In order to keep a monitor system up
to date, install this crontab:

```bash
0 * * * * /Users/pivotal/workspace/capi-checkman/scripts/update_checkman_config
```

## URL

[CI Display](http://fawn.cfapps.io)
