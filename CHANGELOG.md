# v2.0.0-rc.9
This is our first release candidate for this project - we're going to be synchronizing releases across the differents parts of the Reaction Commerce ecosystem, so that's why we're starting with rc.8. This project should be considered `pre-release` until we've released the final 2.0.0 version.

## Features
 - feat: Improve loading pattern for tags and navItems (#461)
 - feat(tlp metadata): render metafield as metadata on TLP (#453)
 - feat(tlp title): add tag listing page's display title (#450)
 - feat: 443: PDP: Remove Tags display (#447)
 - feat:  Add subtotal to CartItems (#437) .. Resolves #240
 - feat: Simplify customization (#454)
 - feat: Use new `order.referenceId` as displayed order ID (#434)
 - feat: 366 nnnnat address validation (#421)
 - feat: Enable/Disable Single-page app routing (#419)
 - feat: Renew access tokens on 401 errors using redirects to auth endpoint (#399)
 - feat: Add "Order Completed" event tracking (#388)
 - feat: Add tracking to checkout flow (#384)
 - feat: Add tracking for "Product Removed" + "Cart Viewed" events (#372)
 - feat: Create hydra client on startup (#363)
 - feat: Add tracking for "Product Added" Segment event (#361)
 - feat: 353 nnnnat status labels (#358)
 - feat: update node to version 10 (#347)
 - feat: Add sign in/up info in auth URL generated by Passport (#320)

## Fixes
 - fix: Fix infinite loader when cart empty (#474)
 - fix: fix logic for retrying 401s with silent re-auth (#471)
 - fix: Add proper isMounted checking (#455)
 - fix: Fix error when clicking links when ENABLE_SPA_LINKS=false (#442)
 - fix: Add null check (#429)
 - fix: incorrect logger.debug (#428)
 - fix: show tax total in all summaries (#424)
 - fix(414): Fullname is not saved or displayed (#420)
 - fix(config): add canonicalUrl to publicRuntimeConfig (#418)
 - fix(340): catch Stripe Payment error and save error message (#406)
 - fix(385): Fix Product title & image URLs in Cart, MiniCart, FinalReviewCheckoutAction (#412)
 - fix: SSR issues with product grids and PDP pages (#407)
 - fix: integration test finished before resolving (#401)
 - fix: 369 compareAtPrice (#383)
 - fix: Remove unused scopes and grant_type (#390)
 - fix: Update src/lib/theme/components.js (#392)
 - fix: PDP Mobile re-org (#373)
 - fix: Add metafields to product query (#378) .. Resolves #375
 - fix: Mobile nav design & bug fixes (#346)
 - fix: issue cause by using Router from `next/routes` on the server (#368)
 - fix: Always use https for npm registry (#365)
 - fix: Duplicated initials in logged in indicator (#343)
 - fix: clear a user's cart after placing an order, and remove MiniCart popper from order completed page. (#332)
 - fix: add padding to cart items in order complete page (#338)
 - fix: Replace passport server-side sessions with cookie session (#349)
 - fix: MiniCart popper occasionally being drawn at the wrong position. (#336)

 ## Docs
 - docs: update install instructions to link to the official Docs (#382)
 - docs: numbering bug (#337)

## Performance Improvements
 - perf: Performance improvements (#396)

## Refactors
 - refactor: inventory status fixes and updated UI design (#459)
 - refactor: unsplit first and last name fields in Checkout saving (#386)
 - refactor: static assets (#367)
 - refactor: progressive image (#362) .. Resolves #227

 ## Chores
 - chore: integrate ssr test + broken link checker to CI (#473)
 - chore: update the component library to 0.60.1 (#464)
 - chore: Add logger messages for 401 error (#423)
 - chore: upgrade reactioncommerce/components to latest (#425)
 - chore: Deploy develop branch to staging environment in ECS (#355)
 - chore: Enable Webpack tree shaking (#352)
 - chore upgrade babel and next (#341)
 - chore: Set project license to Apache 2.0 (#339)
