---
description: >-
  This page lists notable changes to OA.Report as they’re released, newest
  first, including any change that affects your figures.
---

# Product updates

{% if visitor.claims.unsigned.org === "michael-j-fox-foundation" %}

{% endif %}

{% updates format="full" %}
{% if visitor.claims.unsigned.org === "gates-foundation" %}
{% update date="2026-11-03" tags="fixed,gates-foundation" %}
## VeriXiv preprints deduplicated

150 VeriXiv preprints have been removed where a more recent version of the same preprint existed. Each VeriXiv preprint is now counted once.
{% endupdate %}
{% endif %}

{% if visitor.claims.unsigned.org === "michael-j-fox-foundation" %}
{% update date="2026-10-28" tags="changed,michael-j.-fox-foundation" %}
## Grant ID update

Grant ID information has been improved across all exported data: 233 new grant IDs were added, and 666 records now have a recognized grant ID, more than double the total. This increases policy coverage by approximately 50%.
{% endupdate %}
{% endif %}

{% update date="2026-10-27" tags="changed" %}
## Data availability statement figures account for review time

<figure><img src="../../.gitbook/assets/CleanShot 2026-10-28 at 19.53.43.gif" alt=""><figcaption></figcaption></figure>

Data availability statement (DAS) Insight card percentages now account for the roughly six months it takes to review DAS. For date ranges that include the last six months, figures are projected from earlier publications that have had time to be reviewed.

For example, in late October 2026, viewing 2026 gives a projection based on publications from January to April 2026.
{% endupdate %}
{% endupdates %}

{% updates format="full" %}
{% update date="2026-10-06" tags="added,removed" %}
## Explore breakdown tables can be sorted by any column

<figure><img src="../../.gitbook/assets/CleanShot 2026-10-27 at 23.30.49.gif" alt=""><figcaption></figcaption></figure>

Breakdown tables in Explore (e.g., by journal, author, or year) can now be sorted by any column, for tables of up to 2,000 rows. Percentage columns sort by percentage or count, depending on which is displayed.

<figure><img src="../../.gitbook/assets/CleanShot 2026-10-27 at 23.32.22.gif" alt=""><figcaption></figcaption></figure>

A Reset sort button appears once a table has been sorted, and returns it to its default order (i.e., by publication count or by year).

## Columns removed from Explore breakdown tables

To declutter Explore tables and focus on figures we can keep accurate and up to date, we’ve removed the data, code, and identifier columns. These include shared data and code, Open Data and Open Code, ORCIDs, RORs, and grant DOIs.
{% endupdate %}
{% endupdates %}
