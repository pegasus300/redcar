
*Important*

Currently Redcar is being ported to JRuby, and not a lot works on HEAD. If
you would like to run the old GTK version, you MUST check out the tag 'gtk-head'

Redcar
======

by Daniel Lucraft
http://RedcarEditor.com/

DESCRIPTION
-----------

A pure Ruby text editor runnng on JRuby. Has syntax highlighting,
snippets, macros and is highly extensible.

FEATURES
--------
  
* Syntax highlighting for many languages.
* Extensive snippets.
* Ruby plugins.

INSTALLATION
------------

(not yet finalized for the JRuby version)

TESTS (specs)
-------------

On OSX:

  jruby -J-XstartOnFirstThread $(which spec) plugins/#{plugin_name}/spec/

On Linux:

  jruby $(which spec) plugins/#{plugin_name}/spec/

  
TESTS (features)
----------------

On OSX:

  jruby -J-XstartOnFirstThread bin/cucumber plugins/#{plugin_name}/features

On Linux:

  jruby bin/cucumber plugins/#{plugin_name}/features/

LICENSE
-------

Redcar is copyright 2008-2009 Daniel Lucraft and contributors. 
It is licensed under the GPL2. See the included LICENSE file for details.

