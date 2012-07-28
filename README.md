# SimpleDateValidator

## Notice

This is NOT my work and I do not claim any credit from this. I only made minor changes to the original code that enhanced the UX.

Refer to [Changelog](https://github.com/tltan86/SimpleDateValidator/wiki).

## How-to

Refer to [Wiki](https://github.com/tltan86/SimpleDateValidator/wiki) for implementation.

### Step 1: Include 'SimpleDateValidator.js' javascript into the '<head>' section of your webpage:

	<script type="text/javascript" src="SimpleDateValidator.js"></script>

### Step 2: Apply to '<input type='text' />' element:

	<input type="text" name="dob" id="dob" maxlength="10" value="" onfocus="javascript:vDateType='3'" onkeydown="vDateValueBefore=this.value;" onkeyup="vDateValueAfter=this.value;DateFormat(this,this.value,event,false,'3');" onblur="DateFormat(this,this.value,event,true,'3');" />
	
### Step 3: You're done!

## Credits

Source obtained from http://www.openntf.org/Projects/codebin/codebin.nsf/0/1A0C7132B9B145C888256BDC000CC153
Original Author: Richard Gorremans (RichardG@spiritwolfx.com)
Website: http://www.spiritwolfx.com
Website: http://javascript.internet.com

## For Myself

Refer to this sample [README.md](https://raw.github.com/github/android/master/README.md) on how to build this page.