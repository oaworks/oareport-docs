# Data

{% hint style="danger" %}
This data schema is in alpha and can change with no notice.
{% endhint %}

## `doi`

The DOI for the work\
_string_

Source: [OpenAlex ](https://docs.openalex.org/about-the-data/work#title)| [Crossref](https://crossref.org)\
Updated: Daily (paid), occasionally (free)

## `title`

The title of this work\
_string_

`title: "Subscribe to Open: A practical approach for converting subscription journals to open access"`\
\
Source: [OpenAlex](https://docs.openalex.org/about-the-data/work#title-1)\
Updated: Daily (paid), occasionally (free)

PMCID

journal\_oa\_type

author\_email\_name

email

cited\_by\_count

has\_oa\_locations\_embargoed

has\_repository\_copy

is\_oa

is\_retracted

issn

issue

journal

oa\_status

published\_date

published\_year

publisher

subject

subtitle

updated

volume

publisher\_url\_for\_pdf

publisher\_version

repository\_license

repository\_url

repository\_url\_for\_pdf

repository\_url\_in\_pmc

repository\_version

## `can_archive`

Can the work be self-archived in a repository?\
_Boolean_

`can_archive: "true"`

Source: [ShareYourPaper Permissions](https://shareyourpaper.org/permissions)\
Updated: Daily (paid), occasionally (free)

## `version`

What version of the work can be self-archived in a repository?\
_String_

`can_archive: "acceptedVersion"`

Values are based on the [DRIVER Guidelines versioning scheme.](https://wiki.surfnet.nl/display/DRIVERguidelines/DRIVER-VERSION+Mappings)

Source: [ShareYourPaper Permissions](https://shareyourpaper.org/permissions)\
Updated: Daily (paid), occasionally (free)

## `funder`

{% hint style="info" %}
This section is a stub. Refer to our source, [Crossref, for detailed documentation.](https://github.com/CrossRef/rest-api-doc)
{% endhint %}

### `name`

### `award`

## `authorships`

{% hint style="info" %}
This section is a stub. Refer to our source, [OpenAlex, for detailed documentation](https://docs.openalex.org/about-the-data/work#the-authorship-object).
{% endhint %}

## `concepts`

{% hint style="info" %}
This section is a stub. Refer to our source, [Crossref, for detailed documentation.](https://github.com/CrossRef/rest-api-doc)
{% endhint %}

## supplements

### `has_open_data`

Asserts if a paper has created data and that data is licensed cc-by or cc-0.\
_Boolean_

`has_open_data: true`

Source: Remixed from Dataseer, Unpaywall, manual collection by OA.Works.\
Updated: As requested (paid)

### `publisher_license_best`

### `repository_license_best`

### `fundingstatement`

### `has data availability statement`

### `has_made_code`

### `is_preprint`

### `has_made_data`

### `has_open_code`

### `has_open_data`

### `has_reused_data`

### `has_shared_code`

### `has_shared_data`

### `apc_cost`

### `invoice_date`

### `invoice_number`

### `invoice_year`

## Organization specific supplements

### `grantid*`

### `is_compliant*`

### `is_new*`

### `program*`

### `is_approved_repository*`

### `financial_disclosures*`

### `funding-retracted*`

## Other

Some fields are used only for internal use, and so aren't documented above.
