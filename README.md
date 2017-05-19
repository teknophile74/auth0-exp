#   a u t h 0 - e x p  
 The Auth0-dump-test.js and Auth0-dump-test-API.js files are replacements for the a0dump.js from the https://github.com/xurei/auth0-dump-config repo.

This is not meant to be run stand alone.

Auth0-dump-test.js requires https://github.com/xurei/auth0-dump-config installed globally as a base for it to work.

Auth0-dump-test-API.js requires https://github.com/xurei/auth0-dump-config and https://github.com/auth0/node-auth0 installed globally as a base for it to work.

Both are meant to directly replace a0dump.js from the https://github.com/xurei/auth0-dump-config project depending on the desired results.

The configuration also requies minimal configuration per the auth0-dump-config project.

This can be accomplished by running a copy command, on the target system, like the one below:
cp ~/git/auth0-exp/Auth0-dump-test.js /usr/lib/node_modules/auth0-dump-config/a0dump.js

Then running the a0dump command as cited in the auth0-dump-config project.

Example:
a0dump -c ~/auth0exep/deployment-client.json -o ~/auth0exep/deployment-client
