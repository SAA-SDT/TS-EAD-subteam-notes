# Suggested posting to EAD Listserv, issue #517
 
## Email intro
Dear colleagues,

Following up on TS-EAS' (Technical Subcommittee on Encoded Archival Standards) intent to engage with 
the community on suggested new features in the context of the annual calendar for minor revisions, the EAD team
of TS-EAS is looking for community feedback on a suggested addition to EAD3 (see all details of the original proposal 
and the conversation so far on GitHub - https://github.com/SAA-SDT/EAD3/issues/517). 

To ensure that the standards under TS-EAS' purview continue to be based on user needs, we are specifically interested in any 
use cases from your institutions, which would support this change request.

In line with the annual calendar for minor revisions, we will gather your feedback and input until the deadline of 
Tuesday, 31 December 2019, including.

Thank you very much in advance.

## Further details provided with the email
### Summary
Suggestion to add &lt;objectxmlwrap&rt; as an alternative to &lt;did&rt; and its siblings within &lt;c&rt; 
(or numbered &lt;c01&rt; to &lt;c12&rt;)

### Intended new feature
Enable the integration of descriptive metadata from other namespaces (e.g. MARC, VRACode, NUDS, etc.), 
especially when describing single items of other domains, which are part of archival collections

### Options discussed so far
- Giving a choice between either &lt;c&rt;&lt;did&rt; or &lt;c&rt;&lt;objectxmlwrap&rt; to provide identifying descriptive information of a resource
  - This would be the result of the original suggestion.
  - The concern was raised that this would undermine even a minimal level of predictability for metadata exchange, given that EAD already is at the bare minimum of required data.
  - This change would likely constitute a MAJOR REVISION and might hence be put on hold until the next major revision of EAD3
- Using the currently available model of &lt;c&rt;&lt;did&rt; alongside &lt;c&rt;&lt;relations&rt; and make use of the &lt;objectxmlwrap&rt; element within &lt;relation&rt;
  - The question was raised whether establishing a “sameAs” relationship in this context would be conceptually sound.
  - This approach would not REQUIRE ANY CHANGES TO THE SCHEMA
- Adding &lt;objectxmlwrap&rt; as direct, optional sub-element of &lt;did&rt;
  - This suggestion went along with the precondition to still require at least one other sub-element within &lt;did&rt; (i.e. one element of the m.did group)
  - This change would likely constitute a MINOR REVISION and could hence be dealt with in the context of the current annual cycle.