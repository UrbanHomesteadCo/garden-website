# GardenWise Setup Guide 🌱

Complete instructions to get your site live and making money.

---

## STEP 1: Affiliate Program Setup (15 minutes)

### Amazon Associates (RECOMMENDED - Easiest)
1. Go to: https://amazon.com/associates
2. Sign up with your Amazon account
3. Get your **Tracking ID** (looks like: `gardenwise-20`)
4. In `config.js`, replace `YOUR_AMAZON_ASSOCIATE_ID` with your tracking ID
5. Update all product URLs with your tracking ID

**Example URL format:**
```
https://amazon.com/s?k=garden+tools&tag=YOUR_TRACKING_ID
```

### ShareASale (Optional - More Programs)
1. Go to: https://www.shareasale.com
2. Sign up and get approved
3. Find garden/outdoor merchants
4. Get your affiliate links
5. Add to products in `config.js`

### CJ Affiliate (Optional)
1. Go to: https://www.cj.com
2. Similar process to ShareASale
3. Good for specialty garden brands

---

## STEP 2: Customize Your Site (20 minutes)

### Update Configuration
Edit `config.js` and fill in:
- Your Amazon tracking ID
- Your social media handles
- Your email newsletter provider (optional)

### Update Products
In `config.js`, edit each product:
```javascript
{
    id: 1,
    name: "Your Product Name",
    price: 49.99,
    affiliateUrl: "YOUR_AFFILIATE_LINK_HERE",
    // ... other fields
}
```

### Add More Advice
In `config.js`, add to the ADVICE array:
```javascript
{
    title: "Your Topic",
    emoji: "🌱",
    category: "basics",
    content: "Your advice here...",
    details: "More detailed explanation...",
    relatedProducts: [1, 2, 3]
}
```

---

## STEP 3: Get It Online (Choose One)

### Option A: Netlify (EASIEST - FREE)
1. Go to: https://netlify.com
2. Sign up with GitHub/Google
3. Drag and drop your folder with `index.html` and `config.js`
4. Done! You get a free URL like: `gardenwise.netlify.app`

**Upgrade to custom domain:**
1. Buy domain on Namecheap/GoDaddy (~$10/year)
2. In Netlify: Domain Settings → Connect Custom Domain
3. Point nameservers to Netlify

### Option B: Traditional Hosting
1. Buy hosting (Bluehost ~$3/mo, GoDaddy, etc.)
2. Use FTP/File Manager to upload files
3. Upload `index.html` and `config.js` to public_html folder
4. Visit your domain

### Option C: GitHub Pages (FREE)
1. Create GitHub account
2. Create new repo named: `yourusername.github.io`
3. Upload `index.html` and `config.js`
4. Site lives at: `yourusername.github.io`

---

## STEP 4: Add Email Newsletter (Optional but Valuable)

### Mailchimp (Free up to 500 subscribers)
1. Go to: https://mailchimp.com
2. Create account and audience
3. Get your List ID and API Key
4. In `config.js`, add your details
5. Add newsletter signup form to your site

### Alternative: Substack
- Even easier, handles everything
- Readers can subscribe directly
- You get paid per subscriber

---

## STEP 5: SEO & Content Optimization

### Keywords to Target
- "home gardening tips"
- "beginner gardening advice"
- "best garden tools"
- "organic gardening"
- "vegetable gardening"
- "indoor gardening"
- "composting guide"

### On-Page SEO
1. Add keywords naturally to advice sections
2. Use descriptive product names
3. Add meta descriptions
4. Use heading hierarchy (H1, H2, H3)

### Content Strategy
- Write 1-2 detailed guides per month
- Answer common gardening questions
- Create seasonal content
- Link to related products

---

## STEP 6: Drive Traffic & Social Media

### Instagram Strategy
- Post 3-4x per week
- Share before/after garden photos
- Quick gardening tips (Reels perform best)
- Use hashtags: #GardenTips #HomeGardening #GardenAdvice
- Link in bio to your site

### TikTok Strategy
- 30-60 second gardening hacks
- Time-lapse garden growth videos
- "Garden fails" and solutions
- Trending sounds with gardening twist
- Hashtags: #GardenTok #GardenHacks #PlantTok

### Pinterest Strategy (BEST FOR AFFILIATE SALES!)
- Create vertical pins (1000x1500px) for each guide
- Link pins to your advice pages
- Use keywords in pin descriptions
- Create multiple pins per blog post
- Organize boards by category

**Example pin text:**
"10 Easy Gardening Tips for Beginners | GardenWise"

### Reddit
- Join: r/gardening, r/vegetablegardening, r/gardeners
- Answer questions genuinely
- Share your advice (don't spam links)
- Build authority and trust

### Email Marketing
- Send weekly tips (Tuesday mornings work well)
- Feature product recommendations
- Share seasonal guides
- Include affiliate links naturally

---

## STEP 7: Track Your Success

### Google Analytics Setup
1. Go to: https://analytics.google.com
2. Create account and property
3. Get your Tracking ID
4. Add to `config.js`
5. Monitor traffic, clicks, conversions

### Affiliate Dashboard
- Check Amazon Associates earnings weekly
- Track which products sell best
- Optimize based on data
- Promote top performers more

### Metrics to Watch
- Page views
- Click-through rate to products
- Conversion rate
- Top traffic sources
- Best performing products

---

## STEP 8: Monetization Tips

### Increase Affiliate Revenue
1. **Product Placement**: Feature products in advice articles
2. **Seasonal Promotions**: Push relevant products by season
3. **Email Recommendations**: Send curated lists to subscribers
4. **Content Upgrades**: Offer free guides to build email list
5. **Comparison Posts**: "Best Tools Under $50" type content

### Other Revenue Streams (Future)
- Sponsored content (garden brands pay for mentions)
- Affiliate partnerships with garden centers
- Digital courses (paid gardening guides)
- Consulting/coaching calls
- Patreon for exclusive content

---

## STEP 9: Legal & Transparency

### Disclosure Requirements
- Add affiliate disclosure in footer (already included)
- Be transparent about commissions
- Only recommend products you believe in
- FTC requires clear disclosure

### Privacy Policy (Optional but Recommended)
Add simple policy covering:
- What data you collect
- How you use it
- Newsletter opt-in terms

---

## STEP 10: Ongoing Maintenance

### Weekly
- Check affiliate earnings
- Monitor social media engagement
- Respond to comments/questions

### Monthly
- Update product links if needed
- Add new advice/content
- Review analytics
- Adjust strategy based on data

### Quarterly
- Refresh old content
- Add seasonal guides
- Analyze top performers
- Plan next quarter content

---

## Quick Checklist

- [ ] Sign up for Amazon Associates
- [ ] Get tracking ID and update config.js
- [ ] Update all product affiliate links
- [ ] Customize advice sections
- [ ] Deploy to Netlify
- [ ] Set up custom domain (optional)
- [ ] Create social media accounts
- [ ] Post first content to Instagram/TikTok
- [ ] Set up Google Analytics
- [ ] Create email list (Mailchimp/Substack)
- [ ] Write first detailed guide
- [ ] Share on Reddit
- [ ] Monitor analytics and affiliate earnings

---

## Support Resources

- **Netlify Docs**: https://docs.netlify.com
- **Amazon Associates**: https://affiliate-program.amazon.com/help
- **SEO Guide**: https://moz.com/beginners-guide-to-seo
- **Social Media Tips**: https://buffer.com/resources
- **Email Marketing**: https://mailchimp.com/resources

---

## You've Got This! 🚀

Start with the basics:
1. Get affiliate links set up
2. Deploy to Netlify
3. Post on Instagram and Pinterest
4. Watch the traffic and sales grow

Questions? Come back and ask. I can help with any step!
