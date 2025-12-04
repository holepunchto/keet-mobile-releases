# Changelog

## v4.8.0

### Feature

- Sent indicators now available in the lobby. 
- Search and forward messages with extended results.
- Capture a photo and set it as an avatar for group chats.
- Display names now support emojis.
- New group guidelines for Keet's community group chats.
- Calls now ring inside the app for a smoother experience.
- No more mandatory updates when new versions are released. 

### Improvement

- Renamed 'Room' to 'Group' chat across the app for consistency.
- Refined Android call screen for DMs.
- Simplified onboarding flow.
- Updated tooltips design.
- Redesigned edit message UI.
- Input box now clears automatically when replying.
- Improved calls handling for blocked users.
- Screen stays awake during audio playback.
- Larger preview for medium files.
- Character limit hints for group chats' descriptions.
- Square avatars in broadcast feeds' notifications.
- Prevent emojis past character limit.
- Improved Android compatibility with 16 KB page sizes.

### Fixe

- Fixed crash when sending messages with extremely long URLs.
- Fixed iOS scrolling gestures causing layout issues.
- Fixed cursor placement glitches on iOS.
- Fixed Android audio pitch inconsistency when playing at different speeds.
- Fixed messages appearing blank in certain cases.
- Fixed missing link preview descriptions.
- Fixed reply highlight animation glitches.
- Fixed escaped characters in sender names.
- Fixed member name flickering.
- Fixed invisible buttons on dark avatars' edit screen.
- Fixed truncated Admin/Moderator labels for long names.
- Fixed removed usernames not showing correctly in lobby preview.
- Fixed chat input focus visuals.
- Fixed layout spacing in New Group Chat bottom sheet.


## v4.7.5

### Fix

- Fix bug when editing message

## v4.7.4

### Fix
- Fix to repair room

## v4.7.3

### Feature
- Read receipt in DM

### Fix
- Fix Link preview description

## v4.7.2

### Fix
- Fix push notification and Calls not functional on Android

## v4.7.1

### Fix
- Read receipts toggle doesn't throw an error
- Handle random background crashes

## v4.7.0

### Feature

- New sounds for notifications and calls
- Sent indicators in group chats
- Sent and read indicators in DM chats
- See the full list of users who reacted with emoji
- Audio output selector 
- AirPlay support for iOS 

### Improvement

- Forward message flow 
- Emoji size consistency 
- View name, size, and type of attached files.
- Improved behavior when playing notifications.
- Unified share QR style 
- Updated sticky date header for better readability.
- Improved lobby and room UI alignment 
- Added user avatar to bottom navigation.
- Clearer onboarding and setup text.
- Normalised users' display names 
- Character limit feedback in chat input
- General stability and performance improvements in React Native.
- Long messages now truncate gracefully with highlighted previews.
- Improved thumbnail generation for MP4 attachments.
- Unified styling for multiple self-mentions.
- Added link preview support for x.com URLs.
- Optimized large file preview generation to prevent crashes.

### Fix

- Fixed music playback interruption when entering rooms with audio files.
- Fixed username validation and error messages.
- Fixed tooltip scaling for larger system fonts.
- Fixed misplaced custom emoji in lobby.
- Fixed unwanted audio output switch during calls.
- Fixed layout clipping of pinned messages.
- Added proper error handling when file selection fails.
- Fixed voice note playback after cache clear.
- Fixed keyboard flicker during typing.
- Fixed right-to-left layout padding issue.
- Fixed paste button overlapping recovery words.
- Fixed file downloads after clearing cache.
- Fixed portrait video orientation issues.
- Fixed broken mentions on GrapheneOS.
- Fixed muted users appearing in pinned messages.
- Corrected image rotation for HEIC files.
- Removed unwanted white background on notification avatars.
- Prevented text clipping in pinned message displays.


## v4.6.1

### Fix

- Mentions now display correctly in message previews after restarting the app.
- Pinch to zoom now works properly during screenshare, both in normal and fullscreen modes.

## v4.6.0

### Feature

- Unread message counts now stay in sync across all linked devices.
- Search for messages directly within any chat room.
- Easily navigate through conversations with visible day markers while scrolling.
- Long-press the app icon to scan or share your Keet QR instantly.
- Display your actual headset or audio device name in call settings.
- Emoji suggestions when typing ':' in the chat input to get instant emoji recommendations.
- New "About Us" section — Learn more about Keet and Holepunch directly from the app.

### Improvement

- Room QR codes now include the room's avatar for easy identification.
- Join the community room matching your selected language when prompted to discover Keet communities.
- Clearer actions and smoother transitions in DM rooms UX.
- Cleaner and more consistent search bar visual style.
- File upload progress improvements.
- Shows packages per row for better readability.
- Room info redesign.
- Improved file preview generation.
- More responsive and visually consistent emoji picker.
- Improved unread message indicator
- Cleaner room invitation messages
- Refreshed app store details.

### Fix

- Fixes DM loading and display issues
- Fixed audio device switching when enabling video in calls.
- Fixed jumping reaction bar when reacting to messages.
- Fixed reported message display and related linting issues.
- Fixed QR code scanning on iOS when linking devices.
- Fixed disabled button rendering issues.
- Fixed admin badge alignment when renaming rooms.
- Fixed device link QR detection.
- Fixed deleted device display handling.
- Fixed image picker behavior and thumbnail cache.
- Fixed reaction bar jumps and keyboard persistence after opening room links.
- Fixed emoji list being half hidden in the picker.
- Fixed member visibility and type parsing issues.
- Fixed avatar edit panel not sliding up properly.
- Fixed .HEIC and .HEIF file handling on Android.
- Fixed room title copy (copies title instead of key).
- Fixed lobby search loading and repeated QR scan errors.
- Fixed inactivity notification crash on iOS when in background.
- Fixed startup crash on x86_64 devices.
- Fixed file upload status and preview generation.
- Fixed deleted message handling when removing files.
- Fixed edit message file removal behavior.
- Fixed byte size limits in link previews.
- Fixed room info logic and layout issues.
- Fixed scroll position for loaded messages.
- Fixed scroll behavior during fast deceleration.
- Fixed missing attached file dimensions.
- Fixed broken app term links and minor cleanup.


## v4.5.1

### Fix

- Fixed unreads not displaying correctly after upgrade.
- Messages with link previews now send reliably without triggering errors or stuck rooms.
- Fixed call disconnection error on iOS.
- Fixed crash when inactivity notification is sent while the app is in the background on iOS.
- Fixed QR scan error messages.
- Fixed DM auto leave behavior.

## v4.5.0

### Feature

- Remove linked devices from your profile.
- Push notifications now include the rooms' avatar for easier recognition.
- Moderation upgrades for better room management.
- Room admins and moderators can now delete files directly from the room options.

### Improvement

- Updated username validation message to specify Latin letters.
- Large file collections now load in pages for smoother scrolling.
- Swipe gestures and loading placeholders improve the room list experience.
- Unified push notification texts and emojis for consistency.
- Improved emoji handling, input stability, and blur intensity control.
- Refreshed call button design.
- Faster media previews.
- Unified handling of camera, microphone, and photo permissions.
- Removed internal usage of Markdown.

### Fix

- Muted users can no longer start calls or create QR codes.
- Elimination of brief black flashes in media previews.
- Fixed unexpected DM call pop ups when notifications are off.
- Resolved file deletion edge cases and ensured proper cleanup of file types.
- Fixed emoji copying and markdown rendering issues.
- Resolved overlapping tooltips, layout glitches, and scroll issues in chat.
- Various minor crash and edge case fixes, including QR errors and link previews.
- Fixed crash on language selection screens.
- Updated build scripts for Xcode 26 compatibility.


## v4.4.4

### improvement

- Replaced FAQ link with the new Keet Support page.
- Updated blur effect for reported message

### Fix

- Temporarily hidden the hide media & file section in the Room

## v4.4.3

### Fix

- Swipe through image cause app hang/crash
- Room options cause android app crash
- DM request opens blank room with roomType error

## v4.4.2

### Fix

- Fixed scanning a DM QR not working.
- Fixed push notifications and DM call ringing not working when the app was in the background for less than 30 seconds.
- Fixed a duplicated ‘Show all’ button appearing on long messages.

## v4.4.0

### Feature
- Room administrators and moderators can now manage join and leave events in the chant.

### Improvement
- Enhanced chat performance and reliability
- Improved lobby scrolling and rendering performance
- Improved lobby list and removed placeholder.
- Support for excluding file ID in replies with link previews.
- Added a "Show All Text" button for long messages.
- Set Android launch mode to single instance for smoother handling.
- Pressing a link preview now takes you directly to the URL.
- Extended image preview support.
- Synced DM room activities texts with desktop.
- Improve DM unread counts user experience.
- Swiping back clears search instead of minimizing the app.
- Improved layout consistency by switching to a container component.
- Enhanced emoji picker.
- Added toast notification when a file is cleared.
- Ability to mute members directly from chat.
- Clearer message when ID recovery fails.
- Show bare-media version in the software info screen.
- Simplified chat anchor logic.
- Added layout animation to the room list for a smoother experience.
- Link previews are hidden when reported.
- Removed 10 files upload limit.
- Medium preview avatar now shown in room options.
- Unified chat parser with desktop.
- Refactored keyboard views into a single component.

### Fix
- Long inline code no longer breaks the chat UI.
- Adjusted line color for better visibility.
- URLs in messages open correctly.
- Disabled screenshots and replays for privacy.
- Improved handling of wakeup timers.
- Long press on a mention no longer breaks functionality.
- Fixed input freeze after media preview requiring a double tap.
- Emoji sheet no longer causes freeze in empty rooms.
- Can scroll correctly in a new chat.
- Long inline code no longer breaks the lobby view.
- Fixed double anchor and scroll issues in chat.
- Media sharing from Safari now works.
- Mentions picker works correctly when input is focused.
- Sending animated images is now supported.
- Video previews display correctly.
- Rooms without a title now show properly.
- Fixed keyboard focus state issues.
- Can now send saved images from the Media Viewer.
- Files with spaces in names are handled correctly.
- Long messages from desktop now display "see more" instead of being cut off.
- Improved autoscroll performance in lobby.
- Fixed avatar preview issues with Pear links.
- TIFF image handling works correctly.
- Usernames are displayed correctly in the lobby.
- Inline code styling fixed on mobile.
- Added extra animation when switching between keyboard and emoji keyboard.
- Emojis cut correctly across multiple lines.
- Pasting an image in chat works.
- Links in messages now work for all users.
- Android notification grouping fixed.
- Join/leave events are hidden by default.
- Reply icon is correctly aligned when swiping to reply to your own message.
- Push notification paths are normalized.
- Fixed jump issues when navigating to new messages.
- Bottom sheet padding updates correctly instead of shifting.
- First DM request now arrives correctly.
- Chat input no longer gets stuck and scrolls to bottom with long messages.
- Fixed short message previews.
- Rendered list holds its position correctly.
- Fixed file processing issues.
- Lobby keyboard now works and renders anchor correctly.
- Large file uploads now work reliably.
- Anchor position follows keyboard correctly.
- Timestamps for received messages display correctly.
- Keyboard closes when leaving the lobby.
- Joining a call via QR image now appears in front of the scanner.
- Editing messages with link previews works.
- Autoscroll anchor works correctly for new local messages.


## v4.3.2

### Fix

- Fixed rooms failing to load caused by a message deletion edge case.

## v4.3.1

### Fix

- Fixed rooms sometimes getting stuck in a restoring state on Android.
- Fixed the message list briefly scrolling the wrong way after you send a message.
- Prevented error loops: if logging an error fails, it no longer throws or crashes the app.
- Made push notifications more reliable on Android by coordinating the push handler with a lockfile.
- Fixed crash when opening some rooms by updating a core dependency.

## v4.3.0

### Feature

- Support leaving DM rooms.

### Improvement

- Shortened sync time via background content fetch.
- Simplified anchor logic and unified keyboard component. 
- Emoji sizing now respects device fontScale. 
- Hide link preview when it has been reported. 
- Improved anchor handling (active keyboard, batch scroll).
- Improved large file upload handling; addressed speed and download issues. 
- Swiping back now clears the search bar/results instead of minimizing the app. 
- Removed the 10 MB upload limit and improved progress/failure handling. 
- Added layout animation to the room list. 

### Fix

- Fixed reply-to messages with link previews showing images instead of text. 
- Fixed blank lobby keyboard / anchor rendering outside the view. 
- Rendered list now retains its position after updates.
- Anchor position now follows the active keyboard correctly.
- Fixed timestamp location for received messages (UI and landscape video). 
- Autoscroll anchor now works on new local messages.
- Fixed last-character emoji rendering bug.
- Corrected landscape video scaling.
- Keyboard now stays open when navigating from the lobby. 
- Fixed avatar reordering on scroll and avatar selection flow.
- Fixed file processing bug. 
- Joining a call now respects mic preference and permission flow. 
- Fixed bottom-sheet join skipping mic preference. 
- QR image join now appears above the scanner.


## v4.2.1

### Fix

- Background core errors are now logged instead of showing error banners.
- Fixed crash when joining certain community rooms.
- Fixed Italian translation during manual onboarding.

## v4.2.0

### Feature

- Edit or update your username directly from your profile.
- File upload progress indicators.
- Faster image previews via compute-worker integration.
- View original images and load large previews in chat.
- Room mute settings now sync across devices.

### Improvement

- Removed Rive for custom emojis and certain layout animations to improve stability.
- Selected images/videos appear instantly in the chat composer.
- Anchor pauses when you scroll manually in chat.
- Improved user experience for large messages in chat.
- Smoother scrolling in the room list.

### Fix

- Bottom sheet now closes before picking an avatar.
- Fixed WebP rendering issues on Android.
- Stabilized the scroll to bottom behavior.
- Restored link color in chat messages.
- Fixed truncated links.
- Fixed avatars appearing as squares.
- Fixed emoji overflow.
- Fixed unresponsive scrolling in username search.
- Corrected avatar border color in the room list.
- Fixed push notifications showing a null title.
- Camera and microphone permissions are now requested when needed.
- Fixed bottom sheet not opening fully after joining via QR.
- Fixed room icon background color.
- Updated push notification action UI.
- Fixed emoji keyboard being dismissed after sending an emoji.
- Fixed avatars not saving.
- Fixed reconstruction of shorthand emojis.
- Fixed media sharing via system share/intents
- Removed duplicate 'copy' option in the message menu.
- Fixed sequential DM request handling.
- Fixed chats occasionally getting stuck.
- Fixed errors when sending very long messages.
- Fixed message preview inconsistencies in the lobby.
- Fixed role permission visibility.
- Fixed code block layout issues.
- Fixed notification sound handling.
- Fixed crashes in the media picker, camera, and file picker.
- Fixed voice note playback speed button.


## v4.1.1

### Fix

- Resolved occasional errors when creating a username.
- Fixed an issue where setting or editing a username could get stuck until another user triggered a change.
- Fixed the inability to edit usernames in production.
- Eliminated large blank spaces appearing in chat and profile screens.
- Messages no longer shift below the keyboard while typing.
- Message previews in the lobby now display consistently.
- Stats bar no longer overlaps the chat box.
- Scanning a QR code for an existing DM now correctly opens the chat instead of re‑sending a request.

## v4.1.0

### Feature

- Faster app start up time.
- Search users through global search field and connect with them via DM.
- Connect with users via DM by sharing your new profile QR code. 
- Re‑enter your profile secret seed phrase under settings for improved account recovery.

### Improvement

- Show live byte progress while downloading files.
- Prevent the phone from sleeping during long file downloads.
- Added a runtime section to the Software Versions screen.
- Refreshed share profile screen UI.
- Improved in app tooltip components and updated overall tooltip styling.
- Added a loading state for pending username edits.
- Added medium resolution avatars to profiles.
- Removed scroll bars from screen views.
- Improved in app notification handling.
- Chat badge counter now appears immediately on room entry.
- Upgraded to Expo 53 and React Native 0.79.
- Migration banner now shows remaining room count.
- Emoji keyboard mounts on demand.
- Updated wording for "Started a call" events.
- Removed the file delete icon under media & files section.
- Updated Reactotron custom command parameters.

### Fix

- Files with 0 bytes now display correctly.
- Edit tag no longer shows on deleted messages.
- Long emoji strings in after replying to action are now truncated -gracefully.
- Disabled reactions on reported messages.
- Multi line messages no longer overlap metadata.
- Correct input focus border color.
- Caller name now appears in Android notifications.
- Finish button remains disabled until account recovery is complete.
- Lobby state now updates correctly; core starts earlier to avoid delays.
- Fixed squeezed avatars in the lobby.
- Added max length validation to the room name field.
- Correct button logic in DM View.
- Normalised background style for bottom sheet buttons.
- Toasts no longer overlap emoji animations on long text.
- Fixed iOS multi line input focus issue.
- Upload stats now display during file uploads.
- Removed initial linear animation in the username search bar.
- Bottom sheet for message deletion is now smooth.
- Sending a voice note on iOS no longer triggers errors.
- Custom Keet emoji notifications now render on Android 4.0.
- Fixed emoji overflow.
- Unblocked scroll when the keyboard opens on iOS.
- Added safe area insets on the Set Username screen.
- Fixed window metrics type issue.
- Correct initial safe area on iPad.
- Resolved chat screen overflow on small displays.
- Pinned header no longer overlaps content.
- Correct member name in lobby last message preview.
- Restored voice note waveforms.
- Removed DM banner; hidden call button logic adjusted.
- Resetting a Room ID now works reliably.
- Reported messages can be unpinned again.
- Fixed banner text and corresponding tests.
- Fixed user avatars now appear in @ mentions.
- Offline indicator now shows while verifying usernames.
- Fixed toast messages for leave room events.
- Message send performance improved by show/hide instead of re render.
- Animated height fixes for bottom sheets.
- Fixed Android navigation flicker.
- Fixed keyboard overlapping action buttons.
- Sending a new voice note no longer blanks earlier notes.
- Can now join incoming call even without mic permission.
- Call started icon now matches desktop.
- Onboarding screens handle orientation changes correctly.
- Correct flavour suffix in Android builds.
- Fixed ripple effect on Android navigation bar buttons.
- Reduced unnecessary FlatList re renders in chat.
- File preview components now receive the correct fileEntry.
- Fixed video attachments.
- Fixed occasional crash on the files screen.
- Continue button stays disabled if device name is empty.
- Fixed profile name colour in chat.


## v4.0.5

### Fix

- Fixed a crash that could occur when the app was in the background.
- Fixed room mirroring completing successfully and room joining.
- Fixed an issue where the profile setup screen reappeared after migration.
- Messages sent from a suspended device now reliably appear on Desktop without needing to relaunch the app.
- Fixed issues preventing users from leaving broadcast rooms.
- Fixed message rendering in chats reliably.
- Fixed a bug where search results in the room list appeared in reverse order.

## v4.0.4

### Fix

- Avatars no longer disappear or revert to initials after a call.
- Rooms you join now sync correctly to all linked devices after leaving and re entering.
- The user profile view now swaps the DM request button for Chat and Call once your request is sent and accepted.
- Improved room pairing reliability and removed deadlocks that could stall room connections.

## v4.0.3

### Fix

- Removed the ‘Waiting for other user to accept’ banner for DM request senders.
- Fixed peer count briefly showing two different numbers when entering a room.
- Restored mentions in lobby message previews.

## v4.0.2

### Fix

- Fixed searching room list slows down performance
- Fixed wrong image preview
- Fixed migration banner to show progress remaining

## v4.0.1

### Fix

- Fixed broken legacy v3 room Plan B; now loads without errors or stalls.
- Fixed performance wakeup loop that was spiking CPU and battery after launch.
- Fixed migration banner, notice now disappears automatically when the upgrade is done.

## v4.0.0

### Feature

- Keet 4.0.0 introduces a new engine which improves performance, app scalability and sets the ground for a new set of features development.

### Improvement

- Faster room loading with optimised icons and image-preview caching.
- Media previews respect maximum image size to save bandwidth.
- Added a system-update banner to keep you informed of important upgrades.
- Cleaner room creation flow and refined DM request handling.
- Down arrow and room avatar colours match desktop application.
- Bottom tab bar is now hidden until onboarding is complete.
- Clearer username error messages and progress indicators on slow networks.
- Better feedback form now includes your username automatically
- Call experience tweaks: hangs up cleanly; DM ring logic improved; Android auto-end in background.
- Introduced hang-up icon for when call ends in rooms.
- Device naming screen now auto focuses the input field.
- Updated confirm device screen.
- Software version list now shows Hyperdiscovery and lists WebRTC as keet-webrtc.
- Refreshed onboarding pages and UI text updates.
- Improved audio record UX and many 

### Fix

- Fixed avatar rendering issues.
- Removed grey bars at the top of several pages.
- Stopped the tooltip from appearing when the username is already set.
- Aligned the error-log message-field layout.
- Resolved cursor and emoji picker jumps when switching between emoji and keyboard input.
- Corrected chat text input width.
- Restored fullscreen video previews.
- Fixed image loading status indicators.
- Adjusted code block spacing for messages sent from mobile.
- Prevented locked recordings from following you when leaving a room.
- Fixed a crash when opening a room on Android.
- Stopped unnecessary FlatList re-renders.
- Center aligned preview images.
- Resolved chat UI breakage after double tapping the emoji picker icon.
- Corrected contentFit on image messages.
- Ensured pinned messages remain visible during a call.
- Fixed speaker tooltip content overflow.
- Calls: fixed orientation breaks, crash when app is killed, call-ring answer now opens the screen.
- Resolved unrecoverable error when sharing a file from Google Files.
- Eliminated flicker when searching usernames.
- Disabled button presses while a tooltip is visible.
- Fixed Discover Communities being cut off on small devices.
- Disabled bottom tab presses when no identity is set.
- Corrected tooltip orientation on tablets.


## v3.25.5

### Fix

- Fixed batch error logs triggered during room syncing

## v3.25.4

### Fix

- Fixed crash on app launch for Android devices

## v3.25.3

### Fix

- Fixes scrolling causing crashes on iOS and Android

## v3.25.1

### Fix

- Fixed an issue preventing DM room members from manually upgrading the room version
- Resolved swarming connection issues by updating internal networking dependencies

## v3.25.0

### Feature

- Users can now create their unique usernames 
- Introduced option to name your devices
- Join rooms by scanning a QR code from the lobby
- Option to delete your account 
- Call preview before joining
- Call timeout alerts
- Full-screen incoming call on Android
- Listen to audio files at 1.5x speed

### Improvement

– Improved call join/leave flow and UI consistency
– Screen sharing now displays at the same size on iOS and Android
– App checks if a room supports calls before navigating to call settings
– Handled call ring and hangup events for DMs
- Prevented Android modal views from overlapping buttons
- Tapping outside the emoji keyboard now dismisses it
– Mention colours updated for better visibility
– Improved reply icon animation
- Synced chat text input state with UI updates
- Long-pressing preview images now shows chat options
- Status bar color now changes dynamically
– Increased emoji screen size and functionality
- Custom device names now appear when linking a new device
- Improved badge count behavior on iOS and Android
- Broadcast rooms now show only the title, hiding sender name
- Smoother swipe animation in the lobby
- Notification badge and mute icon layout improvements in the lobby
- Emoji picker screen made larger and more functional
- Custom device names now appear when linking a new device
- Disabled top right buttons for users who haven't completed onboarding
- Increased touchable area for top-right icons in the lobby
- Improved bottom sheet animations

### Fix

- Fixed swipe regression in the lobby
- Fixed deep links failing to join rooms
- Fixed emoji picker and text input cursor jumping when switching keyboards
- Fixed chat input icons being unintentionally disabled
- Fixed lobby buttons staying in a disabled color state
- Fixed no activity call button remaining after call ended
- Handled Autobase writable errors in chat
- Fixed incorrect mention colors
- Converted room tips to full-screen views
- Fixed avatar issue on invitation previews
- Fixed incorrect handling of filenames with URL extensions
- Removed unwanted decoding of filenames
- Fixed username tooltip position in the lobby
- Fixed emoji keyboard not closing properly
- Fixed logging after app suspension
- Fixed Android notification subscription on devices below Tiramisu
- Fixed issue with pasting join links silently failing
- Handled call resume/suspend when triggered from lock screen
- Fixed Arabic layout rendering bugs
- Prevented double calls to scroll-to-message
- Fixed UI jumping when returning from Room Members to Admin screen
- Fixed chat input not clearing after sending messages
- Audio recording now stops on long-press release
- Fixed scroll-to-message reliability
- Tooltip on room action buttons now displays correctly
- Fixed pinned message header and code block display issues
- Fixed voice recording lock icon overlapping chat input
- Fixed mentions not returning results
- Fixed gesture interaction issues
- Prevented duplicate room openings on repeated taps
- Enabled autocorrect in chat input
- Fixed alignment issues for older messages


## v3.24.2

### Fix

- Fixed crashes
- Fixed suspension deadlock
- Fixed link preview

## v3.24.1

### Fix

- Fixed UI freeze when creating or joining the first room after a clean install
- Fixed an issue where typing in the chat could cause random backspaces on Android
- Fixed issue when calls are taking from lockscreen

## v3.24.0

### Feature

- Incoming calls now ring in DM rooms, with improved call notification handling
- Swipe left to reply
- Added support to send multiple emojis, including a new bare emoji
- Migrated to the new React Native Architecture for improved performance

### Improvement

- Improved group chat creation flow
- Improved chat performance
- Pinned messages now have paging, updated visuals, and better timestamp handling
- Replying to deleted or reported messages is now disabled
- Scroll improvements and reduced lag while navigating messages
- Enhanced chat events transition effects
- Improved emoji rendering, code block layout and input parsing behaviour
- Updated chat input layout and behaviour
- Improved positioning of custom emoji in room titles
- Smarter layout and transitions for media, file previews and clearing cache
- Improved lobby search, file progress clearing, avatar behaviour and keyboard interaction
- Adjusts height correctly when creating broadcast rooms
- Improved handling of notification grouping, sound and fallback behaviour
- Improved layout and localisation for Arabic and RTL languages
- Reduced CPU usage

### Fix

- Fixed join link pasting failing silently
- Fixed room title/description trimming in lobby
- Fixed under count jumping in lobby
- Fixed text cutoff in lobby
- Fixed emoji size too small in some cases in chat
- Fixed text not clearing after sending in chat
- Fixed input paddings in chat
- Fixed flashing send icon in chat
- Fixed room opens multiple times when tapped repeatedly
- Fixed mention doesn’t return result
- Fixed voice note recording delete button breaking the chat input
- Fixed clearing the app share context on screen focus
- Fixed fast scroll causing crashes
- Fixed swiping in lobby issues
- Fixed edited timestamp alignment and and size
- Fixed codeblock alignment
- Fixed case insensitive link parsing
- Fixed reported message showing as a normal message
- Fixed videos with no preview and file cache issues
- Fixed Arabic layout bugs
- Fixed device link error
- Fixed layout animation crash
- Fixed invite QR code


## v3.23.2

### Fix

- Fixes call sound issue at the start of a call

## v3.23.1

### Fix

- Upgrade rive to v9 due to crash issue
- Fix crash on launch for android 10 and below

## v3.23.0

### Feature

- Display unread message count
- Implement scroll to pinned messages
- Transitioned to bare-kit architecture
- New app background optimized for performance

### Improvement

- Set max width for chat event file container
- Handled webp and GIF for preview
- Sync own text background color with desktop
- Update show all button design
- Updated code block rendering style
- Wide image with long file name not fill the available width
- Load images in consistent way
- Disable keyboard autocomplete in search
- DM request to show source before accept
- Swipe from left on RTL layout
- Android badge count
- Update onboarding and profile setup flow
- Add show more/less stats button
- Reduced confirmation step clicks
- BottomSheet enhancement
- Add rules to Android manifest for < android 12
- Update Recover Account logic
- Update translation

### Fix

- Fix flicker in splash screen
- Tooltip positioning on fresh install
- Mic turns on automatically when you click the “ongoing call” notification
- Manage animate emoji
- Anchor flashing number on autoscroll
- Prevent reactions flicker in pinned message
- Mention highlight based on the role
- Attempt to align emoji same line
- Update way to handle long press
- On scroll to reply/pinned message is covered by pinned banner
- Inline pin message overlap
- Force RTL layout on RTL language to avoid timestamp overlap
- Codeblock alignment withing the text component
- Timestamp string overlapping message
- Inline timestamp is vertically centered in message bubble
- Scroll to bottom after send message
- Prevent blank space & unread banner for messages from blocked user
- Adjust show all button padding
- Show send icon in revert direction in Arabic
- Correctly position timestamp spacer to avoid overlap
- Close report message bottomsheet before showing next sheet
- Pasting image rotates it 90 degrees in RTL langauge
- Parsing shared video dimensions
- Update & align status icons
- Network status flickering
- Message item pressable re-rendering
- Profile picture slide up gets stuck
- Message preview wrong alignment on RTL layout
- Adjust content height when keyboard is open when creating broadcast room
- Dismiss room creation page after creating a broadcast room
- Clicking a room multiple times opens the room multiple times
- DM avatar faded
- Crash when clicking + to join a room
- Update splashscreen background color
- Network status alignment
- Fix Restart app crash
- Create and join modal input border
- Onboarding tool tips are out of alignment
- Fix Edit Profile Bottom sheet stuck
- Fix statusbar warnings on ios


## v3.22.1

- Fixed crash on Startup.

## v3.22.0

### Improvements

- Accessibility fixes for small screen devices
- Rewrite bottom sheets
- Rewrite onboarding Tooltips
- Prevent soft reload app when Android config change
- Update legal TOS
- Replace unknown with icon in push notification
- Update loader and chat bubble color
- Timestamp placement improvement
- Sync reported message UI with desktop
- Hide the Reply message on Pinned message
- handle unsupported files & apply consistent media fileSize
- Update preview attachment logic
- Added swiping to dismiss “Call started!” modal

### Fixes

- Push notification issue in core
- DM default avatar not consistent issue
- Onboarding screen fixes
- Set avatar color based on member name
- Android crashes while deleting notification channel
- Search input jumpiness on RTL layout
- Fix layout of Version Screen
- Fix search and pairing UI inconsistency
- Persist member search state after navigate
- Notification page title
- Settings list items text not responsive at large font sizes
- Item text not responsive in Lobby
- Reset navigation when leave the room
- Limit Member list to 5 in compact mode
- When edit room to have no name kills room
- Pin message on long press not showing
- Fix link preview for name decoding
- Timestamp overlaps some messages
- Show timestamp inline with reactions
- Update input font size
- Chat screen overflows
- Switch to simple strategy for input text wrapping
- Increase line number for link preview title
- Hide reply to on deleted item
- Restrict center aligned event width
- Handle deleted on long press
- Reported message timestamp overlap issue
- Fix broken profile name layout on pinned message
- Update parsing links using marked js lexer
- URL Preview overflowing container
- System events space issue
- Voice message accessibility
- File message inconsistency
- Loading SVG text overflows container
- Fix image placeholder layout to prevent content overflow
- Voice notes on mobile played at different speed


## v3.21.1

- Fixed issue where chat gets stuck

## v3.21.0

### Feature

- Update core with [rocksdb](https://github.com/holepunchto/librocksdb)

### Improvements

- limit Member list to 5 in Room profile screen

### Fixes

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
