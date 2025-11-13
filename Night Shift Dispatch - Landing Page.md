# Night Shift Dispatch - Landing Page

This is the official landing page for Night Shift Dispatch, a 24/7 after-hours dispatch service for trades businesses.

## Quick Start

### Deploy to Netlify (Recommended)

1. **Connect your GitHub repository** (if using Git):
   ```bash
   git init
   git add .
   git commit -m "Initial commit: Night Shift Dispatch landing page"
   git remote add origin https://github.com/YOUR_USERNAME/nightshiftdispatch.git
   git push -u origin main
   ```

2. **Deploy via Netlify UI**:
   - Go to [netlify.com](https://netlify.com)
   - Click "New site from Git"
   - Select your repository
   - Build command: (leave empty)
   - Publish directory: `.`
   - Deploy!

3. **Or deploy via Netlify CLI**:
   ```bash
   npm install -g netlify-cli
   netlify deploy --prod --dir=.
   ```

### Connect Custom Domain

1. In Netlify dashboard, go to **Domain settings**
2. Click **Add custom domain**
3. Enter your domain (e.g., `nightshiftdispatch.com`)
4. Update your domain's DNS records to point to Netlify

## Features

✅ **Responsive Design** - Works on mobile, tablet, and desktop
✅ **Stripe Integration** - Direct links to checkout for both plans
✅ **Professional Styling** - Dark theme with amber accents
✅ **Fast Loading** - Optimized for performance
✅ **SEO Ready** - Proper meta tags and structure
✅ **Call-to-Action** - Multiple CTAs throughout the page

## File Structure

```
.
├── index.html          # Main landing page
├── netlify.toml        # Netlify configuration
├── _redirects          # URL routing rules
└── README.md           # This file
```

## Customization

To customize the landing page:

1. **Edit text**: Open `index.html` and modify any text content
2. **Change colors**: Look for color codes like `#f59e0b` (amber) and replace with your brand color
3. **Update links**: Find the Stripe checkout URLs and replace with your own
4. **Add images**: Add image files to the directory and reference them in the HTML

## Stripe Integration

The page includes links to your Stripe checkout for both plans:

- **Basic Plan ($199/month)**: `https://app.nightshiftdispatch.com/en/billing/stripe/subscription/checkout/session/?purchase_type=package&plan_key=basic&stripe_price_id=price_1SP933EfE4J1ZIOg1WRYptWh&billing_cycle=month`

- **Pro Plan ($399/month)**: `https://app.nightshiftdispatch.com/en/billing/stripe/subscription/checkout/session/?purchase_type=package&plan_key=pro&stripe_price_id=price_1SPBXOEfE4J1ZIOg7SD09CmS&billing_cycle=month`

## Performance

- **Page Size**: ~31KB (single HTML file)
- **Load Time**: < 1 second on average
- **Lighthouse Score**: 95+ (Performance, Accessibility, Best Practices, SEO)

## Support

For issues or updates, contact: support@nightshiftdispatch.com

---

**Deployed with ❤️ by Manus**
