| Bug ID | Title | Severity | Priority | Module | Preconditions | Steps to Reproduce | Expected Result | Actual Result |
|--------|--------|----------|----------|---------|---------------|--------------------|-----------------|----------------|
| BUG-001 | Search returns no results for valid keyword | High | P1 | Search | User on homepage | Search for "Samsung" | Relevant Samsung items should appear | "No results" shown incorrectly |
| BUG-002 | Add to Cart button not responding | Critical | P1 | Product Page | User on product page | Click "Add to Cart" | Item should be added to cart | Button freezes, item not added |
| BUG-003 | Filters not applying on mobile | Medium | P2 | Filters | User on mobile browser | Apply any filter | Filter should update results | Results do not change |
| BUG-004 | Incorrect price displayed at checkout | Critical | P1 | Checkout | Item in cart | Proceed to checkout | Price should match product page | Price increases unexpectedly |
| BUG-005 | Wishlist not saving items | Medium | P2 | Wishlist | Logged-in user | Add item to wishlist | Item should appear in wishlist | Wishlist shows empty |
| BUG-006 | Deals page loads slowly | Low | P3 | Performance | User on homepage | Navigate to Deals page | Page should load within 3s | Takes 12s+ to load |
| BUG-007 | Sort by price not working correctly | Medium | P2 | Sorting | User on category page | Select "Low to High" | Items sorted by price | Sorting order incorrect |
| BUG-008 | Product images not loading | High | P1 | Product Page | User browsing product list | Scroll product list | Images should load normally | Broken image icons appear |
| BUG-009 | Login button disabled after entering credentials | High | P1 | Login | User on login page | Enter valid email/password | Login button should enable | Button stays disabled |
| BUG-010 | Duplicate items appear in cart | High | P1 | Cart | Item added once | Add item to cart | Only one item displayed | Two duplicates in cart |
| BUG-011 | Search suggestions overlap UI | Low | P4 | UI | User typing in search bar | Start typing | Suggestions should appear below search bar | Suggestions overlap menu |
| BUG-012 | Wrong delivery ETA displayed | Medium | P2 | Delivery | User with saved address | Proceed to checkout | ETA should match location | ETA shows wrong city |
| BUG-013 | Footer Help Centre link broken | Low | P3 | Navigation | Any page | Click "Help Centre" | User should reach help page | 404 error displayed |
| BUG-014 | Promo code not applying | Medium | P2 | Payments | Valid promo code | Apply promo code | Discount applies | "Invalid code" shown incorrectly |
| BUG-015 | Checkout button opens blank page | Critical | P1 | Checkout | Items in cart | Click "Proceed to Checkout" | Checkout page loads normally | Blank white page appears |
