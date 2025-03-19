# reCAPTCHA Token Generator

This page provides a simple way for users to generate and test reCAPTCHA v3 tokens. If you want to use this service for testing, please follow the steps below.

## How to Use This Token Generator

### 1. Add This Domain to Your reCAPTCHA Settings

To ensure reCAPTCHA works correctly, you must register your site with Google and include **this GitHub page domain** in your allowed domains.

- Go to [Google reCAPTCHA Admin Console](https://www.google.com/recaptcha/admin/create).
- Choose **reCAPTCHA v3**.
- Enter your own domain **and also include this GitHub page domain:**.

```
wildanmzaki.github.io
```

- Accept the terms and register.
- Copy the **Site Key** and **Secret Key** for use in testing.

### 2. Understanding How This System Works

- This page uses **Google reCAPTCHA v3** to generate a token when a user interacts with the site.
- When you perform an action, the system will automatically request a reCAPTCHA token from Google.
- You can then use this token for verification on your backend system.
- The purpose of this page is to help simulate the token generation process for testing and debugging.

### 3. Test the Token Generator

You can test generating a reCAPTCHA token by visiting **[this GitHub Page](https://wildanmzaki.github.io/recaptcha-token-generator/)**.

Once there, follow the on-screen instructions to generate a token and use it in your own system.

## Additional Notes

- Make sure your **Site Key and Secret Key** are correctly set up in your Google reCAPTCHA admin panel.
- If you encounter errors, check that you have added **this GitHub page domain** to your reCAPTCHA settings.
- This page is designed for **testing and educational purposes** only.

## License

This project is open-source under the MIT License.
