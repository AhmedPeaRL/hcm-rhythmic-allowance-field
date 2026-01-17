## Allowance Invariants

The following invariants must never be violated:

1. No event may cause state accumulation.
2. No interaction may generate intent.
3. No response may be considered necessary.
4. No silence may be treated as failure.
5. No motion may be classified as signal.
6. No signal may demand acknowledgment.

If an implementation attempts to violate any invariant,
it is considered rhythmically invalid,
even if technically correct.
