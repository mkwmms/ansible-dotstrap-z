ansible-z
=========
<!-- [![Build Status](https://travis-ci.org/mkwmms/ansible-z.svg)](https://travis-ci.org/mkwmms/z) -->

Install & configure [z] for [bash], [zsh] & [fish] shells.

Requirements
------------

None.

Role Variables
--------------

See [default variables].

Dependencies
------------

None.

Example Playbook
----------------

```
    - hosts: servers
      roles:
         - { role: mkwmms.z }
```

Notes
-----

__Warning__: This role modifies your default shell configuration file, eg.
`~/.bash_profile`, `~/.zshrc` or `~/.config/fish/config.fish`.

License
-------

GPLv3

Author Information
------------------

[@mkwmms]

[@mkwmms]: https://github.com/mkwmms
[aura]: https://github.com/aurapm/aura
[bash]: https://www.gnu.org/software/bash/manual/bashref.html
[default variables]: defaults/main.yml
[dotstrap]: https://github.com/mkwmms/dotstrap
[fasd]: https://github.com/clvv/fasd
[files]: files/
[fish]: http://fishshell.com/
[homebrew]: https://github.com/Homebrew/homebrew
[pure]: https://github.com/sindresorhus/pure
[variables]: vars/main.yml
[yaourt]: https://github.com/archlinuxfr/yaourt
[z]: https://github.com/rupa/z
[zsh]: http://zsh.sourceforge.net