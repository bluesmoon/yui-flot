YUI-Flot is a port of Flot to YUI.

To use it, include the following lines in your HTML:


<!--[if IE]><script language="javascript" type="text/javascript" src="excanvas.min.js"></script><![endif]-->
<script type="text/javascript" src="http://yui.yahooapis.com/combo?2.7.0/build/yahoo-dom-event/yahoo-dom-event.js&2.7.0/build/datasource/datasource-min.js"></script>
<script type="text/javascript" src="yui.flot.js"></script>

The datasource component is optional, and is only required if one of your axes
has its mode set to "time".
