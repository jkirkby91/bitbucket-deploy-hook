First ensure you bibucket account has all the ssh keys to your server

You must have git installed, shell access to servers and php exec function enabled

clone the repo on the server you want the deploy script to deploy to, then clone this 
deploy scrip repository on the server in the repository of your application.

For security through obscurity you might choose to give your deployment script
a difficult to guess name – bitbucket-hook-a13jsur5kcidwe89z.php, for example 

On the Bitbucket website navigate to your repository’s 
Administration > Hooks screen and add a new POST hook
pointed at http:/<domain>/deploy/bitbucket-hook.php.
