# API

{% hint style="danger" %}
This API is in alpha and can change with no notice.
{% endhint %}

{% swagger method="get" path="" baseUrl="https://api.oa.works/report/works/{doi}" summary="get single work" %}
{% swagger-description %}

{% endswagger-description %}

{% swagger-response status="200: OK" description="doi: "10.1038/35002501", DOI: "10.1038/35002501", subject: [ "Multidisciplinary" ], volume: "403", published_year: 2000, issue: "6772", publisher: "Springer Science and Business Media LLC", published_date: "2000-02-01", title: "Biodiversity hotspots for conservation priorities", journal: "Nature", crossref_license_url_tdm: "http://www.springer.com/tdm", crossref_is_oa: false, oa_status: "closed", has_repository_copy: false, has_oa_locations_embargoed: false, can_archive: true, version: "acceptedVersion", journal_oa_type: "transformative", oadoi_is_oa: false, is_oa: false," %}
```javascript
{
    // Response
}
```
{% endswagger-response %}
{% endswagger %}

{% swagger method="get" path="" baseUrl="https://api.oa.works/report/works/" summary="get list of works" expanded="true" %}
{% swagger-description %}

{% endswagger-description %}

{% swagger-parameter in="query" name="q" %}

{% endswagger-parameter %}

{% swagger-parameter in="query" name="sort" %}

{% endswagger-parameter %}

{% swagger-parameter in="path" name="terms/{key}" %}

{% endswagger-parameter %}

{% swagger-parameter in="path" name="count" %}

{% endswagger-parameter %}

{% swagger-parameter in="path" %}

{% endswagger-parameter %}

{% swagger-parameter in="query" name="size" %}

{% endswagger-parameter %}

{% swagger-response status="200: OK" description="" %}
```javascript
{
    // Response
}
```
{% endswagger-response %}
{% endswagger %}
