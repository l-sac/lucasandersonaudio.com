# lucasandersonaudio.com

## Contact form

The static contact page uses Web3Forms to deliver inquiries. The visitor's email is the reply-to address.

1. In the [Web3Forms dashboard](https://app.web3forms.com/), create a form for the studio inbox and select **hCaptcha** under **Block Spam**. This setting makes Web3Forms verify each submission before forwarding it.
2. Paste the form's **public access key** into the `access_key` input in `contact.html`. The page displays an unavailable message while the key is empty.
3. Publish the updated page. Send an inquiry through it, check that the thank-you page opens, and confirm receipt in the studio inbox.
4. After confirming delivery, request deactivation of the old form under **Is it possible to deactivate forms that I don't use anymore?** on the [FormSubmit help page](https://formsubmit.co/help). Follow the link emailed to the studio inbox. This closes the old submission route for senders who saved its address.
