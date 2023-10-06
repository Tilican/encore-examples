# Slack Bot Starter

This is an Encore starter application for a Slack bot. It brings the greatness of the cowsay utility to Slack!

## Build from scratch with a tutorial

If you prefer to built it yourself, check out the [written tutorial](https://encore.dev/docs/tutorials/slack-bot) to learn how to build this application from scratch.

## Developing locally

When you have [installed Encore](https://encore.dev/docs/install), you can create a new Encore application and clone this example with this command.

```bash
encore app create my-app-name --example=slack-bot
```

## Running locally

```bash
# To use the Slack integration, set the Slack signing secret (see tutorial above).
encore secret set SlackSigningSecret

$ encore run
```

## Open the developer dashboard

While `encore run` is running, open <http://localhost:9400/> to access Encore's [local developer dashboard](https://encore.dev/docs/observability/dev-dash).
Here you can see API docs, make requests in the API explorer, and view traces of the response.

## Deployment

Deploy your application to a staging environment in Encore's free development cloud:

```bash
git push encore
```

Then head over to the [Cloud Dashboard](https://app.encore.dev) to monitor your deployment and find your production URL.

From there you can also connect your own AWS or GCP account to use for deployment.

Now off you go into the clouds!