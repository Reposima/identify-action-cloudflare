
![](https://assets.capsolver.com/prod/images/post/2024-06-17/2923a211-5faa-4663-9b3d-27abf24dbb57.jpeg)
## How to Identify if `action` is Required to Solve Cloudflare Turnstile Using CapSolver Extension

### What is `action`?
`action` is a parameter used in Cloudflare Turnstile to specify the action being protected by the CAPTCHA. This parameter helps Cloudflare understand the context of the user’s interaction and ensures that the CAPTCHA is being used appropriately. It is a key component in determining the validity of a user's actions and helps enhance the accuracy of bot detection. This parameter can be required in certain implementations of Turnstile, depending on the specific security needs and configurations of the website.

### How to Identify if Cloudflare Turnstile is being used Using CapSolver Extension

### CAPTCHA Parameter Detection:

#### Identifiable Parameters for Cloudflare Turnstile:
* Website URL
* Site Key
* action (should have a value if it's required)
* cdata

Once the CAPTCHA parameters have been detected, CapSolver will return a JSON detailing how you should submit the CAPTCHA parameters to their service.

### How to Identify if Cloudflare Turnstile is being used:

1. **Open Developer Tools**:
   Press `F12` to open the developer tools or right-click on the webpage and select "Inspect".
 
2. **Open the CapSolver Panel**:
   Go to the Captcha Detector Panel.

3. **Trigger the Cloudflare Turnstile**:
   Perform the action that triggers the Cloudflare Turnstile on the webpage.

4. **Check the CapSolver Panel**:
   Look at the CapSolver Captcha Detector tab in the developer tools. If it's Cloudflare Turnstile, it will appear like:
   ![](https://assets.capsolver.com/prod/images/post/2024-06-11/a674a609-648e-4bf0-b3b7-5bc2142085c2.png)

By following these steps, you can easily determine if Cloudflare Turnstile is being used on a website.

### Conclusion:

Identifying whether Cloudflare Turnstile is being used with the CapSolver extension is straightforward. CapSolver not only helps you find the site key but also other essential parameters like `action` and `cdata`. Always use such tools responsibly and ethically, respecting the terms of service of the websites you interact with. For more assistance, you can contact CapSolver via email at [support@capsolver.com](mailto:support@capsolver.com).
