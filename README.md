# Alfred Workflows for Developers

## Installing
1. Click the download buttons below
2. Double-click to import into Alfred 2
3. Review the workflow to add custom Hotkeys

## Updating
Run the [Alleyoop Workflow](http://www.alfredforum.com/topic/1582-alleyoop-update-alfred-workflows/) using the keyword `oop`. If you're not comfortable with Alleyoop, **star this repo** to keep up to date on new versions and additional workflows.

## Contributing
See [CONTRIBUTING.md](https://github.com/willfarrell/alfred-workflows/blob/master/CONTRIBUTING.md) for guidelines.

## Workflows
### [Package Managers](https://github.com/willfarrell/alfred-pkgman-workflow) ([Download  v1.15](https://raw.github.com/willfarrell/alfred-pkgman-workflow/master/Package%20Managers.alfredworkflow))
Quick package/plugin/component (repo) lookup of for your favourite package managers. Currently supports `Alcatraz`, `bower`, `CocoaDocs/CocoaPods`, `Composer`, `docker`, `Grunt`, `Homebrew`, `Maven`, `npm`, `pear`, `pypi`, `gems`, and `rpm`. All workflows require constant internet connection.

All repos have caching enabled to speed up common queries. These caches are refreshed after 14 days and may take longer then expected to return results during update. You can force a cache refresh by running `pkgman cachedb` to redownload the databases (applies to `alcatraz`, `grunt`, `cocoa`). Alternatively you can run `pkgman cleardb` to remove all stored cache, but this isn't recommened.

**js, css, html:** `bower {query}`

![alt text][bower]

**node.js:** `npm {query}`

![alt text][npm]

**node.js task runner:** `grunt {query}`

![alt text][grunt]

**XCode:** `alcatraz {query}`, `cocoa {query}`

CocoaPods can be upgraded to CocoaDocs by changing `$apple_docs` to true in the script.

![alt text][alcatraz]
![alt text][cocoa]

**PHP:** `composer {query}`, `pear {query}`

![alt text][composer]
![alt text][pear]

**Python:** `pypi {query}`

The Python Package Index is very slow due to a lack on API and pagaination. A min query length has been put in place to help speed this up. You can change it in the script, `$min_query_length = 3`. Perhaps someone with a python background can improve this.

![alt text][pypi]

**Ruby:** `gems {query}`

![alt text][gems]

**Java** `maven {query}`

![alt text][maven]

**Mac OS X:** `brew {query}` (aka *homebrew*)

![alt text][brew]

**Linux:** `rpm {query}`

![alt text][rpm]

**Linux containers:** `docker {query}`

![alt text][docker]

### [Dash](https://github.com/willfarrell/alfred-dash-workflow) ([Download  v1.5](https://raw.github.com/willfarrell/alfred-dash-workflow/master/Dash.alfredworkflow))
[Dash](http://kapeli.com/) comes with default Alfred 2 Workflow. This is an extension to that by shortening the keyword filters for each language. Does not require online connection.

**Commands Included:** `dash {query}` (default), `html {query}`, `css {query}`, `js {query}`, `jquery {query}`, `angularjs {query}`, `bootstrap {query}`, `svg {query}`, `nodejs {query}`, `php {query}`, `redis {query}`, `mysql {query}`, `cpp {query}`, `backbone {query}`, `underscore {query}`, `sass {query}`, `compass {query}`, `wordpress {query}`, `drupal {query}`

![alt text][dash]

### [man](https://github.com/isometry/alfredworkflows/tree/master/net.isometry.alfred.man) (-) [[Download](https://raw.github.com/isometry/alfredworkflows/master/man.alfredworkflow)]
![alt text][man]

### [Dev Doctor](http://wemakeawesomesh.it/alfred-dev-doctor/) (1.5) [[Download](https://github.com/sydlawrence/alfred-dev-doctor)]
Work just like the Dash Workflow, but requires a constant internet connection. A great alternative for those who don't own Dash.

### [StackOverflow](https://github.com/tzarskyz/Alfred-1) (1.0) [[Download](https://github.com/tzarskyz/Alfred-1/blob/master/stackoverflow.alfredworkflow?raw=true)]

`st {query}`

![alt text][st]

### [ssh](https://github.com/isometry/alfredworkflows/tree/master/net.isometry.alfred.ssh) (-) [[Download](https://raw.github.com/isometry/alfredworkflows/master/ssh.alfredworkflow)]
![alt text][ssh]

### [Jenkins](https://github.com/jeroenseegers/alfred-jenkins-workflow) (1.0) [[Download](https://github.com/jeroenseegers/alfred-jenkins-workflow/raw/master/Jenkins.alfredworkflow)]

`jenkins {query}`

![alt text][jenkins]

### [Kill Process](https://github.com/nathangreenstein/alfred-process-killer) (1.2)  [[Download](https://github.com/nathangreenstein/alfred-process-killer/raw/master/Kill%20Process.alfredworkflow)]

`kill {query}`

![alt text][kill]

### Encode/Decode (1.1) [[Download](https://raw.github.com/willfarrell/alfred-workflows/master/encode-decode.alfredworkflow)]
Using the keywords `encode {query}` or `decode {query}`, will transform your query strings through *base64*, *html*, *url*, and *utf-8* encode/decode. Pressing enter will copy the encoded/decoded string to the clipboard.

![alt text][encode]

### [Colors](https://github.com/TylerEich/Alfred-Extras) (1.2) [[Download](https://github.com/TylerEich/Alfred-Extras/blob/master/Workflows/Colors.alfredworkflow)]
Color convertions: `c`, `hsl`, `rgb`, `#`

### [VMWare Fusion](https://github.com/ctwise/alfred-workflows#vmware-control) (1.1) [[Download](http://tedwi.se/u/d4)]
@ctwise

### VirtualBox (1.0) [[Download](https://www.dropbox.com/s/51pyuuj051pydn2/VirtualBox.alfredworkflow)]
@MattD

### [Beanstalk](https://github.com/Leenug/Alfred-Beanstalk) ([Download  v1.0](https://github.com/Leenug/Alfred-Beanstalk/blob/master/Beanstalk.alfredworkflow?raw=true))


### Github (0.0)
Looking for one that includes secure authentication to allow for 5000 request/hour.

## License
Pick your poison [Apache Public License](https://www.apache.org/licenses/) / [MIT](http://opensource.org/licenses/MIT) / [GNU General Public License](http://www.gnu.org/licenses/gpl.html) Copyright © 2013 will Farrell willfarrell.ca



[alcatraz]: ./Screenshots/alcatraz.png "Sample alcatraz result"
[bower]: ./Screenshots/bower.png "Sample bower result"
[brew]: ./Screenshots/brew.png "Sample brew result"
[cocoa]: ./Screenshots/cocoa.png "Sample cocoa result"
[composer]: ./Screenshots/composer.png "Sample composer result"
[docker]: ./Screenshots/docker.png "Sample docker result"
[gems]: ./Screenshots/gems.png "Sample gems result"
[grunt]: ./Screenshots/grunt.png "Sample grunt result"
[man]: https://raw.github.com/isometry/alfredworkflows/master/screenshots/man_example1.png "Sample man result"
[maven]: ./Screenshots/maven.png "Sample maven result"
[npm]: ./Screenshots/npm.png "Sample npm result"
[pear]: ./Screenshots/pear.png "Sample pear result"
[pypi]: ./Screenshots/pypi.png "Sample pypi result"
[rpm]: ./Screenshots/rpm.png "Sample rpm result"
[ruby]: ./Screenshots/ruby.png "Sample ruby result"

[ssh]: https://raw.github.com/isometry/alfredworkflows/master/screenshots/ssh_user@local.png "Sample ssh result"

[dash]: ./Screenshots/dash.png  "Sample dash result"

[st]: ./Screenshots/st.png "Sample StackOverflow result"

[jenkins]: https://github.com/jeroenseegers/alfred-jenkins-workflow/raw/master/alfred-jenkins-workflow-screenshot.png "Sample jenkins result"

[kill]: https://github.com/nathangreenstein/alfred-process-killer/raw/master/screenshot1.png "Sample kill result"

[encode]: ./Screenshots/encode.png  "Sample encode result"
