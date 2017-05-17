# Welcome to Tobii Stream Engine samples and documentation

  This repository contains samples and [documentation](https://tobii.github.io/stream_engine) to show developers how to
  use our API to build interactive _eye tracking_ enabled games and applications.

  These samples are minimal samples designed to showcase the basic use cases of stream engine.

  Note that Tobii offers several SDK packages targeted at different programming languages and frameworks, so be sure to
  pick the one that fits your needs best. Stream engine is the lowest eye tracking api supplied by Tobii and it is
  mainly intended for advanced users. More developer related information can be found on [Tobii Developer Zone](http://developer.tobii.com/).

# Contact

  If you have problems, questions, ideas, or suggestions, please use the forums on the Tobii Developer Zone (link below).
  That's what they are for!

  Visit the Tobii Developer Zone web site for the latest news and downloads:

  http://developer.tobii.com/

# Compatibility

  Currently Tobii Stream Engine only supports Windows.

# Dependencies
  Binaries are available on NuGet:
  
  * [Stream Engine C# NuGet package](https://www.nuget.org/packages/Tobii.StreamEngine/)
  
  * [Stream Engine C/C++ Native NuGet package](https://www.nuget.org/packages/Tobii.StreamEngine.Native/)

  or as zip archive from the Developer Zone:
  * [Stream Engine C/C++ binary archive](http://developer.tobii.com/downloads/)

# License

  The sample source code in this project is licensed under the MIT License - please see the LICENSE file for details.
  Samples requires Tobii proprietary binaries to access the eye tracker (available on www.nuget.org and [Tobii Developer Zone](http://developer.tobii.com/)).
  Note that these referenced libraries are covered by a [separate license agreement](https://developer.tobii.com/license-agreement/).

# Revision history

Stream Engine change log below:

What's new in version 1.1.1:

	* Fix for possible command mutex starvation, where a command can be delayed for long periods of time during certain conditions.
	* Fix for possible crashes in service transport communication.


What's new in version 1.1.0:

	* New Stream engine consumer zip package, which includes the public consumer parts.
	* Fix C# binding for tobii_set_lens_configuration, was missing a ref modifier.
	* tobii_subscribe_* now returns invalid parameter when supplying a null callback
	* Fixed the trace functionality


What's new in version 1.0.0:

	* First public release of stream engine
