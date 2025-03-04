# Changelog

## v3.21.0

### Feature

- Update core with [rocksdb](https://github.com/holepunchto/librocksdb)

### Improvements

- limit Member list to 5 in Room profile screen

### Fixes

- Fixed voice notes played at different speed sound terrible
- Fixed potential crash due to media preview
- Fixed text overflows for svg, link preview events
- Fixed to not trigger long press deleted message
- Fixed reset navigation when leave the room
- [Android] fixed paste action in Chat input field
- [IOS] Update minimum requirement to IOS 16

## v3.20.0

### Improvements
- Support copy and paste images into chat input
- Keep screen on when a call is in progress
- Improve RTL language support across Android
- Can access filter bar even offline
- Improved chat joining room animation
- Sync no message scenario with desktop
- Improved Multiple message previews
- Add extra bottom offset to interactive keyboard
- Media preview transition improvement

### Fixes

- Fix feedback form crash on submit
- Fix double timestamp on pinned messages screen
- Fix pinned messages background is not blurred
- Hide the reply message on pinned message
- Fix MKV video handling issue
- Fix In-view sync issue in chat
- Update timestamp on focus in the lobby
- Fix chat reaction click not responsive
- Fix attached media lost when typing
- Avoid running intervals when the app is inactive
- Fix DM profile call button logic
- Fix spamming create button creates multiple rooms
- Fix android lobby jumps
- Fix android textinput scroll indicator
- Avoid crash when opening a room with an attached SVG image on iOS <= 17
- Fix stats bar not expandable
- Fix member name color in replies
- Disable keyboard swipe gesture for Android
- Add aiff as unsupported audio type for android
- Correctly show office related file icons, report icons, and unplayable video files icon
- Avoid use of thumb to seek audio voice note
- Drop android devices support for armeabi-v7a architecture

## v3.19.1

### Fixes

- Fix Unable to add reactions to (last) message (keet-store)
- Fix lobby flicker while has plenty rooms
- Fix chat reaction click not responsive
- Fix compress image warning

## v3.19.0

### Features

- Reply to media

### Improvements

- Add call timeout alert
- Improve chat list rendering
- Improved keyboard interactive in chat
- Support non-English alphabet character initials
- Preserve all new lines
- Update audio message UI
- Update reply UI
- Persist pinned message header when keyboard is shown
- Improved dead zone after adding media to Chatbox

### Fixes

- Fix Sent messages occasionally silently fail to send
- Fix infinite loading spinner when enter app from background
- Make tooltips dismissible & increase close timeout
- Fix avoid scroll to end when edit message
- Fix ios share files
- Fix URL parsing and handling in chat input
- Fix Cant long press copy a url
- Fix MemberTag condition logic and styling
- Prevent duplicate reaction bar for voice notes
- Fix long-press reaction not working
- Fix reactions cause media to move left
- Fix return to call button flicker
- Fix Identity Intro page can’t scroll on small devices issue
- Fix unindexed room warning icon color
- Show ‘someone’ when username not found for notification
- Navigate to room options after downgrade self to peer
- Centered lobby action button text

## v3.18.1

### Improvements

- Improved chat scrolling performance
- Preserve all new lines in Chat

### Fix

- avoid network handler to run while app is in background
- fix room info media file entry mismatch

## v3.18.0

### Features

- Express profile setup for existing users

### Improvements

- Play gif in chat
- Add autofocus and zoom to the camera component
- Update new user room tip UI
- Updated room background
- Update unsent draft icon color in lobby
- Update room options UI
- Update design of audio files
- Increase chat preview spacing
- Update avatar size and message preview spacing
- Update reply message component
- Update file stats display
- Update min requirement to Android 9 (sdk 28)
- Update translations

### Fixes

- Refactor chat events
- Fix chat form crash on submit
- Fix android image thumbnail resolution is lower than iOS
- Fix leave room hangs on black screen
- Fix video doesn’t stop playing when going back
- Fix voice only when there’s text
- Fix room detail information UI
- Fix getting in-app toast for blocked user
- Fix media preview disappearing on restart
- Fix filename toLowerCase issue
- Fix enable loud-speaker when turning on cam
- Handle no camera permission on take photo
- Wait for keyboard to dismiss before open tooltip in room
- Fix can’t long press copy a url

## v3.17.0

### Features

- Express profile setup
- Add SVG, HEIC image file support in chat
- Add Audio tab in Media & File

### Improvements

- Scroll to latest message with animation
- Correct condition check when showing unread banner
- Improved link preview image and text display
- Preserve new line in Chat
- Generate Android Audio Waveform properly
- clicking on in app toast will open to that room
- Update Onboarding flow
- Update Setup Name page UI
- Update Device Link flow UI
- Update Recover Account flow UI
- Show offline stat in lobby and room title
- iOS background refresh
- Handle invalid mute/unmute operations
- Show boot date time to stats
- Upgrade to React Native 0.76

### Fixes

- Enable loud-speaker when turn on cam
- Other app music doesn’t pause when joining a call on iOS
- Fix mentions autocomplete
- Revamp the preview file upload logic
- Fix Messages hang outside the right of the screen
- Avoid file opener when saving files
- Big files download status wrong in android
- Display full image at MediaPreview
- Clear file behaviour
- Fix media files
- Fix missing audio/video duration and byteLength
- Fix unable to upload SVG file
- Fix unable to save SVG on iOS
- Can create admin invites with no expiry
- Refactor push subscribe flow
- Refactor UserProfileScreen
- Fix exiting full screen when video ends crashes app
- Scale font properly across all member avatars (已編輯)

## v3.16.1

- Resolved Android crash under certain conditions during app initialization.
- Addressed core stability to resolve frequent crashes in various scenarios.
- Fixed an issue where all messages appeared blurred in the preview after reporting a single message.
- Fixed a crash that occurred during backgrounded calls when receiving push notifications.

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
