# Cooper SMS Opt-In Process

Cooper is a private automation and notification system used only by its owner and administrator. SMS enrollment is not offered to the general public.

## How Consent Is Provided

The owner explicitly chooses to enable SMS notifications and manually adds their own mobile phone number to Cooper's authorized outbound SMS allowlist.

A phone number is not added to the allowlist until the owner has affirmatively chosen to receive SMS notifications from Cooper.

Cooper will only send SMS messages to telephone numbers explicitly authorized in this configuration. Numbers that are not authorized are rejected by the outbound messaging system.

There is no public signup form and no keyword-based opt-in for this campaign.

## Authorized Recipient Configuration

Cooper maintains an outbound SMS allowlist containing the mobile numbers that have explicitly opted in.

Example sanitized configuration:

COOPER_OUTBOUND_ALLOWED_NUMBERS=+1XXXXXXXXXX

The example above is intentionally redacted. The production configuration contains the owner's explicitly authorized mobile number.

The owner is currently the sole SMS recipient.

## Types of Messages

After SMS notifications are enabled, Cooper may send:

- Reminders requested by the owner
- Notifications when monitored conditions change
- Operational alerts from configured integrations
- Etsy order or business activity notifications
- Printer or automation status notifications
- Notifications when requested tasks complete
- Other event-driven notifications configured by the owner

Cooper does not send advertising, promotional messages, lead-generation messages, or third-party marketing messages.

Message frequency varies based on requested reminders and system activity. Message and data rates may apply.

## Opt Out and Help

The recipient may reply STOP at any time to stop receiving SMS messages.

The recipient may reply HELP for assistance.

## Privacy and Terms

Mobile information and SMS consent information are not sold or shared with third parties or affiliates for marketing or promotional purposes.

Privacy Policy:
https://fischerjason.github.io/cooper-sms/privacy.html

Terms and Conditions:
https://fischerjason.github.io/cooper-sms/terms.html
