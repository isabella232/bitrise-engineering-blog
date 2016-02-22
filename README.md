# Bitrise Engineering Blog

We decided to share some insights about our daily engineering at [Bitrise](https://bitrise.io) frequently. This repository holds the code behind the blog.

> If you have any questions/suggestions/compliments/concerns about content, please find the specific article on the blog itself and leave a comment, or find us by [email](mailto:letsconnect@bitrise.io), on [Twitter](https://twitter.com/bitrise), or on our public [Slack](chat.bitrise.io).

## Tech

This blog is a [Heroku](https://www.heroku.com/) app, running a [Ghost blog](https://ghost.org/) engine. To setup Ghost on Heroku with a click of a button, check out [ghost-on-heroku](https://github.com/cobyism/ghost-on-heroku). That's the repo we forked to create this blog as well.

### Monitoring

We connected a [New Relic](http://newrelic.com/) app to monitor our blog's performance and outages. Heroku has an add-on for New Relic, so it's straightforward to integrate. Check out the [guides how to use them together](https://docs.newrelic.com/docs/agents/nodejs-agent/hosting-services/nodejs-agent-heroku).

### Theme

Ghost's default theme [Casper](https://github.com/TryGhost/Casper) looks pretty minimal which we are huge fan of, so we decided to use that with a hint of Bitrise sprinkled on the css.

### Comments

We are using [Disqus](https://disqus.com/) to handle user comments. They are channeled to the [Bitrise forum on Disqus](https://disqus.com/home/forums/bitrise/). It's pretty easy to set up, just follow the guides about [how to add Disqus to Ghost blog](http://support.ghost.org/add-disqus-to-my-ghost-blog/).

### Subscription

Handling newsletter subscription with [MailChimp](https://mailchimp.com). Here's a great tutorial about [how to setup MailChimp on a Ghost blog](http://support.ghost.org/setup-email-subscriptions-mailchimp/), that's what we followed as well.

## Contact

Have a question, a bug, or an unexpected error? Find us on [Twitter](https://twitter.com/bitrise), join our public [Slack](chat.bitrise.io), or shoot us an [email](mailto:letsconnect@bitrise.io) to share.
