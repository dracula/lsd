### [LSD](https://github.com/lsd-rs/lsd)

#### Install using Git

If you are a git user, you can install the theme and keep up to date by cloning the repo:

```bash
git clone https://github.com/dracula/lsd.git
```

#### Install using [Homebrew](https://brew.sh)

Easily install from [dracula/homebrew-install](https://github.com/dracula/homebrew-install):

```sh
brew tap dracula/install
brew install --cask dracula-lsd
```

#### Install manually

Download using the [GitHub `.zip` download option](https://github.com/dracula/lsd/archive/refs/heads/main.zip) and unzip them.

#### Activating theme

##### Mac or Linux

1.  Ensure the [[`$XDG_CONFIG_HOME`](https://specifications.freedesktop.org/basedir-spec/latest)|`~/.config`]`/lsd` folder exists;
2.  Copy [`dracula.yaml`](https://github.com/dracula/lsd/blob/main/dracula.yaml) into this folder as [`colors.yaml`](https://github.com/lsd-rs/lsd#color-theme);
3.  In the [`config.yaml`](https://github.com/lsd-rs/lsd#config-file-content) ensure the `theme` property is set to:

```yaml
theme: custom
```

4.  If there is no config file please feel free to use this one: [`config.yaml`](https://github.com/dracula/lsd/blob/main/config.yaml)

##### Windows

1.  On Windows systems lsd only looks for the `config.yaml` files in one location: `%APPDATA%\lsd`;
2.  Create a theme folder in lsd, usually in `AppData\Roaming\lsd` on ARM it will be in `AppData\Local\lsd`;
3.  Place [dracula.zip](https://github.com/dracula/lsd/files/11517536/dracula.zip) in the theme folder;
4.  In the `config.yaml` change to:

```yaml
theme: dracula
```

5.  If there is no config file please feel free to use this one. [config.zip](https://github.com/dracula/lsd/files/11517553/config.zip)
