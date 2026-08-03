# Acceptrics's Google Tag Manager Template for Cookie Consent Management

Load Acceptrics's consent banner through Google Tag Manager. It loads the widget
and sets Google Consent Mode v2 defaults for you.

## Get your free Account ID

The template needs your **Acceptrics Account ID** so the banner is linked to your
account (your settings and usage are applied correctly).

Don't have one yet? It's free — no credit card required:

1. Go to **[acceptrics.com/wizard](https://acceptrics.com/wizard)**.
2. Enter your email and customize your banner.
3. Your **Account ID** (e.g. `b81d7rbl`) appears on the final step and is emailed
   to you.

Already have an account? Find your Account ID at
**[acceptrics.com/account](https://acceptrics.com/account)**.

## Set up the tag in Google Tag Manager

1. In your GTM container, create a new **Tag** and choose the **Acceptrics CMP**
   template.
2. Paste your **Account ID** into the *Acceptrics Account ID* field.
3. (Optional) Toggle **Advanced consent mode** and **Show banner only in EEA,
   Switzerland and the UK** to match your needs.
4. **Trigger:** fire this tag on **Consent Initialization – All Pages** so the
   consent defaults are set before any other tags run. (Firing it on *All Pages*
   sets the defaults too late.)
5. Publish your container.

Get started at [acceptrics.com](https://acceptrics.com).
