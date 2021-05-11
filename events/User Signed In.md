# User Signed In

## Javascript Code
```js
window.appEventData1105 = window.appEventData1105 || [];
appEventData1105.push({
  "event": "User Signed In",
    "user": {
        "hasPersistedCart": "<hasPersistedCart>",
        "loyalty": {
            "memberId": "<memberId>",
            "memberStatus": "<memberStatus>"
        },
        "organizationID": "<organizationID>",
        "persistedCartValue": "<persistedCartValue>",
        "profileAttributesList": "<profileAttributesList>"
    }
});
```

## Variable Definitions

|Field|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|hasPersistedCart|boolean|Indicator of the user has a persisted shopping cart|TRUE, FALSE|||||||
|memberId|string|Member Identifier in a Loyalty program|abc1234, def876, 87987659|||||||
|memberStatus|string|Member status, level, or tier in a Loyalty program|Gold, Bronze, Platinum, Diamond, Silver|||||||
|organizationID|string|Customer Organization ID associated with website or mobile app behavior.|1234, G72345, Alaska|||||||
|persistedCartValue|string|The total value of all items in the persisted cart|125.05, 432.21, 90.22, 12.05|^[0-9]*(\.[0-9]{1,2})?$||||||
|profileAttributesList|string|A twice delimited string of key / value pairs.  Use ~ between key and value.  Use | between pairs|homeStore~234|loyaltyTier~gold|memberSince~2002|||||||
