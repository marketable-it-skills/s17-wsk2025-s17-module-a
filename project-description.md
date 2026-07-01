# Test Project Outline – Module A – Static Website Design

In this module, you must develop a promotional landing site for an online classifieds service. The platform lets users post and browse listings for collectible and themed goods: LEGO sets, board games, comics, figurines, souvenirs, and more.

Your task is to build a modern landing site that presents the service’s features and benefits for different user types.

## Competitor Information

The landing site must consist of four logically connected pages. Each page must be reachable via navigation, share a consistent style, and display correctly on devices of different sizes.

Please apply SEO optimization and the required meta tags on every page. Configure **OpenGraph** on the website.

Include a **README.md** file with instructions for running the project. In that file, describe how to change the link targets of the `Publish` and `View` buttons.

## Website Requirements

- Frameworks are not allowed
- Responsive layout: correct display on devices with different resolutions
- Consistent navigation structure on all pages
- Semantic, clean markup
- Micro-animations on hover for buttons and links
- High-quality typography and readable text
- Correct input field types and valid links

### Home Page

Include the following:

- Promo block with the project name, a short description, and a call-to-action
- About the project: goals, audience, platform highlights
- Product categories (`media-files/texts/category.txt`)
- Service benefits
- Call-to-action block to engage users
- User testimonials section

### For Seller Page

Include the following:

- Instructions for posting listings. Describe the listing process and how easy it is. Storytelling should be engaging and reflect the service’s values (`media-files/texts/seller-story.txt`)
- Benefits for sellers (`media-files/texts/seller.txt`)
- FAQ section (`media-files/texts/seller-faq.txt`)

### For Seller – Advantages Page

Include the following:

- Price list (`media-files/texts/seller-price-list.txt`). Let the user choose the number of days to calculate the cost of each service. The user must select the number of days using a `range` input. Prices and day counts are defined in the file.
- Benefits for sellers (`media-files/texts/seller-price-list-advantages.txt`)
- FAQ section (`media-files/texts/seller-price-list-faq.txt`)

### For Buyer Page

Include the following:

- Step-by-step buying instructions. Describe the purchase process and how easy it is. Storytelling should be engaging and reflect the service’s values (`media-files/texts/buyer-story.txt`)
- Benefits for buyers (`media-files/texts/buyer.txt`)
- FAQ section (`media-files/texts/buyer-faq.txt`)

### Contacts

Include the following:

- Contact form (name, email, message)
- Contact details: email, business hours
- Social media links
- Map (`media-files/map.png`)

Content is provided in `media-files/texts/contacts.txt`.

### Policy

Place the privacy policy text from `media-files/texts/policy.txt` on a separate page.

Format the text with HTML elements that ensure readability: headings, paragraphs, lists, and other appropriate markup.

## Global Elements

Every page must include a **header** with:

- Logo
- Navigation
- `Publish` and `View` buttons

These buttons currently link to the `For Seller` and `For Buyer` pages, but it must be easy to change their link targets.

Provide two distinct styles and micro-animations for these buttons; styles must switch based on the `data-type` attribute.

The navigation must include:

- Home
- For Seller
  - Advantages
  - Paid Services
  - FAQ
- For Buyer
  - Advantages
  - FAQ

Every menu item except `Home` has a second-level submenu. It must appear on hover as a separate block.

**JavaScript must not be used** to show the second-level menu.

Implement a footer on every page with navigation and links to other pages.
