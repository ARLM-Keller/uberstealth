#Instructions on how to build uberstealth.

# Introduction #

uberstealth should compile out of the box with Visual Studio 2008. Only a few external dependencies are required:
  * [Boost](http://www.boost.org/) (>= 1.48.0)
  * [WTL](http://wtl.sourceforge.net/) (>= 8.1)
  * [Windows Driver Kit](http://msdn.microsoft.com/en-us/windows/hardware/gg454508) (>=7.0)
  * [DDKBuild](http://ddkwizard.assarbad.net/)

# Building uberstealth #

First, make sure to [build boost](http://www.boost.org/doc/libs/1_54_0/more/getting_started/windows.html) and have WTL and the WDK headers and libraries included so your compiler will find them. Also, make sure to setup ddkbuild.