## PHProxy - Web based PHP Proxy

PHProxy is a web HTTP proxy written in php. It is designed to bypass proxy restrictions through a web interface very similar to the popular CGIProxy. The only thing that PHProxy needs is a web server with PHP installed (see Requirements below). Be aware though, that the sever has to be able to access those resources to deliver them to you.

Originaly developed in [SourceForge](http://www.sourceforge.net/projects/poxy/) during 2002-2007 and then abandoned. This project needs to live, this is why I  have copied it here and will continue to develop it.

Well, I forked it, because it still needs to live, and there was no activity. We'll see :')


## Support

Use the Github functionality here: https://github.com/Wr0ngName/phproxy/issues/new


## License

This source code is released under the GPL.
A copy of the license in provided in this package in the file named LICENSE.md


## Documentation

http://phproxy.readthedocs.org


## Requirements

 * php > 5
 * safe_mode=off / fsockopen() allowed
 * openssl for https support
 * zlib for output compression
 * file_uploads=on for file uploads.


## Installation

Simply copy the files of the repository in your public web server folder.

```
cd /var/www/html/
git clone https://github.com:Wr0ngName/phproxy.git
```

## Disclaimer

Basically use at your own risk.
