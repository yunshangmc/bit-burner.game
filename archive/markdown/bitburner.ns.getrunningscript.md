<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [bitburner](./bitburner.md) &gt; [NS](./bitburner.ns.md) &gt; [getRunningScript](./bitburner.ns.getrunningscript.md)

## NS.getRunningScript() method

Get general info about a running script.

<b>Signature:</b>

```typescript
getRunningScript(
    filename?: FilenameOrPID,
    hostname?: string,
    ...args: (string | number | boolean)[]
  ): RunningScript | null;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  filename | [FilenameOrPID](./bitburner.filenameorpid.md) | Optional. Filename or PID of the script. |
|  hostname | string | Optional. Name of host server the script is running on. |
|  args | (string \| number \| boolean)\[\] | Arguments to identify the script |

<b>Returns:</b>

[RunningScript](./bitburner.runningscript.md) \| null

The info about the running script if found, and null otherwise.

## Remarks

RAM cost: 0.3 GB

Running with no args returns current script. If you use a PID as the first parameter, the hostname and args parameters are unnecessary.
