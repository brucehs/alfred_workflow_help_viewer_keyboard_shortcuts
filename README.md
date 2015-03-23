# Enabling Keyboard and Mouse Control of "Back" & "Forward" in Apple's "Help Viewer"—An Alfred Workflow

A simple Alfred workflow using osascript shell scripts to implement keyboard and mouse control in Apple's "Help Viewer". "Help Viewer" does not seem to want to do so natively, so this is a bit of a hack.

[Download][1].

## BetterTouchTool

Mouse Control is achieved through [BetterTouchTool][2]. "Help Viewer" never actually takes focus, so the shortcuts and settings must be enabled universally. Thus the out-of-the-way keyboard shortcuts bound to mouse buttons. Application-specific settings will override them:

![BetterTouchTool Settings][3]

## Further Development

* This workflow was created on 10.9.5 for Alfred 2.6 (374). I don't plan to upgrade to Yosemite anytime soon, so I will keep it functional for Mavericks and Alfred updates. If you would like to adapt it for other versions, please do.

* If anyone knows how to get "Help Viewer" to respond directly to Applescript run by [Keyboard Maestro][4] or BetterTouchTool, that would be a much more straightforward method. I kept getting "posix_spawn: error 7" though.

[1]:https://github.com/brucehs/alfred_workflow_help_viewer_keyboard_shortcuts/archive/master.zip

[2]:http://www.bettertouchtool.net

[3]:https://github.com/brucehs/alfred_workflow_help_viewer_keyboard_shortcuts/blob/master/Workflow/btt_settings.png?raw=true

[4]:http://www.keyboardmaestro.com/main/