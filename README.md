# CyberScheild_Project
CyberShield is a Manifest V3 Chrome extension that protects users from malicious websites and files in real time. A background service worker listens to web navigation and tab events and checks each page against the VirusTotal threat-intelligence API. 

It uses debouncing, retry and rate-limit handling, and a one-hour result cache to keep scans fast. Unsafe sites are blocked before they load: the user sees a warning page that shows the blocked URL and how many security engines flagged it, with a “Go Back” button and an option to add the site to a custom exceptions list. 

A colour-coded badge shows each tab’s scan status (scanning, safe or unsafe), and desktop notifications alert the user to threats. The popup has two tabs: a Website Check for on-demand URL scans, and a File Check that supports drag-and-drop uploads of PDF, Word, image, video, APK and EXE files for malware analysis. The popup also has light and dark themes and an AI assistant panel. Built with JavaScript, the Chrome Extensions API, HTML/CSS and the VirusTotal API v3.
