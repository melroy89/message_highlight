## message_highlight

With this plugin you can colorize the message index rows based on specific criteria like sender, recipient and subject. This repository is a fork and continuation of the orginal work by [Cor Bosman](https://github.com/corbosman/message_highlight).

## Features

Go to your Roundcube settings area and select rules to highlight emails in your mailview.

## Install

Use composer from the Roundcube root directory:

```sh
composer require melroy89/message_highlight:master
```

_NOTE:_ Answer **N** when composer ask you about plugin activation.

Activate the plugin by editing the `HOME_RC/config/config.inc.php` file:

```php
$config['plugins'] = [
        // Other plugins...
        'message_highlight',
];
```

And see the available config options in [config.inc.php-dist](./config.inc.php-dist) file.

## Contact

- Author: Melroy van den Berg (melroy@melroy.org)
- 2nd Author: Gene Hawkins (texxasrulez@yahoo.com)  
- Original Author: Cor Bosman (cor@roundcu.be)

Bug reports through [GitHub Issues](https://github.com/melroy89/message_highlight/issues).

## License

This plugin is distributed under the GNU General Public License Version 2.
Please read through the file LICENSE for more information about this license. See [LICENSE](./LICENSE).
