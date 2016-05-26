**"rss-to-tweet"** is a simple Perl script to grab items from an RSS feed and
post them to Twitter.  Each time the script is run (typically from a cron job)
it looks for one recent item from the feed that it hasn't seen before and if it
finds one, posts it to Twitter.

You'll need to copy/rename the "rss-to-tweet.config-sample" file to
"rss-to-tweet.config" and then edit to suit.  There are comments in the sample
file to help you set it up.

The first time you run the script it will give you a URL for authorising the
Twitter app and will prompt you to enter the PIN which will be supplied when
you click the URL.

For more details, run:

    ./rss-to-tweet --help

