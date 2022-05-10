# Back-End Order Import

### 

## Javascript Code
```js
window.dataLayer = window.dataLayer || [];
dataLayer.push({ event_data: null });  // Clear the previous event_data object.
dataLayer.push({
  "event": "backend_order_import",
  "detailed_event": "Back-End Order Import",
    "event_data": {
        "backend_orders": "<backend_orders>",
        "backend_quantity": <backend_quantity>,
        "backend_value": <backend_value>
    }
});
```

## Variable Definitions

|Path|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|event_data.backend_orders|string|Count of orders taking place offline from internal databases for use in comparing to online orders.||||||||
|event_data.backend_quantity|integer|Count of units taking place offline from internal databases for use in comparing to online units.||||||||
|event_data.backend_value|number|Count of revenue taking place offline from internal databases for use in comparing to online revenue.||||||||




