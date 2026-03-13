# Homestead Seoul UX Strategy

## A. Brand and UX positioning summary
- Homestead Seoul should feel like a clean, calm, trustworthy solo-living option in Seoul: more premium-basic than budget, more practical than aspirational, and more private-room urban living than hotel or guesthouse.
- Korean and English pages should share one brand system but diverge in conversion logic because the audience starts from different levels of understanding.
- Korean users already understand the gosiwon category, so the page should optimize for compare > decide > inquire with rent, deposit, fee clarity, room differences, and fast action.
- English users often do not understand the category, so the page should optimize for understand > trust > inquire with clear explanation, private-room reassurance, included items, and move-in simplicity.
- Korean should feel direct, efficient, comparison-friendly, and move-in practical.
- English should feel explanatory, welcoming, reassuring, and long-stay friendly.

## B. Design system direction
- Color palette: warm white `#f6f2eb`, soft off-white surfaces `#fffdf9`, sand and beige accents `#efe7db`, muted taupe line color `#d8d0c5`, charcoal text `#23201c`, calm sage accent `#617567`.
- Typography direction: modern sans with strong readability; use a Korean sans such as Noto Sans KR and a neutral geometric English sans such as Plus Jakarta Sans so both languages feel aligned without becoming identical.
- Layout principles: large horizontal breathing room, rounded cards, soft section containers, grid-based comparison blocks, and generous spacing between message zones.
- Card style: warm white cards, 1px taupe border, soft elevated shadow, 20-28px radius, clear internal hierarchy, and restrained highlight areas instead of loud gradients.
- Button style: pill-shaped, high-contrast primary sage button, soft surface secondary button, one ghost tertiary button for lower commitment actions.
- Icon style: simple line icons, no emoji, no heavy fill, and consistent visual weight to support a premium-basic tone.
- Image treatment: real, bright, honest images with minimal filtering; show room depth, hallway cleanliness, and exterior clarity; avoid cinematic crops that make rooms feel misleadingly large.
- Mobile responsiveness direction: preserve airy spacing, keep CTA clusters visible without crowding, convert desktop comparison layouts into stacked cards, and use a persistent mobile CTA bar.

## C. Korean homepage information architecture
- Section order: Hero -> Quick Facts summary bar -> Pricing & Terms -> Room Collections -> Room Inventory -> Real Photos -> Included -> Location -> Move-In Flow -> FAQ -> Inquiry.
- This order fits Korean users because it starts with cost and conditions, then immediately supports room comparison, then confirms practicality and location before asking for contact.
- Pricing appears before the deeper room browse because Korean users typically filter by budget first.
- Inquiry comes after enough comparison data to support immediate action without over-explaining the category.

## D. English homepage information architecture
- Section order: Hero -> What It Is -> Included -> Real Photos -> How Move-In Works -> Room Collections -> Room Inventory -> Pricing -> Location -> FAQ -> Inquiry.
- This order fits English users because it explains the concept before asking them to compare room tiers.
- Included and move-in sections appear earlier to reduce uncertainty for foreigners unfamiliar with Seoul housing terminology.
- Pricing comes later because the English page first needs to build trust around what the product actually is.

## E. Korean homepage wireframe
- section name: Hero
- objective: Establish private-room solo-living positioning and trigger immediate inquiry or room comparison.
- recommended content: One-line category label, direct headline, 4 practical chips, 3-photo desktop composition, Naver-focused primary CTA, room-compare secondary CTA, phone tertiary CTA.
- tone of voice: Direct, grounded, practical, trust-building.
- CTA priority: `네이버 문의` -> `객실 비교 보기` -> `전화 문의`
- desktop-first wireframe: Left column copy and CTA cluster, right column 1 large room image plus 2 stacked supporting images.
- mobile-first behavior note: Keep headline and 2 CTAs above the fold; collapse visual to 1 main image with 2 smaller cards below.

- section name: Quick Facts summary bar
- objective: Let experienced Korean users scan cost structure and stay rules in seconds.
- recommended content: Monthly range, deposit, management fee, no extra utility charges, minimum stay.
- tone of voice: Efficient and comparison-led.
- CTA priority: None inside the bar; it supports the next pricing section.
- desktop-first wireframe: Five equal stat cards in one row.
- mobile-first behavior note: Stack into 2-column then 1-column cards while keeping value first and note second.

- section name: Pricing & Terms
- objective: Remove friction around rent, deposit, and management fee structure.
- recommended content: S/A/B pricing rows, separated monthly rent and management fee, deposit rule, A+ room note, no-utilities note.
- tone of voice: Clear, matter-of-fact, reassuring through precision.
- CTA priority: Soft link to inquiry after comparison.
- desktop-first wireframe: Left side pricing rows, right side rule card with deposit/minimum stay/utility notes.
- mobile-first behavior note: Convert each tier into its own stacked pricing card with one rule card underneath.

- section name: Room Collections
- objective: Make room selection feel structured and premium without pushing low-priced rooms down.
- recommended content: Signature Quiet Rooms, Spacious Rooms, Practical Rectangular Layouts, Bright Bathroom Window Rooms.
- tone of voice: Organized, premium-basic, selection-oriented.
- CTA priority: `호실별 비교` anchor.
- desktop-first wireframe: Four collection cards in a 2x2 or 4-column layout.
- mobile-first behavior note: Single-column swipe-like card rhythm, short copy, room numbers visible immediately.

- section name: Room Inventory
- objective: Help users compare individual rooms fast.
- recommended content: Room number, tier, positive tag, quick price presentation, 3 key features, room filter chips.
- tone of voice: Short, factual, easy to scan.
- CTA priority: `이 객실 문의` -> `가격 보기`
- desktop-first wireframe: 3-column card grid with filter bar above.
- mobile-first behavior note: Filter bar becomes horizontal wrap; cards stay full-width with CTA buttons pinned near the bottom of each card.

- section name: Real Photos
- objective: Build trust through honest visuals.
- recommended content: Six actual photos with room overview, hallway, essentials, and exterior.
- tone of voice: Quiet and factual.
- CTA priority: None; trust section.
- desktop-first wireframe: 3-column gallery grid.
- mobile-first behavior note: 2-column grid with tap-to-enlarge modal.

- section name: Included
- objective: Confirm move-in practicality after users compare pricing and rooms.
- recommended content: Private bathroom, kitchenette/kitchen access note, washer, fridge, bed, microwave, table/chair, bedding and supplies.
- tone of voice: Practical and concise.
- CTA priority: Soft move-in anchor.
- desktop-first wireframe: Amenity grid above, three promise cards below.
- mobile-first behavior note: Keep icon, heading, description in one compact stack with strong spacing between cards.

- section name: Location
- objective: Prove commute convenience.
- recommended content: Bangbae Station access, Gangnam-side practicality, Sadang transfer logic, daily routine fit.
- tone of voice: Functional, commute-first.
- CTA priority: `문의하기`
- desktop-first wireframe: Map left, location value card right.
- mobile-first behavior note: Show summary bullets before the full-height map if viewport is short.

- section name: Move-In Flow
- objective: Remove hesitation for immediate move-in users.
- recommended content: Availability check, price confirmation, schedule coordination, move-in start.
- tone of voice: Fast and low-friction.
- CTA priority: `빠른 문의`
- desktop-first wireframe: 4 horizontal step cards.
- mobile-first behavior note: Vertical numbered steps with short copy.

- section name: FAQ
- objective: Catch the last practical objections.
- recommended content: 1-person-only rule, minimum stay, deposit, fee structure, quiet rooms, A+ room note.
- tone of voice: Plain and confident.
- CTA priority: `문의 보내기`
- desktop-first wireframe: Single accordion column.
- mobile-first behavior note: Large tap targets and short answers above the fold.

- section name: Inquiry
- objective: Convert users who already know what they want.
- recommended content: Naver, Kakao, phone, email cards plus inquiry form.
- tone of voice: Immediate and action-oriented.
- CTA priority: `네이버 문의` -> `카카오톡` -> `전화`
- desktop-first wireframe: Contact cards on the left, inquiry form on the right.
- mobile-first behavior note: Contact cards appear before the form and a sticky CTA bar remains visible.

## F. English homepage wireframe
- section name: Hero
- objective: Position the property as furnished solo long-stay living in Seoul.
- recommended content: Explanatory headline, reassurance subtitle, private-room chips, availability CTA, WhatsApp CTA, view-rooms CTA.
- tone of voice: Calm, welcoming, explanatory.
- CTA priority: `Check availability` -> `WhatsApp` -> `View rooms`
- desktop-first wireframe: Left column copy, right column photo collage with room-led imagery.
- mobile-first behavior note: Keep the first two CTAs visible immediately and avoid a long intro paragraph.

- section name: What It Is
- objective: Explain the category without sounding cheap.
- recommended content: Private room for one person, 14-day minimum, practical long-stay living, not hotel/hostel framing.
- tone of voice: Reassuring, plain-language, low-jargon.
- CTA priority: None.
- desktop-first wireframe: Three equal concept cards in one row.
- mobile-first behavior note: Single-column explanatory cards with short headings.

- section name: Included
- objective: Show what daily life already includes.
- recommended content: Private bathroom, kitchen setup note, washer, fridge, bed, microwave, work/eating surface, bedding and basics.
- tone of voice: Helpful, concrete, non-salesy.
- CTA priority: `Check availability`
- desktop-first wireframe: 4-column amenity grid plus three trust cards below.
- mobile-first behavior note: Prioritize essentials in the first 4 cards, then let users continue scrolling for the rest.

- section name: Real Photos
- objective: Reinforce authenticity and reduce size anxiety.
- recommended content: Bright room overview, circulation, hallway, exterior.
- tone of voice: Honest and visual.
- CTA priority: None.
- desktop-first wireframe: Simple 3-column grid with click-to-enlarge.
- mobile-first behavior note: 2-column gallery with large hit areas.

- section name: How Move-In Works
- objective: Reduce friction for international guests unfamiliar with the process.
- recommended content: Send dates, check matching rooms, confirm price and deposit, move in with essentials ready.
- tone of voice: Reassuring and straightforward.
- CTA priority: `Check availability`
- desktop-first wireframe: 4 horizontal step cards.
- mobile-first behavior note: Vertical flow with clear step numbering and short copy blocks.

- section name: Room Collections
- objective: Offer a structured way to browse without real-estate-portal clutter.
- recommended content: Quiet rooms, spacious rooms, rectangular layouts, bathroom-window rooms.
- tone of voice: Curated and calm.
- CTA priority: `View room list`
- desktop-first wireframe: Four premium cards with short collection logic.
- mobile-first behavior note: Single-column cards with room numbers and one strong value sentence each.

- section name: Room Inventory
- objective: Let foreign users understand room differences at a glance.
- recommended content: Room number, tier, positive tag, monthly price presentation, 3 quick features.
- tone of voice: Clear, simple, comparison-friendly without jargon.
- CTA priority: `Ask about this room` -> `See pricing`
- desktop-first wireframe: 3-column card grid with filters above.
- mobile-first behavior note: Filters wrap into multiple rows and each card becomes a clear full-width decision block.

- section name: Pricing
- objective: Present a trustworthy all-in monthly cost.
- recommended content: S/A/B monthly totals, deposit, utilities included, A+ room note, single occupancy rule.
- tone of voice: Transparent and reassuring.
- CTA priority: `Check availability`
- desktop-first wireframe: Tier rows left, rules summary right.
- mobile-first behavior note: Each tier becomes a stacked all-in card with deposit and utilities directly beneath the price.

- section name: Location
- objective: Communicate subway access and daily practicality rather than tourist hype.
- recommended content: Bangbae Station access, Line 2 usefulness, Sadang transfer logic, fit for interns/students/nomads.
- tone of voice: Calm and practical.
- CTA priority: `Contact`
- desktop-first wireframe: Map left, neighborhood-fit card right.
- mobile-first behavior note: Bullet points come before the map if needed to protect speed and readability.

- section name: FAQ
- objective: Answer common foreigner questions before inquiry.
- recommended content: Not a hotel/hostel, private bathroom, what is included, minimum stay, utilities, one person only.
- tone of voice: Friendly and direct.
- CTA priority: `Send inquiry`
- desktop-first wireframe: Single accordion column.
- mobile-first behavior note: Keep question labels short and answers plain-language.

- section name: Inquiry
- objective: Convert after the user understands the offer.
- recommended content: Email, WhatsApp, Kakao, phone cards plus inquiry form.
- tone of voice: Welcoming and low-pressure.
- CTA priority: `Email` / `WhatsApp` / form submit
- desktop-first wireframe: Contact methods left, inquiry form right.
- mobile-first behavior note: Show the contact cards first, keep the sticky availability CTA visible, and make the form short.

## G. Hero design recommendations
- Korean: headline style should be short, direct, and utility-led, such as “서울에서 조용하고 실용적인 1인실”.
- Korean: supporting text should summarize private bathroom, 14-day minimum, deposit, and no extra utility charges in one compact paragraph.
- Korean: visual composition should show one strongest room image with two supporting images that suggest layout truth and property upkeep.
- Korean: CTA arrangement should prioritize Naver inquiry first, room comparison second, phone third.
- English: headline style should explain the offer in plain language, such as “Furnished private rooms in Seoul for solo stays”.
- English: supporting text should define the stay type, reassure privacy, and explain longer-stay suitability.
- English: visual composition should still feel airy and premium-basic, but the image captions should reinforce clarity and trust.
- English: CTA arrangement should prioritize availability inquiry first, WhatsApp second, and room browsing third.

## H. Room card template
- room name/number: `201호` / `Room 201`
- tag or highlight: `시그니처 정숙` / `Signature quiet`
- room tier: S, A+, A, or B
- price presentation: Korean should show `월 총액` first with small split note underneath; English should show the all-in monthly total only.
- key features: 3 short bullets max, such as `대형 타입`, `욕실 창`, `조용함 우선`
- image layout recommendation: one honest 4:3 or 7:5 image at the top, no decorative collage inside the card itself
- CTA placement: primary CTA directly under the feature list, secondary CTA to pricing or inquiry placed beside it

## I. Pricing presentation recommendation
- Compare all-in pricing vs split pricing: all-in is cleaner and more trust-building for unfamiliar users; split pricing is better for Korean housing comparison because users expect rent/management structure.
- Recommend by audience type: Korean users should see split pricing with the total prominently visible; English users should see all-in monthly pricing.
- Suggest exact label wording: Korean `월 총액 100만원 / 기본 월세 90만원 + 관리비 10만원 / 공과금 추가 없음`.
- Suggest exact label wording: English `KRW 1,000,000 / month all-in / no extra utility charges`.
- Suggest exact label wording: Deposit `보증금: 기본 월세 1개월분` for Korean and `Deposit: 1 month rent` for English.
- Suggest exact label wording: Minimum stay `최소 14일` and `Minimum stay: 14 days`.

## J. Navigation and CTA recommendations
- Korean nav labels: 가격, 객실, 구성, 위치, FAQ, 문의
- English nav labels: About, Included, Rooms, Pricing, FAQ, Contact
- Korean CTA labels: 네이버 문의, 객실 비교 보기, 전화 문의, 이 객실 문의, 문의 보내기
- English CTA labels: Check availability, WhatsApp, View rooms, Ask about this room, Send inquiry

## K. FAQ topic recommendations
- Korean FAQ topics: 1인실 여부, 최소 거주 기간, 보증금 기준, 관리비와 공과금, 가장 조용한 객실, A+ 객실 가격 안내
- English FAQ topics: Is this a hotel or hostel, Do I get a private bathroom, What is included, Minimum stay, Are utilities extra, Can two people stay in one room

## L. Content guidance
- how to describe the concept in Korean: `서울에서 혼자 지내는 사람을 위한 조용하고 실용적인 1인 전용 프라이빗룸`
- how to describe the concept in English: `a calm, furnished private-room option in Seoul for one person at a time, designed for stays of 14 days or longer`
- how to explain “gosiwon” in English without sounding cheap or low quality: describe it as `compact private-room urban living` or `private-room long-stay housing in Seoul`, then clarify that every room is single-occupancy and privately furnished
- Avoid English phrases like `cheap hostel`, `budget bunk`, or `capsule-style stay`.
- Avoid Korean phrases that sound too portal-like, such as overloading the interface with listing jargon before the user sees the room logic.

## M. Consistency vs localization
- what should remain the same across both versions: brand palette, typography system, photo style, component language, room data, trust logic, actual business rules, and visual quality level
- what should change across both versions: section order, headline framing, CTA hierarchy, pricing presentation model, explainer depth, FAQ priorities, and contact-method emphasis
- The Korean site should feel like a polished solo-housing decision page.
- The English site should feel like a trustworthy furnished-room landing page for temporary living in Seoul.

## N. Bonus
- Sample homepage content outline for Korean: Hero `서울에서 조용하고 실용적인 1인실` / Room section intro `조용한 객실, 넓은 객실, 직사각형 객실을 기준으로 바로 비교하세요.` / Pricing intro `월 총액과 보증금 구조를 먼저 확인할 수 있게 정리했습니다.` / FAQ intro `입주 전에 가장 많이 확인하는 질문을 모았습니다.`
- Sample homepage content outline for English: Hero `Furnished private rooms in Seoul for solo stays` / Room section intro `Choose by quietness, room shape, or overall spaciousness.` / Pricing intro `All-in monthly pricing makes the stay easier to understand at a glance.` / FAQ intro `Here are the questions most international guests ask before they inquire.`
