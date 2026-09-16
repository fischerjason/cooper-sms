# Cooper SMS Opt-In Process

Cooper is a private personal AI assistant. SMS access is not offered to the general public.

## How Consent Is Provided

The owner explicitly authorizes a mobile phone number in Cooper's SMS configuration before that number is permitted to interact with the assistant.

Only explicitly authorized numbers are accepted by the SMS interface. Unrecognized phone numbers are not authorized to use Cooper.

The authorized user may then initiate a conversation by sending an SMS message to the Cooper phone number.

## Authorized Recipient Configuration

Cooper maintains an allowlist containing the mobile number permitted to use the SMS interface.

Example configuration:

    SMS_ALLOWED_USERS=+1XXXXXXXXXX
    SMS_HOME_CHANNEL=+1XXXXXXXXXX

The example above is intentionally redacted. The production configuration contains the owner's authorized mobile number.

## Types of Messages

After authorization, Cooper may send:

- Conversational responses to messages initiated by the authorized user
- Reminders requested by the authorized user
- Notifications and alerts requested or configured by the authorized user
- Other personal AI assistant responses requested by the authorized user

Cooper does not send advertising, promotional messages, lead-generation messages, or marketing campaigns.

## Opt Out

The authorized user may reply STOP to stop receiving SMS messages.

The user may reply HELP for assistance.

## Privacy

Mobile information and SMS consent information are not sold or shared with third parties for marketing or promotional purposes.

See the Cooper Privacy Policy for additional information.
