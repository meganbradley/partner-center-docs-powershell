---
content_git_url: https://github.com/Microsoft/Partner-Center-PowerShell/blob/master/docs/help/Suspend-PartnerAzureSubscription.md
external help file: Microsoft.Store.PartnerCenter.PowerShell.dll-Help.xml
Module Name: PartnerCenter
online version: https://learn.microsoft.com/powershell/module/partnercenter/Suspend-PartnerAzureSubscription
original_content_git_url: https://github.com/Microsoft/Partner-Center-PowerShell/blob/master/docs/help/Suspend-PartnerAzureSubscription.md
schema: 2.0.0
---

# Suspend-PartnerAzureSubscription

## SYNOPSIS
Suspends an Azure subscription that is part of an Azure Plan.

## SYNTAX

```powershell
Suspend-PartnerAzureSubscription -CustomerId <String> -SubscriptionId <String> [<CommonParameters>]
```

## DESCRIPTION
Suspends an Azure subscription that is part of an Azure Plan.

## EXAMPLES

### Example 1
```powershell
PS C:\> Suspend-PartnerAzureSubscription -CustomerId 'bc79422f-ba9c-46ce-99bf-d747d4721466' -SubscriptionId 'aaaa0a0a-bb1b-cc2c-dd3d-eeeeee4e4e4e'
```

Suspends an Azure subscription that is part of an Azure Plan.

## PARAMETERS

### -CustomerId
The identifier of the customer.

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

### -SubscriptionId
The identifier of the subscription.

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

### CommonParameters
This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable. For more information, see [about_CommonParameters](http://go.microsoft.com/fwlink/?LinkID=113216).

## INPUTS

### None

## OUTPUTS

### System.String

## NOTES

## RELATED LINKS
