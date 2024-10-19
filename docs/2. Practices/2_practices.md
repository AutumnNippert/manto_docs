# Practices

In this section, we explain how to collect data for MANTO.

## 2.1 Getting help

In Nodegoat we can flag problems and leave notes for each other in
entities, ties, and passages:

* **Note (Private):** Here you can leave notes for other
 data collectors about decisions you have made, points of uncertainty
 etc. These are not visible in the public interface.

* **Commentary:** Here you can add commentary that will
 appear in the public interface and help general users understand the
 context for the data, points of uncertainty etc.

* **Attention Required?** Default is 'no'. Change to 'yes'
 when the data requires attention from an expert. This is the best way
 to flag issues that cannot be resolved at the time. Always clearly
 explain what the problem is using **Note** and include
 your name or initials.

* **Checked?** Default is 'no'. Change to 'yes' when the
 data has been checked.

* **Modified?** Default is 'no'. Change to 'yes' if you
 have changed data that had previously been checked and you think that
 someone might want to find it later, but there are no issues that
 would warrant using **Attention Required?**.

* **Add to Public Interface?** Default is 'no'. Change to
 'yes' only when all data for that text has been checked by an expert
 (usually Greta). **[When 'yes' is selected, the tie and its entities will be visible in the public interface].** (The server
 typically requires an hour to update.) **Entities that appear only in unchecked ties will be visible in the public interface if they have attributes that are used in ties that appear in the public interface.**

For further information on communication during the data collection
process, see [5.1](5_data-management.md/#51-communication).

## 2.2 Passages: the basics 

When you identify a passage that provides evidence for a tie, consider
carefully how much text is useful. Be over-generous with the line
numbers you give so that the user gets the context for the information,
and not just (e.g.) the line or section in which the relevant names
appear. Reuse the same passage for as many ties as reasonably possible.

It's quite common to find that a story is interrupted only to be
finished later. As ever, you should always attempt to create fewer,
fuller ties, so treat both parts of the story as a single episode. If
possible, you should then connect that tie to a passage that extends
across both parts of the story (including whatever interrupted it). If
that is not possible (or the passage created would be far too long) then
create two separate passages and connect them to identical ties that
express the full episode. If you (ever!) think a user might be confused
about what you've done and where all your information comes from,
explain yourself in **Commentary** or
**Note.**

### 2.2.1 Creating a passage in Nodegoat 

If the **Author** does not yet exist in MANTO, you will
need to create it:

* **Name**: Follow house style (see [3.1](3_style_guide.md/#31-house-style)) and existing practice. As a general
 rule, aim to create as concise a name as possible since shorter names
 make the interface easier to read. If the author is pseudonymous, use
 the form Ps-\Name\ (e.g. Ps-Plutarch).

* **Identifier**: Give a word or brief phrase that
 distinguishes the author from those with similar names; e.g.,
 Apollodoros the Mythographer and Apollodoros of Athens. This field is
 not visible in the public interface.

* **Alternative names**: Give alternative forms of the
 author's name; e.g. 'Apollodorus' for Apollodoros; 'Pisander' for
 Peisander. This field is not visible in the public interface but aids
 searchability.

* **Note**: Use to provide further information when
 necessary. This field is not visible in the public interface.

* **Wikipedia**: Give a URL for the text in Wikipedia.
 This will become a clickable link in Nodegoat.

If the **Text** does not yet exist in MANTO, you will need
to create it:

**Author**: Select from existing dataset.

* **Title**: Follow house style (see
3.1(#house-style)) and existing practice. As a general
rule, aim to create as concise a name as possible since shorter names
make the interface easier to read. If the text is commonly known by
just the name of its author (e.g., 'Pausanias', 'Strabo'), leave
blank.

* **Alternative title**: give alternative forms of the
name of the text. This field is not visible in the public interface
but aids searchability. If the text is commonly known by just the name
of the author so you have not entered anything in
* **Title**, add the title of the work here.

* **Wikipedia**: Give a URL for the text in Wikipedia.
This will become a clickable link in Nodegoat.

*The fields that follow assign classifications that allow MANTO's data
to be filtered by place, time, and type of evidence*:

* **Source subtype**: Select any genres from the existing
dataset that could usefully classify this text. Multiple subtypes are
allowed in this field; add all that apply. Do not add to the existing
list unless the subtype will be useful for identifying a reasonably
large group of texts. If no other suitable subtype exists, use "Other
prose" or "Other poetry".

* **Period:** Select only from existing dataset. Select
all periods that could apply.

* **Place of Creation:** This field should only be used
where the text expresses the distinctive storytelling perspective of a
place associated with its creation. It is most likely to be used for
texts written to be performed in a specific place (e.g. Attic
tragedies). Select from existing dataset or create new (see [2.4.4 in Manual](2_practices.md/#244-creating-places-and-landmarks)).
Use the city as the most granular location, or region if the city is
unknown. Multiple entries are allowed in this field.

* **Populates "Places" reversal**

* **Place of Commissioning:** This field should only be
used where the text expresses the distinctive storytelling perspective
of a place associated with its commissioning, and that place does not
already appear in **Place of Creation**. Select from
existing dataset or create new (see [2.4.4 in Manual](2_practices.md/#244-creating-places-and-landmarks)).
Use the city as the most granular location, or region if city is
unknown. Multiple entries are allowed in this field.

* **Populates "Places" reversal**

* **Language**: Select any that apply from the list.

* **Note**: Use to provide further information when
necessary. This field is not visible in the public interface.

* **Commentary:** Record information about the
classifications assigned where necessary.

Now, create your passage:

* **Text**: Select from existing dataset.

* **Prefix Edition:** Use if you need to identify a
particular edition (e.g. for fragments) that is conventionally placed
before the fragment number, e.g. FGH, FGrHist 123, BNJ 123. Follow
existing practice for formatting.

* **Passage:** Enter passage(s) of prose text, line(s) of
poetry, or fragment numbers. Don't abbreviate runs of numbers: use
full references including book number (e.g. 2.123-2.154). For
fragments, use the format 'fr. 5b'; for testimonia, use the
abbreviation 'test.'

* **Edition:** Use if you need to identify a particular
edition (e.g. for fragments) that is conventionally placed after the
fragment number. Give the conventional abbreviation as found in the
*Oxford Classical Dictionary*. When creating an edition, provide
bibliographic details (author, title of work, publisher and year) in
* **Full name.**

The following three fields **[(Alternative Prefix Edition, Alternative
Passage, Alternative Edition)]** allow you to enter a
second set of references that identify the same passage. Follow the
instructions given in the three fields above. The two passages will
display with = between them. E.g.: Hecataios of Miletos fr. 25 Fowler
= FGrHist 1 fr. 25.

* **Scaife URL:** Give a URL for the passage in the Scaife
Viewer. This will become a clickable link in Nodegoat. Link to the
most recent English translation, where available. The lines or passage
numbers should be the same as in **Passage**. This will
become a clickable link in Nodegoat.

* **Non-Scaife URL:** If the text is not in Scaife Viewer,
give a URL to another online translation (or original text if that's
all there is.) This will become a clickable link in Nodegoat.

NB: If you need to add or edit a large number of passages to Nodegoat,
it can be a lot easier to create or edit these in a spreadsheet and
then upload that. There are instructions at
[4.11](4_issues.md/#411-uploading-data-using-a-spreadsheet).

## 2.3 Entities: the basics

Entities are the basic, stable components of our database. In theory,
each has its own identity and is clearly distinct from all others.

Your first task is to decide whether an entity should exist in MANTO. We
want our dataset to be comprehensive, but that does not mean that we
need to capture every last thing mentioned in every ancient source.
Equally, we don't create a new entity if we can use an existing one. In
general, we capture all entities that are either:

\(1\) mythically significant (i.e. someone might search for them),

\(2\) given a distinctive name,

\(3\) act as nodes with ties to at least two other entities which
would not otherwise be (as precisely) connected, or

\(4\) required to capture a few historical phenomena

* **Agents:** All named characters must be created as entities. Characters
without names can be ignored unless they create connections between
entities that would not be otherwise apparent (i.e. criterion 3). This
happens a lot in genealogies: i.e. to capture the fact that a hero is
the grandson of another, you might have to create an anonymous mother or
father. (For instructions on naming anonymous entities, see
[2.4.1.3](2_practices.md/#2413-anonymous-entities).)

* **Objects:** the third criterion ('act as nodes...') is also important
in relation to objects. Where a weapon is mentioned solely as the means
by which one hero kills another, it should not be captured as an entity
since it adds nothing to our relational data except more detail. By
contrast, an object like the [Bow of Heracles](https://manto.unh.edu/viewer.p/60/2616/object/6580-8190312)
(see fig.
[1.1.2 (broken-link)](#figure-1.1.-illustration-of-the-concept-of-mythic-networks-graphic-g.-goodwin))
easily fulfills the third criterion since it has a biography of its own:
Apollo gives it to Heracles, Heracles uses it to kill or wound various
monsters, and Philoctetes inherits it. Objects later preserved as relics
must be captured.

* **Collectives:** these should be created as seldom as possible.
Collectives are only useful in MANTO when they represent distinct groups
like siblings with a collective identity (e.g., 'the Daughters of
Proitos'), heroes who come together to achieve a particular purpose
(e.g., 'the Seven Against Thebes') or recognisable species (e.g., 'the
Centaurs'). Large or indistinct groups like 'the Nymphs' should not be
created, but significant groups of nymphs (e.g., the Dictaian Nymphs who
raise Zeus) can be if necessary. Do not create a collective if a place
could easily be used instead (e.g. use 'CADMOS rules THEBES' and not
'CADMOS rules THE THEBANS'.)

* **Mythic Events**: these should be created as seldom as possible. Mythic
events are only useful in MANTO when they bring together agents and
collectives who would not be connected in other ways. Do not create an
event if a collective could be used instead (e.g use 'ACHILLES is member
of THE GREEK CONTINGENT AT TROY' rather than creating 'the Trojan War').
We do create events for: (1) one-off games like [the Funeral Games of Patroclos](https://manto.unh.edu/viewer.p/60/2616/object/6580-9744213)
(see [2.8.11](2_practices.md/#2811-competitions) for the reversals these trigger); (2) prominent weddings like that of [Peleus and Thetis](https://manto.unh.edu/viewer.p/60/2616/object/6580-11296614);
(3) events that create damage etc and so are needed to create ties
(e.g., [the Flood of Deucalion](https://manto.unh.edu/viewer.p/60/2616/object/6580-9055626));
(4) events whose protagonist is immortal, and so capturing the event
helps to establish chronological connections amongst other participants
that wouldn't otherwise be apparent (e.g. [the Search of Demeter for Persephone](https://manto.unh.edu/viewer.p/60/2616/object/6580-10215370))

### 2.3.1 Entity types

Your second task is to decide which **Entity Type** you
should create. You can easily identify the type of existing entities by
the emoji in front of their names. (Nodegoat automatically adds these.)

👤AGENTS: Living entities in the *spatium mythicum*: gods, heroes,
monsters, animals.

👥COLLECTIVES: Groups of agents with recognizable collective
identities. E.g. the Amazons, the Greek Contingent at Troy, the
Daughters of Proitos. If the collective doesn't (and will never) have
any agents, add the **Entity Subtype** 'collective
without members'. This sub-categorisation affects the reversals
relating to children and parents.

🏺OBJECTS: Moveable, object-like entities with specific, recognizable
identities said to be present in the *spatium mythicum.* Some were
preserved as relics in the *spatium historicum.* Includes weapons,
clothing, jewelry, body parts, bones of heroes, statues.

🏛️LANDMARKS: Immovable buildings or smaller natural features which are
(typically) fixed in the landscape. Said to be present in the *spatium
mythicum*; some were preserved as relics in the *spatium historicum.*
Includes city walls, buildings, trees, tombs, altars, springs.

🌍PLACES: Geographical locations, whether fictional or real. Includes
regions, cities, areas within cities, sanctuaries, groves, mountains,
rivers.

⭐CONSTELLATIONS: Stars, groups of stars, planets and other heavenly
bodies in the night sky; typically created when a god or hero is
metamorphosed.

⏳ MYTHICAL EVENTS: Significant events in the mythical period with
widespread participation which cannot be captured in other ways.

📅{.mark} HISTORICAL EVENTS: Significant events in the historical
period used to date (e.g.) when relics were moved.

💠HISTORICAL ARTIFACTS: objects and landmarks created in the *spatium
historicum* and captured in MANTO because they depict a mythical
narrative or were associated with historical cult.

When you are deciding which type to use, look at similar entities in the
checked data and think about how you want your entity to be treated by
Nodegoat. **Entity Type** affects which reversals will be
triggered, and which attributes you can assign. Some things to keep in
mind:

-   Agents (and some collectives) are typically the only entities used
    in 'Blood relationship' ties
    (2.8.2(#blood-relationships)).

-   Certain words ('Sword', 'Altar', 'Sheep' etc) will trigger reversals
    in certain entity types (for details, see
    2.4.2-8(#creating-agents-and-collectives)).

-   If the entity is preserved as a relic in the historical period it
    should be either a landmark or an object.

-   A landmark will not (typically) be movable; an object might be.

-   A landmark or historical artifact might be located within another
    landmark, historical artifact, or place. A place might be located
    within another place but would not typically be located within a
    landmark or historical artifact.

-   If your landmark or object didn't exist in the mythic period,
    consider making it a historical artifact instead. If it's not clear
    whether it existed in mythic period, then err on the side of caution
    and make it a landmark or object. Tombs of agents and collectives
    should not be historical artifacts even if you suspect they were
    built in the historical period.

-   Historical artifacts should only be used to capture cult sites and
    depictions.

-   Historical events are only used in timemarks. They should thus not
    appear in 'related entities'.

## 2.4 Creating entities

Entities are given attributes (called 'sub-objects' in Nodegoat).
Nodegoat does not restrict which attributes you can use with which
* **Entity Type**, but in practice you will give different
kinds of attributes to different types of entities. Sometimes attributes
are used differently between entity types.

Read the instructions in the next sections carefully. Adding specific
words to certain fields will trigger reversals. If these reversals are
not accurate in the case of the entity you are creating, keep the
relevant field(s) empty and leave a note explaining why you did this.

Use **Note, Commentary,** and **[Attention
Required]** as necessary (see
2.1(#getting-help)). The checkboxes that appear after
* **Modified?** relate to specific research projects: do not
touch these.

If you are creating entities that represent alternative names or
rationalized forms of other entities, or personifications, or the entity
you are creating doesn't have a name, read
2.4.1.1-4(#alternative-name-entities) first.

### 2.4.2 Creating agents and collectives 

* **Name:** This is a required field. Follow house style
(see 3.1(#house-style)) and existing practice.

**Agents and collectives with 'Cattle', 'Cow', 'Bull', 'Mare' 'Horse',
'Dog', 'Sheep', 'Lamb', 'Ram', 'Dove', 'Serpent', 'Turtle' 'Livestock'
in Name populate the filecard categories 'animal/animals
belonging to', 'animals' when Of contains an agent or
collective. (If the animal has a proper name, use that here. Placing
'(horse)' or '(dog)' in Minimal Disambiguation will also
trigger this reversal.)**

The next name fields are optional. They are free text fields that aid
findability; i.e. if a user searches for 'Paris' or 'Alexandros'
Nodegoat will return the entity 'Alexander' because they are listed as
alternative names.

* **Name (transliteration):** The name of the entity as
strictly transliterated from the Greek if different from the house
style (κ = k, χ = ch, ῥ = rh, αι = ai, γγ (etc.) = ng). Multiple names
are allowed in this field; enter each in a separate box by clicking
'Add'.

* **Name (Greek Font):** The name of the entity as it
appears in Greek with polytonic accents. Multiple names are allowed in
this field; enter each in a separate box by clicking 'Add'.

* **Name (Latinized):** The name of the entity as rendered
in a Latinized transliteration from the Greek if different from the
house style. These forms are typically used in Loeb editions. Multiple
names are allowed in this field; enter each in a separate box by
clicking 'Add'.

* **Name in Latin texts:** The name as used by Latin
authors if different from the house style (e.g. Jupiter, Hercules,
Pollux). Multiple names are allowed in this field; enter each in a
separate box by clicking 'Add'.

* **Alternative names:** Any alternative spellings or
forms, or other names this entity is known by. Multiple names are
allowed in this field; enter each in a separate box by clicking 'Add'.

* **Minimal disambiguation:** These appear alongside the
name in the public interface and help users distinguish between entities
with the same or similar names. The information that you give here must
go in round brackets '()'. It should be as brief as possible. Use '&'
not 'and', '/' not 'or'. Use minimal capitalization.

For agents and collectives, add a minimal disambiguation only if the
name is identical to or likely to be confused with the name of another
agent or collective. Use either an adjective of a place they are
particularly associated with ('(Athenian)', '(Arcadian)', an
abbreviated genealogy ('(f. of Alexandros)'), or description of
prominent role ('(thunderbolt-makers)'). Distinguish further with
Roman numerals if necessary (e.g. '(Trojan I)', '(Trojan II)').

Fictional agents or collectives created by other agents should include
the word 'persona' (e.g. '(Odyssean persona)').

**Agents with '(horse)' or '(dog)' in [Minimal disambiguation] populate the filecard categories 'animal/animals belonging to', 'animals' when Of contains an agent or collective. This reversal can also be triggered using Name.**

* **Information:** This is an optional, free text field. In
the data collection interface it appears as part of the name. In the
public interface it appears on the filecard. Give the most pertinent
information about this entity to help others identify it accurately.
More information can be given in **Note** or
* **Commentary.**

* **Alternative name for:** See
2.4.1.1(#alternative-name-entities).

* **Possibly the same as:** Use where we do not have enough
information to determine whether two entities are different, and it is
possible that they are in fact the same. Only use this attribute with
one entity of the pair (a reversal will populate the other).

* **Populates filecard category 'Possibly the same as'**

* **Rationalized form of:** See
2.4.1.2(#rationalized-form-entities).

* **Personification of:** See
2.4.1.4(#personifications).

* **Of:** Used to create high-level connections between
entities which are inherent to them. If the 'of' in a collective's name
refers to their parent(s) (e.g. 'the Children of Niobe'), use
* **Children Of** instead.

* **Populates filecard category 'Related entities'**

* **Wikidata:** Enter Wikidata identifier, which is a string
of numbers beginning with "Q". Do not enter the full URL as Nodegoat
will create that from the identifier. Multiple names are allowed in this
field.

* **LIMC headword:** We are not currently collecting LIMC
data, so you do not need to enter anything in this field. (Where
entered, use the exact form as given in headings in LIMC (e.g. 'Briareos
II'); multiple names are allowed in this field.)

* **Gender:** All agents and collectives must have a gender
attribute. Use 'undefined' where (a) the gender of an agent is not
knowable; (b) the gender of an agent is fluid; (c) a collective is (or
might be) made up of both males and females.

* **Children Of:** If the collective has a parent that is
stable in the tradition, give it here: e.g. the Danaids are children of
Danaos, the Sons of Lycaon are children of Lycaon. More than one parent
can be entered.

**Populates filecard categories 'children of', 'mother/father of'. If
the collective has Entity Subtype 'collective without
members' it populates filecard category 'parent of'. If [Children
Of] contains a collective, it populates filecard category
'parents of'.**

* **Part Of** Where a collective is a sub-group of a larger
collective, enter the name of the larger collective here. So, for
example, '[the Mycenae
Contingent](https://manto.unh.edu/viewer.p/60/2616/object/6580-8190247)'
that fights at Troy is 'part of' the larger '[Greek
Contingent](https://manto.unh.edu/viewer.p/60/2616/object/6580-8190050)'.
This 'nests' (see 4.14(#nesting-entities)) collectives
inside each other.

* **Populates filecard category 'subgroups'**

### 2.4.3 Creating objects 

* **Name:** This is a required field. Follow house style
(see 3.1(#house-style)) and existing practice. Use
maximal capitalization, and 'the' where needed; e.g. 'the Bow of
Artemis'.

**Objects with 'Bones' in Name populate filecard
categories 'remains of', 'body parts' when Of is used.**

**Objects with 'Finger', 'Skin', 'Genital', 'Thigh', 'Shoulder',
'Teeth', 'Tooth' 'Blood', 'Hair', 'Head', 'Tusk', 'Horn', 'Bone of',
'Umbilical cord' in Name populate filecard categories
'body part of', 'body parts' when Of is used.**

**Objects with 'Shield', 'Scabbard', 'Sword', 'Armour', 'Bow',
'Arrow', 'Club', 'Breastplate', 'War-belt', 'Helmet', 'Quiver',
'Thunderbolt', 'Spear', 'Dagger', 'Axe', 'Trident' in
Name populate filecard categories 'weapon of',
'weaponry' when Of is used.**

The next name fields are optional. They are free text fields that aid
findability; i.e. if a user searches for 'Paris' or 'Alexandros'
Nodegoat will return the entity 'Alexander' because they are listed as
alternative names.

* **Name (transliteration):** The name of the entity as
strictly transliterated from the Greek if different from the house
style (κ = k, χ = ch, ῥ = rh, αι = ai, γγ (etc.) = ng.). Multiple
names are allowed in this field.

* **Name (Greek Font):** The name of the entity as it
appears in Greek with polytonic accents. Multiple names are allowed in
this field.

* **Name (Latinized):** The name of the entity as rendered
in a Latinized transliteration from the Greek if different from the
house style. These forms are typically used in Loeb editions.

* **Name in Latin texts:** The name as used by Latin
authors if different from the house style (e.g. Jupiter, Hercules,
Pollux). Multiple names are allowed in this field.

* **Alternative names:** Any alternative spellings, or
forms, of this entity's name. Multiple names are allowed in this
field.

* **Minimal disambiguation:** These appear alongside the
name in the public interface and help users distinguish between entities
with the same or similar names. The information that you give here must
go in round brackets '()'. It should be as brief as possible. Use '&'
not 'and', '/' not 'or'. Use minimal capitalization.

For objects, add a minimal disambiguation only if the name is
identical to or likely to be confused with the name of another object.
Use adjectives expressing either maker ('(Daidalean)') or a place it
is particularly associated with ('(Argive)').

* **Information:** This is an optional, free text field. In
the data collection interface it appears as part of the name. In the
public interface it appears on the filecard. Give the most pertinent
information about this entity to help others identify it accurately.
More information can be given in **Note** or
* **Commentary.**

* **Alternative name for:** See
2.4.1.1(#alternative-name-entities).

* **Possibly the same as:** Use where we do not have enough
information to determine whether two or more entities are different, and
it is possible that they are in fact the same. Only use this attribute
with one entity (a reversal will populate the other(s)).

* **Populates filecard category 'Possibly the same as'**

* **Rationalized form of:** See
2.4.1.2(#rationalized-form-entities).

* **Personification of:** See
2.4.1.4(#personifications).

* **Of:** Used to create high-level connections between
entities which are inherent to them. This attribute always triggers the
'related entities' reversal. Entities with specific words in
* **Name** will trigger other reversals: see above for the
list.

* **Wikidata:** Enter Wikidata identifier, which is a string
of numbers beginning with "Q". Do not enter the full URL as Nodegoat
will create that from the identifier. Multiple names are allowed in this
field.

### 2.4.4 Creating places and landmarks

* **Name:** This is a required field. Follow house style
(see 3.1(#house-style)) and existing practice. Use
maximal capitalization, and 'the' where needed; e.g. Mount Olympos, the
Atlas Mountains, the Myrtoan Sea, River Alpheios, the Springs of
Amymone, Hippocrene Spring, the Tomb of Hippolytos.

**Landmarks with 'Tomb' in Name populate filecard
categories 'buried at', 'burial place of' when Of is
used.**

**Landmarks with 'Gate', 'Wall' in Name populate
filecard categories 'fortifications of', 'fortifications' when
Of contains a place. 'In' field should also be used to
express location with these entities.**

**Places and landmarks with 'Altar', 'Temple', 'Sanctuary', 'Oracle',
'Grove' 'Cenotaph' in Name populate filecard categories
'cult site of', 'cult site' when Of is used.**

**Landmarks with 'House', 'Tent', 'Palace', 'Chamber' or 'Cave' in
Name populate filecard categories 'dwelling of',
'dwelling' when Of is used. These landmarks are nested
(see 4.14(#nesting-entities)): if a landmark that is a
dwelling is 'In' another landmark that is a dwelling, its resident(s)
will also populate the 'dwelling of' category of the landmark it is
'In'.**

The next name fields are optional. They are free text fields that aid
findability; i.e. if a user searches for 'Paris' or 'Alexandros'
Nodegoat will return the entity 'Alexander' because they are listed as
alternative names.

* **Name (transliteration):** The name of the entity as
strictly transliterated from the Greek if different from the house
style (κ = k, χ = ch, ῥ = rh, αι = ai, γγ (etc.) = ng.). Multiple
names are allowed in this field.

* **Name (Greek Font):** The name of the entity as it
appears in Greek with polytonic accents. Multiple names are allowed in
this field.

* **Name (Latinized):** The name of the entity as rendered
in a Latinized transliteration from the Greek if different from the
house style. These forms are typically used in Loeb editions.

* **Name in Latin texts:** The name as used by Latin
authors if different from the house style (e.g. Jupiter, Hercules,
Pollux). Multiple names are allowed in this field.

* **Alternative names:** Any alternative spellings, or
forms, of this entity's name. Multiple names are allowed in this
field.

* **Minimal disambiguation:** These appear alongside the
name in the public interface and help users distinguish between entities
with the same or similar names. The information that you give here must
go in round brackets '()'. It should be as brief as possible. Use '&'
not 'and', '/' not 'or'. Use minimal capitalization.

For places and landmarks always provide a disambiguator unless the
entity is very well known and not likely to be confused with another
place or landmark (e.g. 'Egypt', 'River Nile'). For islands, use
'(island(s))'; where two place names might be confused, clearly
differentiate, e.g. 'Rhodes (city)', 'Rhodes (island)'. In all other
cases, use a noun indicating the city or region the place belongs to
(e.g. 'Attica', 'Asia Minor').

* **Information:** This is an optional, free text field. In
the data collection interface it appears as part of the name. In the
public interface it appears on the filecard. Give the most pertinent
information about this entity to help others identify it accurately.
Unlocatable or fictional locations should include the word
'unlocatable'. More information can be given in the Note or Commentary
fields.

* **Alternative name for:** See
2.4.1.1(#alternative-name-entities).

* **Possibly the same as:** Use where we do not have enough
information to determine whether two or more entities are different, and
it is possible that they are in fact the same. Only use this attribute
with one entity (a reversal will populate the other(s)).

* **Populates filecard category 'possibly the same as'**

* **Rationalized form of:** See
2.4.1.2(#rationalized-form-entities).

* **Personification of:** See
2.4.1.4(#personifications).

* **Of:** Used to create high-level connections between
entities which are inherent to them. This attribute always triggers the
'related entities' reversal. Entities with specific words in
* **Name** will trigger other reversals: see above for the
list.

* **Wikidata:** Enter Wikidata identifier, which is a string
of numbers beginning with "Q". Do not enter the full URL as Nodegoat
will create that from the identifier. Multiple names are allowed in this
field.

* **Pleiades URN?**: If you have checked Pleiades and found
that there's no appropriate entry, change to 'no'.

* **Pleiades URN**: Enter Pleiades URN here. Enter just the
numbers (e.g. '579885') and Nodegoat will create a URL. For advice on
selecting the best URN, see
4.10(#choosing-a-pleiades-number). If there is
locational data (long./latt.) for this entity in Pleiades, this will be
fetched next time the Pleiades ingestion is run (see
4.17(#ingesting-locations-from-pleiades)).

* **Populates the '\location\' sub-object**

To run the Pleiades ingestion: From the Nodegoat Data environment
select Processes \Ingestion \Pleiades Location Data Run \Run
Ingestion. This process trashes all locational data in MANTO and
fetches the most recent locational data from Pleiades.

* **In:** This field establishes relations between locations
by 'nesting' one place or landmark within another (see
4.14(#nesting-entities)). All locations within cities,
islands and archipelagos (groups of islands), and within fictional
spaces (e.g. the Underworld), and all locations except cities on
mountains and in rivers should be nested inside each other using the
most granular entities available. E.g. a landmark like a tomb might be
'In' a sanctuary, which is 'In' an area of a city, which is in turn 'In'
the city itself, which is in turn 'In' an island. For real places and
landmarks, do not use locations broader than city, island, river or
mountain in this field (i.e. do not enter names of regions). If (e.g.) a
city is unlocatable but known to be in a certain region, use
* **Somewhere Near** instead.

* **Populates the '\in\' location sub-object.**

**Populates the filecard categories 'encompasses', 'in' (entities are
nested)**

**Affects reversals relating to relics, places of birth, places of
death and burial, cult sites, depictions, related entities. I.e. If
ENTITY1 is 'In' ENTITY2, entities listed in 'Relics preserved on site'
for ENTITY1 will also appear as 'Relics preserved on site' for
ENTITY2.**

* **Somewhere Near**: Only use this field if you cannot
fetch locational data via the 'Pleiades URN' field. For example, the
Pleiades URN for the Messenian town of Tricca (57356) has no locational
data, but we do know that it was in the region of Messenia, so we add
'Messenia' in this field to give it a bit more specificity. Only one
entity can be entered.

* **Populates the '\near\' location sub-object**

### 2.4.5 Creating constellations 

* **Name:** This is a required field. Follow house style
(see 3.1(#house-style)) and existing practice. Use
maximal capitalization, and 'the' where needed; e.g. 'the Crown of
Ariadne\'.

The next name fields are optional. They are free text fields that aid
findability; i.e. if a user searches for 'Paris' or 'Alexandros'
Nodegoat will return the entity 'Alexander' because they are listed as
alternative names.

* **Name (transliteration):** The name of the entity as
strictly transliterated from the Greek if different from the house
style (κ = k, χ = ch, ῥ = rh, αι = ai, γγ (etc.) = ng.). Multiple
names are allowed in this field.

* **Name (Greek Font):** The name of the entity as it
appears in Greek with polytonic accents. Multiple names are allowed in
this field.

* **Name (Latinized):** The name of the entity as rendered
in a Latinized transliteration from the Greek if different from the
house style. These forms are typically used in Loeb editions.

* **Name in Latin texts:** The name as used by Latin
authors if different from the house style (e.g. Jupiter, Hercules,
Pollux). Multiple names are allowed in this field.

* **Alternative names:** Any alternative spellings, or
forms, of this entity's name. Multiple names are allowed in this
field.

* **Minimal disambiguation:** These appear alongside the
name in the public interface and help users distinguish between entities
with the same or similar names. The information that you give here must
go in round brackets '()'. It should be as brief as possible. Use '&'
not 'and', '/' not 'or'. Use minimal capitalization.

For constellations, add a minimal disambiguation only if the name is
identical to or likely to be confused with the name of another
constellation.

* **Information:** This is an optional, free text field. In
the data collection interface it appears as part of the name. In the
public interface it appears on the filecard. Give the most pertinent
information about this entity to help others identify it accurately.
Include words like 'constellation', 'comet' or 'planet' as appropriate.
More information can be given in **Note** or
* **Commentary.**

* **Alternative name for:** See
2.4.1.1(#alternative-name-entities).

* **Possibly the same as:** Use where we do not have enough
information to determine whether two or more entities are different, and
it is possible that they are in fact the same. Only use this attribute
with one entity (a reversal will populate the other(s)).

* **Populates filecard category 'possibly the same as'**

* **Rationalized form of:** See
2.4.1.2(#rationalized-form-entities).

* **Personification of:** See
2.4.1.4(#personifications).

* **Of:** Used to create high-level connections between
entities which are inherent to them. This attribute always triggers the
'related entities' reversal.

* **Wikidata:** Enter Wikidata identifier, which is a string
of numbers beginning with "Q". Do not enter the full URL as Nodegoat
will create that from the identifier. Multiple names are allowed in this
field.

* **In:** This field establishes relations between locations
by 'nesting' one entity (see 4.14(#nesting-entities)).
Where a star (etc) is within a larger constellation which is also an
entity in MANTO, add the constellation here.

* **Populates the '\in\' location sub-object.**

**Populates the filecard categories 'encompasses', 'in' (entities are
nested)**

* **Affects reversals relating to related entities.**

### 2.4.6 Creating mythical events 

* **Name:** This is a required field. Follow house style
(see 3.1(#house-style)) and existing practice. Use
maximal capitalization, and 'the' where needed; e.g. 'the Funeral Games
of Patroclos\'.

**Events with 'Games' in Name populate filecard category
'held to honor' when Of is used**

The next name fields are optional. They are free text fields that aid
findability; i.e. if a user searches for 'Paris' or 'Alexandros'
Nodegoat will return the entity 'Alexander' because they are listed as
alternative names.

* **Name (transliteration):** The name of the entity as
strictly transliterated from the Greek if different from the house
style (κ = k, χ = ch, ῥ = rh, αι = ai, γγ (etc.) = ng.). Multiple
names are allowed in this field.

* **Name (Greek Font):** The name of the entity as it
appears in Greek with polytonic accents. Multiple names are allowed in
this field.

* **Name (Latinized):** The name of the entity as rendered
in a Latinized transliteration from the Greek if different from the
house style. These forms are typically used in Loeb editions.

* **Name in Latin texts:** The name as used by Latin
authors if different from the house style (e.g. Jupiter, Hercules,
Pollux). Multiple names are allowed in this field.

* **Alternative names:** Any alternative spellings, or
forms, of this entity's name. Multiple names are allowed in this
field.

* **Minimal disambiguation:** These appear alongside the
name in the public interface and help users distinguish between entities
with the same or similar names. The information that you give here must
go in round brackets '()'. It should be as brief as possible. Use '&'
not 'and', '/' not 'or'. Use minimal capitalization.

For mythical events, use a noun indicating the city or region where
the event took place if useful.

* **Information:** This is an optional, free text field. In
the data collection interface it appears as part of the name. In the
public interface it appears on the filecard. Give the most pertinent
information about this entity to help others identify it accurately.
More information can be given in **Note** or
* **Commentary.**

* **Alternative name for:** See
2.4.1.1(#alternative-name-entities).

* **Possibly the same as:** Use where we do not have enough
information to determine whether two or more entities are different, and
it is possible that they are in fact the same. Only use this attribute
with one entity (a reversal will populate the other(s)).

* **Populates filecard category 'possibly the same as'**

* **Of:** Used to create high-level connections between
entities which are inherent to them. This attribute always triggers the
'related entities' reversal.

* **Wikidata:** Enter Wikidata identifier, which is a string
of numbers beginning with "Q". Do not enter the full URL as Nodegoat
will create that from the identifier. Multiple names are allowed in this
field.

* **In:** Enter the location of the event if relevant.

**Populates the filecard categories 'encompasses', 'in' (events nest
within places: see 4.14(#nesting-entities))**

### 2.4.8 Creating historical artifacts

* **Name:** This is a required field. Follow house style
(see 3.1(#house-style)) and existing practice. Use
maximal capitalization, and 'the' where needed.

**Historical artifacts with 'Altar', 'Temple' in Name
populate filecard categories 'cult site of', 'cult site' when
Of is used.**

The next name fields are optional. They are free text fields that aid
findability; i.e. if a user searches for 'Paris' or 'Alexandros'
Nodegoat will return the entity 'Alexander' because they are listed as
alternative names.

* **Name (transliteration):** The name of the entity as
strictly transliterated from the Greek if different from the house
style (κ = k, χ = ch, ῥ = rh, αι = ai, γγ (etc.) = ng.). Multiple
names are allowed in this field.

* **Name (Greek Font):** The name of the entity as it
appears in Greek with polytonic accents. Multiple names are allowed in
this field.

* **Name (Latinized):** The name of the entity as rendered
in a Latinized transliteration from the Greek if different from the
house style. These forms are typically used in Loeb editions.

* **Name in Latin texts:** The name as used by Latin
authors if different from the house style (e.g. Jupiter, Hercules,
Pollux). Multiple names are allowed in this field.

* **Alternative names:** Any alternative spellings, or
forms, of this entity's name. Multiple names are allowed in this
field.

* **Minimal disambiguation:** These appear alongside the
name in the public interface and help users distinguish between entities
with the same or similar names. The information that you give here must
go in round brackets '()'. It should be as brief as possible. Use '&'
not 'and', '/' not 'or'. Use minimal capitalization.

For historical artifacts, always provide a disambiguator. Use a noun
indicating the place the artifact belongs to (e.g. 'Athens').

* **Information:** This is an optional, free text field. In
the data collection interface it appears as part of the name. In the
public interface it appears on the filecard. Give the most pertinent
information about this entity to help others identify it accurately.
More information can be given in **Note** or
* **Commentary.**

* **Possibly the same as:** Use where we do not have enough
information to determine whether two or more entities are different, and
it is possible that they are in fact the same. Only use this attribute
with one entity (a reversal will populate the other(s)).

* **Populates filecard category 'possibly the same as'**

* **Of:** Used to create high-level connections between
entities which are inherent to them. This attribute always triggers the
'related entities' reversal; entities with specific words in
* **Name** will also trigger other reversals: see above for
the list.

* **Wikidata:** Enter Wikidata identifier, which is a string
of numbers beginning with "Q". Do not enter the full URL as Nodegoat
will create that from the identifier. Multiple names are allowed in this
field.

* **Pleiades URN?**: If you have checked Pleiades and found
that there's no appropriate entry, change to 'no'.

* **Pleiades URN**: Enter Pleiades URN here. Enter just the
numbers (e.g. '579885') and Nodegoat will create a URL. For advice on
selecting the best URN, see
4.10(#choosing-a-pleiades-number). If there is
locational data (long./latt.) for this entity in Pleiades, this will be
fetched next time the Pleiades ingestion is run.

* **Populates the '\location\' sub-object**

To run the Pleiades ingestion: From the Nodegoat Data environment
select Processes \Ingestion \Pleiades Location Data Run \Run
Ingestion. This process trashes all locational data in MANTO and
fetches the most recent locational data from Pleiades.

* **In:** This field establishes relations between places by
'nesting' one place within another (see
4.14(#nesting-entities)). All historical artifacts
should be given a location within a place or landmark where possible.
Regions should not be entered here; if the artifact cannot be located
with more precision that in a certain region, use **[Somewhere
Near]** instead.

* **Populates the '\in\' location sub-object.**

**Populates the filecard categories 'encompasses', 'in' (entities are
nested) and affects reversals relating to cult sites.**

* **Somewhere Near**: Only use this field if you cannot use
* **In** (see above).

* **Populates the '\near\' location sub-object**

### 2.4.1 Creating special kinds of entities 

There are some special kinds of entities that are found in all entity
types. These instructions should be followed even where they contradict
what you read in
2.4.2-8(#creating-agents-and-collectives).

#### 2.4.1.1 Alternative name entities

Only create alternative names entities if the name is needed to create
ties about naming, eponyms, and etymologies. (In all other instances,
just add the name(s) as free text in the **[Alternative
names]** field of the main entity.)

Use the same **Entity Type** and **[Entity
Subtype]** as the main entity.

Use '(alt. \main entity name\)' in **[Minimal
Disambiguation.]**

Use 'alternative name for \main entity name\' at the beginning of
* **Information.**

Enter the main entity in **Alternative Name For**.

* **Populates filecard category 'alternative name'**

**'Alternative name' entities nest within main entity (see
4.14(#nesting-entities)); any 'related entities' of
the alternative name entity will also populate the main entity.**

These alternative name entities are just stubs that direct the user to
the main entity; do not enter anything in the rest of the fields. For
further details on the use of alternative name entities, see
4.6(#alternative-names).

#### 2.4.1.2 Rationalized form entities

Only create entities to capture rationalized forms where existing
entities cannot be used.

Use the same **Entity Type** and **[Entity
Subtype]** as the main entity.

Use '(rat. \main entity name\)' in **[Minimal
Disambiguation.]** If it is not a rationalization of a
specific entity in MANTO (e.g.
Tricarenia(https://manto.unh.edu/viewer.p/60/2616/object/6580-11296441)),
use '(rationalized)'.

Use 'rationalized form of \main entity name\' at the beginning of
* **Information.** If it is not a rationalization of a
specific entity in MANTO (e.g.
Tricarenia(https://manto.unh.edu/viewer.p/60/2616/object/6580-11296441)),
use 'rationalized' somewhere in **Information**.

Enter the main entity in **Rationalized form of** where
appropriate.

* **Populates filecard category 'rationalized form'**

Complete other fields as required for the entity type. For further
details on the use of rationalized form entities, see 4.13.

#### 2.4.1.3 Anonymous entities

If an entity is not named in the source you are working on but is named
elsewhere, then use that name and record your decision in
* **Note]** or **[Commentary.** If an entity is
never given a name in our ancient sources, you must:

Create a **Name** that describes the entity: e.g.
'[Mother of
Areion](https://manto.unh.edu/viewer.p/60/2616/object/6580-11289354)'
(note: maximum capitalization, no 'the').

Use '(name unknown)' in **Minimal Disambiguation.**

Complete other fields as required for the entity type.

#### 2.4.1.4 Personifications

See 4.8(#personifications-1) for information on
personifications.

For personifications of abstract concepts, use the Greek form (e.g.
'Eros') in **Name** and add English translation(s) (e.g.
'Love', 'Desire') as free text in **Alternative Names**.

For personifications of abstract concepts, include 'personification of
\English translation\]' in **[Information**; for
personifications of rivers, include 'river god' in
* **Information**.

Where this entity is the personification of another entity in MANTO
(e.g. the river god Acheloos is the personification of River
Acheloos), enter the main entity in **[Personification
Of]**.

* **Populates filecard category 'Personification'**

Complete other fields as required for the entity type.
