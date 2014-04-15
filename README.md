## Stash

Stash is an evolving list of technologies that may or may not be interesting.  It provides,

- A list of technologies worth looking into
- A catalogue of technologies that are niche but may eventually be useful
- A catalgoue of observations and evaluations around technologies that may help inform decisions in the future

Rather than build a fancy backend this list utilises the existing power of Github issues, its fuzzy matching, labeling and commenting features all make it a the perfect backend for this sort of list management.  Combined with v3 of the GitHub API it is possible to build static front ends on top of this issue store.

### Concept Mappings

We have taken the concept of content list that contains textual information and associated metadata (tags, comments, statuses) and attempted to map it to the issue model.  As such somethings might be better documented here to clear up any confusion (wihtout out a focused UI to map the issue model back to the original domain we are forced to accept certain UX sacrifices).

- __Open/Closed__ - Wether the status of an issue is open or closed determines if the technology in question is __deprecated__.  Anything that has fallen out of favour based on previous experience or some other serious issue will be closed meaning that it is no longer recommended to use.  Open issues are the opposite.  Not necessarily __recommended__ but in a state of being __not rejected__ so to speak.
- __Labels__ - tags associated with the technology to aid filtering and grouping.  Shouldn't be taken overboard (presently there may be too many tags, and not entirely obvious)
- __Milestones__ - TBH.  Possibly the status.
