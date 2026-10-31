# A/B Experiment Brief, StreamLine (B2C)

## Parameters
| Parameter | Decision |
|---|---|
| Feature under test | A1 Spotlight Curated Rail: a hand-picked homepage rail that bypasses the algorithm |
| Persona | Wanderer: casual subscriber (41% of the base), about 1.1 sessions a week, 61% of plays from trending |
| Expected outcome | More Wanderer sessions reach 30+ minutes because they find something worth watching |
| Primary success metric | 30+ minute session rate among Wanderers |
| Baseline rate | 11% of sessions reach 30+ minutes (down from 19% six months ago) |
| Guardrail metric | Power User sessions per week (4.8) |
| Guardrail boundary | Must not drop more than 5% (below about 4.6 sessions a week) |
| Second guardrail | Overall daily active users (1.49M) must not drop more than 2% |
| Minimum Detectable Effect | +2 pts (11% to 13%) |
| Sample size per arm | 4,144 |
| Traffic split | 50/50 |
| Test duration | 14 days (two full weekly cycles) |
| Significance threshold | p < 0.05 (95%) |

## Control vs. Variant
- **Control (A):** The homepage today. Wanderers scroll rows that are 61% trending, can’t tell what’s worth watching, and leave before pressing play. Only 11% of sessions reach 30+ minutes, and only 34% of searches end in a play.
- **Variant (B):** The same homepage with one hand-picked Spotlight Curated Rail added as the first row. Nothing else changes.
- **Held constant (isolation check):** App version, the recommendation engine and every other row, search, notifications, onboarding, pricing, the content catalog, and the existing Spotlight entry points. The other Now features (A2 label and A3 badge) must not ship to either arm during the test, or you won’t know which one caused the lift.

## Hypothesis
> I believe that A1 Spotlight Curated Rail: a hand-picked homepage rail that bypasses the algorithm for Wanderer: casual subscriber (41% of the base), about 1.1 sessions a week, 61% of plays from trending will result in More Wanderer sessions reach 30+ minutes because they find something worth watching, as measured by a +2 pts (11% to 13%) change in 30+ minute session rate among Wanderers within 14 days (two full weekly cycles). We will protect Power User sessions per week (4.8) throughout the test.

## Shipping criteria
> We will **ship** if 30+ minute session rate among Wanderers improves by ≥ +2 pts (11% to 13%) at p < 0.05 (95%) and Power User sessions per week (4.8) does not reach Must not drop more than 5% (below about 4.6 sessions a week) after 14 days (two full weekly cycles).
> We will **iterate** if direction is positive but lift is below the MDE.
> We will **kill** if the primary metric shows no improvement or moves negatively.
> The read date is fixed at the end of 14 days (two full weekly cycles), no results reviewed before this date.
