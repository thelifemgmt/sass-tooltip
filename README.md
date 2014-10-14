Ferret Tooltip
==============

A pure css tooltip from the Ferret Framework.

[View Demo](http://codepen.io/thelifemgmt/pen/mGhpI)

<br>

How to Use
---

Import the '_ferret-tooltip.scss' file into your project.

  @import 'YOUR_DIRECTORY/ferret-tooltip';


Once the mixin is imported, I would suggest compiling it through autoprefixer. You can then use the tooltip in your project by adding the tooltip html.
 
<br>

Examples
---

<b>Tooltip on Top</b>

	<p>Mauris placerat <tooltip>ultricies eget<tip class="on-top">I am a tooltip on top</tip></tooltip> morbi tristique senectus.</p>


<b>Tooltip on Right</b>

	<p>Mauris placerat <tooltip>ultricies eget<tip class="on-right">I am a tooltip message on the right</tip></tooltip> morbi tristique senectus.</p>


<b>Tooltip on Bottom</b>

	<p>Mauris placerat <tooltip>ultricies eget<tip class="on-bottom">I am a bottom tooltip message</tip></tooltip> morbi tristique senectus.</p>


<b>Tooltip on Left</b>

	<p>Mauris placerat <tooltip>ultricies eget<tip class="on-left">I am a tooltip message, but I am on the left</tip></tooltip> morbi tristique senectus.</p>

<br>

<b>Note:</b> Modern browsers will render <code>&lt;tooltip&gt;</code> just fine, but if you do not want to chance it, you can easily change the markup to span tags like the example below:

	<p>Mauris placerat <span class="tooltip">ultricies eget<span class="tip on-left">I am a tooltip message, but I am on the left</span></span> morbi tristique senectus.</p>