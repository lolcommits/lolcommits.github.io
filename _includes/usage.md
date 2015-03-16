#### Enabling and basic usage

From within any git repository, simply do a `lolcommits --enable`.  From that point on, any git commit will automatically trigger a lolcommit capture!  All lolcommits are stored in `~/.lolcommits` by default, placed in a subdirectory by project name, and with a filename matching the commit hash.

You can also enable lolcommits across all your local git repos. Follow [these steps][enable-all-steps] to achieve this using `git init` and the `init.templatedir` setting.

Don't worry about it too much, half the fun of lolcommits is forgetting it's installed!

[enable-all-steps]: https://github.com/mroth/lolcommits/wiki/Enabling-Lolcommits-for-all-your-Git-Repositories

#### Other commands

Ok, if you insist... Since you know about `--enable`, common sense suggest there is also a repository specific `--disable`, hopefully you can guess what that does.  Other handy common commands include `--last`, which will open for display your most recent lolcommit image, or `--browse`, which pops open the directory containing all the lolcommit images for your current repository.  You can always do `--help` for a full list of available commands.

#### Advanced configuration

Want to do something cray cray like adjusting camera delay, enabling an add-on or creating [animated commit GIFs][animating]? Check out how to [configure commit capturing][commit-capturing] or check out our small but growing list of [plugins][plugins-wiki].

If you like to manage things with <a href="http://boxen.github.com">Boxen</a>, [try this module][boxen-module].

[animating]: https://github.com/mroth/lolcommits#animated-gif-capturing
[commit-capturing]: https://github.com/mroth/lolcommits/wiki/Configure-Commit-Capturing
[plugins-wiki]: https://github.com/mroth/lolcommits/wiki/Configuring-Plugins
[boxen-module]: https://github.com/AssuredLabor/puppet-lolcommits

#### Troubles?

Try our trouble-shooting [FAQ][FAQ], or take a read through our [wiki][wiki] for more information. If you think something is broken or missing, raise a [GitHub issue][issues] (and please take a little time to check if we haven't [already addressed][closed-issues] it).

[FAQ]: https://github.com/mroth/lolcommits/wiki/FAQ
[wiki]: https://github.com/mroth/lolcommits/wiki
[issues]: https://github.com/mroth/lolcommits/issues
[closed-issues]: https://github.com/mroth/lolcommits/issues?q=is%3Aissue+is%3Aclosed
