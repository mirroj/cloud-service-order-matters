# Description

This repository contains a minimal example to reproduce the issue https://developercommunity.visualstudio.com/t/Running-a-cloud-service-project-throws-a/10305876

# How to reproduce
1. Open FolderOrderMattersIncorrect.sln
2. Try to run the cloud service
3. Following errors are thrown

```
CLR assembly 'C:\Program Files\Microsoft Visual Studio\2022\Enterprise\Common7\IDE\PublicAssemblies\Microsoft.VisualStudio.Imaging.Interop.14.0.DesignTime.dll' was imported from a type library and cannot be re-exported to a type library.  Make sure the type library from which the assembly was imported is registered.
```

```
Element not found. (Exception from HRESULT: 0x8002802B (TYPE_E_ELEMENTNOTFOUND))
```
