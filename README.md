# Nativo CLP Validator
This is a single page web app that I wrote while working at Nativo. Publishers setup content landing pages for use with the Nativo platform so they can create advertising content that matches the look and feel of other articles on their site. To avoid SEO and reporting issues, we ask publishers to remove canonical URLs and og tags the while setting up their CLP. Here are some examples:

**Canonical URL Example**
`<link rel="canonical" href="http://www.yoursite.com/sponsored/" />`

**OG Tag Example**
`<meta property="og:url" content="http://www.yoursite.com/sponsored/" />`
 
We also strongly recommend adding `<meta name="robots" content="noindex, nofollow" />` on the CLP to avoid being penalized or even delisted from Google results.

This script analyzes the URL that is entered into the form field and evaluates the response from the website to determine if these elements exist on the page and make recommendations based on the response.