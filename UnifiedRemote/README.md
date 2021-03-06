
#Setup

###Install UnifiedRemote on your mobile device & computer:
http://www.unifiedremote.com/

###Install the preset @ UnifiedRemote:

Copy the `SlideNav` directory from `UnifiedRemote/` to your `Unified Remote\Remotes\Custom` directory

**Custom Remotes Path @**
https://github.com/unifiedremote/Docs/blob/master/intro/whats-included.md

**More Info @**
https://github.com/unifiedremote/Docs/blob/master/intro/getting-started.md

#Layout
```
    ════════════════════════════════  Window Control  ════════════════════════════════

        ┌────────────────────────────────────┐  ┌────────────────────────────────────┐
        │     Switch Windows ( Alt+Tab )     │  │      Exit Current Application      │
        └────────────────────────────────────┘  └────────────────────────────────────┘

    ═════════════════════════════════════  Zoom  ═════════════════════════════════════

        ┌────────────────────────────┐  ┌─────────────┐ ┌────────────────────────────┐
        │   Tap: Decrease Text Size  │  │    Reset    │ │   Tap: Increase Text Size  │
        │  Hold: Zoom Out @ Slides   │  │  Text Size  │ │  Hold: Zoom In @ Slides    │
        └────────────────────────────┘  └─────────────┘ └────────────────────────────┘

    ═══════════════════════════════════  SlideNav  ═══════════════════════════════════

        ┌────────────────────────────────────┐  ┌────────────────────────────────────┐
        │       Tap: Previous Slide          │  │     Tap: Next Slide                │
        │      Hold: Caret To Slide Top      │  │    Hold: Caret To Slide Bottom     │
        └────────────────────────────────────┘  └────────────────────────────────────┘

    ═══════════════════════════════════  LinkNav  ════════════════════════════════════

        ┌────────────────────────────────────┐  ┌────────────────────────────────────┐
        │           Previous Link            │  │             Next Link              │
        └────────────────────────────────────┘  └────────────────────────────────────┘

    ════════════════════════════════════  Scroll  ════════════════════════════════════

        ┌────────────────────────────────────┐  ┌────────────────────────────────────┐
        │              Caret Up              │  │             Caret Down             │
        └────────────────────────────────────┘  └────────────────────────────────────┘
```
#Key Bindings

All keybindings @ `remote.lua` are set up using default SlideNav hotkeys

The following commands are set up for Windows & may require modification to work on non-Windows computers:
```
exit   == Alt + F4
alttab == Alt + Tab
```

#Additional Feature

Also - on my personal copy of this, I have an additional button in the top row which:

* loads SublimeText whether it is running or not
* removes window borders
* sets the window size to full screen

The button & it's function `sublimetext` are commented out in `layout.xml` & `remote.lua`

I commented it out in the release because it is a custom AutoHotkey function & requires additional setup

If you are interested in using the original function, I have included the AutoHotkey script @ `Launch_SublimeText.ahk`

