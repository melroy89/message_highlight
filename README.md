message_highlight
=================

With this plugin you can colorize the message index rows based on specific criteria like sender, recipient and subject.

FEATURES
--------

Go to roundcube settings area and select rules to highlight emails in your mailview.

INSTALL
-------

Use composer from the Roundcube root directory:

```sh
composer require texxasrulez/message_highlight:dev-master
```

_NOTE:_ Answer **N** when composer ask you about plugin activation.

Activate the plugin by editing the `HOME_RC/config/config.inc.php` file:

```php
$config['plugins'] = [
        // Other plugins...
        'message_highlight',
];
```

CONTACT
-------
Author:   Cor Bosman (cor@roundcu.be)

Bug reports through github (https://github.com/corbosman/message_highlight/issues)

LICENSE
-------

This plugin is distributed under the GNU General Public License Version 2.
Please read through the file LICENSE for more information about this license.
