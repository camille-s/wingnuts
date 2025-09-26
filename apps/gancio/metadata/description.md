A shared agenda for local communities.

Last release 1.27.0 - 21 Jun 2025

    2.0 is coming

    After considerable effort, version 2.0 is about to arrive: a complete rewrite of the project to eliminate accumulated technical debt and establish a cleaner, more modern and manageable code base across the entire stack. More details can be found in the CHANGELOG.
    With the release, I started writing better usage and code documentation to support future developments and onboarding, which I have currently placed in a subsection of the website.
    The release is still in alpha and there are still some incompatibilities, so test it via Docker or directly from the code, open issues, but please do not update yet.


Our effort in this project is not to build an alternative that mimics mainstream solutions, we respond to different needs. The assumption here is that technology is neither good nor bad, nor is it neutral. It does not depend (only) on how it is used.

Building software means taking a stand, making decisions, choices. These choices start from a precise look at reality, from specific needs and ends implementing specific features, choose default values, simplify some flow and patterns while making difficult others.
Small is better

The use case we have in mind is that of small nodes tied either to a specific territory or at the limit a small thematic community. This choice is not very fashionable: for a long time in IT one of the priority values is scalability, this is because you are forced to imagine platforms that are suitable for hosting millions of people, millions of customers.
Structuring a project in this way simply means creating a lot of power and centralizing it in a specific place.
Long story short, even if fb/insta/tiktok was in our hands it wouldn’t work, it’s not only the wrong owner, it’s just the tool that wasn’t designed with decent values.
When we started developing gancio, we were asked for a national platform, we preferred to imagine small nodes for local communities.
Focus on content

All people looking at the home page see the same events, there are no personal timelines. This is not an ego-friendly platform. Nowhere on gancio appears the identity of who published the event, not even under a nickname, not even to administrators.
The reason for this is not only to avoid gamification but also to consider the use case we’re all going into of states increasingly intolerant of displays of dissent. That’s also the reason why adding events by anonymous people is a feature enabled by default.
Fuck walled garden

We don’t care about making hits so we export events in many ways: via RSS feeds, via global or individual ics, allowing you to embed list of events or single event via iframe or webcomponent on other websites, via ActivityPub, microdata and microformat.
Unlike GAFAM that does everything to keep users and data about them, we believe that information, like people, must be free. People can stay updated without necessarily going through the site because we don’t need your attention or to sell you anything.
License

Gancio is distributed by an AGPL-3.0 Licence.