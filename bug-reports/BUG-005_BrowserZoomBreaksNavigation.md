# BUG-005: Website Navigation Breaks at Browser Zoom Levels Above 150%

## Summary
The website navigation becomes unusable when the browser zoom level reaches 175% or greater.

## Environment
- Application: Indian Creek Cycles
- Browser: (Enter browser used, e.g., Google Chrome)
- Browser Zoom: 175%
- OS: (Optional)

## Severity
Medium

## Priority
Medium

## Steps to Reproduce
1. Open the Indian Creek Cycles website.
2. Increase the browser zoom level to 175%.
3. Observe the website navigation.

## Expected Result
The website should remain fully functional and navigable at increased browser zoom levels.

## Actual Result
The website remained usable up to 150% zoom. At 175% zoom:
- The navigation bar disappeared.
- The hamburger menu no longer functioned.
- Clicking the logo no longer returned the user to the homepage.

## Impact
Users who rely on increased browser zoom may be unable to navigate the website.

## Evidence
BUG-005_175PercentZoom.png

## Status
Open
