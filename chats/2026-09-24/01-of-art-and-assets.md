# 24 September 2026 — ART, Trigger's regeneration chamber, and asset investigation

## Session focus

Continued development of Project Theseus, concentrating on:

- the biological terminology used by the regeneration system;
- the information visible to researchers during regeneration;
- the first Trigger regeneration procedure and the unexpected age of the resulting arm;
- practical requirements for the regeneration chamber in Fallout 4;
- identifying possible vanilla/DLC assets that could be reused for the chamber and its animations.

---

## Autologous Reconstruction Template (ART)

The term **Autologous Reconstruction Template**, abbreviated **ART**, is now canon.

"Autologous" is medically appropriate terminology: it means derived from the same individual who receives it.

The ART is the individual's biological reconstruction template used by the regeneration system.

The acronym also has a possible authorial joke/resonance with "prior art". This does not need to be acknowledged in-universe.

### Terminology decision

Use:

> **ART — Autologous Reconstruction Template**

Do not use "Somatic Reference State" as the primary terminology.

"Somatic" was discussed and means relating to the physical body/body cells and tissues, but the term was considered less attractive and somewhat too knowing for the researchers' understanding at this stage.

---

## Trigger's regeneration machine: readout

The regeneration chamber must be **opaque**.

This is now an explicit requirement.

The researchers cannot visually observe the regeneration process. They can monitor the subject and the machine through instrumentation/readouts, but they do not see the newly regenerated limb growing.

This is important because Trigger's first regenerated arm is unexpectedly much too small: it is effectively the arm of approximately ten-year-old Trigger.

If the chamber were transparent, the researchers would notice this during regeneration and the discovery would lose much of its impact.

The machine should therefore report what it believes it is doing without providing the crucial answer.

A possible readout:

    AUTOGENIC RECONSTRUCTION SYSTEM

    SUBJECT: ROGER L. PACK
    IDENTITY: VERIFIED

    ANATOMICAL ASSESSMENT
    UPPER RIGHT EXTREMITY: ABSENT

    RECONSTRUCTION STATUS
    ART: ACQUIRED
    ART INTEGRITY: 99.8%
    RECONSTRUCTION: VIABLE

    RECONSTRUCTION INITIALISED

    SKELETAL STRUCTURE ........ COMPLETE
    VASCULAR NETWORK .......... COMPLETE
    MUSCULATURE ................ COMPLETE
    PERIPHERAL NERVES ......... COMPLETE
    DERMAL COVERING ............ COMPLETE

    OVERALL COMPLETION: 100%

    OPERATION COMPLETE.

    TISSUE REGENERATION PROCESS CONCLUDED.

    DETAIL:
    UPPER RIGHT EXTREMITY RECONSTRUCTED
    FROM AUTOLOGOUS RECONSTRUCTION TEMPLATE.

    CHAMBER MAY BE OPENED.

This is illustrative rather than necessarily final UI text, but the following principles are locked:

- ART is reported.
- ART is treated as a normal technical parameter.
- The machine does not report an age.
- The machine does not report a chronological reference state.
- The machine does not tell the researchers that it has reconstructed a younger version of Trigger.
- The researchers discover the significance of ART only by examining the result.

---

## Trigger's first regenerated arm

The previously established Trigger history remains:

1. BattlefieldBuddy was an abandoned West-Tek regeneration project.
2. It was never released to the armed forces as working technology.
3. The project was shelved because its regenerative behaviour was unreliable and poorly understood.
4. Trigger's catastrophic loss of his right arm causes West-Tek to resurrect the research.
5. The first human procedure successfully regenerates an arm.
6. The researchers initially expect the result to be an adult Trigger's current arm.
7. The chamber opens and they discover that the arm is far too small.
8. It is not malformed or an obvious failure.
9. It is a coherent, anatomically correct arm belonging to a much younger Trigger.
10. The working assumption remains that this corresponds to approximately ten-year-old Trigger.

The ten-year-old period is significant because it was around the time before Trigger's mother died and represents the happiest period of his life.

This should **not** be represented in the machine's readout as an explicit "reference age". The machine does not explain the result. The researchers must investigate why ART produced this version of Trigger.

The discovery should feel like:

> The machine did exactly what it thought it was supposed to do.

The mystery is therefore not "why did the machine fail?"

It is:

> **What exactly is ART?**

---

## The ART discovery

The first regenerated arm reveals that ART is not simply a current anatomical scan or a straightforward genetic blueprint.

The researchers expected the system to reconstruct the missing limb according to Trigger's present physical state.

Instead, it reconstructed a limb corresponding to a much younger version of him.

This becomes a major scientific clue.

The earlier BattlefieldBuddy failures also gain new significance.

The old incident in which an ear grew from a thigh wound may not have represented a completely random failure. It may have been the system following an imperfect or misunderstood biological template without knowing the correct anatomical destination.

This gives the project a useful conceptual progression:

> BattlefieldBuddy appears to fail because regeneration is uncontrolled.

Then:

> Trigger demonstrates that the system is actually reconstructing according to an intrinsic biological template.

Then:

> The researchers begin trying to understand and control ART.

Eventually:

> They discover that increasingly extensive parts of a person can be reconstructed from ART.

This is the technological road toward Project Theseus.

---

## Second Trigger procedure

The second attempt should involve the researchers trying to understand/control what ART is doing rather than simply "trying again".

They now know that the system is capable of reconstructing Trigger but that the result is not necessarily his current adult form.

The second procedure successfully produces **adult Trigger's arm**.

This establishes an important new capability:

> The system can reconstruct a particular person's biological structure in a deliberately controlled state.

The precise mechanism by which this is achieved remains to be developed.

No explicit "age selector" should be visible in the early machine UI.

---

# Regeneration chamber design

The regeneration chamber needs to satisfy several fictional requirements:

- A person lies down horizontally inside it.
- The chamber becomes completely opaque during the regeneration process.
- The occupant cannot be visually observed from outside.
- Researchers monitor the process through data/readouts rather than direct observation.
- The machine should feel like sophisticated pre-War biomedical technology.
- It should plausibly evolve into the eventual Theseus machine.
- The Trigger prototype and the final Theseus machine do not need to look identical.

A useful visual starting point is something approximately like:

> a large medical/scientific machine crossed with a sunbed, MRI, isolation chamber, and surgical apparatus.

The "sunbed" quality is useful because it naturally accommodates a horizontal human occupant, but the final design should be much more substantial and technologically imposing.

---

## Vanilla Fallout 4 asset investigation

The possibility of reusing existing Fallout 4/DLC assets was investigated before commissioning custom 3D work.

### Cryo Pod

The vanilla Vault 111 Cryo Pod remains the strongest **technical fallback**.

Reasons:

- It is already designed around a horizontal human occupant.
- Existing Fallout 4 furniture/animation systems can be used for lying-down interaction.
- The pod can potentially be visually modified/replaced while retaining the underlying interaction/animation setup.
- The transparent enclosure is the major problem, but that can potentially be replaced or obscured by an opaque custom/repurposed shell.

The Cryo Pod is therefore retained as the current fallback:

> **Cryo Pod furniture/lying animation + custom/repurposed opaque shell.**

No need to commission a fully animated custom machine if the existing furniture animation can be retained.

### Pulowski Preservation Shelter

Initially considered because it already provides an enclosed, opaque human-sized structure with a door.

Ultimately considered unsuitable as the primary chamber because:

- it is vertically oriented;
- it is cramped;
- its visual language strongly suggests a cheap civilian nuclear survival shelter;
- it would require substantial modification to become a sophisticated biomedical regeneration chamber.

Pulowski can therefore be discarded as the main design direction.

### Institute / FEV assets

Institute medical/scientific assets are promising as **mesh donors**, even though Theseus is not Institute technology.

The FEV chamber is particularly interesting as a possible source of:

- structural enclosure geometry;
- containment-shell ideas;
- scientific machinery/greebles.

It is not suitable as a complete regeneration chamber because it is not a horizontal human treatment bed, but its geometry could potentially be combined with an existing lying-down furniture setup.

### Institute biobed / medical furniture

Institute medical furniture may also provide useful technical/animation precedents.

The underlying principle is more important than using the visual assets unchanged:

> Find an existing Fallout 4 lying-down furniture marker/animation and build the chamber around it.

The difficult technical problem is getting the character to lie down and stand up correctly.

Once that is solved, the visible machine can largely be static geometry surrounding the animation marker.

### Vault 88

Vault-Tec Workshop/Vault 88 contains useful medical and laboratory dressing, but no obvious vanilla/DLC object was identified that directly solves the central requirement:

> horizontal human occupant + opaque enclosure + existing lying-down interaction.

Therefore Vault 88 should not be exhaustively searched for a magical ready-made pod.

It may still provide surrounding laboratory/medical assets.

---

# Preferred development strategy for the chamber

Do not commission a modeller yet.

First prototype the interaction using the vanilla Cryo Pod and existing lying-down animation.

The technical goal is simply:

> enter → lie down → chamber closes → regeneration/wait → chamber opens → stand up.

Once the quest/interaction works, the visible machine can be replaced or rebuilt.

Possible final approaches:

1. Frankenstein together vanilla/DLC meshes.
2. Use Cryo Pod furniture/animation as the hidden functional foundation and build a custom opaque shell around it.
3. Commission only the final chamber shell from a modeller if necessary, rather than commissioning a completely new animated object.

This dramatically reduces the modelling/animation problem.

---

# Visual evolution of the machines

The Trigger machine and final Theseus machine should **not** necessarily look identical.

A useful progression is:

> BattlefieldBuddy research apparatus  
> → Trigger regeneration prototype  
> → increasingly sophisticated ART reconstruction chamber  
> → Project Theseus system  
> → final 2077 full-human reconstruction machine

The Trigger machine can look like a somewhat crude, large West-Tek biomedical prototype.

The final Theseus machine can be much more sophisticated and imposing.

The common technological ancestry should still be visually apparent.

---

# Broader Theseus progression

The previously established story direction remains:

**BattlefieldBuddy → anomalous regeneration → ART discovered → Trigger's arm → controlled adult Trigger reconstruction → increasingly complex biological reconstruction → question of how much of a person can be replaced while remaining the same person → Project Theseus → complete human reconstruction.**

A key philosophical question remains:

> **How much can you replace and have it still be the same person?**

This is likely to become the conceptual bridge to the name **Project Theseus**.

The researchers do not need to immediately attempt whole-body reconstruction. They can progressively replace increasingly complex structures and discover that the same individual can persist through extraordinary degrees of biological replacement.

The final step is reached in 2077:

> They have developed the machine and believe complete human reconstruction should be possible, but have not yet successfully reconstructed an entire human.

Westminster ultimately becomes the first successful complete human reconstruction.

This preserves the established canon that **Westminster is the first successful complete human subject**.

---

## Current status after this session

Locked decisions:

- **ART = Autologous Reconstruction Template.**
- No explicit reference age in machine readouts.
- Trigger's first regenerated arm is approximately his ten-year-old arm.
- The ten-year-old result is an unexpected discovery.
- The regeneration chamber is opaque.
- Researchers monitor data, not the actual regeneration.
- Cryo Pod + existing lying-down animation is the technical fallback.
- Institute/FEV/medical assets are candidates for mesh/visual components.
- Pulowski is not the preferred chamber solution.
- Custom modelling is deferred.
- Trigger's prototype chamber and the final Theseus chamber can look substantially different.

Next useful work remains the detailed **2073–2077 progression from Trigger's successful adult-arm regeneration to Project Theseus and the completed whole-human reconstruction machine**.
