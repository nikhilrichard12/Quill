# Microsoft 365 admin setup · Littlebird docs

Source: https://support.littlebird.ai/docs/microsoft-365/
Fetched: 2026-07-27

---

Features · Integrations

# Microsoft 365 admin setup
Connect Littlebird across a Microsoft 365 organization, with a clear view of the Graph permissions your admin is approving.

Littlebird connects to Outlook mail and calendar through Microsoft Graph. An administrator can approve the integration for the organization while the Microsoft Store listing is in progress.

## Microsoft Store listing status

The Microsoft Store review is underway, but there is no confirmed completion date.

## The quick workaround (admin consent)

In the meantime, a Global Administrator can grant consent directly:

Note

https://login.microsoftonline.com/common/adminconsent?client_id=ce10f26e-efc7-41e0-9e0e-fdf552ef025f&redirect_uri=https://app.lilbird.co/integrations/outlook/admin-consent

This adds Littlebird to Enterprise Applications and grants organization-wide admin consent.

## What access we’re requesting

Littlebird requests 16 delegated Microsoft Graph permissions:

Permission
What it’s for

Calendars.Read
Read user’s calendar

Calendars.Read.Shared
Read shared calendars

Calendars.ReadBasic
Read basic calendar details

Calendars.ReadWrite
Read/write user’s calendar

Contacts.Read
Read user’s contacts

Contacts.Read.Shared
Read shared contacts

Mail.Read
Read user’s emails

Mail.Read.Shared
Read shared mailboxes

Mail.ReadBasic
Read basic email info

Mail.ReadBasic.Shared
Read basic shared mail

Mail.Send
Send email as the user

MailboxSettings.Read
Read mailbox settings

offline_access
Maintain access via refresh token

User.Read
Sign in and read user profile

email
View user’s email address

profile
View basic profile

## Delegated permissions only

All of these are 100% delegated permissions - we use zero application permissions. Per Microsoft’s own documentation, delegated permissions mean the app acts on behalf of the signed-in user and can only access what that specific user can access.

## Check your tenant consent settings

In Microsoft Entra, it’s possible to configure a tenant to block users from providing consent. You can check this under:

Enterprise Applications → Security → Consent and permissions → User consent settings

Make sure that “Do not allow user consent” is not selected. Instead, set it to “Let Microsoft manage your consent settings”.

## Related Microsoft documentation

- Grant tenant-wide admin consent to an application - what the admin consent link above does, and how to do the same from the Entra admin center if you’d rather not use the direct URL.

- Configure how users consent to applications - relevant only if you’d prefer to let individual users consent for themselves instead of granting org-wide consent.

← Previous
Slack (coming soon)
Next →
Hummingbird
