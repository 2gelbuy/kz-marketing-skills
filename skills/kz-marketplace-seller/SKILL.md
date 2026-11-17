---
name: kz-marketplace-seller
description: Use when someone sells or plans to sell goods on Kaspi Магазин (the Kaspi.kz marketplace in Kazakhstan) and asks about product cards, pricing, commission, delivery cost, paid promotion inside the marketplace, seller rating, reviews, quality indicators and disconnection, position among sellers, or what the marketplace forbids.
metadata:
  openclaw:
    homepage: https://konabayev.com/tools/kazakhstan-marketing-skills/
---

# Selling on the Kaspi.kz marketplace

Reply in the language of the user's message: English to English, Russian to Russian, Kazakh to Kazakh. The sources being in Russian does not change that. Quote prices in tenge.

## Facts from the official seller guide

Every fact below comes from Kaspi Гид for partners (guide.kaspi.kz/partner/ru/shop), read on 2026-11-17. Rules change: before the user acts on money or account risk, tell them to open the linked page and check its "Обновлен" date.

- **Who can sell.** An organization that is connected to Kaspi Pay and has accepted payments to its Kaspi Pay account on at least 20 days in the last 2 months. Kaspi's page says "organization" and does not say whether a sole proprietor (ИП) qualifies; tell the user to check in Kaspi Pay. Services go to the separate "Объявления" service. [Source](https://guide.kaspi.kz/partner/ru/shop/conditions/q1338)
- **What may not be sold.** Used goods, fakes and replicas, 18+ goods, smoking goods, weapons, spy devices, digital goods, free samples, animals, uniforms, fine-mesh nets and more ([full list](https://guide.kaspi.kz/partner/ru/shop/conditions/q3904)); some goods cannot be sold in instalments ([list](https://guide.kaspi.kz/partner/ru/shop/conditions/q4659)). A price must be between 10 ₸ and 5 million ₸ ([q1345](https://guide.kaspi.kz/partner/ru/shop/conditions/q1345)). For rules on dual prices see [q4170](https://guide.kaspi.kz/partner/ru/shop/conditions/q4170).
- **Commission.** Fixed per product category, the same for every partner, charged only on a completed sale and returned if the buyer cancels. The 2026 table prints three pairs, without and with VAT: 10.9% / 12.5% for almost every category, 6.4% / 7.3% for food, medicines and pet food, 13.5% / 15.5% for jewellery and some accessories. The pairs do not divide to the 16% VAT rate, so take the exact charge from a real order in the cabinet. The rate without VAT did not change when VAT rose to 16%; the amount with VAT did. It can differ during 0-0-24 instalment promotions. [Rates](https://guide.kaspi.kz/partner/ru/shop/conditions/q1344), [VAT display since 5 January 2026](https://guide.kaspi.kz/partner/ru/shop/conditions/q4467), [VAT rise](https://guide.kaspi.kz/partner/ru/shop/conditions/q5430)
- **Delivery.** Kaspi Доставка is charged to the seller by order total and weight, from 49 ₸ for an order under 1,000 ₸ to 1,099 ₸ and more for an order of 10,000 ₸ and up, and only when the order is handed to the buyer. [Tariffs](https://guide.kaspi.kz/partner/ru/shop/delivery/shipping/q2288)
- **Paid promotion.** Product advertising is pay per click with a 3 ₸ minimum bid; Kaspi advises it for goods with a conversion score of 7 or higher. [Source](https://guide.kaspi.kz/partner/ru/marketing/advert_goods/general/q1682)
- **How buyers find goods.** By product name, category and keywords. [Source](https://guide.kaspi.kz/partner/ru/shop/goods/general/q2235)
- **Order of sellers inside one product card.** Kaspi lists five factors: seller bonuses, price, rating, number of reviews, delivery speed. Kaspi states that the seller with the fastest delivery is always in the top three and that the lowest price takes first place; it does not publish how the factors are weighed. [Source, updated 2026-06-15](https://guide.kaspi.kz/partner/ru/shop/goods/general/q3190)
- **Seller rating.** Average of buyer ratings for the last 90 days, from 1 to 5 in steps of 0.1, calculated once there are at least 3 ratings. Below 4 stars Kaspi may act, up to ending the partnership. Reviews about damage during Kaspi Delivery are not counted. [Source, updated 2026-02-25](https://guide.kaspi.kz/partner/ru/shop/quality_index/rating/q2248)
- **Quality indicators.** Besides the rating Kaspi tracks cancellations through the seller's fault (required under 3%), late hand-overs to Kaspi Доставка (under 10%) and returns for quality (under 2%). At «Плохо» the seller has 14 days to improve, after which «Мой Магазин» becomes unavailable; at «Очень плохо» the rating drops to 3 stars, «Мой Магазин» is switched off, the seller is kept out of the top three, and the partnership may end. [Levels and consequences, updated 2026-11-06](https://guide.kaspi.kz/partner/ru/shop/quality_index/general/q4620); the page for each threshold is linked in `references/quality-indicators.md`.
- **Kaspi's own advice for raising the rating.** Sell only original goods, make sure goods match the card (create a separate card when they do not), pack in a box or courier bag that survives several transfers. [Source](https://guide.kaspi.kz/partner/ru/shop/quality_index/rating/q2251)

## Tactics the rules forbid

Never recommend any of these; they are listed in the [partner rules](https://guide.kaspi.kz/partner/ru/shop/conditions/q1342):

- putting flyers, coupons, gifts or any marketing inserts into an order, or mentioning them in the card;
- listing goods that are not in stock (pre-order is the allowed exception);
- asking a buyer to cancel an order, change a return reason, or offering a reward for it;
- offering money or any other reward for a positive review, or for changing or deleting a review;
- placing orders in your own shop or with competitors to move ratings and reviews;
- setting a higher price for payment through Kaspi than for other payment methods;
- selling used, expired, demo or counterfeit goods;
- handling orders outside the seller cabinet (the API is the allowed exception) or giving cabinet access to third parties.

## Reference files

Read the one the question needs before answering:

- `references/fees-and-delivery.md`: any question about price, margin, commission for a category, delivery tariffs, Express or own delivery. Holds the full tariff tables and the margin formula.
- `references/advertising.md`: whether and how to advertise, bids, budget, conversion score, bonuses on goods.
- `references/product-card.md`: writing or reviewing a title, description, photos or characteristics; an item that is on sale but not visible. Holds the banned words.
- `references/reviews.md`: a falling rating, a negative review, a request to remove a review.
- `references/quality-indicators.md`: cancellations, late hand-overs, returns, chat replies, a warning or disconnection for bad indicators, the «Отличный продавец» status, traffic from Instagram, TikTok or bloggers to a Kaspi card, automatic repricing.

## How to help

1. Ask for the category, price, weight of the packed item, cost of the goods, the competing sellers in the same card (price, rating, delivery term), and the seller's 90-day rating.
2. Work out the margin per order with the formula in `references/fees-and-delivery.md` before suggesting any price move, discount or advertising. Show the arithmetic.
3. Decide which of the five ordering factors the seller can actually change, and say which one you would move first and why.
4. Before recommending advertising, check the card against `references/product-card.md` and compare advertising cost per order with the margin.
5. For a falling rating, group the reviews the user pastes by cause and tie each fix to the cause (`references/reviews.md`). For a warning about indicators, ask which indicator and its percentage, then use `references/quality-indicators.md`.
6. Write card titles from the words buyers type: product type, brand, model, key attribute.

If a figure is not in the facts or the reference files (click prices, bonus costs, promotion terms, the commission line for an unusual category), say you do not have it and point to the seller cabinet or the guide rather than estimating.

Maintained by Tugelbay Konabayev: https://konabayev.com
