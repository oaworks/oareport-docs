---
description: 'Internal: ready-made blocks for organization-specific product updates.'
hidden: true
noIndex: true
noRobotsIndex: true
---

# Templates

Ready-made blocks for product updates that only one organization should see. Copy the whole block for the organization you need (from its condition down to the end of the update), paste it into the Product updates page in date order, then replace the date, tag, title, and text.

Before merging, check the update with the organization’s link, e.g. `https://about.oa.report/about-oa.report/product-updates?visitor.org=wellcome`.

## Gates Foundation

{% if visitor.claims.unsigned.org === "gates-foundation" %}
{% updates format="full" %}
{% update date="2026-11-10" tags="changed" %}
## _For your organization:_ Update title

Update text.
{% endupdate %}
{% endupdates %}
{% endif %}

## Michael J. Fox Foundation

{% if visitor.claims.unsigned.org === "michael-j-fox-foundation" %}
{% updates format="full" %}
{% update date="2026-11-10" tags="changed" %}
## _For your organization:_ Update title

Update text.
{% endupdate %}
{% endupdates %}
{% endif %}

## Robert Wood Johnson Foundation

{% if visitor.claims.unsigned.org === "rwjf" %}
{% updates format="full" %}
{% update date="2026-11-10" tags="changed" %}
## _For your organization:_ Update title

Update text.
{% endupdate %}
{% endupdates %}
{% endif %}

## Templeton World Charity Foundation

{% if visitor.claims.unsigned.org === "templeton-world-charity-foundation" %}
{% updates format="full" %}
{% update date="2026-11-10" tags="changed" %}
## _For your organization:_ Update title

Update text.
{% endupdate %}
{% endupdates %}
{% endif %}

## Wellcome

{% if visitor.claims.unsigned.org === "wellcome" %}
{% updates format="full" %}
{% update date="2026-11-10" tags="changed" %}
## _For your organization:_ Update title

Update text.
{% endupdate %}
{% endupdates %}
{% endif %}

## Several organizations

Edit the list to the organizations you need.

{% if ["gates-foundation", "wellcome"].includes(visitor.claims.unsigned.org) %}
{% updates format="full" %}
{% update date="2026-11-10" tags="changed" %}
## _For your organization:_ Update title

Update text.
{% endupdate %}
{% endupdates %}
{% endif %}

## Any client organization

Shown to anyone arriving from their OA.Report, hidden from the public.

{% if !!visitor.claims.unsigned.org %}
{% updates format="full" %}
{% update date="2026-11-10" tags="changed" %}
## _For your organization:_ Update title

Update text.
{% endupdate %}
{% endupdates %}
{% endif %}
