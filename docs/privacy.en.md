# Swell: Art & Clock Privacy Policy

English · [简体中文](privacy.zh-CN.md) · [Back to Swell](../README.md)

Last updated: October 16, 2026

Swell: Art & Clock is a macOS app developed by Bingxi Liu. It displays digital art, a clock, imported photos and videos, and optional music and weather information. This policy explains how the app handles information and how you can contact us.

## Information on your Mac

Swell saves your display preferences and library selections locally. When you import a photo or video, the app copies the file into its local library and creates a thumbnail. The library also stores information such as the file name, display name, and playback settings. Swell does not upload your imported photos or videos to the developer.

If you enable weather, the app saves your selected city, its coordinates, and the most recent weather result locally. The weather cache includes the observation time and Apple Weather attribution so that a recent result can remain available during a network interruption.

## Weather and location

Weather is optional. City search uses a GeoNames city index bundled with the app and works offline. Search text stays on your Mac; it is not sent to Apple, GeoNames, or another search service. Fetching weather sends the coordinates of your selected place to Apple Weather through WeatherKit. The app also downloads Apple's weather attribution artwork. These services receive the network information needed to process the requests, such as your IP address.

Using a manually selected city does not require location permission. If you click Use Current Location, Swell requests macOS location permission and a location reading to determine a place for weather. It sends that location to Apple's geocoding service to obtain a place name. The app rounds the coordinates saved for this feature to two decimal places. It does not continuously track your location or maintain a location history.

You can turn off Show Weather, clear or change the selected city, and revoke location permission in macOS System Settings. Clearing the city removes the saved selection; it does not immediately erase the existing weather cache file.

## Music information

The optional Music Widget uses macOS Automation permission to read information from the Music app, including the current track title, artist, album, playback position, duration, and available cover artwork. It uses this information to display the current track. Swell does not request your Apple Account password or upload your music files to the developer.

Cover artwork is read locally from Music and cached in memory. If the current track has no usable artwork, Swell checks for a matching item in the local Music library and retries a limited number of times. If no artwork is available, it shows a placeholder. Swell does not send album or artist names to online artwork lookup services.

You can disable the Music Widget and revoke its Automation permission in macOS System Settings. The Music app's own network activity is governed by Apple's policies.

## Accounts and analytics

Swell does not require an app account. The app has no advertising or third-party analytics SDK, and it does not send usage analytics, imported media, or local preferences to a developer-operated server. It does not sell your personal information or track you across other companies' apps and websites.

Apple services process their own requests under Apple's applicable policies. Beta distribution and feedback submitted through TestFlight are handled through Apple's service and applicable terms. See [Apple's privacy policy](https://www.apple.com/legal/privacy/).

## Support messages and public feedback

If you email [1004707367@qq.com](mailto:1004707367@qq.com), we receive your email address and the information and attachments you choose to send. We use them to answer your request, investigate the reported issue, and provide support. Please avoid sending passwords, payment information, or private photos and videos unless they are necessary for your request.

Support correspondence is retained for as long as reasonably needed to handle the request, maintain relevant support records, and meet applicable obligations. You may contact the same address to request deletion of support correspondence, subject to any applicable retention requirements.

If you submit feedback through the public [Swell GitHub repository](https://github.com/Whaleer/Swell/issues), your issues, comments, and attachments are publicly visible. Do not include private information in public feedback; use email instead. GitHub handles account and service information under its [Privacy Statement](https://docs.github.com/en/site-policy/privacy-policies/github-general-privacy-statement).

## Retention and your choices

Preferences and imported media remain on your Mac until you change or remove them. Removing an imported item from Swell deletes the app's local copy; a file currently in use may be retained until playback ends. Your original source file is not deleted. Weather results are replaced by later successful updates; turning weather off does not automatically delete the cached file.

Quitting Swell clears its in-memory music artwork cache. Removing the app alone may leave preferences or support files on your Mac. Contact us if you need help removing local app data. Swell does not provide its own cloud backup or synchronization service; any device backups you choose to use are managed separately.

## Changes and contact

We update this policy when the app's data practices or support channels change and revise the date above. For privacy questions or requests, contact Bingxi Liu at [1004707367@qq.com](mailto:1004707367@qq.com).
