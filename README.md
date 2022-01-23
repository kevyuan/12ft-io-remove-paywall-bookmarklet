# 12ft.io Remove Paywall Bookmarklet

A simple bookmarklet to remove a paywall from an URL.

## Description

This bookmarklet does the following:
* Takes the URL in the current window
* Prepends "https://12ft.io" to the URL
* Opens it in the same window -- and with the paywall removed from the page

Warning: The page will be modified by 12ft.io. I am not familiar with the data collection policy from 12ft.io. Use at your own discretion. 

## Getting Started

### Dependencies
* Any modern browser (i.e. Firefox, Chrome, Edge, Safari)

### Installation

#### Method 1: Click and drag
1. Drag this "<a href="javascript:(()=>{window.open('https://12ft.io/'+window.location.href,'_self')})();">Remove Paywall</a>" link onto your bookmarks bar
2. If the above link does not show, go [here](https://kevyuan.github.io/12ft-io-remove-paywall-bookmarklet/) first

#### Method 3: Manually create new bookmark
1. Create a new bookmark using this code block:

```
javascript: (() => {
    window.open("https://12ft.io/" + window.location.href, "_self")
})();
```

## Usage
1. Go to a [URL](https://www.economist.com/briefing/2016/04/16/spectrum-shift) with a paywall
2. Click on the bookmarklet

## Authors
Kevin Yuan - [@kevyuan](https://twitter.com/kevyuan)


## License
Distributed under the MIT License. See the 'LICENSE' for more information.

## Acknowledgments
* Thank you to [12ft.io](https://12ft.io/) for providing the service
