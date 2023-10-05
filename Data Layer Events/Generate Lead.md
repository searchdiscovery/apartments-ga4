# Generate Lead

### 

## Javascript Code
```js
window.dataLayer = window.dataLayer || [];
dataLayer.push({ event_data: null });  // Clear the previous event_data object.
dataLayer.push({ page_data: null });  // Clear the previous page_data object.
dataLayer.push({
  "event": "generate_lead",
  "detailed_event": "Generate Lead",
    "event_data": {
        "confirm_availability_checked": <confirm_availability_checked>,
        "custom_message_checked": <custom_message_checked>,
        "listing_city": "<listing_city>",
        "listing_country": "<listing_country>",
        "listing_county": "<listing_county>",
        "listing_neighborhood_poi": "<listing_neighborhood_poi>",
        "listing_property_type": "<listing_property_type>",
        "listing_region": "<listing_region>",
        "listing_state": "<listing_state>",
        "listing_zipcode": "<listing_zipcode>",
        "request_application_checked": <request_application_checked>,
        "schedule_tour_checked": <schedule_tour_checked>
    },
    "page_data": {
        "account_id": "<account_id>",
        "listing_id": "<listing_id>",
        "listing_tier": "<listing_tier>"
    }
});
```

## Variable Definitions

|Path|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|event_data.confirm_availability_checked|boolean|Confirm Availability checkbox is checked|true, false|||||||
|event_data.custom_message_checked|boolean|Custom Message checkbox is checked|true, false|||||||
|event_data.listing_city|string|Listing city|Vancouver|||||||
|event_data.listing_country|string|Listing country|Canada|||||||
|event_data.listing_county|string|Listing county|Arapahoe|||||||
|event_data.listing_neighborhood_poi|string|Listing neighborhood POI|Restaurants|||||||
|event_data.listing_property_type|string|Listing property type|Apartments|||||||
|event_data.listing_region|string|Listing region||||||||
|event_data.listing_state|string|Listing state|Minnesota|||||||
|event_data.listing_zipcode|string|Listing zipcode|80603|||||||
|event_data.request_application_checked|boolean|Request Application checkbox is checked|true, false|||||||
|event_data.schedule_tour_checked|boolean|Schedule Tour checkbox is checked|true, false|||||||
|page_data.account_id|string|Listing Account ID||||||||
|page_data.listing_id|string|Site Specific ID of Property Listing||||||||
|page_data.listing_tier|string|The Tier of the specific listing.||||||||




