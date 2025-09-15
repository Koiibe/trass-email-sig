# Email Signature Template

A clean, professional, and customizable HTML email signature template that works across all major email clients.

## Features

- 📱 **Responsive Design**: Looks great on desktop and mobile devices
- 🎨 **Customizable Styling**: Easy to modify colors, fonts, and layout via CSS variables
- 🖼️ **Logo Support**: Integrated company logo with proper scaling
- 🔗 **Professional Links**: Clean website and contact information display
- 📧 **Email Client Compatible**: Works with Gmail, Outlook, Apple Mail, and more

## Quick Start

1. **Download the template**: Save `email-signature-template.html` to your computer
2. **Replace the placeholders** with your information:
   - `{{FULL_NAME}}` - Your full name
   - `{{EMAIL_ADDRESS}}` - Your email address
   - `{{PHONE_NUMBER}}` - Your phone number
   - `{{WEBSITE_URL}}` - Full URL to your website (e.g., https://example.com)
   - `{{WEBSITE_DISPLAY}}` - Display text for website (e.g., example.com)
   - `{{LOGO_URL}}` - Direct URL to your logo image
   - `{{COMPANY_NAME}}` - Your company name (used for logo alt text)

3. **Open in browser** and copy the rendered signature to your email client

## Preview

![Trass Logo](./Trass%20Lockup%20Funnel.svg)

*Example logo used in the email signature template*

## Customization

### Colors and Styling

The template uses CSS custom properties (variables) that you can easily modify:

```css
:root {
  --signature-font: "Inter", -apple-system, BlinkMacSystemFont, "Segoe UI", sans-serif;
  --signature-color: #2d3748;      /* Main text color */
  --border-color: #e2e8f0;         /* Border color between logo and text */
  --logo-width: 60px;              /* Logo container width */
}
```

### Fonts

To change the font:
1. Update the Google Fonts import URL in the `<style>` section
2. Modify the `--signature-font` variable with your chosen font family

### Logo Requirements

For best results, your logo should be:
- **Format**: PNG with transparent background (recommended) or JPG
- **Size**: Maximum 200px width, 100px height
- **Aspect Ratio**: Horizontal or square logos work best
- **Hosting**: Must be publicly accessible (consider GitHub, Imgur, or your website)

## Installation in Email Clients

### Gmail
1. Open the HTML file in your browser
2. Select all (Ctrl/Cmd + A) and copy (Ctrl/Cmd + C)
3. In Gmail: Settings → General → Signature → Create New
4. Paste your signature

### Outlook (Desktop)
1. Open the HTML file in your browser
2. Copy the rendered signature
3. In Outlook: File → Options → Mail → Signatures
4. Create new signature and paste

### Outlook (Web)
1. Copy the rendered signature from browser
2. Settings → Mail → Compose and reply → Email signature
3. Paste your signature

### Apple Mail
1. Copy the rendered signature from browser
2. Mail → Preferences → Signatures
3. Create new signature and paste

## File Structure

```
email-signature-template/
├── email-signature-template.html    # Main template file
├── example-signature.html           # Example with sample data
├── Trass Lockup Funnel.svg         # Trass company logo
├── placeholder-logo.svg            # Sample logo placeholder
└── README.md                        # This file
```

## Troubleshooting

### Images Not Showing
- Ensure your logo URL is publicly accessible
- Try opening the logo URL directly in a browser
- Some email clients block external images by default

### Formatting Issues
- Different email clients may render HTML slightly differently
- Test your signature by sending yourself an email
- Keep styling simple for better compatibility

### Mobile Responsiveness
- The template is optimized for mobile viewing
- Test on various devices to ensure proper display

## Contributing

Feel free to submit issues or pull requests to improve this template!

## License

This template is free to use for personal and commercial purposes.
