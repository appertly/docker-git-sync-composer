# docker-git-sync-composer
A better Git synchronization sidecar container with Composer support.

This is built on-top of [git-sync](http://github.com/appertly/docker-git-sync), with the addition that `composer` is configured to do `composer update` after any `git clone` or `git pull`.

You can override the exact command by overriding the `GIT_SYNC_POST_PULL` environment variable.
