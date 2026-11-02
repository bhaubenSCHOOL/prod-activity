# prod-activity
A productivity tracker that rewards time on productive tabs with play time, drains it on unproductive ones, and locks the screen with a practice problem once the balance hits zero.

## Goal
Keep user on task and reduce time spent on unproductive tabs.

## MVP scope
- Tab detection
- Productive site list
- Reward timer
- Popup/Problems
- Lockout
- Problem R/W
- Penalty/Reward
- Problem set loading

## Future plans
- Weekly stats
- Custom problems (non set)
- Sync across browsers (maybe platforms?)

## Tech stack
- Chrome extension (with default libraries)
- (Languages) JavaScript, HTML, CSS
- (Built in to extension) chrome.tabs, chrome.storage.local, chrome.alarms, chrome.runtime.sendMessage
