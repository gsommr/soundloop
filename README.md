# soundloop
var widgetIframe = document.getElementById("soundcloud"),
    widget       = SC.Widget(widgetIframe);

widget.bind(SC.Widget.Events.FINISH, function() {
    widget.play();
});
