---
title: pushprinterconnections
description: Reference article for the pushprinterconnections command, which reads Deployed Printer Connection settings from Group Policy and deploys/removes printer connections as needed.
ms.topic: article
ms.assetid: c30afb97-b149-478f-a4b9-2cbc25361818
author: coreyp-at-msft
ms.author: coreyp
manager: dongill
ms.date: 10/16/2017
---

# pushprinterconnections

Reads Deployed Printer Connection settings from Group Policy and deploys/removes printer connections as needed.

> [!IMPORTANT]
> This utility is for use in machine startup or user logon scripts, and shouldn't be run from the command line.

## Syntax

```
pushprinterconnections <-log> <-?>
```

### Parameters

| Parameter | Description |
|--|--|
| <-log> | Writes a per user debug log file to *%temp*, or writes a per machine debug log to *%windir%\temp*. |
| <-?> | Displays Help at the command prompt. |

## Additional References

- [Command-Line Syntax Key](command-line-syntax-key.md)

- [Print Command Reference](print-command-reference.md)

- [Deploy Printers by Using Group Policy](https://go.microsoft.com/fwlink/?LinkId=230627)
