## Implementation Notes

This repository may remain entirely declarative.

If code is introduced:
- It must not evaluate success.
- It must not persist outcomes.
- It must not optimize behavior.

Timers are allowed.
Listeners are allowed.
Observers are allowed.

Controllers are forbidden.
Schedulers are forbidden.
Optimizers are forbidden.

Any implementation must be removable
without altering system meaning.
