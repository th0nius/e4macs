# e4macs

Sources to the Emacs+ plugin for Eclipse [forked from Mulgasoft/e4macs]

## Preparations

* Download and install Eclipse for plugin development (PDE)
* Start Eclipse with a clean workspace

## Import the project from git

* Git -> Project from Git
* Clone URI
* URI: https://github.com/MulgaSoft/e4macs.git or https://github.com/th0nius/e4macs.git
* Import existing projects
* Search for nested projects

## Build the update site

* In **Project Explorer** select 'Emacs+Update'
* Open 'site.xml'
* Select 'Synchronize' (synchronize all features on the site)
* Save -> Build All

At this point the update site is ready and could be hosted as update site for Eclipse. Alternatively to installing the plugin from a update site a package (zip) can be created. This is simply done by creating a zip of the directory

    e4macs/Emacs+Update

The zip-package can be installed as usual via the **Install new Software** mechanism.

