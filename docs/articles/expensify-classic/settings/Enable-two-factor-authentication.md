---
title: Enable Two-factor authentication
description: Use 2FA for extra login security 
---
<div id="expensify-classic" markdown="1">

Add an extra layer of security to help keep your financial data safe and secure by enabling two-factor authentication (2FA). This will require you to enter a code generated by your preferred authenticator app (like Google Authenticator or Microsoft Authenticator) when you log in.

Expensify's Two-Factor Authentication (2FA) is implemented via a Time-based One-Time Password (TOTP) algorithm. This requires you to use an Authenticator app to generate a unique code each time you log in, adding a second “factor” to your login.

You can choose to use whichever authenticator you prefer, but here are a few we recommend:
- [1Password](https://support.1password.com/one-time-passwords/)
- [Authy](https://authy.com/)
- [Google Authenticator](https://support.google.com/accounts/answer/1066447)
- [Microsoft Authenticator](https://www.microsoft.com/en-us/security/mobile-authenticator-app)

You will need to select an authenticator app to use before proceeding.

## Enable and Set Up Two-factor authentication

1. Hover over Settings, then click **Account**.
2. Under the Account Details tab, scroll down to the Two Factor Authentication section and enable the toggle.
3. Save a copy of your backup codes. 
   - Click **Download** to save a copy of your backup codes to your computer.
   - Click **Copy** to paste the codes into a document or other secure location. 

{% include info.html %}
This step is critical—You will lose access to your account if you cannot use your authenticator app and do not have your recovery codes.  
{% include end-info.html %}

4. Click **Continue**. 
5. Download or open your authenticator app and either:
   - Scan the QR code shown on your computer screen. 
   - Enter the 6-digit code from your authenticator app into Expensify and click **Verify**.

When you log in to Expensify in the future, you’ll be emailed a magic code that you’ll use to log in with. Then you’ll be prompted to open your authenticator app to get the 6-digit code and enter it into Expensify. A new code regenerates every few seconds, so the code is always different. If the code time runs out, you can generate a new code as needed.

## Lost recovery codes and authenticator app

If you have lost your mobile device and can’t find your recovery codes, your Domain Admin can complete the steps below to reset your 2FA **only if (1) you use a company email address or email address on a domain that you own and (2) the Domain Admin also has 2FA enabled**:

If your domain has 2FA enabled, a domain admin can follow Settings > Domains > Domain Members and click **Edit Settings** for your email address. 
They can then click **Reset** to reset two-factor authentication (2FA) on your account. This will allow you to gain access to your account on the web or mobile app and configure 2FA again.

If your domain does not have 2FA enabled, a domain admin can follow Settings > Domains > Domain Members and enable Two Factor Authentication. Then they can follow the previously mentioned steps to reset 2FA for your account.

{% include info.html %}
If you use a public email address such as gmail, hotmail, or yahoo, we unfortunately can’t help you disable your 2FA setting. If you are unable to find your recovery codes, you may need to create a new Expensify account with a different email address. 
{% include end-info.html %}

If you don’t have a Domain Admin, follow the steps in this [guide](https://help.expensify.com/articles/expensify-classic/domains/Claim-And-Verify-A-Domain) to verify the domain. 

## General troubleshooting

Make sure your phone’s time is set to automatically update (a manual time that’s fractionally different can cause issues).
Try disabling 2FA using a device that you are still logged into. For example, if you’re having trouble logging in with your computer, try to see if your mobile device is still logged in. If so,
Hover over Settings, then click Account.
Under the Account Details tab, scroll down to the Two Factor Authentication section and disable the toggle.
Try logging in with your other device. 
Once you’ve logged in again, you can re-enable 2FA.

</div>
