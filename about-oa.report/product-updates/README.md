---
description: >-
  This page lists notable changes to OA.Report as they’re released, newest
  first, including any change that affects your figures.
---

# Product updates

{% updates format="full" %}
{% if visitor.claims.unsigned.org === "wellcome" %}
{% update date="2026-11-16" tags="wellcome-trust,added" %}
## 17,000 works re-added

Adding \~17,0000 works previously excluded due to concerns about high rates of false positives in Europe PMC data. This batch contains works we have high confidence are funded by Wellcome including based on Crossref metadata, mentions of Wellcome in acknowledgement statements, and excludes works where we can see the Grant ID Europe PMC provided is attributed to other funders in other sources.

This may cause other figures to vary for a few days while other processes catch up.
{% endupdate %}
{% endif %}

{% update date="2026-11-16" tags="changed" %}
## Explore breakdown tables can be sorted at larger sizes

<figure><img src="../../.gitbook/assets/CleanShot 2026-11-15 at 21.45.57.gif" alt=""><figcaption></figcaption></figure>

Explore breakdown tables (i.e., aggregate tables such as by subject, journal, or year; not article-level ones) of any size can now be sorted, up from the previous limit of 2,000 rows. The one exception is percentage columns in tables of over 40,000 rows, which currently only affects the largest author tables; however, switching to the Count view enables their sorting.

Rows with the same value now stay in the order of the previously selected sort.
{% endupdate %}

{% if visitor.claims.unsigned.org === "michael-j-fox-foundation" %}
{% update date="2026-11-04" tags="added,michael-j.-fox-foundation" %}
## Open Access preprint figure added to Insights

<figure><img src="../../.gitbook/assets/CleanShot 2026-11-15 at 21.42.29@2x.png" alt=""><figcaption></figcaption></figure>
{% endupdate %}
{% endif %}

{% update date="2026-11-04" tags="changed" %}
## Data availability statement figures account for review time

<figure><img src="../../.gitbook/assets/CleanShot 2026-10-28 at 19.53.43.gif" alt=""><figcaption></figcaption></figure>

Data availability statement (DAS) Insight card percentages now account for the roughly six months it takes to review DAS. For date ranges that include the last six months, figures are projected from earlier publications that have had time to be reviewed.

For example, in late October 2026, viewing 2026 gives a projection based on publications from January to April 2026.
{% endupdate %}

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
{% endupdates %}

{% updates format="full" %}
{% update date="2026-10-06" tags="added,removed" %}
## Explore breakdown tables can be sorted by any column

<figure><img src="../../.gitbook/assets/CleanShot 2026-10-27 at 23.30.49.gif" alt=""><figcaption></figcaption></figure>

Breakdown tables in Explore (e.g., by journal, author, or year) can now be sorted by any column, for tables of up to 2,000 rows. Percentage columns sort by percentage or count, depending on which is displayed.

<figure><img src="../../.gitbook/assets/CleanShot 2026-10-27 at 23.32.22.gif" alt=""><figcaption></figcaption></figure>

A Reset sort button appears once a table has been sorted, and returns it to its default order (i.e., by publication count or by year).

## Columns removed from Explore breakdown tables

To declutter Explore tables and focus on accurate and up-to-date figures, data, code, and identifier columns have been removed. These include shared data and code, Open Data and Open Code, ORCIDs, RORs, and grant DOIs.
{% endupdate %}
{% endupdates %}
