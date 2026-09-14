# Privybudget — User stories

**Product:** [PRODUCT.md](./PRODUCT.md)


### Consortium privacy officer

- As a consortium privacy officer, I want to allocate an ε budget per member and purpose, so that collaborative learning cannot silently exhaust privacy risk.
- As a consortium privacy officer, I want a round blocked when budget is insufficient, so that policy is enforced by the system rather than by email.
- As a consortium privacy officer, I want an exportable attestation pack after each release candidate, so that I can brief a data-trust board.

### Member ML engineer

- As a member ML engineer, I want to register an existing training job for federation, so that I do not rebuild my pipeline to participate.
- As a member ML engineer, I want to see remaining privacy budget before I launch a round, so that I do not waste compute on jobs that will be rejected.
- As a member ML engineer, I want encrypted or SMPC modes available as a toggle with clear performance implications, so that I can meet the stricter members’ requirements.

### Data custodian

- As a data custodian, I want raw records to stay inside my institution’s boundary, so that joining a consortium does not create a new breach surface.
- As a data custodian, I want to freeze outbound updates immediately if an incident is suspected, so that exposure is capped.

### Model validator / FAT reviewer

- As a model validator, I want fairness and accountability checks attached to promotion gates, so that “the algorithm made me do it” is not an acceptable release rationale.
- As a model validator, I want to reject a candidate when attestation purpose does not match the intended clinical or risk use, so that purpose limitation is operational.

### Platform administrator

- As a platform administrator, I want membership, keys, and node health visible per institution, so that a downed member does not silently skew a round.
- As a platform administrator, I want to record exception approvals with dual control, so that emergency budget top-ups cannot be unilateral.
