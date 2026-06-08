## Project Overview
<pre>
<b>Project:</b>   FXCK
<b>Role:</b>      Brand Identity Designer, UI/UX Designer, & Lead Web Developer
<b>Tools:</b>     Photoshop, Wordpress, WooCommerce, PHP, MySQL, HTML, CSS, JS/jQuery, Foundation
           Tumblr (custom Theme), LocalStorage, Formspree API
</pre>

&nbsp;<strong><a href="https://shopfxckbrand.tumblr.com/">View project</a></strong>

<p><a href="https://shopfxckbrand.tumblr.com/"><img src="https://doylesee.github.io/fxck/thumbnail.jpg" /></a></p>
<br />

## The Challenge
The streetwear brand FXCK required an online storefront that captured their bold, counter-culture aesthetic while offering a frictionless shopping experience. The initial challenge was to build a clean, product-first e-commerce store with zero pre-existing branding assets, requiring me to construct the entire visual identity from the ground up.

Years later, a unique business hurdle emerged as the brand decided to pause its core operations and needed to completely eliminate the high hosting and maintenance costs of WordPress and WooCommerce. However, they still wanted to maintain an active, highly styled online brand presence and allow users to browse and buy archival pieces. The challenge shifted to migrating their entire WordPress environment to Tumblr, a historically restrictive blogging platform, while somehow preserving a functional, interactive cart / checkout experience.

<br />

## Core Objectives
**Comprehensive Brand Architecture**<br />
Establish a cohesive streetwear brand identity, including logos, color palettes, and strict typography rules.

**Intuitive E-Commerce Layout**<br />
Design and build a streamlined WordPress homepage layout optimized specifically for product discovery and social conversion.

**Immersive Lookbook Integration**<br />
Build a custom media slider module to showcase seasonal collections and lookbooks dynamically.

**Platform Migration & Creative Engineering**<br />
Reverse-engineer a custom Tumblr theme to function as a seamless, low-cost "faux" e-commerce site complete with a functional cart/checkout experience.

<br />

## My Approach & Implementation
### 1. Brand Identity & WordPress E-Commerce Launch
Having been immersed in the streetwear industry for years, it was an organic process to formulate FXCK's core brand styles and guidelines. This also allowed me to pull from years of creative experience and marry those artistic assets with my core WordPress expertise.

In the initial phase, I designed a clean, intuitive UI built on WordPress and WooCommerce. I structured the homepage layout to focus strictly on what the brand needed to convert visitors:

**The Hero Element**<br />
A massive, high-contrast bold banner establishing the seasonal aesthetic.

**The Product Grid**<br />
A clean, WooCommerce grid displaying all available pieces immediately below the fold.

**Social Media & Contact**<br />
An integrated footer block featuring a stylized contact info alongside live-rendered featured social media posts from Twitter and Instagram.

**The Lookbook Carousel**<br />
A highly responsive, touch-enabled media slider allowing users to look through editorial lookbooks of recent apparel drops.

### 2. The Tumblr Pivot: Engineering a Faux E-Commerce Experience
When the brand restructured to cut overhead costs, I migrated their WordPress environment to Tumblr. Since Tumblr doesn’t natively support inventory, databases, or checkout pipelines, I engineered a serverless, database-free e-commerce architecture entirely on the client side using JavaScript, jQuery, and LocalStorage:

**State Management via LocalStorage:**<br />
I wrote a custom script that captures item interactions (product name, price, and size selection), appends a precise date-time stamp to create a unique identifier, and pushes it into an array saved directly in the user's browser storage.

**Dynamic Checkout Processing:**<br />
On a custom Tumblr checkout sub-page, the script parses the localized browser string array, loops through the array items to dynamically calculate and display cart rows, aggregates the item prices into a live dynamic total string, and appends the final text bundle into invisible form inputs.

**Serverless Order Routing:**<br />
To eliminate backend management fees, I integrated Formspree into the order execution stage. When a user submits an order, the system acts as a pipeline—passing the full structured order sheet and shipping records to the client, flushing the localStorage array clean, and gracefully redirecting the consumer back to the main homepage.

<br />

## Results & Impact
**Full-Scale Creative Execution**<br />
Successfully launched a distinct streetwear brand identity and optimized online storefront entirely from scratch, utilizing a unified design-to-code workflow.

**Unconventional Technical Ingenuity**<br />
Overcame severe blogging platform limits by writing a custom state management system from scratch using LocalStorage and jQuery—simulating a full add-to-cart, remove-item, and form-routed checkout flow on Tumblr without requiring an expensive runtime database.

**Massive Cost Optimization**<br />
Safely decommissioned an expensive database-driven WordPress architecture, reducing the client's monthly hosting and platform maintenance fees significantly.

**Lasting Brand Longevity**<br />
Maintained FXCK's digital footprint and cult-brand aesthetic online, ensuring past lookbooks and remaining archive inventory stayed accessible to their community.

<br /><strong><a href="https://shopfxckbrand.tumblr.com/">View project</a></strong>
