# HTTP Reject Workaround
This is a simple guide how to allow resources over HTTP when you load a page in your browser over HTTPS.

When trying to publish a website or an application on e.g. GitHub Pages, you may encounter the following error message in your `console`: "Mixed Content: The page at  `xxx`  was loaded over HTTPS, but requested an insecure resource `xxx`. This request has been blocked; the content must be served over HTTPS".

To fix this, simply add `https://cors-anywhere.herokuapp.com/` in front of your API call, like so `https://cors-anywhere.herokuapp.com/http://yourdomainname.com`.

Courtesy of [Rob Wu](https://github.com/Rob--W/cors-anywhere). Big thanks!
