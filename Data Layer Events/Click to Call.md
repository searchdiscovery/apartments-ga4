# Click to Call

### 

## Javascript Code
```js
window.dataLayer = window.dataLayer || [];
dataLayer.push({ page_data: null });  // Clear the previous page_data object.
dataLayer.push({
  "event": "click_to_call",
  "detailed_event": "Click to Call",
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
|page_data.account_id|string|Listing Account ID||||||||
|page_data.listing_id|string|Site Specific ID of Property Listing||||||||
|page_data.listing_tier|string|The Tier of the specific listing.||||||||




