#Amalgamated hosts file

A hosts file, named `hosts` (with no file extension), is a plain-text file used by all operating systems to map hostnames to IP addresses. 

In most operating systems, the `hosts` file is preferential to `DNS`.  Therefore if a host name is resolved by the `hosts` file, the request never leaves your computer.

Having a smart `hosts` file goes a long way towards blocking malware, adware, and other irritants.

For example, to nullify requests to some doubleclick.net servers, adding these lines to your hosts file will do it:

    # block doubleClick's servers
    127.0.0.1 ad.ae.doubleclick.net
    127.0.0.1 ad.ar.doubleclick.net
    127.0.0.1 ad.at.doubleclick.net
    127.0.0.1 ad.au.doubleclick.net
    127.0.0.1 ad.be.doubleclick.net
    # etc...

## Source of host data amalgamated

Currently the `hosts` files from the following locations are amalgamated and de-duped to create one large consolidated hosts file.

* MVPs.org Hosts file at [http://winhelp2002.mvps.org/hosts.htm](http://winhelp2002.mvps.org/hosts.htm), updated monthly, or thereabouts.
* Dan Pollock at [http://someonewhocares.org/hosts/](http://someonewhocares.org/hosts/) updated regularly.
* My own small list in raw form [here](https://raw.github.com/StevenBlack/hosts/master/data/StevenBlack/hosts).

**Currently this hosts file contains 22210 unique entries.**


## Location of your hosts file
To modify your current `hosts` file, look for it in the following places:

**Mac OS X, iOS, Android**: `/etc/hosts`

**Windows**: `%SystemRoot%\system32\drivers\etc\hosts`

