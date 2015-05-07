# phpnuget
Host your own nuget feed with this docker image running phpnuget from kendar.org.

Start: docker run -p 80:80 --name phpnuget bwaller/phpnuget

Point web browser to http://\<yourhost\>/phpnuget/setup.php

Change settings and save.

Login at http://\<yourhost\>/phpnuget/

and start uploading packages.
