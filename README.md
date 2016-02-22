# Bitrise Engineering Blog

We decided to share some insights about our daily engineering at [Bitrise](https://bitrise.io) frequently. This repository holds the code behind the blog itself.

> If you have questions/suggestions/compliments/concerns about content, please find the specific article on the blog itself and leave a comment, or find us by [email](mailto:letsconnect@bitrise.io), on [Twitter](https://twitter.com/bitrise), or on our public [Slack](chat.bitrise.io).

## Tech

This blog is a [Heroku](https://www.heroku.com/) app, running a [Ghost blog](https://ghost.org/) engine. To setup Ghost on Heroku with a click of a button, check out [ghost-on-heroku](https://github.com/cobyism/ghost-on-heroku). That's the repo we forked to create this blog as well.

### Monitoring

We connected a [New Relic](http://newrelic.com/) app to monitor our blog's performance and outages.

### Theme

Ghost's default theme [Casper](https://github.com/TryGhost/Casper) looks pretty minimal which we are a huge fan of, so we decided to use that with a hint of Bitrise sprinkled on the css.

### Comments

We are using [Disqus](https://disqus.com/) to handle user comments. They are channeled to the [Bitrise forum on Disqus](https://disqus.com/home/forums/bitrise/).

### Subscription

Handling newsletter subscription with [MailChimp](https://mailchimp.com).

## Contact

Have a question, a bug, or an unexpected error? Find us on [Twitter](https://twitter.com/bitrise), join our public [Slack](chat.bitrise.io), or shoot us an [email](mailto:letsconnect@bitrise.io) to share.
