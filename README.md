sublime_text_conf
=================

Commande pour installer package control dans SublimeText3 :
```python
import urllib.request,os,hashlib; h = '7183a2d3e96f11eeadd761d777e62404' + 'e330c659d4bb41d3bdf022e94cab3cd0'; pf = 'Package Control.sublime-package'; ipp = sublime.installed_packages_path(); urllib.request.install_opener( urllib.request.build_opener( urllib.request.ProxyHandler()) ); by = urllib.request.urlopen( 'http://sublime.wbond.net/' + pf.replace(' ', '%20')).read(); dh = hashlib.sha256(by).hexdigest(); print('Error validating download (got %s instead of %s), please try manual install' % (dh, h)) if dh != h else open(os.path.join( ipp, pf), 'wb' ).write(by)
```

Liste de mes plugins :
- [Nexus Theme](https://github.com/EleazarCrusader/nexus-theme) 
- [Codeivate](https://github.com/codeivate/codeivate-st)
- [RegReplace](https://github.com/facelessuser/RegReplace)
- [SQL Beautifier](https://github.com/zsong/SqlBeautifier)
