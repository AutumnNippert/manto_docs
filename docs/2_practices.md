
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
Nodegoat. * **Entity Type** affects which reversals will be
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

Use * **Note, Commentary,** and **[Attention
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
More information can be given in * **Note** or
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
More information can be given in * **Note** or
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
More information can be given in * **Note** or
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
More information can be given in * **Note** or
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
More information can be given in * **Note** or
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

Use the same * **Entity Type** and **[Entity
Subtype]** as the main entity.

Use '(alt. \main entity name\)' in **[Minimal
Disambiguation.]**

Use 'alternative name for \main entity name\' at the beginning of
* **Information.**

Enter the main entity in * **Alternative Name For**.

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

Use the same * **Entity Type** and **[Entity
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
use 'rationalized' somewhere in * **Information**.

Enter the main entity in * **Rationalized form of** where
appropriate.

* **Populates filecard category 'rationalized form'**

Complete other fields as required for the entity type. For further
details on the use of rationalized form entities, see 4.13.

#### 2.4.1.3 Anonymous entities

If an entity is not named in the source you are working on but is named
elsewhere, then use that name and record your decision in
* **Note]** or * **[Commentary.** If an entity is
never given a name in our ancient sources, you must:

Create a * **Name** that describes the entity: e.g.
'[Mother of
Areion](https://manto.unh.edu/viewer.p/60/2616/object/6580-11289354)'
(note: maximum capitalization, no 'the').

Use '(name unknown)' in * **Minimal Disambiguation.**

Complete other fields as required for the entity type.

#### 2.4.1.4 Personifications

See 4.8(#personifications-1) for information on
personifications.

For personifications of abstract concepts, use the Greek form (e.g.
'Eros') in * **Name** and add English translation(s) (e.g.
'Love', 'Desire') as free text in * **Alternative Names**.

For personifications of abstract concepts, include 'personification of
\English translation\]' in * **[Information**; for
personifications of rivers, include 'river god' in
* **Information**.

Where this entity is the personification of another entity in MANTO
(e.g. the river god Acheloos is the personification of River
Acheloos), enter the main entity in **[Personification
Of]**.

* **Populates filecard category 'Personification'**

Complete other fields as required for the entity type.

## 2.5 Ties: the basics

Ties take the form of grammatically-standardized sentences. We don't use
them to retell the myth, but to assert connections between entities.

Our data collection process allows for a lot of flexibility and
creativity. That said, we must impose constraints on ourselves if we are
to produce high-quality, useful data that is machine-readable. So,
although our ties are based on the structures of human language, we
create them according to set rules. Don't just rely on the norms of
English grammar!

Data collection for MANTO often requires a bit of lateral thinking and
often checking what has already been done. Here are some key principles
to keep in mind:

### 2.5.1 Comprehensiveness

When you create a tie, you are capturing the fact that all the entities
in the tie appear in the passage (even if unnamed or implicit), and that
there is some kind of connection between them. (These connections are
collected by the 'appears in', 'mentioned in text' and 'related
entities' reversals.)

It is crucial that you make sure you have captured every entity that
appears in a text at least once (see
4.2(#repeating-ties)). You must also make sure that you
have captured some kind of relationship between entities that are
connected somehow in the source. This means that you will want to make
your ties as rich as possible and use prepositions, genitive absolutes,
and purpose clauses to connect together as many entities as you can.

You will often have several options about how you construct your ties.
As a general rule, you should try to put the entities that are most
important in that episode in the first few fields, i.e. in the semantic
triple (subject, direct object, indirect object) and the prepositional
phrases (especially 'in').

### 2.5.2 Specificity

Always consider what the data you are collecting will look like when it
finally appears on the filecards. You should aim to trigger reversals
that will populate all filecard categories and phenomena that are
relevant to that passage. As you become more familiar with the
interactions described below (see
2.8.1-21(#interactions)) you will notice that several
different ties can all be used to trigger the same reversal. This means
that there are often several different ways to create the same end
result. In general, creating fewer ties is better since this makes
checking and revising data easier.

Because you are always trying to trigger reversals with your ties, you
should use ties that don't trigger more specific reversals (like 'is
associated with' or 'is mentioned') only where there are no other
options.

### 2.5.3 Hierarchies

The only exception to the principle of trying to trigger as many
reversals as possible is where actions exist in a kind of 'hierarchy'.
These are clearly identified in the usage notes for interactions in
2.8.1-21(#interactions). So, for example, even though
the interaction 'wounds' does trigger reversals (i.e. 'wounds', 'wounded
by' etc) you should not use it if you can use 'blinds' or 'kills'
instead, because those are more specific and significant actions. This
principle is most apparent when you are capturing data from descriptions
of fights between two heroes: Don't be tempted to try to retell the
narrative using lots of ties; just follow the instructions in
2.8.1-21(#interactions) and capture the most significant
actions.

Because we focus on the most significant actions in myth, MANTO's
dataset does not comprehensively capture all instances of an action even
when we have a tie that seems to describe it. For example, searching for
ties that use 'wounds' will not return all instances of wounding in
Greek myth, because if the wounding involved blinding it would have been
captured using 'blinds', and if the wounded person was later killed by
the attacker, it would have been captured by 'kills'.

### 2.5.3 Consistency

MANTO's 'grammar' is designed to be multi-purpose: it should work well
with many different ancient sources. Because of this, it imposes a kind
of uniformity on the tradition which emphasizes in particular the
outcomes of interactions, and specific kinds of relationships.

This grammar is not designed to capture the styles and concerns of
specific ancient storytellers. In trying to retrieve just the 'facts' of
myth, it tends to smooth out narratological differences. This
information is not lost, since users of MANTO can always access the
ancient versions themselves, but it is not going to appear in the data.
In particular, our methodology is not well suited to expressing the
internal lives of mythic characters, actions contemplated but not
carried out, or ethical judgements added by the storyteller.

Consistency is crucial across such a large project and makes checking
and revising ties much easier. We will frequently encounter the same
episodes in different passages and texts. If you are capturing a story
that has already been captured, try to copy how it was captured
previously if that makes sense in the passage you are working
on---though doubtlessly you will find that some elements may be missing
or altered, while others will need to be added. But keeping a consistent
'kernel' in terms of structure will go a long way in keeping the
structured data clean.

## 2.7 Creating a Tie

All fields are optional except * **Passage** and
* **Predicate.**

You can place any type of entity in any field. 

### 2.7.1 The Semantic Triple

 The basic fields of the tie are as follows: 

 

* **Source: Passage:** Only one passage is allowed in this
field. This is a required field. 

**Populates filecard categories 'appears in', 'mentioned in',
'mentions'**

 

* **Subject:** Multiple entities are allowed in this
field. If you don't know who carried out a particular action, you can
leave this field blank. This is a little like constructing a passive
sentence; e.g. '\BLANK\ buries AGENT at PLACE' means 'AGENT is
buried at PLACE'. Only 'passive' uses that are not obvious are noted
in usage notes.

* **Predicate:** Only one Interaction is allowed in this
field. This is a required field. 

* **Direct Object:** Multiple entities are allowed in this
field. Use where the chosen interaction does not require a
preposition. 

* **Indirect Object (to/for):** Multiple entities are
allowed in this field. Use where the chosen interaction takes an
indirect object (see usage notes in
2.8(#interactions)).

### 2.7.2 Prepositional Phrases

Usually, you should use whichever preposition makes a comprehensible
sentence, but check usage notes for your chosen interaction in
2.8(#interactions). Multiple entities are allowed in
each field. 

* **In/on/at:** Use to express where an action happens, or
at which event.

* **Near:** Use to express physical proximity. Use only if
'in/on/at' is not an option since 'near' is both less specific, and
involved in many fewer reversals.

* **From:** Use as instructed in usage notes for
interactions or to express motion away from.

* **To:** Use as instructed in usage notes for
interactions or to express motion towards. Note particularly which
interactions use * **To** and which use **[Indirect Object
(to/for)]**.

* **Via:** Use as instructed in usage notes for
interactions or to capture waypoints on a journey. A tie expressing an
itinerary should be made as rich as possible using
* **Via** to connect stopping points. Capture locations in
the same order as they are visited in the itinerary being described.

* **While intending to go to:** Use where an entity is
described as intending to make a journey, but only completes part of
the itinerary.

* **Using:** Use to capture the instrument used in an
interaction. Often this would be more commonly expressed in English
using 'with' (e.g. 'Heracles kills the Hydra with his
bow').

**Where entity in Using is an object, populates filecard
categories 'used by', 'used at'.**

* **Of:** Use as instructed in usage notes for
interactions, or where it makes grammatical sense and no other
preposition could be used.

* **For:** Use as instructed in usage notes for
interactions , or where it makes grammatical sense and no other
preposition could be used. In the context of giving, can mean 'in
exchange for'. Note particularly which interactions use
* **For** and which use **[Indirect Object
(to/for).]**

* **Into:** Use only with interactions expressing
transformations, as noted in the interactions. Do not use to express
motion towards.

* **Against:** Use as instructed in usage notes for
interactions, or where it makes grammatical sense and no other
preposition could be used.

* **Concerning:** Use as instructed in usage notes for
interactions, or where it makes grammatical sense and no other
preposition could be used.

### 2.7.3 Genitive absolutes

Multiple * **Entities** are allowed in each field. Usually,
you should use whichever phrase makes a comprehensible sentence, but
check usage notes for your chosen interaction in
2.8(#interactions).

* **With the aid of:** Use in instances where an entity
(often a god(dess)) helps generally but does not actually partake in
an interaction.

* **At the command of:** Use to express where an action is
ordered or requested by a third party.

* **At the instigation of:** Use to express where an
action is instigated by a third party out of hostility, malice, or a
desire for revenge.

* **With the involvement of:** Use when an entity is
involved in the action but cannot be connected to it in any other way.
Use this field to capture where a city is responsible for the fact
that there is (e.g.) a votive depicting a hero in another place (e.g.
at Delphi or Olympia).

* **In accordance with a prophecy from:** Use to express
the source of a prophecy, which may be the god or a mortal prophet, or
both. Where the prophecy is from Delphi, use 'the Oracle at Delphi'
and do not add (e.g.) 'Apollo', 'Pythia'. Use whether or
not the prophecy is obeyed/understood and regardless of the type of
prophecy (i.e. oracle, dream, bird signs). See
4.3(#prophecies-at-delphi).

* **In accordance with a prophecy about:** Use to express
the subject of a prophecy. Use whether or not the prophecy is
obeyed/understood and regardless of the type of prophecy (i.e. oracle,
dream, bird signs). See 4.3(#prophecies-at-delphi).

### 2.7.4 Purpose Clauses

Multiple * **Entities** are allowed in each field. Usually,
you should use whichever phrase makes a comprehensible sentence, but
check usage notes for your chosen interaction in
2.8(#interactions).

* **To avenge:** Use when the subject undertakes an action
specifically to avenge the death or (perceived) mistreatment of a
third party.

* **To aid:** Use when the subject undertakes an action
specifically to aid a third party.

* **To obtain:** Use when the subject undertakes an action
specifically to obtain an entity.

* **To protect:** Use when the subject undertakes an
action specifically to protect a third party.

* **To honor:** Use when the subject undertakes an action
specifically to honor a third party.

* **To thwart:** Use when the subject undertakes an action
specifically to hinder or defeat the plans of another entity.

* **To punish:** Use when the subject undertakes an action
specifically to punish a third party.

* **And they conceive:** Use with ties expressing sexual
intercourse.

### 2.7.5 Timemarks

For advice on time in MANTO, see
4.9(#modeling-time-in-manto). Timemarks are not
currently visible in the public interface.

The next fields allow us to capture information about when in the
historical period a relic existed, or was moved, or a mythical agent was
claimed as an ancestor or appeared in an epiphany.

If you do not add a timemark to the ties 'is a relic', 'is moved',
'claims as ancestor' 'appears as in an epiphany', it is assumed that the
time when these things happened is the same as the time the source text
was written.

Only objects of the type 'time period' can be used in these fields.
* **These do not populate the reversal 'Related entities'.**

* **Timemark: when:** Select the option that best fits the
situation. Options are: 'during', 'until', 'from the time of',
'sometime before', 'sometime after'.

* **Timemark: historical event:** Must use an object of
the type 'Time Period' (see
2.7.5.1(#creating-historical-events)). Do not create
new historical events without consulting Greta and/or Scott. Multiple
entities are allowed in this field; if you are not sure when an event
took place, add any periods that are possible or use 'Historical
Events of Uncertain Date'. Entering more than one entity in this field
means either the event spans several periods, or it cannot be more
precisely dated.

Our sources are often vague about when these kinds of events took place.
Equally, MANTO's system of timemarks cannot express every kind of
temporal situation precisely. Where necessary, use
* **Commentary** to provide further information.

#### 2.7.5.1 Creating historical events 

* **Name:** This is a required field. Follow house style
(see 3.1(#house-style)) and existing practice. Use
maximal capitalization. Add dates in brackets: e.g. "(ca. 306-610
CE)".

* **ChronOntology URI:** chose the most appropriate entity
from the dataset.

### 2.7.6 Tags

We also capture some basic information about the context of the mythic
data.

* **Data Uncertain:** Default is 'no'. Select 'yes' if you
cannot be sure that the data in the tie is correct because there is
some kind of uncertainty with the source material. This may be because
a scene allows several different interpretations, there are problems
with textual transmission, or the author is unclear or allusive on a
particular point. Where necessary, create separate ties to capture all
possibilities. Explain the uncertainty in * **Note** or
* **Commentary**.

* **Doubt or disbelief expressed:** Default is 'no'.
Select 'yes' if the author or artist explicitly expresses doubt about
a narrative tradition or explicitly argues that it is untrustworthy.
If the author also describes alternatives, use **[Alternatives
given]** as well. Explain the doubt or disbelief in
* **Note]** or * **[Commentary**.

* **Alternatives given:** Default is 'no'. Select 'yes' if
the passage (or another one nearby) gives information that contradicts
the information given in the tie and so it is clear that the author or
artist is intending to give variant traditions. Each alternative
should be captured in a separate tie and tagged with **[Alternatives
given]**. Any alternatives that the author or artist
expresses doubt about should be tagged with **[Doubt or disbelief
expressed]** as well. Where the passage chosen does not
encompass the alternative version, or the discrepancy is not obvious,
explain it in * **Commentary.**

* **Data implicit:** Default is 'no'. Select 'yes' if the
information in the tie is not explicitly stated, but you have
logically deduced it from context, or perhaps supplied it from a
well-known and conventional aspect of the mythical tradition. See
examples in 4.18(#when-to-tag-implicit-data). Explain
your decision in * **Note** or
* **Commentary**.

* **Textual source:** Multiple passages are allowed. Use
where an author explicitly attributes information to another text.
Identify the specific passage or fragment where possible. If the
passage is already in MANTO, re-use that passage and follow the format
of the existing tie if possible.

* **Populates filecard category 'mentions'**

* **Local tradition at:** Multiple entities are allowed.
Use where an author explicitly attributes information to local
populations. Do not use where the attribution is non-specific (e.g.
'they say' or 'it is said'). The entity should be a place: i.e. if
information is attributed to 'the Athenians', use 'Athens'.

* **Inscription at:** Multiple entities are allowed. Use
where an author explicitly attributes information to an inscription.
The entity should be a place, landmark, or object, i.e. the location
of the inscription.

* **Depicted at:** Multiple entities are allowed. Use
where the source explicitly describes a visual depiction (whether the
thing or place it is depicted on is real or fictional, historical or
mythical).

* **Populates filecard categories 'has depictions of', 'depictions'.**

## 2.8 Interactions

Restrictions on the use of each interaction appear in notes next to
them. Unless otherwise specified, any entity can be used with any
interaction. The prepositions typically used with each one are given in
square brackets, but these are not an exhaustive list.

Many interactions trigger reversals when used in particular ways. If the
reversal is not accurate in this context, then do not use that
interaction in that way. (For an explanation of reversals, see
1.5(#reversals-and-filecards).)

### 2.8.1 Qualities 

* **ENTITY has hybrid form**

Use where an entity is explicitly said to be a mixture or blending of
two or more species, e.g. the Centaurs, the Minotaur, Pegasos. Use
where an entity is both hybrid and monstrous. Use also to capture
passages where the hybridity of traditionally hybrid creatures is
explicitly denied and tag with 'Doubt or disbelief expressed'.

* **Triggers phenomenon 'monstrosity and hybridity'**

* **ENTITY has monstrous form**

Use where an entity is explicitly said to have some unconventional
physical characteristic, excluding hybridity, e.g. unusual size,
single eye (Polyphemos), extra limbs (Hundred-handers). If the
monstrosity is accompanied by some aspect of hybridity, use 'has
hybrid form' instead. Use also to capture passages where the
monstrosity of traditionally monstrous creatures is explicitly denied
and tag with 'Doubt or disbelief expressed'.

* **Triggers phenomenon 'monstrosity and hybridity'**

### 2.8.2 Blood relationships

Ties using these interactions typically only involve agents and
collectives.

Blood relationships are exceptions to the usual rule that we try to make
each tie as rich as possible. Do not add prepositions, genitive
absolutes or purpose clauses to these interactions. If an episode of
childbirth is described, use 'is born', or 'gives birth' as well.

* **ENTITY1 is child of ENTITY2**

If ENTITY1 is a collective that already has Children of:
ENTITY2 as an attribute, do not enter that information again in this
tie.

**Populates filecard categories 'son/daughter/child of', 'children
of', 'mother/father of', 'parents of', 'has children with'**

* **ENTITY is sibling of ENTITY**

Use only where you cannot use 'is child of', with the name(s) of the
parent(s) implied.

* **ENTITY is twin of ENTITY**

* **Populates filecard categories 'twin of'**

* **Triggers phenomenon 'mythic twins'**

* **ENTITY1 is mother by parthenogenesis of ENTITY2**

Use where a mother conceives her offspring on her own. Do not use if
the father is simply unknown.\
**Populates filecard categories 'son/daughter/child of', 'mother of',
'gives birth by parthenogenesis to'**

* **Triggers phenomenon 'parthenogenesis', 'unusual births'**

* **ENTITY has no children**

Use only where an agent is explicitly said to have died childless

* **ENTITY is a descendant of ENTITY**

Use only where the exact relationship between two agents is not
apparent and cannot be extrapolated from data elsewhere (even by the
creation of anonymous figures). These relationships are difficult to
code accurately so might not be able to be included in visualizations.
For descendants in historical period, use \'is claimed as ancestor\'.

* **Populates filecard category 'descendant of'**

* **ENTITY1 is claimed as ancestor** \in/on/at ENTITY2\

Use only where the person or group making the claim exists in the
historical period. Do not use where an historical figure (e.g.
Alexander the Great) claims to have a god for a parent. Use with a
timemark; if the timemark is left empty, the claim to ancestry was
being made at the time when the passage was written.

### 2.8.3 Relationships by marriage

* **ENTITY1 is spouse of ENTITY2**

If a more detailed episode is described, use 'marries' or 'gives in
marriage'.

* **Populates filecard category 'wife/husband of'**

* **ENTITY1 marries ENTITY2**

* **Populates filecard category 'wife/husband of'**

* **ENTITY1 gives in marriage ENTITY2** \indir. obj. ENTITY3\

* **Populates filecard category 'wife/husband of'**

* **ENTITY1 offers in marriage ENTITY2** \indir. obj. ENTITY3\

Use where a marriage did not take place, or to capture (e.g.) the
place the marriage arrangement was made. If the marriage takes place
later, use 'marries' or 'is spouse of' as well.


### 2.8.4 Birth

Use only if childbirth episode is described, or other entities need to
be captured in relation to it. Otherwise use one of the 'blood
relationships' interactions in 2.14.2.

* **ENTITY1 is born** \in/on/at ENTITY2\] \[from ENTITY3\ \[with
involvement of ENTITY4\]

Use where location of birth is significant, or episode of birth is
significant and mother is not identified (if she needs to be captured,
use 'gives birth'). ENTITY3 will be something which does not typically
give birth (e.g. 'the Head of Medousa', 'the Eggs of Leda'). ENTITY4
is an agent that causes ENTITY1 to be born by (e.g.) scattering
dragon's teeth.

**Populates filecard categories 'born at', 'born from', 'place of
birth of', 'from which is created'.**

* **Triggers phenomenon 'unusual births' if 'from' is used**

* **ENTITY1 gives birth** \indir.obj. ENTITY2\] \[in/on/at ENTITY3\

This tie does not trigger genealogical reversals; use 'is child of'
(etc) as well.

* **Populates filecard categories 'born at', 'place of birth of'**

* **ENTITY1 is born by autochthony** \in/on/at ENTITY2\

Autochthons are agents and collectives who are born out of the earth
without the involvement of parents. Capture only explicit instances of
autochthony. Do not capture these as children of Ge / Gaia. ENTITY2
should typically be a region or city. If the birth is from an object
(etc) use 'is born \from\'.

* **Populates filecard category 'born at', 'place of birth of'**

* **Triggers phenomenon 'autochthons', 'unusual births'**

* **ENTITY1 comes into being**

Use where an entity spontaneously comes into existence, e.g. Gaia,
Chaos etc in Hesiod's *Theogony*. Use 'is born by autochthony' if the
entity is born from the earth in a place.\
**Triggers phenomenon 'comes into being at the beginning of the
world', 'unusual births'**

### 2.8.5 Death

* **ENTITY1 kills ENTITY2** \using ENTITY3\

**Populates filecard category 'dies at', 'place of death of', 'killed
by', 'kills',**

**If 'using' contains an object or landmark, populates 'killed by' and
'used to kill'**

* **ENTITY dies**

Use only when more specific ties (e.g. 'kills\' or \'dies by suicide\')
are not appropriate.

* **Populates filecard category 'dies at', 'place of death of'**

* **ENTITY dies by suicide**

* **Populates filecard category 'dies at', 'place of death of'**

* **If 'using' contains an object or landmark, populates 'used to kill'**

* **Triggers phenomenon 'deaths by suicide'**

* **ENTITY disappears**

Use when an agent disappears rather than dies.

* **Populates filecard category ' disappears at'**

* **Triggers phenomenon 'disappearing heroes'**

* **ENTITY mourns ENTITY**

* **ENTITY resurrects ENTITY**

Use where one agent returns another to life. Where the resurrection
involves an agent bringing another formerly-living agent back from the
Underworld, use 'ENTITY takes ENTITY from THE UNDERWORLD').

* **Populates filecard category 'resurrected at', 'resurrected by'**

* **Triggers phenomenon 'resurrected heroes'**

* **ENTITY has post-mortem existence** \in/on/at\

Use where an agent is described as existing after death in some form
(e.g. on the Isles of the Blessed) or appears as a ghost in the
terrestrial realm.

* **Populates filecard category 'has post-mortem existence at'**

* **Triggers phenomenon**

* **ENTITY1 buries ENTITY2** \in/on/at ENTITY3\

Use only where an agent disposes of a body after death. Use even when
the body is not literally buried but (e.g.) placed on a funeral pyre.
Use 'hides' where an object is buried in earth for safekeeping, etc.
ENTITY3 should be a place or landmark (e.g. 'the Tomb of Achilles').
Where the tomb is a relic in historical period, use also 'is a relic'.

**Populates filecard categories 'buried at', 'buried by', 'burial
place of'**

* **ENTITY recovers the body of ENTITY** \from\] \[to\

* **ENTITY has cenotaph** \in/on/at\

Use in the form \'AGENT has cenotaph at PLACE\' (* **not**
\'PLACE has cenotaph of AGENT\'). Use where tomb is specifically said
not to include a body; where a body is present, use 'buries' above.
Where the cenotaph is a relic in historical period, use also 'is a
relic'.

* **Populates filecard categories 'cult sites', 'cult site of'**

### 2.8.6 Roles and non-familial relationships 

Most of the interactions in this category have similar interactions in
other categories (e.g. 'is prophet' / 'gives prophecy' etc.) We use the
interactions listed in this category where the role is considered
integral to an entity's identity, or the entity is described primarily
in terms of the role but not described as necessarily performing the
action. Typically these ties populate filecard categories, whereas the
other ties do not.

* **ENTITY1 is slave** \of ENTITY2\

Use where the agent's primary identity is as slave of another; \'sells
as slave\' also exists to capture the specific action, especially
where the state of slavery is not permanent. 'Wins as warprize' also
exists. See 2.8.12(#capturing-enslaving-imprisoning).\
* **Populates filecard category 'enslaved to'**

* **ENTITY is charioteer** \of\\
* **Populates filecard category 'charioteer of'**

* **ENTITY1 is herald** \of ENTITY2\] \[in/on/at\\
* **Populates filecard categories 'herald of', 'herald at'**

**If ENTITY2 is a collective, populates filecard categories 'includes',
'belongs to'**

* **ENTITY1 is helmsman** \of ENTITY2\\
* **Populates filecard category 'helmsman of'**

**If ENTITY2 is a collective, populates filecard categories 'includes',
'belongs to'**

* **ENTITY is lawgiver** \in/on/at ENTITY\\
* **Populates filecard categories 'lawgiver at'**

* **ENTITY1 is healer** \of ENTITY2\

Use \'heals\' to capture the specific action.\
* **Populates filecard categories 'healer of'**

**If ENTITY2 is a collective, populates filecard categories 'includes',
'belongs to'**

* **ENTITY1 is nurse** \of ENTITY2\

Use where an infant is cared for by someone who is not the parent
('nurses' also exists to capture the specific action).\
* **Populates filecard category 'nurse of'**

* **ENTITY1 is teacher** \of\

Use \'teaches\' to capture the specific action\
* **Populates filecard category 'teacher of'**

* **ENTITY1 is priest** \of ENTITY2\] \[in/on/at ENTITY3\

ENTITY2 should be the divinity ENTITY2 is priest of; ENTITY3 should be
temple or sanctuary. For more specific ritual interactions, see
2.8.15(#ritual-interactions).

**Populates filecard categories 'priest/priestess of', 'priest/priestess
at'**

* **ENTITY is divine patron** \of\

Use where a god or goddess has a particularly close relationship with
a hero or place.\
* **Populates filecard category 'divine patron of'**

* **ENTITY1 is prophet** \of ENTITY2\] \[in/on/at\

ENTITY2 should be the agent or collective to whom ENTITY2 gives
prophecies, and/or the deity that the prophecies come from. Where an
agent is prophet of Apollo at Delphi, put 'Apollo' in 'of' field, and
'the Oracle of Apollo (Delphi)' in 'in/on/at' field. \'Gives
prophecy\' and 'grants power of prophecy' also exist (see
2.8.15(#ritual-interactions)).

* **Populates filecard categories 'prophet of', 'prophet at'**

**If ENTITY2 is a collective, populates filecard categories 'includes',
'belongs to'**

### 2.8.7 Names and Transformation 

* **ENTITY is eponym of ENTITY**

An eponym is the hero(ine) after whom a place is named. Where eponym
is also founder or ruler, use 'founds as eponym' or 'rules as eponym'.

* **Populates filecard categories 'eponym of', 'eponym'**

* **ENTITY1 derives etymology** \from ENTITY2\

Use where etymology is not a simple case of eponymy. ENTITY2 should
have significance for the etymology even if that significance is not
immediately clear from the names. Explain the connection in
* **Commentary** where necessary.

* **Populates filecard category 'derives etymology from'**

* **ENTITY1 names ENTITY2** \to honor ENTITY3\

Use where ENTITY2 has no previous name, e.g. the first naming of
cities. ENTITY3 is what ENTITY2 is named after. If ENTITY2 has an
eponym or etymology, capture that in a separate tie as well.

* **Populates filecard category 'named by'**

* **ENTITY1 changes name to ENTITY2** \to honor ENTITY3\

Use where ENTITY1's name changes, but there you cannot capture an
entity that does the renaming. (Where ENTITY1 is given a new name by
someone else, use 'changes name of'.) ENTITY3 is what ENTITY2 is named
after. Where the name change happens during deification, use \'becomes
immortal\' instead. If ENTITY2 has an eponym or etymology capture that
in a separate tie as well. This interaction does not
populate the filecard categories 'alternative name' and 'alternative
name for'.

* **ENTITY1 changes name of ENTITY2** \ind.obj. ENTITY3\ \[to honor
ENTITY4\]

Use where ENTITY1 changes the name of ENTITY2, which already has a
name. ENTITY4 is what ENTITY3 is named after. Where the name change
happens during deification, use \'becomes immortal\' instead. If
ENTITY3 has an eponym or etymology capture in a separate tie as well.
This interaction does not populate the filecard
categories 'alternative name' and 'alternative name for'.

* **Populates filecard category 'named by'**

* **ENTITY1 is alternative name for ENTITY2**

Use where it is specifically asserted that two names refer to the same
entity, or where the usage in the passage suggests this connection. If
one of the entities is an 'alternative name' entity (see
2.4.1.1(#alternative-name-entities)), make that one
ENTITY1. Where the alternative name is used specifically in a
particular place, use the 'local tradition at' field. This interaction
does not populate the filecard categories 'alternative
name' and 'alternative name for'.

* **ENTITY1 metamorphoses ENTITY2** \into ENTITY3\

ENTITY2 undergoes metamorphosis; ENTITY1 (usually a god) directly
instigates the process. Capture ENTITY3 only where it exists as an
entity in MANTO. This tie will always have a direct object: where an
agent metamorphoses themselves or the instigator of the metamorphosis
is not identified, use 'is metamorphosed'. Any actions done by ENTITY2
in metamorphosed form should be captured against the original identity
if the metamorphosis is later reversed.

* **Populates filecard categories 'transformed into', 'transformed from'**

* **Triggers phenomenon 'metamorphosis'**

* **ENTITY1 is metamorphosed** \into ENTITY2\

ENTITY1 undergoes metamorphosis. Capture ENTITY2 only where it exists
as an entity in MANTO. This tie should be used where an agent
metamorphoses themselves or the instigator of the metamorphosis is not
identified. Where a direct instigator is identified, use 'is
metamorphosed'. Any actions done by ENTITY1 in metamorphosed form
should be captured against the original identity if the metamorphosis
is later reversed.

* **Populates filecard categories 'transformed into', 'transformed from'**

* **Triggers phenomenon 'metamorphosis'**

* **ENTITY1 makes immortal ENTITY2** \into ENTITY3\

ENTITY2 is made immortal; ENTITY1 directly instigates the process.
Capture ENTITY3 only where it exists as an entity in MANTO. If no
instigator is identified, use 'becomes immortal'

* **Populates filecard categories 'transformed into', 'transformed from'**

* **Triggers phenomenon 'mortals who become gods'**

* **ENTITY1 becomes immortal ENTITY2**

ENTITY1 is made immortal. Capture ENTITY3 only where it exists as an
entity in MANTO. If an instigator of the process is identified, use
'makes immortal'.

* **Populates filecard categories 'transformed into', 'transformed from'**

* **Triggers phenomenon 'mortals who become gods'**

* **ENTITY1 takes form of ENTITY2**

Use where ENTITY1 (typically a god) temporarily takes on the form of
another entity. Actions performed by that entity when in disguise
should be captured against ENTITY1.

* **ENTITY1 invents ENTITY2**

Use where ENTITY1 creates ENTITY2 as a fictional persona either to
serve as an alias, or to be used in made-up stories. Where ENTITY1
creates a physical person (e.g. Pandora), use 'creates'.

* **Populates filecard categories 'invents', 'created by'**

### 2.8.8 Friendly interactions

* **ENTITY helps ENTITY**

Use only if action is not captured by a more specific interaction.

* **ENTITY requests help** \from\

Use also to capture supplication and prayer.

* **ENTITY heals ENTITY**

'Is healer of' also exists. 'heals' does not populate
filecard category 'healer of'.

* **ENTITY purifies ENTITY**

Purification is a ritual act used to relieve guilt, an affliction, or
a curse. For medical treatment, use 'heals'.

* **ENTITY bathes**

Use to capture one entity bathing another (i.e. ENTITY1 bathes
ENTITY2), an entity bathing (ENTITY1 bathes in/on/at ENTITY2) or
someone being bathed by an unknown entity (\BLANK\ bathes ENTITY1).

* **ENTITY raises ENTITY**

Use where a child or adolescent is raised, especially by a
step-parent. For raising of the dead, use 'resurrects'. 'Nurses' and
'is nurse of' exists for relationships to infants.

* **ENTITY nurses ENTITY**

Use where an infant is fed. 'Is nurse of' also exists. 'Nurses' [does
not] populate filecard category 'nurse of').

* **ENTITY teaches ENTITY**

'Is teacher of' also exists. 'Teaches' does not populate
filecard category 'teacher of')

* **ENTITY hosts ENTITY**

Use only if action is not captured by a more specific interaction.

* **ENTITY visits ENTITY**

Use only if action is not captured by a more specific interaction.

* **ENTITY protects ENTITY** \from\

Use only if action is not captured by a more specific interaction.

### 2.8.9 Hostile Interactions

* **ENTITY hinders ENTITY**

Use only if action is not captured by a more specific interaction.

* **ENTITY mistreats ENTITY** \using\

Use only if action is not captured by a more specific interaction.

**If 'using' contains an object or landmark, populates filecard category
'used to harm'**

* **ENTITY deceives ENTITY**

Use only if action is not captured by a more specific interaction.

* **ENTITY plots against ENTITY**

Use only if 'at the instigation of' or 'to punish' are not appropriate.

* **ENTITY pursues ENTITY** \from\] \to\ \[via\

* **ENTITY hunts ENTITY**

Use only in instances of hunting an animal. \'Pursues\' also exists.

* **ENTITY punishes ENTITY** \in/on/at\] \[using\

**If 'using' contains an object or landmark, populates filecard category
'used to harm'**

**If 'in/on/at' contains 'the Underworld' or 'Tartaros', populates
filecard category 'has post-mortem existence at'**

* **~~Triggers phenomenon 'people punished in the underworld'~~**

* **ENTITY curses ENTITY**

Use where \'punishes\' is not appropriate.

* **ENTITY abandons ENTITY**

Use also in instances of abandonment or divorce of a spouse. For
throwing away an object, use 'discards'.

* **ENTITY exposes ENTITY**

Use only where a child is left out to die.

* **Triggers phenomenon 'children exposed'**

* **ENTITY drives insane ENTITY**

* **ENTITY tests ENTITY**

Use only if action is not captured by a more specific interaction.

### 2.8.10 Physical Altercations

Where action occurs in the context of competition, use interactions
listed under 2.8.11(#competitions); see also
interactions in
2.8.12(#capturing-enslaving-imprisoning).

Verbal altercations are listed under
2.8.14(#conversations).

For advice on collecting data related to fights, see
2.5.3(#hierarchies).

* **ENTITY fights ENTITY**

Use only in the context of physical fights. Use only if \'kills\',
\'wounds\', 'captures' are not appropriate. For places, use 'attacks'
instead.

* **ENTITY1 wounds ENTITY2** \using ENTITY3\

If ENTITY2 is subsequently killed by ENTITY1, use 'kills' instead. Use
only if 'blinds' is not appropriate. ENTITY3 is typically a weapon
that exists as an entity in the dataset.

* **Populates filecard category 'wounded by' (both subject and 'using')**

**If 'using' contains an object or landmark, populates filecard category
'used to harm'**

* **ENTITY1 defeats ENTITY2** \using ENTITY3\

Use where ENTITY1 wins, but ENTITY2 is not killed. ENTITY3 is
typically a weapon that exists as an entity in the dataset. Use only
if 'wounds' or 'captures' is not appropriate. For places, use
'conquers', or 'destroys' instead.

* **ENTITY1 blinds ENTITY2** \using ENTITY3\

Use without subject where ENTITY2 is said to be blind but the blinding
is not described. ENTITY3 is typically a weapon that exists as an
entity in the dataset.

* **Populates filecard category 'blinded by' (both subject and using)**

**If 'using' contains an object or landmark, populates filecard category
'used to harm'**

* **Triggers phenomenon 'blinded heroes'**

* **ENTITY attacks ENTITY**

Use only if action is not captured by a more specific interaction.

### 2.8.11 Competitions

Where action occurs in the context of combat use interactions listed
under 2.8.10(#physical-altercations).

Only create games as entities where they are one-off events. See
2.4.6(#creating-mythical-events) and
4.7(#panhellenic-games). For regular competitions like
the Olympic, Isthmian, Nemean, Pythian games or prominent regional
games, use 'in/on/at PLACE' instead.

* **ENTITY competes** \for\] \against\ \[in/on/at\

**If 'in/on/at' contains an event, populates filecard categories
'competitors', 'competes in'**

* **ENTITY1 wins in competition ENTITY2** \against ENTITY3\ \[in/on/at
ENTITY4\]

ENTITY2 is the prize; ENTITY3 is the defeated opponent; ENTITY4 is the
place or event at which the competition occurs. Where ENTITY2 is also
a war prize won in competition, use 'wins as war prize' or 'is slave
as well.

**If 'in/on/at' contains an event, populates filecard categories
'competitors', 'competes in'**

* **ENTITY1 establishes games** \in/on/at ENTITY2\] \[to honor ENTITY3\

Use to capture the first instance of a regular event (e.g. the
Olympic, Isthmian, Nemean, Pythian games or prominent regional games).
ENTITY2 is the location of the event; ENTITY3 is the god or hero
honored. If the games exists as an event, use 'holds'.

**Populates filecard categories 'games established by', 'establishes
games at'**

* **ENTITY1 holds games** \in/on/at ENTITY2\] \[to honor ENTITY3\

Use to capture a regular event (e.g. the Olympic, Isthmian, Nemean,
Pythian games or prominent regional games). ENTITY2 is the location of
the event; ENTITY3 is the god or hero honored. To capture the first
instance of these games, use 'establishes games'. If the games exists
as an event, use 'holds'.

* **Populates filecard categories 'games held by', 'holds games at'**

* **ENTITY1 holds** * **EVENT** \to honor ENTITY3\

ENTITY3 is the god or hero honored. If the games is not captured as an
event (e.g. the Olympic, Isthmian, Nemean, Pythian games or prominent
regional games) use 'holds games'.

* **Populates filecard category 'held by', 'holds', 'held to honor'**

### 2.8.12 Capturing, Enslaving, Imprisoning

* **ENTITY imprisons ENTITY**

* **ENTITY1 sells as slave ENTITY2** (ind. obj. ENTITY 3)

ENTITY2 is the enslaved agent. Both ENTITY1 and ENTITY3 are enslavers.
\'Is slave of\' and 'wins as war prize' also exist.

* **Populates filecard category 'enslaved to'**

* **Triggers phenomenon 'people enslaved'**

* **ENTITY1 wins as war prize ENTITY2**

Use only in the context or aftermath of war. 'Sells as slave' and 'is
slave of' also exist.

* **Populates filecard category 'enslaved to'**

* **Triggers phenomenon 'people enslaved'**

* **ENTITY abducts ENTITY**

Use only in the context of amorous desire. 'Captures' and 'rapes' also
exist.

* **ENTITY1 captures ENTITY2**

If ENTITY2 is subsequently enslaved, use 'wins as war prize'. If the
thing captured is a place, use 'conquers', or 'destroys'.

* **ENTITY1 ransoms ENTITY2** \from ENTITY3\

ENTITY1 pays a ransom. 'Releases' also exists.

* **ENTITY1 releases ENTITY2** \ind.obj. ENTITY3\] \[from\

Use where 'ransoms' is not appropriate.

* **ENTITY rescues ENTITY** \from\

If the rescue involves retrieval from the Underworld, use 'takes'.

* **ENTITY guards ENTITY**

Use also where animals are being herded.

### 2.8.13 Sexual Relations

* **ENTITY1 has sex with ENTITY2** \in/on/at ENTITY3\ \[and they
conceive ENTITY4\]

Use only where 'rapes', 'attempts to rape' are not accurate. ENTITY4
is the resulting offspring.

**When 'in/on/at' and 'and they conceive' are used, populates filecard
categories 'conceived at', 'place of conception of'**

**When 'and they conceive' is used, populates filecard categories
'son/daughter/child/ children of', 'mother/father of', 'has children
with'**

* **ENTITY desires ENTITY**

Use only if action is not captured by a more specific interaction.

* **ENTITY1 rapes ENTITY2** \in/on/at ENTITY3\ \[and they conceive
ENTITY4\]

Use in instances of explicit sexual assault; otherwise, use
\'abducts\' or \'has sex with\'. ENTITY4 is the resulting offspring.

**When 'in/on/at' and 'and they conceive' are used, populates filecard
categories 'conceived at', 'place of conception of'**

**When 'and they conceive' is used, populates filecard categories
'son/daughter/child/ children of', 'mother/father of', 'has children
with'**

* **ENTITY attempts to rape ENTITY**

Use only where the attempt fails.

### 2.8.14 Conversations 

* **ENTITY speaks in assembly** \of COLLECTIVE\] \[in/on/at PLACE\

* **ENTITY1 puts on trial ENTITY2**

Use to capture all kinds of legal interactions**\
Populates filecard category 'place of trial of'**

* **ENTITY threatens ENTITY**

* **ENTITY insults ENTITY**

Use in context of verbal insults. Where an agent acts in a generally
insulting way, use \'offends\'.

* **ENTITY offends ENTITY**

Use only if the action is not captured by a more specific interaction.
Use to capture a mortal acting offensively towards (esp.) a god(dess)
by (e.g.) not giving sacrifices.

* **ENTITY quarrels with ENTITY**

Use only if action is not captured by a more specific interaction

* **ENTITY warns ENTITY** \against\

* **ENTITY1 pledges oath with ENTITY2** \against ENTITY3\ \[with the
involvement of ENTITY4\]

ENTITY4 should be gods (etc) invoked to witness the oath.

* **ENTITY performs \in/on/at\] \for\ \[using\**

Capture the content of the song (etc) in a separate tie.

* **Triggers phenomenon 'mythic performers'**

### 2.8.15 Ritual interactions

Note: 'is priest' and 'is prophet' appear in
2.8.6(#roles-and-non-familial-relationships).

For prayer or supplication, use 'requests help' in
2.8.8(#friendly-interactions).

* **ENTITY1 makes sacrifice** \of ENTITY2\] \[ind.obj. ENTITY3\ \[using
ENTITY4\]

ENTITY2 is the thing sacrificed; ENTITY3 is the god or hero sacrificed
to.

**If ENTITY2 is an agent, populates filecard categories 'dies at',
'place of death of', 'killed by', 'kills'**

**If ENTITY2 is an agent, and ENTITY4 is an object or landmark,
populates 'killed by', 'used to kill'**

* **Triggers phenomenon 'human sacrifices'**

* **ENTITY1 dedicates** * **ENTITY2** \ind.obj. ENTITY3\

ENTITY2 is a votive, and typically an object; ENTITY3 is the god or
hero to which it is dedicated. If the votive is not an entity in
MANTO, use 'makes sacrifice'.

* **Populates filecard categories 'dedicated at', 'dedicated by'**

* **ENTITY1 establishes cult** \of ENTITY2\] \[in/on/at ENTITY3\ \[from
ENTITY4\]

If cult to ENTITY2 already exists at ENTITY3, use 'develops cult'
instead. ENTITY4 is the place rituals etc are brought from. Use
'creates', 'dedicates' etc to capture specific objects and landmarks
as well.

* **Populates filecard categories 'cult site of' 'cult sites'**

**If ENTITY3 contains 'sanctuary', 'oracle' or 'grove', populates
filecard category 'cult established by', 'creates'**

* **ENTITY1 develops cult** \of ENTITY2\] \[in/on/at ENTITY3\

Use where an agent expands, improves or popularizes a pre-existing
cult of ENTITY2 at ENTITY3. Use 'creates', 'dedicates' etc to capture
specific objects and landmarks as well.

* **Populates filecard category 'cult site of', 'cult sites'**

* **ENTITY1 has cult site** \in/on/at ENTITY2\

ENTITY1 is an agent or collective; ENTITY2 is a landmark or place. You
do not need to capture cult sites dedicated to Olympian gods,
Heracles, Asclepios, Demeter, Persephone, and personifications that
have no connection to the *spatium mythicum*.

* **Populates filecard categories 'cult site of', 'cult sites'**

* **ENTITY1 initiates into cult** * **ENTITY2** \of ENTITY3\ \[in/on/at
ENTITY4\]

ENTITY2 is the agent who is initiated; ENTITY3 is the god or hero whose
cult it is.

* **ENTITY1 gives special gift** \ind. obj. ENTITY2\

ENTITY1 is a divine figure who bestows a special gift upon a mortal,
which is not an entity in MANTO (e.g. the first grapevine). 'Grants
superhuman power' also exists.

* **ENTITY1 grants superhuman power** \ind.obj. ENTITY2\

ENTITY1 is a divine figure who grants a superhuman power to ENTITY2.
ENTITY2 must be a hero or heroine and not (e.g.) a monster, animal, or
object. Where ENTITY2 has superhuman power but no god is identified as
granting it, use '\BLANK\] grants power \[ind.obj. ENTITY2\. Where
the power is specifically said to be prophecy, use 'grants power of
prophecy'.

* **Populates filecard category 'granted superhuman power by'**

* **Triggers phenomenon 'superhuman powers'**

* **ENTITY1 grants power of prophecy** \ind.obj. ENTITY2\

ENTITY1 is a divine figure who grants the power of prophecy to
ENTITY2. Where ENTITY2 is described as being granted prophetic power
but no god is identified as granting it, use '\BLANK\ grants power
of prophecy \ind.obj. ENTITY2\'. 'Is prophet' and 'gives prophecy'
also exist.

* **Populates filecard category 'granted power of prophecy by'**

* **Triggers phenomenon 'superhuman powers'**

* **ENTITY1 gives prophecy** \ind.obj. ENTITY2\

ENTITY1 is the source of the prophecy, either the god or the prophet
or both. If the prophecy is given at Delphi and comes from Apollo,
ENTITY1 should be 'Oracle of Apollo' (see
4.3(#prophecies-at-delphi)).

* **ENTITY1 appears in an epiphany** \ind.obj. ENTITY2\ \[in/on/at
ENTITY3\]

Where the epiphany occurs in the historical period, use 'appears as an
epiphany in the historical period'.

* **ENTITY1 appears in an epiphany in the historical period** \[in/on/at
ENTITY2\]

ENTITY3 is the location where the epiphany occurred. Use with a
timemark; if the timemark is left empty, the epiphany occurred when
the passage was written. Where the epiphany occurs in the mythical
period, use 'appears in an epiphany'.

### 2.8.16 Possession, creation, usage, and gifting

* **ENTITY possesses ENTITY**

Use only if not captured by a more specific interaction.

* **ENTITY creates humans**

Use only where an entity creates humankind. Where an entity creates a
specific human (e.g. Pandora), use 'creates'.

* **Populates filecard category 'humans created onsite by'**

* **Triggers phenomenon 'creators of humans'**

* **ENTITY1 creates ENTITY2** \from ENTITY3\

ENTITY3 is something which ENTITY1 uses to create ENTITY2. Where
ENTITY2 is a sanctuary, use 'establishes cult'; where ENTITY2 is a
fictional agent, use 'invents'.

**Populates filecard categories 'created at', 'created by', 'creates',
'created from', 'from which is created'**

**If ENTITY2 contains 'walls', 'gate', populates filecard category
'fortified by'.**

**Triggers phenomenon 'creators of humans' if ENTITY2 is a collective or
agent**

* **ENTITY destroys ENTITY**

Where ENTITY2 is also conquered, use 'conquers' as well.

* **Populates filecard category 'destroyed by'**

* **ENTITY1 damages ENTITY2**

Use only if 'destroys' is not appropriate.

* **ENTITY discards ENTITY2**

ENTITY2 is typically an object. 'Abandons' exists for agents.

* **ENTITY consumes ENTITY**

Use in contexts of eating and drinking.

* **ENTITY takes ENTITY** \from\] \to\ \[via\

* **ENTITY1 gives** * **ENTITY2** \ind.obj. ENTITY3\] \[for ENTITY4\

If the thing given is not an entity in MANTO, use 'gives something'.
Where ENTITY2 is a kingdom, use also 'rules', 'succeeds' etc to
trigger reversals. ENTITY4 is something given in exchange. 'Gives in
marriage', 'grants power (of prophecy)', 'gives special gift',
'dedicates' also exist.

* **ENTITY1 gives something \ind. obj. ENTITY2\**

Use only where the thing given is not an object in MANTO; otherwise,
use 'gives'.

* **ENTITY offers ENTITY** \ind.obj.\

Use only if the offer is not accepted, or promised but never
delivered. 'Offers in marriage' also exists.

* **ENTITY hides ENTITY** \from\

Use either to capture an entity hiding another, or an entity hiding
him or herself (i.e. ENTITY hides \[BLANK). For disappearances
analogous to death, use 'disappears'; for the hiding of bodies in the
ground, use 'buries'.

### 2.8.17 Collectives and Groups

Agents can also be enrolled as members of collectives using 'is herald,
'is helmsman', 'is healer', 'is prophet' (see
2.8.6(#roles-and-non-familial-relationships)).

Sub-groups can be nested inside larger collectives using the entity
attribute * **Part of**. Where an agent is a member of a
subgroup, they will also appear in the filecard categories 'belongs to'
and 'includes' in relation to the larger collective.

**ENTITY1 leads ENTITY2\
ENTITY2 must be a collective.**

**Populates filecard categories 'led by', 'includes', 'leader of',
'belongs to'**

* **ENTITY assembles ENTITY**

* **ENTITY1 is member of ENTITY2**

ENTITY1 is typically an agent; ENTITY2 is always a collective. Use to
express membership of agents in collectives. If the collective is a
group of siblings (e.g. "the Children of Niobe"), you will need to
also create a "is child of" tie.\
* **Populates filecard categories 'includes', 'belongs to'**

### 2.8.18 Rulership and Landownership

* **ENTITY1 rules ENTITY2** \for ENTITY3\] \[from ENTITY4\

ENTITY2 should be a place. Where a king or kingdom is strongly
associated with both a region and a capital city within that region,
give both as ENTITY2 (E.g. 'Pandion rules Athens, Attica'). ENTITY3 is
a minor or absent ruler for whom ENTITY1 acts as regent. ENTITY4 is a
place outside of ENTITY2 where ENTITY1 rules from. Where an entity
leads a collective, use 'leads'. Where a ruler is also eponym, use
'rules as eponym'. 'Succeeds' also exists.

**Populates filecard categories 'ruled by', 'ruler of' (both d.obj and
'from' are places ruled)**

* **ENTITY1 rules as eponym ENTITY2** \for ENTITY3\] \[from ENTITY4\

ENTITY2 should be a place for which ENTITY1 is both ruler and eponym.
ENTITY3 is a minor or absent ruler for whom ENTITY1 acts as regent.
ENTITY4 is a place outside of ENTITY2 where ENTITY1 rules from. This
interaction is a shortcut; it is equivalent to creating two separate
ties ('rules' and 'is eponym of').

**Populates filecard categories 'ruled by', 'ruler of', 'eponym of',
'eponym'**

* **ENTITY1 succeeds ENTITY2** \in/on/at ENTITY3\

ENTITY1 and ENTITY2 are successive rulers of ENTITY3, which should be
a place. 'Gives' can also be used to express kingship. Where a king or
kingdom is strongly associated with both a region and a capital city
within that region, give both as ENTITY3 (E.g. 'Pandion succeeds
Cecrops in/on/at Athens, Attica').

**Populates filecard categories 'ruled by', 'ruler of' (both sbj and
obj are rulers)**

* **ENTITY1 founds ENTITY2** \from ENTITY3\

Use only for founding of cities. For regions, islands etc use
'settles'. For sanctuaries, use 'establishes cult'. ENTITY3 is where
ENTITY1 comes from. Capture details of eponym, naming etc in separate
tie(s)

**Populates filecard categories 'founder of', 'founded by', 'founded
from'**

* **ENTITY1 founds as eponym ENTITY2** \from ENTITY3\

Use only for founding of cities where ENTITY1 is both founder and
eponym of ENTITY2. For regions, islands etc use 'settles'; for
sanctuaries, use 'establishes cult'. ENTITY3 is where ENTITY1 comes
from. This interaction is a shortcut; it is equivalent to creating two
separate ties ('founds' and 'is eponym of').

**Populates filecard categories 'founder of', 'founded by', 'founded
from', 'eponym of', 'eponym'**

* **ENTITY1 conquers ENTITY2**

Where ENTITY2 is also destroyed, use 'destroys' as well.

* **Populates filecard categories 'conquered by'**

* **ENTITY1 settles ENTITY2** \from ENTITY3\

ENTITY2 should be a region or area, perhaps already inhabited, which
is settled by ENTITY1. ENTITY3 is where ENTITY1 comes from. 'Conquers'
also exists. Use 'founds' for cities. Where ENTITY1 is also eponym of
the region, use 'is eponym of' as well.

**Populates filecard categories 'settles', 'settled by', 'settled
from'**

### 2.8.19 Connections to places

* **ENTITY1 resides** \in/on/at ENTITY2\] \[near\

If ENTITY2 is not a landmark, use only if action is not captured by a
more specific interaction. If ENTITY2 is a landmark, use only for
(semi-)permanent residence there.

**If 'in/on/at' contains a landmark, populates filecard categories
'dwelling', 'dwelling of'**

* **ENTITY is depicted** \Depicted on: ENTITY2\ \[with the involvement
of ENTITY3\]

ENTITY2 is the thing or place on or at which the depiction is
displayed. Use also for depictions created in the historical period.
ENTITY3 is the place that commissioned or was otherwise involved in
the creation of the object displayed at ENTITY2 (typically used where
a city dedicates a votive at Delphi or Olympia). You do not need to
capture depictions of Olympian gods, Heracles, Asclepios, Demeter,
Persephone, and personifications unless there is clear narrative
content or they are included in a grouping that seems significant in
some way.

* **Populates filecard categories 'has depictions of', 'depictions'.**

* **ENTITY is a relic** \in/on/at\

Use where a mythic object or landmark is described as surviving in the
historical period, or an animal is so long-lived that it was born in
the mythic period and encountered in the historical period. Use with
an historical timemark; if the timemark is left empty, the relic was
in existence when the passage was written.

**Populates filecard categories 'survives as a relic at', 'relics
preserved on site'**

* **Triggers phenomenon 'preserved relics'**

* **ENTITY1 is moved** \from ENTITY2\] \[to ENTITY3\

ENTITY1 is a mythic relic moved during the historical period from
ENTITY2 to ENTITY3. Use with a timemark; if the timemark is left
empty, the relic was being moved when the passage was written.

**Populates filecard categories 'moved in the historical period
from/to', 'survives as a relic at', 'relics preserved on site' (places
drawn from both 'to' and 'from' fields)**

* **Triggers phenomenon 'preserved relics'**

* **ENTITY1 is entrance to ENTITY2**

Use only to capture entrances to the Underworld. ENTITY2 must be 'the
Underworld'.

**Populates filecard categories 'serves as entrance to' and
'entrances:'**

* **Triggers phenomenon 'entrances to underworld'**

* **ENTITY1 flows into ENTITY2**

Both ENTITY1 and ENTITY2 are waterways, typically rivers or springs.
Use only where they are said to flow into or out of one another
against geographical accuracy.

* **Populates filecard category 'flows into or out of'**

* **Triggers phenomenon 'impossible waterways'**

* **ENTITY fortifies ENTITY**

When walls and gates exist in MANTO as fortifications (see
2.4.4(#creating-places-and-landmarks)), use 'creates'
instead.

* **Populates filecard category 'fortified by'**

### 2.8.20 Movement

* **ENTITY1 travels** \from ENTITY2\] \to ENTITY3\ \[via ENTITY4\

Use to capture complex travel itineraries in the mythical period with
ENTITY4 used to capture stops along the route in order; use if action
is not captured by a more specific interaction (e.g. 'visits',
'migrates').

* **ENTITY1 goes past ENTITY2**

Use where ENTITY1 does not visit or stop at ENTITY2.

* **ENTITY1 crosses ENTITY2**

Use where ENTITY1 crosses ENTITY2, which will be a specific waterway.

**ENTITY1 shipwrecks ENTITY2 \in/on/at ENTITY3\ \[while intending to
go to ENTITY4\]**

ENTITY1 causes the shipwreck; ENTITY2 is shipwrecked (including the
vessel if it is an entity in MANTO). ENTITY4 is the place ENTITY2 was
heading towards. Where no god (etc.) is identified as causing the
shipwreck, use '\BLANK\] shipwrecks \[ENTITY\'.

* **Triggers phenomenon 'shipwrecks'**

* **ENTITY sends** * **ENTITY** \against\] \from\] \[to\ \[via\

* **ENTITY1 expels ENTITY2** \from ENTITY3\] \[to ENTITY4\

* **ENTITY searches for ENTITY** \in/on/at\] \from\] \[to\ \[via\

* **ENTITY flees** \from\] \to\ \[via\

* **ENTITY1 encounters ENTITY2**

Use only if action is not captured by a more specific interaction.
Both ENTITY1 and ENTITY2 should typically be agents or collectives.

* **ENTITY migrates** \from\] \[to\

Use where an entity changes their homeland in a (semi-)permanent
manner (e.g. a woman is born into a family from one region and marries
into a family in another) and the action cannot be captured by a more
specific interaction.

### 2.8.21 Miscellaneous, disambiguation and conflation

* **ENTITY is associated with ENTITY**

Use only if not captured by a more specific interaction.

* **ENTITY1 is mentioned**

Use where there is no other entity in MANTO to connect ENTITY1 to.
These ties should only have subject and predicate. Particularly useful
when collecting data from fragments, where sometimes a name appears
with no context.

* **ENTITY is conflated with ENTITY**

Use where two entities that are ontologically distinct in MANTO are
said to be the same entity. When a mythic entity is identified in the
historical period, use 'is identified \as\'. When the context is the
syncretism of Greek and non-Greek entities, use '\Non-Greek entity\
is identified as \Greek entity\' (see
4.4(#syncretism-of-gods-and-goddesses))

* **Populates filecard category 'sometimes conflated with'**

* **ENTITY1 is identified as ENTITY2**

ENTITY1 is a mythic entity; ENTITY2 is an historical entity. 'Is
identified \in/on/at\' also exists.

* **Populates filecard category 'identified as'**

* **\ENTITY1\] is identified** \in/on/at ENTITY2\ \[near\

ENTITY1 is a mythic entity; ENTITY2 is an historical entity. 'Is
identified as' also exists

* **Populates filecard category 'identified in' (only on sbj's filecard)**

* **\Non-Greek entity\] is identified as \[Greek entity\**

Use to capture syncrecism of Greek and non-Greek deities and heroes.
See 4.4(#syncretism-of-gods-and-goddesses).

* **Populates filecard category 'identified as'**

* **Triggers phenomenon 'syncretism'**

* **ENTITY is** * **located** \in/on/at\] \[near\

Use to express topographical relationships which are not ontologically
stable enough to be captured as attributes of the entity itself. Often
used to express relationships between mythical places (e.g. locations
within the Underworld). Use 'is identified \as\' where a mythic
entity is identified in the historical period.

* **ENTITY is contemporary of ENTITY**

Use only where no other interaction captures the fact that two agents
or collectives belong to the same generation.

* **ENTITY is compared to ENTITY**

Use where a passage directly compares the qualities of two otherwise
unrelated entities, and no other interaction can be captured.