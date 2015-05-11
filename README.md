<a href="http://info.smartmessages.net"><img src="http://www.smartmessages.net/img/smartmessages-logo.svg" width="400" alt="Smartmessages logo"></a>
Smartmessages snippets for SublimeText
==============================

This project is to help you build templates for the [Smartmessages.net](http://info.smartmessages.net) email marketing system in the [SublimeText](http://www.sublimetext.com) editor.

In SublimeText, select "Preferences" then "Browse packages..." from the application menu. That will show you a "Packages" folder containing a "User" folder; place the `smartmessages.sublime-completions` file in there.

The completions will be available immediately - type `sm_` then ctrl-space and you will be shown a list of completions; selecting one will expand to the full syntax that Smartmessages expects.

Where tags have a range of parameters, the completion usually includes all of them with default values - you will probably want to delete the options that you don't need. For example the gravatar tag is completed to `[[gravatar size=80 rating="pg" email=$subscriber.email default="identicon"]]`, which is equivalent to the default behaviour obtained by a simple `[[gravatar]]`.

You can find full documentation on Smartmessages markup and all these template tags [here](http://wiki.smartmessages.net/#TemplateGuide).

If you have any ideas for changes, improvements or additions to this project, please report issues or even better, fork and send us pull requests.
