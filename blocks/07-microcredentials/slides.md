---
session: "07"
title: "Microcredentials"
version: 0.1.0
---

--- slide
id: s06-01
layout: Title
role: title
subtitle: A VET reading for the post-MICROBOL, eIDAS wallet era
notes: |
  Narration (0:00-0:40):
  Ask an academic what defines a microcredential and the answer often begins with assessment, ECTS and the higher-education framework developed through MICROBOL.

  That is one important lineage, but it does not describe every vocational learning claim now entering Europe's digital credential infrastructure. In the wallet era, the better opening question is not simply “Is this a microcredential?” It is “What exactly does this credential claim?”

  Source: I-RESTART D8.6, Introduction and “Assessment”.
---

--- slide
id: s06-02
layout: Comparison
title: MICROBOL did not determine the VET model
left_head: Higher-education inheritance
left:
  type: ul
  items:
    - MICROBOL applied Bologna instruments to smaller learning experiences
    - ECTS, assessment, quality assurance and recognition travel together
    - The 2022 Recommendation defines assessed learning outcomes as part of a microcredential
    - Issuer authority is often inherited from an accredited institution or programme
right_head: Emerging VET architecture
right:
  type: ul
  items:
    - DC4EU proposes EUVETMC for bounded vocational learning
    - The provider, assessor, issuer and recognising body may be different organisations
    - The VET profile can represent learning without making assessment mandatory
    - eIDAS adds electronic attestations, issuer trust routes and wallet presentation
notes: |
  Narration (0:40-2:00):
  MICROBOL asked how the established instruments of the European Higher Education Area could apply to microcredentials. In that environment, assessment, credit, institutional quality assurance and recognition are closely connected. The 2022 Council Recommendation reflects that lineage by defining a microcredential as a record of assessed learning outcomes from a small volume of learning.

  Vocational education is more varied. Learning may be provided by a college, employer, sector body or public programme. Assessment, issuance and recognition may sit with different actors. The later DC4EU sectoral work therefore proposes a European VET Microcredential in which assessment information may be present but is not structurally mandatory.

  This is not a clean replacement of the 2022 policy definition. It is a genuine tension between a higher-education-derived definition and an emerging VET digital implementation. The responsible response is to make the actual claim and evidence explicit.

  Source: I-RESTART D8.6, “The task and the changing policy context”, “Issuance” and “Assessment”.
dok: 2
---

--- slide
id: s06-03
layout: Cards
title: Four different claims can travel
head1: Learning activity
card1:
  type: p
  text: The person participated in or completed a defined learning experience.
head2: Assessment
card2:
  type: p
  text: A judgement was made using a stated method, criteria and evidence.
head3: Achievement
card3:
  type: p
  text: The person is held to know, understand or be able to do something.
head4: Entitlement
card4:
  type: p
  text: The person holds a right, permission or status arising from recognition.
notes: |
  Narration (2:00-3:15):
  The European Learning Model separates four claims that ordinary educational language often combines.

  A learning activity records participation in learning. An assessment records that a judgement occurred. An achievement records what the learner is held to know or be able to do. An entitlement records a right or permission arising from learning or recognition.

  These are not compulsory stages that must always appear together. A record of completed learning is not a defective achievement credential. It is a complete learning-activity claim. The problem begins only when participation is presented as if it proved assessed mastery or conferred an entitlement.

  Source: I-RESTART D8.6, “Four classes of learning claim”.
dok: 2
---

--- slide
id: s06-04
layout: Comparison
title: Assessment is optional only when the claim is narrower
left_head: No assessment claim
left:
  type: ul
  items:
    - States that defined learning occurred
    - Does not imply that mastery was tested
    - Contains no invented grade or assessment method
    - May be sufficient as evidence of training or participation
right_head: Assessment or achievement claim
right:
  type: ul
  items:
    - States what was judged and why
    - Records method, criteria, evidence and result
    - Identifies the assessor or awarding decision
    - May support progression, recognition or a competence claim
notes: |
  Narration (3:15-4:40):
  In the DC4EU VET model, an omitted assessment field means that the issuer makes no assessment claim. It does not mean that an invisible assessment should be assumed, and it does not make the digital record technically incomplete.

  This permits a microcredential to record bounded vocational learning honestly, even when no summative assessment occurred. A receiver might accept that as evidence of required training, continuing development or workplace induction.

  Where assessment did occur, it should be visible: its purpose, method, conditions, criteria, evidence and result. A professional body or regulator may require that stronger evidence. The distinction is not assessment versus no standards. It is a disciplined match between the evidence recorded and the claim being made.

  Source: I-RESTART D8.6, “Schemas, validation profiles and optionality”, “Assessment” and Protocol Step 4.
dok: 3
---

--- slide
id: s06-05
layout: Cards
title: The post-2026 credential has four layers
head1: Claim
card1:
  type: p
  text: What activity, assessment, achievement or entitlement is being asserted?
head2: Issuer
card2:
  type: p
  text: Which organisation makes the claim, and what is the scope of its authority?
head3: Proof
card3:
  type: p
  text: Can the credential's integrity, status and issuing key be checked?
head4: Trust route
card4:
  type: p
  text: Is it an ordinary, qualified or public-body electronic attestation—and what follows from that?
notes: |
  Narration (4:40-6:00):
  The amended eIDAS framework gives digital credentials a trust infrastructure, but it does not define the educational claim for us.

  First comes the claim. Second is the issuer and the basis on which it expects to be trusted. Third is the cryptographic proof that protects the credential and allows its status and provenance to be checked. Fourth is the applicable trust route: an ordinary non-qualified electronic attestation, a qualified attestation, or one issued by or on behalf of a public-sector body responsible for an authentic source.

  From 19 August 2026, the scheme-catalogue and authentic-source arrangements in Implementing Regulation 2025/1569 apply. Further wallet-relying-party registration rules apply from 24 December 2026. These mechanisms support trusted exchange; they do not turn every issuer into a recognised awarding authority.

  Source: I-RESTART D8.6, “The task and the changing policy context” and “Where trust terminates”; Regulation (EU) 2024/1183; Implementing Regulations (EU) 2025/1569 and 2025/848.
dok: 2
---

--- slide
id: s06-06
layout: Comparison
title: The wallet verifies the credential—not the competence
left_head: What can be checked
left:
  type: ul
  items:
    - Whether the credential has been altered
    - Which key or trust service secured it
    - Whether it follows the relevant technical profile
    - Its status and association with the holder, where supported
right_head: What still requires judgement
right:
  type: ul
  items:
    - Whether the issuer was entitled to make the educational claim
    - Whether any assessment was valid and sufficient
    - Whether another body will recognise the learning
    - Whether the credential creates professional or legal effect
notes: |
  Narration (6:00-7:20):
  A wallet can help a learner store and present an electronic attestation. A verifier can check its integrity, provenance, status and—in the appropriate architecture—its association with the holder.

  That is powerful, but deliberately limited. A valid signature proves that the credential came from the controller of a key and has not been changed. It does not prove that the issuer was educationally authorised, that the assessment was strong, or that another institution, employer or regulator must recognise the result.

  Digital verification answers, “Is this the claim that this issuer made?” Recognition answers, “Do we accept this issuer and this evidence for our purpose?” Those are different decisions.

  Source: I-RESTART D8.6, “Credential claims, formats and proof”, “Where trust terminates” and “Portability, facilitated recognition and legal effect”.
dok: 3
---

--- slide
id: s06-07
layout: Cards
title: Workload and level must not be manufactured
head1: Hours
card1:
  type: p
  text: Record the actual learning workload available from the source. Hours are a valid VET measure of volume.
head2: ECTS
card2:
  type: p
  text: Record ECTS only where it has been formally assigned. Never reverse-calculate credit from hours.
head3: EQF
card3:
  type: p
  text: A formal EQF level attaches to a qualification through the relevant referencing process.
head4: VET equivalence
card4:
  type: p
  text: State alignment or contribution to a levelled qualification, supported by descriptors and a published rationale.
notes: |
  Narration (7:20-8:40):
  A small unit of learning needs a transparent statement of volume, but there is no need to disguise vocational workload as higher-education credit.

  Record hours when hours are the evidence available. Record ECTS only where an authorised process has actually assigned it. A conversion formula does not create credit, and the I-RESTART catalogue explicitly avoids calculating ECTS backwards from hours.

  Apply the same discipline to EQF. A qualification receives a formal level through the relevant national referencing process. A VET microcredential may contribute to that qualification or may be aligned with particular EQF descriptors for knowledge, skills, responsibility and autonomy. If a level is stated, identify the referenced qualification or publish the rationale. Equivalence is a relationship to explain, not a level for the microcredential to award itself.

  Source: I-RESTART D8.6, Protocol Steps 1 and 3; “Source assembly and catalogue architecture”.
dok: 3
---

--- slide
id: s06-08
layout: Cards
title: Read the credential—not the label
head1: What happened?
card1:
  type: p
  text: Is this activity, assessment, achievement or entitlement—or a clear combination?
head2: What confirms it?
card2:
  type: p
  text: Was assessment conducted, and what evidence and judgement are actually recorded?
head3: Who says so?
card3:
  type: p
  text: Can the issuer be verified, and what gives it authority for this particular claim?
head4: How can it be used?
card4:
  type: p
  text: What do the workload, level relationship, recognition route and any entitlement support?
notes: |
  Narration (8:40-10:00):
  When you encounter a microcredential, resist the temptation to infer its meaning from the label.

  Ask what happened. Was learning completed, was it assessed, was an achievement confirmed, or was an entitlement conferred? Ask what confirms the claim and whether the evidence is visible. Ask who issued it and why a receiver should accept that organisation's authority. Finally, ask how it can be used: what the workload represents, how any EQF relationship was established, and whether recognition or legal effect follows.

  In the post-2026 environment, the strongest microcredential is not necessarily the one carrying the most fields. It is the one that makes a precise claim, preserves the evidence available, and does not imply what was never established.

  Source: I-RESTART D8.6, Protocol for issuing vocational digital credentials.
dok: 3
---
