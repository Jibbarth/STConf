# STConf
My own Sublime Text configuration


## Install Package Control

[See Package control official website](https://packagecontrol.io/installation)
```
Open Console  with View > Show Console
import urllib.request,os,hashlib; h = '2915d1851351e5ee549c20394736b442' + '8bc59f460fa1548d1514676163dafc88'; pf = 'Package Control.sublime-package'; ipp = sublime.installed_packages_path(); urllib.request.install_opener( urllib.request.build_opener( urllib.request.ProxyHandler()) ); by = urllib.request.urlopen( 'http://packagecontrol.io/' + pf.replace(' ', '%20')).read(); dh = hashlib.sha256(by).hexdigest(); print('Error validating download (got %s instead of %s), please try manual install' % (dh, h)) if dh != h else open(os.path.join( ipp, pf), 'wb' ).write(by)
```

## Install Package Syncing

[See package page](https://packagecontrol.io/packages/Package%20Syncing)

## Configuration

On each machine, clone this repo.
On sublime text, `Ctrl`+`Alt`+`P` and type `Package Syncing: Define Sync Folder`. Select the git repo previously cloned.

Restart Sublime Text

# Hey, Salut  olivier !!!! :)