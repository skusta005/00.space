---
title: User Interface/Visuals
icon: versions
order: -5
redirect: https://web.00xo.space/
---
### Revert Debug Menu UI Change
```json
{
    "FFlagImproveMicroprofilerReadability": "False"
}
```
### Red Font/Highlight Font
```json
{
    "FStringDebugHighlightSpecificFont": "rbxasset://fonts/families/BuilderSans.json"
}
```
### Voicechat Mute Toggles
![example](https://github.com/user-attachments/assets/186d3b58-5560-4ea7-ba6f-cc62f8ab5351)
```json
{
    "FFlagMuteTogglesEnableIXP": "False"
}
```
### Mini Webview
```json
{
    "FFlagWebViewProtocol": "False"
}
```
### Remove Parental Controls Tab
```json
{
    "FFlagLuaAppsEnableParentalControlsTab": "False"
}
```
### Legacy Search
```json
{
    "FFlagAXSearchLandingPageIXPEnabled4": "False"
}
```
### Disable Profile Picture Customization
```json
{
     "FFlagAXDefaultAvatarToShopEnabled3": "False"
}
```
```
{
    "FFlagEnableNewChatTabExperiment5": "False"
}
```
### Disable Toast Notifications
```json
{
    "FFlagToastNotificationsProtocolEnabled2": "False"
}
```
### Rename Communications to Voice Enabled
```json
{
    "FFlagGameDetailsDecoupledCommunication": "False"
}
```
### Break Reduced Motion V4
@kezcn
![image](https://github.com/user-attachments/assets/cfdc9732-084e-4c09-bc43-8039a3bf0d89)
```json
{
    "FFlagFixReducedMotionStuckIGM2": "False"
}
```
### V2 Menu
```json
{
    "FIntNewInGameMenuPercentRollout3": "100",
    "FFlagEnableInGameMenuControls": "False",
    "FFlagDisableNewIGMinDUA": "True",
    "FFlagEnableInGameMenuChromeABTest4": "False",
    "FFlagEnableInGameMenuSongbirdABTest": "False"
}
```
### Custom Disconnect Message
```json
{
    "FFlagReconnectDisabled": "True",
    "FStringReconnectDisabledReason": "You're stupid and I hate you"
}
```
### Display FPS
```json
{
    "FFlagDebugDisplayFPS": "True"
}
```
### Verified Badge
> [!NOTE]
> Clientsided only
```json
{
    "FStringWhitelistVerifiedUserId": "UserID"
}
```
### Verified Badge on everyone
> [!NOTE]
> Clientsided only
```json
{
    "FFlagOverridePlayerVerifiedBadge": "True"
}
```
### Applies cool colors to stuff
```json
{
    "FFlagDebugDisplayUnthemedInstances": "True"
}
```
### Remove Disconnect Blur/Loading Blur
```json
{
    "FIntRobloxGuiBlurIntensity": "0"
}
```
### Disable New Chat Translation Settings
```json
{
    "FFlagChatTranslationSettingEnabled3": "False"
}
```
### New Camera Mode
```json
{
    "FFlagNewCameraControls": "True"
}
```
### Custom MicroProfile Size
```json
{
    "DFIntMicroProfilerDpiScaleOverride":  "100"
}
```
### Disable New MicroProfiler/Debug UIs
```json
{
    "FFlagImproveMicroprofilerReadability": "False"
}
```
### Adjust Scroll Speed
```json
{
    "FIntScrollWheelDeltaAmount": "140"
}
```
### Set Custom Kick Message Length
```json
{
    "FIntMaxKickMessageLength": "1"
}
```
### Disable New Blue Theme
```json
{
    "FFlagLuaAppUseUIBloxColorPalettes1": "False",
    "FFlagLuaAppEnableFoundationColors7": "False"
}
```
### Enable New Settings Layout
```json
{
    "FFlagInExperienceMenuReorderFirstVariant2": "True"
}
```
### No Transparency V4 Menu **(2023)**
```json
{
    "FStringInGameMenuModernizationStickyBarForcedUserIds": "UserID"
}
```
### Subscriptions Page
```json
{
    "FFlagLuaAppDevSubsEnabled": "True"
}
```
### Overlay that shows what you type 
```json
{
    "FFlagDebugTextBoxServiceShowOverlay": "True"
}
```
### Ammount of lines to show at once for above
```json
{
    "DFIntTextBoxServiceHistorySize": "1"
}
```
### Hides Gui
```json
{
    "FFlagDebugAdornsDisabled":  "True"
}
```
### Hides Gui 2
```json
{
    "FFlagDebugDontRenderUI": "True"
}
```
### Hides Gui 3
```json
{
    "FFlagDebugDontRenderScreenGui": "True"
}
```
### Disable Autocomplete
```json
{
    "FFlagEnableCommandAutocomplete": "False"
}
```
### Break Top Bar Menu
```json
{
    "FStringNewInGameMenuForceds": "UserID",
    "FFlagEnableInGameMenuChrome": "True"
}
```
### Break Collectible Icon
```json
{
    "FFlagDisplayCollectiblesIcon": "False"
}
```
### Disable Bubble Chat
```json
{
    "FFlagEnableBubbleChatFromChatService": "False"
}
```
### Disable Avatar Chat
```json
{
    "FFlagAvatarChatServiceEnabled3": "False"
}
```
### Remove VC Beta Badge
```json
{
    "FFlagVoiceBetaBadge": "False",
    "FFlagTopBarUseNewBadge": "False",
    "FFlagBetaBadgeLearnMoreLinkFormview": "False",
    "FFlagControlBetaBadgeWithGuac": "False",
    "FStringVoiceBetaBadgeLearnMoreLink": "null"
}
```
### VR Controller transparency
```json
{
    "FIntVRTouchControllerTransparency": "0"
}
```
### Disable VR Collision Fade
```json
{
    "FFlagViewCollisionFadeToBlackInVR": "False"
}
```
### Limit Videos Playing
```json
{
    "DFIntVideoMaxNumberOfVideosPlaying": "0"
}
```
### Disable DSA Reporting In-game
@kezcn
```json
{
    "FFlagDSAIllegalContentReporting2": "False"
}
```
### Desktop App Dev Tools
> [!IMPORTANT]
> Only works on web view windows like profiles, Ctrl + Shift + I
```json
{
    "FFlagDebugEnableNewWebView2DevTool": "True"
}
```
### Enable Events Tab/Change Events Tab URL
```json
{
    "FFlagPlatformEventEnabled2": "True",
    "FStringPlatformEventUrl": "AnyLinkHere"
}
```
### Better Trackpad Scrolling
```json
{
    "FFlagBetterTrackpadScrolling": "True"
}
```
### Reset Character instead of Respawn in Experience Menu
```json
{
    "FFlagInExperienceMenuResetButtonTextToRespawn": "False"
}
```
