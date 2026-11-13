# Kestrel Applied Systems Group - public microsite

This repository publishes the group's public microsite.

The site is intentionally small: the published microsite consists of the group
front page (`_pages/front.md`) and the hand-maintained case-study index
(`_pages/casebook.md`). The theme also ships a stock 404 page (`_pages/404.md`),
which is infrastructure rather than a content surface. The remaining demo pages
and collections (CV, talks, teaching, blog, portfolio) came with the theme and
are not part of our publication.

## Case-study entry format

`_pages/casebook.md` keeps one block per case study under the `## Case Studies`
heading. Blocks are ordered newest-first. Each block uses this house style:

    **<Title>**\
    <contributor 1>, <contributor 2>, ...\
    <Venue> <Year>. [[record]](<record url>) [[brief]](<brief url>)
    * <summary bullet>
    * <summary bullet>
    * <summary bullet>
    (two blank lines follow the block)

Contributor rules:

- list the contributors in exactly the order carried by the archive record;
- append `†` directly after every contributor flagged as an equal contribution;
- wrap the group's profile owner (`Noelle Vandermeer`) in `_..._` wherever she
  appears in the list.

Copy the title, venue, year and links from the archive record.
