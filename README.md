# nodejs install script

This script helps to install nodejs in your home directory. NodeJS is downloaded, compiled and installed in ~/local/ and stow is used to handle multiple nodejs versions.

Example:
<code>
./nodejs-install-env
</code>

To install nodejs 0.6.18 :
<code>
./nodejs-install-env --node-version=0.6.18
</code>

To install nodejs 0.7.9 :
<code>
./nodejs-install-env --node-version=0.7.9
</code>

