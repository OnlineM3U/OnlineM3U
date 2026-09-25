# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [2.0.3] - 2026-09-25
### Added
- **Player Updates:** Added the ability to favorite content in the search screen. 

## [2.0.2] - 2026-09-24
### Fixed
- **Player Stability:** Hotfix to resolve a bug where specific .mkv (HEVC) streams would silently fail to hardware decode, causing infinite buffering without falling back to the software decoder.
- **Dashboard Crash:** Fixed an edge-case bug where the application would crash when attempting to render the dashboard history if a user watched a video on a fresh install.

## [2.0.1] - 2026-09-24
### Fixed
- **Stream Error Handling:** Minor hotfix to display specific troubleshooting steps and a direct resolution guide when users encounter "Mixed Content" (HTTP blocked) streams on the web platform.

## [2.0.0] - 2026-09-24
OnlineM3U 2.0 is our biggest update yet, bringing a complete UI redesign, a brand-new unified player, and massive feature additions designed to give you a premium, seamless streaming experience.

### Added
- **Complete UI Redesign:** Enjoy a fresh, modern, and highly intuitive interface across the entire application.
- **Brand New Unified Player:** A completely rebuilt video player delivering lightning-fast playback, built-in settings, and deep UI customizations to suit your preferences.
- **New Modular Dashboard:** A smarter, personalized dashboard giving you quick access to your content.
- **Dedicated Content Views:** Brand new, optimized browsing views specifically designed for Live TV, Series, and Movies.
- **Continue Watching & Favorites:** Seamlessly pick up exactly where you left off and easily save your favorite channels and movies for quick access.
- **Binge-Watching Ready:** Added Auto-play for series episodes and smart content suggestions after movies finish.
- **Language Settings:** Added dedicated language settings to customize your interface and content preferences.
- **Browser Extensions (Coming Soon):** We are excited to announce official browser extensions for Firefox and Chrome, arriving soon to guarantee CORS bypasses!
- **Auto-Updater for Web:** A new silent auto-updater ensures you are always running the latest, fastest, and most secure version of the web app without having to refresh.
- **New Guides & Tools:** Launched a comprehensive portal filled with new tutorials, setup guides, and IPTV tools.
- **Progressive Web App (PWA):** Install OnlineM3U directly to your desktop or mobile home screen for a fast, native app-like experience.
- **Chromecast Support:** Cast your favorite Live TV and movies directly to your TV with built-in Chromecast integration.
- **Social Sharing:** Easily share your favorite streams and content with friends using the new sharing modal.

### Changed
- **Immersive Watch Experience:** The player now features an auto-hide header and distraction-free layout, putting the focus entirely on your content.
- **Streamlined Navigation:** Reorganized menus and layouts for a faster, frictionless browsing experience on both desktop and mobile devices.

### Fixed
- **Stream Error Handling:** Improved automatic retries and error reporting for unreliable streams.
- **Player Visuals:** Fixed a visual glitch where the play/pause icon would incorrectly appear when hovering over the video.

## [1.2.0] - 2026-09-11
### Added
- **About Page:** Created a dedicated About Us page detailing the project's mission, core values, and client-side architecture.
- **Feedback & Support:** Added a "Report Bug / Request Feature" button in the sidebar linking directly to the GitHub issues tracker.

### Changed
- **UI Tweaks:** Resized the sidebar action buttons (Media Guides, Bug Report, Share) and adjusted their icons to lay inline with the text for a cleaner look. Swapped the order of the Share and Bug Report buttons.

## [1.1.1] - 2026-09-10
### Changed
- **Privacy Compliance:** Switched to Google's Consent Management Platform (CMP) for handling GDPR/CCPA cookie consent, removing the legacy custom cookie banner.

## [1.1.0] - 2026-09-09
### Changed
- **Ad-Free Experience:** Completely removed third-party banner ads from the sidebar and pre-roll video ads from the media player to provide a cleaner, uninterrupted streaming experience.
- **Improved Legal Navigation:** Moved Privacy Policy and DMCA information out of pop-up modals and onto their own dedicated, standalone pages for easier reading.
- **Updated Footer:** Revamped the site footer to include direct links to all new standalone pages.

### Added
- **Desktop Apps:** Launched native desktop applications for Windows, Mac, and Linux.
- **Terms of Service:** Added a dedicated Terms of Service page outlining the player's client-side, non-hosted nature.
- **Contact Page:** Added a dedicated Contact Us page for support and inquiries.
- **Playlist Caching:** Implemented local caching for built-in playlists to dramatically improve load times and reduce unnecessary network requests on subsequent visits.

## [1.0.0] - 2026-09-05
### Added
- Initial release.
