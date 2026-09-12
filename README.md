# Activity Monitor

[🇬🇧 English](README.md) · [🇷🇺 Русский](README.ru.md)

A small browser-based tool for monitoring and inspecting activity in the current browser tab.

**Live demo:** [ba1ram.github.io/Site-Activity-Monitor](https://ba1ram.github.io/Site-Activity-Monitor/)

## Features

* Monitor activity and state of the current browser tab
* Track browser events such as:

  * mouse and pointer events
  * keyboard events
  * copy, cut and paste
  * scrolling and wheel events
  * focus and visibility changes
  * input and form events
  * drag & drop
  * touch events
  * fullscreen and window resize
  * online / offline status
  * page lifecycle events
* Event log with timestamps down to milliseconds
* Event filtering
* Monitoring and active-time statistics
* Current browser and tab state information
* Export collected events to JSON
* English / Russian interface
* No installation or dependencies required

## How to use

1. Open the [live demo](https://ba1ram.github.io/Site-Activity-Monitor/).
2. Click **Start**.
3. Perform actions in the current tab.
4. Review the collected events in the event log.
5. Use **Filters** to hide events you don't need.
6. Export the collected data as JSON if needed.

The event filter works as a **blacklist**: events are shown by default, and only explicitly hidden event types are filtered out.

## Privacy

The monitor runs entirely in the browser.

It does not send collected events to a server. Clipboard contents and form field values are not stored by the monitor.

The tool is intended for diagnostics, testing and experimenting with browser events.

## Limitations

This is a small browser-based diagnostic tool, not a complete activity recorder or anti-cheat system.

Browser APIs have their own limitations, and some events or information may behave differently depending on the browser, operating system and device.

## License

This project is provided as-is for personal use, experimentation and learning.
