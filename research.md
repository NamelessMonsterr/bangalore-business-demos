# Bangalore small-business demo website research
1 October 2026

Build three distinct, mobile-first sites around the task each customer wants to finish. Gym: decide whether the training fits, compare memberships, then request a trial. Salon: see the aesthetic, compare services and starting prices, then request an appointment. Cafe: inspect the menu, understand the space, then find hours and location. Visual polish should support those tasks, not bury them.

## Design choices
| Demo | Visual direction | Flow | Primary action |
| Gym | Charcoal, acid lime, bold uppercase typography, large training photograph | Hero, training options, weekly schedule, membership comparison, beginner FAQ, trial preview | Try a session |
| Salon | Warm ivory, burgundy, editorial serif, portrait crops and generous whitespace | Hero, service categories and prices, gallery, appointment process, FAQ, appointment preview | Choose a service |
| Cafe | Cream, forest green, warm coffee photography, playful serif | Hero, filterable priced menu, atmosphere/story, hours and neighbourhood, visit preview | Explore the menu |

## Research findings
- Zenoti recommends a visible booking action, categorized service prices, real-work galleries, team context and contact/hours. It is a booking vendor, so its advice has commercial incentives. Its mobile percentage and conversion claims were not independently validated and are not used as promised results.
- Vurve demonstrates explicit INR service menus, starting/length-dependent prices and WhatsApp enquiries. Our salon uses original illustrative prices, not copied Vurve prices.
- MASIV and Lotus demonstrate the importance of training categories, beginner guidance, included membership benefits and local facility context. Their business claims are operator claims, not independently audited.
- 6oz prioritizes menu, directions, neighbourhood, hours and coffee categories. Its review claims were not checked and are not reproduced. A cafe visitor should not have to download a PDF to see basic menu items.
- Nielsen Norman Group recommends visible desktop navigation, familiar labels and strong contrast. Mobile navigation must stay easy to find and operate.
- web.dev recommends flexible responsive layouts, allowing zoom, logical source order and roomy touch targets. We choose 48px main controls, visible focus styles, semantic HTML and reduced-motion support.
- web.dev performance guidance supports small JavaScript, early discovery of the hero image, and explicit dimensions to avoid layout shift. We choose static HTML, local embedded compressed photography, no framework runtime, no trackers, no autoplay video and no external font dependency.

## Tradeoffs and limits
The best-performing design cannot be established from visual research alone. These are reasoned starting points, not proven conversion winners. Measure actual enquiries, qualified leads and page speed after a real launch. Real sites need verified service prices, owner-approved photography, real reviews with permission, contact details, policy text and a working booking/contact destination. Demo preview interactions send nothing and collect no personal information. No fake testimonials, ratings, client counts or guaranteed fitness outcomes are included.

## Sources
1. Zenoti, Salon Website Design. Vendor guide. https://www.zenoti.com/salon-website-design
2. Nielsen Norman Group, Menu-Design Checklist: 17 UX Guidelines, 7 June 2024. Independent UX guidance. https://www.nngroup.com/articles/menu-design/
3. Google web.dev, Accessible responsive design, updated 31 March 2020. Technical guidance. https://web.dev/articles/accessible-responsive-design
4. Google web.dev, The most effective ways to improve Core Web Vitals. Technical guidance. https://web.dev/articles/top-cwv
5. MASIV. Bangalore operator example. https://masiv.in/
6. Vurve, Salon Price List & Service Menu. Operator example. https://vurvesalon.com/menu/
7. 6oz Coffee. Bangalore operator example. https://6oz.coffee/
8. Lotus Fitness, Membership and Services. Bangalore operator example. https://www.lotusfitness.in/membershipandservices

All eight pages were fetched and read before building. Observed online 1 October 2026. Source patterns inspired the information architecture; wording and fictional branding are original.


## Photography credits
Gym: George Pagan III. https://unsplash.com/photos/gym-equipment-inside-room-iDJoeqe5Lug
Salon: Guilherme Petri. https://unsplash.com/photos/photo-of-saloon-interior-view-PtOfbGkU3uI
Cafe photo source: https://images.unsplash.com/photo-1495474472287-4d71bcdd2085
Stock photography illustrates mood only, not these fictional businesses.
