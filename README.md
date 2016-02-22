# STConf
My own Sublime Text configuration


## Install Package Control

[See Package control official website](https://packagecontrol.io/installation)
```
Open Console  with View > Show Console
import urllib.request,os,hashlib; h = 'eb2297e1a458f27d836c04bb0cbaf282' + 'd0e7a3098092775ccb37ca9d6b2e4b7d'; pf = 'Package Control.sublime-package'; ipp = sublime.installed_packages_path(); urllib.request.install_opener( urllib.request.build_opener( urllib.request.ProxyHandler()) ); by = urllib.request.urlopen( 'http://packagecontrol.io/' + pf.replace(' ', '%20')).read(); dh = hashlib.sha256(by).hexdigest(); print('Error validating download (got %s instead of %s), please try manual install' % (dh, h)) if dh != h else open(os.path.join( ipp, pf), 'wb' ).write(by)
```

## Install Package Syncing

[See package page](https://packagecontrol.io/packages/Package%20Syncing)

## Configuration

On each machine, clone this repo.
On sublime text, `Ctrl`+`Alt`+`P` and type `Package Syncing: Define Sync Folder`. Select the git repo previously cloned.

Restart Sublime Text

That's cool
