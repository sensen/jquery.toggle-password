# jquery-toggle-password

A simply jQuery plugin to toggle the display of value on `<input type="password">` element between masked and plain characters.

## Requirements
* jQuery >= 1.9.0
* Modern browsers

## Usage

    <script src="//ajax.googleapis.com/ajax/libs/jquery/1.9.0/jquery.min.js"></script>
    <script src="/jquery-toggle-password.js"></script>
    <script type="text/javascript">
        $(function() {
            $( "input#p11" ).togglePassword({ el: "input#t1", ev: "click" });
            $( "input#p21, input#p22" ).togglePassword({ el: "input#t2" });
        });
    </script>


## Compatibility
* GNU/Linux
  * FF 26
  * Chrome 32
* OS X
  * FF 26
  * Chrome 32
* Windows
  * FF 26
  * Chrome 32
  * Opera 18
  * IE 11

