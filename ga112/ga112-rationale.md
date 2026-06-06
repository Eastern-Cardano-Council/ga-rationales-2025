## Summary
We have determined that this treasury withdrawal governance action is constitutional.

## Rationale Statement
The governance action with ID "gov_action1ggr2uz7prwn5l84cdn2krwngfez0p7wluy4u3u3ez9pz5ls2whesqnsjly8" and title "Pebble & Ecosystem maintenance: TypeScript core of Cardano" is a Treasury Withdrawal, and is therefore subject to the following sections and guardrails in the Cardano Constitution.

ARTICLE II, Section 6 of the Cardano Constitution states that governance actions must follow a standardized and legible format, including a URL hosting an immutable document and a corresponding hash, and must provide sufficient rationale including a title, abstract, justification, and supporting materials.

This governance action includes a valid URL and hash, which matches the hash of the off-chain documentation referenced. The rationale also meets the minimum content specified in this section.

ARTICLE II, Section 7 specifies that Treasury Withdrawal governance actions must include the following:

1\. Purpose, Delivery Period, Costs, and Refund Conditions

This governance action specifies:

- The purpose of the withdrawal is to fund "two complementary engineering tracks" being "Pebble: the first production-ready imperative smart-contract language on Cardano" and "Tooling maintenance: keeping HLabs' TypeScript stack (cardano-ledger-ts, ouroboros-miniprotocols-ts, plutus-machine, uplc, etc.) synchronized with protocol upgrades."
- The period for delivery of proposed activities "spans over 12 months, throughout which there will be several deliveries and demos."
- The relevant costs and expenses under the heading "Budget Breakdown"
- The language regarding circumstances under which funds may be refunded to the Cardano Treasury is somewhat vague, such as "Sweep early (return unused funds)" under the Budget Administration section, and a 15% refundable contingency.

While the refund circumstances could have been more clearly stated, we have determined that the information supplied just meets the criteria for Article II, Section 7(1).

2\. Prior Treasury Funding Disclosure

ARTICLE II, Section 7(2) requires disclosure of whether the prospective recipient has received ada from the Cardano Treasury within the last 24 months.

This governance action includes a link to an external document that provides a "full retrospective of past funding and deliverables". This fulfils the requirement of ARTICLE II, Section 7(2).

3\. Net Change Limit (NCL)

ARTICLE II, Section 7(3) requires that Treasury Withdrawals must not exceed the Net Change Limit.

The Net Change Limit in effect at the time of submission of this vote on-chain is the governance action with ID "gov_action1m3xx08yv788vfxqh6nfvrjtvmqpwezsy0ggaczctkyjmttc2wmxsq4jsr7q".

- A. Current NCL Amount: 350000000 ada
- B. Current NCL Time Period: Epoch 613 to Epoch 713 (Inclusive)
- C. Total of Treasury Withdrawals within the Current NCL Time Period: 199352090 ada
- D. Amount of this Treasury Withdrawal: 4600000 ada
- E. "C" plus "D" = 203952090 ada
- F. "A" minus "E" = 146047910 ada

As the value of "F" is greater than or equal to zero, this governance action fulfils the NCL requirement.

4\. Audit Allocation and Oversight Metrics

ARTICLE II, Section 7(4) states "Treasury Withdrawals actions shall require an allocation of ada as a part of such funding request to cover the cost of periodic independent audits and the implementation of oversight metrics as to the use of such ada."

This governance action states that "As part of the operational overhead included in the FTE cost structure, the proposal incorporates a independent financial audit of fund flows, designed to ensure transparency, accountability, and verifiability of treasury fund usage.", which fulfils the requirements of ARTICLE II, Section 7(4).

5\. Designated Administrators

ARTICLE II, Section 7(5) requires that one or more administrators are designated to monitor fund usage and ensure deliverables are achieved.

This governance action states that an "Independent Oversight Board" will act as an administrator, which fulfils this requirement.

6\. Fund Management Requirements

ARTICLE II, Section 7(6) states "Any ada received from a Cardano Blockchain treasury withdrawal, so long as such ada is being held by an administrator prior to further disbursement to the Treasury Withdrawal Recipient, must be kept in one or more separate accounts that can be audited by the Cardano Community, and such accounts shall not be delegated to an SPO but must be delegated to the predefined abstain voting option."

This governance action specifies the following withdrawal address, which at the time of assessment is not delegated to an SPO and is delegated to the auto abstain voting option:

- stake17x3n2krrld46qms4f4hzqqxzjgaf59u3fecvl6eh8scmaacjqmvjw

Finally, the guardrails that require consideration for this governance action are TREASURY-01a, TREASURY-02a, and TREASURY-03a.  These are addressed as follows:

- TREASURY-01a - The net change limit with governance action ID "gov_action1m3xx08yv788vfxqh6nfvrjtvmqpwezsy0ggaczctkyjmttc2wmxsq4jsr7q" is currently in effect, after being "agreed by the DReps via an on-chain governance action with a threshold of greater than 50% of the active voting stake".
- TREASURY-02a - As per the above assessment, this treasury withdrawal does not exceed the current Net Change Limit.
- TREASURY-03a - This treasury withdrawal is denominated in ada.

We therefore find this governance action **Constitutional**.

## Precedent Discussion
None

## Counterargument Discussion
None

## Conclusion
This governance action sufficiently fulfils the criteria specified for treasury withdrawals in the Cardano Constitution, so is deemed constitutional.

## Internal Vote
- Constitutional: 5
- Unconstitutional: 0
- Abstain: 2
- Did Not Vote: 0

## References
None
