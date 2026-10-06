# Exercise 1: design a useful radio experiment

Level: beginner · Format: planning worksheet · Hardware: none required

## Outcome

Write a test plan that somebody else could repeat. This exercise contains no transmissions or measured range claims.

## Choose a question

Example: 'Under the same test conditions, does moving one device change delivery success?'

Choose one variable to change. Keep device models, firmware, antenna setup, message size, permitted settings and test duration fixed where possible. Record any unavoidable differences.

## Record the plan

| Field | Your entry |
| --- | --- |
| Technology and question | |
| Hardware and firmware | |
| Antennas and power supply | |
| Authorized test area, described without private coordinates | |
| Region and verified permitted settings | |
| Message payload and number of attempts | |
| Timing and repetition method | |
| Variable changed and factors held fixed | |
| Delivery and latency measurement method | |
| Stop conditions and cleanup | |

## Practice with fictional data

If 18 of 20 attempted messages arrive, delivery success for that sample is `18 / 20 = 90%`. That small fictional sample does not prove a device's general reliability. Record duplicates, missing messages and timing consistently; repeat tests before drawing conclusions.

## Technology reading

LoRa and LoRaWAN describe different layers of a wireless system; [The Things Network introduction](https://www.thethingsnetwork.org/docs/lorawan/what-is-lorawan/) explains the distinction. [Meshtastic's introduction](https://meshtastic.org/docs/introduction/) describes its mesh project. Use the chosen project's hardware and setup documentation when turning the plan into a real test.

## Deliverable

A completed plan, a blank results table and one paragraph describing what the experiment cannot establish. Label all invented numbers as examples.
