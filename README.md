# calvin-arduino

This is a port to Arduino of a minimal implementaion of [Ericsson's Calvin platform](http://www.ericsson.com/research-blog/cloud/open-source-calvin/).
The port is implemented as an arduino library and should be called during `setup()` within the sketch.

##	Installation

** The following instruction is not consistent with the folder structure och naming conventions of this repo. Most likely it is the `src` folder that needs to be inlcuded as  a library, but that name doe snot comply with the Arduino naming convention. The folder actually called calvin arduino contains the example sketch. Uek **

In order to use this library the library folder must be placed inside your Arduino libraries.

1. Clone the repo och download as zip-archive. 
2. Navigate to `.../arduino-1.x/libraries/` and add the Calvin Arduino library folder. _(If the folder does not exist, simply add the folder)._
3. Restart the Arduino application and the Calvin Arduino will be available to include to your sketch.

For further information please browse the Documents folder.
