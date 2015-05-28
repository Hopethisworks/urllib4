urllib style HTTP/FTP client library base on pycurl

## Features ##
  * compatible with urllib2.urlopen
  * identical behavior for http:// and https:// urls
  * progress meters - the ability to report download progress automatically
  * HTTP redirect with 301 and location header
  * HTTP authentication with Basic, Digest and NTLM etc
  * proxy support - support for authenticated http and socks 4/5 proxies
  * hierarchical exception structure
  * local DNS cache
  * connect and operation timeout
  * page encoding - guess HTML page encoding base on HTTP header, meta tag and text
  * page modified - guess HTML page modified base on ETag, Last-Modified and MD5
  * connection pool - batched downloads multiple files simultaneously

## TODO List ##
  * identical behavior for ftp://, and file:// urls
  * DNS timeout and prefetch
  * page content cache - base on the HTTP cache strategy
  * web browser simulator with profile
  * http keepalive - faster downloads of many files by using only a single connection
  * byte ranges - fetch only a portion of the file
  * reget - for a urlgrab, resume a partial download
  * MIME type - guess MIME type base on the content header
  * throttling - restrict bandwidth usage and IP/domain based flow control
  * multihoming IP round robin
  * retries - automatically retry a download if it fails.
  * fast fail - reschedule failed http request base on IP/domain
  * authenticated server access for http and ftp
  * cookie management
  * certification/CA management
  * CDN bypass
