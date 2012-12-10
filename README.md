smtpprox
========

trivial transparent SMTP proxy

About smtpprox
--------------

smtpprox is a trivial transparent SMTP proxy, an SMTP server and
client combination. It uses its own SMTP server and client modules
which are designed to expose every step of the protocol dialogue to
the calling program, which provides for the greatest flexibility in
hooking in envelope and content controls and scanning.

For efficiency reasons, it pre-forks and serves from a pool of
servers, Apache-style.

Author
------

smtpprox was written by Bennett Todd, <bet@rahul.net>.

About this repository
---------------------

This github repository was setup to track smtpprox source and patches
needed to build a debian package.

smtpprox Copyright
------------------

   This code is Copyright (C) 2001 Morgan Stanley Dean Witter, and
   is distributed according to the terms of the GNU Public License
   as found at <URL:http://www.fsf.org/copyleft/gpl.html>.


   This program is distributed in the hope that it will be useful,
   but WITHOUT ANY WARRANTY; without even the implied warranty of
   MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
   GNU General Public License for more details.

