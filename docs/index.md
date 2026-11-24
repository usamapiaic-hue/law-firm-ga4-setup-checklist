# GA4 Setup Checklist for Law Firm Websites

Most law firm websites have Google Analytics installed, but few count what matters: calls, form submissions and booked consultations. Without those, you can see traffic but not which pages or channels produce clients. This checklist sets up GA4 so leads are counted. Published by Legal Web Agency.

## 1. The basics

| Check | Pass condition |
|-------|----------------|
| One GA4 property for the site | Not several old ones collecting partial data |
| Tag on every page | Including thank-you pages and the blog |
| Internal traffic filtered | Office IP addresses excluded |
| Data retention set to the maximum | So year-on-year comparisons work |
| Search Console linked | Queries visible alongside behaviour |
| Google Ads linked (if used) | Conversions can be imported into Ads |

## 2. Define what a lead is

Mark these as **key events** (conversions) in GA4:

| Lead type | How to track it |
|-----------|-----------------|
| Form submission | A thank-you page view, or the form plugin's success event |
| Phone call from the website | A click on a `tel:` link (counts taps, not completed calls) |
| Call from a tracking number | Your call-tracking tool's integration |
| Booked consultation | The booking tool's confirmation event |
| Live chat lead | The chat tool's lead event |

Do not count page views, scrolls or button hovers as conversions; they inflate the numbers without telling you anything about clients.

## 3. Make calls countable

Phone calls are often the largest share of legal leads, and the easiest to miss.

- Make every phone number a tappable `tel:` link.
- Track clicks on those links as an event.
- For real call counts and durations, use a call-tracking service with dynamic numbers by source, and keep the main number consistent on your Google Business Profile.

## 4. Tag your campaigns

Add UTM parameters to links you control: the Google Business Profile website link, email newsletters, social posts and directory listings. Then GA4 can tell you which of them produce leads.

## 5. Check it works

1. Submit a test form and tap the phone link on a phone.
2. Open GA4's real-time report and confirm both events arrive.
3. A day later, confirm they show as key events in the reports.
4. Repeat after any website redesign or plugin change, because tracking often breaks silently.

## 6. Read it monthly

Look at leads by landing page and by channel, not just sessions. A page with little traffic but steady form submissions is worth more than a popular blog post with none.

## Further reading

Legal Web Agency's guide to [conversion tracking for law firms](https://legalwebagency.com/law-firm-website-conversion-tracking/) goes deeper, including call tracking options, and the [Legal Web Agency](https://legalwebagency.com/) team can set this up for firms.

---

*Published by [Legal Web Agency](https://legalwebagency.com/), a website design and SEO studio for law firms.*
