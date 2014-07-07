# Disable Admin Login

A WordPress plugin that blocks logins using the usernames 'admin' or 'administrator'

## What it does

that blocks any attempt to login to your WordPress website with the usernames 'admin' or 'administrator'

Why? Because a cursory inspection of my server logs showed that most automated brute force hacking attempts use one of these two usernames. Stopping these attempts as early as possible significantly reduces load on the server.

## Installation

Important! Before installation, you must ensure that your main administrator username is set to something other than 'admin' or 'administrator', or you wll be locked out of your own website.

Upload this file to wp-content/mu-plugins

Do not put it in a sub-folder.

The plugin will be automatically activated. Running it as a mu-plugin ('Must Use' plugin) allows the blocking to happen very early, thus reducing the amount of WordPress code that runs, therefore reducing load on your server.

## License

Copyright (c) Lumpy Lemon Ltd. All rights reserved.

Released under the GPL license:
http://www.opensource.org/licenses/gpl-license.php

This program is free software; you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation; either version 2 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

## Changelog

* 1.0 (7th July 2014)
* Initial release

## To-do
* readme.txt
* Release on wordpress.org