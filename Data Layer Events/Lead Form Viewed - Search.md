# Lead Form Viewed - Search

### 

## Javascript Code
```js
window.dataLayer = window.dataLayer || [];
dataLayer.push({ event_data: null });  // Clear the previous event_data object.
dataLayer.push({
  "event": "lead_form_viewed",
  "detailed_event": "Lead Form Viewed - Search",
    "event_data": {
        "account_id": "<account_id>",
        "listing_id": "<listing_id>",
        "listing_tier": "<listing_tier>"
    }
});
```

## Variable Definitions

|Path|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|event_data.account_id|string|Account ID for a listing passed with certain events.||||||||
|event_data.listing_id|string|Listing ID to be sent with certain events.||||||||
|event_data.listing_tier|string|Listing tier of a listing to be set with certain events.||||||||




