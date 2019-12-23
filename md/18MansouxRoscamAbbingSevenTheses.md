---
Pr-id: MoneyLab
P-id: INC Reader
A-id: 10
Type: article
Book-type: anthology
Anthology item: article
Item-id: unique no.
Article-title: title of the article
Article-status: accepted
Author: name(s) of author(s)
Author-email:   corresponding address
Author-bio:  about the author
Abstract:   short description of the article (100 words)
Keywords:   50 keywords for search and indexing
Rights: CC BY-NC 4.0
...


# Seven Theses on the Fediverse and the Becoming of FLOSS

### Aymeric Mansoux and Roel Roscam Abbing 

## Meet the Fediverse

In recent years, in the context of sustained criticism and general
fatigue that surrounds large-scale corporate social media platforms,[^13MansouxRoscamAbbingSevenTheses_1]
the desire to build alternatives has grown stronger. This has manifested
through the emergence of a wide range of projects, driven by various
motives. These projects introduce themselves by emphasizing what makes
them distinct from corporate social media, whether it is their ethics,
their organizational structure, their underlying technologies, their
features, their source code access, or the special interest communities
they seek to support. Although diverse, these platforms tend to have one
common purpose: to directly question the vendor lock-in of the dominant
social media landscape. As a result, they call for different levels of
decentralization and interoperability in terms of network architectures
and data circulation. These platforms are colloquially known as
the ‘Fediverse’,* *a portmanteau of ‘federation’ and ‘universe’.
Federation is a concept derived from political theory in which various
actors that constitute a network decide to cooperate collectively. Power
and responsibility are distributed as they do so. In the context of
social media, federated networks exist as different communities on
different servers that can interoperate with each other, rather than
existing as a single software or single platform. This idea is not new,
but it has recently gained traction and revitalized efforts toward
building alternative social media.[^13MansouxRoscamAbbingSevenTheses_2]

Earlier attempts to create federated social media platforms came from
Free/Libre and Open Source Software (FLOSS) communities.[^13MansouxRoscamAbbingSevenTheses_3] They
traditionally had an interest in providing *libre* alternatives to
existing closed source and proprietary software. As such, these projects
were originally promoted as similar in function to the corporate
platforms but made with FLOSS. As they were mostly articulated around
the openness of protocols and source code, these software platforms
catered to a limited audience of users and software developers, who were
largely concerned with issues typical of FLOSS culture. This lack of
reach changed in 2016 with the introduction of Mastodon, a combination
of client and server software for federated social media. Mastodon was
quickly adopted by a diverse community of users, including many people
usually under-represented in FLOSS: women, people of color, and
queer-identifying people. Upon joining Mastodon, these less-represented
communities questioned the social dynamics of existing FLOSS
environments, as well as started to contribute both code and critique,
which challenged the dominant one-size-fits-all narrative of corporate
social media. It is no coincidence that this shift happened in the wake
of Gamergate[^13MansouxRoscamAbbingSevenTheses_4] in 2014, with the rise of the ‘alt-right’, and the 2016
US presidential elections. By the end of 2017, Mastodon counted more
than one million users who wanted to try out the Fediverse as an
alternative to corporate social media platforms. There, they could test
for themselves whether or not a different infrastructure would lead to
different discourses, cultures, and safe spaces.

Today the Fediverse is comprised of more than 3.5 million accounts
distributed over almost 5,000 servers, referred to as ‘instances’, which
use software projects such as Friendica, Funkwhale, Hubzilla, Mastodon,
Misskey, PeerTube, PixelFed, and Pleroma, to name a few.[^13MansouxRoscamAbbingSevenTheses_5] Most of
these instances can be interconnected and are often focused on a
specific practice, ideology, or professional activity. In view of this,
the Fediverse demonstrates that a shift from universal gigantic social
networks to small interconnected instances is not just technically
possible, it also responds to a concrete need.

The current popularity of the Fediverse can be seen to be driven by two
parallel tendencies. First, an interest in engaging with specific
technical choices and concerns about closed protocols and proprietary
platforms. Second, a wider willingness to recover agency as users of
social media infrastructures. More specifically, while corporate social
media platforms have allowed many to publish content online, the biggest
impact of Web 2.0 has been the apparent decoupling of matters of
infrastructure from matters of social organization. The mix of operating
systems and social systems from which net culture first emerged,[^13MansouxRoscamAbbingSevenTheses_6] has
been replaced by a system of limited user permissions and privileges.
Those who engage with the Fediverse work to undo this decoupling. They
want to contribute to network infrastructures that are more honest about
their underlying ideologies. These infrastructures do not hide behind
manipulative or delusional exploits of ideas like openness, universal
access, or apolitical engineering. Although today it is too early to
tell whether or not the Fediverse will live up to the expectations of
its inhabitants, and how it will impact FLOSS in the long run, it is
already possible to map current transformations, as well as the
challenges faced in this latest episode of the never-ending saga of net
and computational culture. To do so, we present seven theses on the
Fediverse and the becoming of FLOSS, in the hope of opening up
discussions around some of their most pressing issues.

## 

## 1. The Fediverse as the Transition from Meme Wars to Network Wars

We acknowledge that any good reflection on net culture today must
address memes in one way or another. But what can be added to the
discussion of memes in 2020? It seems that everything has already been
argued, countered, and overexploited by both academics and artists. What
else is left to do apart from constantly keeping up with new meme types
and their meanings? One often overlooked point is that, crucially, memes
do not exist in a vacuum. There are systems that enable their
circulation and amplification: social media platforms. 

Social media platforms have taken the democratization of meme production
and circulation to a previously unseen scale. Moreover, these platforms
have grown in symbiosis with internet meme culture. Corporate social
media platforms have been optimized and engineered to favor material
with memetic qualities. This material encourages reaction and
recirculation and is part of a strategy of user retention and
participation in surveillance capitalism. Consequently, in the
environments used today for the vast majority of online communication,
almost everything has become a meme, or needs to exhibit memetic
properties to survive – or be visible – in the universe of algorithmic
timelines and feeds informed by metrics.[^13MansouxRoscamAbbingSevenTheses_7]

Given that social media is geared toward communication and interaction,
what was completely underestimated was how memes would become far more
than either strategically engineered vessels to plant ideas, or funny
viral things to share with peers. They became a language, a slang, a
collection of signs and symbols through which cultural and subcultural
identity could materialize. The circulation of such memes has in turn
strengthened certain political discourses, which has become a growing
concern for the platforms. Indeed, to maximize the exploitation of their
user activity, corporate social media platforms must find the right
balance between laissez-faire and regulation. They try to do so by means
of algorithmic filtering, community feedback, and terms of services. The
corporate platforms are increasingly faced, however, with the fact that
they have created Petri dishes for all sorts of opinions and beliefs to
circulate out of control, in spite of their efforts to reduce and shape
discursive, user-generated content toward inoffensive,
business-friendly, and otherwise trivial material. Regardless of what
these platforms pretend in PR campaigns or hearings in front of
legislators, it is clear that no amount of tech solutionism and no
amount of outsourced precarious work by traumatised human moderators[^13MansouxRoscamAbbingSevenTheses_8]
will help them to get back into full control.

As a result of increased policing of corporate social media platforms,
all those excluded from or harmed in these environments have become
further interested in migrating to other platforms that they might
control for themselves. The reasons for migrating vary. LGBTQ-affiliated
groups seek safe spaces to avoid online bullying and harassment. White
supremacists look for platforms where their interpretation of free
speech goes unchallenged. Raddle, a radical left Reddit clone, grew out
of the ban of its original Reddit forum; on the far-right, there is
Voat, another Reddit clone.[^13MansouxRoscamAbbingSevenTheses_9] Both developed their own FLOSS platform
as a response to their exclusion. While access to source code, and FLOSS
in general is valued in all these efforts, one of the key historical
advantage of FLOSS practice is surprisingly ignored: the ability to
benefit from and build upon each other’s work. What seems to matter now
is to write the same software for a limited audience, making sure the
source code is not tainted with contributions from another community.
This is a new development within FLOSS communities, who have often
argued that their work is apolitical.[^13MansouxRoscamAbbingSevenTheses_10] This is why, if we’re going
to talk about memes today, we must talk about these social media
platforms. We must talk about these environments that allow, for better
or worse, the sedimentation of knowledge: what happens when a specific
discourse accumulates online, the kind of community it attracts and
fosters, via the feedback loops by which memetic assemblages form. We
must talk about how this process is both enabled by, and impacts the
perception of FLOSS.

Corporate social media platforms have decided to cut anything that could
endanger their business, while remaining ambivalent about their claim of
neutrality. But unlike the radical exodus and software-writing exile of
some communities, the Fediverse offers instead a vast system in which
communities can be independent while still interfacing with others over
several servers. In a situation where either censorship or isolated
exodus were the only options, federation opens a third way. It allows a
community to engage with exchanges or have conflicts with other
platforms while remaining true to its own scope, ideology, and
interests. From here, two new scenarios are possible: One, where a
localized online culture could be established and appropriated as part
of the circulation of discourse within a shared communication network.
Two: where radicalized memetic material would likely favor the emergence
of thinking along axes of friends and enemies spread across instances,
to the extent that simplistic meme wars and propaganda would be replaced
with network wars.

## 2. The Fediverse as an Ongoing Critique of Openness

The concepts of openness, universality, and the free circulation of
information have been central narratives for promoting technological
progress and growth on the internet and the web. While these narratives
have been instrumental in advocating FLOSS and free culture, they have
also been crucial in the development of social media, where the goal was
to create ever-growing networks, encompassing evermore people, freely
communicating with one another. Following liberal traditions, this
approach was believed to favor productive exchanges of opinions by
providing ample space for free speech, access to more information, and
the possibility for anyone to participate. However, these open systems
were also open to capture by the market and exposed to the predatory
culture of corporations. In the case of the web, this has led to
business models that make use of both the structures and the content
circulating across the network.[^13MansouxRoscamAbbingSevenTheses_11] Fast forward to now: corporate
social media leads in the surveillance of individuals and the prediction
of their behavior, in order to convince them to buy into both products
and political ideas.

Historically, alternative social media projects such as GNU Social, and
more precisely Identi.ca/StatusNet, sought to salvage this situation by
creating platforms that tackled this particular form of well-marketed
openness. They created interoperating systems explicitly opposed to
advertising and tracking. In doing so, they hoped to prove that it is
still possible to have an ever-growing network while distributing
responsibility over the ownership of data, and in theory to provide the
means for various communities to appropriate the platforms’ source code
and contribute to protocol design. This was pretty much the shared
belief in the Fediverse around 2016. This belief remained unchallenged
because the Fediverse at the time had not changed much from its early
days as a FLOSS social media federation project, started more than a
decade before. Consequently, it was made up of a largely homogenous
crowd, whose interests intersected technology, FLOSS, and anti-corporate
ideologies. However, as the Fediverse’s population grew more diverse
when Mastodon attracted more heterogeneous communities, conflicts
emerged between these different communities. This time it was the
Fediverse’s own idea of openness that was increasingly challenged by the
newcomers. As part of this critique, a call emerged within the user
community of Mastodon for the ability to block or ‘defederate’ with
other servers in the Fediverse. Blocking means that users or
administrators of servers could choose to prevent content from other
servers in the network from reaching them. ‘Defederation’ in this sense
became an additional option in the toolkit for strong community-based
moderation, since it prevented confrontation with unwanted or harmful
content.

At first the introduction of defederation caused a lot of friction with
users of other Fediverse software. Frequent complaints that Mastodon was
‘breaking the federation’ underscored how the move was seen as a threat
to the entire network.[^13MansouxRoscamAbbingSevenTheses_12] In this view, the bigger and more
interconnected the network could become, the more successful it might be
as an alternative to corporate social media. Similarly, many saw
blocking as limiting the possibilities for personal expression and the
productive exchange of ideas, fearing filter bubbles and isolation as a
consequence. By striving for selected disconnection and challenging the
very idea that online discourse is necessarily generative, the
communities advocating for defederation also challenged the broader
liberal assumptions about openness and universality on which prior
Fediverse software was built.

The fact that concurrently to these developments, the Fediverse grew
from 200,000 to over 3.5 million accounts, at the time of writing, is
unlikely to be a coincidence. Rather than thwarting the network,
defederation, self-governing communities, and the rejection of
universality allowed the Fediverse to accommodate even more communities.
The presence of different servers representing very distinct communities
that each have their local culture and agency over their own slice of
the network, without being isolated from the larger whole, is one of the
more interesting aspects of the Fediverse. However, almost one million
of the total number of accounts are the result of the alt-right platform
Gab switching to the Fediverse protocols, which shows that the network
is still open to capture or domination by a single large party.[^13MansouxRoscamAbbingSevenTheses_13] At
the same time, this development immediately triggered a variety of
efforts to strengthen the possibilities for servers to deal with this
risk of domination. For example, the possibility for some server
implementations to federate based on white lists, which allows servers
to interconnect on an opt-in rather than opt-out basis. Another proposed
response is to extend ActivityPub, one of the most popular and most
discussed protocols of the Fediverse, with stronger authorization
methods based on an object-capability model of computer security,
allowing parties to retroactively withdraw consent from other parties to
see or use their data. What is unique about the Fediverse is this both
technical and cultural acknowledgement that openness has its limits, and
is itself open to wide-ranging interpretations dependent on context,
which are not fixed in time. This is a fundamentally new point of
departure for reimagining social media today.

## 3. The Fediverse as a Site for Online Agonistic Pluralism

As we have established, one of the most important traits of the
Fediverse is that the different software stacks and applications that
constitute it can be hosted by virtually anyone and for any purpose.
This means that it is possible to create an online community that can
interface with the rest of the Fediverse but that operates according to
its own local rules, guidelines, modes of organization, and ideology. In
this process, each community is able to define itself not only through
its own memetic language, interests, and scope, but also in relation to
the other, via difference. Such specificity might make the Fediverse
seem like an infrastructural assemblage that follows the principles of
agonistic pluralism. Agonistic pluralism, or agonism, was first
articulated by Ernesto Laclau and Chantal Mouffe, who then further
developed this political theory. In Mouffe’s view, political consensus
is impossible and radical negativity cannot be avoided in a system where
diversity is limited to similar competing groups within the same
hegemonic order.[^13MansouxRoscamAbbingSevenTheses_14] Mouffe’s thesis addresses democratic systems where
politics that fall outside of what the liberal consensus deems
acceptable are systematically excluded. However, this process is also
visible on corporate social media platforms, in the way they shape and
control discourse in order to stay within the bounds of what is
acceptable for the liberal paradigm, which is aligned with their own
business interests. This has led to the radicalization of those who are
excluded.

The bet made by agonism is that by creating a system in which a
pluralism of hegemonies is permitted, it is possible to move from an
understanding of the other as an enemy, to the other as a political
adversary. For this to happen, different ideologies must be allowed to
materialize via different channels and platforms. An important
prerequisite is that the goal of political consensus must be abandoned
and replaced with conflictual consensus, in which an acknowledgement of
the other becomes the foundational building block of new relationships,
even if this means, for example, accepting non-Western views on
democracy, secularism, communities, and the individual. Translated to
the Fediverse, it is clear that it already contains a relatively diverse
political landscape and that transitions from political consensus to
conflictual consensus can be witnessed in the way communities relate to
one another. At the base of these conflictual exchanges are various
points of view on the collective design and use of the software stack
and the underlying protocols that would be needed to further enable a
sort of online agonistic pluralism.

This said, the fact that discussions around the aforementioned usage of
instance blocking and defederation are fiercely debated, and, at time of
writing, with the seemingly irreconcilable presence of factions of
radical left and alt-right in the Fediverse, the realities of antagonism
will be highly challenging to resolve. The Fediverse’s idea of a system
in which different communities can find a place for themselves amongst
others was concretely put to the test in July 2019, when the explicitly
alt-right platform Gab announced it would change its code base, moving
away from its proprietary system to instead rely on Mastodon’s source
code. As a project that explicitly takes a stance against the ideology
of Gab, Mastodon was confronted with the neutrality of FLOSS licenses.
Other Fediverse projects such as mobile phone clients FediLab and Tusky
were also faced with the same issue; perhaps even more so, because the
direct motivation for Gab’s developers to switch to Fediverse software
was to circumvent their ban from the Apple and Google app stores for
violating their terms of service. By relying on generic FLOSS Fediverse
clients, Gab would be able to escape such bans in the future, and also
forge alliances with other ideologically compatible instances on the
Fediverse.[^13MansouxRoscamAbbingSevenTheses_15] As part of a larger anti-fascist strategy to de-platform
and block Gab on the Fediverse, calls went out to software developers to
add code that would prevent them from using their clients to log in to
Gab servers. This resulted in extensive debates on the nature of FLOSS,
the effectiveness of such measures on public source code modifications,
given that they can be easily reverted, and on the political alignment
of software maintainers.

At the heart of this conflict lies the question of the neutrality of the
code, the network, and the protocols. Should – or even can – a client be
neutral? Does doubling down on neutrality mean the maintainers condone
alt-right ideology? What does it mean to block or to not block another
instance? This latter question has created a complicated back-and-forth
where some instances will demand other instances to explicitly take part
in a conflict, by blocking specific other instances in order to avoid
being blocked themselves. Neutrality, whether driven by ambivalence,
unspoken support, hypocrisy, the desire to troll, a lack of interest,
faith in apolitical technology, or by an agonistic desire to engage with
all sides so as to reach a state of conflictual consensus, is very
difficult to achieve. The Fediverse is the closest environment we
currently have to a diverse global network of local singularities.
However, its complex topology and struggle to deal with the infamous
paradox of tolerance – what to do about the idea of free speech – shows
the difficulty of reaching a state of conflictual consensus. It also
demonstrates the challenge of translating a theory of agonism into a
shared strategy for the design of protocols, software, and community
guidelines. Tolerance and free speech have become volatile topics after
nearly two decades of political manipulation and filtering within
corporate social media; seeing how popular imageboards and discussion
forums have failed to solve these issues does not make for a hopeful
outlook for future experimentation.

Rather than reaching a state of agonistic pluralism, it could be that
the Fediverse will create at best a form of bastard agonism through
pillarization. That is to say, we could witness a situation in which
instances would form large agonistic-without-agonism aggregations only
among both ideologically and technically compatible communities and
software, with only a minority of them able and willing to bridge with
radically opposed systems. Regardless of the outcome, this question of
agonism and of politics in general is crucial for net and computational
culture. In the context of Western post-political systems and the way
these are translated to the net, a sense of loss of political
partisanship and agency has given the illusion, or delusion, that there
is no longer a political compass. If the Fediverse teaches us anything,
it is that the net and the FLOSS components of its infrastructure have
never been more politicized than today. The politics that are generated
and hosted on the Fediverse are not trivial but they are clearly
articulated. What’s more, as demonstrated by the proliferation of social
media political celebrities and politicians actively using social media,
a new form of representative democracy is emerging, in which the memetic
language of post-digital cultures are effectively translated into the
world of electoral politics and back.[^13MansouxRoscamAbbingSevenTheses_16]

## 4. The Fediverse as a Shift from a Technical to a Social Understanding of Privacy

In the past, debates around the risks of corporate social media have
focused on the issues of privacy and surveillance, especially since the
Snowden revelations in 2013. Consequently, many of the technical
responses, particularly those born out of FLOSS communities, have
focused on addressing privacy through security. This was exemplified by
the post-Snowden proliferation of specialized applications for secure
encrypted messaging and email.[^13MansouxRoscamAbbingSevenTheses_17] In these communities, the perceived
threat is the possibility of surveillance at the network level, by
either government agencies or large corporations. Proposed solutions are
therefore conceived as tools that implement strong encryption of both
the transmission and the content of messages, ideally making use of
anonymity over peer-to-peer network topologies. These approaches, while
thorough, require considerable technical knowledge on the part of users.

The Fediverse is then shifting from a predominantly technical to a more
social understanding of privacy, as was clear in relation to discussions
on issue trackers during the early stages of the development of
Mastodon. The threat model discussed there is the one that consists of
other users of the network, accidental associations between accounts,
and the dynamics of online conversations themselves. This means that
rather than focusing on technical features such as peer-to-peer
topologies and end-to-end encryption, development has been centered
around building robust moderation tools, granular visibility settings
for posts, and the possibility to block other instances.

These features, which accommodate for a social understanding of privacy,
have been developed and advocated for by members of marginalized
communities, a substantial part of whom identify as queer. As Sarah
Jamie Lewis notes:

Much of the modern rhetoric around \[…\] privacy tools is focused on
state

> surveillance. Queer communities often wish to hide things from some of
> their family and friends, while also being able to share parts of
> their life with others. Making friends, dating, escaping abusive
> situations, accessing healthcare, exploring themselves and others,
> finding jobs, engaging in safe sex work are all aspects of queer lives
> underserved by the modern privacy community.[^13MansouxRoscamAbbingSevenTheses_18]

So while everyone has a stake in considering the privacy implications
that come from (involuntary) associations between online accounts, for
example between an employer and an employee, marginalized communities
are disproportionately impacted by such forms of surveillance and their
consequences. As the development of newer Fediverse platforms such as
Mastodon got underway, with members of such communities helping to build
them, these issues were put on the agenda of software development
roadmaps. All of a sudden, tools that were used to track and discuss
technical defects during the development of FLOSS also became a
discursive venue for social, cultural, and political issues. We will
return to this point in section six.

The techniques that were eventually developed included server-wide
blocks, advanced moderation tools, content warnings, and improved
accessibility. This allowed for geographically, culturally, and
ideologically disparate communities to share the same network on their
own terms. As such, the Fediverse can be understood as different
communities that rally around a server, or instance, so as to create an
environment where everyone feels comfortable. Again, this represents a
third way: neither the model of privacy where technically inclined
individuals are in full command of their own communications, nor the
model whereby the multitude believes they have ‘nothing to hide’ simply
because they have no say nor control over the systems they depend on. In
effect, the move to a social understanding of privacy has shown that the
Fediverse is now a working laboratory in which questions of social
organization and governance can no longer pretend to be decoupled from
software.

What matters is that the Fediverse represents a shift from defining the
issues of surveillance and privacy as technical problems to defining
them as social ones. However, the focus on social aspects of privacy has
so far resulted in placing a lot of trust in other servers and
administrators to act respectfully. This can be problematic, as for
example direct messages, with their implied privacy, would be far better
managed with technical solutions such as end-to-end encryption. Further,
many of the solutions sought in Fediverse software development seem to
be based on the collective rather than on the individual. This is not to
say that technical security considerations are of no concern at all.
Fediverse servers tend to come with ‘privacy by default’ settings, such
as required transport encryption and the proxying of remote queries in
order not to expose individual users. Still, this shift to a social
understanding of privacy remains young, and the discussion must continue
at many other levels.

## 5. The Fediverse as a Way Out of Data Sharecropping and Free Labor

Corporate social media platforms with their focus on self-gratifying
metrics and gamification are infamous for taking free labor as far as
they can. Whatever information is fed into the system, will be used to
directly or indirectly create models, reports, and new datasets that
have core economic value for the platform owners: enter the world of
surveillance capitalism.[^13MansouxRoscamAbbingSevenTheses_19]

So far regulating these products and services has been extremely
difficult, in part because of effective lobbying from the platform
owners and shareholders, but also, perhaps more importantly, because of
the derivative nature of the monetization that takes place inside
corporate social media. What is capitalized by these platforms is an
algorithmic by-product, crude or not, of the activity and data uploaded
by its users. This creates a distance that makes it ever-harder to grasp
the relationship between online labor, user-generated content, tracking,
and monetization. This distance effectively works in two ways. First, it
obfuscates the exact mechanics at play, making it harder to regulate
data capture and analysis. It allows for situations where these
platforms can develop products that they can benefit from while still
complying with privacy laws from different jurisdictions, and therefore
promote their service as privacy friendly. The latter is often
reinforced by giving their users all sorts of options to mislead them
into believing they are in control of what they feed the machine.
Second, by making it seem that no personally identifiable data is
directly used for monetization; these platforms are hiding the economic
transaction behind other types of transactions, such as personal
interactions between users, professional opportunities, online
community-managed groups and discussions, and so on. In the end, users
are unable to make a connection between their social or professional
activity and its exploitation because it is all derivative of other
transactions that have become essential in our ever-connected lives,
especially in the age of entreprecariat[^13MansouxRoscamAbbingSevenTheses_20] and quasi-mandatory network
connectivity.

As we saw in the discussion of how a social understanding of digital
privacy informed the initial design of Mastodon, the Fediverse offers a
refreshing take on the question of surveillance capitalism. Discussions
surrounding user data and how these issues are tackled at the level of
protocols and graphical interface design are quite transparent and open.
These discussions take place publicly on the Fediverse and on related
software project issue trackers. The way data circulates is made
explicit to new users by other users or their local admin when they are
welcomed onto an instance. These greetings usually contain information
on how federation works and how that affects the visibility and access
of the data they share.[^13MansouxRoscamAbbingSevenTheses_21] This echoes what Robert Gehl sees as one of
the characteristics of alternative social media platforms – that both
the network and its code have a pedagogical function, demonstrating how
they can be used, and how one can move beyond the habitual mode of
limited user-permissions to take part in coding, administrating, and
organizing such platforms.[^13MansouxRoscamAbbingSevenTheses_22] In this sense, users are encouraged to
become active in ways other than simply posting and liking, and are made
aware of the ways in which their data circulate.

Yet regardless of how the community of an instance is organized,
empowered, and actively participating in the platform and network – not
to mention the fact that getting into coding is easier said than done –
more control over data is not guaranteed. It is still possible to easily
scrape or collect information from these platforms, possibly even more
so than from corporate social networks since commercial services
actively prevent others from exploiting their data silo. At present, it
is quite simple to crawl the Fediverse and profile its users. Even
though most Fediverse platforms are themselves against user tracking and
data sharecropping, third parties can do so anyway because the Fediverse
operates as an open network primarily designed for public posts.
Additionally, as certain interests, notably political discussions, tend
to be concentrated on specific servers, activist communities may be more
readily exposed to intelligence. So while the Fediverse helps users to
understand, or be reminded, that whatever is published online can and
will escape their control, it cannot prevent all the habits and false
sense of online security inherited from corporate social media from
going on, after nearly two decades of digital privacy
misinformation.[^13MansouxRoscamAbbingSevenTheses_23]

Furthermore, although the exploitation of user labor is not the same as
that on corporate social media platforms, there are still issues
surrounding labor in this network. To understand these issues, we must
first acknowledge the damage done by the free-to-use wonder of corporate
social media on the one hand, and the misunderstanding of FLOSS
practices on the other; namely, how labor issues and workers’ struggles
have been obfuscated in these processes.[^13MansouxRoscamAbbingSevenTheses_24] This situation has led
people to believe that software production, server maintenance, and
online services should be available free of charge. Corporate social
media platforms are able to financially support their infrastructure
specifically because of the direct and indirect monetization of their
users’ content and activity. In a system where this monetization is
avoided, impossible, or actively resisted, the problem of labor and
exploitation surfaces at the level of server administration and software
development, and concerns all those contributing to the design,
consideration, and support of these infrastructures.

In response to this problem, there is a tendency in the Fediverse toward
making the costs of operation of a community server explicit. Users and
administrators alike encourage funding the various projects through
donations, therefore acknowledging that the production and maintenance
of these platforms cost money. More prominent projects such as Mastodon
have access to larger funds and have set up a system through which
contributors can get paid for their work.[^13MansouxRoscamAbbingSevenTheses_25] These attempts to
compensate labor are a good step, however making them more widespread,
and maintaining such projects in the long run, will require more
structural support. Without substantial funding for ongoing development
and maintenance, these projects will remain contingent upon the
exploitation of the free labor of well-meaning individuals, or subject
to the whims of people making time for their FLOSS hobby. At the same
time there is increasing acknowledgement and precedent that much of
FLOSS can be considered public utility goods, which should be funded
from public sources.[^13MansouxRoscamAbbingSevenTheses_26] In times when the regulation of corporate
social media is on the table for its role in eroding public
institutions, the lack of public funding for non-predatory alternatives
should be more actively discussed.

Finally, in some cases, non-technical tasks like moderation are
remunerated by Fediverse communities. This raises the question of why
some kinds of labor are compensated, and others not, if there is
compensation at all. What about the vital early work of care and
critique by members of marginalized communities in voicing how Fediverse
projects should address a social understanding of privacy, for example?
Without a doubt it was this work that enabled the Fediverse to reach the
user base it has today. Then how can such work be measured? It happens
in and throughout the network, in meta-discussion threads, or on issue
trackers, which is not as quantifiable nor visible as code commits. So
while there are some interesting shifts happening, it remains to be seen
whether users and developers on the Fediverse can be made fully aware of
these issues, and if economic models outside of surveillance capitalism
can thrive to support non-exploitative solidarity and care across the
whole stack.

## 6. The Fediverse as the Rise of a New Kind of Usership

One way to understand the Fediverse is as a signifier of a set of
practices, or rather a set of expectations and demands about social
media software, in which the disparate efforts of alternative social
media projects converge into a shared network with roughly aligned
goals. Diverse models of usership, shared between servers, range from
venture-capital-backed alt-right platforms to Japanese imageboard
systems, anarcho-communist collectives, political factions, live-coding
algoravers, ‘safe spaces’ for sex workers, gardening forums, personal
blogs, and self-hosting cooperatives. These practices happen in parallel
with the problem of data sharecropping and free labor, and represent
part of the ongoing transformation of what it entails to be a software
user.

The first software users, or users of computational devices, were also
their programmers, and the ones who would then provide the tools and
documentation for others to contribute actively to the development and
usage of these systems.[^13MansouxRoscamAbbingSevenTheses_27] This role was so important that the first
user communities were fully supported and taken care of by hardware
manufacturers. Fast forward a couple of decades and, with the growth of
the computer industry, what it is to be a user has completely changed to
a tamed consumer with limited opportunities to contribute or change the
systems they use, beyond trivial or cosmetic customizations. It is this
situation that helped shape much of the growing popularity of FLOSS in
the 90s, as an adversary of proprietary commercial operating systems for
personal computers, specifically reinforcing earlier concepts of users’
freedom.[^13MansouxRoscamAbbingSevenTheses_28] With the advent of Web 2.0, the situation changed again.
Because of the communicative and ubiquitous dimension of the software
behind corporate social media platforms, vendors have begun to offer a
small window of opportunity to their users to give feedback, as a way to
make their product more engaging and relevant to everyday activities.
Users can usually easily report bugs, suggest new features, or help
shape the platforms’ culture through the conversations they have and
content they share. Twitter is a well-known example of this, where core
features such as the ‘@’ usernames and the ‘\#’ hashtags were first
suggested by users. Forums like Reddit also allow users to set up and
moderate boards, creating distinct and specific communities.

On alternative social media platforms like the Fediverse, particularly
in its early days, these forms of participation move a step further.
Users do not only engage in bug reporting, or help with the creation of
the products’ culture, they also become involved with scrutinizing the
code, debating its effects, and even contributing code back. As the
Fediverse grows in size and encompasses a greater diversity of cultures
and software stacks, the behaviors of this usership are becoming even
more comprehensive. People set up additional nodes in the network and
work on the development of tailored codes of conducts and terms of
services that aid the enforcement of community guidelines for that node.
They also consider how to make these efforts sustainable through funding
via the community.

This said, not all requests for change, including fully functional code
contributions, are accepted by the main developers of the platforms.
This is in part because the larger Fediverse platforms believe in
well-considered default settings that work for diverse majorities,
rather than the old archetypical model of FLOSS, to provide extensive
customization and intricate options that appeal to programmers, but
discourage many others. Thanks to the availability of source code, a
rich ecosystem of modified versions of projects nevertheless exists, to
extend, or limit, certain features while retaining a degree of
compatibility with the wider network. Debates over the merits of
features and the modified software they generate foster further
discussion over the direction of such projects, which in turn leads to
increased attention around their governance.

To be sure, these developments are neither new nor unique to the
Fediverse. The way service facilitators are supported on the Fediverse,
for example, is analogous to the way in which content creators on
streaming platforms in gaming communities are supported by their
audience. Calls for better governance of software projects are also
ongoing in FLOSS communities more widely. The development of codes of
conduct (a key document for Fediverse instances to lay out their vision
of their community and politics) was introduced in various FLOSS
communities in the early 10s, in response to systematic misogyny and
the exclusion of minorities from FLOSS spaces both on- and offline.[^13MansouxRoscamAbbingSevenTheses_29]
Codes of conduct also serve the need for generative forms of conflict
resolution across cultural and language barriers.

Likewise, many of the moderation and community management practices seen
in the Fediverse have been informed by experiences on other platforms,
by the successes and failures of other tools and systems. The synthesis
and coordination of all these practices has become increasingly visible
in the Fediverse. In turn, issues and approaches represented in the
Fediverse set a precedent for other FLOSS projects, encouraging
transformation and discussions that were until now limited or difficult
to initiate.

It is obviously not the case, given the diversity of usership models,
that the entirety of the Fediverse operates along these lines. The
developments described above do though suggest how many models of
usership are yet to be discovered and how the Fediverse is a productive
environment for their trial. The evolving nature of usership on the
Fediverse shows how much space there is between the stereotypical
extremes of the surveillance capitalist model and the self-inflicted
martyrdom of free-labor-powered platforms. This has implications for the
role of users in relation to alternative social media, as well as for
the development of FLOSS culture.[^13MansouxRoscamAbbingSevenTheses_30]

## 7. The Fediverse as the End of Free/Libre and Open Source Software as We Know It

Until now, the vast majority of discussions around FLOSS licensing have
remained locked in a tiresome comparison between free software’s
emphasis on user ethics versus the open source approach based on
economics.[^13MansouxRoscamAbbingSevenTheses_31] Whether motivated by ethics or economics, both free
software and open source software share the ideal that their position is
superior to closed source and proprietary modes of production. However
in both cases, the foundational liberal drive at the base of these
ethical and economic perspectives is rarely challenged. This drive is
deeply rooted in a Western context that over the past few decades has
favored individual freedom in the form of liberalism and libertarianism
at the expense of equality and care. Questioning this drive is a pivotal
step, as this would open up discussions about other ways to approach the
writing and circulation of, and access to, source code. By extension
this would stop the pretension that these practices are either
apolitical, universal, or neutral. Unfortunately, such discussions have
been difficult to facilitate for reasons that go beyond the dogmatic
nature of both free and open source software agendas. In fact they have
been inconceivable because one of the most important aspects of FLOSS is
that it was conceived as non-discriminatory in nature. To be sure, with
non-discriminatory, we refer to FLOSS licensing, that permits anyone to
make use of a FLOSS source code for any purpose.

There have been some efforts to try to tackle this problem, for example
at the level of licensing – making discriminatory licenses to protect
worker-owned productions, or to exclude use by the military and
intelligence services.[^13MansouxRoscamAbbingSevenTheses_32] These efforts were negatively received
because of the non-discriminatory baseline of FLOSS and its discourse.
To make things worse, the main concern of FLOSS advocacy has
historically been about widespread adoption in administration,
education, professional, and commercial environments, and
depoliticization was seen to be key to achieving this goal. However more
recently, the belief in, or the strategy of depoliticization has started
to suffer in several ways.

First, the rise of this new kind of usership meant a new questioning of
the archetypal models of governance of FLOSS projects, such as the
benevolent dictator. Consequently, several long-standing FLOSS projects
have been pressured to adopt accountability structures and migrate to
community-oriented forms of governance such as co-ops or associations.
Second, licenses now tend to be combined with other textual documents
like copyright transfer agreements, terms of services, and codes of
conduct. These documents are used to shape the community, make their
ideological alignment clearer, and try to prevent manipulation and
misunderstanding around vague notions like openness, transparency, and
freedom. Third, the strong political coloring of source code challenges
the existing understanding of FLOSS. As previously mentioned, some of
these efforts are driven by the desire to avoid the censorship and
control of corporate social media platforms, while others explicitly
seek to develop software for anti-fascist use. These efforts not only
dispute the universality and global usefulness of large, general social
media platforms, they also interrogate the supposed universality and
neutrality of software. This is particularly true when software comes
with politically explicit complementary terms, codes, and agreements for
their users and developers to accept.

With its relatively diverse constituency of users, developers, agenda,
software, and ideologies, the Fediverse is gradually becoming the most
relevant system for the articulation of new forms of FLOSS critique. The
Fediverse has become a site where traditional notions about FLOSS are
confronted and revised by people who understand its use as part of a
wider set of practices that challenge the status quo. Sometimes this
happens in a reflective, discursive way across several communities,
sometimes through the materialization of experiments and projects that
directly challenge FLOSS as we know it. It has become the sprawling site
where constructive critiques of FLOSS and a longing for its
reimagination are most vivid. In its current state, FLOSS culture feels
like a patched-up collection of irreconcilable pieces from another era,
and it is urgent to revaluate many of its characteristics that have been
taken for granted. If we can accept the much-needed sacrilege of
thinking of free software without free software, it remains to be seen
what could fill the void left by its absence.

[^13MansouxRoscamAbbingSevenTheses_1]: See Geert Lovink, *Sad by Design: On Platform Nihilism*, London: Pluto Press, 2019.

[^13MansouxRoscamAbbingSevenTheses_2]: Throughout this text we use ‘corporate social media’ and
    ‘alternative social media’ as defined in Robert W. Gehl, ‘The Case
    for Alternative Social Media’, *Social Media + Society* 1.2 (22
    September 2015),
    <https://journals.sagepub.com/doi/pdf/10.1177/2056305115604338>.

[^13MansouxRoscamAbbingSevenTheses_3]: Danyl Strype, ‘A Brief History of the GNU Social Fediverse and
    “The Federation”’, *Disintermedia*, 1 April 2017,
    <https://www.coactivate.org/projects/disintermedia/blog/2017/04/01/a-brief-history-of-the-gnu-social-fediverse-and-the-federation>.

[^13MansouxRoscamAbbingSevenTheses_4]: For an exploration of \#GamerGate and toxic technocultures, see
    Adrienne Massanari, ‘\#Gamergate and The Fappening: How Reddit’s
    Algorithm, Governance, and Culture Support Toxic Technocultures’,
    *New Media & Society* 19.3 (2016): 329-346.

[^13MansouxRoscamAbbingSevenTheses_5]: Due to its distributed nature it is not easy to get exact numbers
    on the amount of users but a few projects do exist that try to
    quantify the network: The Federation, <https://the-federation.info>;
    Fediverse Network <https://fediverse.network>; Mastodon Users,
    *Bitcoin Hackers*, <https://bitcoinhackers.org/@mastodonusercount>.

[^13MansouxRoscamAbbingSevenTheses_6]: For an example of such early relationship, see Michael Rossman,
    ‘Implications of Community Memory’, *SIGCAS – Computers & Society*
    6.4 (1975): 7-10.

[^13MansouxRoscamAbbingSevenTheses_7]: Aymeric Mansoux, ‘Surface Web Times’, *MCD* 69 (2013): 50-53.

[^13MansouxRoscamAbbingSevenTheses_8]: Burcu Gültekin Punsmann, ‘What I learned from three months of
    Content Moderation for Facebook in Berlin’, *SZ Magazin*, 6 January
    2018,
    <https://sz-magazin.sueddeutsche.de/internet/three-months-in-hell-84381>.

[^13MansouxRoscamAbbingSevenTheses_9]: For source code, see Raddle, <https://raddle.me/>; Postmill,
    ‘GitLab’, <https://gitlab.com/postmill/Postmill>; Voat,
    <https://voat.co/>; Voat, ‘GitLab’, <https://github.com/voat/voat>.

[^13MansouxRoscamAbbingSevenTheses_10]: Gabriella Coleman, ‘The Political Agnosticism of Free and Open
    Source Software and the Inadvertent Politics of Contrast’,
    *Anthropological Quarterly* 77.3 (2004): 507-519.

[^13MansouxRoscamAbbingSevenTheses_11]: For a more thorough discussion on the multifaceted enabling
    aspect of openness but also a comment on openwashing, see Jeffrey
    Pomerantz and Robin Peek, ‘Fifty Shades of Open’, *First Monday*
    21.5 (2016),
    <https://firstmonday.org/ojs/index.php/fm/article/view/6360/5460>.

[^13MansouxRoscamAbbingSevenTheses_12]: As an example of the discourse against defederating see the
    comment by Kaiser to the blog entry by robek ‘rw’ world, ‘Mastodon
    Social Is THE Twitter Alternative For…’, *Robek World*, 12 January
    2017,
    <https://robek.world/internet/mastodon-social-is-the-twitter-alternative-for/>.

[^13MansouxRoscamAbbingSevenTheses_13]: Around the time Gab joined the network, all Fediverse statistics
    jumped by approximately one million users. These numbers, like all
    Fediverse usage numbers, are contested. For context, see John
    Dougherty and Michael Edison Hayden, ‘“No Way” Gab has 800,000
    Users, Web Host Says’, *Southern Poverty Law Center*, 14 February
    2019,
    <https://www.splcenter.org/hatewatch/2019/02/14/no-way-gab-has-800000-users-web-host-says>
    and emsenn (graden and unionize), Mastodon post, 10 August 2019,
    04:51, <https://tenforward.social/@emsenn/102590414178698570>.

[^13MansouxRoscamAbbingSevenTheses_14]: For an exhaustive introduction to Mouffe’s writing, see Chantal
    Mouffe, *Agonistics: Thinking the World Politically*, London: Verso,
    2013.

[^13MansouxRoscamAbbingSevenTheses_15]: Andrew Torba, ‘Moving to the ActivityPub protocol as our base
    allows us to get into mobile App Stores without even having to
    submit and get approval of our own apps, whether Apple and Google
    like it or not’, post to Gab,
    <https://gab.com/a/posts/VnZRendFcDM1alBhNm9QeWV4d0xidz09>, las
    accessed May 2019.

[^13MansouxRoscamAbbingSevenTheses_16]: David Garcia, ‘The Revenge of Folk Politics’,
    *transmediale/journal* 1 (2018),
   <https://transmediale.de/content/the-revenge-of-the-folk-politics>.

[^13MansouxRoscamAbbingSevenTheses_17]: hbsc & friends, ‘Have You Considered the Alternative?’, Homebrew
    Server Club, 9 March 2017,
    <https://homebrewserver.club/have-you-considered-the-alternative.html>.

[^13MansouxRoscamAbbingSevenTheses_18]: Sarah Jamie Lewis (ed), *Queer Privacy: Essays From The Margin Of
    Society,* Victoria, British Columbia: Lean Pub/Mascherari Press,
    2017, p. 2.

[^13MansouxRoscamAbbingSevenTheses_19]: Shoshana Zuboff, *The Age of Surveillance Capitalism: The Fight
    for a Human Future at the New Frontier of Power*, New York:
    PublicAffairs, 2019.

[^13MansouxRoscamAbbingSevenTheses_20]: Silvio Lorusso, *Entreprecariat – Everyone Is an Entrepreneur.
    Nobody Is Safe*, Onomatopee: Eindhoven, 2019.

[^13MansouxRoscamAbbingSevenTheses_21]: For an example of a frequently circulated user-generated
    introduction, see Noëlle Anthony, Joyeusenoelle/GuideToMastodon,
    2019, <https://github.com/joyeusenoelle/GuideToMastodon>.

[^13MansouxRoscamAbbingSevenTheses_22]: Throughout this text we use ‘corporate social media’ and
    ‘alternative social media’ as defined in Gehl, ‘The Case for
    Alternative Social Media’.

[^13MansouxRoscamAbbingSevenTheses_23]: For an ongoing survey of these issues, see Pervasive Labour Union
    Zine, <https://ilu.servus.at>.

[^13MansouxRoscamAbbingSevenTheses_24]: Even though framed in the context of Tumblr, for a thorough
    discussion on the tension between digital labour, post-digital
    communities, and activism, see Cassius Adair and Lisa Nakamura, ‘The
    Digital Afterlives of *This Bridge Called My Back:* Woman of Color
    Feminism, Digital Labor, and Networked Pedagogy’, *American
    Literature* 89.2 (2017): 255-278.

[^13MansouxRoscamAbbingSevenTheses_25]: ‘Mastodon’, *Open Collective*,
    <https://opencollective.com/mastodon>.

[^13MansouxRoscamAbbingSevenTheses_26]: For elements of discussion on the public funding of free
    software, as well as some analysis of early draft laws regarding the
    access of source code for software purchased with public money, see
    Jesús M. González-Barahona, Joaquín Seoane Pascual and Gregorio
    Robles, *Introduction to Free Software*, Barcelona: Universitat
    Oberta de Catalunya, 2009.

[^13MansouxRoscamAbbingSevenTheses_27]: For instance, see Atsushi Akera, ‘Voluntarism and the Fruits of
    Collaboration: The IBM UserGroup, Share’, *Technology and Culture*
    42.4 (2001): 710-736.

[^13MansouxRoscamAbbingSevenTheses_28]: Sam Williams, *Free as in Freedom: Richard Stallman’s Crusade for
    Free Software*, Farnham: O’Reilly, 2002.

[^13MansouxRoscamAbbingSevenTheses_29]: Femke Snelting, ‘Codes of Conduct: Transforming Shared Values
    into Daily Practice’, in Cornelia Sollfrank (ed) *The Beautiful
    Warriors: Technofeminist Praxis in the 21st Century*, Colchester:
    Minor Compositions, 2019, pp. 57-72.

[^13MansouxRoscamAbbingSevenTheses_30]: Dušan Barok, *Privatising Privacy: Trojan Horse in Free Open
    Source Distributed Social Platforms*, master thesis, Networked
    Media, Piet Zwart Institute, Rotterdam/Netherlands, 2011.

[^13MansouxRoscamAbbingSevenTheses_31]: See the Stallman-Ghosh-Glott mail exchange on the FLOSS survey,
    ‘Two Communities or Two Movements in One Community?’, in Rishab
    Aiyer Ghosh, Ruediger Glott, Bernhard Krieger and Gregorio Robles,
    ‘Free/Libre and Open Source Software: Survey and Study’, FLOSS final
    report, International Institute of Infonomics, University of
    Maastricht, Netherlands, 2002,
    <http://flossproject.merit.unu.edu/floss1/stallman.html>.

[^13MansouxRoscamAbbingSevenTheses_32]: For instance, see Felix von Leitner, ‘Mon Jul 6 2015’, *Fefes
    Blog*, 6 July 2015, <https://blog.fefe.de/?ts=ab645846>.
