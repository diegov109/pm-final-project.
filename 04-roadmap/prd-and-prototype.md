# PRD & Prototype Sprint (Module 4)

## Pick & scope with MoSCoW
- **The “Now” feature I’m scoping (name + one-line core description):** Spotlight Curated Rail, a hand-picked first row on the homepage that bypasses the algorithm.
- **My finalized Must-Haves (after overriding the AI):** -The rail is the first row for Wanderers
-8 hand-picked titles in a fixed editorial order
-Poster, title, and runtime on each card
-A “Spotlight, picked by our editors” label
-Tap to a title page, then Play
-An unavailable pick is replaced by the next one
- **What I demoted from Must → Should/Won’t, and why:** -Weekly editorial refresh and hiding watched titles (Must to Should): Wanderers watch about 1.1 sessions a week, so they won’t run out of picks in the first sprint.
-The “Why You’ll Love This” reason and Hidden Gem Badge (to Won’t): they’re separate roadmap features, and keeping them out means a lift in the A/B test can be traced to the rail.
-Personalized ordering (to Won’t): there’s little taste data for Wanderers, and users distrust “the algorithm.”

## Generate your Simplified PRD
- **One thing my PRD makes explicit that a vague brief would have missed:** The rail is in the same editorial order for every user and isn’t personalized. A vague brief that said “curated rail” would have let an algorithm creep back in, which is exactly what your interviewee distrusted.

## Prompt-to-prototype sprint
- **Where did the prototype reveal a gap in my PRD logic? (what I had to update):** The PRD covered tap to title page to Play, but not how the user gets back. Building it showed that a Wanderer who leaves a title page needs to land on the homepage with the rail still first, so I added that as requirement 7. Run your own tool’s output through your PRD too, because the gap you find there may be a different one.
- **My prototype, as a link or a screenshot (publish or share from your tool; in Lovable that is Share → Share Preview, in Bolt Publish → Web. No share URL? Screenshot the working flow):** https://claude.ai/artifact/R9Q4cd8hzH6xUb1yMMPgJ4
