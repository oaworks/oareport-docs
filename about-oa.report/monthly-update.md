---
description: >-
  A monthly summary of all changes to OA.Report, newest first, covering new
  features, improvements, removals, and fixes.
hidden: true
---

# Monthly update

{% hint style="info" %}
For notable changes as they’re released, see the [Changelog](product-updates.md).
{% endhint %}

### September & October 2026

#### Added

* Breakdown tables in Explore (e.g., by journal, author, or year) can now be sorted by any column, for tables of up to 2,000 rows. Percentage columns sort by percentage or count, depending on which is displayed.
* A **Reset sort** button in Explore, which is activated when any table has been sorted by the user, and returns it to its default order (i.e., by publication count or by year).

#### Changed

* Data availability statement (DAS) Insight card percentages now account for the roughly six months it takes to review DAS. For date ranges that include the last six months, figures are projected from earlier publications that have had time to be reviewed. For example, in late October 2026, viewing 2026 gives a projection based on publications from January to April 2026.
* Help text across the report has been reviewed and rewritten to be clearer, more concise, and more consistent, with redundant text removed. Explanations now appear where they’re most useful, such as your organisation’s own policy criteria in coverage and compliance tooltips, and Insight cards and Explore tables now make clearer what each figure counts. Data availability statement (DAS) definitions also note that recent figures may take up to six months to be complete.
* Tooltips work more consistently across the report: definitions open on click, and hover tooltips appear after a short delay to avoid distraction.

#### Removed

* Data, code, and identifier columns have been removed from Explore breakdown tables, including those for shared and Open Data or code, ORCIDs, RORs, and grant DOIs.

#### Fixed

* “Add filter” only shows fields available in your report, rather than non-existent filters.
* Emails drafted from Actions are no longer cut short when a publication title or author name contains special characters such as & or #.
* The Publications column tooltip in Explore now reflects the correct active filter; it was previously showing the wrong help text.
* Info tooltips in Explore are now fully accessible by keyboard and screen reader, and info icons have better colour contrast (improved accessibility).
