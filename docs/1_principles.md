# Principles

In this section, we explain some of the foundational concepts and aims
of MANTO.

## 1.1 Ontology 

Every digital project requires a formal ontology. This helps us to agree
on basic principles so that we collect data in a relatively consistent
way. Our ontology simplifies and homogenizes Greek myth to make it
useful for many different ancient sources.

We posit that a single timeline runs from the beginnings of the world to
the present. This timeline contains both the *spatium mythicum* (the
'mythical period') and the *spatium historicum* (the 'historical
period') (see *fig. 1.1.1*). These two periods are also distinct
'worlds' with their own norms of geography, chronology, biological and
physical possibility, and social organization. So, for example, whereas
people in the *spatium mythicum* may be born directly from the earth
(i.e. by autochthony), this is not possible in the historical
Mediterranean. Equally, whereas events in the *spatium historicum* can
be recorded precisely as having happened in specific years, months, and
even days; mythic time time can be marked only by generations, reigns,
or by referencing significant events.

!(media/image1.jpg)

*Figure 1.1.1: MANTO ontology for the Greek past (graphic: G. Goodwin)*

Even though the *spatium mythicum* and the *spatium historicum* are very
different from one another, they are not unconnected. Because many of
the events of Greek myth were said to have happened in the
Mediterranean, the *spatium mythicum* still impacted the historical
present. Cities were named for the heroes who founded them; there were
tombs preserving heroic remains; very old objects were said to have been
created by mythic craftsmen; rulers might claim gods and goddesses as
ancestors. This means that various kinds of mythical relics were still
encountered in the *spatium mythicum.*

MANTO is a relational dataset (fig. 1.1.2). It breaks up myths into
manageable 'factoids' and then uses these to construct a massive
network. We are in effect capturing two kinds of relationships. The
first kind is interactions between people, places and objects within the
mythic storyworld. The second kind is the impacts that these people,
places and objects had on the landscapes of the historical
Mediterranean. Although these two kinds of relationships are
theoretically distinct from one another, we capture them both at the
same time using similar methods.

At the core of MANTO is a list of 'entities'. These are specific people,
places, objects (etc.) with ontological fixity: they are stable,
unchanging, and identifiable. We then collect 'ties' that express
connections between these entities. Each tie represents an assertion of
fact found in an ancient source. Quite often the information in one tie
will contradict information in another. Greek myth is full of variants
and disputes so this is not surprising. We never try to decide whether
any particular assertion is true or not. We simply capture them as
evidence for how people have told stories about the Greek mythic world,
and understood its impacts on the historical present.

!(media/image2.jpg)

*Figure 1.1.2: Illustration of the concept of mythic networks (graphic: G. Goodwin)*

## 1.2 Entities in the *spatium mythicum*

We define the *spatium mythicum* as starting with the births of the gods
and ending five generations after the return of the Heracleidai to the
Peloponnese.

Every entity in this storyworld belongs to one of the following
categories:

* 👤 AGENTS: Living entities, including gods, heroes, monsters, and animals.

* 👥 COLLECTIVES: Groups of agents with recognizable collective identities, e.g. the Argonauts](https://manto.unh.edu/viewer.p/60/2616/object/6580-8187813),the Daughters of Proitos](https://manto.unh.edu/viewer.p/60/2616/object/6580-10158859), [the Centaurs(https://manto.unh.edu/viewer.p/60/2616/object/6580-8187970), [the Cattle of Helios.(https://manto.unh.edu/viewer.p/60/2616/object/6580-8190292)

* 🏺 OBJECTS: Moveable, object-like entities without agency and with specific identities, e.g. the Scepter of Agamemnon](https://manto.unh.edu/viewer.p/60/2616/object/6580-8190286), [the Shoulder of Pelops(https://manto.unh.edu/viewer.p/60/2616/object/6580-10055354)

* 🏛️ LANDMARKS: Immovable buildings or smaller natural features, e.g.
 the Tomb of Helen](https://manto.unh.edu/viewer.p/60/2616/object/6580-10149928), [the Olive Tree on the Acropolis(https://manto.unh.edu/viewer.p/60/2616/object/6580-9619257)

* 🌍 PLACES: Significant geographical locations in the mythic storyworld, e.g. Athens](https://manto.unh.edu/viewer.p/60/2616/object/6580-8188815), the Underworld(https://manto.unh.edu/viewer.p/60/2616/object/580-8188448), [Mount Olympos(https://manto.unh.edu/viewer.p/60/2616/object/6580-8253991)

* ⭐ CONSTELLATIONS: stars, groups of stars, and planets in the night sky,
e.g. [the
Pleiades](https://manto.unh.edu/viewer.p/60/2616/object/6580-9882842)

* ⏳ MYTHICAL EVENTS: Significant events which bring together gods and goddesses, heroes and heroines e.g. the Flood of Deucalion](https://manto.unh.edu/viewer.p/60/2616/object/6580-9055626), [the Funeral Games of Achilles(https://manto.unh.edu/viewer.p/60/2616/object/6580-9744216)

For more detail about these types of entities, see
2.3.1(#entity-types).

## 1.3 Entities in the *spatium historicum*

Because the events of myth also impacted the historical present (i.e.
the *spatium historicum*), we also need a few non-mythic entities. But
whereas we are trying to create as comprehensive a model of the networks
of the *spatium mythicum* as we can, we limit our data collection
regarding the *spatium historicum* to the following phenomena:

-   RELICS surviving in the historical world which were objects or
    landmarks created in the *spatium mythicum*.

-   MOVEMENT of relics during the historical period (e.g. transferal of
    the bones of heroes, plundering of sanctuaries).

-   An historical person or group in a particular place claiming
    ANCESTRY from a mythical agent or collective where the connection to
    that location would not otherwise be captured.

-   EPIPHANIES of mythic entities in the historical world (We do not
    systematically capture historical epiphanies of personifications.)

-   REPRESENTATION of mythical entities made in the historical world.
    (*We do not systematically capture depictions of Olympian gods,
    Heracles, Asclepios, Demeter, Persephone, personifications,
    monsters, and mythic objects except where they convey clear
    narrative content or they are involved in a grouping of entities
    that is mythically significant. We do not systematically capture
    images of common mythic entities whose function is decorative rather
    than indicative of clear narrative content or local significance*)

-   CULT SITES created in the historical period which attest a
    relationship between mythical entities which would not otherwise be
    captured. (We do not systematically capture cult sites dedicated to
    Olympian gods, Heracles, Asclepios, Demeter, Persephone, and
    personifications that have no connection to the *spatium mythicum*.)

-   IDENTIFICATION of a mythical place with an historical location (i.e.
    implicit METANOMASIA).

Most of these phenomena are manifestations of entities that we already
have in MANTO because they existed in the *spatium mythicum*. So, an
object in the *spatium mythicum* survives as a relic in the *spatium
historicum*, and an agent or collective might be treated as an ancestor
in the *spatium historicum*. Other phenomena do, however, require the
creation of new entities that existed entirely in the *spatium
historicum*. These are:

* 🌍 PLACES and 🏛️ LANDMARKS that are identified as mythic locations, or associated with historical cult.

* 💠 HISTORICAL ARTIFACTS on which mythical entities are represented or which are associated with historical cult.

* 📅 HISTORICAL EVENTS that are required as timemarks.

For more detail about these types of entities, see
2.3.1(2_practices.md/#231-entity-types).

## 1.4 Ties

We use ties to express connections between entities in our dataset. Each
tie represents an assertion made or implied in a specific piece of
evidence from antiquity (e.g. a passage of text).

All ties in MANTO have the form of a grammatically-standardized
sentence, based on the semantic triple (subject - predicate - object),
but with modifications and additions to allow us to capture more complex
situations. The \'nouns\' in these sentences come from our dataset of
entities; they are often written in CAPS in this manual for clarity. The
predicates come from our list of interactions. Prepositional phrases,
genitive absolutes, and purpose clauses are also allowed. (These are all
listed in 2.7.2-4(2_practices.md/#272-prepositional-phrases).) Figure 1.4.1
shows some examples of actual ties in our dataset from Apollodoros'
*Library*:

!alt text(media/image.png)

*Figure 1.4.1: Examples of Ties in MANTO. Entities are in caps (graphic: G. Goodwin)*

All ties must adhere to the same grammatically-standardized structure so
that our data will be machine-readable; nonetheless, this is a highly
flexible system that suits the richness of myth and allows for a great
deal of autonomy in data collection.

Always keep in mind how these ties will later be used. Firstly, MANTO
works as an index of myth by connecting every entity back to a piece of
ancient evidence. So, a user who searches for
Apia(https://manto.unh.edu/viewer.p/60/2616/object/6580-8194366)
would discover passage
2.1.1(https://manto.unh.edu/viewer.p/60/2800/object/6581-8316517)
in Apollodoros' *Library*; a user who searches for
Deianeira(https://manto.unh.edu/viewer.p/60/2616/object/6580-8188140)
would discover Apollod. *Lib.*
2.7.7(https://manto.unh.edu/viewer.p/60/2800/object/6581-8316560).

Secondly, these ties show the networks of the mythic storyworld. When
entities appear together in a tie, we assume that there is some kind of
relationship between them. This is why they are listed on each others'
filecards as 'Related Entities'. From this we can create larger maps of
relationships \-- you can see these in the public interface by using the
'Network' tabs. These networks are essentially quantitative: they are
shown as stronger or weaker based on the number of ties shared by two
entities.

A third use of this data takes advantage of the fact that our ties
convey much more than the mere fact that a relationship exists between
two entities. Each tie shows the *kinds* of relationships between
entities: we can identify families, for example, or affinities between
gods and particular places, or the way certain cities might have
preserved objects connected to particular wars.

Because our ties are quite specific, and our entities have certain
attributes (like gender) assigned to them, from each piece of data we
collect we can often deduce further information. So, from the third
example in fig.
1.4.1(#figure-1.4.1-examples-of-ties-in-manto.-entities-are-in-caps-graphic-g.-goodwin)
'THERIMACHOS and CREONTIADES and DEICOON and IOLAOS is child of HERACLES and MEGARA(https://manto.unh.edu/viewer.p/60/2800/object/6582-9602152)
we can create certain further statements, for instance:

> HERACLES is father of THERIMACHOS and
> CREONTIADES] and [DEICOON and
> IOLAOS
>
> MEGARA] is mother of [THERIMACHOS and
> CREONTIADES] and [DEICOON and
> IOLAOS
>
> THERIMACHOS is son of HERACLES and MEGARA
>
> MEGARA has children with HERACLES
>
> HERACLES has children with MEGARA
>
> THERIMACHOS] and [CREONTIADES and
> DEICOON] and [IOLAOS belong to the same
> generation
>
> HERACLES and MEGARA belong to a generation earlier than
> THERIMACHOS] and [CREONTIADES and
> DEICOON] and [IOLAOS

Finally, it is important to understand what MANTO is not
able to do. MANTO is like the supercharged index to a book: it helps the
user navigate mythic sources, but is not intended to replace them. For
example, MANTO does not capture *how* an author chooses to tell a myth.
In the final example of fig.1.4.1(#figure-1.4.1-examples-of-ties-in-manto.-entities-are-in-caps-graphic-g.-goodwin),
for example, it's not clear that Deianeira kills her husband Heracles
without meaning to -- the tie 'kills' is used to capture all killings,
but does not distinguish acts of cold-blooded murder from instances of
battlefield slaughter, or unintentional homicide.

## 1.5 Reversals and Filecards

Having tens of thousands of complicated ties in a database is not much
use unless we can sort through them quickly to find what we need. The
filecards in the public interface aim to present basic information about
each entity under standardized headings (e.g. 'daughter of', 'killed
by', 'cult site of' etc).

Most of the information on these filecards cannot be edited directly.
Instead, you will add to them by triggering 'reversals'. Reversals are
logical inferences that MANTO makes automatically based on the ties we
supply and the attributes we assign to different entities.

These reversals mean that we can work very efficiently and accurately. A
single tie will often send different information to several filecards at
the same time. For example, when we add this tie to our dataset \--

**Apollodoros, *Library* 3.6.6-3.6.8:**

**[ZEUS kills CAPANEUS at THE WALLS OF THEBES using THE THUNDERBOLT OF
ZEUS](https://manto.unh.edu/viewer.p/60/2800/object/6582-9613756)**

MANTO will automatically send information to these filecards \--

<table>
<colgroup>
<col style="width: 32%" />
<col style="width: 34%" />
<col style="width: 32%" />
</colgroup>
<thead>
<tr class="header">
<th><p><a
href="https://manto.unh.edu/viewer.p/60/2616/object/6580-8188419"><strong><u>ZEUS</u></strong></a></p>
<p>Kills: CAPANEUS</p>
<p>Uses: THE THUNDERBOLT OF ZEUS</p>
<p>Related entities: CAPANEUS, THE THUNDERBOLT OF ZEUS, THE WALLS OF
THEBES</p>
<p>Mentioned in: Apollod 3.6.6-8</p></th>
<th><p><a
href="https://manto.unh.edu/viewer.p/60/2616/object/6580-8187949"><strong><u>CAPANEUS</u></strong></a></p>
<p>Killed by: ZEUS, THE THUNDERBOLT OF ZEUS</p>
<p>Dies at: THE WALLS OF THEBES</p>
<p>Related entities: ZEUS, THE THUNDERBOLT OF ZEUS, THE WALLS OF
THEBES</p>
<p>Mentioned in: Apollod 3.6.6-8</p></th>
<th><p><a
href="https://manto.unh.edu/viewer.p/60/2616/object/6580-8190284"><strong><u>THE
THUNDERBOLT OF ZEUS</u></strong></a></p>
<p>Used by: ZEUS</p>
<p>Used at: THE WALLS OF THEBES</p>
<p>Used to kill: CAPANEUS</p>
<p>Related entities: ZEUS, CAPANEUS, THE WALLS OF THEBES</p>
<p>Mentioned in: Apollod 3.6.6-8</p></th>
</tr>
<tr class="odd">
<th><p><a
href="https://manto.unh.edu/viewer.p/60/2616/object/6580-9613054"><strong><u>THE
WALLS OF THEBES</u></strong></a></p>
<p>In: THEBES</p>
<p>Place of death of: CAPANEUS</p>
<p>Related entities: ZEUS, CAPANEUS, THE THUNDERBOLT OF ZEUS</p>
<p>Mentioned in: Apollod 3.6.6-8</p></th>
<th><p><a
href="https://manto.unh.edu/viewer.p/60/2616/object/6580-8253960"><strong><u>THEBES</u></strong></a></p>
<p>Encompases: THE WALLS OF THEBES</p>
<p>Place of death of: CAPANEUS</p>
<p>Related entities: ZEUS, CAPANEUS, THE THUNDERBOLT OF ZEUS</p></th>
<th></th>
</tr>
</thead>
<tbody>
</tbody>
</table>

Full details about how ties and entity attributes populate these
filecards are given in Part 2.

## 1.6 Mythic phenomena

Capturing connections with a lot of richness also allows us to identify
specific mythic phenomena.

In some instances, we collect this data directly. For example, we
distinguish in our ties between kinds of births and deaths. So, we can
use Nodegoat's filters to create lists of all the heroes and heroines
who were born from objects by searching on ties that use 'is born \[from
object\]', or all those born by parthenogenesis by searching on ties
that use 'is mother by parthenogenesis', or instances of human sacrifice
by searching on ties that use 'makes sacrifice \of agent\'. Equally,
because we capture when a monster is described as a multi-species
hybrid, or a place is said to be an entrance to the underworld, we can
create lists of those particular phenomena too. These and other
phenomena will be directly accessible in MANTO's public interface soon.
(You will see in 2.8.1-21(2_practices.md/#281-qualities) how we plan to
create them from specific ties.)

But the uses of MANTO's data go beyond just the things we set out to
capture with direct ties. For instance, we recently combined our data
about genealogy with our data about rulership to create an authoritative
list of all of the mythic kings who inherited their kingdom through
matriliny (e.g. because they were son or husband of the former king's
daughter). The ability to surface such examples with relative ease and
then use them to analyze Greek myth at unprecedented scale is what makes
MANTO a unique tool. These kinds of phenomena will not be available to
users in the public interface, but can be created and used by
researchers.

## 1.7 Linked Open Data

One benefit of digital projects is that we can easily use other people's
data to improve our own, and offer our own data to help others. We
follow [Linked Open Data
(LOD)](https://www.manto-myth.org/blog/linked-open-data-the-basics)
principles wherever possible.

For textual passages we use the CTS-URN system as found in [Scaife
Viewer](https://scaife.perseus.org/).

To identify places and fetch locational data, we use the
Pleiades(https://pleiades.stoa.org/) Gazetteer.

Where possible, we add
Wikidata(https://www.wikidata.org/wiki/Wikidata:Main_Page)
links to our entities, and link to
Wikipedia(https://www.wikipedia.org/) to give further
information about the ancient sources we use. MANTO's principal
importance as an LOD resource is in its provision of an authoritative
list of mythic 'people' and objects with stable Unique Resource
Identifiers (URIs). These are the 'object IDs' that appear at the end of
each URL in the public interface. E.g., for
Theseus(https://manto.unh.edu/viewer.p/60/2616/object/6580-8188822):
8188822.

MANTO's canonical URLs have the form (e.g. for Theseus)
https://resource.manto.unh.edu/8188822(https://resource.manto.unh.edu/8188822).
The API can be queried at
https://api.manto.unh.edu/(https://api.manto.unh.edu/).

MANTO is recognised as an authoritative source in Wikidata (Q107400883).
MANTO URIs can be added to Wikidata using the property 'MANTO ID'
(P9736).
