# User Detected

## Javascript Code
```js
window.appEventData1105 = window.appEventData1105 || [];
appEventData1105.push({
  "event": "User Detected",
    "user": {
        "loyalty": {
            "memberId": "<memberId>",
            "memberStatus": "<memberStatus>"
        },
        "profileAttributesList": "<profileAttributesList>"
    }
});
```

## Variable Definitions

|Field|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|memberId|string|Member Identifier in a Loyalty program|abc1234, def876, 87987659|||||||
|memberStatus|string|Member status, level, or tier in a Loyalty program|Gold, Bronze, Platinum, Diamond, Silver|||||||
|profileAttributesList|string|A twice delimited string of key / value pairs.  Use ~ between key and value.  Use | between pairs|homeStore~234|loyaltyTier~gold|memberSince~2002|||||||
