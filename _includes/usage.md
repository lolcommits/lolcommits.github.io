#### Enabling and basic usage

From within any git repository, simply do a `lolcommits --enable`.  From that
point on, any git commit will automatically trigger a lolcommit capture!  All
lolcommits are stored in `~/.lolcommits` by default, placed in a subdirectory by
project name, and with a filename matching the commit hash.

Don't worry about it too much, half the fun of lolcommits is forgetting it's
installed!

#### Other commands

Ok, if you insist... Since you know about `--enable`, common sense suggest there
is also a repository specific `--disable`, hopefully you can guess what that
does.

Other handy common commands include `--last`, which will open for display
your most recent lolcommit image, or `--browse`, which pops open the directory
containing all the lolcommit images for your current repository.  You can always
do `--help` for a full list of available commands.

#### Advanced configuration

Want to do something cray cray like adjusting camera delay, ironically applying
a [hipster][hipster] style, configuring add-ons or even [animating your
lols][animating]? Then check out how to [configure commit
capturing][commit-capturing] and try some of our growing list of
[plugins][plugins-wiki].

[hipster]: https://twitter.com/matthutchin/status/738411190343368704
[animating]: https://github.com/lolcommits/lolcommits#animated-gif-capturing
[commit-capturing]: https://github.com/lolcommits/lolcommits/wiki/Configure-Commit-Capturing
[plugins-wiki]: https://github.com/lolcommits/lolcommits/wiki/Configuring-Plugins

#### Troubles?

Try our trouble-shooting [FAQ][FAQ], or take a read through our [wiki][wiki] for
more information. If you think something is broken or missing, raise a [GitHub
issue][issues] (and please take a little time to check if we haven't [already
addressed][closed-issues] it).

[FAQ]: https://github.com/lolcommits/lolcommits/wiki/FAQ
[wiki]: https://github.com/lolcommits/lolcommits/wiki
[issues]: https://github.com/lolcommits/lolcommits/issues
[closed-issues]: https://github.com/lolcommits/lolcommits/issues?q=is%3Aissue+is%3Aclosed
