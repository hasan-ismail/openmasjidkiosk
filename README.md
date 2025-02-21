# openmasjidkiosk
A easy and comprehensive Guide on making a masjid Donation kiosk with no monthly charges
# 📖 Stripe Donation Setup Guide

This guide will walk you through setting up a Stripe M2 reader with Give A Little for accepting donations at your masjid.

<a href="https://www.buymeacoffee.com/hasanismail" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png" alt="Buy Me A Coffee" style="height: 60px !important;width: 217px !important;" ></a>

## 🏦 Stripe Fees
Stripe charges standard fees for transactions:
- **Regular Account:** 2.9% + $0.30 per transaction
- **Nonprofit Account (for Masjids):** 2.2% + $0.30 per transaction *(if successfully verified as a nonprofit)*

## 🛠️ Step 1: Choose Your Hardware
You will need:
- A **Stripe M2 Reader** (purchase from the official Stripe store)
- An **Android device** (phone or tablet). Recommended device: [15 inch wall mount Android Tablet](https://www.amazon.com/dp/B0CQS3VN1T?ref=fed_asin_title&th=1)

## 📲 Step 2: Sign Up for Give A Little
1. Go to [Give A Little](https://givealittle.co) and create an account.
2. Submit the required documents for approval.
3. Once approved, download the **Give A Little** app on your Android device.
4. Log in to the **Give A Little** dashboard and create a campaign.
5. Select your campaign in the app and set the donation amounts.

**Note:** Give A Little is a freemium service. The free plan allows up to **$1,200** in donations per month without additional transaction fees. Higher limits require a paid plan.

## 🔒 Step 3: Lock Down the Android Device
To prevent users from exiting the donation app, we will use a kiosk mode application.

1. Download **Fully Single App Kiosk** from the Play Store: [Download Here](https://play.google.com/store/apps/details?id=com.fullykiosk.singleapp&hl=en_US&pli=1)
2. Purchase the app (one-time payment).
3. Configure it to lock the device to the **Give A Little** app.

## 🎉 Step 4: Test & Deploy
1. Run test donations to ensure everything works.
2. Once verified, set up the device at your masjid and start accepting donations.
🔧 Troubleshooting

If you run into issues, here are some common troubleshooting steps:

🛑 Stripe Reader Not Connecting

- Ensure the Stripe M2 Reader is fully charged.

- Check that Bluetooth is enabled on your Android device.

- Restart both the Stripe M2 Reader and the Android device.

- Make sure the Give A Little app has the necessary permissions (Bluetooth, Location, etc.).

⚠️ Payments Not Processing

- Verify that your Stripe account is active and properly linked.

- Double-check that the campaign is correctly set up in the Give A Little dashboard.

- Ensure that your internet connection is stable.

- Try reinstalling the Give A Little app if issues persist.

🔒 Kiosk Mode Not Working

- Ensure that Fully Single App Kiosk is correctly installed and activated.

- Restart the Android device after enabling kiosk mode.

- Check if the app has the required device admin permissions.

Now you're all set! 🕌✨

