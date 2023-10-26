# Listing Add to Wishlist

### 

## Javascript Code
```js
window.dataLayer = window.dataLayer || [];
dataLayer.push({ event_data: null });  // Clear the previous event_data object.
dataLayer.push({
  "event": "add_to_wishlist",
  "detailed_event": "Listing Add to Wishlist",
    "event_data": {
        "listing_id": "<listing_id>"
    }
});
```

## Variable Definitions

|Path|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|event_data.listing_id|string|Listing ID to be sent with certain events.||||||||




