# Issues

4.1: Epithets

Because MANTO is primarily concerned with mythic narratives rather than
cult practices or religious ideas, we do not distinguish between the
various facets of gods as identified by their epithets. So, for example,
we treat Zeus Eleutherios ('the deliverer') and Zeus Horcios ('guardian
of oaths') as the same entity, i.e.
'Zeus(https://manto.unh.edu/viewer.p/60/2616/object/6580-8188419)'!
With heroes, epithets can sometimes be too vague or poetic to be
captured in our database. In other words, we ignore descriptors like
'godlike' or 'scion/peer of Ares'. (i.e. do not capture 'ACHILLES is
compared to ARES' or 'HELEN is compared to APHRODITE' if the point of
the comparison is simply to say that she is beautiful and he is fierce
in war.)

However, we do need to take note of epithets that express concrete
relationships between that entity and other entities. Because the
meaning of epithets tends to be quite allusive or uncertain, you often
need to draw on outside knowledge to create a useful tie and use your
own judgment as to which might be the best interaction to use. As
always, try searching Nodegoat to see what other people have done
previously, and use **Data uncertain, Note,** and
**Commentary** if appropriate.

Some examples:

'Zeus Lycaios' might be captured as 'ZEUS is associated with MOUNT
LYCAION'

'Zeus Dicte' might be captured as 'ZEUS is associated with MOUNT DICTE'

'Zeus Cronides' might be captured as 'ZEUS is child of CRONOS'

'Zeus Agamemnon' might be captured as 'ZEUS is associated with
AGAMEMNON'

Note of course that if there is a more specific passage in the text that
you can use to capture such relationships (preferably using a more
specific interaction!), then you should use that instead. It's not
necessary to capture the same information more than once in a text.

If an epithet is used in place of the actual name in a text, and you
think a user might be confused when they click through to the text, add
a note in **Commentary** explaining your decision (e.g.
''Argeiphontes' is used in line 110 to mean Hermes').

# 4.2: Repeating ties

You will not be able to capture absolutely every possible relationship
in every line of text---believe us, we've tried!

Our job is to capture the relationships that make up the Greek
storyworld in its fullness; the dataset will not be able to act as a
list of everywhere that Zeus is called the son of Cronos, or Apollo
called 'Delian', or Helen described as the wife of Menelaos. These just
appear too frequently. The most important thing is that we capture as
many different relationships as we can in the dataset. Ideally, we would
also capture each of these relationships in connection to each text that
it appears in, but not in every passage of that text. This means that,
for commonly-repeated pieces of mythical data you should capture them
once per text: choose either the first time it occurs, or a particularly
useful example of it. Any time it reappears after that, you can ignore
it. (There is nothing necessarily wrong with capturing the same tie more
than once in a text, it is simply creating extra work!)

# 4.3: Prophecies at Delphi

To capture oracles given at Delphi (usually by the Pythia) whose
ultimate source is Apollo, use '[the Oracle of
Apollo](https://manto.unh.edu/viewer.p/60/2616/object/6580-10186749)'
entity in the 'in accordance with a prophecy from' field, or as subject
in 'gives prophecy' ties. Do not also use \'Apollo\',
\'Pythia\', or \'Delphi\'.

We only use
Pythia(https://manto.unh.edu/viewer.p/60/2616/object/6580-8189965)
as an entity when she is an active agent in a mythical event (e.g.
breaking up the fight between Apollo and Heracles over the tripod).

# 4.4 Syncretism of gods and goddesses

'Syncretism' means that people identified one deity as equivalent to, or
perhaps embodying some aspect of, another deity. These ideas are a
challenge to our data model, which is based on the idea that each entity
is (theoretically) distinct from the others. Because MANTO is primarily
concerned with mythic narratives rather than cult practices or
religious, we do not fully capture all instances of syncretism described
in our sources. You should not use 'is conflated with' in these
situations. Here are some possible strategies:

You might find that an author asserts that a hero or heroine transformed
into a god or goddess; in these instances, you can use interactions like
'becomes immortal' etc. (see
2.8.7(#names-and-transformation)).

Where a Greek agent is said to be the same as a non-Greek one, use
'\Non-Greek entity\] is identified as \[Greek entity\'. E.g. --

> *Apollodoros 2.1.3:"having found Epaphus \[Io\ came to Egypt and was
> married to Telegonus, who then reigned over the Egyptians. And she set
> up an image of Demeter, whom the Egyptians called Isis, and Io
> likewise they called by the name of Isis.]{.mark}*
>
> ***ISIS is identified as DEMETER{.mark}***
>
> ***local source: EGYPT{.mark}***
>
> ***ISIS is identified as IO{.mark}***
>
> ***local source: EGYPT{.mark}***

Where a text is clearly conflating two Greek deities, capture using 'is
associated with' or 'is mentioned' as appropriate. E.g.:

> *Euripides,* Phoenician Women *109-10: "O Lady Hecate,*
>
> *child of Leto! The plain is one lightning-flash of bronze."*
>
> *(NB 'child of Leto' refers to Artemis)*
>
> ***HECATE is associated with ARTEMIS***

# 4.5: Seemingly 'mythical' entities in the historical period

Our definition of 'mythical' is strictly chronological, i.e. existing in
the period which ends 5 generations after the return of the Heracleidai
to the Peloponnese (see 1.1(#ontology)).

This means that we don't capture a number of things which might seem
'mythical'. For example, we don't capture Herodotus' gold-digging ants,
the Griffins who fight the Arimaspians, or the many other strange
creatures on the edges of the known world recorded by ancient
geographers. We do, however, capture groups like the Amazons since even
though they were said to have existed in the historical world, they were
also present in the mythical period.

We also do not capture data about Romulus even though he was the son of
Mars and features in stories that look very similar to the mythic ones
we collect. Because he is 13 generations after Aeneas, he is not
'eligible' to be counted as an agent in MANTO.

# 4.6 Alternative names

The basic principle of MANTO is that each entity in our dataset should
correspond to one particular entity in the ancient world. All entities
have names so that we can identify them easily, but entities are really
concepts rather than labels; so, you should think of an entity like
'[the
Peloponnese](https://manto.unh.edu/viewer.p/60/2616/object/6580-8194371)'
as expressing the concept of a particular location (i.e. the territory
of the Peloponnese that constituted the kingdom of heroes like
Phoroneus, Apis and Argos) even though this location was known by
various different names.

However, this simple principle does need to be broken sometimes.

For the most part, where an entity has several different names we simply
list them in the various fields under **Name.** This means
that they can be used to search for that entity. So, if you search for
either 'Alexandros' or 'Paris' you will find the entity
'Alexander(https://manto.unh.edu/viewer.p/60/2616/object/6580-8182124)'
because both are listed as alternative names.

We only create 'Alternative name' entities when we need an entity to
capture information directly relevant to that name in the dataset. This
usually means that they are needed to appear in ties like 'is eponym
of', or 'changes name of'. So, in the example below, we already have a
main entity '[the
Peloponnese](https://manto.unh.edu/viewer.p/60/2616/object/6580-8194371)'
but we also need to create alternative name entities for
'Apia(https://manto.unh.edu/viewer.p/60/2616/object/6580-8194366)'
and
'Argos(https://manto.unh.edu/viewer.p/60/2616/object/6580-8360025)'
to capture the assertion that
Apis(https://manto.unh.edu/viewer.p/60/2616/object/6580-8182232)
was the eponym of Apia and
Argos(https://manto.unh.edu/viewer.p/60/2616/object/6580-8187815)
was the eponym of Argos. (We connect the alternative name entities Apia
and Argos to the main entity ('the Peloponnese') following the
instructions in 2.4.1.1(#alternative-name-entities).
This means that these alternative name entities should be easy to spot
when you are entering data.)

You will notice that these alternative name entities are just stubs:
they mainly exist to direct the user to the main entity. They don't need
attributes like Pleiades URNs or gender because they are identical to
their main entities in these regards. And you will notice that they are
only used in a few ties, since we use the main entities wherever
possible. So, in the example below, we say that Phoroneus and Apis both
ruled the Peloponnese even though the location was not known by that
name at the time. E.g.,

> *Apollodorus, Library 2.1.1-2: "Phoroneus ruled over all the territory
> that would later be called the Peloponnesos. With the nymph Teledice
> he had Apis and Niobe. Apis turned his power into tyranny, was a
> violent dictator, and named the Peloponnesos Apia after himself ...
> Argos received the kingdom and called the Peloponnesos Argos after
> himself."*
>
> ***PHORONEUS rules THE PELOPONNESE***
>
> ***APIS, NIOBE is child of PHORONEUS, TELEDICE***
>
> ***APIS succeeds PHORONEUS at THE PELOPONNESE***
>
> ***APIS is eponym of APIA (ALT. PELOPONNESE)***
>
> ***APIS names APIA (ALT. PELOPONNESE)***
>
> ***ARGOS succeeds APIS at THE PELOPONNESE***
>
> ***ARGOS is eponym of ARGOS (ALT. PELOPONNESE)***
>
> ***ARGOS changes name of APIA (ALT. PELOPONNESE) to ARGOS (ALT.
> PELOPONNESE)***

The tie 'is alternative name for' exists to capture assertions about
alternative names. You can use this with entities that are not treated
in MANTO as alternative names if required. You do not need to use this
tie every time a name that we treat as an 'alternative name entity' is
used, but it is useful for (e.g.) capturing assertions about the local
uses of names. E.g.:

> *Pausanias 9.12.2: "[Those who think that the Cadmus who came to the
> Theban land was an Egyptian, and not a Phoenician, have their opinion
> contradicted by the name of this Athena, because she is called by the
> Phoenician name of Onga, and not by the Egyptian name of
> Sais."]{.mark}*
>
> ***[ONGA (ALT. ATHENA) is alternative name for ATHENA; local tradition
> at: PHOINICIA, THEBES]{.mark}***

[(Note that in the past we collected more data about alternative names
than we do now, so you may notice that some of the older data doesn't
conform with these instructions.)]{.mark}

'Alternative name entities' should not be created where an entity
undergoes a profound transformation. In these instances they become a
different entity. E.g., the heroine
Ino(https://manto.unh.edu/viewer.p/60/2616/object/6580-8188585)
transforms into the goddess
Leucothea(https://manto.unh.edu/viewer.p/60/2616/object/6580-8189686)
or the woman
Cainis(https://manto.unh.edu/viewer.p/60/2616/object/6580-8189365)
becomes the man
Caineus(https://manto.unh.edu/viewer.p/60/2616/object/6580-8189365).
There are examples amongst the places as well: e.g., the city of
Troy(https://manto.unh.edu/viewer.p/60/2616/object/6580-8194710)
was built on the [Hill of Phrygian
Ate](https://manto.unh.edu/viewer.p/60/2616/object/6580-9615945).
All of these entities are treated as main entities in MANTO because the
transformation is not merely a change of name.

# 4.7 Panhellenic games

We capture one-off events like funeral games as mythic events, but not
games that were celebrated regularly. In these instances, we simply
collect data against the place where the event happened. This mainly
affects the four Panhellenic games (at Olympia, Delphi (the Phythian),
Nemea and Isthmia) as well as some local festivals (e.g. the panathenaic
games at Athens). The ties for collecting data about regular events are
a little different from those used when there is a mythic event that can
be created as an entity in MANTO. See
2.8.11(#competitions).

# 4.8 Personifications

Personifications are agents or collectives that either represent an
abstract concept like 'love' or 'death', or divine incarnations of a
landscape feature, like river gods.

MANTO is primarily concerned with collecting data about mythic
narratives. Personifications (particularly of abstract concepts) are
often used in poetry to express general concepts rather than concrete
events in the mythic world. You should not capture descriptions of
personifications in action which are obviously poetic tropes (e.g.
'Panic defeated the Greek contingent at Troy', 'Rosy-fingered Dawn gave
birth to Day') or the uses of gods' names as personified qualities (e.g.
'Ares' for war or 'Aphrodite' for love).

You may find that some ancient sources deliberately confuse the actions
of personifications of landscape features, and the landscape features
themselves. As a general rule, when the personification acts like an
agent (e.g. gives birth, is metamorphized etc.), capture this data using
the agent entity. Where the natural feature acts like a natural feature
(e.g. is the location for something etc.) then use the place or landmark
entity.

There are instructions for creating personifications as entities in
Nodegoat at 2.4.1.4(#personifications).

## 

# 4.9 Modeling time in MANTO

MANTO does not directly collect information about when events happened
in the *spatium mythicum.* Our data structure focuses on creating ties,
which represent the outcomes of events. But we do not have the ability
to order these events with chronological precision. So, we might have a
list of all the heroes killed at Troy during the war there, but we
cannot determine in which order each died from our data. For this kind
of information, users would need to read the sources themselves.

Even though we can't express time in highly granular ways, MANTO does
indirectly offer ways of modeling mythic time more broadly. We can use
the data in MANTO to determine which agents and collectives interacted
with one another, and so could be said to belong to the same generation.
We can also use ties like 'is child of' to recreate family trees. These
can also reveal the aspects of the chronology of the mythic period.

We do have a small number of mythic events as entities. (See
2.3(#entities-the-basics).) These mark moments in time
in that they capture where a group of people came together at a
particular place. For example, any agent who participates in the
[Funeral Games of
Pelias](https://manto.unh.edu/viewer.p/60/2616/object/6580-9713956)
must be at Iolcos at the same time as all other participants in the
games. So these mythical event entities do provide another way of
establishing broad, relative chronologies within MANTO's mythical
networks.

We also create historical events to use only in timemarks. (See
2.7.5(#timemarks).) When we capture information about
(e.g.) the movement of relics in the historical world we want to be able
to say when such events happened, and so we mark time in these instances
using an historical event entity.

# 4.10: Choosing a Pleiades Number

Pleiades URNs allow us to fetch the locational data (longitude and
latitude) that displays in our maps, and also to link our project to
other digital initiatives.

When you search for a place in Pleiades, you might need to try several
spellings before you find the right one. Pleiades is a community-built
gazetteer so there are some gaps and double-ups in its data. If you are
unsure which of several Pleiades URNs is the best one for our purposes,
some have text references listed that you can check against. You could
also check the index volume to the Barrington Atlas (unfortunately not
online). Pleiades URNs also show the period cities were in existence.
All things being equal, if you need to choose between several options,
use the URN with the earliest dates (preferably 750 BC - )

Because Pleiades is an historical atlas, it is not exactly suited to our
purposes. Many of the places that we describe as fictional or
unlocatable do have URNs in Pleiades -- use these if you can find them.
Take care, however, that you do not use a Pleiades URN that will fetch
locational data if we have described a place as fictional or unlocatable
in MANTO.

See 4.17(#ingesting-locations-from-pleiades) for
instructions on ingesting locational data from Pleiades.

# 4.11: Uploading data using a spreadsheet

Any data can be uploaded by spreadsheet into Nodegoat. This can be
useful for editing lists of entities etc. Where we find it a real
timesaver is in the creation of passages before we start entering the
data of a new text. The full guide from Nodegoat is here:
https://nodegoat.net/guides/csvfile(https://nodegoat.net/guides/csvfile)
but it's useful to have a description of the process specifically geared
towards creating passages:

> First, manually create the AUTHOR and TEXT in Nodegoat.
>
> Next, create an Excel file with the headings AUTHOR, TITLE, PASSAGE,
> CTS URN in the first rows. Fill out the columns with the name of the
> author, title of the text, passage numbers, and CTS URN link to Scaife
> (see 2.3) in the appropriate fields. Note that you can use Excel to
> generate sequential numbers. Finally, Excel removes trailing zeros
> from decimals (e.g. 2.100 is changed to 2.1). To adjust for this,
> select any passage numbers with two decimals (e.g. 2.10-2.99) -\>
> Right Click -\> Format Cells -\> Number -\> Category: Number, and set
> the Decimal Places from 2 to 1, then back to 2. Do the same for any
> numbers with three or more decimals, changing the value to 3 or more,
> as needed.
>
> Finally, save the file as a CSV. Open the drop-down menu that is set
> to Excel Workbook (\*.xlsx) and change this to CSV UTF-8 (Comma
> delimited) (\*.csv) (do not use the other CSV file types, as these do
> not use UTF-8 encoding).
>
> In Nodegoat, upload the CSV using Model -\> Import -\> CSV Files -\>
> Add CSV File.
>
> Next, create a template using Model -\> Import -\> Import Templates
> -\> Add Import Template. Select the CSV file you have just uploaded,
> and select 'Passage' as the target. There will now be four columns to
> adjust. Change the second column from 'Author' to 'Title', 'Passage'
> and 'CTS URN' as appropriate. For 'Author' and 'Title' change the
> final column to 'Object Name'. Save the template.
>
> Finally, click 'Run' on the right-hand side of your new template.
> Nodegoat will display samples of the first, middle, and last passage
> that will be created. Ensure these look correct, then run the template
> to create all of the passages.

# 4.12: Identification of mythical places with historical locations 

Most places in the *spatium mythicum* have quite secure relationships
with places in the *spatium historicum*. For example, the
'Athens(https://manto.unh.edu/viewer.p/60/2616/object/6580-8188815)'
of myth can clearly be assumed to be located on the site of the
historical city.

But when the relationship between a mythical place and an historical
place is not as straightforward, we need to capture this 'messiness'
carefully.

'Messy' relationships between places tend to be of two kinds. The first
kind is where an (e.g.) epic poet describes a certain place, and there
is later dispute over where that place was. A good example of this is
Oichalia(https://manto.unh.edu/viewer.p/60/2616/object/6580-8254017).
There is an archaic epic that tells of its sacking by Heracles in which
it is treated as a specific place (probably on Euboia), but by the
Hellenistic period several different cities claimed to have once been
Oichalia. The second kind is where a place is obviously fictional in
poetry but in later traditions it is located somewhere in the historical
Mediterranean. So, for example, Circe's island of
Aiaia(https://manto.unh.edu/viewer.p/60/2616/object/6580-9051582)
is clearly a fantasy location in the *Odyssey*, but like many of the
places Odysseus visits it was later said to be in southern Italy.

When collecting data for MANTO, we treat both kinds of places in the
same way. We create entities for the unlocatable places (e.g.
'Oichalia', 'Aiaia') and put the word 'unlocatable' in
**Information.** We also create entities for each location
in the *spatium historicum* that claimed to be this place and use the
interaction 'is identified (as)' to connect them. E.g.:

> *[Pausanias 4.2.3: "The Thessalians say that Eurytium, which to-day is
> not inhabited, was formerly a city and was called Oechalia. The
> account given by the Euboeans agrees with the statements of Creophylus
> in his Heraeleia ; and Hecataeus of Miletus stated that Oechalia is in
> Scius, a part of the]{.mark} territory of Eretria. Nevertheless, I
> think that the whole version of the Messenians is more probable than
> these, particularly on account of the bones of Eurytus, which my story
> will deal with later."*
>
> ***OICHALIA (UNLOCATABLE) is identified as EURYTION***
>
> ***Local tradition at: THESSALY***
>
> ***Doubt or disbelief expressed: yes***
>
> ***Alternatives given: yes***
>
> ***EURYTOS is eponym of EURYTION***
>
> ***Doubt or disbelief expressed: yes***
>
> ***Data implicit: yes***
>
> ***OICHALIA (UNLOCATABLE) is identified as OICHALIA (EUBOIA)***
>
> ***Textual source: [Creophylos, Capture of Oichalia fr. 2; Hecataios
> fr. 28 ]{.mark}***
>
> ***Local tradition at: EUBOIA***
>
> ***Doubt or disbelief expressed: yes***
>
> ***Alternatives given: yes***
>
> ***OICHALIA (UNLOCATABLE) is identified as CARNASION***
>
> ***Local tradition at: MESSENIA***
>
> ***Doubt or disbelief expressed: no***
>
> ***Alternatives given: yes***
>
> ***THE TOMB OF EURYTOS (CARNASION) is a relic at CARNASION***

You can see from the second and fifth ties that we collect any
assertions relevant to the specific historical locations against those
specific entities.

It can be difficult in some instances to know whether to collect
narrative data against the mythic location or one of the historical
claimants. Where data is relevant to both, you should capture it against
both.

# 4.13 Rationalized variants

Rationalizations are versions of the traditional stories which are
manipulated to seem less fantastic in some way. You can read more about
them in this [blog
post](https://www.manto-myth.org/blog/rationalising-myth-in-manto).

Wherever possible, you should capture rationalizations in the same way
that you capture traditional forms of the myth. Use the same entities,
and replicate the ties used to capture the episode elsewhere where these
fit the context. Ideally you should also use the commentary field to
alert the user (e.g. 'In this passage, Pausanias gives a rationalized
account of Theseus and Peirithous' journey to the Underworld'). If the
source expresses explicit skepticism of the mythic data, tag the tie
with **Doubt of disbelief expressed.**

If the characters in the rationalized version do things that do not
happen in the traditional versions, and so the data looks very different
from the data that we used to capture the traditional version, then you
need to create new agents. Use **Rationalized form of** to
capture the connection between the rationalized and traditional figures.
(See 2.4.1.2(#rationalized-form-entities) for creating
rationalized entities).

So, in this example of Plutarch's rationalization of Theseus and
Peirithous' trip to the underworld, we use the existing entities to
capture data about
Theseus(https://manto.unh.edu/viewer.p/60/2616/object/6580-8188822),
Peirithous(https://manto.unh.edu/viewer.p/60/2616/object/6580-8189133),
and
Cerberos(https://manto.unh.edu/viewer.p/60/2616/object/6580-8187977),
since they do what they normally do in the myth (except that the action
takes place in Epeiros, not the Underworld). However, we do need new
entities to capture
Aidoneus(https://manto.unh.edu/viewer.p/60/2616/object/6580-10150526),
king of Epeiros as the rationalized form of Hades, and to capture the
fact that Persephone's traditional role is now divided between two
separate figures,
'Phersephone(https://manto.unh.edu/viewer.p/60/2616/object/6580-10150526)',
and
'Kore(https://manto.unh.edu/viewer.p/60/2616/scenario/1/geo/)'.

> Plutarch, *Theseus* 31.4:
> "*Then Theseus, to return the service of Peirithous, journeyed with
> him to Epirus, in quest of
> the daughter of Aidoneus the king of the Molossians. This man called
> his wife Phersephone, his daughter Kore, and his dog
> Cerberus, with which beast he ordered that all suitors of his 
> daughter should fight, promising her to him that should overcome it.
> However, when he
> learned that Peirithous and his friend were come not to woo, but to 
> teal away his daughter,
> he seized them both. Peirithous he put out of the way at once by
> means of the dog, but Theseus he kept in close confinement."*
>
> ***KORE (RAT. PERSEPHONE) is child of AIDONEUS (RAT. HADES),
> PHERSEPHONE (RAT. PERSEPHONE)***
>
> ***AIDONEUS (RAT. HADES) rules MOLOSSIA***
>
> ***AIDONEUS (RAT. HADES) is spouse of PHERSEPHONE (RAT. PERSEPHONE)***
>
> ***CERBEROS kills PEIRITHOUS in MOLOSSIA at the command of AIDONEUS
> (RAT. HADES)***
>
> ***(not all ties included here)***

# 4.14 Nesting entities 

By 'nesting' entities we make our data tidier and more systematic. It
also makes data collection quick because we only need to capture the
most granular form of the assertion, and reversals will take care of the
rest.

When creating places, landmarks, constellations, mythical events and
historical artifacts, you can nest one entity inside another using
**In.** When creating collectives and historical events,
you can nest one entity inside another using **Part of.**
(See 2.4.4-8(#creating-places-and-landmarks) and
2.7.5.1(#creating-historical-events) for details.) By
using these attributes we are expressing how entities relate to each
other in terms of their locations, or the fact that they are subsets of
larger groupings or periods of time.

This allows us to work with quite complex arrangements of entities. So,
at
Troy(https://manto.unh.edu/viewer.p/60/2616/object/6580-8194710)
for example, we have not merely the city 'Troy' but also smaller areas
in and around the city and various landmarks (see fig. 4.14.1) and these
all need to be nested inside one another. You can read more about this
conception of Troy in this [blog
post](https://www.manto-myth.org/blog/a-narrative-gazetteer-of-troy).

!(media/image5.png){width="6.267716535433071in"
height="3.5277777777777777in"}

##### Figure 4.14.1: Nesting of locations at Troy (graphic: G. Goodwin)

The advantage of doing this is that we can capture data in very granular
ways, using the most precise location that we can find. Meanwhile,
reversals in Nodegoat will make sure that this same data also populates
the 'outer' layers of the nest, so that we can be sure that our lists of
(e.g.) everyone who had a tomb in a particular city are accurate since
the tombs that are only collected against the 'inner' layers of the nest
are also listed. In the example of Troy, the [Scaian
Gates](https://manto.unh.edu/viewer.p/60/2616/object/6580-8240597)
is one of the landmarks that
Troy(https://manto.unh.edu/viewer.p/60/2616/object/6580-8194710)
'encompases'.

**Figure 4.14.2: Nesting of locations at Athens (graphic: G. Hawes)**

Take the example of another complex site, Athens. Fig. 4.14.2 shows just
one part of the city. The innermost layer of this nest is the olive tree
that Athena gave to the city and which was preserved there in historical
times. When we collect the tie '[THE OLIVE TREE OF ATHENA is a relic at
THE SANCTUARY OF
PANDROSOS'](https://manto.unh.edu/viewer.p/60/2800/object/6582-9619265),
reversals will populate the filecards for the
tree(https://manto.unh.edu/viewer.p/60/2616/object/6580-9619257)
('survives as a relic at: Sanctuary of Pandrosos') and the
Sanctuary(https://manto.unh.edu/viewer.p/60/2616/object/6580-9619261)
('relics preserved on site: Olive Tree'). And reversals will also send
this data to the outer layers of the nest as well, so that the
information 'relics preserved on site: Olive Tree' will also appear on
the filecards for the
Acropolis(https://manto.unh.edu/viewer.p/60/2616/object/6580-8188821)
and for
Athens(https://manto.unh.edu/viewer.p/60/2616/object/6580-8188815)
itself.

The reversals that are affected by nesting are: "Place of conception
of", "Place of birth of", "Place of death of", "Place of burial of",
"Has depictions of", "Relics on site", and "Related Entities".

# 4.16 Dead bodies 

We create entities that represent the dead bodies of agents as seldom as
possible. When we use interactions like 'buries' or 'recovers the body
of' we use the agent as an entity. Landmarks that represent heroic tombs
(i.e. with the name 'the Tomb of ...') do implicitly contain the body of
an agent, but it is not necessary to create a specific entity to
represent the body itself.

The main reason we do need to create dead bodies as entities is in
situations where the body of a hero is described as a relic or moved in
the historical period. In these situations, the body should be an
Object, and usually have the name 'the Bones of ...'.

# 4.17 Ingesting locations from Pleiades

To run the Pleiades ingestion: From the Nodegoat Data environment select
Processes \> Ingestion \> Pleiades Location Data Run \> Run Ingestion.
This process trashes all locational data in MANTO and fetches the most
recent locational data from Pleiades.

# 4.18 When to tag implicit data

The tag **Data implicit** means the information in the tie
is deduced from the information in the passage, and very likely to be
correct, but it is not explicitly stated in the source material.

Examples include:

(1) When a hero's grandfather is named, which allows you to deduce his
    parentage. E.g.:

> *[Pausanias 2.16.1: "Argus, the grandson of Phoroneus, succeeding to
> the throne after Phoroneus, gave his name to the land." (Implicit in
> this statement is the role of Niobe, who is always Argos' mother and
> Phoroneus' daughter)]{.mark}*
>
> ***ARGOS is child of NIOBE{.mark}***
>
> ***Data implicit: yes***
>
> ***NIOBE is child of PHORONEUS{.mark}***
>
> ***Data implicit: yes***

(2) When a well-known story is alluded to and so you capture more
    complete data than is mentioned in the passage. E.g.:

> *Pindar,* Nemean *5 lines 13-16: "Phocus was the son of the goddess
> Psamatheia; he was born by the shore of the sea. Reverence restrains
> me from speaking of an enormous and unjust venture, how indeed they
> left the glorious island, and what divine power drove the brave men
> from Oenone." (Pindar here refuses to tell the well-known story of how
> Phocos was killed by his brothers, who were then exiled from Aigina)*
>
> ***PELEUS, TELAMON kills PHOCOS in AIGINA***
>
> ***Data implicit: yes***
>
> ***\BLANK\ expels PELEUS, TELAMON from AIGINA***
>
> ***Data implicit: yes***

(3) When a connection is made between (e.g.) a place and a hero, but the
    exact nature of the connection is not spelled out in the passage.
    E.g.:

> *[Pausanias 4.2.3: "The Thessalians say that Eurytium, which to-day is
> not inhabited, was formerly a city and was called Oechalia."]{.mark}
> (Implicit in this statement is the Thessalians' logic: the mythical
> city of Oichalia was ruled by Eurytos, so they are implicitly claiming
> that their city of Eurytion was renamed for him.)*
>
> ***EURYTOS is eponym of EURYTION***
>
> ***Data implicit: yes***

(4) When a character from myth is not very well-known and is identified
    only by a description, meaning that some readers might be uncertain
    about who is meant. E.g.:

> *[Pausanias 2.21.3: "\...Tyrsenus was the son of Heracles and the
> Lydian woman..."]{.mark}*
>
> ***TYRSENOS is child of HERACLES and OMPHALE***{.mark}
>
> ***Data implicit: yes{.mark}***

As always, if you think that a user might be confused about how you
created a tie from that passage, explain yourself in
**Commentary]** or **[Note.** [E.g., in the
final example above, "Omphale is unnamed in the text but is identifiable
by Pausanias\' reference to \'the Lydian woman\'".]{.mark}

# 4.19 Entity attributes for research projects

You will notice that several checkboxes appear after
**Modified?**. These include: **[Ruined city in Pausanias,
Functional city in Pausanias, Matriliny - former king, Matriliny - new
king, Matriliny - woman, Generation.]** These are being used
for specific research projects. Their use is not covered in this manual
and you should not touch them.
