# qrsnap.io-CDN
QR Snap hosts a CDN (Content Delivery Network) for QR Snap website integration tools. There are multiple QR Snap tools such as Snapalytics, SnapURL, Facebook Pixel, Google Analytics that all can be sideloaded with JavaScript and CSS from our CDN. Our core business always takes into account the cost of every action and mitigates all issues with the inclusion of our .js and .css files. For those with a technical background, these files are loaded asynchronously so that the impact if the script is blocked or unreachable is zero. In those cases the additional QR Snap functions will not function but your business website will continue to operate at maximum performance.

# QR Snap CSS inclusion
The optimization of CSS inclusion to your stores website is critical. To do this follow this structure.

##CSS
'''
<link rel="stylesheet" href="https://qrsnap.io/cdn/<your business>/css/<your file>.css" media="SnapSync" onload="this.media='all'">
'''
