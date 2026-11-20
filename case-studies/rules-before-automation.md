# Rehearse a rule before trusting it

I chose to make a customer rule an explicit, reviewable object. A historical rejection can be useful evidence, but it should not silently become a universal policy for every later invoice.

The workflow separates recording an example, drafting a sourced rule, rehearsing it against examples and publishing a version. A batch check can then identify the rule and version behind its result. Recovery follows the same principle: an imported rule does not become active simply because it was present in a backup.

The tradeoff is a narrower product with manual setup and review. That boundary keeps the prototype assessable before adding document parsing, external accounting systems or automatic communication. Real pilot measurements and customer decisions should determine whether expansion is worthwhile.
