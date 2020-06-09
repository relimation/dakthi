# Proto-Dakthi

This is a ~~draft~~ fictional protolang for Dakthi proper. It's speakers are an exotic insectoid species of the same name.

The Dakthi are a highly sexually dimorphic species. Only the males are sapient; the females have animal-level intelligence. Physically, adult females resemble large butterflies, while adult males resemble large crickets. So different are the sexes, that the Dakthi language doesn't have the concept of gender, not even on pronouns. Hereafter, whenever I refer to Dakthi, I will be referring to the males.

Without delving into the entire lifecycle, Dakthi reproduction requires the death of the parents. Upon emerging from the pupal stage, Dakthi retain the memories of their father. In a sense, they aren't even different people, but rather the same consciousness which has multiplied into the children. The entire stage of childhood maturation typical in most species is skipped. This does not mean that Dakthi remember everything from the beginning of time; memories fade and distort, just like anyone.

The linguistic consequence is that plurality and the past are intricately connected. Across a reproductive cycle, the past tense of "I sit" is not "I sat" but "We sat", as in "We, us brothers who collectively remember the same act of sitting".

## Phonology

*Consonants*
|             | Mandibular | Labrumal | Ligular | Mentumal |Submentumal| Hypopharyngeal |
|-------------|:----------:|:--------:|:-------:|:--------:|:---------:|:--------------:|
| Plosive     | p          | t        | k       | d        | c         | q              |
| Click       | !          |          | ǂ        | ǁ        |           |                |
| Fricative   | θ          |          | x       | r        |           |                |
| Approximate |            |          | j       | l        |           |                |

Yes, that table looks strange, though perhaps not so strange if you've read [this post by /u/MobiusFlip](https://www.reddit.com/r/conlangs/comments/6p59py/do_you_have_any_additional_places_of_articulation/dkn2elg/). I've ~~butchered~~ reworked his phonology for my purposes. 

/ p t k d c q ! ǂ ǁ θ x r j l /

*Vowels*

/a e i o u/

*Vibratives*

Dakthi have four vibratives that can be coarticulated with other phonemes. They are crestal /s/, palpitative /z/, spiraculative /f/, and hypopharyngeal /v/. I mark them with a prefix, but understand they are articulated for the whole word. If adjacent words are marked with the same vibrative, they are not released and rearticulated, but carried across the words.

*Syllable Structure*

CV

*Stress*
Stress always falls on the final syllable of the root. Suffixes are not stressed. 

## Writing system
Dakthi dip both of their antennae in ink, to use as brushes for calligraphic writing. Dakthi is written top-to-bottom, left-to-right. With only 14 consonants, 5 vowels, and a fixed syllable structure, Proto-Dakthi used a 70-character syllabary for vowels and consonants. However, sound changes have led to some historical spelling. Vibratives marked with vertical lines beside/through the glyphs.

Many of the glyphs feature parallel lines or rotations; these are drawn with both antennae simultaneously. Note that free, independent movement from both antennae would exceed a Dakthi's ability to concentrate on fine motor skills, which why these parallel glyphs arose in the first place. 

## Grammar

### Introduction

Dakthi is a head-final, analytic language. Aside from negation, affixes are only used to change part of speech.

Every Dakthi verb requires both a subject and object. Some intransitive English verbs become reflexive, while others incorporate prepositions.

Subject - Object - Verb

Adjective - Noun

Classifier - Numeral/Quantifier - (Noun)

Noun - Postposition

Possessor - Possessive Particle - Possessee

Verb - Auxiliary

### Pronouns
	pe  	I   	1.SG
	s'pe	we   	1.PL
	te  	you  	2.SG
	s'te	y'all	2.PL
	ke  	he/she	3.SG
	s'ke	they	3.PL
	qe	it	ANIM.SG
	s'qe	its	ANIM.PL
	qela	it	INAN.SG
	s'qela	its	INAN.PL

Note that the plural forms have a strong sense of collective memory. "s'pe" best translates as "we, who have shared memory" rather than English "we, who are in proximity to the speaker"; similarly for the 2nd and 3rd persons. A Dakthi would prefer passive constructions such as "the people" to avoid referring a group of mixed company with a collective pronoun, even if "the people" includes the speaker or audience.

If the speaker refers to a future event after an expected reproductive cycle, the plural form is again used. This creates ambiguous sentences, resolved by context.

	s'pe 	te 	poxi	ti
	1PL 	2SG	see 	will
	We, as in I who will reproduce, will see you./
	We, us brothers/cousins who share memory, will see you.

The more distant the relation, the less relevant the shared memory, the less likely is it that the second meaning is implied.

# Derivation

Dakthi has several productive affixes to change part of speech.

	-qu  	Derives classifier from noun
	da-  	Derives noun from verb's object
	-xoli	Derives noun from verb's agent
	-ru  	Derives adjective from noun

Dakthi lacks definite/indefinite marking. Instead, a speaker may indicate definiteness with use of the "da-" prefix.

	ke  ǁidala poxi. ke  dapoxi     kowa. dakowa      ca!uru do
	1SG rock   see.  1SG seen.thing take. taken.thing black  COP
	Lit. I see a rock. I take the thing I saw. The thing I took is black.
	I see a rock. I take the rock. The rock is black.

Note how the same rock is derived from a new verb in each sentence. This is typical in informal speech, but "dapoxi" could have been used in the third sentence for emphasis, particularly for literary effect. 

Of course, a shorter construction would simply use the inanimate, alienable pronoun "qela" here. However, pronouns can be ambiguous.

	ke  ǁidala poxi. ke  xiri kowa. qela       ca!uru do
	1SG rock   see.  1SG cup  take. POSS.ALIEN black  COP
	I see a rock. I take a cup. It is black.

"it" is ambiguous between the rock and the cup here. We can disambiguate with "dapoxi" (the thing I saw; the rock) or "dakowa" (the thing I took; the cup). Just using "ǁidala" (rock) or "xiri" (cup) would introduce a different ambiguity; the speaker could be referring to the previously mentioned rock and cup, or some new rock or cup.

### Past/Plural
Layering the /s/ vibrative onto a verb phrase turns it into past tense.

	xoli 	!eju 	s'poxi
	person	animal	PST-see
	The person saw the animal

Layering /s/ onto a noun phrase turns it plural

	s'xoli 		!eju 	poxi
	PL-person	animal	see	 
	The people see the animal

Adjectives must agree with the noun

	xoli 	s'kapa	s'!eju 		poxi
	Person	PL-big	PL-animal	see
	The person sees the big animals

### Causative/Deontic Aspect
Layering the /v/ vibrative onto an additional noun turns into a causitive. 
The causation noun must the start of the sentence

	v'pe 	xoli 	!eju 	poxi
	CAU-1SG	person	animal	see
	I make the person see the animal

The causative is often used for instructions, but other constructions work.

	v'pe` xiri xalaqe do
	CAU-1SG cup full be
	Lit. I make the cup be full
	I fill the cup

	v'pe v'rali v'qatole pe qela puli
	CAU-1SG POSS.INAL hunger 1SG it eat
	Lit. My hunger makes me eat it.

Removing the causer and shifting /v/ onto the verb phrase adds the deontic mood 

	xoli 	!eju	v'poxi
	person	animal	DEO-see
	The person must see the animal

If instead the /v/ layering is on the agent of a sentence, the sentence is both deontic and descriptive.

	v'xoli 	    	!eju 	poxi
	DEO-person	animal	see
	The person must see the animal, and he is. 

The /v/ layering reminds the listener that his action is a fulfilment of a duty. 

This turns /v/ layering on pronouns into a type of honorific, but not one that maps onto traditional human social heirarchies. Both leaders and peasants may or may not use the /v/ honorific; the key aspect being that they must be fulfilling their duty.

Obligations are so important to Dakthi, that even desires are expressed by negating obligative phrases.

	pe	v'roti-ca
	1SG	DEO-sit-NEG
	I must not sit (but I want to).

### Interrogative Mood
Layering the /f/ vibrative onto a verb phrase adds the interrogative mood.

On the copula, /f/ asks yes/no questions

	xoli	kexa	f'do
	person	dead	INT-COP
	Is the person dead?

	xoli	kexa	f'ca
	person	dead	INT-COP.NEG
	Is the person not dead? (presumptively he was)

If the declarative statement lack a copula, it can be added as a particle.

	ke	!eju	tali	f'do
	3SG	animal	hunt	INT
	Is he hunting the animal?

	ke	!eju	tali	f'ca
	3SG	animal	hunt	INT-NEG
	Is he not hunting the animal? (presumptively he is)

Yes/no question are affirmatively answered with echo response. Affirmative answers to the above examples would be "kexa" and "tali" respectively.

Negative answers simply respond with "ca". 

When /f/ is layered onto a collective noun, it asks for which item from the class.

"ǂaco" means thing, so "f'ǂaco" forms what

	te 	f'ǂaco		poxi
	2SG	INT-thing	see?
	Lit. What thing do you see?
	What do you see?

	vf'ǂaco     	te	roti
	CAU-INT-thing	2SG	sit
	Lit. What thing caused you to sit?
	Why are you sitting?

"xoli" means person, so "f'xoli" forms who/whom

	f'xoli 		te 	poxi
	INT-person	2SG	see
	Lit. What person sees you?
	Who sees you?

	te 	f'xoli 		poxi
	2SG	INT-person	see
	Lit. What person do you see?
	You see whom?

	vf'xoli	    	te 	roti
	CAU-INT-person	2SG	sit
	Who made you sit?

"qaceli" means place, so "f'qaceli" forms where

	te 	f'qaceli	raθe
	2SG	INT-place	go
	Lit. What place are you going to?
	Where are you going?

On the verb, /f/ interrogates how (manner)

	te 	qaceli	f'raθe
	2SG	place	INT-go
	How are you going to the place?

### Evidential Aspect
Layering the /z/ vibrative adds evidentiality. The source of the evidence may be added to the start of the sentence

	z'te 	xoli 	!eju 	poxi
	EV-2SG	person	animal	see
	You know the person sees the animal 

If omitted, the source is understood to be the speaker.

	xoli 	!eju 	z'poxi
	person	animal	EV-see
	(I know) the person sees the animal

/z/ may be layered on other parts of the sentence to emphasize certainty

	z'xoli 		!eju 	poxi
	EV.EMP-person	animal	see
	(I know) *the person* sees the animal

	xoli 	z'!eju 		poxi
	person	EV.EMP-animal	see
	(I know) The person sees *the animal*

If plural is added to the evidential source, evidence is understood to come from shared collective memory. This invalidates certain combinations of tenses.

	*zs'pe 	xoli 	!eju 	poxi
	EV-PL-1	person	animal	sees
	We know (from shared memory) the person sees the animal

That is ungrammatical, for even if we are all witnessing the event first-hand, we would not have a shared memory of the present.

	zs'pe	xoli 	!eju 	s'poxi
	EV-Pl-1	person	animal	PST-saw
	We know (from our shared memory) the person saw the animal

With the verb in the past tense, the sentence is grammatical.

### Copula
"do" is the copula

	xoli 	kapa 	do
	person	big 	COP
	The person is big

	xoli	kapa	s'do
	person	big 	PST-COP
	The person was big

	!eju	kexa	v'do
	animal	dead	DEO-COP
	The animal should be dead

	v'pe	xoli	kexa	do
	CAU-1SG	person	dead	COP
	Lit. I make the person dead
	I kill the person

	xoli	kexa	z'do
	person	dead	EV-COP
	(I know) the person is dead.

There is a second negative copula, "ca".

	xoli	kapa	ca
	person	big	COP.NEG
	The person isn't big

### Conjunctions

The copula "do" may also be used as the or conjunction, but only between clauses.

	pe	!eju 	poxi	do	te 	ce	rito
	1SG	animal	see 	or	2SG	REFL	sit
	(I see the animal) or (you sit)

The negative copula "ca" cannot be used as a conjunction.

	*pe	!eju	poxi	ca	te 	ce	rito
	1SG	animal	see 	not	2SG	REFL	sit
	(I see the animal) not (you sit)

That is ungrammatical. Of course, "-ca" still works a negative affix

	pe 	!eju 	poxi	do	te 	ce	rito-ca
	1SG	animal	see	or	2SG	REFL	sit-NEG
	(I see the animal) or (you don't sit)

Layering in /s/ turns "do" into and. 

	pe 	!eju 	poxi	s'do	te 	ce	rito
	1SG	animal	see 	and 	2SG	REFL	sit
	(I see the animal) and (you sit)

Layering in /v/ turns "do" into so. 

	pe 	!eju 	poxi	v'do	v'pe 	!eju 	kexa	do
	1SG	animal	see 	so	CAU-1SG	animal	dead	COP
	Lit. (I see the animal) so (I make the animal be dead)
	(I see the animal) so (I kill the animal)

The or conjunction "li" is used between nouns

	pe 	!eju 	li	te 	poxi
	1SG	animal	or	2SG	see
	I see (the animal or you)

Similarly, layering in /s/ turns "li" into and. 

	pe 	!eju 	s'li	te 	poxi
	1SG	animal	and 	2SG	see
	I see (the animal and you)

However, layering /v/ onto "li" works the same as layering /v/ onto any noun phrase

	v'ke	v'li	v'pe	ce	rito
	DEO-2SG	DEO-and DEO-1SG REFL	sit
	You and I must sit.

/v/ layering is typically done across the the entire noun phrase, but can be shifted for emphasis

	v'ke		v'li	pe	ce	rito
	EMP.DEO-2SG	DEO-and 1SG	REFL	sit
	You and I (but especially you) must sit.

# Numerals

Dakthi has six digits.

| Dakthi | Digit |
|--------|:-----:|
| ci     | 0     |
| po     | 1     |
| ta     | 2     |
| ku     | 3     |
| di     | 4     |
| qi     | 5     |

Dakthi uses an alternating radix system; starting in base-6, then base-4, back to base-6, and so on.

| Digit | Multiplier  |
|-------| ------------|
| 1st   | 1           |
| 2nd   | 6    =1×6   |
| 3rd   | 24   =6×4   |
| 4th   | 144  =24×6  |
| 5th   | 576  =144×4 |
| 6th   | 3456 =576×6 |

Dakthi count base-6 digits by tapping one of their six legs, then use their left and right antennae and mandibles to count base-4 digits. 

Dakthi is read out least significant digit first (backwards to most humans). So qi-ta-po-ci-di = 5₆2₄1₆0₄4₆ = 5×1 + 2×6 + 1×24 + 0×144 + 4×576 = 5 + 12 + 24 + 0 + 2304 = 2345₁₀. 

Something like ta-qi = 2₆5₄ = 2×1 + 5×6 = 2 + 30 = 32₁₀ is understandable, but improper; that second digit shouldn't exceed it's radix. The proper form is ta-po-po = 2₆1₄1₆ = 2×1 + 1×6 + 1×24 = 2 + 6 + 24 = 32₁₀.

A bare number without a classifier is ungrammatical. The common generic classifiers are "xoqu", "juqu", and "laqu" for Dakthi, animate, and inanimate nouns respectively. However, Dakthi has an open set of classifiers; the "-qu" suffix may be added to any noun to produce a classifier. The productive nature of Dakthi classifiers eliminates the distinction between mass nouns and count nouns.

        s'xiri-qu       s'ku-po s'dajuθepa
        PL-cup-CL       PL-nine water
        nine cups of water

        s'xo-qu         s'ku-po s'pe
        PL-person-CL    PL-nine PL-1
        nine of us

Note how pluralisation must agree for the entire noun phrase.

The noun can be omitted, trading ambiguity for brevity.

        s'xiri-qu       s'ku-po
        PL-cup-CL       PL-nine
        nine cups

        s'xo-qu         s'ku-po
        PL-person-CL    PL-nine
        nine people

Ordinal numbers are indicated by adding the adjective suffix "-ru" the number.

        xiri-qu ku-po-ru        jupata
        cup-CL  nine-ORD        water
        ninth cup of water

        xo-qu           ku-po-ru
        person-CL       nine-ORD
        ninth person

Fractional numbers are indicated by placing the denominator before the classifier, and the numerator after.

        s'ci-po s'xiri-qu       s'qi
        PL-six  PL-cup-CL       PL-five
        five sixths of a cup

Improper fractions are preferred over mixed fractions.

Quantifiers also use the classifier construction

	s'xiri-qu	s'ciri
	PL-cup-CL	PL-all
	all cups

	s'xiri-qu	s'repe
	PL-cup-CL	PL-some
	some cups

# Comparatives

"kilo" and "kila" translate to more and less, respectively.

	ke  kilo diloqeru do
	2SG more young    COP
	You are younger.

	ke  kila rataru    do
	2SG less honorable COP
	You are less honorable.

"z'li" is the conjunction used for comparison. Unlike English "than", "z'li" is a conjunction, not an adjunct; it cannot move to the end of the phrase.

	ke  z'li pe  kilo lora  do
	2SG than 1SG more quick COP
	You are quicker than me.

Comparatives can precede classifiers.

	ke  z'li pe  kilo s'xiri-qu s'ku     s'jupata ǁaθe
	2SG than 1SG more PL-cup-CL PL-three PL-water POSS.ALIEN
	You have three more cups of water than me.

The numeral may be omitted in a comparison.

	ke  z'li pe  kilo s'xiri-qu s'jupata ǁaθe
	2SG than 1SG more PL-cup-CL PL-water POSS.ALIEN
	You have more cups of water than me.

Superlatives are constructed using a quantifier

	s'xoqu       s'ciri rali      ke  kilo rataru do
	PL-person.CL PL-all POSS.INAL 2SG more honorable COP
	Of all people, you are most honorable.

# Nature

Weather verbs in Dakthi take the subject noun "ǁixa".

        ǁixa    ce      juθepa
        nature  REFL    water
        Lit. Nature waters itself.
        It rains.

        ǁixa    ce      θiǂuǁa
        nature  REFL    shines.upon
        Lit. Nature shines upon itself.
        It is sunny.

Unlike the English it, ǁixa has semantic meaning; nature. Weather is always done by nature. The object doesn't need to be reflexive.

        ǁixa    poticiqi        ca!uro
        nature  sun             covers
        Lit. Nature covers the sun.
        It is cloudy.

Dakthi experience frequent eclipses, described using the same word "ca!uro". As inanimate nouns, neither the moon or the world can act as agents, so a causative construction is used.

        v'ǁixa          joθa    papi    ca!uro
        CAU-nature      world   moon    cover
        Lit. Nature makes the world cover the moon.
        There is a lunar eclipse.

        v'ǁixa          papi    poticiqi        ca!uro
        CAU-nature      moon    sun             cover
        Lit. Nature makes the moon cover the sun.
        There is a solar eclipse.

Dakthi believe nature has certain obligations.

        ǁixa    ce      v'juθepa
        nature  REFL    DEO-water
        Lit. Nature must water itself.
        It must rain.

Droughts are not simply unfortunate, but morally wrong; nature has failed it's duty to water itself. In this way, nature is anthropomorphized, but not deified. Nature is not a perfect thing to be worshipped, but another person to be chastised why they fail.


## Evolution

A few brief notes on how Proto-Dakthi is likely to evolve

- Phonological evolution will increase syllable structure complexity
- vibratives may be incorporated into some words
- Vibrative slurring; when a vibrative surrounds a word, the word will also take on the vibrative
- Definiteness and quantifiers will emerge 
- Subordinate clauses


## Summary

My goals for this language are to highlight the alien elements of Dakthi biology, making the most use of vibratives. The language should feel alien and bizarre, but not Lovecraftian levels of incomprehensible. It should make and erase distinctions typical of human culture.

- Are there any suggestions to better accomplish my goals? Feel free even if your suggestion requires a complete rework
- Two of my vibratives, /z/.EV and /v/.CAU, can increase the valency of the clause. Could/should the other vibratives do the same? How? There doesn't seem like a natural way of extending the concept the way /v/ deontic changes to /v/ causative.
- The /z/ and /v/ vibratives are only used for emphasis on non-valency changing nouns; what else could they communicate here? This may conflict with vibrative incorporation evolution, but maybe such conflict could lead to interesting irregularities?
