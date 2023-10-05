# Page Load Started

### 

## Javascript Code
```js
window.dataLayer = window.dataLayer || [];
dataLayer.push({ event_data: null });  // Clear the previous event_data object.
dataLayer.push({ page_data: null });  // Clear the previous page_data object.
dataLayer.push({
  "event": "page_load_started",
  "detailed_event": "Page Load Started",
    "event_data": {
        "search_affordability": "<search_affordability>",
        "search_amenities": "<search_amenities>",
        "search_city": "<search_city>",
        "search_country": "<search_country>",
        "search_county": "<search_county>",
        "search_lifestyle": "<search_lifestyle>",
        "search_location_type": "<search_location_type>",
        "search_move_in_date": "<search_move_in_date>",
        "search_neighborhood_poi": "<search_neighborhood_poi>",
        "search_new": "<search_new>",
        "search_rating": "<search_rating>",
        "search_region": "<search_region>",
        "search_state": "<search_state>",
        "search_type": "<search_type>",
        "search_zipcode": "<search_zipcode>"
    },
    "page_data": {
        "account_id": "<account_id>",
        "country": "<country>",
        "language": "<language>",
        "listing_city": "<listing_city>",
        "listing_country": "<listing_country>",
        "listing_county": "<listing_county>",
        "listing_id": "<listing_id>",
        "listing_neighborhood_poi": "<listing_neighborhood_poi>",
        "listing_property_type": "<listing_property_type>",
        "listing_region": "<listing_region>",
        "listing_state": "<listing_state>",
        "listing_tier": "<listing_tier>",
        "listing_zipcode": "<listing_zipcode>",
        "name": "<name>",
        "page_location": "<page_location>",
        "page_title": "<page_title>",
        "search_action": "<search_action>",
        "search_activities": "<search_activities>",
        "search_facets": "<search_facets>",
        "search_keyword": "<search_keyword>",
        "search_listing_age": "<search_listing_age>",
        "search_listing_sale_type": "<search_listing_sale_type>",
        "search_listing_status": "<search_listing_status>",
        "search_max_acres": "<search_max_acres>",
        "search_max_bathrooms": "<search_max_bathrooms>",
        "search_max_bedrooms": "<search_max_bedrooms>",
        "search_max_price": "<search_max_price>",
        "search_max_square_feet": "<search_max_square_feet>",
        "search_min_acres": "<search_min_acres>",
        "search_min_bathrooms": "<search_min_bathrooms>",
        "search_min_bedrooms": "<search_min_bedrooms>",
        "search_min_price": "<search_min_price>",
        "search_min_square_feet": "<search_min_square_feet>",
        "search_property_type": "<search_property_type>",
        "search_residence": "<search_residence>",
        "site_name": "<site_name>",
        "type": "<type>"
    },
    "user_data": {
        "user_id": "<user_id>",
        "user_type": "<user_type>"
    }
});
```

## Variable Definitions

|Path|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|event_data.search_affordability|string|Affordability specified in search||||||||
|event_data.search_amenities|string|Search Amenities. Comma-delimited.|Air Conditioning,Parking|||||||
|event_data.search_city|string|Search city|Vancouver|||||||
|event_data.search_country|string|Search country|Canada|||||||
|event_data.search_county|string|Search county|Arapahoe|||||||
|event_data.search_lifestyle|string|Search lifestyle|Short Term|||||||
|event_data.search_location_type|string|Search location type|Apartments|||||||
|event_data.search_move_in_date|string|Search move-in date|Sept 26|||||||
|event_data.search_neighborhood_poi|string|Search Neighborhood Poi|Restaurants|||||||
|event_data.search_new|string|Whether the search is a new search or a refinement|true|||||||
|event_data.search_rating|string|Search rating|5|||||||
|event_data.search_region|string|Search region||||||||
|event_data.search_state|string|Search state|Minnesota|||||||
|event_data.search_type|string|Search type - initial vs refinement|Initial|||||||
|event_data.search_zipcode|string|Search zipcode|80704|||||||
|page_data.account_id|string|Listing Account ID||||||||
|page_data.country|string|The country associated with the current page.|US, CA, FR, UK|||||||
|page_data.language|string|The language of the current page, usually pulled from the &lt;html&gt; tag lang attribute.|en-us, en-gb, ch-cn, fr-ca, fr-fr|||||||
|page_data.listing_city|string|Listing city|Vancouver|||||||
|page_data.listing_country|string|Listing country|Canada|||||||
|page_data.listing_county|string|Listing county|Arapahoe|||||||
|page_data.listing_id|string|Site Specific ID of Property Listing||||||||
|page_data.listing_neighborhood_poi|string|Listing neighborhood POI|Restaurants|||||||
|page_data.listing_property_type|string|Listing property type|Apartments|||||||
|page_data.listing_region|string|Listing region||||||||
|page_data.listing_state|string|Listing state|Minnesota|||||||
|page_data.listing_tier|string|The Tier of the specific listing.||||||||
|page_data.listing_zipcode|string|Listing zipcode|80603|||||||
|page_data.name|string|Captures the name of the page the user is on|product - XYZ123, Mens - Tops - Sweaters, Order Confirmation|||||||
|page_data.page_location|string|Use this only if you need to report Page URLs different from those that appear in the address bar of the browser, for example redacting PII, providing page paths when none exist for SPAs, etc. Captures the URL of the page currently being viewed. This value will include the full, unaltered URL of the page\/screen the user is currently viewing, including query parameters, fragments, etc., for example https:\/\/www.example.com\/home?user=true&audience=test\#aboutus.|https:\/\/www.example.com\/home?user=true&audience=test\#aboutus|||||||
|page_data.page_title|string|The title of the page currently being viewed, generally available in &lt;title&gt;.||||||||
|page_data.search_action|string|Action taken to generate search results page: search, refine\/filter, sort, page load, etc||||||||
|page_data.search_activities|string|List of Activities Facets is applied to search||||||||
|page_data.search_facets|string|List of selected additional facets of search||||||||
|page_data.search_keyword|string|Keyword if used in search||||||||
|page_data.search_listing_age|string|Selected listing age in search||||||||
|page_data.search_listing_sale_type|string|Sale type of Listing in Search||||||||
|page_data.search_listing_status|string|Status of listings if selected in search||||||||
|page_data.search_max_acres|string|Max acres if selected in search||||||||
|page_data.search_max_bathrooms|string|Max bathrooms if selected in search||||||||
|page_data.search_max_bedrooms|string|max bedrooms if selected in search||||||||
|page_data.search_max_price|string|Max Price if selected in search||||||||
|page_data.search_max_square_feet|string|Max square feet if selected in search results||||||||
|page_data.search_min_acres|string|Min acres if selected in search||||||||
|page_data.search_min_bathrooms|string|Minimum bathrooms if selected in search||||||||
|page_data.search_min_bedrooms|string|Min bedrooms if selected in search||||||||
|page_data.search_min_price|string|Min price if selected in search||||||||
|page_data.search_min_square_feet|string|Min square feet if selected in search||||||||
|page_data.search_property_type|string|Property type if selected in search||||||||
|page_data.search_residence|string|Residence if selected in search||||||||
|page_data.site_name|string|Common language used within the business to refer to the website. May be specific County Sites.|Prospecting-EU, Prospecting-US, Member Portal, Shop-CA, Shop-US, Shop-EU|||||||
|page_data.type|string|The type of page currently viewed.|home, pdp, article|||||||
|user_data.user_id|string|The id of the user currently logged in to the site, if the site offers authentication and the user is authenticated.|123456, abc123|||||||
|user_data.user_type|string|Captures the type associated with the user \(i.e. guest, registered, prime, etc\).|employee, guest, agent, customer|||||||




