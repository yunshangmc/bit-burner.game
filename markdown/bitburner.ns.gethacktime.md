<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [bitburner](./bitburner.md) &gt; [NS](./bitburner.ns.md) &gt; [getHackTime](./bitburner.ns.gethacktime.md)

## NS.getHackTime() method

Get the execution time of a hack() call.

<b>Signature:</b>

```typescript
getHackTime(host: string): number;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  host | string | Host of target server. |

<b>Returns:</b>

number

Returns the amount of time in milliseconds it takes to execute the hack Netscript function. Returns Infinity if called on a Hacknet Server.

## Remarks

RAM cost: 0.05 GB

Returns the amount of time in milliseconds it takes to execute the hack Netscript function on the target server. The function takes in an optional hackLvl parameter that can be specified to see what the hack time would be at different hacking levels.
