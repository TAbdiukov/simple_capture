#  ![oooOOOooo](icons8-third-eye-symbol-64.png) simple_capture ( `SCAPTURE.EXE` )
Simple capturing tool for legacy/embedded/crazy systems

## Compat
* Runs on everything made by microsoft and having a 8086-compatible processor
	* Made for systems not supporting capturing software for whatever reason (like embedded systems)

## Features
* **Takes into consideration how weird the windows programming is**
	* Doesn't use any external WinApi
	* The slight limitation, tool saves in `.bmp` only. 
		PNG/other lossless formats require winapi/3rd party classes, which is probably too much
	* Unsigned ints impossible in vb? The hell?? Anyway, taken care of
* Doesn't require any crazy compiling procedures! Compile in IDE -> Good to go!


* Not too crazy


## Usage

* Run the tool, make sure the status is ON
* Press `Printscreen`
* Get your sweet pics in the directory

## Sidenote
* Third Eye Symbol icon icon by Icons8

	( although I have the Icons8 licence from github 2019, best safe than sorry)

### Exploitz	
* Sometimes, upon startup, the tool captures out-of-place random icons, such as the classic Windows logo (on Win 10!) for some reason. Windows exploitation time?
* Clipboard.GetData.Type *LITERALLY* lets you read and write everywhere, just like fmt str. It deals Booleans, sure, but still pretty dangerous