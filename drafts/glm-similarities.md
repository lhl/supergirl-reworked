# GLM-5.2 vs. Fable draft similarities

Sources compared:

- Story bible / shared prompt source: `../README.md`
- GLM draft: `draft-script-glm5.2.md`
- Fable draft: `draft-script-fable.md`

## Framing note

These two scripts were generated independently from the same prompt: **write a full script from the `README.md` story bible**.

That matters a lot. The story bible is not a loose outline; it is already a detailed prose treatment with scene order, key images, bits of dialogue, exact thematic language, and even suggested jokes. So this comparison should **not** be read as proof that one draft had access to the other, or as proof of model lineage. A lot of the overlap is exactly what a faithful model should produce from this particular bible.

The useful question is narrower:

> When the two drafts solve the same highly-specified assignment, where does GLM feel like a flatter / more confused / more literal version of the Fable draft, and where is it actually doing something different?

Short answer: **GLM reads less like an independent alternate movie and more like a longer, more literal, less elegant pass over the same treatment that Fable also adapted.** Fable usually compresses, specifies, and gives images dramatic charge. GLM often expands the same beats into many more sluglines, explains the theme in the body text, and occasionally loses or muddies the story logic.

## High-level verdict

### What is genuinely very similar

Both drafts share the same:

1. **Macro architecture**: cold open murder → Kara red-sun avoidance → bar collision → Krypto poison → failed yellow-sun sprint → rest stop / bus → Bilki → Lobo → sword wound → yellow-sun rebirth → Krem non-fight → Ruthye cuts the chain → birthday / home ending.
2. **Emotional engine**: Ruthye and Kara are two mile-markers on the same revenge road; Kara tries to save Ruthye from becoming what grief made Kara; Ruthye eventually saves Kara back.
3. **Cinematic grammar**: red/yellow palette, hands against glass/barriers, jacket as armor/shedding skin, Krypto as the last living link, Lobo as seductive/corrosive violence, final sword-to-chain misdirect.
4. **Recurring phrasing**: many of the same memorable turns appear in both drafts almost verbatim.
5. **Scene choreography**: not just the same events, but the same event-shapes — e.g. Lobo makes killing effortless, Ruthye cites the code, Kara steps into the blade, Ruthye forces Lobo upward, Kara heals in the sun, and Lobo flees the feelings.

### What is less meaningful than it first looks

A surprising amount of the most “uncanny” overlap is actually inherited from the `README.md` story bible. Examples include:

- “Avoidance isn't something that happened to her. It's a practice she maintains every morning.”
- “Not grief. Not shock. Rage — the kind that has already decided something, before the mind catches up.”
- “You don't want to go there.” / “Technically.”
- The drop-shell “rated for toxic atmosphere and plausible deniability.”
- Lobo's line about a code being worth more than all the corpses on the planet.
- “Take us to the sun / take us or kill me now. The code demands it.”
- “The universe, personified, can do anything except feel.”
- The final idea that killing Krem “wouldn't prove anything. It wouldn't disprove anything. It would just be killing.”

So the scripts read similarly partly because they are both faithful to a very literary, scene-prescriptive source.

### What still makes GLM feel like “worse Fable”

Even after accounting for the shared bible, GLM often behaves like it is doing the **same scene-by-scene transposition** as Fable, but with three weaknesses:

1. **Flattening specificity**: Fable names Andy, Marye, Tomme; uses the father's crossbow; names Oasis Station; gives the bus passengers sharper weirdness. GLM often substitutes generic Father/Mother/Brother, generic weapons, generic rest stop, generic alien commerce.
2. **Explaining rather than staging**: Fable also has literary/meta prose, but GLM more often tells us the function of the beat — “the audience should,” “the metaphor doesn't need to be stated,” “this is the moment” — instead of trusting the image.
3. **Story-logic drift**: GLM gets several mechanics confused or underpaid, especially around the final birthday beat, the bubble suit / atmosphere, the final weapon mechanics, and Clark's voicemail payoff.

---

# Manual scene-by-scene comparison

## 1. Cold open: Ruthye's home / Krem's lesson

### Shared structure

Both drafts open with a farm world under red light, a family meal, Krem arriving with Brigands, an ugly but survivable raid, and then the deliberate murder of Ruthye's father after the off-ramp is visibly available.

Both drafts frame the killing as a lesson aimed at Ruthye rather than tactical necessity. In both, Krem sees defiance in Ruthye and kills to overwrite it with his creed: **“This is what the world is.”**

Both end the sequence on Ruthye holding/protecting her younger brother while looking toward the road Krem took — the life she should choose physically in her arms, the death-road in her eyes.

### Shared phrases / turns

- Flat red / sodium-lamp / embalming light.
- Ordinary life that “exists because someone chose to build it.”
- Krem as tired, weathered, not a cartoon monster.
- The “off-ramp” — the transaction is ugly but complete; he could leave.
- “This is what the world is.”
- “Not grief. Not shock. Rage — the kind that has already decided something, before the mind catches up.”

Most of these are strongly prompted by the story bible, but both drafts preserve them in screenplay prose rather than translating them away.

### Differences

Fable is more specific and more elegant:

- The family are **Andy Knoll, Marye Knoll, Tomme, Ruthye Marye Knoll**.
- The meal has pie, family teasing, and a small domestic comedy before the dread arrives.
- Krem steals Andy's father's crossbow; that object later becomes a violation, tracker anchor, murder weapon, and climax payoff.
- Krem's worldview gets sharper language: “A universe of the uninvolved.”

GLM is more generic:

- The family are mostly FATHER, MOTHER, YOUNGER BROTHER.
- The food is bread/preserves rather than a more memorable pie/table ritual.
- Krem uses a sidearm rather than the father's crossbow.
- Ruthye's line “You don't have to be this” makes the trigger more explicit but less eerie than Fable's silent defiant look.

### GLM story / craft issue

GLM preserves the off-ramp but makes Krem's escalation feel a bit more conventional: Ruthye verbally challenges him, he backhands the mother, father reacts, Krem shoots father. Fable's version is creepier because the room is already cooling and Krem turns back solely because Ruthye's eyes offend him.

GLM also loses the prop chain. It later says Ruthye's tracker is keyed to one of her father's stolen weapons, but the weapon never becomes an emotionally legible object. Fable's crossbow solves that cleanly.

## 2. Kara's morning: nightmare, bottle, voicemail

### Shared structure

Both drafts cut from Ruthye's rage to Kara waking from Argo fragments, reaching for alcohol before fully waking, hearing a Clark/Kal voicemail, not calling back, and existing under the same red sun that lit Ruthye's tragedy.

Both drafts make the red sun physicalized avoidance: Kara is choosing a place that makes her weaker because weakness/numbness is the point.

### Shared phrases / turns

- Hand reaching for the bottle before her eyes are open.
- The red sun visible through the porthole.
- Clark/Kal's voicemail as loving pressure from an available family.
- Krypto as the one living thing she has not numbed or pushed away.
- Exact or near-exact use of: “Avoidance isn't something that happened to her. It's a practice she maintains every morning.”

### Differences

Fable is tighter and more textured:

- Unheard messages: 11.
- Clark's birthday voicemail has Ma, Lois, and cake texture.
- The cape shoved on a shelf and the oversized jacket as half-blanket / half-armor do visual work.
- Krypto's “idiot-saint sincerity” lands immediately.

GLM is more explanatory:

- Clark's voicemail is longer and more generic.
- Kara's ship and town geography are laid out clearly, but with less style.
- It directly explains the thematic point after showing it.

### GLM story / craft issue

GLM sets up Clark strongly enough that the mid-credits should answer him. Fable at least has Kara call Kal. GLM's mid-credits does not pay this off; it resolves “home” abstractly through Metropolis and Krypto but leaves the actual Clark voicemail thread dangling.

## 3. First meeting / port bar

### Shared structure

Both drafts have Ruthye enter a port bar already on the hunt. She demonstrates competence by handling an adult threat. Kara notices despite herself. Ruthye explains the code and the murder. Kara asks about living family, cracks, and tells Ruthye to go home.

Then Ruthye reveals the drive crystal / fuel core and tracker. The tracker blooms: Krem is here. Krem enters for the stolen crystal. The brawl follows. Krypto takes a Brigand poison bolt meant for Kara. Krem recovers the crystal and escapes.

### Shared phrases / turns

- Kara watches Ruthye “despite herself” / recognizes something.
- Ruthye is not lost, not scared, and not helpless.
- Kara's emotional crack at “mother and brother alive.”
- “Go home.”
- The drive crystal as a baseball-sized metal-and-glass case.
- Tracker keyed to a family weapon, not magic.
- The bar recalculates after Ruthye's violence.
- Kara has “residue, not command.”
- Krypto as loyal idiot-saint / white blur / the one who takes the bolt.

### Differences

Fable's bar sequence is cleaner:

- Ruthye's ask is formal and strange: she seeks the “strongest arm” to hire.
- The bartender's five eyes involuntarily slide to Kara.
- Ruthye's drive-crystal reveal has a great line: “I do not chase. I hold.”
- Krem's scanner mirrors Ruthye's tracker, making both sides' logistics feel real.
- The brawl has a compact three-beat power demonstration: burst, too-hard hit, stumble.

GLM is more conventional but very legible:

- Ruthye asks the bartender for Krem directly.
- She fights crewmen in a clearer, longer barfight.
- Kara and Ruthye have a more extended dialogue about family and code.
- The antidote stakes are not planted until later, but the emotional stakes are clear.

### GLM story / craft issue

GLM's added length makes the scene easier to follow but less sharp. It keeps explaining the math: farm dirt, tracker direction, drive crystal, port logic, Krem's presence. Fable leaves more for the audience to infer and therefore feels more cinematic.

Also: both drafts put Kara at the bar, not hidden in a booth/back table. If the next pass wants Kara's avoidance staged more strongly, the booth is still better.

## 4. Krypto's poisoning / failed yellow-sun sprint

### Shared structure

Both drafts take Krypto to Kara's ship, identify Brigand poison, establish that only a ranking Brigand's antidote can save him, and then have Kara try the obvious solution: reach a yellow sun. The ship cannot make it and breaks down / limps to a rest stop.

### Differences

Fable compresses this pressure into one continuous failure:

- The medbay gives “soon” rather than a clean arithmetic countdown.
- The ship voice's fuel/drive warnings recur from the morning.
- The failed yellow-sun sprint is about Kara choosing movement under panic, not solving a technical puzzle.

GLM expands it into **THE ROAD, PART ZERO — THE SHIP AND THE COUNTDOWN**:

- Krypto has 14 hours 22 minutes, then 13:47, then 11:14, etc.
- Yellow sun is 16 hours away; maybe 15 if pushed.
- Kara tries a jury-rigged artificial yellow-sun spectrum inside the ship.
- The yellow light briefly helps, then kills the drive.

### GLM story / craft issue

This is one of GLM's biggest story drifts.

The story bible is explicit that the clock should be emotional pressure, **not arithmetic**, and that the yellow-sun rebirth should be the single true solar transition. GLM turns this into a more mechanical countdown and introduces a failed artificial-yellow-light test. That creates avoidable questions:

- If yellow-spectrum generation is possible, why is it not tried again at the rest stop?
- Does artificial yellow light “count” or not?
- Is the later yellow-sun rebirth still the one clean power transition, or did we already see a mini-version?
- Are we now solving power states through engineering rather than character and geography?

The sequence is emotionally understandable — Kara panics and tries anything — but it opens the kind of gadget/math logic the bible is trying to avoid.

## 5. Rest stop / clinic / mechanic / bus

### Shared structure

Both drafts use the deep-space rest stop as the road-trip hinge:

- Krypto goes into a stabilizing tube.
- The healer confirms Brigand poison and ranking-officer antidote.
- The mechanic says the ship's drive component can be regrown/replaced, but not in time.
- Ruthye aligns the tracker with a public spacemap.
- Destination resolves as Bilki, dead Brigand homeworld, still technically on a bus/drop route.
- They buy supplies, including food Ruthye wants but won't ask for and a bubble suit/ring.
- The washroom beat lets Ruthye briefly become a scared thirteen-year-old.
- Lobo is teased by a wanted poster / white hand / chain / blue flame.

### Shared phrases / turns

- “You don't want to go there.”
- “Bilki. Was. Brigand homeworld, depending who you ask. No one lives there anymore.”
- “Is it still on the drop-off route?”
- “Technically.”
- “Now you won't die in space.” / “I wasn't planning to.”
- Ruthye looking smaller than she has all movie.
- The rest stop as life insisting on itself in the void.

### Differences

Fable's Oasis Station is much stronger:

- The name **Oasis Station** gives the place identity.
- The attendant, stamps, advisory glyphs, Gate Six, and “last row” line make the bureaucracy funny and specific.
- The food errand and bubble-suit purchase feel like a tiny parent/child road-trip sequence.
- The Lobo tease is funnier and more precise.

GLM is functionally clear but more generic:

- It calls the place a deep-space rest stop / transit hub.
- The mechanic and healer are competent but less memorable.
- It separates scenes into more literal blocks.
- It explains the route and return-shell logistics more directly.

### GLM story / craft issues

There is a small but concrete dialogue bug in the clinic section:

> KARA: And Krem is —  
> KARA: (beat) The ranking officer. Yes.

That second line probably belongs to the Dock-Healer or Ruthye. As written, Kara appears to answer herself in a way that reads like a script-generation glitch.

GLM also states the ship is grounded for weeks but later simply shows it repaired with a salvaged Brigand drive crystal. Fable pays this off with the mechanic and the graft / “estate sale” joke. GLM's version is understandable but abrupt.

## 6. Bus confession

### Shared structure

Both drafts have Kara wake from Argo fragments on the bus, reach for a flask, and have Ruthye tell her: **“You should stop that.”** Kara then tells Ruthye about Argo's slow death and says she has been down Ruthye's revenge road. Revenge will not make her feel better.

Both end with Kara realizing she has pulled the flask out again and choosing to put it away.

### Shared phrases / turns

- “You should stop that.”
- The line delivered not as scolding but as a controlled, matter-of-fact demand.
- Argo's death was slow, not clean.
- People died in ones and twos before all at once.
- Ruthye listens without comparing grief.
- “The confession just sits between them.”
- “Drunk with opinions” / Kara no longer being fileable as that.

### Differences

Fable is more compressed and better-phrased:

- “He inherited a dead world. I attended mine.”
- “I've done what you're planning. Revenge won't make you feel better.”
- It leaves more of Kara's revenge past unstated.

GLM is more literal and longer:

- Kara narrates more of the city dying.
- It adds explicit emotional explanation: holes closing, feeling less vs better.
- It includes a nebula beat where Kara says the universe is mostly empty and cold, “but sometimes it does that.” That is pretty, but more on-the-nose.

### Note for next pass

Both drafts have Kara obey Ruthye too neatly. The better version is probably: Kara hears “You should stop that,” finishes the swallow because habit wins, then later reaches again and chooses not to. That would make the confession actually change behavior rather than have Ruthye magically interrupt addiction.

## 7. Bilki drop and dead-world trail

### Shared structure

Both drafts turn the bus route into a ridiculous, dangerous drop-shell descent:

- Bilki appears gray and dead from orbit.
- The drop-shell is clear / half escape pod / half luggage chute.
- A yellow sun glints briefly on the shell; Kara presses her hand against the glass, yearning for light through a barrier.
- A blue flame arc foreshadows Lobo.
- On the surface, Bilki is nuclear winter, gray, ash, lightning, old fires, dead infrastructure.
- The tracker leads to a depot / bunker / transit complex.
- Automated defenses wake up.
- Kara protects Ruthye through gunfire/mines and carries her in a depleted piggyback run.
- Ruthye resents being protected.
- Screams/laughter/explosions ahead announce Lobo.

### Shared phrases / turns

- “Rated for toxic atmosphere and plausible deniability.”
- “A tiny, impossible glint” of yellow light.
- Ruthye notices Kara reaching for the sun.
- “This isn't a trap. It's just what Bilki is.”
- Machines with no ideology and no mercy.
- “A ruined, depleted approximation” of superheroics.
- “Barely standing, heaving against the world.”

### Differences

Fable is visually stronger:

- The Yellow Hills / terrace echo makes Bilki feel like the dead version of Ruthye's farm world.
- Kara's alcohol-withdrawal / flask-hand moment on Bilki extends the addiction arc.
- The gauntlet is described as a series of images, not a full tactical scene.

GLM is more tactical:

- It spells out perimeter guns, minefields, cover, exact movement.
- It gives Ruthye more immediate physical presence but less strange atmosphere.
- It separates “approach,” “complex edge,” “defense trap,” “piggyback run,” and “aftermath.”

### GLM story / craft issue

GLM says, after the yellow-sun rescue, Kara descends back through Bilki with Ruthye in her arms and **“the bubble suit retracted now.”** Since Bilki has been established as toxic / nuclear-winter atmosphere requiring masks or environmental protection, this is a continuity problem unless Kara has some unstated way to shield Ruthye. Fable's handling is also a little hand-wavy, but GLM explicitly retracts it during descent, which makes the issue more visible.

## 8. Lobo scene

### Shared structure

This is the place where the two drafts are most recognizably the same movie.

Both have:

- Lobo tearing through Brigands with gleeful, charismatic ultraviolence.
- The violence starting as fun and becoming queasy.
- An Action Comics / Superman-style truck-lift image that curdles when the truck crushes people.
- A dying Brigand begging “Please” and Lobo answering “You're welcome” while killing him.
- Krem reduced to begging.
- Ruthye stopping Lobo because Krem's death belongs to her by code.
- Lobo respecting code, handing Krem to Ruthye, and telling her she'll feel great.
- Krem kneeling, pathetic.
- Ruthye saying “This is what the world is.”
- Kara stepping into the sword.
- Lobo genuinely stunned because he has no frame of reference for self-sacrifice as moral rescue.
- Krem escaping because Ruthye's revenge attempt created the emergency.
- Kara saying, “I had to save you. That's my code.”
- Ruthye choosing Kara over the chase and forcing Lobo to take them to the sun.

### Shared phrases / turns

- “The Main Man.”
- “Action Comics shot.”
- “Having a code is worth more than all the corpses on this planet.”
- “You got moxie.”
- “You'll feel great. Trust me.”
- “The most powerful being in the scene has made killing effortless.”
- “No fight, no moral anguish, no cost.”
- “Even the Main Man has no frame of reference...”
- “Two codes. One sword.”
- “Take us up / take us to the sun, or kill me now. The code demands it.”
- “Not begging. Demanding.”

Again, many of these are directly in the story bible, but the degree of scene-choreography overlap is still striking when reading the scripts back-to-back.

### Differences

Fable is better calibrated:

- The tonal turn from comedy to horror is more controlled.
- Krem's philosophy collapsing under fear is sharper.
- Lobo lighting a cigar and settling in for Ruthye's execution makes the moral wrongness more vivid.
- Kara's slash is staged as the weakest Supergirl doing the strongest moral act.

GLM is readable but blunter:

- It gives Lobo more generic one-liners.
- It explains the thesis in paragraph form.
- It subdivides the handoff / moment / slash / hit / reaction / Ruthye-and-Kara / escape / ultimatum into many scene headings, which makes the sequence feel less like one tightening vise.

### GLM story / craft issue

GLM adds a mirrored line at the later climax — Ruthye tells Kara, “I had to save you. That's my code.” It is understandable as a callback, but it risks over-explication. The Lobo scene already made that turn physical: Ruthye saved Kara by choosing the sun over Krem. Repeating the line later makes the code motif feel more declared than earned.

## 9. Yellow-sun rebirth

### Shared structure

Both drafts cut from Lobo's ascent into the full Argo memory, then back into yellow light above Bilki. Kara floats in space, wounded, fetal/open, the yellow sun heals her, and the shredded jacket drifts away like a shed skin. Ruthye cries in the bubble suit. Kara holds her. Lobo is mortified by the feelings and leaves with “that was fucked up” / “fucking codes, man.”

### Shared phrases / turns

- Full memory, not fragments.
- “Promise me you'll be good.”
- Kara's body insisting on living the way her parents insisted she live.
- The jacket as death shawl / old hide / thing she wrapped around herself to disappear.
- The sun does what the sun does; life insists on itself.
- Ruthye crying in the bubble.
- Lobo watching “two people hugboxing in the sunlight.”
- “The universe, personified, can do anything except feel.”

### Differences

Fable has the more powerful image grammar:

- Hands align across the bubble membrane.
- The barrier motif resolves: pod glass, tube glass, shell glass, bubble membrane.
- The jacket “simply cannot come with her into the person she is choosing to be.”

GLM states the metaphor more directly:

- “The metaphor doesn't need to be stated: from death to life...” — but then it states it.
- It says this is Kara Zor-El, the woman who promised her mother she'd be good.

### Shared issue from the source

Both drafts inherit the bible's simplified Argo catastrophe. If the next pass wants DC/Kara canon alignment, this should be rewritten as the two-stage Krypton/Argo trauma: Krypton dies, Argo survives, then Argo dies slowly from Kryptonite/radiation poisoning. This is not GLM-specific; both drafts need correction.

## 10. Climax / Krem non-fight / Ruthye's final choice

### Shared structure

Both drafts make the full-power climax a non-fight:

- Supergirl descends under her own power.
- Krem is at a shuttle with loot and an oversized weapon.
- The antidote hangs on a chain around his neck.
- He says some version of “There was never anyone to save us.”
- He fires; Kara is too fast / too powerful.
- She disables him more roughly than needed and catches herself being angry.
- He overloads the weapon in a red/white blast.
- Supergirl appears gone.
- Ruthye walks through smoke with sword drawn.
- Krem, hollowed out, says “Just do it.”
- Ruthye raises the sword as if to kill him.
- She cuts the chain, not the neck.
- Kara has been standing behind her, watching, trusting.
- They leave Krem's fate unshown.

### Shared phrases / turns

- “There was never anyone to save us.”
- “This is the place that taught him his creed.”
- “Mistaken surviving it for understanding the universe.”
- “The absurdity of the power disparity.”
- Kara didn't expect him to be so weak, or herself so angry.
- “Nothing in her body language telegraphs mercy. Nothing suggests hesitation.”
- “Killing him wouldn't prove anything. It wouldn't disprove anything. It would just be killing.”
- Kara protected / restrained / was saved by / now trusts Ruthye.
- “The story was never about him.”

### Differences

Fable's climax is cleaner because it keeps the father's crossbow in play:

- Krem has Andy's crossbow / poison bow, tying the first murder, tracker, and final non-fight together.
- Kara plucks a physical poison bolt out of the air; the image is simple and legible.
- The gold and jewels scattered in the ash give Krem's predation a visual grave.

GLM is more generic and a little confused:

- Krem has a giant energy cannon harness instead of the crossbow.
- Kara “plucks” an energy bolt out of the air, which is more comic-book abstract and less tactile.
- The cannon is attached to his left shoulder/arm, but Kara also “slams the cannon — the whole giant rig — out of his hand,” and later it is still attached as charred ruin. The mechanics wobble.
- The father's weapon/tracker setup is not paid off as a visible object.

### GLM story / craft issue

The final weapon sequence is a good example of GLM preserving the **shape** of Fable/bible — non-fight, power temptation, overload blast, Ruthye final choice — while losing the clean prop logic that makes Fable's version feel inevitable.

## 11. Resolution / birthday / Ruthye home

### Shared structure

Both drafts return to the clinic, inject Krypto, and let him breathe. Then they return Ruthye to her homestead, where her mother and brother are alive. Kara tells Ruthye she would trade the world for what Ruthye has. The “go home” line finally becomes true. Kara then remembers they never finished celebrating her birthday. Ruthye giggles for the first time.

### Shared phrases / turns

- No fanfare, no speech, just the needle and the breath.
- Krypto's full-body dog joy.
- “I would trade the world for what you have.”
- “The line that started as a drunk's plea in a bar...”
- “We never did get a chance to finish celebrating my birthday.”
- Ruthye's first giggle as the weight comes off.
- The red sky/light reclaimed as home rather than avoidance.

### Differences

Fable pays off the birthday cleanly:

- Ruthye goes with Kara in the ship for the birthday adventure.
- Kara yells, “We'll be back tonight! Tomorrow at the latest!”
- Marye asks, “Which?!”
- Final image: Ruthye laughing in the cockpit, Krypto's ears in the vents. The adventure finally gets to be fun.

GLM gets this muddled:

- Ruthye says she belongs at home.
- Kara says they never finished celebrating her birthday.
- Kara yells to Ruthye's mother, “We'll be back tonight — tomorrow at the latest!”
- But then Ruthye appears to stay behind: Kara hugs her, says “Be good,” goes up the ramp, and the final image is Ruthye watching the ship leave from the yard.

### GLM story issue

This is the clearest GLM-specific confusion.

The scene seems to want both endings at once:

1. Ruthye chooses home and stays with mother/brother.
2. Ruthye goes on the earned birthday flight and returns later.

Fable reconciles these: Ruthye belongs home, but she can take one joyful flight and come back. GLM instead has Kara announce “we'll be back” while visually leaving Ruthye behind, so the birthday line does not actually pay off.

## 12. Mid-credits / Kara home

### Shared structure

Both drafts end Kara in Metropolis, present rather than numb, with Krypto alive and no bottle in hand. She says some version of “Maybe I'll stick around a bit longer this time” and “It's good to be... home.”

### Differences

Fable includes the device / Kal call:

- Kara presses CALL.
- Clark answers on the first ring.
- This pays off the voicemail thread from the beginning.

GLM omits that:

- Kara looks out over Metropolis.
- Krypto causes chaos.
- Morning/yellow sun starts.
- The audience is told she is choosing to stay.

### GLM story issue

GLM's mid-credits is emotionally clear but structurally underpaid. Clark was the first evidence that Kara had a living family she was avoiding. If she never calls him / sees him / answers him, the “home” choice is less concrete.

---

# Phrase and motif ledger — with story-bible source audit

This is a selective ledger of shared turns that stood out in the manual pass, now annotated for whether the overlap appears to come from the shared `README.md` story bible.

Source-status legend:

- **Direct bible** = wording or near-wording appears in `README.md`.
- **Bible-specified beat** = the exact scenario/object/action is specified in `README.md`, even if the wording differs.
- **Bible-derived** = the overlap is a natural inference from a bible description, but not a line-for-line instruction.
- **Draft convergence** = not clearly dictated by the bible; more interesting as a Fable/GLM similarity.

| Phrase / motif | Fable usage | GLM usage | Story-bible source status | What to do with the similarity |
|---|---|---|---|---|
| Flat sodium-lamp / embalming red light | Opening Evelie palette | Opening Evelie palette | **Direct bible.** The visual-language section specifies “dead red,” “flat, sodium-lamp light,” and “embalmed.” | Not evidence of draft-to-draft similarity; both are faithfully carrying over palette language. |
| “Life exists because someone chose to build it” | Family warmth thesis | Farmhouse / normal life line | **Direct / close bible.** Cold-open section describes “ordinary domestic warmth” as “the kind of life that exists because someone chose to build it.” | Shared because the bible gives the sentence. Interesting only in how Fable dramatizes it with named family texture. |
| “The off-ramp” | Krem is leaving; murder is choice | GLM labels the same beat explicitly | **Direct bible / specified beat.** The bible repeatedly names the off-ramp and explains why Krem must refuse it. | Not a unique draft overlap; this is the required Krem mechanism. GLM is just more explicit. |
| “This is what the world is” | Krem's lesson; Ruthye later echoes | Same | **Direct bible.** Central Krem line appears throughout the bible. | Core required line; similarity expected. |
| “Rage ... already decided something” | Final cold-open image | Same | **Direct bible.** The final cold-open image includes this exact formulation. | Strong apparent overlap, but source is the bible. |
| Bottle before eyes open | Kara morning | Same | **Direct bible / specified image.** Kara reaches for bottle before eyes open. | Similarity expected; both keep the image rather than paraphrasing it away. |
| “Avoidance isn't something...” | Exact | Exact | **Direct bible.** The sentence appears nearly verbatim in the Kara morning section. | One of the most uncanny repeated lines, but it is bible language. |
| Kara notices Ruthye “despite herself” / recognizes something | Bar | Bar | **Direct / close bible.** The first-meeting section says Kara notices and is intrigued despite herself, maybe recognizing something. | Bible-derived. Fable's phrasing is punchier; GLM expands it. |
| “Go home” | First meeting | First meeting | **Bible-specified beat.** The section title and relationship line are “Go Home.” | Required structural refrain; not meaningful as independent convergence. |
| Baseball-sized metal/glass drive crystal | Bar reveal | Bar reveal | **Direct bible.** Bible specifies a “baseball-sized, grungy metal-and-glass case” with a glowing drive crystal. | Direct source carry-over. |
| “Residue, not command” | Brawl power grammar | Brawl power grammar | **Direct bible.** From the power-logic map and bar-brawl description. | Expected; both are using the same power rule language. |
| “You don't want to go there” / “Technically” | Info desk | Info desk | **Direct bible.** The rest-stop/info-desk scene gives this exchange. | Direct source carry-over. |
| “Now you won't die in space” | Bubble suit | Bubble suit | **Direct bible.** The bubble-ring purchase is specified with this line. | Direct source carry-over. |
| Washroom tear / hand on shoulder | Ruthye's armor drops | Same | **Bible-specified beat.** The washroom mirror, Ruthye looking smaller, Kara's shoulder/tear comfort are all in the bible. | Expected shared scenario. Fable is subtler; GLM is clearer. |
| Drop shell as luggage chute / plausible deniability | Bilki drop | Bilki drop | **Direct bible.** “Half escape pod, half luggage chute — rated for toxic atmosphere and plausible deniability.” | Direct source carry-over. |
| Yellow glint on shell; Kara hand to glass | Bilki drop | Bilki drop | **Bible-specified beat.** The bible explicitly describes the yellow glint and Kara pressing her hand to the shell. | Expected. Both preserve the barrier/light motif. |
| “Machines with no ideology and no mercy” | Bilki defenses | Same concept | **Direct bible.** The automated defenses section uses this phrase. | Direct source carry-over. |
| Lobo's Action Comics truck shot curdling into gore | Lobo scene | Same | **Bible-specified beat.** The bible explicitly asks for this homage curdling into horror. | Expected set-piece overlap. Fable executes it better. |
| Dying Brigand: “Please” / Lobo: “You're welcome” | Lobo scene | Same | **Direct / close bible.** The bible proposes this exact begging/response gag. | Direct source carry-over. |
| “A code ... worth more than all the corpses...” | Lobo to Ruthye | Same | **Direct bible.** Exact line appears in the Lobo section. | Direct source carry-over. |
| “You'll feel great. Trust me.” | Lobo handing over Krem | Same | **Direct bible.** Exact line appears in Lobo's handoff. | Direct source carry-over. |
| “No fight, no moral anguish, no cost” | Execution temptation | Same idea | **Direct bible.** The bible describes the execution temptation in this language. | Direct source carry-over; GLM leaves it more visibly as prose-theory. |
| Kara steps into the blade | Lobo scene | Same | **Bible-specified mechanism.** One of the central Act II turns. | Required plot mechanism, not independent convergence. |
| “That's my code” | Kara | Same | **Direct bible.** Exact line appears in the slash aftermath. | Direct source carry-over. |
| “Take us / kill me now. The code demands it.” | Ruthye to Lobo | Same | **Direct bible / specified beat.** The ultimatum is spelled out. | Direct source carry-over. |
| Jacket as death shawl / shed skin | Rebirth | Same | **Direct / close bible.** The bible describes jacket as death shawl / old hide / thing she used to disappear. | Expected motif. GLM overstates; Fable turns it into cleaner image grammar. |
| “Hugboxing in the sunlight” | Lobo discomfort | Same | **Direct bible.** Very distinctive exact phrase in the rebirth section. | Direct source carry-over; should not be counted as Fable-specific. |
| “Fucking codes, man” | Lobo exit | Same | **Direct bible.** Exact exit line. | Direct source carry-over. |
| “There was never anyone to save us” | Krem climax | Same | **Direct bible.** Exact Krem line in climax. | Direct source carry-over. |
| “Mistaken surviving it for understanding the universe” | Krem's worldview | Same / close | **Direct bible.** The climax section uses this phrasing. | Direct source carry-over, though still useful for seeing GLM's treatment-like register. |
| Killing him would prove/disprove nothing | Ruthye's final perception | Same | **Direct bible.** The final-choice section gives this logic almost verbatim. | Direct source carry-over. |
| Kara stands behind Ruthye and does not intervene | Final trust | Same | **Bible-specified mechanism.** Protected → restrained → saved → trusted is an explicit bible design. | Required climax design. Not evidence of unique similarity. |
| “I would trade the world for what you have” | Ending | Same | **Direct bible.** Exact line in ending. | Direct source carry-over. |
| Birthday/giggle | Ending | Same, but GLM muddles logistics | **Bible-specified payoff.** The birthday, Ruthye's first giggle, and final red-sky joy are spelled out. | Similarity expected; GLM's contradiction is the interesting part. |
| “Maybe I'll stick around...” | Mid-credits | Same | **Direct bible.** Exact mid-credits line. | Direct source carry-over. |
| Named Knoll family / Andy, Marye, Tomme | Fable uses specific names | GLM uses generic family labels | **Not bible-specified in the main treatment.** The bible names Ruthye but not these family names. | This is a Fable strength, not a GLM similarity. GLM's generic version is weaker. |
| Father's crossbow as prop chain | Fable uses it throughout | GLM lacks equivalent object | **Bible-derived but not required.** The bible says tracker is keyed to a taken family weapon; it does not require a crossbow object-chain. | Fable's independent craft solution. GLM's absence exposes a weakness. |
| Oasis Station name / stamp bureaucracy | Fable gives specific station identity | GLM has generic rest stop | **Bible-derived, not direct.** The bible asks for transit bureaucracy and weird mundane logistics, not this exact implementation. | Fable-specific improvement rather than shared overlap. |
| Kara's artificial yellow-sun emitter | Not in Fable | GLM adds it | **Not bible-specified; arguably against bible.** Bible wants one true yellow-sun rebirth. | GLM-specific drift/confusion, not similarity. |
| Ruthye staying vs. birthday flight contradiction | Fable cleanly sends her on the joy ride | GLM seems to leave her behind | **Bible-specified payoff, GLM mishandled.** Bible wants final image of Ruthye laughing/flying after choosing life. | This is a GLM confusion caused by trying to honor two endpoint ideas at once. |

## What this audit changes

The source audit downgrades a lot of the “uncanny” phrase overlap. Many of the strongest repeated phrases are **not Fable-specific**; they are lifted or closely paraphrased from the shared bible. The overlap is still worth documenting, but the interpretation should be:

- **Direct bible carry-over** explains most exact phrasing.
- **Shared scene choreography** explains most scenario overlap, because the bible already lays out the choreography in detail.
- The more meaningful comparison is **execution quality and failure modes**:
  - Fable adds specificity where the bible leaves room: names, crossbow object-chain, Oasis Station texture, cleaner image motifs.
  - GLM tends to literalize the bible, over-explain the theme, and occasionally introduce mechanics that conflict with the bible's guardrails.

So the most defensible claim is not “GLM copied Fable.” It is: **given the same detailed bible, GLM independently converges on many of the same lines and scene-shapes, but often as a more literal / confused adaptation of the source treatment, while Fable finds stronger cinematic objects and rhythms.**

---

# GLM-specific story confusions / weaker choices

These are the places where GLM is not merely “less stylish” than Fable but seems to lose track of story mechanics or payoff.

| Issue | Where | Why it matters |
|---|---|---|
| Artificial yellow-sun emitter | Ship countdown section | Adds gadget/power math and partially duplicates the one true yellow-sun rebirth. |
| Over-numeric countdown | Ship/medbay | Pushes audience into arithmetic despite the bible's “emotional pressure, not stopwatch” principle. |
| Dialogue attribution error | Rest-stop clinic | Kara appears to answer her own “And Krem is—” line with “The ranking officer. Yes.” |
| Father's weapon / tracker not paid off | Cold open → tracker → climax | GLM says tracker is keyed to a stolen family weapon, but no specific object carries emotional weight. Fable's crossbow solves this. |
| Final weapon mechanics wobble | Climax | Krem's cannon is harnessed to his arm, knocked out of his hand, then still attached and overloading. The physical action is muddy. |
| Energy “bolt” plucked from air | Climax | Less tactile and less thematically connected than Fable's poison arrow/crossbow image. |
| Bubble suit retracted during descent | Post-rebirth descent | Bilki atmosphere was established as dangerous; retracting protection before landing creates a continuity/safety question. |
| Birthday ending contradiction | Ending | Kara says “we'll be back,” but Ruthye appears not to go. The birthday payoff fizzles. |
| Clark voicemail not paid off | Mid-credits | Kara's living-family avoidance is set up through Clark, but GLM never answers him. |
| Ship repair / drive crystal abrupt | Resolution | GLM says Kara's ship has a salvaged Brigand drive crystal installed without the clean mechanic/graft payoff Fable provides. |
| Meta prose retained too bluntly | Throughout | “The audience should,” “the metaphor doesn't need to be stated,” etc. reads like treatment notes left in the screenplay. |

---

# Overall comparison by draft personality

## Fable draft

Fable feels like a more cinematic interpretation of the bible. It is still literary, sometimes too meta for a final screenplay, but it understands objects and motifs:

- Crossbow = father / violation / tracker / murder / final power disparity.
- Jacket = avoidance / armor / skin to shed.
- Glass/barriers = pod, porthole, tube, shell, bubble.
- Palette = argument.
- Lobo = seductive violence curdling in real time.
- Birthday = the first truly fun adventure, earned after choosing life.

Its main weakness is that it sometimes sounds like a brilliant treatment rather than a shootable script. But the movie in it is coherent.

## GLM draft

GLM feels like a faithful but less confident expansion of the same blueprint. It is longer, clearer in some logistics, and often more conventionally screenplay-shaped, but it loses some of the reasons the blueprint works.

Patterns:

- Splits Fable-like sequences into many smaller sluglined scenes.
- Explains emotional meanings that Fable lets images carry.
- Uses generic substitutes where Fable has named/specific objects.
- Adds mechanical problem-solving that complicates the clean moral/power design.
- Occasionally resolves a setup only halfway, or tries to satisfy two endings at once.

This is why it reads like “Fable, but worse”: not because it preserves every Fable choice — it actually drops several of the best ones — but because it follows the same scene skeleton and often the same prose turns while weakening the object logic and rhythm.

---

# Bottom line

The careful read changes the conclusion slightly:

- **Yes**, GLM and Fable are strikingly similar in structure, scenario order, emotional beat design, and many turns of phrase.
- **But** much of that similarity is best explained by the shared `README.md`, which is itself highly specific and phrase-rich.
- The real qualitative difference is execution: **Fable makes the story feel inevitable; GLM makes it feel explained.**
- GLM's most useful contribution is clarity and completeness; its biggest liability is confusion around mechanics/payoffs, especially the artificial-yellow-light beat, the final weapon, the birthday ending, and the missing Clark payoff.

If mining GLM for a future pass, I would not treat it as a source of new structure. Its structure is essentially the same. I would use it mainly as a checklist for:

1. places where Fable's compressed version may need a little more causal clarity, and
2. places where a model can accidentally misunderstand the bible, so the next draft should be explicit in the right way.

The Fable draft remains the stronger artistic execution; GLM is useful mostly because its mistakes reveal which story mechanics are fragile.
