# Swell user guide and support

English · [简体中文](support.zh-CN.md) · [Back to Swell](../README.md)

Swell: Art & Clock is a digital art app for Apple Silicon Macs running macOS 15 or later. It combines animated artwork, clocks, optional Music and weather information, and local photo and video playback.

## Install the beta

Install Apple's TestFlight app on your Mac, then open the [Swell beta invitation](https://testflight.apple.com/join/nZGUq3mh) and follow the installation instructions. Use TestFlight to check for beta updates.

The beta may change between builds. If TestFlight cannot install Swell, check the invitation page for availability and confirm that your Mac meets the requirements above.

## Choose what to play

| Module | Getting started |
| --- | --- |
| **Lumina** | Choose a built-in theme from the filmstrip. Open **Adjust** to see the options available for that theme. |
| **Cinema** | Use **Import** to add MP4 or MOV videos that macOS can play. Select a video to preview it; folders help organize your collection. |
| **Pixellery** | Use **Import** to add JPEG, PNG, or HEIC images. Choose an image to start your pixel gallery. An empty library displays the built-in collection. |

## Start, navigate, and exit full screen

Click **Full Screen** or press **Command-Return** to start playback. Press **Escape** to return to the gallery. While playing full screen, use **Page Up** or **Page Down** to move to the previous or next available theme or media item.

On a Mac keyboard without dedicated Page Up and Page Down keys, use **Fn-Up Arrow** and **Fn-Down Arrow**.

Swell is a full-screen app. It does not install or replace the macOS system screen saver.

## Set up the clock

In Lumina or Pixellery, open **Adjust → Clock**, enable **Show Clock**, and choose **Flip** or **Clear Glass**. You can also change the time format, seconds, date, and size.

Lumina and Pixellery share their clock style, while each remembers whether its clock is visible. Cinema uses its own clock layout. Dot Progress shows time through its own visualization and does not add a clock overlay.

Clear Glass uses native Liquid Glass on macOS 26 or later, with a material appearance on macOS 15. Its appearance also responds to the macOS accessibility settings for transparency, contrast, and motion.

If you change settings while a full-screen session is running, return to the gallery and start full screen again to use the new settings.

## Music information or artwork does not appear

Enable **Show Clock** and **Music Widget** for the current module, play a track in the Music app, and allow Swell to access Music when macOS asks. Review permission in **System Settings → Privacy & Security → Automation**.

The widget reads from Music on this Mac. It does not read playback from other music apps. Cover artwork is read locally from the current track or a matching item in your Music library, with a limited number of retries. Some tracks have no usable artwork; Swell then shows a placeholder. It does not search online for missing covers.

Turning the widget off or denying permission does not prevent artwork or local media playback.

## Weather does not appear

In a supported Lumina theme or in Pixellery, open **Adjust → Weather** and enable **Show Weather**. Search for and select a city, or choose **Use Current Location** and allow location access when macOS asks. Dot Progress does not add a weather overlay.

City search works offline, and choosing a city manually does not require location permission. **Use Current Location** requests a location reading when you click it; Swell does not continuously track your location.

Weather updates need an internet connection. A recent cached result may remain visible during a connection problem, with its observation time. Try the refresh button after your connection returns. You do not need an API key or a developer account to use weather in the distributed app.

## Imported media and disk space

Swell stores its own local copies of imported images and videos, so importing media uses additional disk space. Moving your original files does not remove the app's copies.

Removing an imported item removes Swell's copy and leaves the original file intact. An item currently used by a full-screen session may be retained until playback ends.

If a file cannot be imported, check that it opens in another app on your Mac and that sufficient disk space is available. MP4 and MOV are container formats; the video inside must also be playable by macOS.

## Multiple displays and keeping the display awake

Enable **All Displays** in Adjust's playback settings to play across connected displays. The main display carries the clock and information; secondary displays show artwork.

**Keep Display Awake** is optional and active only during full-screen playback. Press Escape to end playback and release it.

## What works offline?

Built-in artwork and local photo and video playback work offline. City search also works offline. Weather updates require a connection. Music information comes from the local Music app; that app may need its own connection to play some tracks.

Swell stores preferences and imported media locally. It does not upload imported photos or videos to the developer and has no advertising or usage analytics SDK.

## Contact and feedback

For questions, bug reports, feature requests, or privacy requests, email [1004707367@qq.com](mailto:1004707367@qq.com). Swell is developed by Bingxi Liu.

You can also use [GitHub Issues](https://github.com/Whaleer/Swell/issues) to report a bug or suggest a feature, in English or Chinese. Issues, comments, and attachments are public; use email for private requests.

For a bug report, please include:

- Swell version and TestFlight build number, if available.
- macOS version and Mac model.
- The affected module or theme, and your display setup if relevant.
- Steps to reproduce, what you expected, and what happened.
- A screenshot or the exact error message, if helpful.

Remove private information before sending attachments. We do not need your Apple Account password or payment details.

Read the [privacy policy](privacy.en.md) for details about local storage, Music, weather, location, and support messages.
