# WAWeb
An Android application to use WhatsApp Web feature on Android smartphone.

This project is just a demonstration of user agent tweaks in Android WebView.

It loads `https://web.whatsapp.com` in android WebView using User agent `Mozilla/5.0 (X11; U; Linux i686; en-US; rv:1.9.0.4) Gecko/20100101 Firefox/34.0`

## Known issue
Before `Android KIT_KAT (API 19)`, The WhatsApp web QR screen loads first time only.
after that WhatsApp Web detects the user agent and so, it redirects to whatsapp home page on app launched next time.
A workaround is to clear app data from `Settings> App info> WAWeb> Clear Data`.
