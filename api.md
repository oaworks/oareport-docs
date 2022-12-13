# API



{% hint style="danger" %}
This API is in alpha and can change with no notice.
{% endhint %}

{% hint style="warning" %}
Coming soon: completed descriptions for all routes
{% endhint %}

{% swagger method="get" path="" baseUrl="https://api.oa.works/report/works/{doi}" summary="get single work" expanded="true" %}
{% swagger-description %}

{% endswagger-description %}

{% swagger-response status="200: OK" description="" %}
{% code title="some keys omitted for brevity" %}
```json
{
  "supplements": [
    {
      "orgs": [
        "climate change and biodiversity"
      ],
      "sheets": [
        "ipcc-ar6-wg2__climate"
      ],
      "ror": "",
      "paid": ""
    }
  ],
  "orgs": [
    "climate change and biodiversity"
  ],
  "paid": [],
  "doi": "10.1038/35002501",
  "DOI": "10.1038/35002501",
  "subject": [
    "Multidisciplinary"
  ],
  "volume": "403",
  "published_year": 2000,
  "issue": "6772",
  "publisher": "Springer Science and Business Media LLC",
  "published_date": "2000-02-01",
  "title": "Biodiversity hotspots for conservation priorities",
  "journal": "Nature",
  "crossref_license_url_tdm": "http://www.springer.com/tdm",
  "crossref_is_oa": false,
  "oa_status": "closed",
  "has_repository_copy": false,
  "has_oa_locations_embargoed": false,
  "can_archive": true,
  "version": "acceptedVersion",
  "journal_oa_type": "transformative",
  "oadoi_is_oa": false,
  "is_oa": false
  
}
```
{% endcode %}
{% endswagger-response %}
{% endswagger %}

{% swagger method="get" path="" baseUrl="https://api.oa.works/report/works/" summary="get list of works" expanded="true" %}
{% swagger-description %}

{% endswagger-description %}

{% swagger-parameter in="query" name="q" type="String" %}

{% endswagger-parameter %}

{% swagger-parameter in="query" name="sort" type="String" %}

{% endswagger-parameter %}

{% swagger-parameter in="path" name="terms/{key}" type="String" %}

{% endswagger-parameter %}

{% swagger-parameter in="path" name="count" type="String" %}

{% endswagger-parameter %}

{% swagger-parameter in="query" name="size" type="String" %}

{% endswagger-parameter %}

{% swagger-parameter in="query" name="includes" type="String" %}
Denotes what keys you want in your response.



Comma separated listed of keys, as listed in [data](data/ "mention")
{% endswagger-parameter %}

{% swagger-parameter in="path" name="sum/{key}" type="String" %}

{% endswagger-parameter %}

{% swagger-response status="200: OK" description="" %}
{% code title="" %}
```json
{
  "took": 3,
  "timed_out": false,
  "_shards": {
    "total": 1,
    "successful": 1,
    "skipped": 0,
    "failed": 0
  },
  "hits": {
    "total": 1238652,
    "max_score": 1,
    "hits": [
      {
        "_index": "paradigm_report_works",
        "_type": "_doc",
        "_id": "10.1016_j.biocon.2016.06.013",
        "_score": 1,
        "_source": {
          "supplements": [
            {
              "orgs": [
                "Robert Wood Johnson Foundation"
              ],
              "sheets": [
                "custom_keys__rwjf"
              ],
              "ror": "02ymmdj85",
              "paid": true,
              "publisher_license_crossref": "cc-by-nc-nd",
              "is_preprint": false,
              "publisher_simple": "elsevier",
              "publisher_license_best": "cc-by-nc-nd",
              "repository_license_best": "cc-by-nc-nd"
            }
          ],
          "doi": "10.1016/j.biocon.2016.06.013",
          "subject": [
            "Nature and Landscape Conservation",
            "Ecology, Evolution, Behavior and Systematics"
          ],
          "volume": "213",
          "published_year": 2017,
          "publisher": "Elsevier BV",
          "published_date": "2017-09-01",
          "title": "A vision for global monitoring of biological invasions",
          "journal": "Biological Conservation",
          "crossref_license_url_tdm": "https://www.elsevier.com/tdm/userlicense/1.0/",
          "crossref_license_url_vor": "http://creativecommons.org/licenses/by-nc-nd/4.0/",
          "crossref_is_oa": true,
          "publisher_license": "cc-by-nc-nd",
          "publisher_url_for_pdf": null,
          "publisher_version": "publishedVersion",
          "repository_license": "cc-by-nc-nd",
          "best_oa_location_url": "https://doi.org/10.1016/j.biocon.2016.06.013",
          "best_oa_location_url_for_pdf": null,
          "oa_status": "hybrid",
          "has_repository_copy": true,
          "has_oa_locations_embargoed": false,
          "can_archive": true,
          "version": "acceptedVersion",
          "journal_oa_type": "hybrid",
          "oadoi_is_oa": true,
          "is_oa": true
}
```
{% endcode %}
{% endswagger-response %}
{% endswagger %}

{% swagger method="get" path="" baseUrl="https://api.oa.works/report/works.csv" summary="export a csv of works" expanded="true" %}
{% swagger-description %}
supports all the parameters provided in 

[#get-list-of-works](api.md#get-list-of-works "mention")


{% endswagger-description %}

{% swagger-parameter in="query" name="email" required="true" type="String" %}

{% endswagger-parameter %}

{% swagger-parameter in="query" name="size" type="String" %}

{% endswagger-parameter %}

{% swagger-response status="200: OK" description="" %}
```
https://static.oa.works/export/report_works_8wl6t8lkjkmji2dltjuvf.csv
```
{% endswagger-response %}
{% endswagger %}

{% swagger method="get" path="" baseUrl="https://api.oa.works/report/orgs" summary="get list of organizations" expanded="true" %}
{% swagger-description %}
supports all the parameters provided in 

[#get-list-of-works](api.md#get-list-of-works "mention")


{% endswagger-description %}
{% endswagger %}
