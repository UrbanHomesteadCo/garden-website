# 🔧 GardenWise Troubleshooting Guide

Common issues and how to fix them.

---

## Website Issues

### Site shows 404 error
**Problem:** Page not found when visiting your Netlify URL

**Solutions:**
1. Make sure `netlify.toml` is in your folder
2. Check that redirects are configured
3. Do a hard refresh (Ctrl+Shift+R on Windows, Cmd+Shift+R on Mac)
4. Wait 1-2 minutes for Netlify to rebuild
5. Check Netlify dashboard for build errors

### Products not showing up
**Problem:** Product list is empty

**Solutions:**
1. Check that `config.js` is in the same folder as `index.html`
2. Make sure `config.js` is properly formatted (no syntax errors)
3. Check browser console (F12) for JavaScript errors
4. Try clearing browser cache and reloading

### Affiliate links not working
**Problem:** Clicking products doesn't go to Amazon

**Solutions:**
1. Check that affiliate URLs are correct in `config.js`
2. Make sure URLs start with `https://`
3. Test link in new tab (right-click → Open in new tab)
4. Check your Amazon Associates account is active
5. Verify tracking ID is correct

### Shopping cart not working
**Problem:** Can't add items to cart

**Solutions:**
1. Check browser console (F12) for errors
2. Make sure JavaScript is enabled
3. Try a different browser
4. Clear browser cache and reload
5. Check that `index.html` is complete (all code present)

### Site looks broken/ugly
**Problem:** CSS not loading, site looks wrong

**Solutions:**
1. Check that all code is in one `index.html` file
2. Make sure there are no line breaks in CSS section
3. Hard refresh (Ctrl+Shift+R)
4. Try different browser
5. Check file isn't corrupted (download fresh copy)

---

## Deployment Issues

### Netlify won't accept files
**Problem:** Can't drag files onto Netlify

**Solutions:**
1. Make sure you're signed into Netlify
2. Create a folder with your files first
3. Drag the folder, not individual files
4. Try refreshing the Netlify page
5. Try a different browser
6. Check file names (no spaces, no special characters)

### Site takes forever to load
**Problem:** Netlify site is slow

**Solutions:**
1. Check your internet connection
2. Try clearing browser cache
3. Wait 5 minutes (Netlify may be building)
4. Check Netlify dashboard for build status
5. Try different browser
6. Check if you're using too many images

### Custom domain not working
**Problem:** Domain name doesn't point to your site

**Solutions:**
1. Wait 24-48 hours (DNS propagation takes time)
2. Check nameserver settings in domain registrar
3. Verify domain is pointing to Netlify nameservers
4. Check Netlify domain settings are correct
5. Use DNS checker tool: https://www.whatsmydns.net

### Site shows old version
**Problem:** Changes aren't appearing on live site

**Solutions:**
1. Hard refresh (Ctrl+Shift+R)
2. Wait 2-3 minutes for Netlify to rebuild
3. Check Netlify deployment status
4. Clear browser cache
5. Try incognito/private window
6. Check you deployed the right files

---

## Configuration Issues

### Changes to config.js not showing
**Problem:** Updated products/advice but site unchanged

**Solutions:**
1. Make sure you saved the file
2. Re-upload file to Netlify
3. Hard refresh browser (Ctrl+Shift+R)
4. Wait 2-3 minutes for rebuild
5. Check file is valid JavaScript (no syntax errors)

### Admin panel not working
**Problem:** Can't add products or advice

**Solutions:**
1. Make sure `admin.html` is deployed
2. Access via: yoursite.com/admin.html
3. Check browser console (F12) for errors
4. Make sure you're using a modern browser
5. Try in incognito/private window
6. Check localStorage is enabled (Settings → Privacy)

### Settings not saving
**Problem:** Admin panel won't save changes

**Solutions:**
1. Check browser console for errors
2. Make sure localStorage is enabled
3. Check you're not in private/incognito mode
4. Try different browser
5. Clear browser cache
6. Check browser storage isn't full

---

## Affiliate & Monetization Issues

### Not getting Amazon commissions
**Problem:** No earnings despite sales

**Solutions:**
1. Check Amazon Associates account is active
2. Verify tracking ID is correct in config.js
3. Make sure affiliate link format is correct
4. Check 24-hour cookie window (customer must buy within 24 hours)
5. Verify you're using correct Amazon region
6. Check Amazon Associates dashboard for rejected sales

### Affiliate links showing as broken
**Problem:** Links 404 or redirect wrong

**Solutions:**
1. Test link directly (copy URL into browser)
2. Check URL format is correct
3. Make sure URL includes tracking ID
4. Try with `https://` instead of `http://`
5. Check Amazon product still exists
6. Update link with new product

### Wrong commission rate
**Problem:** Earning less than expected

**Solutions:**
1. Check your Amazon Associates tier (new accounts get 1%)
2. Verify commission rate for product category
3. Check for promotional codes (some have lower rates)
4. Review Amazon Associates terms
5. Contact Amazon support

---

## Social Media Issues

### Can't grow followers
**Problem:** Not getting engagement

**Solutions:**
1. Post consistently (3-5x per week minimum)
2. Use trending sounds/hashtags
3. Engage with other accounts (like, comment, follow)
4. Post at optimal times (6-9 AM, 7-11 PM)
5. Use calls-to-action ("Follow for more tips!")
6. Create shareable content
7. Go live occasionally
8. Collaborate with other creators

### Low click-through to site
**Problem:** Few people visiting from social

**Solutions:**
1. Add link in bio (most important)
2. Add CTA in captions ("Link in bio for full guide")
3. Create compelling content (people need reason to visit)
4. Use shorter, cleaner links
5. Make sure link works
6. Test link from different devices
7. Use UTM parameters to track (advanced)

### No email subscribers
**Problem:** Newsletter list not growing

**Solutions:**
1. Add newsletter signup to website
2. Promote in every social post ("Subscribe for weekly tips")
3. Offer lead magnet (free guide, checklist)
4. Add popup to website (after 10 seconds)
5. Make signup easy (email only, no password)
6. Send valuable content (people need reason to subscribe)

---

## Content & SEO Issues

### No organic search traffic
**Problem:** Google isn't sending visitors

**Solutions:**
1. Add keywords naturally to content
2. Write descriptive titles and meta descriptions
3. Link related articles together
4. Create quality content (1,000+ words)
5. Update old content regularly
6. Build backlinks (other sites linking to you)
7. Submit sitemap to Google Search Console
8. Be patient (takes 3-6 months for SEO)

### Content not getting shared
**Problem:** Low engagement on posts

**Solutions:**
1. Create more valuable content
2. Use better headlines/titles
3. Add visuals (images, videos)
4. Ask questions in captions
5. Use trending hashtags
6. Post at optimal times
7. Engage with similar content
8. Create more entertaining content

### Advice not ranking well
**Problem:** Articles not showing in search results

**Solutions:**
1. Use keywords in title and first paragraph
2. Make content longer (1,000+ words)
3. Add internal links to related content
4. Use descriptive headings (H2, H3)
5. Add alt text to images
6. Update old content
7. Get backlinks from other sites
8. Submit to Google Search Console

---

## Analytics Issues

### Google Analytics not tracking
**Problem:** No traffic data in Analytics

**Solutions:**
1. Add tracking code to website
2. Wait 24-48 hours for data to appear
3. Check property is set up correctly
4. Verify tracking ID is correct
5. Check you're not filtering yourself out
6. Use incognito to test tracking
7. Check Analytics account is active

### Metrics don't match
**Problem:** Different numbers in different tools

**Solutions:**
1. Different tools count differently (normal)
2. Allow 24 hours for data to sync
3. Check date ranges match
4. Different tools have different definitions
5. This is normal - use one tool as primary

---

## Email & Newsletter Issues

### Newsletter signup not working
**Problem:** Can't subscribe to emails

**Solutions:**
1. Check Mailchimp account is active
2. Verify API key is correct
3. Check list ID is correct
4. Make sure form is properly configured
5. Test with different email address
6. Check spam folder
7. Contact Mailchimp support

### Low email open rates
**Problem:** People not opening your emails

**Solutions:**
1. Write better subject lines
2. Send at optimal time (9 AM Tuesday-Thursday)
3. Send from recognizable name
4. Make emails shorter
5. Add clear CTA
6. Segment your list
7. Test different send times

---

## Performance Issues

### Site is slow
**Problem:** Pages take too long to load

**Solutions:**
1. Check internet connection
2. Reduce image sizes
3. Remove unnecessary code
4. Use CDN (Netlify does this automatically)
5. Check for JavaScript errors
6. Test on different device/connection
7. Use PageSpeed Insights: https://pagespeed.web.dev

### High bounce rate
**Problem:** People leave without exploring

**Solutions:**
1. Improve page design (make it attractive)
2. Add clear navigation
3. Improve page speed
4. Add engaging content
5. Make CTA clear
6. Reduce ads/popups
7. Make mobile experience better

---

## Browser Compatibility Issues

### Site works in Chrome but not Firefox
**Problem:** Site broken in certain browsers

**Solutions:**
1. Test in multiple browsers
2. Check for browser-specific CSS issues
3. Use standard CSS (avoid experimental features)
4. Check JavaScript compatibility
5. Test on mobile browsers too
6. Use caniuse.com to check support

---

## Security Issues

### Getting security warnings
**Problem:** Browser shows warning about site

**Solutions:**
1. Make sure site uses HTTPS (not HTTP)
2. Check for mixed content (some resources aren't HTTPS)
3. Update SSL certificate if needed
4. Check Netlify certificate is active
5. Remove any insecure links

---

## General Troubleshooting Steps

1. **Check browser console** (F12 → Console tab)
   - Look for red error messages
   - Search error message online

2. **Try different browser**
   - Chrome, Firefox, Safari
   - If works in one, it's browser-specific

3. **Clear cache and reload**
   - Ctrl+Shift+R (Windows)
   - Cmd+Shift+R (Mac)

4. **Check file names**
   - Lowercase, no spaces
   - Correct spelling

5. **Validate code**
   - Check for typos
   - Use validator: https://validator.w3.org

6. **Check documentation**
   - Review relevant guide
   - Check comments in code

7. **Search online**
   - Copy error message
   - Add "netlify" or "javascript"
   - Usually someone has same issue

8. **Contact support**
   - Netlify support (if deployment issue)
   - Amazon Associates (if affiliate issue)
   - Browser developer (if code issue)

---

## Getting Help

### For Website/Code Issues
- Check browser console (F12)
- Validate HTML: https://validator.w3.org
- Validate JavaScript: https://jshint.com
- Check Netlify build logs

### For Netlify Issues
- Check Netlify dashboard
- Review deployment logs
- Check Netlify status: https://www.netlifystatus.com
- Contact Netlify support

### For Amazon Affiliate Issues
- Check Amazon Associates dashboard
- Review affiliate terms
- Contact Amazon support
- Check tracking ID is correct

### For General Questions
- Review all documentation
- Check comments in code
- Search online
- Ask in relevant community forum

---

## Still Stuck?

1. **Read the relevant documentation** for your issue
2. **Check browser console** for error messages
3. **Search online** for the error message
4. **Try in different browser** to isolate issue
5. **Contact relevant support** (Netlify, Amazon, etc.)

Most issues have simple solutions. Don't give up!

---

**Good luck! You've got this! 🚀**
