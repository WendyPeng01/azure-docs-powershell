---
external help file: Microsoft.WindowsAzure.Commands.ServiceManagement.dll-Help.xml
online version: 
schema: 2.0.0
ms.assetid: 985D040B-1148-40B1-ACDD-8C30DD3C7B29
---

# Get-AzureAffinityGroup

## SYNOPSIS
Gets an Azure affinity group object.

## SYNTAX

```
Get-AzureAffinityGroup [[-Name] <String>] [-Profile <AzureProfile>] [<CommonParameters>]
```

## DESCRIPTION
The **Get-AzureAffinityGroup** cmdlet gets an Azure affinity group.
The affinity group object includes the affinity group name, location, label, description and the storage and hosted services that are part of the affinity group.

## EXAMPLES

### Example 1: Get properties of an affinity group
```
PS C:\>Get-AzureAffinityGroup -Name "South01"
```

This command gets the properties of the affinity group named South01.

## PARAMETERS

### -Name
Specifies the name of the affinity group that this cmdlet gets.
Names for affinity groups created through the Management Portal are typically GUIDs.
The Management Port shows the affinity group label.

```yaml
Type: String
Parameter Sets: (All)
Aliases: 

Required: False
Position: 0
Default value: None
Accept pipeline input: True (ByPropertyName)
Accept wildcard characters: False
```

### -Profile
Specifies the Azure profile from which this cmdlet reads.
If you do not specify a profile, this cmdlet reads from the local default profile.

```yaml
Type: AzureProfile
Parameter Sets: (All)
Aliases: 

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### CommonParameters
This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable. For more information, see about_CommonParameters (http://go.microsoft.com/fwlink/?LinkID=113216).

## INPUTS

## OUTPUTS

### AffinityGroup

## NOTES

## RELATED LINKS

[New-AzureAffinityGroup](./New-AzureAffinityGroup.md)

[Remove-AzureAffinityGroup](./Remove-AzureAffinityGroup.md)

[Set-AzureAffinityGroup](./Set-AzureAffinityGroup.md)


