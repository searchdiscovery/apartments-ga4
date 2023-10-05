# Click to Call - Search

### 

## Javascript Code
```js
window.dataLayer = window.dataLayer || [];
dataLayer.push({ event_data: null });  // Clear the previous event_data object.
dataLayer.push({
  "event": "click_to_call",
  "detailed_event": "Click to Call - Search",
    "event_data": {
        "account_id": "<account_id>",
        "listing_city": "<listing_city>",
        "listing_country": "<listing_country>",
        "listing_county": "<listing_county>",
        "listing_id": "<listing_id>",
        "listing_neighborhood_poi": "<listing_neighborhood_poi>",
        "listing_property_type": "<listing_property_type>",
        "listing_region": "<listing_region>",
        "listing_state": "<listing_state>",
        "listing_tier": "<listing_tier>",
        "listing_zipcode": "<listing_zipcode>"
    }
});
```

## Variable Definitions

|Path|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|event_data.account_id|string|Account ID for a listing passed with certain events.||||||||
|event_data.listing_city|string|Listing city|Vancouver|||||||
|event_data.listing_country|string|Listing country|Canada|||||||
|event_data.listing_county|string|Listing county|Arapahoe|||||||
|event_data.listing_id|string|Listing ID to be sent with certain events.||||||||
|event_data.listing_neighborhood_poi|string|Listing neighborhood POI|Restaurants|||||||
|event_data.listing_property_type|string|Listing property type|Apartments|||||||
|event_data.listing_region|string|Listing region||||||||
|event_data.listing_state|string|Listing state|Minnesota|||||||
|event_data.listing_tier|string|Listing tier of a listing to be set with certain events.||||||||
|event_data.listing_zipcode|string|Listing zipcode|80603|||||||




