Role Name
=========
[![license][2i]][2p]
[![twitter][3i]][3p]

Install zsh with [oh-my-zsh][4]

Description
-----------

Nothing too fancy. I tend to use zsh for **everything** under the sun. As such, the first darn thing to install on my provisions is usually that with a small update to the plugins I use. This is just that.

Role Variables
--------------

The only variable that needs to be changed is in `defaults/main.yml`; **user.home**. It will install the [oh-my-zsh][4] in the userhome.

Usage
-----

Very simple to use. Simply change the role variable listed above and add to your playbook:

``` yaml
- hosts: servers
    roles:
        - zsh
```

Author Information
------------------

[Alejandro Baez][1]

[1]: https://keybase.io/baez
[2i]: https://img.shields.io/badge/license-BSD_2-green.svg
[2p]: ./LICENSE
[3i]: https://img.shields.io/badge/twitter-a_baez-blue.svg
[3p]: https://twitter.com/a_baez
[4]: https://github.com/robbyrussell/oh-my-zsh
