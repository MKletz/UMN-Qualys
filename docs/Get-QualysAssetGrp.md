---
external help file: UMN-Qualys-help.xml
Module Name: UMN-Qualys
online version:
schema: 2.0.0
---

# Get-QualysAssetGrp

## SYNOPSIS
Get a list of AssetGroup IDs or the ID for a specific AssetGroup

## SYNTAX

```
Get-QualysAssetGrp [[-id] <String>] [-qualysServer] <String> [-cookie] <WebRequestSession> [<CommonParameters>]
```

## DESCRIPTION
Get a list of AssetGroup IDs or the ID for a specific AssetGroup

## EXAMPLES

### Example 1
```powershell
PS C:\> {{ Add example code here }}
```

{{ Add example description here }}

## PARAMETERS

### -id
Asset Group ID, use this to get a single Asset Group

```yaml
Type: String
Parameter Sets: (All)
Aliases:

Required: False
Position: 1
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -qualysServer
FQDN of qualys server, see Qualys documentation, based on wich Qualys Platform you're in.

```yaml
Type: String
Parameter Sets: (All)
Aliases:

Required: True
Position: 2
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -cookie
Use Connect-Qualys to get session cookie

```yaml
Type: WebRequestSession
Parameter Sets: (All)
Aliases:

Required: True
Position: 3
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### CommonParameters
This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable. For more information, see [about_CommonParameters](http://go.microsoft.com/fwlink/?LinkID=113216).

## INPUTS

## OUTPUTS

## NOTES

## RELATED LINKS
