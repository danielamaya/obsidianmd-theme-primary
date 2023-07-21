## Please see README.orig for the original README from the repo at https://github.com/ceciliamay/obsidianmd-theme-primary.

## Install

* Find your vault directory:

```
$ find ~/ -type d -name .obsidian 2>/dev/null
```

The directory on my MacBook is `/Users/danielamaya/Documents/myvault/.obsidian`. Replace _my_ directory with _your_ directory in commands below.

Note: It is possible that the vault directory is not in your home directory. In that case go to the following link for directions on finding your vault: https://forum.obsidian.md/t/finding-and-verifying-the-obsidian-vault-to-move-it-to-dropbox/7439/2.

* Create a directory for the theme:

```
$ mkdir /Users/danielamaya/Documents/myvault/.obsidian/themes/primary
```

* Clone the repo

```
$ git clone https://github.com/danielamaya/obsidianmd-theme-primary.git
```

* Copy files to theme directory

```
$ cp obsidianmd-theme-primary/{manifest.json,theme.css} /Users/danielamaya/Documents/myvault/.obsidian/themes/primary
```

* Change your theme to primary.
