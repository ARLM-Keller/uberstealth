# uberstealth Overview #
uberstealth is a plugin for [IDA Pro](http://www.hex-rays.com/idapro/) and [OllyDbg](http://www.ollydbg.de/version2.html) which aims to hide the debugger from most common anti-debugging techniques. The plugin consists of two files, the plugin itself and a dll which is injected into the debuggee as soon as the debugger attaches to the process. The injected dll actually implements most of the stealth techniques either by hooking system calls or by patching memory in the debuggee.

# News #

# Documentation #
  * [Building](http://code.google.com/p/uberstealth/wiki/Building)<br>
<ul><li><a href='http://code.google.com/p/uberstealth/wiki/Installation'>Installation</a><br>
</li><li><a href='http://code.google.com/p/uberstealth/wiki/Usage'>Usage</a></li></ul>

<h1>Getting Involved</h1>
If you find bugs or have a feature request please add them to the <a href='http://code.google.com/p/uberstealth/issues/list'>issue tracker</a>.<br>
You can also send me bugs, suggestions or patches via email.<br>
<br>
<h1>Screenshots</h1>
<img src='http://wiki.uberstealth.googlecode.com/git/screenshot_about.png' />

