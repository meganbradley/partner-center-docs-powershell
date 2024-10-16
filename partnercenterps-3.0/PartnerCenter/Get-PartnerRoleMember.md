---
content_git_url: https://github.com/Microsoft/Partner-Center-PowerShell/blob/master/docs/help/Get-PartnerRoleMember.md
external help file: Microsoft.Store.PartnerCenter.PowerShell.dll-Help.xml
Module Name: PartnerCenter
online version: https://learn.microsoft.com/powershell/module/partnercenter/Get-PartnerRoleMember
original_content_git_url: https://github.com/Microsoft/Partner-Center-PowerShell/blob/master/docs/help/Get-PartnerRoleMember.md
schema: 2.0.0
---

# Get-PartnerRoleMember

## SYNOPSIS
Gets the members of the specified partner role.

## SYNTAX

```powershell
Get-PartnerRoleMember [[-RoleId] <String>] [<CommonParameters>]
```

## DESCRIPTION
Gets the members of the specified partner role.

## EXAMPLES

### Example 1
```powershell
PS C:\> Get-PartnerRole -RoleId '00000000-0000-0000-0000-000000000000'
```

Gets the members of the specified role.

## PARAMETERS

### -RoleId
The identifier of the role.

```yaml
Type: String
Parameter Sets: (All)
Aliases:

Required: False
Position: 0
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### CommonParameters
This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable. For more information, see [about_CommonParameters](http://go.microsoft.com/fwlink/?LinkID=113216).

## INPUTS

### None

## OUTPUTS

### Microsoft.Store.PartnerCenter.PowerShell.Models.Roles.PSUserMember

## NOTES

## RELATED LINKS
