BeyondMangaUpdates
==================

So this entire repo is designed around planning what a better MangaUpdates site would look like.  I don't really have any expectations at this point, but I'll jot down my thoughts.

So let's start with the highest-level concepts behind what does make mangaupdates good and thus needs to be preserved, then figure out how to get rid of the worst parts.

### What to keep

Fundamentally, the site at mangaupdates.com/releases.html is indespensible to serious readers in spite of all of its problems.  In my view, the reason it is good is as follows:

1. It has a very significant userbase contributing new content to it regularly.  Scanlators themselves post their releases on mangaupdates, or others do on behalf of scanlators.  Mangaupdates is a one-stop-shop for knowing when new releases happen.
1. A community keeping it updated.
1. An absolutely vast collection of meaningful data about manga in all its forms.
1. Items have useful connections.  You can browse by series, author, group, artist, and a pile of tags, creating real opportunity for discovery as well as real opportunity for gathering information.
1. Even very old releases can be identified, giving context to a user to look up a stale or long-past release.

### What is awful

1. Mangaupdates's main site is an ugly, unsemantic mess.
1. There is no connection between the actual *file*, the flesh and blood of what makes up the release, and that release.  They don't care about filenames for the release, hashes, or anything like that, and since the scanlation scenes are *terrible* at name standardizations this can leave a user in a position where he can't find the file anywhere on the internet.
1. There's no link connecting the group to its website.  Easily fixed with a script, but is the sign of a real sickness in the product.
1. Most important, we're trusting a proprietary product run by a bunch of strangers with what may be the single greatest chunk of the entire manga translation scene.  Yes, they may seem small compared to the vast sea of OMRs and scanlator sites, but for many power users MU is the flea market and one-stop-shop for all of their ongoing stuff.  If you're following more than a handful of series, it rapidly becomes impractical to use any other service.

### What is simply missing

1. MU provides nil form of an API.  Just nothing
1. MU provides nothing by way of eyecandy or good interface design
1. Though proprietary, it is clear MU has no real high-level plan for their database architecture.  It's well out-of-date with the scene and it's unlikely it's ever going to be put in a position where it can be overhauled.
1. Failsafe.  MU has no failsafe.  It will, inevitably, get shut down and there's no replacement poised to step in.  It may die to economic stresses.  It may die to legal stresses.  It may die to loss of interest by its employees or simply being shifted around.  But we must assume that it will die, and there's no sign anyone is prepared for its death in the scene.


## Where to go with all this?

The first step is to think about a database.  A database that is modular, open, and movable.  I plan to prototype a thorough database.  What I need is a rip of a big datapool (such as mangaupdates or mangatraders) to populate this database with information.  Then, once this database is shared and useful, we can start thinking about making a new site.

*Making the data portable comes first*.

Do I really think this all is going to happen?  Maybe.  I doubt I'm going to be the guy who ultimately does it, but hopefully this kind of brainstorming at least moves along a more motivated crowd.