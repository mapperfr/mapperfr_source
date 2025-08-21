---
title: "How to move your Mastodon account to another instance"
author: Jérémy Garniaux
type: post
date: 2023-10-31
categories:
  - blog
tags:
  - mastodon
  - tutorial
---

Here are the steps to follow to move your Mastodon account to another instance - and to join us at https://mapstodon.space, for example!

- On your old account, go to **Preferences** > **Import and export** > **Request your archive**. After a little moment, you will be able to download the ZIP archive that has been created (you can also wait to receive the email informing you that your archive is ready). You will use this later to re-import certain data that has not been transferred.

- Create a new account on the instance you want to join. If it is an instance that manually validates registrations, such as Mapstodon.Space, you will have to wait for your account to be validated before moving on to the next step.

- In this new account, add an "alias" to your old account on another instance. In **Preferences** > **Account** > **Move from a different account** (at the bottom of the page) > **Create an account alias**, enter the address of your old account.

![](albums/carnet/mastodon-migration/mastodon-migration-en-1.png)

- From your old account, go to **Preferences** > **Account** > **Move *to* a different account**:

![](albums/carnet/mastodon-migration/mastodon-migration-en-2.png)

Once this setting is configured, all of your subscribers will also be subscribed to the new account (I believe they'll remain subscribed to the old one, but I'm not sure. Feel free to give me some feedback if you follow this tutorial!). For everything else — your subscriptions, blocked or hidden contacts, for example — you'll need to reimport the data.

To do this, go to **Preferences** > **Import and Export** > **Import Data**, and upload the file you downloaded in the first step. Processing this file may take some time, so it's normal if your old subscriptions don't appear immediately. Similarly, if some accounts you were subscribed to don't automatically accept new subscription requests, you'll have to wait for them to approve the request before you can find them in your subscription list.

You can then choose to delete the old account or keep it — I suggest the former option for greater clarity for your subscribers. In the meantime, your old account will be greyed out and a redirect message will inform visitors that you have migrated to a new instance.
