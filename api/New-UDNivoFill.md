﻿{% hint style="info" %}
Universal Dashboard is now a part of PowerShell Universal. This documentation is for reference to the v2 version of Universal Dashboard and is no longer maintained. PowerShell Universal Documentation can be found [here](https://docs.ironmansoftware.com).
{% endhint %}


---
external help file: classes.dll-Help.xml
Module Name: UniversalDashboard
online version: https://go.microsoft.com/fwlink/?LinkID=217032
schema: 2.0.0
---

# New-UDNivoFill

## SYNOPSIS
Assigns a pattern or gradient to an element. 

## SYNTAX

```
New-UDNivoFill -ElementId <String> -PatternId <String> [<CommonParameters>]
```

## DESCRIPTION
Assigns a pattern or gradient to an element. 

## EXAMPLES

### Example 1
```
PS C:\> $Pattern = New-UDNivoPattern -Dots -Id 'fill'
```

{{ Add example description here }}

## PARAMETERS

### -ElementId
The element or serie id to assign the pattern to.

```yaml
Type: String
Parameter Sets: (All)
Aliases: 

Required: True
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -PatternId
The ID of the pattern. You use New-UDNivoPattern to create these patterns. 

```yaml
Type: String
Parameter Sets: (All)
Aliases: GradientId

Required: True
Position: Named
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



