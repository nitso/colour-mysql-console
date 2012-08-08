colour-mysql-console
====================
Sample config files showing how to colorize linux console mysql client using grc

How to use it
-------------
1. Install grc (for debian systems: `apt-get install grc`)
2. Copy both config files into your home directory
3. Run mysql client `mysql -u <user> -p -h <hostname>`
4. Enjoy!

How does it work
----------------
Mysql client supports using predefined pager for data output.
So we can set grcat (Generic Colouriser) for processing mysql output.
grcat reads supplied config file, parces output according to regexp's and adds colours.
grc manual can be founded via `man grc` or here: http://kassiopeia.juls.savba.sk/~garabik/software/grc/README.txt

Sample screenshots
------------------

![Table screenshot](https://raw.github.com/nitso/colour-mysql-console/master/Screen_table.png)
![Vertical screenshot](https://raw.github.com/nitso/colour-mysql-console/master/Screen_G.png)