# Claude's pick: v5 — Neighbourhood Story

**Job:** before signing a lease, know in plain words whether this exact spot will work for *my* business.
**Audience / scene:** first-time small-business owners, on a phone, anxious, not analysts.

## Why v5

1. **It passes the 5-second test on the phone by showing, not telling.** The first thing a visitor reads
   is a real verdict in plain English: “A pharmacy on Vía Argentina? Good spot.”, with 74/100 and medium
   confidence right above it. The product's value *is* the headline. No dashboard, no form wall.
2. **The flow sits in thumb reach from the first second, one question at a time.** The bottom dock asks
   for the address first, then the business. Tapping a business runs the check. That is two small, calm
   steps for a nervous non-expert, instead of a dense form. The answer then replaces the sample in place
   (same quote, same map), so "this is what you'll get" and "this is yours" look the same.
3. **The reasons sit on the street they come from.** Handwritten notes on the neighbourhood map
   ("Busy all day ↑", "Only 2 pharmacies ↑", "Quiet evenings ↓", "Calle Uruguay: 79 — worth a look") make
   the reasons concrete and local, which is what someone who knows their street will trust. Missing data and
   "what would change it" are in the full answer below. It also passes the invisible-platform test best:
   plaster pink, Pacific blue, a serif quote and a hand-drawn layer. None of the other three sites can wear that.

**Did English change the judgement?** No — it strengthened it. The English verdict reads as a natural spoken
question-and-answer, and the hand layer moved from Amatic SC to Caveat, which stays legible at phone size
(~19px). The English short labels are longer than the Hebrew ones, so two of the notes now wrap onto two
balanced lines by design.

## Borrow from the runner-up (v1 — Street Sign)

v1's yellow verdict plate keeps the verdict, the reasons, **what would change it** and the alternative in
one scannable block. In v5 "what would change it" sits below the fold. Bring one line of it up under the
quote in the hero (e.g. "What would change it: a third pharmacy on the block → ~66"). Then the first screen
alone carries the verdict, the reasons and the condition.

## Known limits of v5 (to fix in refinement)
- The map is a stylised illustration. In production it would be the real map kit with a hand-annotation layer.
- Notes use fixed anchor spots. When the user's corner moves (e.g. Calle Uruguay), a note can land on the
  catchment or a street label. Notes need simple collision avoidance, and testing with the longest Spanish labels.
- The "worth a look" note is placed per alternative from a small table; a real build should anchor it to the
  alternative's map position.

Sample data (Panama City) is for the mockup only.
