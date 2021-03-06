﻿{% hint style="info" %}
Universal Dashboard is now a part of PowerShell Universal. This documentation is for reference to the v2 version of Universal Dashboard and is no longer maintained. PowerShell Universal Documentation can be found [here](https://docs.ironmansoftware.com).
{% endhint %}


---
external help file: UniversalDashboard.Community-help.xml
Module Name: UniversalDashboard
online version: 
schema: 2.0.0
---

# Send-UDToast

## SYNOPSIS
Sends a toast message from an endpoint.

## SYNTAX

```
Send-UDToast [-Message] <String> [-Duration <Int32>] [<CommonParameters>]
```

## DESCRIPTION
Sends a toast message from an endpoint.

## EXAMPLES

### Example 1
```
PS C:\> New-UDButton -Text "Click me" -OnClick {
    Send-UDToast -Message 'Ouch!"
}
```

Sends a toast to the user when the button is clicked. 

## PARAMETERS

### -Duration
The number of milliseconds to show the toast.

```yaml
Type: Int32
Parameter Sets: (All)
Aliases: 

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Message
A message to show to the user. 

```yaml
Type: String
Parameter Sets: (All)
Aliases: 

Required: True
Position: 0
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### CommonParameters
This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable. For more information, see about_CommonParameters (http://go.microsoft.com/fwlink/?LinkID=113216).

## INPUTS

### None

## OUTPUTS

### System.Object

## NOTES

## RELATED LINKS



