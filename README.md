# netflix-paid-sharing-did
Estimating the Causal Effect of Netflix's Paid Sharing Rollout


## Known Limitations

**No true control group.** Netflix rolled out paid sharing to nearly every market it operates in, so this analysis has no "never-treated" countries to serve as a clean baseline. Instead, it uses a staggered adoption design: later-wave countries act as temporary controls for earlier-wave countries, before their own treatment kicks in. This is a standard and accepted approach in DiD, but it means every comparison group is itself treated eventually.

**Rollout dates mark the start, not full completion.** The May 23, 2023 date for Wave 4 (103 countries) reflects when Netflix announced and began the expansion, not necessarily simultaneous, complete rollout in every one of those markets on that exact day. The U.S. rollout in particular was delayed multiple times before landing on this date. Treatment dates should be treated as reasonable approximations rather than precise, verified per-country cutovers.