---
external help file: AdminUI.PS.Dcm.dll-Help.xml
online version: 
schema: 2.0.0
---

# Set-CMComplianceRuleAssembly

## SYNOPSIS
Sets a compliance rule assembly

## SYNTAX

### ByCIToken (Default)
```
Set-CMComplianceRuleAssembly -InputObject <IResultObject> [-PublicKeyToken] -RuleName <String>
 [-ExpressionOperator <RuleExpressionOperator>] [-ReportNoncompliance <Boolean>] [-NewRuleName <String>]
 [-PassThru] [-Remediate <Boolean>] [-ExpectedValue <String[]>]
 [-NoncomplianceSeverity <NoncomplianceSeverity>] [-RuleDescription <String>] [-DisableWildcardHandling]
 [-ForceWildcardHandling] [-WhatIf] [-Confirm] [<CommonParameters>]
```

### ByCICulture
```
Set-CMComplianceRuleAssembly [-Culture] -InputObject <IResultObject> -RuleName <String>
 [-ExpressionOperator <RuleExpressionOperator>] [-ReportNoncompliance <Boolean>] [-NewRuleName <String>]
 [-PassThru] [-Remediate <Boolean>] [-ExpectedValue <String[]>]
 [-NoncomplianceSeverity <NoncomplianceSeverity>] [-RuleDescription <String>] [-DisableWildcardHandling]
 [-ForceWildcardHandling] [-WhatIf] [-Confirm] [<CommonParameters>]
```

### ByRuleCulture
```
Set-CMComplianceRuleAssembly [-Culture] -Rule <Rule> [-ExpressionOperator <RuleExpressionOperator>]
 [-ReportNoncompliance <Boolean>] [-NewRuleName <String>] [-PassThru] [-Remediate <Boolean>]
 [-ExpectedValue <String[]>] [-NoncomplianceSeverity <NoncomplianceSeverity>] [-RuleDescription <String>]
 [-DisableWildcardHandling] [-ForceWildcardHandling] [-WhatIf] [-Confirm] [<CommonParameters>]
```

### ByRuleToken
```
Set-CMComplianceRuleAssembly [-PublicKeyToken] -Rule <Rule> [-ExpressionOperator <RuleExpressionOperator>]
 [-ReportNoncompliance <Boolean>] [-NewRuleName <String>] [-PassThru] [-Remediate <Boolean>]
 [-ExpectedValue <String[]>] [-NoncomplianceSeverity <NoncomplianceSeverity>] [-RuleDescription <String>]
 [-DisableWildcardHandling] [-ForceWildcardHandling] [-WhatIf] [-Confirm] [<CommonParameters>]
```

## DESCRIPTION
 

## EXAMPLES

### Example 1
```
PS C:\>  
```

 

## PARAMETERS

### -Confirm
Prompts you for confirmation before running the cmdlet.

```yaml
Type: SwitchParameter
Parameter Sets: (All)
Aliases: cf

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Culture
 

```yaml
Type: SwitchParameter
Parameter Sets: ByCICulture, ByRuleCulture
Aliases: 

Required: True
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -DisableWildcardHandling
DisableWildcardHandling treats wildcard characters as literal character values. Cannot be combined with **ForceWildcardHandling**.

```yaml
Type: SwitchParameter
Parameter Sets: (All)
Aliases: 

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -ExpectedValue
 

```yaml
Type: String[]
Parameter Sets: (All)
Aliases: ExpectedValues

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -ExpressionOperator
 

```yaml
Type: RuleExpressionOperator
Parameter Sets: (All)
Aliases: 
Accepted values: And, Or, Other, IsEquals, NotEquals, GreaterThan, LessThan, Between, NotBetween, GreaterEquals, LessEquals, BeginsWith, NotBeginsWith, EndsWith, NotEndsWith, Contains, NotContains, AllOf, OneOf, NoneOf, SetEquals, SubsetOf, ExcludesAll

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -ForceWildcardHandling
ForceWildcardHandling processes wildcard characters and may lead to unexpected behavior (not recommended). Cannot be combined with **DisableWildcardHandling**.

```yaml
Type: SwitchParameter
Parameter Sets: (All)
Aliases: 

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -InputObject
 

```yaml
Type: IResultObject
Parameter Sets: ByCIToken, ByCICulture
Aliases: ConfigurationItem

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -NewRuleName
 

```yaml
Type: String
Parameter Sets: (All)
Aliases: 

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -NoncomplianceSeverity
 

```yaml
Type: NoncomplianceSeverity
Parameter Sets: (All)
Aliases: 
Accepted values: None, Informational, Warning, Critical, CriticalWithEvent

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -PassThru
Returns an object representing the item with which you are working. By default, this cmdlet may not generate any output.

```yaml
Type: SwitchParameter
Parameter Sets: (All)
Aliases: 

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -PublicKeyToken
 

```yaml
Type: SwitchParameter
Parameter Sets: ByCIToken, ByRuleToken
Aliases: 

Required: True
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Remediate
 

```yaml
Type: Boolean
Parameter Sets: (All)
Aliases: 

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -ReportNoncompliance
 

```yaml
Type: Boolean
Parameter Sets: (All)
Aliases: 

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Rule
 

```yaml
Type: Rule
Parameter Sets: ByRuleCulture, ByRuleToken
Aliases: 

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -RuleDescription
 

```yaml
Type: String
Parameter Sets: (All)
Aliases: 

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -RuleName
 

```yaml
Type: String
Parameter Sets: ByCIToken, ByCICulture
Aliases: 

Required: True
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -WhatIf
Shows what would happen if the cmdlet runs.
The cmdlet is not run.

```yaml
Type: SwitchParameter
Parameter Sets: (All)
Aliases: wi

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### CommonParameters
This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable. For more information, see about_CommonParameters (http://go.microsoft.com/fwlink/?LinkID=113216).

## INPUTS

### Microsoft.ConfigurationManagement.ManagementProvider.IResultObject
Microsoft.SystemsManagementServer.DesiredConfigurationManagement.Rules.Rule

## OUTPUTS

### System.Object

## NOTES

## RELATED LINKS

