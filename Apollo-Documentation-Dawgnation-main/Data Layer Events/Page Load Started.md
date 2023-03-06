# Page Load Started

### 

## Javascript Code
```js
window.dataLayer = window.dataLayer || [];
dataLayer.push({ page_data: null });  // Clear the previous page_data object.
dataLayer.push({
  "event": "page_load_started",
  "detailed_event": "Page Load Started",
    "page_data": {
        "byline": "<byline>",
        "content_id": "<content_id>",
        "content_type": "<content_type>",
        "country": "<country>",
        "language": "<language>",
        "page_location": "<page_location>",
        "page_path": "<page_path>",
        "page_title": "<page_title>",
        "previous_page": "<previous_page>",
        "publication_name": "<publication_name>",
        "publish_date": "<publish_date>",
        "site_section": "<site_section>",
        "site_section2": "<site_section2>",
        "topics": "<topics>",
        "user_group_id": "<user_group_id>"
    },
    "user_data": {
        "user_registration_status": "<user_registration_status>"
    }
});
```

## Variable Definitions

|Path|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|page_data.byline|string|The byline of the page.||||||||
|page_data.content_id|string|The content ID of the page.|T3FAWCMCENGILOUBIU2LY2XB7Y|||||||
|page_data.content_type|string|The content type of the page.||||||||
|page_data.country|string|The country associated with the current page.|US, CA, FR, UK|||||||
|page_data.language|string|The language of the current page, usually pulled from the &lt;html&gt; tag lang attribute.|en-us, en-gb, ch-cn, fr-ca, fr-fr|||||||
|page_data.page_location|string|The url of the page currently being viewed.||||||||
|page_data.page_path|string|Captures the path portion of the page URL.||||||||
|page_data.page_title|string|The title of the page currently being viewed, generally available in &lt;title&gt;.||||||||
|page_data.previous_page|string|The name of the previous page.||||||||
|page_data.publication_name|string|The name of the publication associated with the page.|Atlanta Journal-Constitution|||||||
|page_data.publish_date|string|The publish date of the page||||||||
|page_data.site_section|string|The section of the site that the current page resides in. site\_section2 through site\_section5can also be used if the site has many sections.||||||||
|page_data.site_section2|string|Captures the sub-section of the site where the page being viewed is located|Shop &gt; Kids, Shop &gt; Mens, Shop &gt; Womens|||||||
|page_data.topics|string|The content topics for the page.||||||||
|page_data.user_group_id|string|The user group id of the page,||||||||
|user_data.user_registration_status|string|Captures the current registration status of the user.|registered|||||||




