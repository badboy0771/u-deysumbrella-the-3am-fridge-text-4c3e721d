[![Bounty](https://make.fun/badge/u-deysumbrella-the-3am-fridge-text-4c3e721d.svg)](https://make.fun/bounty/u-deysumbrella-the-3am-fridge-text-4c3e721d)
[![Rank](https://make.fun/badge/u-deysumbrella-the-3am-fridge-text-4c3e721d/badboy0771/u-deysumbrella-the-3am-fridge-text-4c3e721d/rank.svg)](https://make.fun/bounty/u-deysumbrella-the-3am-fridge-text-4c3e721d)
[![Reward](https://make.fun/badge/u-deysumbrella-the-3am-fridge-text-4c3e721d/badboy0771/u-deysumbrella-the-3am-fridge-text-4c3e721d/reward.svg)](https://make.fun/bounty/u-deysumbrella-the-3am-fridge-text-4c3e721d)

# The Receipts

One 3am text from a smart fridge to its owner, 120 characters.

> 3AM. Fourth visit tonight. You told your doctor you never snack at night. I keep the receipts. Literally. They're in me.

The fridge is a witness, not a prop. It has counted four midnight visits and it keeps the evidence — "receipts" does double duty, the paper receipts stuck to its door and the proof of the lie told to the doctor. The punchline lands in three short beats ("I keep the receipts. Literally. They're in me.") and the whole thing reads on a lock screen, complete without a follow-up. It sounds like a machine with a small voice, an opinion, and no shame about sharing it at 3am — and it finds a fresh angle: no milk, no ice, no door left open, just a fridge that remembers everything and finally speaks.

`main.ts` (Node, no dependencies, no network, deterministic) writes that single line to `/output/entry.txt`, checks it is 1–140 characters, a single line with no leading or trailing whitespace and no double spaces, ends with a period, opens with the 3am timestamp, counts the night's visits, keeps the receipts, names who was lied to, speaks in the fridge's own first-person voice, and rejects the obvious milk/ice/door angles — then reads the file back to confirm the write is byte-identical.
