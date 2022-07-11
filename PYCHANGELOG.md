# Changelog

## [''](https://github.com/UncannyOwl/Automator/tree/'') (2022-07-11)

[Full Changelog](https://github.com/UncannyOwl/Automator/compare/v4.1.1.1...'')

**New Integrations:**
- Pabbly Connect [\#2266](https://github.com/UncannyOwl/Automator/issues/2266)
- Studiocart [\#1697](https://github.com/UncannyOwl/Automator/issues/1697)

**New Triggers:**
- Mailpoet - A user submits a form [\#217](https://github.com/UncannyOwl/Automator/issues/217)
- Studiocart - A user completes an order for a product [\#2210](https://github.com/UncannyOwl/Automator/issues/2210)
- Studiocart - A user purchases a product [\#2226](https://github.com/UncannyOwl/Automator/issues/2226)
- Studiocart - A user's order for a product is refunded [\#2227](https://github.com/UncannyOwl/Automator/issues/2227)
- Uncanny Groups - A group is created [\#1478](https://github.com/UncannyOwl/Automator/issues/1478)

**New Actions:**
- Pabbly Connect -  Send data to Pabbly Connect [\#2212](https://github.com/UncannyOwl/Automator/issues/2212)

**New Tokens:**
- WooCommerce - Product SKU [\#2179](https://github.com/UncannyOwl/Automator/issues/2179)
- WooCommerce - Product categories [\#2190](https://github.com/UncannyOwl/Automator/issues/2190)
- WooCommerce - Product tags [\#2191](https://github.com/UncannyOwl/Automator/issues/2191)

**Added:**
- Premium Integrations & Webhooks now runs asynchronously [\#2106](https://github.com/UncannyOwl/Automator/issues/2106)

**Updated:**
- Automator Core - Improved performance on high data & traffic sites [\#2149](https://github.com/UncannyOwl/Automator/issues/2149)
- Instagram - Permissions errors are now properly reflected in Recipe logs [\#2272](https://github.com/UncannyOwl/Automator/issues/2272)
- Instagram - Permissions/scopes validation added before making the action available in UI [\#1606](https://github.com/UncannyOwl/Automator/issues/1606)
- Instagram - Recipe logs now reflect error if the Instagram account is delinked from the Facebook [\#2273](https://github.com/UncannyOwl/Automator/issues/2273)
- Mailchimp - "Send an email campaign" - "From" dropdown description added [\#1451](https://github.com/UncannyOwl/Automator/issues/1451)
- Recipe UI - "Use a token/custom value" added in token dropdown for several actions  [\#1742](https://github.com/UncannyOwl/Automator/issues/1742)
- Recipe UI - JSON strings are now supported in fields #41375 [\#2203](https://github.com/UncannyOwl/Automator/issues/2203)
- Recipe list - All actions are listed in recipe order now #40306 [\#2007](https://github.com/UncannyOwl/Automator/issues/2007)
- Review Banner - Several UI upgrades [\#2229](https://github.com/UncannyOwl/Automator/issues/2229)
- WordPress - "A user's post receives a comment" - Duplicate "Any" options removed [\#2182](https://github.com/UncannyOwl/Automator/issues/2182)
- WordPress - All triggers now have standard post/page/comment tokens; Post/Page ID, Post/Page content, Post type, Post/Page author first name, Post/Page author last name, Post/Page author display name, Post/Page author email tokens added [\#2209](https://github.com/UncannyOwl/Automator/issues/2209)
- WordPress - Triggers with post type option now list all post types [\#2180](https://github.com/UncannyOwl/Automator/issues/2180)

**Internal:**
- Automator Core - Premium Integrations and Webhooks now runs asynchronously [\#1797](https://github.com/UncannyOwl/Automator/issues/1797)
- Automator Core - `automator_before_process_action` do action, `automator_maybe_parse_replaceable` filter [\#2194](https://github.com/UncannyOwl/Automator/issues/2194)

**Fixed:**
- Automator Closure - Usermeta now parses reliably #41541 [\#2251](https://github.com/UncannyOwl/Automator/issues/2251)
- Automator Core - Duplicate Action "code" conflict in a specific situation [\#2207](https://github.com/UncannyOwl/Automator/issues/2207)
- BuddyBoss - Profile field tokens now parses as comma-separated string instead of Array #41453 [\#2221](https://github.com/UncannyOwl/Automator/issues/2221)
- Elementor - PHP Error on PHP 8.x+ when email token is used on the "To" field of send an email action #41409 [\#2214](https://github.com/UncannyOwl/Automator/issues/2214)
- Facebook Settings - Nonce verification fixed [\#2263](https://github.com/UncannyOwl/Automator/issues/2263)
- Fixed: WordPress - "A user submits a comment on a post" firing for all custom post types [\#2259](https://github.com/UncannyOwl/Automator/issues/2259)
- WPForms - Multiple select field token now separates data by comma instead of newline #41477 [\#2225](https://github.com/UncannyOwl/Automator/issues/2225)
- Warning - URL redirect in WP-CLI mode [\#2231](https://github.com/UncannyOwl/Automator/issues/2231)
- WordPress - "A user publishes a post with a taxonomy  term in a taxonomy" now lists all post types reliably [\#2196](https://github.com/UncannyOwl/Automator/issues/2196)
- WordPress - "A user publishes a type of post with a taxonomy term in a taxonomy" now parses tokens reliably  #41494 [\#2245](https://github.com/UncannyOwl/Automator/issues/2245)
- WordPress - "A user views a custom post type" firing on any post #41495 [\#2243](https://github.com/UncannyOwl/Automator/issues/2243)

**Help Desk:**
- Question: WooCommerce - Shipping and WP All Import #41159 [\#2253](https://github.com/UncannyOwl/Automator/issues/2253)
- Uncanny Automator - User gets logged out #41434 [\#2249](https://github.com/UncannyOwl/Automator/issues/2249)

**Closed Issues:**
- Add "the user" to the sentences of all actions that act on the current user. [\#356](https://github.com/UncannyOwl/Automator/issues/356)
- Automator actions - dealy actions are not working as expected #41347 [\#2219](https://github.com/UncannyOwl/Automator/issues/2219)
- Basic math operations in fields [\#1276](https://github.com/UncannyOwl/Automator/issues/1276)
- BuddyBoss - "A user requests access to a private group" - PHP Error when BuddyBoss's forum component is not enabled [\#2215](https://github.com/UncannyOwl/Automator/issues/2215)
- BuddyBoss action - Send a private message to a user is completing but message is not actually received #41380 [\#2202](https://github.com/UncannyOwl/Automator/issues/2202)
- BuddyPress - All of the triggers [\#847](https://github.com/UncannyOwl/Automator/issues/847)
- Create Pabbly icon [\#2224](https://github.com/UncannyOwl/Automator/issues/2224)
- Date condition fails #36149 [\#1371](https://github.com/UncannyOwl/Automator/issues/1371)
- Facebook Groups - Automator is not posting anything on Facebook #41525 [\#2250](https://github.com/UncannyOwl/Automator/issues/2250)
- Facebook Pages - the Facebook connection is not working #41349 [\#2220](https://github.com/UncannyOwl/Automator/issues/2220)
- Fix - GamiPress "An achievement is revoked from a user" now triggers reliably [\#2213](https://github.com/UncannyOwl/Automator/issues/2213)
- In-plugin reviews - 100 free credits are used [\#2165](https://github.com/UncannyOwl/Automator/issues/2165)
- In-plugins reviews - show widget after 100 emails are sent [\#2166](https://github.com/UncannyOwl/Automator/issues/2166)
- Instagram - The "Feature image URL" token is returning blank #40745 [\#2064](https://github.com/UncannyOwl/Automator/issues/2064)
- Toolkit Pro - Enhanced Lesson & Topics Grid issue with lesson/topic order when using Legacy template #41518 [\#2257](https://github.com/UncannyOwl/Automator/issues/2257)
- Update ambiguous trigger sentences to clearly indicate target of actions [\#355](https://github.com/UncannyOwl/Automator/issues/355)
- WhatsApp - Send a message template to a number [\#2205](https://github.com/UncannyOwl/Automator/issues/2205)
- WooCommerce - Add token support in "Create an order for a product" action #41159 [\#2173](https://github.com/UncannyOwl/Automator/issues/2173)
- WooCommerce - trigger is not running if the payment is executed by PayPal #40916 [\#2119](https://github.com/UncannyOwl/Automator/issues/2119)

**Closed Pull Requests:**
- Pull Request:  Bail if in WP CLI mode. [\#2232](https://github.com/UncannyOwl/Automator/pull/2232) ([m4munib](https://github.com/m4munib))
- Pull Request: #1451 ⁃ Mailchimp - Send an email campaign [\#2145](https://github.com/UncannyOwl/Automator/pull/2145) ([JosephGabito](https://github.com/JosephGabito))
- Pull Request: #2179 ⁃ New Tokens: WooCommerce - Product SKU [\#2184](https://github.com/UncannyOwl/Automator/pull/2184) ([JosephGabito](https://github.com/JosephGabito))
- Pull Request: #2180 ⁃ Refactor all_wp_post_types method in Automator Free version to make it more reliable [\#2181](https://github.com/UncannyOwl/Automator/pull/2181) ([JosephGabito](https://github.com/JosephGabito))
- Pull Request: #2182 ⁃ Fix: WordPress - "A user's post receives receives a comment" trigger showing two "Any" options, one with "- 1" value and other other has zero value [\#2188](https://github.com/UncannyOwl/Automator/pull/2188) ([JosephGabito](https://github.com/JosephGabito))
- Pull Request: #2221 ⁃ Fix: BuddyBoss - Handled profile field tokens that returns array. Now it returns a string separated by comma. [\#2247](https://github.com/UncannyOwl/Automator/pull/2247) ([JosephGabito](https://github.com/JosephGabito))
- Pull Request: #2225 ⁃ Fix: WPForms tokens separating multiple selector by newline instead of a comma, ticket 41477 [\#2240](https://github.com/UncannyOwl/Automator/pull/2240) ([JosephGabito](https://github.com/JosephGabito))
- Pull Request: #2229 ⁃ Change behavior of reviews banner [\#2239](https://github.com/UncannyOwl/Automator/pull/2239) ([JosephGabito](https://github.com/JosephGabito))
- Pull Request: #2263 ⁃ Facebook integrations (Pages, and Groups) handle missing state validation. [\#2264](https://github.com/UncannyOwl/Automator/pull/2264) ([JosephGabito](https://github.com/JosephGabito))
- Pull Request: 1437 New Action - Uncanny codes generate {{a batch of codes}} for automator [\#2083](https://github.com/UncannyOwl/Automator/pull/2083) ([ankituc](https://github.com/ankituc))
- Pull Request: 1797 update move additional triggers to use `options callback` method [\#2152](https://github.com/UncannyOwl/Automator/pull/2152) ([ankituc](https://github.com/ankituc))
- Pull Request: 217 Mailpoet - New trigger - a user submits {a form} [\#2262](https://github.com/UncannyOwl/Automator/pull/2262) ([ankituc](https://github.com/ankituc))
- Pull Request: 2209 wpcore standard post tokens [\#2242](https://github.com/UncannyOwl/Automator/pull/2242) ([saad-siddique](https://github.com/saad-siddique))
- Pull Request: 4.2 Setup [\#2265](https://github.com/UncannyOwl/Automator/pull/2265) ([saad-siddique](https://github.com/saad-siddique))
- Pull Request: Add hooks to the advanced settings tab [\#2267](https://github.com/UncannyOwl/Automator/pull/2267) ([ajayver](https://github.com/ajayver))
- Pull Request: Added new filter and action [\#2110](https://github.com/UncannyOwl/Automator/pull/2110) ([JosephGabito](https://github.com/JosephGabito))
- Pull Request: Added trigger_to_match param to only query applicable trigger. [\#2260](https://github.com/UncannyOwl/Automator/pull/2260) ([m4munib](https://github.com/m4munib))
- Pull Request: Adjusted condition to make sure user current user is detected properly. [\#2261](https://github.com/UncannyOwl/Automator/pull/2261) ([m4munib](https://github.com/m4munib))
- Pull Request: Fix: Allow duplicated item codes [\#2222](https://github.com/UncannyOwl/Automator/pull/2222) ([ajayver](https://github.com/ajayver))
- Pull Request: Fixes applied to list actions in proper way. [\#2218](https://github.com/UncannyOwl/Automator/pull/2218) ([ankituc](https://github.com/ankituc))
- Pull Request: Group-Codes-group-created-trigger [\#2052](https://github.com/UncannyOwl/Automator/pull/2052) ([huma-uncannyowl](https://github.com/huma-uncannyowl))
- Pull Request: Handle JSON string [\#2230](https://github.com/UncannyOwl/Automator/pull/2230) ([saad-siddique](https://github.com/saad-siddique))
- Pull Request: Instagram Updates [\#2122](https://github.com/UncannyOwl/Automator/pull/2122) ([JosephGabito](https://github.com/JosephGabito))
- Pull Request: New Feature: Calculation token [\#2246](https://github.com/UncannyOwl/Automator/pull/2246) ([ajayver](https://github.com/ajayver))
- Pull Request: Pabbly Connect [\#2268](https://github.com/UncannyOwl/Automator/pull/2268) ([saad-siddique](https://github.com/saad-siddique))
- Pull Request: Performance updates [\#2124](https://github.com/UncannyOwl/Automator/pull/2124) ([saad-siddique](https://github.com/saad-siddique))
- Pull Request: Premium Integrations & Webhooks now run asynchronously [\#2238](https://github.com/UncannyOwl/Automator/pull/2238) ([ajayver](https://github.com/ajayver))
- Pull Request: Studiocart Integration [\#2217](https://github.com/UncannyOwl/Automator/pull/2217) ([m4munib](https://github.com/m4munib))
- Pull Request: Update elem-tokens.php [\#2216](https://github.com/UncannyOwl/Automator/pull/2216) ([JosephGabito](https://github.com/JosephGabito))
- Pull Request: Update wp-usercreatespost.php [\#2271](https://github.com/UncannyOwl/Automator/pull/2271) ([saad-siddique](https://github.com/saad-siddique))
- Pull Request: Update wp-viewcustompost.php [\#2244](https://github.com/UncannyOwl/Automator/pull/2244) ([saad-siddique](https://github.com/saad-siddique))
- Pull Request: supports_custom_value default true [\#2192](https://github.com/UncannyOwl/Automator/pull/2192) ([huma-uncannyowl](https://github.com/huma-uncannyowl))
