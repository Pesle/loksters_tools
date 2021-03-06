Lokster's Tools for Engraving through Inkscape
============
This is a inkscape plugin, generating Gcode files from Vector Paths in [Inkscape](https://inkscape.org/en/).  
**The code originally came from [Lokster](http://lokspace.eu/anet-a8-3d-printer-laser-engraver-mod/) modified by [Deadolus](https://github.com/Deadolus/loksters_tools), and now me (Pesle)**  
Deadolus changed the behaviour so that the calibration up front is optional.  
Deadolus also changed a scaling factor, because the old one seemed to produce too small results for him.

I have added the ability to invert the power levels, 
My TTL controlled laser requires 5V from my 3D printers 12V, so I am using an Optocoupler, which inverts the power signal.
[Ryan Griggs came up with this Solution](https://electronics.stackexchange.com/questions/321987/convert-12vdc-fan-controller-output-to-ttl-signal-of-laser#answer-322104)

Head over to [Lokster's Webpage](http://lokspace.eu/anet-a8-3d-printer-laser-engraver-mod/) for a tutorial on how to use the Inkscape plugin.

Install Instructions
-------------

### On Linux
Move the files contained in this directory in to .config/inkscape/extensions


### On Windows
Move the files contained in this directory in to %Inkscape Directory%\share\extensions  
Where %Inkscape Directory% is where you installed Inkscape, e.g. "C:\Program Files\Inkscape\"


The extension will then appear under Extensions-->Lokster's Tools

Disclaimer
-------------
THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR  
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,  
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE  
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER  
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,  
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE  
SOFTWARE.

Copyright
-------------
Lokster has published his work under [CC Attribution-Share Alike 4.0 International](https://creativecommons.org/licenses/by-sa/4.0/).   
I also publish my code under this license.  
If you like Lokster's work head over to his site and checkout his other content. 
You may also donate directly to him if you wish so. 
