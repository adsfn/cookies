# Product

<!-- impeccable:product-schema 1 -->

## Platform

web

## Users

Health-minded home bakers: adults who already bake and want lower-sugar, wholefood treats without giving up taste. They browse to pick a cookie, then come back to the recipe in the kitchen, often on a phone, to measure, scale and bake.

## Product Purpose

Crumb & Co. is a free recipe site of healthier homemade cookies. Nothing is sold. It answers one question: can a cookie be good for you and still taste like a treat? Success means visitors bake the recipes and come back for more.

## Positioning

Every recipe is built to be healthier from the start (fruit-sweetened, wholegrain, nut- or legume-based) rather than being a regular cookie with a "lighter" note added. Each one comes with full measurements, approximate nutrition per cookie, explained ingredients and healthy swaps that scale with the batch.

## Operating Context

- Discovery: a landing "cookie wheel" where visitors drag, scroll or swipe through the cookies, each shown as a 3D cookie, then open one.
- Use: a recipe page per cookie covering ingredients with a reason for each, nutrition per cookie, the method, batch scaling (½×, 1×, 2×, …) with cookie counts and notes, healthy swaps, serving tips, storage, dietary info and "More cookies".
- An About page covers the team and mission.
- Used on desktop and mobile; the kitchen use happens mostly on a phone.

## Capabilities and Constraints

- Six recipes at present: Oat & Date, Almond Butter, Dark Cacao (chickpea flour), Pumpkin Spice, Coconut Lime, Blueberry Walnut.
- Static site in a single `index.html` (inline CSS/JS, Google Fonts), with no build step and no framework. The 3D cookie model is embedded as base64 GLB, so the file is about 1.7 MB.
- Installable as a PWA (`site.webmanifest`); always dark (the "night bake" palette, whatever the system preference), and respects `prefers-reduced-motion`.
- Nutrition values are approximate, per cookie, and must keep saying so.
- The 3D cookie model is by TiraArt on Sketchfab. Keep the credit wherever the model is used.

## Brand Commitments

- Name: Crumb & Co. Tagline in use: "Good-for-you cookies".
- Official logo: the Monogram (`brand/monogram-logo.svg`, `brand/monogram-logo-on-dark.svg`, `brand/monogram-mark.svg`). The Crumb and Alt Chef files in `brand/` are unused alternatives. The current favicon set does not yet match the Monogram mark.
- Voice in the existing copy is warm, plain and appetising, and states health benefits without preaching ("Sweetened by fruit alone.", "Naturally good.").

## Evidence on Hand

- Real recipes with measurements, nutrition, swaps, tips and storage notes, all in `index.html`.
- The team, stated on the About page: four founders: Benjamin Xian (founder and designer, who also designed the site), Akshayan Sriananthan (founder and facilitator), Skylar Hom (founder and marketing) and James Ancheta (founder and researcher).
- None of the following exist, so none may be invented: testimonials, reviews, ratings, press, photography of baked cookies, certified or lab-tested nutrition data, or bakery or retail claims.

## Product Principles

1. Taste first, health built in. The treat has to sound worth baking before the benefits matter.
2. Kitchen-ready. Measurements, scaling and steps should be usable mid-bake on a phone.
3. Honest about health. Use approximate nutrition and plain ingredient reasons, with no medical or diet-culture claims.
4. Explain the why. Every ingredient and swap says what it does, so bakers can adapt with confidence.
5. Free and generous. No paywalls or sales pressure; the recipes are the product.

## Accessibility & Inclusion

Dietary info (gluten-free, refined-sugar-free and so on) must stay accurate and visible for bakers with dietary needs. The interactive wheel needs keyboard and swipe alternatives, and motion has to respect reduced-motion settings, as it does now.
