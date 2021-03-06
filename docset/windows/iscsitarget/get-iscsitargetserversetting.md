---
ms.mktglfcycl: manage
ms.sitesec: library
ms.author: coreyp
author: coreyp-at-msft
description: Use this topic to help manage Windows and Windows Server technologies with Windows PowerShell.
external help file: Microsoft.Iscsi.Target.Commands.dll-Help.xml
keywords: powershell, cmdlet
manager: jasgro
ms.date: 12/20/2016
ms.prod: w10
ms.technology: powershell-windows
ms.topic: reference
online version: 
schema: 2.0.0
title: Get-IscsiTargetServerSetting
ms.assetid: 07C8D0C2-6032-453C-9E66-AA58669EC71D
---

# Get-IscsiTargetServerSetting

## SYNOPSIS
Gets the global settings or common configurations for iSCSI target, virtual disk or snapshots.

## SYNTAX

```
Get-IscsiTargetServerSetting [-ComputerName <String>] [-Credential <PSCredential>] [<CommonParameters>]
```

## DESCRIPTION
The **Get-IscsiTargetServerSetting** cmdlet gets the global settings or common configurations for iSCSI targets, virtual disks or snapshots.

## EXAMPLES

### Example 1: Get portal entries for the local computer
```
PS C:\> Get-IscsiTargetServerSetting
ComputerName                            Version                                 Portals 
------------                            -------                                 ------- 
fssvr.contoso.com                       6.3.9600                                {+172.21.0.1:3260, ...
```

This example gets all of the portal entries of the local server.

## PARAMETERS

### -ComputerName
Specifies the computer name, or IP address, of the remote computer, if this cmdlet is run on a remote computer.

Specifies the cluster resource group network name, or cluster node name, if this cmdlet is run on a cluster configuration.

```yaml
Type: String
Parameter Sets: (All)
Aliases: 

Required: False
Position: Named
Default value: None
Accept pipeline input: True (ByPropertyName)
Accept wildcard characters: False
```

### -Credential
Specifies the credentials when connecting to a remote computer.

```yaml
Type: PSCredential
Parameter Sets: (All)
Aliases: 

Required: False
Position: Named
Default value: None
Accept pipeline input: True (ByPropertyName)
Accept wildcard characters: False
```

### CommonParameters
This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable. For more information, see [about_CommonParameters](http://go.microsoft.com/fwlink/?LinkID=113216).

## INPUTS

### None

## OUTPUTS

### None

## NOTES

## RELATED LINKS

[Set-IscsiTargetServerSetting](./Set-IscsiTargetServerSetting.md)

