# Sistemas Informáticos

## Ejercicio de clase 3 - Primitive Datatype

### Josep M Castell Colom

## Disclaimer

A pesar de haber realizado `Update-Help` seguimos recibiendo el mensaje de:

```powerhell
Get-Help no encuentra los archivos de Ayuda para este cmdlet en el equipo. Mostrará solo una parte de la Ayuda.
        -- Para descargar e instalar los archivos de Ayuda para el módulo que incluye este cmdlet, use Update-Help.
        -- Para ver en línea el tema de Ayuda de este cmdlet, escriba "Get-Help Get-Help -Online" o
           vaya a https://go.microsoft.com/fwlink/?LinkID=113316.
```

Mensaje de error de `Update-Help`: 

```powershell
Update-Help : No se pudo actualizar la Ayuda para los módulos:
'AppBackgroundTask, Appx, BitLocker, BitsTransfer, CimCmdlets, Defender, DirectAccessClientComponents, Dism,
DnsClient, EventTracingManagement, International, iSCSI, ISE, Kds, Microsoft.PowerShell.Archive,
Microsoft.PowerShell.Core, Microsoft.PowerShell.Diagnostics, Microsoft.PowerShell.Host,
Microsoft.PowerShell.LocalAccounts, Microsoft.PowerShell.Management, Microsoft.PowerShell.ODataUtils,
Microsoft.PowerShell.Security, Microsoft.PowerShell.Utility, Microsoft.WSMan.Management, MMAgent, MsDtc, NetAdapter,
NetConnection, NetEventPacketCapture, NetLbfo, NetNat, NetQos, NetSecurity, NetSwitchTeam, NetTCPIP,
NetworkConnectivityStatus, NetworkSwitchManager, NetworkTransition, PackageManagement, PcsvDevice, PKI, PnpDevice,
PowerShellGet, PrintManagement, ProcessMitigations, Provisioning, PSDesiredStateConfiguration, PSScheduledJob,
PSWorkflow, PSWorkflowUtility, ScheduledTasks, SecureBoot, SmbShare, SmbWitness, StartLayout, Storage, TLS,
TroubleshootingPack, TrustedPlatformModule, VpnClient, Wdac, Whea, WindowsDeveloperLicense, WindowsErrorReporting,
WindowsSearch, WindowsUpdate'
Acceso denegado. El comando no pudo actualizar los temas de Ayuda para los módulos principales de Windows PowerShell o
para los módulos del directorio $pshome\Modules. Para actualizar estos temas de Ayuda, inicie Windows PowerShell con
el comando "Ejecutar como administrador" e intente volver a ejecutar Update-Help.
En línea: 1 Carácter: 1
+ Update-Help
+ ~~~~~~~~~~~
    + CategoryInfo          : InvalidOperation: (:) [Update-Help], Exception
    + FullyQualifiedErrorId : UpdatableHelpSystemRequiresElevation,Microsoft.PowerShell.Commands.UpdateHelpCommand

Update-Help : No se pudo actualizar la Ayuda para los módulos 'ConfigDefender, ConfigDefenderPerformance, PSReadline'
con las referencias culturales de interfaz de usuario {es-ES} : No se puede recuperar el archivo XML HelpInfo para la
referencia cultural de la interfaz de usuario es-ES. Asegúrese de que la propiedad HelpInfoUri del manifiesto del
módulo sea válida o compruebe la conexión de red e intente ejecutar el comando de nuevo.
En línea: 1 Carácter: 1
+ Update-Help
+ ~~~~~~~~~~~
    + CategoryInfo          : ResourceUnavailable: (:) [Update-Help], Exception
    + FullyQualifiedErrorId : UnableToRetrieveHelpInfoXml,Microsoft.PowerShell.Commands.UpdateHelpCommand

Update-Help : No se pudo actualizar la Ayuda para los módulos 'Microsoft.PowerShell.Operation.Validation' con las
referencias culturales de interfaz de usuario {en-US} : Acceso denegado a la ruta de acceso 'C:\Program
Files\WindowsPowerShell\Modules\Microsoft.PowerShell.Operation.Validation\1.0.1\en-US'.
En línea: 1 Carácter: 1
+ Update-Help
+ ~~~~~~~~~~~
    + CategoryInfo          : InvalidOperation: (:) [Update-Help], Exception
    + FullyQualifiedErrorId : UnknownErrorId,Microsoft.PowerShell.Commands.UpdateHelpCommand

```

## Task 1

```powershell
> Get-Help Get-Help

NOMBRE
Get-Help

SINTAXIS
    Get-Help [[-Name] <string>]  [<CommonParameters>]

    Get-Help [[-Name] <string>]  [<CommonParameters>]

    Get-Help [[-Name] <string>]  [<CommonParameters>]

    Get-Help [[-Name] <string>]  [<CommonParameters>]

    Get-Help [[-Name] <string>]  [<CommonParameters>]

    Get-Help [[-Name] <string>]  [<CommonParameters>]                                               
    
ALIAS

  Ninguno                                                                                           

NOTAS
  Get-Help no encuentra los archivos de Ayuda para este cmdlet en el equipo. Mostrará solo una parte de la Ayuda.
        -- Para descargar e instalar los archivos de Ayuda para el módulo que incluye este cmdlet, use Update-Help.
        -- Para ver en línea el tema de Ayuda de este cmdlet, escriba "Get-Help Get-Help -Online" o
           vaya a https://go.microsoft.com/fwlink/?LinkID=113316.


> Get-Help New-Item

NOMBRE
    New-Item

SINTAXIS
    New-Item [-Path] <string[]>  [<CommonParameters>]

    New-Item [[-Path] <string[]>]  [<CommonParameters>]


ALIAS
    ni


NOTAS
    Get-Help no encuentra los archivos de Ayuda para este cmdlet en el equipo. Mostrará solo una parte de la Ayuda.
        -- Para descargar e instalar los archivos de Ayuda para el módulo que incluye este cmdlet, use Update-Help.
        -- Para ver en línea el tema de Ayuda de este cmdlet, escriba "Get-Help New-Item -Online" o
           vaya a https://go.microsoft.com/fwlink/?LinkID=113353.
           

> Get-Help New-Alias

NOMBRE
    New-Alias

SINTAXIS
    New-Alias [-Name] <string> [-Value] <string>  [<CommonParameters>]


ALIAS
    nal


NOTAS
    Get-Help no encuentra los archivos de Ayuda para este cmdlet en el equipo. Mostrará solo una parte de la Ayuda.
        -- Para descargar e instalar los archivos de Ayuda para el módulo que incluye este cmdlet, use Update-Help.
        -- Para ver en línea el tema de Ayuda de este cmdlet, escriba "Get-Help New-Alias -Online" o
           vaya a https://go.microsoft.com/fwlink/?LinkID=113352.


> Get-Help Get-AuthenticodeSignature

NOMBRE
    Get-AuthenticodeSignature

SINTAXIS
    Get-AuthenticodeSignature [-FilePath] <string[]>  [<CommonParameters>]

    Get-AuthenticodeSignature  [<CommonParameters>]

    Get-AuthenticodeSignature  [<CommonParameters>]


ALIAS
    Ninguno


NOTAS
    Get-Help no encuentra los archivos de Ayuda para este cmdlet en el equipo. Mostrará solo una parte de la Ayuda.
        -- Para descargar e instalar los archivos de Ayuda para el módulo que incluye este cmdlet, use Update-Help.
        -- Para ver en línea el tema de Ayuda de este cmdlet, escriba "Get-Help Get-AuthenticodeSignature -Online" o
           vaya a https://go.microsoft.com/fwlink/?LinkID=113307.

> Get-Help Get-ControlPanelItem

NOMBRE
    Get-ControlPanelItem

SINTAXIS
    Get-ControlPanelItem [[-Name] <string[]>]  [<CommonParameters>]

    Get-ControlPanelItem  [<CommonParameters>]


ALIAS
    Ninguno


NOTAS
    Get-Help no encuentra los archivos de Ayuda para este cmdlet en el equipo. Mostrará solo una parte de la Ayuda.
        -- Para descargar e instalar los archivos de Ayuda para el módulo que incluye este cmdlet, use Update-Help.
        -- Para ver en línea el tema de Ayuda de este cmdlet, escriba "Get-Help Get-ControlPanelItem -Online" o
           vaya a https://go.microsoft.com/fwlink/?LinkID=219982.
```

## Task 2

```powershell
> Get-Help Get-Help -Examples

NOMBRE
    Get-Help

ALIAS
    Ninguno


NOTAS
    Get-Help no encuentra los archivos de Ayuda para este cmdlet en el equipo. Mostrará solo una parte de la Ayuda.
        -- Para descargar e instalar los archivos de Ayuda para el módulo que incluye este cmdlet, use Update-Help.
        -- Para ver en línea el tema de Ayuda de este cmdlet, escriba "Get-Help Get-Help -Online" o
           vaya a https://go.microsoft.com/fwlink/?LinkID=113316.


> Get-Help New-Item -Examples

NOMBRE
    New-Item

ALIAS
    ni


NOTAS
    Get-Help no encuentra los archivos de Ayuda para este cmdlet en el equipo. Mostrará solo una parte de la Ayuda.
        -- Para descargar e instalar los archivos de Ayuda para el módulo que incluye este cmdlet, use Update-Help.
        -- Para ver en línea el tema de Ayuda de este cmdlet, escriba "Get-Help New-Item -Online" o
           vaya a https://go.microsoft.com/fwlink/?LinkID=113353.


> Get-Help New-Alias -Examples

NOMBRE
    New-Alias

ALIAS
    nal


NOTAS
    Get-Help no encuentra los archivos de Ayuda para este cmdlet en el equipo. Mostrará solo una parte de la Ayuda.
        -- Para descargar e instalar los archivos de Ayuda para el módulo que incluye este cmdlet, use Update-Help.
        -- Para ver en línea el tema de Ayuda de este cmdlet, escriba "Get-Help New-Alias -Online" o
           vaya a https://go.microsoft.com/fwlink/?LinkID=113352.


> Get-Help Get-AuthenticodeSignature -Examples

NOMBRE
    Get-AuthenticodeSignature

ALIAS
    Ninguno


NOTAS
    Get-Help no encuentra los archivos de Ayuda para este cmdlet en el equipo. Mostrará solo una parte de la Ayuda.
        -- Para descargar e instalar los archivos de Ayuda para el módulo que incluye este cmdlet, use Update-Help.
        -- Para ver en línea el tema de Ayuda de este cmdlet, escriba "Get-Help Get-AuthenticodeSignature -Online" o
           vaya a https://go.microsoft.com/fwlink/?LinkID=113307.


> Get-Help Get-ControlPanelItem -Examples

NOMBRE
    Get-ControlPanelItem

ALIAS
    Ninguno


NOTAS
    Get-Help no encuentra los archivos de Ayuda para este cmdlet en el equipo. Mostrará solo una parte de la Ayuda.
        -- Para descargar e instalar los archivos de Ayuda para el módulo que incluye este cmdlet, use Update-Help.
        -- Para ver en línea el tema de Ayuda de este cmdlet, escriba "Get-Help Get-ControlPanelItem -Online" o
           vaya a https://go.microsoft.com/fwlink/?LinkID=219982.
```

## Task 3

```powershell

```
