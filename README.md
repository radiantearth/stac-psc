# STAC Project Steering Committee

This document describes how the STAC (SpatioTemporal Asset Catalog) Project Steering Committee makes decisions on STAC and STAC API project issues. STAC is concerned with the following GitHub repositories and organizations:
- [stac-spec](https://github.com/radiantearth/stac-spec)
- [stac-api-spec](https://github.com/radiantearth/stac-api-spec)
- [stac-extensions](https://github.com/stac-extensions)
- [stac-api-extensions](https://github.com/stac-api-extensions)

In brief the committee votes on proposals on <https://github.com/radiantearth/stac-psc/issues>. Proposals are available for review for at least five business days, and a single veto is sufficient to delay progress though ultimately a majority of members can pass a proposal.

## Members

The list of members of the Project Steering Committee is:

* Chris Holmes (chair, [@cholmes](https://github.com/cholmes))
* James Banting ([@jbants](https://github.com/jbants))
* Matthew Hanson ([@matthewhanson](https://github.com/matthewhanson))
* Rob Emanuele ([@lossyrob](https://github.com/lossyrob))
* Matthias Mohr ([@m-mohr](https://github.com/m-mohr))

The current list will be maintained by the Radiant Earth team ([@radiantearth](https://github.com/radiantearth)) and will also be published to the STAC web page.

## Detailed Process

1. Proposals are written up and submitted on <https://github.com/radiantearth/stac-psc/issues/new/choose> for discussion and voting, by any interested party, not just committee members.
2. Proposals need to be available for review for at least five business days before a final decision can be made. Public holidays count as business days.
3. Respondents may vote `+1` to indicate support for the proposal and a willingness to support implementation.
4. Respondents may vote `-1` to veto a proposal, but must provide clear reasoning and alternate approaches to resolving the problem within the five business days.
5. A vote of `-0` indicates mild disagreement, but has no effect. A `0` indicates no opinion. A `+0` indicates mild support, but has no effect.
6. Anyone may comment on proposals on the list, but only members of the Project Steering Committee’s votes will be counted.
7. A proposal will be accepted if it is accepted by the majority of members (including the proposer) and no vetoes (-1) or has not received enough votes in 20 business days.
8. If a proposal is vetoed, and it cannot be revised to satisfy all parties, then it can be resubmitted for an override vote in which a majority of all eligible voters indicating +1 is sufficient to pass it. Note that this is a majority of all committee members, not just those who actively vote.
9. Upon completion of discussion and voting the proposer should announce whether they are proceeding (proposal accepted) or are withdrawing their proposal (vetoed).
10. The Chair gets a vote.
11. The Chair is responsible for keeping track of who is a member of the Project Steering Committee.
12. Addition and removal of members from the committee, as well as selection of a Chair should be handled as a proposal to the committee.
13. The Chair adjudicates in cases of disputes about voting.

### When is Vote Required?

Generally speaking, technical decisions should be made by consensus within STAC components. However, if a decision cannot be decided by consensus of the committers involved in the component, any committer can request the decision be brought to a vote of the STAC PSC. Technical decision that would be suitable for such a process include:

* Any change to PSC membership (new members, removing inactive members)
* Anything that could cause backward compatibility issues in normative specifications (e.g., any of the specifications).
* Adding or changing substantial amounts of the normative specifications.
* Issues of procedure (e.g. changes to these guidelines).
* When stable releases should take place.
* Strategic decisions regarding the project and anything that might be controversial.

### Final remarks

* The Chair is the ultimate adjudicator if things break down.
* The maximum number of PSC members is 7.
* The maximum number of PSC members per company is 2.
* The absolute majority rule can be used to override an obstructionist veto, but it is intended that in normal circumstances vetoers need to be convinced to withdraw their veto. We are trying to reach consensus.

## Committee Membership

### Adding Members

Any member of the STAC PSC or anyone with contributions to the GitHub repositories/organisations listed above may nominate someone for committee membership at any time. Only existing PSC committee members may vote on new members. Nominees must receive a majority vote from existing members to be added to the PSC.

### Stepping Down

If for any reason a PSC member is not able to fully participate then they certainly are free to step down. If a member is not active (e.g., no voting or email/meeting participation) for a period of 12 months then the PSC reserves the right to seek nominations to fill that position. Should that person become active again then they would certainly be welcome, but would require a nomination.

## History

This document is based on the [GDAL Project Management Committee Guidelines](https://gdal.org/development/rfc/rfc1_pmc.html#rfc-1) and was accepted by the STAC project board on [instert date].

The following changes have been made thereafter: <https://github.com/radiantearth/stac-psc/compare/v1...main>
