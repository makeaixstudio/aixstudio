# AIX Studio 2
> **Note**:
> If you want to download the desktop version of AIX Studio 2, please do so from the [official website](https://aixstudio.cedric.kim).

This is the repository that contains the AIX Studio 2 IDE Theia configuration. This is NOT where most of the source code is; if you're looking to contribute to AIX Studio 2 and do not want to touch build settings, have a look at the [`makeaixstudio/plugins`](https://github.com/makeaixstudio/plugins) repo. This is also NOT where AIX Studio 2 Desktop is packaged, and it is also not where AIX Studio 2 Now is packaged. This is only for the core Theia code.
## Building
AIX Studio 2 is built using a simple `yarn` command:
```
$ yarn theia build
```
Now, you can use AIX Studio 2 like so:
```
$ yarn start
```
Do NOT push your built version of AIX Studio 2 to GitHub.