# Changelog

## v3.16.0

### Features
- Member mute/unmute functionality
- Implement ignore DMs and context update.

### Improvements
- New icons to differentiate group chat, DM, and broadcast rooms
- Improved chat input and button sizes
- Updated DM request notification UI
- Enhanced chat event components refactoring
- Improved link preview processing
- Enabled chat deceleration rate and windowSize by default
- Implemented new UI for reporting inappropriate messages
- Media auto-play when clicking on video
- App will linger longer in the background based on OS feedback

### Fixes
- Fixed first message in broadcast room not displayed
- Corrected chat header loading issue
- Fixed font scaling across member avatars
- Fixed account avatar to show member display name
- Resolved issue with unread messages banner
- Fixed messages hanging outside screen
- Corrected iOS notification titles for direct messages
- Fixed toggling speaker in calls crashing the app
- Resolved recovery phrase display issues
- Fixed preview handling for images and files
- Corrected URL preview styles
- Fixed offline red dot indicator
- Addressed chat input and preview issues
- Fixed member name rendering with trailing backslash
- Resolved spinning wheel in member list search
- Fixed tiny GIFs breaking UI

## v3.15.3

### Fixes
- Fix send email address but got mixed words
- Fix show file icon of attached doc
- Fix dmg file treated as image
- Removed maxHeight restriction to the file

## v3.15.2

### Fixes
- Fix unable to view latest message in small rooms
- Fix miss dimensions when upload image previews (ex: github link previews)
- Show URL previews sent from desktop
- Correctly process and render member names with trailing backslash in Chat

## v3.15.1

### Improvements
- Align with desktop, show white background button when function disabled

### Fixes
- Fix crash when received over 200 notifications
- Fix tiny gifs break the UI when loading
- Fix DM keyboard freeze & float create room button
- Fix call loading infinitely when enter from dialog
- Fix Spinning wheel when getting no results in member list search
- Fix max-height of invitation/link preview
- Fix preview for the unsecure url request
- Fix Custom emoji out of position on lobby preview and toast and single emoji not scaled up
- Fix message preview + toast displayed in lobby for blocked messages

## v3.15.0

### Features
- Links can generate preview
- Room admin can remove member from a room  (for new rooms only until full rollout)

### Improvements
- Room invite can have image preview
- Update various designs including DM, Pinned message, call top, unindexed room warning
- Update device name editing
- Update mention link handling
- Update mention username when changed by user
- Optimize system events

### Fixes
- Fix inline code viewport spillover
- Fix various emoji display issues (multiline, single emoji scaling)
- Fix markdown link formatting
- Fix Chat message editing
- Fix message auto scroll and anchor issues
- Fix image picker error on Android
- Fix error when long press voice note
- Fix lobby mentions style
- Fix leaving and re-entering call, mic is auto-toggled
- Fix to prevent link clicks in lobby and pin preview
- Fix open image is unresponsive in chat
- Fix started a call shown as a message and not an event

## v3.14.2

### Fix:
- Markdown not being sent
- single apostrophe sent as escaped character
- & ampersand parsed/expanded in lobby search & can't be deleted
- emoji gets corrupted or displaced in sentence when sent with line space
- extra emojis added to mentions
- Prev message (emoji corrupt) gets removed from chat

## v3.14.1

### Improvements
- Core update to enable DM for all rooms

### Fixes:
- Fix sharing file menu still shown in the lobby after app go background
- Fix UI breaking with media & emojis

## v3.14.0

### Features:
- Direct Message (Limited to newly created room until all rooms upgrade next week)
- Blind media mirroring for all rooms

### Improvements
- Faster speed between clicking push notification to app opening
- Role Management: Admin/mod of the room can change user role directly in room setting

### Fixes:
- Fix unable to toggle mute/unmute
- Fix able to hear send/receive msg sounds when phone is on silent
- Fix sending message to a room while in a call turns on loudspeaker
- Fix inaccurate anchor count with each visit to the lobby
- Fix sound for send message
- Fix calls are joined with mic muted
- Fix limited access to profile picture throws unknown error
- Fix videos sent from mobile don’t have previews on desktop
- Fix recorded videos are in landscape chat bubbles
- Fix feedback form crashes on submit
- Fix filtering out current room activity toasts
- Fix message preview text size varies for chat events

## v3.13.1

### Improvements:
- Roll out block user

### Fixes:

- Fix recorded videos are in landscape chat bubble
- Fix unknown error when allowing limited access to profile picture
- Fix Videos sent from mobile don't have previews on desktop

## v3.13.0

### Improvements:
- Broadcast feed disclaimer page
- Seed phrase confirm page tooltip and styling
- Media preview video handling

### Fixes:
- Fix feedback form crash on submit
- Fix download error on limited-access file
- Fixed unindexed warning hiding behind chat
- Fix profile pics not saved
- Fix call speaker selector flickering
- Fix error when changing avatar

## v3.12.1
- Fix room scroll
- Fix reactions

## v3.12

### Feature
- Error Log with reporting

### Improvements
- Improve room loading speed
- Reduce memory consumption on chat screen
- Decrease lag when inputing text
- Revamp Audio Waveform
- Use regex to validate prefix for emoji autocomplete
- Update invite message text

### Fixes
- Fix various call issues
- Fix to reduce room screen legacy code & reduce re-renders
- Fix Profile tab shows network indicator during app startup
- Fix sound uneven loudness on receiving and sending messages
- Fix add url sanitize function to room search
- Fix to remove add reaction button from pinned messages
- Fix to invalidate chat cache at different time
- Fix to disable reply text for chat events
- Fix pin icon moving around when adding reactions
- Fix messages in chat with decreased opacity
- Fix file delete error
- Fix to not download initial video fragment if preview is not defined
- Fix Profile tab shows red dot for a while during app startup
- Fix red flicker on profile images
- Fix don’t show error for expired links
- Fix to reduce re-renders on Members List
- Fix to update the chatInput fix position on navBar navigation
- Fix to not show error when user cancel image selection

#### Android specific
- Fix android crash on pick multiple files
