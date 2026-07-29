# Estimating the Causal Effect of Netflix's Paid Sharing Rollout


## Known Limitations

**No true control group.** Netflix rolled out paid sharing to nearly every market it operates in, so this analysis has no "never-treated" countries to serve as a clean baseline. Instead, it uses a staggered adoption design: later-wave countries act as temporary controls for earlier-wave countries, before their own treatment kicks in. This is a standard and accepted approach in DiD, but it means every comparison group is itself treated eventually.

**Rollout dates mark the start, not full completion.** The May 23, 2023 date for Wave 4 (103 countries) reflects when Netflix announced and began the expansion, not necessarily simultaneous, complete rollout in every one of those markets on that exact day. The U.S. rollout in particular was delayed multiple times before landing on this date. Treatment dates should be treated as reasonable approximations rather than precise, verified per-country cutovers.

**Treatment dates vary in precision by wave.** Waves 1, 2, 3, and 5 are backed by specific, well-documented press dates. Wave 4 (the May 23, 2023 global expansion covering ~103 countries) is treated as a single simultaneous rollout date across all included countries, consistent with how Netflix itself communicated the change — press coverage and Netflix's own announcements describe it as one coordinated global launch rather than a staggered per-country schedule. It's possible some countries in this wave saw slight day-to-day variation in actual enforcement, but no public source documents this at a finer grain, and Google Trends' weekly resolution wouldn't be able to detect day-level differences even if it existed.

**Outcome variable is a behavioral proxy, not ground truth.** Google Trends search interest approximates user reaction to the policy change, but it isn't a direct measure of subscriptions, cancellations, or revenue. Spikes or dips in search interest can also be driven by unrelated events (major show releases, news coverage, pricing changes), which parallel-trends and placebo checks help rule out but can't fully eliminate.