# StaffBar Extension
If you're ready to give our extension a try, please reach out and we'll get you setup! `brian@staffbar.com`


## Installation

0. Download the extension & unzip
1. Visit `chrome://extensions`
2. Enable Developer mode in the top right
3. Press `Load Unpacked` in the top left
4. Select the unziped build


## Getting Started

1. Once installed, visit a page you would like to inspect
2. Use the shortcut `cmd+shift+s` or click the extension icon in the chrome menu to activate StaffBar
3. You should see requests appear, use the mouse to click (or j/k then enter) to select a request
4. (Optionally expand the window with `z`) and edit the requets
5. Replay the request with `r` or the "reload" icon in the center of the screen.


## Known Limitations

- Right now our extension only works with `fetch` but we're adding `XMLHttpRequest` support soon. 
- Rendering on some sites will not work as expected if they have a floating navigation bar. 

## Changelog 

### 0.0.3 - 6/2/21
- Handles uncaught error in trying to post message from background to content
- Narrowed permissions required to `activeTab` and `<all_urls>`

### 0.0.2 - 6/2/21
- Moved activate of the extension to a browser action, by default StaffBar is now hidden
- Cleaned up console.log & source map noise. 
- Submitted to the Chrome Web App Store

### 0.0.1 - 6/1/21
- Initial release 🎉


