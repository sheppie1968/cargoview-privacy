# Privacy Policy for CargoView

**Last updated: 3 October 2026**

CargoView is a local video viewer for IP cameras (Uniview, Hikvision, Dahua, TP-Link, and other RTSP-compatible devices) on your own network. This policy explains what data the app handles.

## Who We Are

CargoView (package name `com.rearviewvan.app`) is published on Google Play under the developer name **Mark Shepherd**, on behalf of **HYBRID LEARNING SOLUTIONS (PTY) LTD**, Kuils River, South Africa (https://hybride.co.za/). HYBRID LEARNING SOLUTIONS (PTY) LTD is responsible for the app and for this policy. In this policy, "we", "us" and "our" mean HYBRID LEARNING SOLUTIONS (PTY) LTD.

## Data We Collect

CargoView does not collect, transmit, or share any personal data with us or any third party. We have no servers, and the app contains no analytics, advertising, or crash-reporting SDKs of any kind.

## Data Stored On Your Device

The app stores your camera connection settings — IP address, port, username, password, and stream preferences — locally on your device only, using Android's DataStore. This information:

- Never leaves your device except to connect directly to the camera you configured, over your local network.
- Is excluded from Android's cloud backup and from device-to-device transfer, so it is never copied off your device by the system.
- Is not accessible to us, as we do not operate any backend service.
- Is removed if you clear the app's data or uninstall the app.

## Network Access

The app declares the following permissions:

- **Internet access** (`INTERNET`) — required to open a video connection (RTSP) directly to your camera on your local network.
- **Network state access** (`ACCESS_NETWORK_STATE`) — used to read your device's local network address range, so the optional "Scan Network for Cameras" feature can look for cameras on your own subnet. The scan contacts only addresses on your local network; it sends nothing outside it.
- **Wake lock** (`WAKE_LOCK`) — declared by the Android media playback library the app uses, to keep video playing smoothly. It grants no access to your data.

The optional "Find Camera Automatically" feature listens for cameras advertising themselves over mDNS on your local network. Like the subnet scan, it is initiated only when you tap it and never leaves your network.

## Demo Mode

A new install starts in Demo mode, which plays a short sample clip that is bundled inside the app itself. Demo mode needs no internet connection and contacts no server — ours or anyone else's.

## Third-Party Services

CargoView does not use any third-party analytics, advertising, or tracking SDKs.

## Children's Privacy

CargoView does not knowingly collect data from anyone, including children, because it does not collect data at all.

## Changes to This Policy

If this policy changes, the updated version will be posted at this same location with a revised "Last updated" date.

## Contact

Questions about this policy can be sent to Mark Shepherd, HYBRID LEARNING SOLUTIONS (PTY) LTD, at: shepherdmark1968@gmail.com
