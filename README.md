# StaffBar Extension
If you're ready to give our extension a try, please reach out and we'll get you setup! `brian@staffbar.com`


## Instructions

0. Download the extension & unzip
1. Visit `chrome://extensions`
2. Enable Developer mode in the top right
3. Press `Load Unpacked` in the top left
4. Select the unziped build

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

## Known Limitations

Right now our extension only works with `fetch` but we're adding `XMLHttpRequest` support soon. 
