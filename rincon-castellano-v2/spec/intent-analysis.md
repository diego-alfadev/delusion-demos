# intent-analysis · 2026-07-12T01:52:10.403Z

**Run:** b0f97acd-50ab-4e02-839d-d0b0016c2edd

## Request

dossier-derived enriched brief

## Agent notes & decisions

## VERIFIED FACTS (every entry MUST appear on the site — omission fails review like invention)
- phone: 622 48 84 07
- name: Restaurante Rincón Castellano
- category: Restaurante — asador / brasa y espetos
- hours_phrase: Abierto de lunes a domingo - mediodía, tarde y noche
- price_costillar: 15.50€
- price_chuleton: 32€
- price_espeto_pulpo: 29.50€
- price_espeto_sardina: 14€
- price_espeto_calamar: 39€
- whatsapp_link: bit.ly/reservasRC
- amenities: terraza grande, parrilla/brasa, zona infantil, parking, espacio eventos, chillout, barra de cócteles, rincón de helados, photocall de marca
- map_embedded: Google Maps embed present on landing
- reviews_embedded: Customer review screenshots with stars present on landing

## UNVERIFIED (off-limits — do not state, even generically)
- phone_incorrect: unverified — Documented incident: this number does not belong to the business and was used in a past demo causing a production patch. (do not state, not even generically)
- barrio: unverified — Marked as NO CONFIRMADO; suspected recycled text from another demo, not found in any primary source. (do not state, not even generically)
- social_followers: unverified — Single source (comparativa document), not reverified; insufficient verification. (do not state, not even generically)
- price_range: unverified — Single source (Google Maps), not confirmed by landing text or any second source. (do not state, not even generically)
- rating: unverified — Single source (Google Maps); landing does not display rating text, so not independently confirmed. (do not state, not even generically)
- address_street: unverified — Street and postal code only from one source (Google Maps); number not confirmed; landing only gives city. (do not state, not even generically)
- photo_count: unverified — Discrepancy between visual inspection (~15) and fetch (12+); no single verified number. (do not state, not even generically)

## PARITY CHECKLIST (implement each item, or drop it with a one-line justification)
- Real photos of food, terrace, kids area (minimum 12)
- WhatsApp and phone call CTAs, visually prominent and repeated
- Embedded customer reviews (screenshot format with stars)
- Embedded Google Map
- List of amenities: terrace, grill area, kids area, parking, events space, chillout, cocktail bar, ice cream corner, brand photocall
- Show menu with prices (at least costillar 15.50€, chuletón 32€, espeto de pulpo 29.50€, espeto de sardina 14€, espeto de calamar 39€)
- Display hours as the exact phrase: 'Abierto de lunes a domingo - mediodía, tarde y noche'
- No form-based reservation system (current landing relies on WhatsApp and phone only)

## CONVERSION MANDATES (render only in the structure given — never fabricate a shape the dossier lacks)
- Provide phone number 622 48 84 07 as the primary contact
- Provide WhatsApp link (bit.ly/reservasRC) as the main reservation channel
- Keep a self-hosted reservation form as an additional conversion advantage (improvement over current landing)
- Use the exact hours phrase: 'Abierto de lunes a domingo - mediodía, tarde y noche' (do not invent or use evasive alternatives)
- Reinforce the job 'contactar para reservar ya' by making WhatsApp and phone CTAs the most prominent actions
- Do not introduce other reservation channels (e.g., email) unless explicitly requested by the business
