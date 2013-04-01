$.AdBlockDetect
=============
jQuery plugin to detect if AdBlock is installed or not.

Usage:
------------
Put this in the head of your document
```html
<script src="//raw.github.com/killswitch/adblockdetect/master/adblockdetect.min.js"></script>
<script>
$.AdBlockDetect({
  detected: function() {
    $('body').text('We have detected Adblock.');
  },
  undetected: function() {
    $('body').text('Thank you for not using Adblock.');
  }
  support: '#footer'
});
</script>
```
Options:
------------
`detected`: Use this option to tell the script what to do if AdBlock has been detected.

`undetected`: Use this option to tell the script what to do if AdBlock has not been detected.

`support`: This is option allows you to set an element to display the support message saying your site is protected by AdBlockDetect with a link to this repo on it.

Credits:
------------
Credit goes to me as the author clearly, but also all those people out there who use such a unethical plugin. You should be ashamed of yourselves.
