# README
## mrconfig
This is my .mrconfig file being stored in git.
### Usage
  * Setup your proxy information ```export HTTP_PROXY='http://user:password@proxyserver.com:port'```
  * Clone out the myrepos repo to get the  ```mr``` command ```git clone https://github.com/joeyh/myrepos.git /var/tmp/myrepos```
  * Run ```mr``` to bootstrap the other repos ```/var/tmp/myrepos/mr bootstrap https://raw.githubusercontent.com/bigashman/mrconfig/master/home/.mrconfig```
    * Note: This will error as we try to run homeshick from an untrusted repository.  If you are happy that you have the correct ```.mrconfig``` then we can use ```--trust-all```
