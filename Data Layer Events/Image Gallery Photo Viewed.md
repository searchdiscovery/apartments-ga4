# Image Gallery Photo Viewed

### 

## Javascript Code
```js
window.dataLayer = window.dataLayer || [];
dataLayer.push({ event_data: null });  // Clear the previous event_data object.
dataLayer.push({
  "event": "image_gallery_photo_viewed",
  "detailed_event": "Image Gallery Photo Viewed",
    "event_data": {
        "photo_number": "<photo_number>"
    }
});
```

## Variable Definitions

|Path|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|event_data.photo_number|string|Tracks the number of total of the photo being viewed. 4\/8 for example.|2\/5, 4\/8, 9\/9, etc|||||||




