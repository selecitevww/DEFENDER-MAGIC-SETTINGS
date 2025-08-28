MANUAL SETTING!

  ![https://github.com/selecitevww/DEFENDER-MAGIC-SETTINGS/blob/main/%EF%BF%BD%EF%BF%BD%EF%BF%BD%EF%BF%BD%EF%BF%BD/Bat_to_Exe_Conventer16.docx]

DONT IMPORT!

  ```
  
<?xml version="1.0" encoding="UTF-8"?>
<MitigationPolicy>
  <SystemConfig>
    <DEP Enable="true" EmulateAtlThunks="false" />
    <ASLR ForceRelocateImages="true" RequireInfo="false" BottomUp="true" HighEntropy="true" />
    <ControlFlowGuard Enable="true" SuppressExports="false" />
    <SEHOP Enable="true" TelemetryOnly="false" />
    <Heap TerminateOnError="true" />
  </SystemConfig>
  <AppConfig Executable="7z.exe">
    <DEP Enable="true" EmulateAtlThunks="false" />
    <ASLR BottomUp="true" HighEntropy="false" />
    <StrictHandle Enable="true" />
    <SystemCalls DisableWin32kSystemCalls="false" Audit="true" />
    <ExtensionPoints DisableExtensionPoints="true" />
    <DynamicCode BlockDynamicCode="false" AllowThreadsToOptOut="false" Audit="true" />
    <SignedBinaries MicrosoftSignedOnly="false" AllowStoreSignedBinaries="true" Audit="true" AuditStoreSigned="true" EnforceModuleDependencySigning="false" />
    <Fonts DisableNonSystemFonts="false" AuditOnly="false" Audit="true" />
    <ImageLoad BlockRemoteImageLoads="false" AuditRemoteImageLoads="true" BlockLowLabelImageLoads="false" AuditLowLabelImageLoads="true" />
    <Payload EnableExportAddressFilter="false" AuditEnableExportAddressFilter="true" EnableExportAddressFilterPlus="false" AuditEnableExportAddressFilterPlus="true" EnableImportAddressFilter="false" AuditEnableImportAddressFilter="true" EnableRopStackPivot="true" AuditEnableRopStackPivot="false" EnableRopCallerCheck="false" AuditEnableRopCallerCheck="true" EnableRopSimExec="false" AuditEnableRopSimExec="true" />
    <SEHOP Enable="true" TelemetryOnly="false" />
    <Heap TerminateOnError="true" />
    <ChildProcess DisallowChildProcessCreation="false" Audit="true" />
    <UserShadowStack UserShadowStack="true" UserShadowStackStrictMode="true" AuditUserShadowStack="false" />
  </AppConfig>
  <AppConfig Executable="7zFM.exe">
    <DEP Enable="true" EmulateAtlThunks="false" />
    <ASLR BottomUp="true" HighEntropy="false" />
    <StrictHandle Enable="true" />
    <SystemCalls DisableWin32kSystemCalls="false" Audit="true" />
    <ExtensionPoints DisableExtensionPoints="true" />
    <DynamicCode BlockDynamicCode="false" AllowThreadsToOptOut="false" Audit="true" />
    <SignedBinaries MicrosoftSignedOnly="false" AllowStoreSignedBinaries="true" Audit="true" AuditStoreSigned="true" EnforceModuleDependencySigning="false" />
    <Fonts DisableNonSystemFonts="false" AuditOnly="false" Audit="true" />
    <ImageLoad BlockRemoteImageLoads="false" AuditRemoteImageLoads="true" BlockLowLabelImageLoads="false" AuditLowLabelImageLoads="true" />
    <Payload EnableExportAddressFilter="false" AuditEnableExportAddressFilter="true" EnableExportAddressFilterPlus="false" AuditEnableExportAddressFilterPlus="true" EnableImportAddressFilter="false" AuditEnableImportAddressFilter="true" EnableRopStackPivot="true" AuditEnableRopStackPivot="false" EnableRopCallerCheck="false" AuditEnableRopCallerCheck="true" EnableRopSimExec="false" AuditEnableRopSimExec="true" />
    <SEHOP Enable="true" TelemetryOnly="false" />
    <Heap TerminateOnError="true" />
    <ChildProcess DisallowChildProcessCreation="false" Audit="true" />
    <UserShadowStack UserShadowStack="true" UserShadowStackStrictMode="true" AuditUserShadowStack="false" />
  </AppConfig>
  <AppConfig Executable="7zG.exe">
    <DEP Enable="true" EmulateAtlThunks="false" />
    <ASLR BottomUp="true" HighEntropy="false" />
    <StrictHandle Enable="true" />
    <SystemCalls DisableWin32kSystemCalls="false" Audit="true" />
    <ExtensionPoints DisableExtensionPoints="true" />
    <DynamicCode BlockDynamicCode="false" AllowThreadsToOptOut="false" Audit="true" />
    <SignedBinaries MicrosoftSignedOnly="false" AllowStoreSignedBinaries="true" Audit="true" AuditStoreSigned="true" EnforceModuleDependencySigning="false" />
    <Fonts DisableNonSystemFonts="false" AuditOnly="false" Audit="true" />
    <ImageLoad BlockRemoteImageLoads="false" AuditRemoteImageLoads="true" BlockLowLabelImageLoads="false" AuditLowLabelImageLoads="true" />
    <Payload EnableExportAddressFilter="false" AuditEnableExportAddressFilter="true" EnableExportAddressFilterPlus="false" AuditEnableExportAddressFilterPlus="true" EnableImportAddressFilter="false" AuditEnableImportAddressFilter="true" EnableRopStackPivot="true" AuditEnableRopStackPivot="false" EnableRopCallerCheck="false" AuditEnableRopCallerCheck="true" EnableRopSimExec="false" AuditEnableRopSimExec="true" />
    <SEHOP Enable="true" TelemetryOnly="false" />
    <Heap TerminateOnError="true" />
    <ChildProcess DisallowChildProcessCreation="false" Audit="true" />
    <UserShadowStack UserShadowStack="true" UserShadowStackStrictMode="true" AuditUserShadowStack="false" />
  </AppConfig>
  <AppConfig Executable="AkelPad.exe">
    <DEP Enable="true" EmulateAtlThunks="true" />
    <ASLR BottomUp="true" HighEntropy="false" />
    <StrictHandle Enable="true" />
    <SystemCalls DisableWin32kSystemCalls="false" Audit="true" />
    <ExtensionPoints DisableExtensionPoints="true" />
    <DynamicCode BlockDynamicCode="false" AllowThreadsToOptOut="false" Audit="true" />
    <SignedBinaries MicrosoftSignedOnly="false" AllowStoreSignedBinaries="true" Audit="true" AuditStoreSigned="true" EnforceModuleDependencySigning="false" />
    <Fonts DisableNonSystemFonts="false" AuditOnly="false" Audit="true" />
    <ImageLoad BlockRemoteImageLoads="false" AuditRemoteImageLoads="true" BlockLowLabelImageLoads="false" AuditLowLabelImageLoads="true" />
    <Payload EnableExportAddressFilter="false" AuditEnableExportAddressFilter="true" EnableExportAddressFilterPlus="false" AuditEnableExportAddressFilterPlus="true" EnableImportAddressFilter="false" AuditEnableImportAddressFilter="true" EnableRopStackPivot="true" AuditEnableRopStackPivot="false" EnableRopCallerCheck="false" AuditEnableRopCallerCheck="true" EnableRopSimExec="false" AuditEnableRopSimExec="true" />
    <SEHOP Enable="true" TelemetryOnly="false" />
    <Heap TerminateOnError="true" />
    <ChildProcess DisallowChildProcessCreation="false" Audit="true" />
    <UserShadowStack UserShadowStack="false" UserShadowStackStrictMode="true" AuditUserShadowStack="true" />
  </AppConfig>
  <AppConfig Executable="AutoClicker-3.1.exe">
    <DEP Enable="true" EmulateAtlThunks="false" />
    <ASLR BottomUp="true" HighEntropy="false" />
    <StrictHandle Enable="true" />
    <SystemCalls DisableWin32kSystemCalls="false" Audit="true" />
    <ExtensionPoints DisableExtensionPoints="true" />
    <DynamicCode BlockDynamicCode="false" AllowThreadsToOptOut="false" Audit="true" />
    <SignedBinaries MicrosoftSignedOnly="false" AllowStoreSignedBinaries="true" Audit="true" AuditStoreSigned="true" EnforceModuleDependencySigning="false" />
    <Fonts DisableNonSystemFonts="false" AuditOnly="false" Audit="true" />
    <ImageLoad BlockRemoteImageLoads="false" AuditRemoteImageLoads="true" BlockLowLabelImageLoads="false" AuditLowLabelImageLoads="true" />
    <Payload EnableExportAddressFilter="false" AuditEnableExportAddressFilter="true" EnableExportAddressFilterPlus="false" AuditEnableExportAddressFilterPlus="true" EnableImportAddressFilter="false" AuditEnableImportAddressFilter="true" EnableRopStackPivot="true" AuditEnableRopStackPivot="false" EnableRopCallerCheck="false" AuditEnableRopCallerCheck="true" EnableRopSimExec="false" AuditEnableRopSimExec="true" />
    <SEHOP Enable="true" TelemetryOnly="false" />
    <Heap TerminateOnError="true" />
    <ChildProcess DisallowChildProcessCreation="false" Audit="true" />
    <UserShadowStack UserShadowStack="false" UserShadowStackStrictMode="true" AuditUserShadowStack="true" />
  </AppConfig>
  <AppConfig Executable="AutoClicker.exe">
    <DEP Enable="true" EmulateAtlThunks="true" />
    <ASLR ForceRelocateImages="true" RequireInfo="true" BottomUp="true" HighEntropy="false" />
    <StrictHandle Enable="true" />
    <SystemCalls DisableWin32kSystemCalls="false" Audit="true" />
    <ExtensionPoints DisableExtensionPoints="true" />
    <DynamicCode BlockDynamicCode="false" AllowThreadsToOptOut="false" Audit="true" />
    <ControlFlowGuard Enable="true" SuppressExports="false" StrictControlFlowGuard="true" />
    <SignedBinaries MicrosoftSignedOnly="false" AllowStoreSignedBinaries="true" Audit="true" AuditStoreSigned="true" EnforceModuleDependencySigning="false" />
    <Fonts DisableNonSystemFonts="false" AuditOnly="false" Audit="true" />
    <ImageLoad BlockRemoteImageLoads="false" AuditRemoteImageLoads="true" BlockLowLabelImageLoads="false" AuditLowLabelImageLoads="true" />
    <Payload EnableExportAddressFilter="false" AuditEnableExportAddressFilter="true" EnableExportAddressFilterPlus="false" AuditEnableExportAddressFilterPlus="true" EnableImportAddressFilter="false" AuditEnableImportAddressFilter="true" EnableRopStackPivot="false" AuditEnableRopStackPivot="true" EnableRopCallerCheck="false" AuditEnableRopCallerCheck="true" EnableRopSimExec="false" AuditEnableRopSimExec="true" />
    <SEHOP Enable="true" TelemetryOnly="false" />
    <Heap TerminateOnError="true" />
    <ChildProcess DisallowChildProcessCreation="false" Audit="true" />
    <UserShadowStack UserShadowStack="false" UserShadowStackStrictMode="true" AuditUserShadowStack="true" />
  </AppConfig>
  <AppConfig Executable="CareUEyes 2.4.10.0.exe">
    <DEP Enable="true" EmulateAtlThunks="true" />
    <ASLR BottomUp="true" HighEntropy="false" />
    <StrictHandle Enable="true" />
    <SystemCalls DisableWin32kSystemCalls="false" Audit="true" />
    <ExtensionPoints DisableExtensionPoints="true" />
    <DynamicCode BlockDynamicCode="false" AllowThreadsToOptOut="false" Audit="true" />
    <SignedBinaries MicrosoftSignedOnly="false" AllowStoreSignedBinaries="true" Audit="true" AuditStoreSigned="true" EnforceModuleDependencySigning="false" />
    <Fonts DisableNonSystemFonts="false" AuditOnly="false" Audit="true" />
    <ImageLoad BlockRemoteImageLoads="false" AuditRemoteImageLoads="true" BlockLowLabelImageLoads="false" AuditLowLabelImageLoads="true" />
    <Payload EnableExportAddressFilter="false" AuditEnableExportAddressFilter="true" EnableExportAddressFilterPlus="false" AuditEnableExportAddressFilterPlus="true" EnableImportAddressFilter="false" AuditEnableImportAddressFilter="true" EnableRopStackPivot="true" AuditEnableRopStackPivot="false" EnableRopCallerCheck="false" AuditEnableRopCallerCheck="true" EnableRopSimExec="false" AuditEnableRopSimExec="true" />
    <SEHOP Enable="true" TelemetryOnly="false" />
    <Heap TerminateOnError="true" />
    <ChildProcess DisallowChildProcessCreation="false" Audit="true" />
    <UserShadowStack UserShadowStack="true" UserShadowStackStrictMode="true" AuditUserShadowStack="false" />
  </AppConfig>
  <AppConfig Executable="CareUEyes.exe">
    <DEP Enable="true" EmulateAtlThunks="false" />
    <ASLR BottomUp="true" HighEntropy="false" />
    <StrictHandle Enable="true" />
    <SystemCalls DisableWin32kSystemCalls="false" Audit="true" />
    <ExtensionPoints DisableExtensionPoints="true" />
    <DynamicCode BlockDynamicCode="false" AllowThreadsToOptOut="false" Audit="true" />
    <SignedBinaries MicrosoftSignedOnly="false" AllowStoreSignedBinaries="true" Audit="true" AuditStoreSigned="true" EnforceModuleDependencySigning="false" />
    <Fonts DisableNonSystemFonts="false" AuditOnly="false" Audit="true" />
    <ImageLoad BlockRemoteImageLoads="false" AuditRemoteImageLoads="true" BlockLowLabelImageLoads="false" AuditLowLabelImageLoads="true" />
    <Payload EnableExportAddressFilter="false" AuditEnableExportAddressFilter="true" EnableExportAddressFilterPlus="false" AuditEnableExportAddressFilterPlus="true" EnableImportAddressFilter="false" AuditEnableImportAddressFilter="true" EnableRopStackPivot="true" AuditEnableRopStackPivot="false" EnableRopCallerCheck="false" AuditEnableRopCallerCheck="true" EnableRopSimExec="false" AuditEnableRopSimExec="true" />
    <SEHOP Enable="true" TelemetryOnly="false" />
    <Heap TerminateOnError="true" />
    <ChildProcess DisallowChildProcessCreation="false" Audit="true" />
    <UserShadowStack UserShadowStack="true" UserShadowStackStrictMode="true" AuditUserShadowStack="false" />
  </AppConfig>
  <AppConfig Executable="CCEnhancer.exe">
    <DEP Enable="true" EmulateAtlThunks="true" />
    <ASLR ForceRelocateImages="true" RequireInfo="false" BottomUp="true" HighEntropy="false" />
    <StrictHandle Enable="true" />
    <SystemCalls DisableWin32kSystemCalls="false" Audit="true" />
    <ExtensionPoints DisableExtensionPoints="true" />
    <DynamicCode BlockDynamicCode="true" AllowThreadsToOptOut="true" Audit="false" />
    <ControlFlowGuard Enable="true" SuppressExports="false" StrictControlFlowGuard="true" />
    <SignedBinaries MicrosoftSignedOnly="true" AllowStoreSignedBinaries="true" Audit="false" AuditStoreSigned="false" EnforceModuleDependencySigning="true" />
    <Fonts DisableNonSystemFonts="true" AuditOnly="false" Audit="false" />
    <ImageLoad BlockRemoteImageLoads="true" AuditRemoteImageLoads="false" BlockLowLabelImageLoads="true" AuditLowLabelImageLoads="false" />
    <Payload EnableExportAddressFilter="false" AuditEnableExportAddressFilter="true" EnableExportAddressFilterPlus="false" AuditEnableExportAddressFilterPlus="true" EnableImportAddressFilter="true" AuditEnableImportAddressFilter="false" EnableRopStackPivot="true" AuditEnableRopStackPivot="false" EnableRopCallerCheck="true" AuditEnableRopCallerCheck="false" EnableRopSimExec="true" AuditEnableRopSimExec="false" />
    <SEHOP Enable="true" TelemetryOnly="false" />
    <Heap TerminateOnError="true" />
    <ChildProcess DisallowChildProcessCreation="false" Audit="true" />
    <UserShadowStack UserShadowStack="true" UserShadowStackStrictMode="true" AuditUserShadowStack="false" />
  </AppConfig>
  <AppConfig Executable="CCleaner.exe">
    <DEP Enable="true" EmulateAtlThunks="true" />
    <ASLR BottomUp="true" HighEntropy="false" />
    <StrictHandle Enable="true" />
    <SystemCalls DisableWin32kSystemCalls="false" Audit="true" />
    <ExtensionPoints DisableExtensionPoints="true" />
    <DynamicCode BlockDynamicCode="false" AllowThreadsToOptOut="false" Audit="true" />
    <SignedBinaries MicrosoftSignedOnly="false" AllowStoreSignedBinaries="true" Audit="true" AuditStoreSigned="true" EnforceModuleDependencySigning="false" />
    <Fonts DisableNonSystemFonts="false" AuditOnly="false" Audit="true" />
    <ImageLoad BlockRemoteImageLoads="false" AuditRemoteImageLoads="true" BlockLowLabelImageLoads="false" AuditLowLabelImageLoads="true" />
    <Payload EnableExportAddressFilter="false" AuditEnableExportAddressFilter="true" EnableExportAddressFilterPlus="false" AuditEnableExportAddressFilterPlus="true" EnableImportAddressFilter="false" AuditEnableImportAddressFilter="true" EnableRopStackPivot="true" AuditEnableRopStackPivot="false" EnableRopCallerCheck="false" AuditEnableRopCallerCheck="true" EnableRopSimExec="false" AuditEnableRopSimExec="true" />
    <SEHOP Enable="true" TelemetryOnly="false" />
    <Heap TerminateOnError="true" />
    <ChildProcess DisallowChildProcessCreation="false" Audit="true" />
    <UserShadowStack UserShadowStack="true" UserShadowStackStrictMode="true" AuditUserShadowStack="false" />
  </AppConfig>
  <AppConfig Executable="CCleaner64.exe">
    <DEP Enable="true" EmulateAtlThunks="true" />
    <ASLR BottomUp="true" HighEntropy="false" />
    <StrictHandle Enable="true" />
    <SystemCalls DisableWin32kSystemCalls="false" Audit="true" />
    <ExtensionPoints DisableExtensionPoints="true" />
    <DynamicCode BlockDynamicCode="false" AllowThreadsToOptOut="false" Audit="true" />
    <SignedBinaries MicrosoftSignedOnly="false" AllowStoreSignedBinaries="true" Audit="true" AuditStoreSigned="true" EnforceModuleDependencySigning="false" />
    <Fonts DisableNonSystemFonts="false" AuditOnly="false" Audit="true" />
    <ImageLoad BlockRemoteImageLoads="false" AuditRemoteImageLoads="true" BlockLowLabelImageLoads="false" AuditLowLabelImageLoads="true" />
    <Payload EnableExportAddressFilter="false" AuditEnableExportAddressFilter="true" EnableExportAddressFilterPlus="false" AuditEnableExportAddressFilterPlus="true" EnableImportAddressFilter="false" AuditEnableImportAddressFilter="true" EnableRopStackPivot="true" AuditEnableRopStackPivot="false" EnableRopCallerCheck="false" AuditEnableRopCallerCheck="true" EnableRopSimExec="false" AuditEnableRopSimExec="true" />
    <SEHOP Enable="true" TelemetryOnly="false" />
    <Heap TerminateOnError="true" />
    <ChildProcess DisallowChildProcessCreation="false" Audit="true" />
    <UserShadowStack UserShadowStack="true" UserShadowStackStrictMode="true" AuditUserShadowStack="false" />
  </AppConfig>
  <AppConfig Executable="cef_browser_process.exe">
    <DEP Enable="true" EmulateAtlThunks="true" />
    <ASLR BottomUp="true" HighEntropy="true" />
    <StrictHandle Enable="true" />
    <SystemCalls DisableWin32kSystemCalls="false" Audit="true" />
    <ExtensionPoints DisableExtensionPoints="true" />
    <DynamicCode BlockDynamicCode="false" AllowThreadsToOptOut="false" Audit="true" />
    <SignedBinaries MicrosoftSignedOnly="false" AllowStoreSignedBinaries="true" Audit="true" AuditStoreSigned="true" EnforceModuleDependencySigning="true" />
    <Fonts DisableNonSystemFonts="false" AuditOnly="false" Audit="true" />
    <ImageLoad BlockRemoteImageLoads="false" AuditRemoteImageLoads="true" BlockLowLabelImageLoads="false" AuditLowLabelImageLoads="true" />
    <Payload EnableExportAddressFilter="false" AuditEnableExportAddressFilter="true" EnableExportAddressFilterPlus="false" AuditEnableExportAddressFilterPlus="true" EnableImportAddressFilter="true" AuditEnableImportAddressFilter="false" EnableRopStackPivot="true" AuditEnableRopStackPivot="false" EnableRopCallerCheck="true" AuditEnableRopCallerCheck="false" EnableRopSimExec="true" AuditEnableRopSimExec="false" />
    <SEHOP Enable="true" TelemetryOnly="false" />
    <Heap TerminateOnError="true" />
    <ChildProcess DisallowChildProcessCreation="false" Audit="true" />
    <UserShadowStack UserShadowStack="true" UserShadowStackStrictMode="true" AuditUserShadowStack="false" />
  </AppConfig>
  <AppConfig Executable="cef_subprocess.exe">
    <DEP Enable="true" EmulateAtlThunks="true" />
    <ASLR BottomUp="true" HighEntropy="true" />
    <StrictHandle Enable="true" />
    <SystemCalls DisableWin32kSystemCalls="true" Audit="false" />
    <ExtensionPoints DisableExtensionPoints="true" />
    <DynamicCode BlockDynamicCode="true" AllowThreadsToOptOut="true" Audit="false" />
    <SignedBinaries MicrosoftSignedOnly="false" AllowStoreSignedBinaries="true" Audit="true" AuditStoreSigned="true" EnforceModuleDependencySigning="true" />
    <Fonts DisableNonSystemFonts="true" AuditOnly="false" Audit="false" />
    <ImageLoad BlockRemoteImageLoads="true" AuditRemoteImageLoads="false" BlockLowLabelImageLoads="true" AuditLowLabelImageLoads="false" />
    <Payload EnableExportAddressFilter="true" AuditEnableExportAddressFilter="false" EnableExportAddressFilterPlus="true" AuditEnableExportAddressFilterPlus="false" EnableImportAddressFilter="true" AuditEnableImportAddressFilter="false" EnableRopStackPivot="true" AuditEnableRopStackPivot="false" EnableRopCallerCheck="true" AuditEnableRopCallerCheck="false" EnableRopSimExec="true" AuditEnableRopSimExec="false" />
    <SEHOP Enable="true" TelemetryOnly="false" />
    <Heap TerminateOnError="true" />
    <ChildProcess DisallowChildProcessCreation="true" Audit="false" />
    <UserShadowStack UserShadowStack="true" UserShadowStackStrictMode="true" AuditUserShadowStack="false" />
  </AppConfig>
  <AppConfig Executable="chrmstp.exe">
    <DEP Enable="true" EmulateAtlThunks="false" />
    <ASLR ForceRelocateImages="true" RequireInfo="false" BottomUp="true" HighEntropy="true" />
    <StrictHandle Enable="true" />
    <SystemCalls DisableWin32kSystemCalls="true" Audit="false" />
    <ExtensionPoints DisableExtensionPoints="false" />
    <DynamicCode BlockDynamicCode="true" AllowThreadsToOptOut="true" Audit="false" />
    <ControlFlowGuard Enable="true" SuppressExports="false" />
    <SignedBinaries MicrosoftSignedOnly="true" AllowStoreSignedBinaries="false" Audit="false" AuditStoreSigned="false" EnforceModuleDependencySigning="true" />
    <Fonts DisableNonSystemFonts="true" AuditOnly="false" Audit="false" />
    <ImageLoad BlockRemoteImageLoads="true" AuditRemoteImageLoads="false" BlockLowLabelImageLoads="true" AuditLowLabelImageLoads="false" />
    <Payload EnableExportAddressFilter="true" AuditEnableExportAddressFilter="false" EnableImportAddressFilter="true" AuditEnableImportAddressFilter="false" EnableRopStackPivot="true" AuditEnableRopStackPivot="false" EnableRopCallerCheck="true" AuditEnableRopCallerCheck="false" EnableRopSimExec="true" AuditEnableRopSimExec="false" />
    <SEHOP Enable="true" TelemetryOnly="false" />
    <Heap TerminateOnError="true" />
    <ChildProcess DisallowChildProcessCreation="true" Audit="false" />
    <UserShadowStack UserShadowStack="true" UserShadowStackStrictMode="true" AuditUserShadowStack="false" />
  </AppConfig>
  <AppConfig Executable="chrome.exe">
    <DEP Enable="true" EmulateAtlThunks="true" />
    <ASLR ForceRelocateImages="true" RequireInfo="true" BottomUp="true" HighEntropy="false" />
    <StrictHandle Enable="true" />
    <SystemCalls DisableWin32kSystemCalls="false" Audit="true" />
    <ExtensionPoints DisableExtensionPoints="true" />
    <DynamicCode BlockDynamicCode="false" AllowThreadsToOptOut="false" Audit="true" />
    <ControlFlowGuard Enable="true" SuppressExports="false" StrictControlFlowGuard="true" />
    <SignedBinaries MicrosoftSignedOnly="false" AllowStoreSignedBinaries="true" Audit="true" AuditStoreSigned="true" EnforceModuleDependencySigning="false" />
    <Fonts DisableNonSystemFonts="false" AuditOnly="false" Audit="true" />
    <ImageLoad BlockRemoteImageLoads="false" AuditRemoteImageLoads="true" BlockLowLabelImageLoads="false" AuditLowLabelImageLoads="true" />
    <Payload EnableExportAddressFilter="false" AuditEnableExportAddressFilter="true" EnableExportAddressFilterPlus="false" AuditEnableExportAddressFilterPlus="true" EnableImportAddressFilter="false" AuditEnableImportAddressFilter="true" EnableRopStackPivot="true" AuditEnableRopStackPivot="false" />
    <SEHOP Enable="true" TelemetryOnly="false" />
    <Heap TerminateOnError="true" />
    <ChildProcess DisallowChildProcessCreation="false" Audit="true" />
    <UserShadowStack UserShadowStack="false" UserShadowStackStrictMode="true" AuditUserShadowStack="true" />
  </AppConfig>
  <AppConfig Executable="chrome_installer.exe">
    <DEP Enable="true" EmulateAtlThunks="true" />
    <ASLR ForceRelocateImages="true" RequireInfo="false" BottomUp="true" HighEntropy="true" />
    <StrictHandle Enable="true" />
    <SystemCalls DisableWin32kSystemCalls="true" Audit="false" />
    <ExtensionPoints DisableExtensionPoints="true" />
    <DynamicCode BlockDynamicCode="true" AllowThreadsToOptOut="true" Audit="false" />
    <ControlFlowGuard Enable="true" SuppressExports="false" StrictControlFlowGuard="true" />
    <SignedBinaries MicrosoftSignedOnly="true" AllowStoreSignedBinaries="true" Audit="false" AuditStoreSigned="false" EnforceModuleDependencySigning="true" />
    <Fonts DisableNonSystemFonts="true" AuditOnly="false" Audit="false" />
    <ImageLoad BlockRemoteImageLoads="true" AuditRemoteImageLoads="false" BlockLowLabelImageLoads="true" AuditLowLabelImageLoads="false" />
    <Payload EnableExportAddressFilter="true" AuditEnableExportAddressFilter="false" EnableExportAddressFilterPlus="true" AuditEnableExportAddressFilterPlus="false" EnableImportAddressFilter="true" AuditEnableImportAddressFilter="false" EnableRopStackPivot="true" AuditEnableRopStackPivot="false" EnableRopCallerCheck="true" AuditEnableRopCallerCheck="false" EnableRopSimExec="true" AuditEnableRopSimExec="false" />
    <SEHOP Enable="true" TelemetryOnly="false" />
    <Heap TerminateOnError="true" />
    <ChildProcess DisallowChildProcessCreation="true" Audit="false" />
    <UserShadowStack UserShadowStack="true" UserShadowStackStrictMode="true" AuditUserShadowStack="false" />
  </AppConfig>
  <AppConfig Executable="chrome_proxy.exe">
    <DEP Enable="true" EmulateAtlThunks="true" />
    <ASLR BottomUp="true" HighEntropy="false" />
    <StrictHandle Enable="true" />
    <SystemCalls DisableWin32kSystemCalls="false" Audit="true" />
    <ExtensionPoints DisableExtensionPoints="true" />
    <DynamicCode BlockDynamicCode="false" AllowThreadsToOptOut="false" Audit="true" />
    <SignedBinaries MicrosoftSignedOnly="false" AllowStoreSignedBinaries="true" Audit="true" AuditStoreSigned="true" EnforceModuleDependencySigning="false" />
    <Fonts DisableNonSystemFonts="false" AuditOnly="false" Audit="true" />
    <ImageLoad BlockRemoteImageLoads="false" AuditRemoteImageLoads="true" BlockLowLabelImageLoads="false" AuditLowLabelImageLoads="true" />
    <Payload EnableExportAddressFilter="false" AuditEnableExportAddressFilter="true" EnableExportAddressFilterPlus="false" AuditEnableExportAddressFilterPlus="true" EnableImportAddressFilter="false" AuditEnableImportAddressFilter="true" EnableRopStackPivot="false" AuditEnableRopStackPivot="true" EnableRopCallerCheck="false" AuditEnableRopCallerCheck="true" EnableRopSimExec="false" AuditEnableRopSimExec="true" />
    <SEHOP Enable="true" TelemetryOnly="false" />
    <Heap TerminateOnError="true" />
    <ChildProcess DisallowChildProcessCreation="false" Audit="true" />
    <UserShadowStack UserShadowStack="false" UserShadowStackStrictMode="true" AuditUserShadowStack="true" />
  </AppConfig>
  <AppConfig Executable="X:\Program Files\Google\Chrome\Application\139.0.7258.139\chrome_pwa_launcher.exe">
    <DEP Enable="true" EmulateAtlThunks="true" />
    <ASLR ForceRelocateImages="true" RequireInfo="false" BottomUp="true" HighEntropy="true" />
    <StrictHandle Enable="true" />
    <SystemCalls DisableWin32kSystemCalls="true" Audit="false" />
    <ExtensionPoints DisableExtensionPoints="true" />
    <DynamicCode BlockDynamicCode="true" AllowThreadsToOptOut="true" Audit="false" />
    <ControlFlowGuard Enable="true" SuppressExports="false" StrictControlFlowGuard="true" />
    <SignedBinaries MicrosoftSignedOnly="true" AllowStoreSignedBinaries="true" Audit="false" AuditStoreSigned="false" EnforceModuleDependencySigning="true" />
    <Fonts DisableNonSystemFonts="true" AuditOnly="false" Audit="false" />
    <ImageLoad BlockRemoteImageLoads="true" AuditRemoteImageLoads="false" BlockLowLabelImageLoads="true" AuditLowLabelImageLoads="false" />
    <Payload EnableExportAddressFilter="true" AuditEnableExportAddressFilter="false" EnableExportAddressFilterPlus="true" AuditEnableExportAddressFilterPlus="false" EnableImportAddressFilter="true" AuditEnableImportAddressFilter="false" EnableRopStackPivot="true" AuditEnableRopStackPivot="false" EnableRopCallerCheck="true" AuditEnableRopCallerCheck="false" EnableRopSimExec="true" AuditEnableRopSimExec="false" />
    <SEHOP Enable="true" TelemetryOnly="false" />
    <Heap TerminateOnError="true" />
    <ChildProcess DisallowChildProcessCreation="true" Audit="false" />
    <UserShadowStack UserShadowStack="true" UserShadowStackStrictMode="true" AuditUserShadowStack="false" />
  </AppConfig>
  <AppConfig Executable="cmd.exe">
    <Payload EnableRopStackPivot="true" AuditEnableRopStackPivot="false" />
    <Heap TerminateOnError="true" />
    <UserShadowStack UserShadowStack="true" UserShadowStackStrictMode="true" AuditUserShadowStack="false" />
  </AppConfig>
  <AppConfig Executable="com.westbyte.downloadmaster.exe">
    <DEP Enable="true" EmulateAtlThunks="true" />
    <ASLR ForceRelocateImages="true" RequireInfo="true" BottomUp="true" HighEntropy="false" />
    <StrictHandle Enable="true" />
    <SystemCalls DisableWin32kSystemCalls="false" Audit="true" />
    <ExtensionPoints DisableExtensionPoints="true" />
    <DynamicCode BlockDynamicCode="false" AllowThreadsToOptOut="false" Audit="true" />
    <ControlFlowGuard Enable="true" SuppressExports="false" StrictControlFlowGuard="true" />
    <SignedBinaries MicrosoftSignedOnly="false" AllowStoreSignedBinaries="true" Audit="true" AuditStoreSigned="true" EnforceModuleDependencySigning="true" />
    <Fonts DisableNonSystemFonts="false" AuditOnly="false" Audit="true" />
    <ImageLoad BlockRemoteImageLoads="false" AuditRemoteImageLoads="true" BlockLowLabelImageLoads="false" AuditLowLabelImageLoads="true" />
    <Payload EnableExportAddressFilter="false" AuditEnableExportAddressFilter="true" EnableExportAddressFilterPlus="false" AuditEnableExportAddressFilterPlus="true" EnableImportAddressFilter="false" AuditEnableImportAddressFilter="true" EnableRopStackPivot="true" AuditEnableRopStackPivot="false" EnableRopCallerCheck="false" AuditEnableRopCallerCheck="true" EnableRopSimExec="false" AuditEnableRopSimExec="true" />
    <SEHOP Enable="true" TelemetryOnly="false" />
    <Heap TerminateOnError="true" />
    <ChildProcess DisallowChildProcessCreation="false" Audit="true" />
    <UserShadowStack UserShadowStack="true" UserShadowStackStrictMode="true" AuditUserShadowStack="false" />
  </AppConfig>
  <AppConfig Executable="dbInstaller.exe">
    <DEP Enable="true" EmulateAtlThunks="true" />
    <ASLR ForceRelocateImages="true" RequireInfo="true" BottomUp="true" HighEntropy="false" />
    <StrictHandle Enable="true" />
    <SystemCalls DisableWin32kSystemCalls="false" Audit="true" />
    <ExtensionPoints DisableExtensionPoints="true" />
    <DynamicCode BlockDynamicCode="false" AllowThreadsToOptOut="false" Audit="true" />
    <ControlFlowGuard Enable="true" SuppressExports="false" StrictControlFlowGuard="true" />
    <SignedBinaries MicrosoftSignedOnly="false" AllowStoreSignedBinaries="true" Audit="true" AuditStoreSigned="true" EnforceModuleDependencySigning="false" />
    <Fonts DisableNonSystemFonts="false" AuditOnly="false" Audit="true" />
    <ImageLoad BlockRemoteImageLoads="false" AuditRemoteImageLoads="true" BlockLowLabelImageLoads="false" AuditLowLabelImageLoads="true" />
    <Payload EnableExportAddressFilter="false" AuditEnableExportAddressFilter="true" EnableExportAddressFilterPlus="false" AuditEnableExportAddressFilterPlus="true" EnableImportAddressFilter="false" AuditEnableImportAddressFilter="true" EnableRopStackPivot="false" AuditEnableRopStackPivot="true" EnableRopCallerCheck="false" AuditEnableRopCallerCheck="true" EnableRopSimExec="false" AuditEnableRopSimExec="true" />
    <SEHOP Enable="true" TelemetryOnly="false" />
    <Heap TerminateOnError="true" />
    <ChildProcess DisallowChildProcessCreation="false" Audit="true" />
    <UserShadowStack UserShadowStack="false" UserShadowStackStrictMode="true" AuditUserShadowStack="true" />
  </AppConfig>
  <AppConfig Executable="DesktopHook.exe">
    <DEP Enable="true" EmulateAtlThunks="true" />
    <ASLR ForceRelocateImages="true" RequireInfo="false" BottomUp="true" HighEntropy="true" />
    <StrictHandle Enable="true" />
    <SystemCalls DisableWin32kSystemCalls="true" Audit="false" />
    <ExtensionPoints DisableExtensionPoints="true" />
    <DynamicCode BlockDynamicCode="true" AllowThreadsToOptOut="true" Audit="false" />
    <ControlFlowGuard Enable="true" SuppressExports="false" StrictControlFlowGuard="true" />
    <SignedBinaries MicrosoftSignedOnly="true" AllowStoreSignedBinaries="false" Audit="false" AuditStoreSigned="false" EnforceModuleDependencySigning="true" />
    <Fonts DisableNonSystemFonts="true" AuditOnly="false" Audit="false" />
    <ImageLoad BlockRemoteImageLoads="true" AuditRemoteImageLoads="false" BlockLowLabelImageLoads="true" AuditLowLabelImageLoads="false" />
    <Payload EnableExportAddressFilter="true" AuditEnableExportAddressFilter="false" EnableExportAddressFilterPlus="true" AuditEnableExportAddressFilterPlus="false" EnableImportAddressFilter="true" AuditEnableImportAddressFilter="false" EnableRopStackPivot="true" AuditEnableRopStackPivot="false" EnableRopCallerCheck="true" AuditEnableRopCallerCheck="false" EnableRopSimExec="true" AuditEnableRopSimExec="false" />
    <SEHOP Enable="true" TelemetryOnly="false" />
    <Heap TerminateOnError="true" />
    <ChildProcess DisallowChildProcessCreation="true" Audit="false" />
    <UserShadowStack UserShadowStack="true" UserShadowStackStrictMode="true" AuditUserShadowStack="false" />
  </AppConfig>
  <AppConfig Executable="DesktopHook64.exe">
    <DEP Enable="true" EmulateAtlThunks="false" />
    <ASLR ForceRelocateImages="true" RequireInfo="false" BottomUp="true" HighEntropy="true" />
    <StrictHandle Enable="false" />
    <SystemCalls DisableWin32kSystemCalls="true" Audit="false" />
    <ExtensionPoints DisableExtensionPoints="true" />
    <DynamicCode BlockDynamicCode="true" AllowThreadsToOptOut="false" Audit="false" />
    <ControlFlowGuard Enable="true" SuppressExports="false" StrictControlFlowGuard="true" />
    <SignedBinaries MicrosoftSignedOnly="true" AllowStoreSignedBinaries="true" Audit="false" AuditStoreSigned="false" EnforceModuleDependencySigning="true" />
    <Fonts DisableNonSystemFonts="true" AuditOnly="false" Audit="false" />
    <ImageLoad BlockRemoteImageLoads="true" AuditRemoteImageLoads="false" BlockLowLabelImageLoads="true" AuditLowLabelImageLoads="false" />
    <Payload EnableExportAddressFilter="true" AuditEnableExportAddressFilter="false" EnableImportAddressFilter="true" AuditEnableImportAddressFilter="false" EnableRopStackPivot="true" AuditEnableRopStackPivot="false" EnableRopCallerCheck="true" AuditEnableRopCallerCheck="false" EnableRopSimExec="true" AuditEnableRopSimExec="false" />
    <SEHOP Enable="true" TelemetryOnly="false" />
    <Heap TerminateOnError="true" />
    <ChildProcess DisallowChildProcessCreation="true" Audit="false" />
    <UserShadowStack UserShadowStack="true" UserShadowStackStrictMode="true" AuditUserShadowStack="false" />
  </AppConfig>
  <AppConfig Executable="DfSdkS.exe">
    <DEP Enable="true" EmulateAtlThunks="true" />
    <ASLR ForceRelocateImages="true" RequireInfo="false" BottomUp="true" HighEntropy="true" />
    <StrictHandle Enable="true" />
    <SystemCalls DisableWin32kSystemCalls="true" Audit="false" />
    <ExtensionPoints DisableExtensionPoints="true" />
    <DynamicCode BlockDynamicCode="true" AllowThreadsToOptOut="false" Audit="false" />
    <ControlFlowGuard Enable="true" SuppressExports="false" StrictControlFlowGuard="true" />
    <SignedBinaries MicrosoftSignedOnly="true" AllowStoreSignedBinaries="true" Audit="false" AuditStoreSigned="false" EnforceModuleDependencySigning="true" />
    <Fonts DisableNonSystemFonts="true" AuditOnly="false" Audit="false" />
    <ImageLoad BlockRemoteImageLoads="true" AuditRemoteImageLoads="false" BlockLowLabelImageLoads="true" AuditLowLabelImageLoads="false" />
    <Payload EnableExportAddressFilter="true" AuditEnableExportAddressFilter="false" EnableExportAddressFilterPlus="true" AuditEnableExportAddressFilterPlus="false" EnableImportAddressFilter="true" AuditEnableImportAddressFilter="false" EnableRopStackPivot="true" AuditEnableRopStackPivot="false" EnableRopCallerCheck="true" AuditEnableRopCallerCheck="false" EnableRopSimExec="true" AuditEnableRopSimExec="false" />
    <SEHOP Enable="true" TelemetryOnly="false" />
    <Heap TerminateOnError="true" />
    <ChildProcess DisallowChildProcessCreation="true" Audit="false" />
    <UserShadowStack UserShadowStack="true" UserShadowStackStrictMode="true" AuditUserShadowStack="false" />
  </AppConfig>
  <AppConfig Executable="Display Driver Uninstaller.exe">
    <DEP Enable="true" EmulateAtlThunks="false" />
    <ASLR BottomUp="true" HighEntropy="false" />
    <StrictHandle Enable="true" />
    <SystemCalls DisableWin32kSystemCalls="true" Audit="false" />
    <ExtensionPoints DisableExtensionPoints="true" />
    <DynamicCode BlockDynamicCode="false" AllowThreadsToOptOut="false" Audit="true" />
    <SignedBinaries MicrosoftSignedOnly="false" AllowStoreSignedBinaries="true" Audit="true" AuditStoreSigned="true" EnforceModuleDependencySigning="false" />
    <Fonts DisableNonSystemFonts="false" AuditOnly="false" Audit="true" />
    <ImageLoad BlockRemoteImageLoads="false" AuditRemoteImageLoads="true" BlockLowLabelImageLoads="false" AuditLowLabelImageLoads="true" />
    <Payload EnableExportAddressFilter="false" AuditEnableExportAddressFilter="true" EnableExportAddressFilterPlus="false" AuditEnableExportAddressFilterPlus="true" EnableImportAddressFilter="false" AuditEnableImportAddressFilter="true" EnableRopStackPivot="true" AuditEnableRopStackPivot="false" EnableRopCallerCheck="false" AuditEnableRopCallerCheck="true" EnableRopSimExec="false" AuditEnableRopSimExec="true" />
    <SEHOP Enable="true" TelemetryOnly="false" />
    <Heap TerminateOnError="true" />
    <ChildProcess DisallowChildProcessCreation="false" Audit="true" />
    <UserShadowStack UserShadowStack="true" UserShadowStackStrictMode="true" AuditUserShadowStack="false" />
  </AppConfig>
  <AppConfig Executable="dmaster.exe">
    <DEP Enable="true" EmulateAtlThunks="true" />
    <ASLR BottomUp="true" HighEntropy="false" />
    <StrictHandle Enable="true" />
    <SystemCalls DisableWin32kSystemCalls="false" Audit="true" />
    <ExtensionPoints DisableExtensionPoints="true" />
    <DynamicCode BlockDynamicCode="false" AllowThreadsToOptOut="false" Audit="true" />
    <SignedBinaries MicrosoftSignedOnly="false" AllowStoreSignedBinaries="true" Audit="true" AuditStoreSigned="true" EnforceModuleDependencySigning="false" />
    <Fonts DisableNonSystemFonts="false" AuditOnly="false" Audit="true" />
    <ImageLoad BlockRemoteImageLoads="false" AuditRemoteImageLoads="true" BlockLowLabelImageLoads="false" AuditLowLabelImageLoads="true" />
    <Payload EnableExportAddressFilter="false" AuditEnableExportAddressFilter="true" EnableExportAddressFilterPlus="false" AuditEnableExportAddressFilterPlus="true" EnableImportAddressFilter="false" AuditEnableImportAddressFilter="true" EnableRopStackPivot="false" AuditEnableRopStackPivot="true" EnableRopCallerCheck="false" AuditEnableRopCallerCheck="true" EnableRopSimExec="false" AuditEnableRopSimExec="true" />
    <SEHOP Enable="true" TelemetryOnly="false" />
    <Heap TerminateOnError="true" />
    <ChildProcess DisallowChildProcessCreation="false" Audit="true" />
    <UserShadowStack UserShadowStack="false" UserShadowStackStrictMode="true" AuditUserShadowStack="true" />
  </AppConfig>
  <AppConfig Executable="DnsJumper.exe">
    <DEP Enable="true" EmulateAtlThunks="false" />
    <ASLR BottomUp="true" HighEntropy="false" />
    <StrictHandle Enable="true" />
    <SystemCalls DisableWin32kSystemCalls="true" Audit="false" />
    <ExtensionPoints DisableExtensionPoints="true" />
    <DynamicCode BlockDynamicCode="false" AllowThreadsToOptOut="false" Audit="true" />
    <SignedBinaries MicrosoftSignedOnly="false" AllowStoreSignedBinaries="true" Audit="true" AuditStoreSigned="true" EnforceModuleDependencySigning="false" />
    <Fonts DisableNonSystemFonts="false" AuditOnly="false" Audit="true" />
    <ImageLoad BlockRemoteImageLoads="false" AuditRemoteImageLoads="true" BlockLowLabelImageLoads="false" AuditLowLabelImageLoads="true" />
    <Payload EnableExportAddressFilter="false" AuditEnableExportAddressFilter="true" EnableExportAddressFilterPlus="false" AuditEnableExportAddressFilterPlus="true" EnableImportAddressFilter="false" AuditEnableImportAddressFilter="true" EnableRopStackPivot="true" AuditEnableRopStackPivot="false" EnableRopCallerCheck="false" AuditEnableRopCallerCheck="true" EnableRopSimExec="false" AuditEnableRopSimExec="true" />
    <SEHOP Enable="true" TelemetryOnly="false" />
    <Heap TerminateOnError="true" />
    <ChildProcess DisallowChildProcessCreation="false" Audit="true" />
    <UserShadowStack UserShadowStack="true" UserShadowStackStrictMode="true" AuditUserShadowStack="false" />
  </AppConfig>
  <AppConfig Executable="downloader.exe">
    <DEP Enable="true" EmulateAtlThunks="true" />
    <ASLR ForceRelocateImages="true" RequireInfo="false" BottomUp="true" HighEntropy="true" />
    <StrictHandle Enable="true" />
    <SystemCalls DisableWin32kSystemCalls="true" Audit="false" />
    <ExtensionPoints DisableExtensionPoints="true" />
    <DynamicCode BlockDynamicCode="true" AllowThreadsToOptOut="true" Audit="false" />
    <ControlFlowGuard Enable="true" SuppressExports="false" StrictControlFlowGuard="true" />
    <SignedBinaries MicrosoftSignedOnly="true" AllowStoreSignedBinaries="false" Audit="false" AuditStoreSigned="false" EnforceModuleDependencySigning="true" />
    <Fonts DisableNonSystemFonts="true" AuditOnly="false" Audit="false" />
    <ImageLoad BlockRemoteImageLoads="true" AuditRemoteImageLoads="false" BlockLowLabelImageLoads="true" AuditLowLabelImageLoads="false" />
    <Payload EnableExportAddressFilter="true" AuditEnableExportAddressFilter="false" EnableExportAddressFilterPlus="true" AuditEnableExportAddressFilterPlus="false" EnableImportAddressFilter="true" AuditEnableImportAddressFilter="false" EnableRopStackPivot="true" AuditEnableRopStackPivot="false" EnableRopCallerCheck="true" AuditEnableRopCallerCheck="false" EnableRopSimExec="false" AuditEnableRopSimExec="true" />
    <SEHOP Enable="true" TelemetryOnly="false" />
    <Heap TerminateOnError="true" />
    <ChildProcess DisallowChildProcessCreation="true" Audit="false" />
    <UserShadowStack UserShadowStack="true" UserShadowStackStrictMode="true" AuditUserShadowStack="false" />
  </AppConfig>
  <AppConfig Executable="DTDrop64.exe">
    <DEP Enable="true" EmulateAtlThunks="false" />
    <ASLR ForceRelocateImages="true" RequireInfo="false" BottomUp="true" HighEntropy="true" />
    <StrictHandle Enable="true" />
    <SystemCalls DisableWin32kSystemCalls="true" Audit="false" />
    <ExtensionPoints DisableExtensionPoints="true" />
    <DynamicCode BlockDynamicCode="true" AllowThreadsToOptOut="false" Audit="false" />
    <ControlFlowGuard Enable="true" SuppressExports="false" StrictControlFlowGuard="true" />
    <SignedBinaries MicrosoftSignedOnly="true" AllowStoreSignedBinaries="false" Audit="false" AuditStoreSigned="false" EnforceModuleDependencySigning="true" />
    <Fonts DisableNonSystemFonts="true" AuditOnly="false" Audit="false" />
    <ImageLoad BlockRemoteImageLoads="true" AuditRemoteImageLoads="false" BlockLowLabelImageLoads="true" AuditLowLabelImageLoads="false" />
    <Payload EnableExportAddressFilter="true" AuditEnableExportAddressFilter="false" EnableImportAddressFilter="true" AuditEnableImportAddressFilter="false" EnableRopStackPivot="true" AuditEnableRopStackPivot="false" EnableRopCallerCheck="true" AuditEnableRopCallerCheck="false" EnableRopSimExec="true" AuditEnableRopSimExec="false" />
    <SEHOP Enable="true" TelemetryOnly="false" />
    <Heap TerminateOnError="true" />
    <ChildProcess DisallowChildProcessCreation="true" Audit="false" />
    <UserShadowStack UserShadowStack="true" UserShadowStackStrictMode="false" AuditUserShadowStack="false" />
  </AppConfig>
  <AppConfig Executable="EcMenu.exe">
    <DEP Enable="true" EmulateAtlThunks="false" />
    <ASLR BottomUp="true" HighEntropy="false" />
    <StrictHandle Enable="true" />
    <SystemCalls DisableWin32kSystemCalls="true" Audit="false" />
    <ExtensionPoints DisableExtensionPoints="true" />
    <DynamicCode BlockDynamicCode="false" AllowThreadsToOptOut="false" Audit="true" />
    <SignedBinaries MicrosoftSignedOnly="false" AllowStoreSignedBinaries="true" Audit="true" AuditStoreSigned="true" EnforceModuleDependencySigning="false" />
    <Fonts DisableNonSystemFonts="false" AuditOnly="false" Audit="true" />
    <ImageLoad BlockRemoteImageLoads="false" AuditRemoteImageLoads="true" BlockLowLabelImageLoads="false" AuditLowLabelImageLoads="true" />
    <Payload EnableExportAddressFilter="false" AuditEnableExportAddressFilter="true" EnableExportAddressFilterPlus="false" AuditEnableExportAddressFilterPlus="true" EnableImportAddressFilter="false" AuditEnableImportAddressFilter="true" EnableRopStackPivot="true" AuditEnableRopStackPivot="false" EnableRopCallerCheck="false" AuditEnableRopCallerCheck="true" EnableRopSimExec="false" AuditEnableRopSimExec="true" />
    <SEHOP Enable="true" TelemetryOnly="false" />
    <Heap TerminateOnError="true" />
    <ChildProcess DisallowChildProcessCreation="false" Audit="true" />
    <UserShadowStack UserShadowStack="true" UserShadowStackStrictMode="true" AuditUserShadowStack="false" />
  </AppConfig>
  <AppConfig Executable="EcMenu_x64.exe">
    <DEP Enable="true" EmulateAtlThunks="false" />
    <ASLR BottomUp="true" HighEntropy="false" />
    <StrictHandle Enable="true" />
    <SystemCalls DisableWin32kSystemCalls="true" Audit="false" />
    <ExtensionPoints DisableExtensionPoints="true" />
    <DynamicCode BlockDynamicCode="false" AllowThreadsToOptOut="false" Audit="true" />
    <SignedBinaries MicrosoftSignedOnly="false" AllowStoreSignedBinaries="true" Audit="true" AuditStoreSigned="true" EnforceModuleDependencySigning="false" />
    <Fonts DisableNonSystemFonts="false" AuditOnly="false" Audit="true" />
    <ImageLoad BlockRemoteImageLoads="false" AuditRemoteImageLoads="true" BlockLowLabelImageLoads="false" AuditLowLabelImageLoads="true" />
    <Payload EnableExportAddressFilter="false" AuditEnableExportAddressFilter="true" EnableExportAddressFilterPlus="false" AuditEnableExportAddressFilterPlus="true" EnableImportAddressFilter="false" AuditEnableImportAddressFilter="true" EnableRopStackPivot="true" AuditEnableRopStackPivot="false" EnableRopCallerCheck="false" AuditEnableRopCallerCheck="true" EnableRopSimExec="false" AuditEnableRopSimExec="true" />
    <SEHOP Enable="true" TelemetryOnly="false" />
    <Heap TerminateOnError="true" />
    <ChildProcess DisallowChildProcessCreation="false" Audit="true" />
    <UserShadowStack UserShadowStack="true" UserShadowStackStrictMode="true" AuditUserShadowStack="false" />
  </AppConfig>
  <AppConfig Executable="elevated_tracing_service.exe">
    <DEP Enable="true" EmulateAtlThunks="true" />
    <ASLR ForceRelocateImages="true" RequireInfo="false" BottomUp="true" HighEntropy="true" />
    <StrictHandle Enable="true" />
    <SystemCalls DisableWin32kSystemCalls="true" Audit="false" />
    <ExtensionPoints DisableExtensionPoints="true" />
    <DynamicCode BlockDynamicCode="true" AllowThreadsToOptOut="false" Audit="false" />
    <ControlFlowGuard Enable="true" SuppressExports="false" StrictControlFlowGuard="true" />
    <SignedBinaries MicrosoftSignedOnly="true" AllowStoreSignedBinaries="false" Audit="false" AuditStoreSigned="false" EnforceModuleDependencySigning="true" />
    <Fonts DisableNonSystemFonts="true" AuditOnly="false" Audit="false" />
    <ImageLoad BlockRemoteImageLoads="true" AuditRemoteImageLoads="false" BlockLowLabelImageLoads="true" AuditLowLabelImageLoads="false" />
    <Payload EnableExportAddressFilter="false" EnableImportAddressFilter="true" AuditEnableImportAddressFilter="false" EnableRopStackPivot="true" AuditEnableRopStackPivot="false" EnableRopCallerCheck="true" AuditEnableRopCallerCheck="false" EnableRopSimExec="true" AuditEnableRopSimExec="false" />
    <SEHOP Enable="true" TelemetryOnly="false" />
    <Heap TerminateOnError="true" />
    <ChildProcess DisallowChildProcessCreation="true" Audit="false" />
    <UserShadowStack UserShadowStack="true" UserShadowStackStrictMode="true" AuditUserShadowStack="false" />
  </AppConfig>
  <AppConfig Executable="elevation_service.exe">
    <DEP Enable="true" EmulateAtlThunks="true" />
    <ASLR BottomUp="true" HighEntropy="true" />
    <StrictHandle Enable="true" />
    <SystemCalls DisableWin32kSystemCalls="true" Audit="false" />
    <ExtensionPoints DisableExtensionPoints="true" />
    <DynamicCode BlockDynamicCode="true" AllowThreadsToOptOut="true" Audit="false" />
    <SignedBinaries MicrosoftSignedOnly="true" AllowStoreSignedBinaries="true" Audit="false" AuditStoreSigned="false" EnforceModuleDependencySigning="true" />
    <Fonts DisableNonSystemFonts="true" AuditOnly="false" Audit="false" />
    <ImageLoad BlockRemoteImageLoads="true" AuditRemoteImageLoads="false" BlockLowLabelImageLoads="true" AuditLowLabelImageLoads="false" />
    <Payload EnableExportAddressFilter="true" AuditEnableExportAddressFilter="false" EnableExportAddressFilterPlus="true" AuditEnableExportAddressFilterPlus="false" EnableImportAddressFilter="true" AuditEnableImportAddressFilter="false" EnableRopStackPivot="true" AuditEnableRopStackPivot="false" EnableRopCallerCheck="true" AuditEnableRopCallerCheck="false" EnableRopSimExec="true" AuditEnableRopSimExec="false" />
    <SEHOP Enable="true" TelemetryOnly="false" />
    <Heap TerminateOnError="true" />
    <ChildProcess DisallowChildProcessCreation="true" Audit="false" />
    <UserShadowStack UserShadowStack="true" UserShadowStackStrictMode="true" AuditUserShadowStack="false" />
  </AppConfig>
  <AppConfig Executable="EXEDecrypt.exe">
    <DEP Enable="true" EmulateAtlThunks="false" />
    <ASLR BottomUp="true" HighEntropy="false" />
    <StrictHandle Enable="true" />
    <SystemCalls DisableWin32kSystemCalls="true" Audit="false" />
    <ExtensionPoints DisableExtensionPoints="true" />
    <DynamicCode BlockDynamicCode="false" AllowThreadsToOptOut="false" Audit="true" />
    <SignedBinaries MicrosoftSignedOnly="false" AllowStoreSignedBinaries="true" Audit="true" AuditStoreSigned="true" EnforceModuleDependencySigning="false" />
    <Fonts DisableNonSystemFonts="false" AuditOnly="false" Audit="true" />
    <ImageLoad BlockRemoteImageLoads="false" AuditRemoteImageLoads="true" BlockLowLabelImageLoads="false" AuditLowLabelImageLoads="true" />
    <Payload EnableExportAddressFilter="false" AuditEnableExportAddressFilter="true" EnableExportAddressFilterPlus="false" AuditEnableExportAddressFilterPlus="true" EnableImportAddressFilter="false" AuditEnableImportAddressFilter="true" EnableRopStackPivot="true" AuditEnableRopStackPivot="false" EnableRopCallerCheck="false" AuditEnableRopCallerCheck="true" EnableRopSimExec="false" AuditEnableRopSimExec="true" />
    <SEHOP Enable="true" TelemetryOnly="false" />
    <Heap TerminateOnError="true" />
    <ChildProcess DisallowChildProcessCreation="false" Audit="true" />
    <UserShadowStack UserShadowStack="true" UserShadowStackStrictMode="true" AuditUserShadowStack="false" />
  </AppConfig>
  <AppConfig Executable="exit.exe">
    <DEP Enable="true" EmulateAtlThunks="false" />
    <ASLR BottomUp="true" HighEntropy="false" />
    <StrictHandle Enable="true" />
    <SystemCalls DisableWin32kSystemCalls="true" Audit="false" />
    <ExtensionPoints DisableExtensionPoints="true" />
    <DynamicCode BlockDynamicCode="false" AllowThreadsToOptOut="false" Audit="true" />
    <SignedBinaries MicrosoftSignedOnly="false" AllowStoreSignedBinaries="true" Audit="true" AuditStoreSigned="true" EnforceModuleDependencySigning="false" />
    <Fonts DisableNonSystemFonts="false" AuditOnly="false" Audit="true" />
    <ImageLoad BlockRemoteImageLoads="false" AuditRemoteImageLoads="true" BlockLowLabelImageLoads="false" AuditLowLabelImageLoads="true" />
    <Payload EnableExportAddressFilter="false" AuditEnableExportAddressFilter="true" EnableExportAddressFilterPlus="false" AuditEnableExportAddressFilterPlus="true" EnableImportAddressFilter="false" AuditEnableImportAddressFilter="true" EnableRopStackPivot="true" AuditEnableRopStackPivot="false" EnableRopCallerCheck="false" AuditEnableRopCallerCheck="true" EnableRopSimExec="false" AuditEnableRopSimExec="true" />
    <SEHOP Enable="true" TelemetryOnly="false" />
    <Heap TerminateOnError="true" />
    <ChildProcess DisallowChildProcessCreation="false" Audit="true" />
    <UserShadowStack UserShadowStack="true" UserShadowStackStrictMode="true" AuditUserShadowStack="false" />
  </AppConfig>
  <AppConfig Executable="ExtExport.exe">
    <DEP Enable="true" EmulateAtlThunks="false" />
    <ASLR BottomUp="true" HighEntropy="false" />
    <StrictHandle Enable="true" />
    <SystemCalls DisableWin32kSystemCalls="true" Audit="false" />
    <ExtensionPoints DisableExtensionPoints="true" />
    <DynamicCode BlockDynamicCode="false" AllowThreadsToOptOut="false" Audit="true" />
    <SignedBinaries MicrosoftSignedOnly="false" AllowStoreSignedBinaries="true" Audit="true" AuditStoreSigned="true" EnforceModuleDependencySigning="false" />
    <Fonts DisableNonSystemFonts="false" AuditOnly="false" Audit="true" />
    <ImageLoad BlockRemoteImageLoads="false" AuditRemoteImageLoads="true" BlockLowLabelImageLoads="false" AuditLowLabelImageLoads="true" />
    <Payload EnableExportAddressFilter="false" AuditEnableExportAddressFilter="true" EnableExportAddressFilterPlus="false" AuditEnableExportAddressFilterPlus="true" EnableImportAddressFilter="false" AuditEnableImportAddressFilter="true" EnableRopStackPivot="true" AuditEnableRopStackPivot="false" EnableRopCallerCheck="false" AuditEnableRopCallerCheck="true" EnableRopSimExec="false" AuditEnableRopSimExec="true" />
    <SEHOP Enable="true" TelemetryOnly="false" />
    <Heap TerminateOnError="true" />
    <ChildProcess DisallowChildProcessCreation="false" Audit="true" />
    <UserShadowStack UserShadowStack="true" UserShadowStackStrictMode="true" AuditUserShadowStack="false" />
  </AppConfig>
  <AppConfig Executable="FreqTransfer32.exe">
    <DEP Enable="true" EmulateAtlThunks="true" />
    <ASLR ForceRelocateImages="true" RequireInfo="true" BottomUp="true" HighEntropy="false" />
    <StrictHandle Enable="true" />
    <SystemCalls DisableWin32kSystemCalls="false" Audit="true" />
    <ExtensionPoints DisableExtensionPoints="true" />
    <DynamicCode BlockDynamicCode="false" AllowThreadsToOptOut="false" Audit="true" />
    <ControlFlowGuard Enable="true" SuppressExports="false" StrictControlFlowGuard="true" />
    <SignedBinaries MicrosoftSignedOnly="false" AllowStoreSignedBinaries="true" Audit="true" AuditStoreSigned="true" EnforceModuleDependencySigning="false" />
    <Fonts DisableNonSystemFonts="false" AuditOnly="false" Audit="true" />
    <ImageLoad BlockRemoteImageLoads="false" AuditRemoteImageLoads="true" BlockLowLabelImageLoads="false" AuditLowLabelImageLoads="true" />
    <Payload EnableExportAddressFilter="false" AuditEnableExportAddressFilter="true" EnableExportAddressFilterPlus="false" AuditEnableExportAddressFilterPlus="true" EnableImportAddressFilter="false" AuditEnableImportAddressFilter="true" EnableRopStackPivot="false" AuditEnableRopStackPivot="true" EnableRopCallerCheck="false" AuditEnableRopCallerCheck="true" EnableRopSimExec="false" AuditEnableRopSimExec="true" />
    <SEHOP Enable="true" TelemetryOnly="false" />
    <Heap TerminateOnError="true" />
    <ChildProcess DisallowChildProcessCreation="false" Audit="true" />
    <UserShadowStack UserShadowStack="false" UserShadowStackStrictMode="true" AuditUserShadowStack="true" />
  </AppConfig>
  <AppConfig Executable="FreqTransfer64.exe">
    <DEP Enable="true" EmulateAtlThunks="true" />
    <ASLR ForceRelocateImages="true" RequireInfo="true" BottomUp="true" HighEntropy="false" />
    <StrictHandle Enable="true" />
    <SystemCalls DisableWin32kSystemCalls="false" Audit="true" />
    <ExtensionPoints DisableExtensionPoints="true" />
    <DynamicCode BlockDynamicCode="false" AllowThreadsToOptOut="false" Audit="true" />
    <ControlFlowGuard Enable="true" SuppressExports="false" StrictControlFlowGuard="true" />
    <SignedBinaries MicrosoftSignedOnly="false" AllowStoreSignedBinaries="true" Audit="true" AuditStoreSigned="true" EnforceModuleDependencySigning="false" />
    <Fonts DisableNonSystemFonts="false" AuditOnly="false" Audit="true" />
    <ImageLoad BlockRemoteImageLoads="false" AuditRemoteImageLoads="true" BlockLowLabelImageLoads="false" AuditLowLabelImageLoads="true" />
    <Payload EnableExportAddressFilter="false" AuditEnableExportAddressFilter="true" EnableExportAddressFilterPlus="false" AuditEnableExportAddressFilterPlus="true" EnableImportAddressFilter="false" AuditEnableImportAddressFilter="true" EnableRopStackPivot="false" AuditEnableRopStackPivot="true" EnableRopCallerCheck="false" AuditEnableRopCallerCheck="true" EnableRopSimExec="false" AuditEnableRopSimExec="true" />
    <SEHOP Enable="true" TelemetryOnly="false" />
    <Heap TerminateOnError="true" />
    <ChildProcess DisallowChildProcessCreation="false" Audit="true" />
    <UserShadowStack UserShadowStack="false" UserShadowStackStrictMode="true" AuditUserShadowStack="true" />
  </AppConfig>
  <AppConfig Executable="Google.Chrome.exe">
    <DEP Enable="true" EmulateAtlThunks="true" />
    <ASLR BottomUp="true" HighEntropy="false" />
    <StrictHandle Enable="true" />
    <SystemCalls DisableWin32kSystemCalls="true" Audit="false" />
    <ExtensionPoints DisableExtensionPoints="true" />
    <DynamicCode BlockDynamicCode="false" AllowThreadsToOptOut="false" Audit="true" />
    <SignedBinaries MicrosoftSignedOnly="false" AllowStoreSignedBinaries="true" Audit="true" AuditStoreSigned="true" EnforceModuleDependencySigning="false" />
    <Fonts DisableNonSystemFonts="false" AuditOnly="false" Audit="true" />
    <ImageLoad BlockRemoteImageLoads="true" AuditRemoteImageLoads="false" BlockLowLabelImageLoads="false" AuditLowLabelImageLoads="true" />
    <Payload EnableExportAddressFilter="false" AuditEnableExportAddressFilter="true" EnableExportAddressFilterPlus="false" AuditEnableExportAddressFilterPlus="true" EnableImportAddressFilter="false" AuditEnableImportAddressFilter="true" EnableRopStackPivot="true" AuditEnableRopStackPivot="false" EnableRopCallerCheck="true" AuditEnableRopCallerCheck="false" EnableRopSimExec="false" AuditEnableRopSimExec="true" />
    <SEHOP Enable="true" TelemetryOnly="false" />
    <Heap TerminateOnError="true" />
    <ChildProcess DisallowChildProcessCreation="false" Audit="true" />
    <UserShadowStack UserShadowStack="true" UserShadowStackStrictMode="true" AuditUserShadowStack="false" />
  </AppConfig>
  <AppConfig Executable="GoogleCrashHandler.exe">
    <DEP Enable="true" EmulateAtlThunks="false" />
    <ASLR BottomUp="true" HighEntropy="false" />
    <StrictHandle Enable="true" />
    <SystemCalls DisableWin32kSystemCalls="true" Audit="false" />
    <ExtensionPoints DisableExtensionPoints="true" />
    <DynamicCode BlockDynamicCode="false" AllowThreadsToOptOut="false" Audit="true" />
    <SignedBinaries MicrosoftSignedOnly="false" AllowStoreSignedBinaries="true" Audit="true" AuditStoreSigned="true" EnforceModuleDependencySigning="false" />
    <Fonts DisableNonSystemFonts="false" AuditOnly="false" Audit="true" />
    <ImageLoad BlockRemoteImageLoads="false" AuditRemoteImageLoads="true" BlockLowLabelImageLoads="false" AuditLowLabelImageLoads="true" />
    <Payload EnableExportAddressFilter="false" AuditEnableExportAddressFilter="true" EnableExportAddressFilterPlus="false" AuditEnableExportAddressFilterPlus="true" EnableImportAddressFilter="false" AuditEnableImportAddressFilter="true" EnableRopStackPivot="true" AuditEnableRopStackPivot="false" EnableRopCallerCheck="false" AuditEnableRopCallerCheck="true" EnableRopSimExec="false" AuditEnableRopSimExec="true" />
    <SEHOP Enable="true" TelemetryOnly="false" />
    <Heap TerminateOnError="true" />
    <ChildProcess DisallowChildProcessCreation="false" Audit="true" />
    <UserShadowStack UserShadowStack="true" UserShadowStackStrictMode="true" AuditUserShadowStack="false" />
  </AppConfig>
  <AppConfig Executable="GoogleCrashHandler64.exe">
    <DEP Enable="true" EmulateAtlThunks="false" />
    <ASLR BottomUp="true" HighEntropy="false" />
    <StrictHandle Enable="true" />
    <SystemCalls DisableWin32kSystemCalls="true" Audit="false" />
    <ExtensionPoints DisableExtensionPoints="true" />
    <DynamicCode BlockDynamicCode="false" AllowThreadsToOptOut="false" Audit="true" />
    <SignedBinaries MicrosoftSignedOnly="false" AllowStoreSignedBinaries="true" Audit="true" AuditStoreSigned="true" EnforceModuleDependencySigning="false" />
    <Fonts DisableNonSystemFonts="false" AuditOnly="false" Audit="true" />
    <ImageLoad BlockRemoteImageLoads="false" AuditRemoteImageLoads="true" BlockLowLabelImageLoads="false" AuditLowLabelImageLoads="true" />
    <Payload EnableExportAddressFilter="false" AuditEnableExportAddressFilter="true" EnableExportAddressFilterPlus="false" AuditEnableExportAddressFilterPlus="true" EnableImportAddressFilter="true" AuditEnableImportAddressFilter="false" EnableRopStackPivot="true" AuditEnableRopStackPivot="false" EnableRopCallerCheck="false" AuditEnableRopCallerCheck="true" EnableRopSimExec="false" AuditEnableRopSimExec="true" />
    <SEHOP Enable="true" TelemetryOnly="false" />
    <Heap TerminateOnError="true" />
    <ChildProcess DisallowChildProcessCreation="false" Audit="true" />
    <UserShadowStack UserShadowStack="true" UserShadowStackStrictMode="true" AuditUserShadowStack="false" />
  </AppConfig>
  <AppConfig Executable="GoogleUpdate.exe">
    <DEP Enable="true" EmulateAtlThunks="true" />
    <ASLR ForceRelocateImages="true" RequireInfo="false" BottomUp="true" HighEntropy="true" />
    <StrictHandle Enable="true" />
    <SystemCalls DisableWin32kSystemCalls="true" Audit="false" />
    <ExtensionPoints DisableExtensionPoints="true" />
    <DynamicCode BlockDynamicCode="true" AllowThreadsToOptOut="false" Audit="false" />
    <ControlFlowGuard Enable="true" SuppressExports="false" StrictControlFlowGuard="true" />
    <SignedBinaries MicrosoftSignedOnly="true" AllowStoreSignedBinaries="false" Audit="false" AuditStoreSigned="false" EnforceModuleDependencySigning="true" />
    <Fonts DisableNonSystemFonts="true" AuditOnly="false" Audit="false" />
    <ImageLoad BlockRemoteImageLoads="true" AuditRemoteImageLoads="false" BlockLowLabelImageLoads="true" AuditLowLabelImageLoads="false" />
    <Payload EnableExportAddressFilter="true" AuditEnableExportAddressFilter="false" EnableExportAddressFilterPlus="true" AuditEnableExportAddressFilterPlus="false" EnableImportAddressFilter="true" AuditEnableImportAddressFilter="false" EnableRopStackPivot="true" AuditEnableRopStackPivot="false" EnableRopCallerCheck="true" AuditEnableRopCallerCheck="false" EnableRopSimExec="true" AuditEnableRopSimExec="false" />
    <SEHOP Enable="true" TelemetryOnly="false" />
    <Heap TerminateOnError="true" />
    <ChildProcess DisallowChildProcessCreation="true" Audit="false" />
    <UserShadowStack UserShadowStack="true" UserShadowStackStrictMode="true" AuditUserShadowStack="false" />
  </AppConfig>
  <AppConfig Executable="GoogleUpdateBroker.exe">
    <DEP Enable="true" EmulateAtlThunks="false" />
    <ASLR BottomUp="true" HighEntropy="false" />
    <StrictHandle Enable="true" />
    <SystemCalls DisableWin32kSystemCalls="true" Audit="false" />
    <ExtensionPoints DisableExtensionPoints="true" />
    <DynamicCode BlockDynamicCode="false" AllowThreadsToOptOut="false" Audit="true" />
    <SignedBinaries MicrosoftSignedOnly="false" AllowStoreSignedBinaries="true" Audit="true" AuditStoreSigned="true" EnforceModuleDependencySigning="false" />
    <Fonts DisableNonSystemFonts="false" AuditOnly="false" Audit="true" />
    <ImageLoad BlockRemoteImageLoads="false" AuditRemoteImageLoads="true" BlockLowLabelImageLoads="false" AuditLowLabelImageLoads="true" />
    <Payload EnableExportAddressFilter="false" AuditEnableExportAddressFilter="true" EnableExportAddressFilterPlus="false" AuditEnableExportAddressFilterPlus="true" EnableImportAddressFilter="false" AuditEnableImportAddressFilter="true" EnableRopStackPivot="true" AuditEnableRopStackPivot="false" EnableRopCallerCheck="false" AuditEnableRopCallerCheck="true" EnableRopSimExec="false" AuditEnableRopSimExec="true" />
    <SEHOP Enable="true" TelemetryOnly="false" />
    <Heap TerminateOnError="true" />
    <ChildProcess DisallowChildProcessCreation="false" Audit="true" />
    <UserShadowStack UserShadowStack="true" UserShadowStackStrictMode="true" AuditUserShadowStack="false" />
  </AppConfig>
  <AppConfig Executable="GoogleUpdateComRegisterShell64.exe">
    <DEP Enable="true" EmulateAtlThunks="false" />
    <ASLR BottomUp="true" HighEntropy="false" />
    <StrictHandle Enable="true" />
    <SystemCalls DisableWin32kSystemCalls="true" Audit="false" />
    <ExtensionPoints DisableExtensionPoints="true" />
    <DynamicCode BlockDynamicCode="false" AllowThreadsToOptOut="false" Audit="true" />
    <SignedBinaries MicrosoftSignedOnly="false" AllowStoreSignedBinaries="true" Audit="true" AuditStoreSigned="true" EnforceModuleDependencySigning="false" />
    <Fonts DisableNonSystemFonts="false" AuditOnly="false" Audit="true" />
    <ImageLoad BlockRemoteImageLoads="false" AuditRemoteImageLoads="true" BlockLowLabelImageLoads="false" AuditLowLabelImageLoads="true" />
    <Payload EnableExportAddressFilter="false" AuditEnableExportAddressFilter="true" EnableExportAddressFilterPlus="false" AuditEnableExportAddressFilterPlus="true" EnableImportAddressFilter="false" AuditEnableImportAddressFilter="true" EnableRopStackPivot="true" AuditEnableRopStackPivot="false" EnableRopCallerCheck="false" AuditEnableRopCallerCheck="true" EnableRopSimExec="false" AuditEnableRopSimExec="true" />
    <SEHOP Enable="true" TelemetryOnly="false" />
    <Heap TerminateOnError="true" />
    <ChildProcess DisallowChildProcessCreation="false" Audit="true" />
    <UserShadowStack UserShadowStack="true" UserShadowStackStrictMode="true" AuditUserShadowStack="false" />
  </AppConfig>
  <AppConfig Executable="GoogleUpdateCore.exe">
    <DEP Enable="true" EmulateAtlThunks="false" />
    <ASLR BottomUp="true" HighEntropy="false" />
    <StrictHandle Enable="true" />
    <SystemCalls DisableWin32kSystemCalls="false" Audit="true" />
    <ExtensionPoints DisableExtensionPoints="true" />
    <DynamicCode BlockDynamicCode="false" AllowThreadsToOptOut="false" Audit="true" />
    <SignedBinaries MicrosoftSignedOnly="false" AllowStoreSignedBinaries="true" Audit="true" AuditStoreSigned="true" EnforceModuleDependencySigning="false" />
    <Fonts DisableNonSystemFonts="false" AuditOnly="false" Audit="true" />
    <ImageLoad BlockRemoteImageLoads="false" AuditRemoteImageLoads="true" BlockLowLabelImageLoads="true" AuditLowLabelImageLoads="false" />
    <Payload EnableExportAddressFilter="false" AuditEnableExportAddressFilter="true" EnableExportAddressFilterPlus="false" AuditEnableExportAddressFilterPlus="true" EnableImportAddressFilter="false" AuditEnableImportAddressFilter="true" EnableRopStackPivot="true" AuditEnableRopStackPivot="false" EnableRopCallerCheck="false" AuditEnableRopCallerCheck="true" EnableRopSimExec="false" AuditEnableRopSimExec="true" />
    <SEHOP Enable="true" TelemetryOnly="false" />
    <Heap TerminateOnError="true" />
    <ChildProcess DisallowChildProcessCreation="false" Audit="true" />
    <UserShadowStack UserShadowStack="true" UserShadowStackStrictMode="true" AuditUserShadowStack="false" />
  </AppConfig>
  <AppConfig Executable="GoogleUpdateOnDemand.exe">
    <DEP Enable="true" EmulateAtlThunks="true" />
    <ASLR BottomUp="true" HighEntropy="false" />
    <StrictHandle Enable="true" />
    <SystemCalls DisableWin32kSystemCalls="true" Audit="false" />
    <ExtensionPoints DisableExtensionPoints="true" />
    <DynamicCode BlockDynamicCode="false" AllowThreadsToOptOut="false" Audit="true" />
    <SignedBinaries MicrosoftSignedOnly="false" AllowStoreSignedBinaries="true" Audit="true" AuditStoreSigned="true" EnforceModuleDependencySigning="false" />
    <Fonts DisableNonSystemFonts="false" AuditOnly="false" Audit="true" />
    <ImageLoad BlockRemoteImageLoads="false" AuditRemoteImageLoads="true" BlockLowLabelImageLoads="false" AuditLowLabelImageLoads="true" />
    <Payload EnableExportAddressFilter="false" AuditEnableExportAddressFilter="true" EnableExportAddressFilterPlus="false" AuditEnableExportAddressFilterPlus="true" EnableImportAddressFilter="false" AuditEnableImportAddressFilter="true" EnableRopStackPivot="true" AuditEnableRopStackPivot="false" EnableRopCallerCheck="false" AuditEnableRopCallerCheck="true" EnableRopSimExec="false" AuditEnableRopSimExec="true" />
    <SEHOP Enable="true" TelemetryOnly="false" />
    <Heap TerminateOnError="true" />
    <ChildProcess DisallowChildProcessCreation="false" Audit="true" />
    <UserShadowStack UserShadowStack="true" UserShadowStackStrictMode="true" AuditUserShadowStack="false" />
  </AppConfig>
  <AppConfig Executable="HighresBlender32.exe">
    <DEP Enable="true" EmulateAtlThunks="true" />
    <ASLR ForceRelocateImages="true" RequireInfo="true" BottomUp="true" HighEntropy="false" />
    <StrictHandle Enable="true" />
    <SystemCalls DisableWin32kSystemCalls="false" Audit="true" />
    <ExtensionPoints DisableExtensionPoints="true" />
    <DynamicCode BlockDynamicCode="false" AllowThreadsToOptOut="false" Audit="true" />
    <ControlFlowGuard Enable="true" SuppressExports="false" StrictControlFlowGuard="true" />
    <SignedBinaries MicrosoftSignedOnly="false" AllowStoreSignedBinaries="true" Audit="true" AuditStoreSigned="true" EnforceModuleDependencySigning="false" />
    <Fonts DisableNonSystemFonts="false" AuditOnly="false" Audit="true" />
    <ImageLoad BlockRemoteImageLoads="false" AuditRemoteImageLoads="true" BlockLowLabelImageLoads="false" AuditLowLabelImageLoads="true" />
    <Payload EnableExportAddressFilter="false" AuditEnableExportAddressFilter="true" EnableExportAddressFilterPlus="false" AuditEnableExportAddressFilterPlus="true" EnableImportAddressFilter="false" AuditEnableImportAddressFilter="true" EnableRopStackPivot="false" AuditEnableRopStackPivot="true" EnableRopCallerCheck="false" AuditEnableRopCallerCheck="true" EnableRopSimExec="false" AuditEnableRopSimExec="true" />
    <SEHOP Enable="true" TelemetryOnly="false" />
    <Heap TerminateOnError="true" />
    <ChildProcess DisallowChildProcessCreation="false" Audit="true" />
    <UserShadowStack UserShadowStack="false" UserShadowStackStrictMode="true" AuditUserShadowStack="true" />
  </AppConfig>
  <AppConfig Executable="HighresBlender64.exe">
    <DEP Enable="true" EmulateAtlThunks="true" />
    <ASLR ForceRelocateImages="true" RequireInfo="true" BottomUp="true" HighEntropy="false" />
    <StrictHandle Enable="true" />
    <SystemCalls DisableWin32kSystemCalls="false" Audit="true" />
    <ExtensionPoints DisableExtensionPoints="true" />
    <DynamicCode BlockDynamicCode="false" AllowThreadsToOptOut="false" Audit="true" />
    <ControlFlowGuard Enable="true" SuppressExports="false" StrictControlFlowGuard="true" />
    <SignedBinaries MicrosoftSignedOnly="false" AllowStoreSignedBinaries="true" Audit="true" AuditStoreSigned="true" EnforceModuleDependencySigning="false" />
    <Fonts DisableNonSystemFonts="false" AuditOnly="false" Audit="true" />
    <ImageLoad BlockRemoteImageLoads="false" AuditRemoteImageLoads="true" BlockLowLabelImageLoads="false" AuditLowLabelImageLoads="true" />
    <Payload EnableExportAddressFilter="false" AuditEnableExportAddressFilter="true" EnableExportAddressFilterPlus="false" AuditEnableExportAddressFilterPlus="true" EnableImportAddressFilter="false" AuditEnableImportAddressFilter="true" EnableRopStackPivot="false" AuditEnableRopStackPivot="true" EnableRopCallerCheck="false" AuditEnableRopCallerCheck="true" EnableRopSimExec="false" AuditEnableRopSimExec="true" />
    <SEHOP Enable="true" TelemetryOnly="false" />
    <Heap TerminateOnError="true" />
    <ChildProcess DisallowChildProcessCreation="false" Audit="true" />
    <UserShadowStack UserShadowStack="false" UserShadowStackStrictMode="true" AuditUserShadowStack="true" />
  </AppConfig>
  <AppConfig Executable="ie4uinit.exe">
    <ASLR ForceRelocateImages="true" RequireInfo="false" />
    <Payload EnableRopStackPivot="true" AuditEnableRopStackPivot="false" />
    <Heap TerminateOnError="true" />
    <UserShadowStack UserShadowStack="true" UserShadowStackStrictMode="true" AuditUserShadowStack="false" />
  </AppConfig>
  <AppConfig Executable="iediagcmd.exe">
    <DEP Enable="true" EmulateAtlThunks="true" />
    <ASLR BottomUp="true" HighEntropy="true" />
    <StrictHandle Enable="true" />
    <SystemCalls DisableWin32kSystemCalls="false" Audit="true" />
    <ExtensionPoints DisableExtensionPoints="true" />
    <DynamicCode BlockDynamicCode="false" AllowThreadsToOptOut="false" Audit="true" />
    <SignedBinaries MicrosoftSignedOnly="false" AllowStoreSignedBinaries="true" Audit="true" AuditStoreSigned="true" EnforceModuleDependencySigning="true" />
    <Fonts DisableNonSystemFonts="false" AuditOnly="false" Audit="true" />
    <ImageLoad BlockRemoteImageLoads="false" AuditRemoteImageLoads="true" BlockLowLabelImageLoads="false" AuditLowLabelImageLoads="true" />
    <Payload EnableExportAddressFilter="false" AuditEnableExportAddressFilter="true" EnableExportAddressFilterPlus="false" AuditEnableExportAddressFilterPlus="true" EnableImportAddressFilter="true" AuditEnableImportAddressFilter="false" EnableRopStackPivot="false" AuditEnableRopStackPivot="true" EnableRopCallerCheck="true" AuditEnableRopCallerCheck="false" EnableRopSimExec="true" AuditEnableRopSimExec="false" />
    <SEHOP Enable="true" TelemetryOnly="false" />
    <Heap TerminateOnError="true" />
    <ChildProcess DisallowChildProcessCreation="false" Audit="true" />
    <UserShadowStack UserShadowStack="true" UserShadowStackStrictMode="true" AuditUserShadowStack="false" />
  </AppConfig>
  <AppConfig Executable="ieinstal.exe">
    <DEP Enable="true" EmulateAtlThunks="true" />
    <ASLR BottomUp="true" HighEntropy="true" />
    <StrictHandle Enable="true" />
    <SystemCalls DisableWin32kSystemCalls="false" Audit="true" />
    <ExtensionPoints DisableExtensionPoints="true" />
    <DynamicCode BlockDynamicCode="false" AllowThreadsToOptOut="false" Audit="true" />
    <SignedBinaries MicrosoftSignedOnly="false" AllowStoreSignedBinaries="true" Audit="true" AuditStoreSigned="true" EnforceModuleDependencySigning="false" />
    <Fonts DisableNonSystemFonts="false" AuditOnly="false" Audit="true" />
    <ImageLoad BlockRemoteImageLoads="false" AuditRemoteImageLoads="true" BlockLowLabelImageLoads="false" AuditLowLabelImageLoads="true" />
    <Payload EnableExportAddressFilter="false" AuditEnableExportAddressFilter="true" EnableExportAddressFilterPlus="false" AuditEnableExportAddressFilterPlus="true" EnableImportAddressFilter="false" AuditEnableImportAddressFilter="true" EnableRopStackPivot="false" AuditEnableRopStackPivot="true" EnableRopCallerCheck="false" AuditEnableRopCallerCheck="true" EnableRopSimExec="false" AuditEnableRopSimExec="true" />
    <SEHOP Enable="true" TelemetryOnly="false" />
    <Heap TerminateOnError="true" />
    <ChildProcess DisallowChildProcessCreation="false" Audit="true" />
    <UserShadowStack UserShadowStack="true" UserShadowStackStrictMode="true" AuditUserShadowStack="false" />
  </AppConfig>
  <AppConfig Executable="ielowutil.exe">
    <DEP Enable="true" EmulateAtlThunks="true" />
    <ASLR BottomUp="true" HighEntropy="false" />
    <StrictHandle Enable="true" />
    <SystemCalls DisableWin32kSystemCalls="false" Audit="true" />
    <ExtensionPoints DisableExtensionPoints="true" />
    <DynamicCode BlockDynamicCode="false" AllowThreadsToOptOut="false" Audit="true" />
    <SignedBinaries MicrosoftSignedOnly="true" AllowStoreSignedBinaries="true" Audit="false" AuditStoreSigned="false" EnforceModuleDependencySigning="false" />
    <Fonts DisableNonSystemFonts="true" AuditOnly="false" Audit="false" />
    <ImageLoad BlockRemoteImageLoads="true" AuditRemoteImageLoads="false" BlockLowLabelImageLoads="false" AuditLowLabelImageLoads="true" />
    <Payload EnableExportAddressFilter="false" AuditEnableExportAddressFilter="true" EnableExportAddressFilterPlus="false" AuditEnableExportAddressFilterPlus="true" EnableImportAddressFilter="false" AuditEnableImportAddressFilter="true" EnableRopStackPivot="false" AuditEnableRopStackPivot="true" EnableRopCallerCheck="false" AuditEnableRopCallerCheck="true" EnableRopSimExec="false" AuditEnableRopSimExec="true" />
    <SEHOP Enable="true" TelemetryOnly="false" />
    <Heap TerminateOnError="true" />
    <ChildProcess DisallowChildProcessCreation="false" Audit="true" />
    <UserShadowStack UserShadowStack="false" UserShadowStackStrictMode="true" AuditUserShadowStack="true" />
  </AppConfig>
  <AppConfig Executable="ieUnatt.exe">
    <ASLR ForceRelocateImages="true" RequireInfo="false" />
    <Payload EnableRopStackPivot="true" AuditEnableRopStackPivot="false" />
    <Heap TerminateOnError="true" />
    <UserShadowStack UserShadowStack="true" UserShadowStackStrictMode="true" AuditUserShadowStack="false" />
  </AppConfig>
  <AppConfig Executable="iexplore.exe">
    <DEP Enable="true" EmulateAtlThunks="false" />
    <ASLR BottomUp="true" HighEntropy="true" />
    <StrictHandle Enable="true" />
    <SystemCalls DisableWin32kSystemCalls="true" Audit="false" />
    <ExtensionPoints DisableExtensionPoints="true" />
    <DynamicCode BlockDynamicCode="true" AllowThreadsToOptOut="true" Audit="false" />
    <SignedBinaries MicrosoftSignedOnly="true" AllowStoreSignedBinaries="true" Audit="false" AuditStoreSigned="false" EnforceModuleDependencySigning="true" />
    <Fonts DisableNonSystemFonts="true" AuditOnly="false" Audit="false" />
    <ImageLoad BlockRemoteImageLoads="true" AuditRemoteImageLoads="false" BlockLowLabelImageLoads="true" AuditLowLabelImageLoads="false" />
    <Payload EnableExportAddressFilter="true" AuditEnableExportAddressFilter="false" EnableExportAddressFilterPlus="true" AuditEnableExportAddressFilterPlus="false" EnableImportAddressFilter="true" AuditEnableImportAddressFilter="false" EnableRopStackPivot="true" AuditEnableRopStackPivot="false" EnableRopCallerCheck="true" AuditEnableRopCallerCheck="false" EnableRopSimExec="true" AuditEnableRopSimExec="false" />
    <SEHOP Enable="true" TelemetryOnly="false" />
    <Heap TerminateOnError="true" />
    <ChildProcess DisallowChildProcessCreation="true" Audit="false" />
    <UserShadowStack UserShadowStack="true" UserShadowStackStrictMode="true" AuditUserShadowStack="false" />
  </AppConfig>
  <AppConfig Executable="installer.exe">
    <DEP Enable="true" EmulateAtlThunks="false" />
    <ASLR BottomUp="true" HighEntropy="true" />
    <StrictHandle Enable="true" />
    <SystemCalls DisableWin32kSystemCalls="true" Audit="false" />
    <ExtensionPoints DisableExtensionPoints="true" />
    <DynamicCode BlockDynamicCode="true" AllowThreadsToOptOut="true" Audit="false" />
    <SignedBinaries MicrosoftSignedOnly="true" AllowStoreSignedBinaries="true" Audit="false" AuditStoreSigned="false" EnforceModuleDependencySigning="true" />
    <Fonts DisableNonSystemFonts="true" AuditOnly="false" Audit="false" />
    <ImageLoad BlockRemoteImageLoads="true" AuditRemoteImageLoads="false" BlockLowLabelImageLoads="true" AuditLowLabelImageLoads="false" />
    <Payload EnableExportAddressFilter="true" AuditEnableExportAddressFilter="false" EnableExportAddressFilterPlus="true" AuditEnableExportAddressFilterPlus="false" EnableImportAddressFilter="true" AuditEnableImportAddressFilter="false" EnableRopStackPivot="true" AuditEnableRopStackPivot="false" EnableRopCallerCheck="true" AuditEnableRopCallerCheck="false" EnableRopSimExec="true" AuditEnableRopSimExec="false" />
    <SEHOP Enable="true" TelemetryOnly="false" />
    <Heap TerminateOnError="true" />
    <ChildProcess DisallowChildProcessCreation="true" Audit="false" />
    <UserShadowStack UserShadowStack="true" UserShadowStackStrictMode="true" AuditUserShadowStack="false" />
  </AppConfig>
  <AppConfig Executable="installer_helper_64.exe">
    <DEP Enable="true" EmulateAtlThunks="true" />
    <ASLR ForceRelocateImages="true" RequireInfo="false" BottomUp="true" HighEntropy="true" />
    <StrictHandle Enable="true" />
    <SystemCalls DisableWin32kSystemCalls="true" Audit="false" />
    <ExtensionPoints DisableExtensionPoints="true" />
    <DynamicCode BlockDynamicCode="true" AllowThreadsToOptOut="true" Audit="false" />
    <ControlFlowGuard Enable="true" SuppressExports="false" />
    <SignedBinaries MicrosoftSignedOnly="true" AllowStoreSignedBinaries="true" Audit="false" AuditStoreSigned="false" EnforceModuleDependencySigning="true" />
    <Fonts DisableNonSystemFonts="true" AuditOnly="false" Audit="false" />
    <ImageLoad BlockRemoteImageLoads="true" AuditRemoteImageLoads="false" BlockLowLabelImageLoads="true" AuditLowLabelImageLoads="false" />
    <Payload EnableExportAddressFilter="true" AuditEnableExportAddressFilter="false" EnableExportAddressFilterPlus="true" AuditEnableExportAddressFilterPlus="false" EnableImportAddressFilter="true" AuditEnableImportAddressFilter="false" EnableRopStackPivot="true" AuditEnableRopStackPivot="false" EnableRopCallerCheck="true" AuditEnableRopCallerCheck="false" EnableRopSimExec="true" AuditEnableRopSimExec="false" />
    <SEHOP Enable="true" TelemetryOnly="false" />
    <Heap TerminateOnError="true" />
    <ChildProcess DisallowChildProcessCreation="true" Audit="false" />
    <UserShadowStack UserShadowStack="true" UserShadowStackStrictMode="true" AuditUserShadowStack="false" />
  </AppConfig>
  <AppConfig Executable="KillPot64.exe">
    <DEP Enable="true" EmulateAtlThunks="true" />
    <ASLR BottomUp="true" HighEntropy="true" />
    <StrictHandle Enable="true" />
    <SystemCalls DisableWin32kSystemCalls="true" Audit="false" />
    <ExtensionPoints DisableExtensionPoints="true" />
    <DynamicCode BlockDynamicCode="true" AllowThreadsToOptOut="true" Audit="false" />
    <SignedBinaries MicrosoftSignedOnly="true" AllowStoreSignedBinaries="true" Audit="false" AuditStoreSigned="false" EnforceModuleDependencySigning="true" />
    <Fonts DisableNonSystemFonts="true" AuditOnly="false" Audit="false" />
    <ImageLoad BlockRemoteImageLoads="true" AuditRemoteImageLoads="false" BlockLowLabelImageLoads="true" AuditLowLabelImageLoads="false" />
    <Payload EnableExportAddressFilter="true" AuditEnableExportAddressFilter="false" EnableExportAddressFilterPlus="true" AuditEnableExportAddressFilterPlus="false" EnableImportAddressFilter="true" AuditEnableImportAddressFilter="false" EnableRopStackPivot="true" AuditEnableRopStackPivot="false" EnableRopCallerCheck="true" AuditEnableRopCallerCheck="false" EnableRopSimExec="true" AuditEnableRopSimExec="false" />
    <SEHOP Enable="true" TelemetryOnly="false" />
    <Heap TerminateOnError="true" />
    <ChildProcess DisallowChildProcessCreation="true" Audit="false" />
    <UserShadowStack UserShadowStack="true" UserShadowStackStrictMode="true" AuditUserShadowStack="false" />
  </AppConfig>
  <AppConfig Executable="launcher.exe">
    <DEP Enable="true" EmulateAtlThunks="true" />
    <ASLR ForceRelocateImages="true" RequireInfo="false" BottomUp="true" HighEntropy="true" />
    <StrictHandle Enable="true" />
    <SystemCalls DisableWin32kSystemCalls="true" Audit="false" />
    <ExtensionPoints DisableExtensionPoints="true" />
    <DynamicCode BlockDynamicCode="true" AllowThreadsToOptOut="false" Audit="false" />
    <SignedBinaries MicrosoftSignedOnly="true" AllowStoreSignedBinaries="true" Audit="false" AuditStoreSigned="false" EnforceModuleDependencySigning="true" />
    <Fonts DisableNonSystemFonts="true" AuditOnly="false" Audit="false" />
    <ImageLoad BlockRemoteImageLoads="true" AuditRemoteImageLoads="false" BlockLowLabelImageLoads="true" AuditLowLabelImageLoads="false" />
    <Payload EnableExportAddressFilter="true" AuditEnableExportAddressFilter="false" EnableExportAddressFilterPlus="true" AuditEnableExportAddressFilterPlus="false" EnableImportAddressFilter="true" AuditEnableImportAddressFilter="false" EnableRopStackPivot="true" AuditEnableRopStackPivot="false" EnableRopCallerCheck="true" AuditEnableRopCallerCheck="false" EnableRopSimExec="true" AuditEnableRopSimExec="false" />
    <SEHOP Enable="true" TelemetryOnly="false" />
    <Heap TerminateOnError="true" />
    <ChildProcess DisallowChildProcessCreation="true" Audit="false" />
    <UserShadowStack UserShadowStack="true" UserShadowStackStrictMode="true" AuditUserShadowStack="false" />
  </AppConfig>
  <AppConfig Executable="LaunchWebUI.exe">
    <DEP Enable="true" EmulateAtlThunks="false" />
    <ASLR ForceRelocateImages="true" RequireInfo="false" BottomUp="true" HighEntropy="true" />
    <StrictHandle Enable="true" />
    <SystemCalls DisableWin32kSystemCalls="true" Audit="false" />
    <ExtensionPoints DisableExtensionPoints="true" />
    <DynamicCode BlockDynamicCode="true" AllowThreadsToOptOut="true" Audit="false" />
    <ControlFlowGuard Enable="true" SuppressExports="false" StrictControlFlowGuard="true" />
    <SignedBinaries MicrosoftSignedOnly="true" AllowStoreSignedBinaries="true" Audit="false" AuditStoreSigned="false" EnforceModuleDependencySigning="true" />
    <Fonts DisableNonSystemFonts="true" AuditOnly="false" Audit="false" />
    <ImageLoad BlockRemoteImageLoads="true" AuditRemoteImageLoads="false" BlockLowLabelImageLoads="true" AuditLowLabelImageLoads="false" />
    <Payload EnableExportAddressFilter="true" AuditEnableExportAddressFilter="false" EnableExportAddressFilterPlus="true" AuditEnableExportAddressFilterPlus="false" EnableImportAddressFilter="true" AuditEnableImportAddressFilter="false" EnableRopStackPivot="true" AuditEnableRopStackPivot="false" EnableRopCallerCheck="true" AuditEnableRopCallerCheck="false" EnableRopSimExec="true" AuditEnableRopSimExec="false" />
    <SEHOP Enable="true" TelemetryOnly="false" />
    <Heap TerminateOnError="true" />
    <ChildProcess DisallowChildProcessCreation="true" Audit="false" />
    <UserShadowStack UserShadowStack="true" UserShadowStackStrictMode="true" AuditUserShadowStack="false" />
  </AppConfig>
  <AppConfig Executable="LestaErrorMonitor.exe">
    <DEP Enable="true" EmulateAtlThunks="false" />
    <ASLR BottomUp="true" HighEntropy="true" />
    <StrictHandle Enable="true" />
    <SystemCalls DisableWin32kSystemCalls="true" Audit="false" />
    <ExtensionPoints DisableExtensionPoints="true" />
    <DynamicCode BlockDynamicCode="true" AllowThreadsToOptOut="true" Audit="false" />
    <SignedBinaries MicrosoftSignedOnly="true" AllowStoreSignedBinaries="true" Audit="false" AuditStoreSigned="false" EnforceModuleDependencySigning="true" />
    <Fonts DisableNonSystemFonts="true" AuditOnly="false" Audit="false" />
    <ImageLoad BlockRemoteImageLoads="true" AuditRemoteImageLoads="false" BlockLowLabelImageLoads="true" AuditLowLabelImageLoads="false" />
    <Payload EnableExportAddressFilter="true" AuditEnableExportAddressFilter="false" EnableExportAddressFilterPlus="true" AuditEnableExportAddressFilterPlus="false" EnableImportAddressFilter="true" AuditEnableImportAddressFilter="false" EnableRopStackPivot="true" AuditEnableRopStackPivot="false" EnableRopCallerCheck="true" AuditEnableRopCallerCheck="false" EnableRopSimExec="true" AuditEnableRopSimExec="false" />
    <SEHOP Enable="true" TelemetryOnly="false" />
    <Heap TerminateOnError="true" />
    <ChildProcess DisallowChildProcessCreation="true" Audit="false" />
    <UserShadowStack UserShadowStack="true" UserShadowStackStrictMode="true" AuditUserShadowStack="false" />
  </AppConfig>
  <AppConfig Executable="lesta_game_center_install_ru_dc9gclv5vdl5.exe">
    <Payload EnableRopStackPivot="true" AuditEnableRopStackPivot="false" />
    <Heap TerminateOnError="true" />
    <UserShadowStack UserShadowStack="true" UserShadowStackStrictMode="true" AuditUserShadowStack="false" />
  </AppConfig>
  <AppConfig Executable="lgc.exe">
    <DEP Enable="true" EmulateAtlThunks="false" />
    <ASLR BottomUp="true" HighEntropy="true" />
    <StrictHandle Enable="true" />
    <SystemCalls DisableWin32kSystemCalls="true" Audit="false" />
    <ExtensionPoints DisableExtensionPoints="true" />
    <DynamicCode BlockDynamicCode="true" AllowThreadsToOptOut="true" Audit="false" />
    <SignedBinaries MicrosoftSignedOnly="true" AllowStoreSignedBinaries="false" Audit="false" AuditStoreSigned="false" EnforceModuleDependencySigning="true" />
    <Fonts DisableNonSystemFonts="true" AuditOnly="false" Audit="false" />
    <ImageLoad BlockRemoteImageLoads="true" AuditRemoteImageLoads="false" BlockLowLabelImageLoads="true" AuditLowLabelImageLoads="false" />
    <Payload EnableExportAddressFilter="true" AuditEnableExportAddressFilter="false" EnableExportAddressFilterPlus="true" AuditEnableExportAddressFilterPlus="false" EnableImportAddressFilter="true" AuditEnableImportAddressFilter="false" EnableRopStackPivot="true" AuditEnableRopStackPivot="false" EnableRopCallerCheck="true" AuditEnableRopCallerCheck="false" EnableRopSimExec="true" AuditEnableRopSimExec="false" />
    <SEHOP Enable="true" TelemetryOnly="false" />
    <Heap TerminateOnError="true" />
    <ChildProcess DisallowChildProcessCreation="true" Audit="false" />
    <UserShadowStack UserShadowStack="true" UserShadowStackStrictMode="true" AuditUserShadowStack="false" />
  </AppConfig>
  <AppConfig Executable="lgc_api.exe">
    <DEP Enable="true" EmulateAtlThunks="true" />
    <ASLR BottomUp="true" HighEntropy="true" />
    <StrictHandle Enable="true" />
    <SystemCalls DisableWin32kSystemCalls="true" Audit="false" />
    <ExtensionPoints DisableExtensionPoints="true" />
    <DynamicCode BlockDynamicCode="true" AllowThreadsToOptOut="true" Audit="false" />
    <SignedBinaries MicrosoftSignedOnly="true" AllowStoreSignedBinaries="true" Audit="false" AuditStoreSigned="false" EnforceModuleDependencySigning="true" />
    <Fonts DisableNonSystemFonts="true" AuditOnly="false" Audit="false" />
    <ImageLoad BlockRemoteImageLoads="true" AuditRemoteImageLoads="false" BlockLowLabelImageLoads="true" AuditLowLabelImageLoads="false" />
    <Payload EnableExportAddressFilter="true" AuditEnableExportAddressFilter="false" EnableExportAddressFilterPlus="true" AuditEnableExportAddressFilterPlus="false" EnableImportAddressFilter="true" AuditEnableImportAddressFilter="false" EnableRopStackPivot="true" AuditEnableRopStackPivot="false" EnableRopCallerCheck="true" AuditEnableRopCallerCheck="false" EnableRopSimExec="true" AuditEnableRopSimExec="false" />
    <SEHOP Enable="true" TelemetryOnly="false" />
    <Heap TerminateOnError="true" />
    <ChildProcess DisallowChildProcessCreation="true" Audit="false" />
    <UserShadowStack UserShadowStack="true" UserShadowStackStrictMode="true" AuditUserShadowStack="false" />
  </AppConfig>
  <AppConfig Executable="LiveTuner2.exe">
    <DEP Enable="true" EmulateAtlThunks="true" />
    <ASLR BottomUp="true" HighEntropy="false" />
    <StrictHandle Enable="true" />
    <SystemCalls DisableWin32kSystemCalls="false" Audit="true" />
    <ExtensionPoints DisableExtensionPoints="true" />
    <DynamicCode BlockDynamicCode="false" AllowThreadsToOptOut="false" Audit="true" />
    <SignedBinaries MicrosoftSignedOnly="false" AllowStoreSignedBinaries="true" Audit="true" AuditStoreSigned="true" EnforceModuleDependencySigning="false" />
    <Fonts DisableNonSystemFonts="false" AuditOnly="false" Audit="true" />
    <ImageLoad BlockRemoteImageLoads="false" AuditRemoteImageLoads="true" BlockLowLabelImageLoads="false" AuditLowLabelImageLoads="true" />
    <Payload EnableExportAddressFilter="false" AuditEnableExportAddressFilter="true" EnableExportAddressFilterPlus="false" AuditEnableExportAddressFilterPlus="true" EnableImportAddressFilter="false" AuditEnableImportAddressFilter="true" EnableRopStackPivot="true" AuditEnableRopStackPivot="false" EnableRopCallerCheck="false" AuditEnableRopCallerCheck="true" EnableRopSimExec="false" AuditEnableRopSimExec="true" />
    <SEHOP Enable="true" TelemetryOnly="false" />
    <Heap TerminateOnError="true" />
    <ChildProcess DisallowChildProcessCreation="false" Audit="true" />
    <UserShadowStack UserShadowStack="true" UserShadowStackStrictMode="true" AuditUserShadowStack="false" />
  </AppConfig>
  <AppConfig Executable="LiveTunerService.exe">
    <DEP Enable="true" EmulateAtlThunks="true" />
    <ASLR BottomUp="true" HighEntropy="false" />
    <StrictHandle Enable="true" />
    <SystemCalls DisableWin32kSystemCalls="false" Audit="true" />
    <ExtensionPoints DisableExtensionPoints="true" />
    <DynamicCode BlockDynamicCode="false" AllowThreadsToOptOut="false" Audit="true" />
    <SignedBinaries MicrosoftSignedOnly="false" AllowStoreSignedBinaries="true" Audit="true" AuditStoreSigned="true" EnforceModuleDependencySigning="false" />
    <Fonts DisableNonSystemFonts="false" AuditOnly="false" Audit="true" />
    <ImageLoad BlockRemoteImageLoads="false" AuditRemoteImageLoads="true" BlockLowLabelImageLoads="false" AuditLowLabelImageLoads="true" />
    <Payload EnableExportAddressFilter="false" AuditEnableExportAddressFilter="true" EnableExportAddressFilterPlus="false" AuditEnableExportAddressFilterPlus="true" EnableImportAddressFilter="false" AuditEnableImportAddressFilter="true" EnableRopStackPivot="true" AuditEnableRopStackPivot="false" EnableRopCallerCheck="false" AuditEnableRopCallerCheck="true" EnableRopSimExec="false" AuditEnableRopSimExec="true" />
    <SEHOP Enable="true" TelemetryOnly="false" />
    <Heap TerminateOnError="true" />
    <ChildProcess DisallowChildProcessCreation="false" Audit="true" />
    <UserShadowStack UserShadowStack="true" UserShadowStackStrictMode="true" AuditUserShadowStack="false" />
  </AppConfig>
  <AppConfig Executable="MCU.exe">
    <DEP Enable="true" EmulateAtlThunks="true" />
    <ASLR ForceRelocateImages="true" RequireInfo="true" BottomUp="true" HighEntropy="false" />
    <StrictHandle Enable="true" />
    <SystemCalls DisableWin32kSystemCalls="false" Audit="true" />
    <ExtensionPoints DisableExtensionPoints="true" />
    <DynamicCode BlockDynamicCode="false" AllowThreadsToOptOut="false" Audit="true" />
    <ControlFlowGuard Enable="true" SuppressExports="false" StrictControlFlowGuard="true" />
    <SignedBinaries MicrosoftSignedOnly="false" AllowStoreSignedBinaries="true" Audit="true" AuditStoreSigned="true" EnforceModuleDependencySigning="false" />
    <Fonts DisableNonSystemFonts="false" AuditOnly="false" Audit="true" />
    <ImageLoad BlockRemoteImageLoads="false" AuditRemoteImageLoads="true" BlockLowLabelImageLoads="false" AuditLowLabelImageLoads="true" />
    <Payload EnableExportAddressFilter="false" AuditEnableExportAddressFilter="true" EnableExportAddressFilterPlus="false" AuditEnableExportAddressFilterPlus="true" EnableImportAddressFilter="false" AuditEnableImportAddressFilter="true" EnableRopStackPivot="false" AuditEnableRopStackPivot="true" EnableRopCallerCheck="false" AuditEnableRopCallerCheck="true" EnableRopSimExec="false" AuditEnableRopSimExec="true" />
    <SEHOP Enable="true" TelemetryOnly="false" />
    <Heap TerminateOnError="true" />
    <ChildProcess DisallowChildProcessCreation="false" Audit="true" />
    <UserShadowStack UserShadowStack="false" UserShadowStackStrictMode="true" AuditUserShadowStack="true" />
  </AppConfig>
  <AppConfig Executable="miner.exe">
    <DEP Enable="true" EmulateAtlThunks="false" />
    <ASLR BottomUp="true" HighEntropy="true" />
    <StrictHandle Enable="true" />
    <SystemCalls DisableWin32kSystemCalls="true" Audit="false" />
    <ExtensionPoints DisableExtensionPoints="true" />
    <DynamicCode BlockDynamicCode="true" AllowThreadsToOptOut="true" Audit="false" />
    <SignedBinaries MicrosoftSignedOnly="true" AllowStoreSignedBinaries="true" Audit="false" AuditStoreSigned="false" EnforceModuleDependencySigning="true" />
    <Fonts DisableNonSystemFonts="true" AuditOnly="false" Audit="false" />
    <ImageLoad BlockRemoteImageLoads="true" AuditRemoteImageLoads="false" BlockLowLabelImageLoads="true" AuditLowLabelImageLoads="false" />
    <Payload EnableExportAddressFilter="true" AuditEnableExportAddressFilter="false" EnableExportAddressFilterPlus="true" AuditEnableExportAddressFilterPlus="false" EnableImportAddressFilter="true" AuditEnableImportAddressFilter="false" EnableRopStackPivot="true" AuditEnableRopStackPivot="false" EnableRopCallerCheck="true" AuditEnableRopCallerCheck="false" EnableRopSimExec="true" AuditEnableRopSimExec="false" />
    <SEHOP Enable="true" TelemetryOnly="false" />
    <Heap TerminateOnError="true" />
    <ChildProcess DisallowChildProcessCreation="true" Audit="false" />
    <UserShadowStack UserShadowStack="true" UserShadowStackStrictMode="true" AuditUserShadowStack="false" />
  </AppConfig>
  <AppConfig Executable="mscorsvw.exe">
    <ExtensionPoints DisableExtensionPoints="true" />
  </AppConfig>
  <AppConfig Executable="msfeedssync.exe">
    <ASLR ForceRelocateImages="true" RequireInfo="false" />
  </AppConfig>
  <AppConfig Executable="mshta.exe">
    <ASLR ForceRelocateImages="true" RequireInfo="false" />
  </AppConfig>
  <AppConfig Executable="NetHost.exe">
    <Payload EnableRopStackPivot="true" AuditEnableRopStackPivot="false" />
    <Heap TerminateOnError="true" />
    <UserShadowStack UserShadowStack="false" UserShadowStackStrictMode="true" AuditUserShadowStack="true" />
  </AppConfig>
  <AppConfig Executable="ngen.exe">
    <ExtensionPoints DisableExtensionPoints="true" />
  </AppConfig>
  <AppConfig Executable="ngentask.exe">
    <ExtensionPoints DisableExtensionPoints="true" />
  </AppConfig>
  <AppConfig Executable="notification_helper.exe">
    <DEP Enable="true" EmulateAtlThunks="true" />
    <ASLR BottomUp="true" HighEntropy="true" />
    <StrictHandle Enable="true" />
    <SystemCalls DisableWin32kSystemCalls="true" Audit="false" />
    <ExtensionPoints DisableExtensionPoints="true" />
    <DynamicCode BlockDynamicCode="true" AllowThreadsToOptOut="true" Audit="false" />
    <SignedBinaries MicrosoftSignedOnly="true" AllowStoreSignedBinaries="true" Audit="false" AuditStoreSigned="false" EnforceModuleDependencySigning="true" />
    <Fonts DisableNonSystemFonts="true" AuditOnly="false" Audit="false" />
    <ImageLoad BlockRemoteImageLoads="true" AuditRemoteImageLoads="false" BlockLowLabelImageLoads="true" AuditLowLabelImageLoads="false" />
    <Payload EnableExportAddressFilter="true" AuditEnableExportAddressFilter="false" EnableExportAddressFilterPlus="true" AuditEnableExportAddressFilterPlus="false" EnableImportAddressFilter="true" AuditEnableImportAddressFilter="false" EnableRopStackPivot="true" AuditEnableRopStackPivot="false" EnableRopCallerCheck="true" AuditEnableRopCallerCheck="false" EnableRopSimExec="true" AuditEnableRopSimExec="false" />
    <SEHOP Enable="true" TelemetryOnly="false" />
    <Heap TerminateOnError="true" />
    <ChildProcess DisallowChildProcessCreation="true" Audit="false" />
    <UserShadowStack UserShadowStack="true" UserShadowStackStrictMode="true" AuditUserShadowStack="false" />
  </AppConfig>
  <AppConfig Executable="NvCameraEnable.exe">
    <DEP Enable="true" EmulateAtlThunks="true" />
    <ASLR ForceRelocateImages="true" RequireInfo="true" BottomUp="true" HighEntropy="false" />
    <StrictHandle Enable="true" />
    <SystemCalls DisableWin32kSystemCalls="false" Audit="true" />
    <ExtensionPoints DisableExtensionPoints="true" />
    <DynamicCode BlockDynamicCode="false" AllowThreadsToOptOut="false" Audit="true" />
    <ControlFlowGuard Enable="true" SuppressExports="false" StrictControlFlowGuard="true" />
    <SignedBinaries MicrosoftSignedOnly="false" AllowStoreSignedBinaries="true" Audit="true" AuditStoreSigned="true" EnforceModuleDependencySigning="false" />
    <Fonts DisableNonSystemFonts="false" AuditOnly="false" Audit="true" />
    <ImageLoad BlockRemoteImageLoads="false" AuditRemoteImageLoads="true" BlockLowLabelImageLoads="false" AuditLowLabelImageLoads="true" />
    <Payload EnableExportAddressFilter="false" AuditEnableExportAddressFilter="true" EnableExportAddressFilterPlus="false" AuditEnableExportAddressFilterPlus="true" EnableImportAddressFilter="false" AuditEnableImportAddressFilter="true" EnableRopStackPivot="false" AuditEnableRopStackPivot="true" EnableRopCallerCheck="false" AuditEnableRopCallerCheck="true" EnableRopSimExec="false" AuditEnableRopSimExec="true" />
    <SEHOP Enable="true" TelemetryOnly="false" />
    <Heap TerminateOnError="true" />
    <ChildProcess DisallowChildProcessCreation="false" Audit="true" />
    <UserShadowStack UserShadowStack="false" UserShadowStackStrictMode="true" AuditUserShadowStack="true" />
  </AppConfig>
  <AppConfig Executable="nvdebugdump.exe">
    <DEP Enable="true" EmulateAtlThunks="true" />
    <ASLR ForceRelocateImages="true" RequireInfo="true" BottomUp="true" HighEntropy="false" />
    <StrictHandle Enable="true" />
    <SystemCalls DisableWin32kSystemCalls="false" Audit="true" />
    <ExtensionPoints DisableExtensionPoints="true" />
    <DynamicCode BlockDynamicCode="false" AllowThreadsToOptOut="false" Audit="true" />
    <ControlFlowGuard Enable="true" SuppressExports="false" StrictControlFlowGuard="true" />
    <SignedBinaries MicrosoftSignedOnly="false" AllowStoreSignedBinaries="true" Audit="true" AuditStoreSigned="true" EnforceModuleDependencySigning="false" />
    <Fonts DisableNonSystemFonts="false" AuditOnly="false" Audit="true" />
    <ImageLoad BlockRemoteImageLoads="false" AuditRemoteImageLoads="true" BlockLowLabelImageLoads="false" AuditLowLabelImageLoads="true" />
    <Payload EnableExportAddressFilter="false" AuditEnableExportAddressFilter="true" EnableExportAddressFilterPlus="false" AuditEnableExportAddressFilterPlus="true" EnableImportAddressFilter="false" AuditEnableImportAddressFilter="true" EnableRopStackPivot="false" AuditEnableRopStackPivot="true" EnableRopCallerCheck="false" AuditEnableRopCallerCheck="true" EnableRopSimExec="false" AuditEnableRopSimExec="true" />
    <SEHOP Enable="true" TelemetryOnly="false" />
    <Heap TerminateOnError="true" />
    <ChildProcess DisallowChildProcessCreation="true" Audit="false" />
    <UserShadowStack UserShadowStack="false" UserShadowStackStrictMode="true" AuditUserShadowStack="true" />
  </AppConfig>
  <AppConfig Executable="nvdispco64.exe">
    <DEP Enable="true" EmulateAtlThunks="true" />
    <ASLR ForceRelocateImages="true" RequireInfo="true" BottomUp="true" HighEntropy="false" />
    <StrictHandle Enable="true" />
    <SystemCalls DisableWin32kSystemCalls="false" Audit="true" />
    <ExtensionPoints DisableExtensionPoints="true" />
    <DynamicCode BlockDynamicCode="false" AllowThreadsToOptOut="false" Audit="true" />
    <ControlFlowGuard Enable="true" SuppressExports="false" StrictControlFlowGuard="true" />
    <SignedBinaries MicrosoftSignedOnly="false" AllowStoreSignedBinaries="true" Audit="true" AuditStoreSigned="true" EnforceModuleDependencySigning="false" />
    <Fonts DisableNonSystemFonts="false" AuditOnly="false" Audit="true" />
    <ImageLoad BlockRemoteImageLoads="false" AuditRemoteImageLoads="true" BlockLowLabelImageLoads="false" AuditLowLabelImageLoads="true" />
    <Payload EnableExportAddressFilter="false" AuditEnableExportAddressFilter="true" EnableExportAddressFilterPlus="false" AuditEnableExportAddressFilterPlus="true" EnableImportAddressFilter="false" AuditEnableImportAddressFilter="true" EnableRopStackPivot="false" AuditEnableRopStackPivot="true" EnableRopCallerCheck="false" AuditEnableRopCallerCheck="true" EnableRopSimExec="false" AuditEnableRopSimExec="true" />
    <SEHOP Enable="true" TelemetryOnly="false" />
    <Heap TerminateOnError="true" />
    <ChildProcess DisallowChildProcessCreation="false" Audit="true" />
    <UserShadowStack UserShadowStack="false" UserShadowStackStrictMode="true" AuditUserShadowStack="true" />
  </AppConfig>
  <AppConfig Executable="NVDisplay.Container.exe">
    <DEP Enable="true" EmulateAtlThunks="true" />
    <ASLR ForceRelocateImages="true" RequireInfo="true" BottomUp="true" HighEntropy="true" />
    <StrictHandle Enable="true" />
    <SystemCalls DisableWin32kSystemCalls="true" Audit="false" />
    <ExtensionPoints DisableExtensionPoints="true" />
    <DynamicCode BlockDynamicCode="true" AllowThreadsToOptOut="true" Audit="false" />
    <ControlFlowGuard Enable="true" SuppressExports="false" StrictControlFlowGuard="true" />
    <SignedBinaries MicrosoftSignedOnly="true" AllowStoreSignedBinaries="true" Audit="false" AuditStoreSigned="false" EnforceModuleDependencySigning="true" />
    <Fonts DisableNonSystemFonts="true" AuditOnly="false" Audit="false" />
    <ImageLoad BlockRemoteImageLoads="true" AuditRemoteImageLoads="false" BlockLowLabelImageLoads="true" AuditLowLabelImageLoads="false" />
    <Payload EnableExportAddressFilter="true" AuditEnableExportAddressFilter="false" EnableExportAddressFilterPlus="true" AuditEnableExportAddressFilterPlus="false" EnableImportAddressFilter="true" AuditEnableImportAddressFilter="false" EnableRopStackPivot="true" AuditEnableRopStackPivot="false" EnableRopCallerCheck="true" AuditEnableRopCallerCheck="false" EnableRopSimExec="true" AuditEnableRopSimExec="false" />
    <SEHOP Enable="true" TelemetryOnly="false" />
    <Heap TerminateOnError="true" />
    <ChildProcess DisallowChildProcessCreation="true" Audit="false" />
    <UserShadowStack UserShadowStack="true" UserShadowStackStrictMode="true" AuditUserShadowStack="false" />
  </AppConfig>
  <AppConfig Executable="nvgwls.exe">
    <DEP Enable="true" EmulateAtlThunks="true" />
    <ASLR ForceRelocateImages="true" RequireInfo="true" BottomUp="true" HighEntropy="false" />
    <StrictHandle Enable="true" />
    <SystemCalls DisableWin32kSystemCalls="false" Audit="true" />
    <ExtensionPoints DisableExtensionPoints="true" />
    <DynamicCode BlockDynamicCode="false" AllowThreadsToOptOut="false" Audit="true" />
    <ControlFlowGuard Enable="true" SuppressExports="false" StrictControlFlowGuard="true" />
    <SignedBinaries MicrosoftSignedOnly="false" AllowStoreSignedBinaries="true" Audit="true" AuditStoreSigned="true" EnforceModuleDependencySigning="false" />
    <Fonts DisableNonSystemFonts="false" AuditOnly="false" Audit="true" />
    <ImageLoad BlockRemoteImageLoads="false" AuditRemoteImageLoads="true" BlockLowLabelImageLoads="false" AuditLowLabelImageLoads="true" />
    <Payload EnableExportAddressFilter="false" AuditEnableExportAddressFilter="true" EnableExportAddressFilterPlus="false" AuditEnableExportAddressFilterPlus="true" EnableImportAddressFilter="false" AuditEnableImportAddressFilter="true" EnableRopStackPivot="false" AuditEnableRopStackPivot="true" EnableRopCallerCheck="false" AuditEnableRopCallerCheck="true" EnableRopSimExec="false" AuditEnableRopSimExec="true" />
    <SEHOP Enable="true" TelemetryOnly="false" />
    <Heap TerminateOnError="true" />
    <ChildProcess DisallowChildProcessCreation="false" Audit="true" />
    <UserShadowStack UserShadowStack="false" UserShadowStackStrictMode="true" AuditUserShadowStack="true" />
  </AppConfig>
  <AppConfig Executable="nvidia-pcc.exe">
    <DEP Enable="true" EmulateAtlThunks="true" />
    <ASLR ForceRelocateImages="true" RequireInfo="true" BottomUp="true" HighEntropy="false" />
    <StrictHandle Enable="true" />
    <SystemCalls DisableWin32kSystemCalls="false" Audit="true" />
    <ExtensionPoints DisableExtensionPoints="true" />
    <DynamicCode BlockDynamicCode="false" AllowThreadsToOptOut="false" Audit="true" />
    <ControlFlowGuard Enable="true" SuppressExports="false" StrictControlFlowGuard="true" />
    <SignedBinaries MicrosoftSignedOnly="false" AllowStoreSignedBinaries="true" Audit="true" AuditStoreSigned="true" EnforceModuleDependencySigning="false" />
    <Fonts DisableNonSystemFonts="false" AuditOnly="false" Audit="true" />
    <ImageLoad BlockRemoteImageLoads="false" AuditRemoteImageLoads="true" BlockLowLabelImageLoads="false" AuditLowLabelImageLoads="true" />
    <Payload EnableExportAddressFilter="false" AuditEnableExportAddressFilter="true" EnableExportAddressFilterPlus="false" AuditEnableExportAddressFilterPlus="true" EnableImportAddressFilter="false" AuditEnableImportAddressFilter="true" EnableRopStackPivot="false" AuditEnableRopStackPivot="true" EnableRopCallerCheck="false" AuditEnableRopCallerCheck="true" EnableRopSimExec="false" AuditEnableRopSimExec="true" />
    <SEHOP Enable="true" TelemetryOnly="false" />
    <Heap TerminateOnError="true" />
    <ChildProcess DisallowChildProcessCreation="false" Audit="true" />
    <UserShadowStack UserShadowStack="false" UserShadowStackStrictMode="true" AuditUserShadowStack="true" />
  </AppConfig>
  <AppConfig Executable="nvidia-smi.exe">
    <DEP Enable="true" EmulateAtlThunks="true" />
    <ASLR ForceRelocateImages="true" RequireInfo="true" BottomUp="true" HighEntropy="false" />
    <StrictHandle Enable="true" />
    <SystemCalls DisableWin32kSystemCalls="false" Audit="true" />
    <ExtensionPoints DisableExtensionPoints="true" />
    <DynamicCode BlockDynamicCode="false" AllowThreadsToOptOut="false" Audit="true" />
    <ControlFlowGuard Enable="true" SuppressExports="false" StrictControlFlowGuard="true" />
    <SignedBinaries MicrosoftSignedOnly="false" AllowStoreSignedBinaries="true" Audit="true" AuditStoreSigned="true" EnforceModuleDependencySigning="false" />
    <Fonts DisableNonSystemFonts="false" AuditOnly="false" Audit="true" />
    <ImageLoad BlockRemoteImageLoads="false" AuditRemoteImageLoads="true" BlockLowLabelImageLoads="false" AuditLowLabelImageLoads="true" />
    <Payload EnableExportAddressFilter="false" AuditEnableExportAddressFilter="true" EnableExportAddressFilterPlus="false" AuditEnableExportAddressFilterPlus="true" EnableImportAddressFilter="false" AuditEnableImportAddressFilter="true" EnableRopStackPivot="false" AuditEnableRopStackPivot="true" EnableRopCallerCheck="false" AuditEnableRopCallerCheck="true" EnableRopSimExec="false" AuditEnableRopSimExec="true" />
    <SEHOP Enable="true" TelemetryOnly="false" />
    <Heap TerminateOnError="true" />
    <ChildProcess DisallowChildProcessCreation="false" Audit="true" />
    <UserShadowStack UserShadowStack="false" UserShadowStackStrictMode="true" AuditUserShadowStack="true" />
  </AppConfig>
  <AppConfig Executable="NvImageConvert32.exe">
    <DEP Enable="true" EmulateAtlThunks="true" />
    <ASLR ForceRelocateImages="true" RequireInfo="true" BottomUp="true" HighEntropy="false" />
    <StrictHandle Enable="true" />
    <SystemCalls DisableWin32kSystemCalls="false" Audit="true" />
    <ExtensionPoints DisableExtensionPoints="true" />
    <DynamicCode BlockDynamicCode="false" AllowThreadsToOptOut="false" Audit="true" />
    <ControlFlowGuard Enable="true" SuppressExports="false" StrictControlFlowGuard="true" />
    <SignedBinaries MicrosoftSignedOnly="false" AllowStoreSignedBinaries="true" Audit="true" AuditStoreSigned="true" EnforceModuleDependencySigning="false" />
    <Fonts DisableNonSystemFonts="false" AuditOnly="false" Audit="true" />
    <ImageLoad BlockRemoteImageLoads="false" AuditRemoteImageLoads="true" BlockLowLabelImageLoads="false" AuditLowLabelImageLoads="true" />
    <Payload EnableExportAddressFilter="false" AuditEnableExportAddressFilter="true" EnableExportAddressFilterPlus="false" AuditEnableExportAddressFilterPlus="true" EnableImportAddressFilter="false" AuditEnableImportAddressFilter="true" EnableRopStackPivot="false" AuditEnableRopStackPivot="true" EnableRopCallerCheck="false" AuditEnableRopCallerCheck="true" EnableRopSimExec="false" AuditEnableRopSimExec="true" />
    <SEHOP Enable="true" TelemetryOnly="false" />
    <Heap TerminateOnError="true" />
    <ChildProcess DisallowChildProcessCreation="false" Audit="true" />
    <UserShadowStack UserShadowStack="false" UserShadowStackStrictMode="true" AuditUserShadowStack="true" />
  </AppConfig>
  <AppConfig Executable="NvImageConvert64.exe">
    <DEP Enable="true" EmulateAtlThunks="true" />
    <ASLR ForceRelocateImages="true" RequireInfo="true" BottomUp="true" HighEntropy="false" />
    <StrictHandle Enable="true" />
    <SystemCalls DisableWin32kSystemCalls="false" Audit="true" />
    <ExtensionPoints DisableExtensionPoints="true" />
    <DynamicCode BlockDynamicCode="false" AllowThreadsToOptOut="false" Audit="true" />
    <ControlFlowGuard Enable="true" SuppressExports="false" StrictControlFlowGuard="true" />
    <SignedBinaries MicrosoftSignedOnly="false" AllowStoreSignedBinaries="true" Audit="true" AuditStoreSigned="true" EnforceModuleDependencySigning="false" />
    <Fonts DisableNonSystemFonts="false" AuditOnly="false" Audit="true" />
    <ImageLoad BlockRemoteImageLoads="false" AuditRemoteImageLoads="true" BlockLowLabelImageLoads="false" AuditLowLabelImageLoads="true" />
    <Payload EnableExportAddressFilter="false" AuditEnableExportAddressFilter="true" EnableExportAddressFilterPlus="false" AuditEnableExportAddressFilterPlus="true" EnableImportAddressFilter="false" AuditEnableImportAddressFilter="true" EnableRopStackPivot="false" AuditEnableRopStackPivot="true" EnableRopCallerCheck="false" AuditEnableRopCallerCheck="true" EnableRopSimExec="false" AuditEnableRopSimExec="true" />
    <SEHOP Enable="true" TelemetryOnly="false" />
    <Heap TerminateOnError="true" />
    <ChildProcess DisallowChildProcessCreation="false" Audit="true" />
    <UserShadowStack UserShadowStack="false" UserShadowStackStrictMode="true" AuditUserShadowStack="true" />
  </AppConfig>
  <AppConfig Executable="nvngx_update.exe">
    <DEP Enable="true" EmulateAtlThunks="true" />
    <ASLR ForceRelocateImages="true" RequireInfo="true" BottomUp="true" HighEntropy="false" />
    <StrictHandle Enable="true" />
    <SystemCalls DisableWin32kSystemCalls="false" Audit="true" />
    <ExtensionPoints DisableExtensionPoints="true" />
    <DynamicCode BlockDynamicCode="false" AllowThreadsToOptOut="false" Audit="true" />
    <ControlFlowGuard Enable="true" SuppressExports="false" StrictControlFlowGuard="true" />
    <SignedBinaries MicrosoftSignedOnly="false" AllowStoreSignedBinaries="true" Audit="true" AuditStoreSigned="true" EnforceModuleDependencySigning="false" />
    <Fonts DisableNonSystemFonts="false" AuditOnly="false" Audit="true" />
    <ImageLoad BlockRemoteImageLoads="false" AuditRemoteImageLoads="true" BlockLowLabelImageLoads="false" AuditLowLabelImageLoads="true" />
    <Payload EnableExportAddressFilter="false" AuditEnableExportAddressFilter="true" EnableExportAddressFilterPlus="false" AuditEnableExportAddressFilterPlus="true" EnableImportAddressFilter="false" AuditEnableImportAddressFilter="true" EnableRopStackPivot="false" AuditEnableRopStackPivot="true" EnableRopCallerCheck="false" AuditEnableRopCallerCheck="true" EnableRopSimExec="false" AuditEnableRopSimExec="true" />
    <SEHOP Enable="true" TelemetryOnly="false" />
    <Heap TerminateOnError="true" />
    <ChildProcess DisallowChildProcessCreation="false" Audit="true" />
    <UserShadowStack UserShadowStack="false" UserShadowStackStrictMode="true" AuditUserShadowStack="true" />
  </AppConfig>
  <AppConfig Executable="nvsmartmaxapp.exe">
    <DEP Enable="true" EmulateAtlThunks="true" />
    <ASLR ForceRelocateImages="true" RequireInfo="true" BottomUp="true" HighEntropy="false" />
    <StrictHandle Enable="true" />
    <SystemCalls DisableWin32kSystemCalls="false" Audit="true" />
    <ExtensionPoints DisableExtensionPoints="true" />
    <DynamicCode BlockDynamicCode="false" AllowThreadsToOptOut="false" Audit="true" />
    <ControlFlowGuard Enable="true" SuppressExports="false" StrictControlFlowGuard="true" />
    <SignedBinaries MicrosoftSignedOnly="false" AllowStoreSignedBinaries="true" Audit="true" AuditStoreSigned="true" EnforceModuleDependencySigning="false" />
    <Fonts DisableNonSystemFonts="false" AuditOnly="false" Audit="true" />
    <ImageLoad BlockRemoteImageLoads="false" AuditRemoteImageLoads="true" BlockLowLabelImageLoads="false" AuditLowLabelImageLoads="true" />
    <Payload EnableExportAddressFilter="false" AuditEnableExportAddressFilter="true" EnableExportAddressFilterPlus="false" AuditEnableExportAddressFilterPlus="true" EnableImportAddressFilter="false" AuditEnableImportAddressFilter="true" EnableRopStackPivot="false" AuditEnableRopStackPivot="true" EnableRopCallerCheck="false" AuditEnableRopCallerCheck="true" EnableRopSimExec="false" AuditEnableRopSimExec="true" />
    <SEHOP Enable="true" TelemetryOnly="false" />
    <Heap TerminateOnError="true" />
    <ChildProcess DisallowChildProcessCreation="false" Audit="true" />
    <UserShadowStack UserShadowStack="false" UserShadowStackStrictMode="true" AuditUserShadowStack="true" />
  </AppConfig>
  <AppConfig Executable="nvsmartmaxapp64.exe">
    <DEP Enable="true" EmulateAtlThunks="true" />
    <ASLR ForceRelocateImages="true" RequireInfo="true" BottomUp="true" HighEntropy="false" />
    <StrictHandle Enable="true" />
    <SystemCalls DisableWin32kSystemCalls="false" Audit="true" />
    <ExtensionPoints DisableExtensionPoints="true" />
    <DynamicCode BlockDynamicCode="false" AllowThreadsToOptOut="false" Audit="true" />
    <ControlFlowGuard Enable="true" SuppressExports="false" StrictControlFlowGuard="true" />
    <SignedBinaries MicrosoftSignedOnly="false" AllowStoreSignedBinaries="true" Audit="true" AuditStoreSigned="true" EnforceModuleDependencySigning="false" />
    <Fonts DisableNonSystemFonts="false" AuditOnly="false" Audit="true" />
    <ImageLoad BlockRemoteImageLoads="false" AuditRemoteImageLoads="true" BlockLowLabelImageLoads="false" AuditLowLabelImageLoads="true" />
    <Payload EnableExportAddressFilter="false" AuditEnableExportAddressFilter="true" EnableExportAddressFilterPlus="false" AuditEnableExportAddressFilterPlus="true" EnableImportAddressFilter="false" AuditEnableImportAddressFilter="true" EnableRopStackPivot="false" AuditEnableRopStackPivot="true" EnableRopCallerCheck="false" AuditEnableRopCallerCheck="true" EnableRopSimExec="false" AuditEnableRopSimExec="true" />
    <SEHOP Enable="true" TelemetryOnly="false" />
    <Heap TerminateOnError="true" />
    <ChildProcess DisallowChildProcessCreation="false" Audit="true" />
    <UserShadowStack UserShadowStack="false" UserShadowStackStrictMode="true" AuditUserShadowStack="true" />
  </AppConfig>
  <AppConfig Executable="nvWmi64.exe">
    <DEP Enable="true" EmulateAtlThunks="true" />
    <ASLR ForceRelocateImages="true" RequireInfo="true" BottomUp="true" HighEntropy="false" />
    <StrictHandle Enable="true" />
    <SystemCalls DisableWin32kSystemCalls="false" Audit="true" />
    <ExtensionPoints DisableExtensionPoints="true" />
    <DynamicCode BlockDynamicCode="false" AllowThreadsToOptOut="false" Audit="true" />
    <ControlFlowGuard Enable="true" SuppressExports="false" StrictControlFlowGuard="true" />
    <SignedBinaries MicrosoftSignedOnly="false" AllowStoreSignedBinaries="true" Audit="true" AuditStoreSigned="true" EnforceModuleDependencySigning="false" />
    <Fonts DisableNonSystemFonts="false" AuditOnly="false" Audit="true" />
    <ImageLoad BlockRemoteImageLoads="false" AuditRemoteImageLoads="true" BlockLowLabelImageLoads="false" AuditLowLabelImageLoads="true" />
    <Payload EnableExportAddressFilter="false" AuditEnableExportAddressFilter="true" EnableExportAddressFilterPlus="false" AuditEnableExportAddressFilterPlus="true" EnableImportAddressFilter="false" AuditEnableImportAddressFilter="true" EnableRopStackPivot="false" AuditEnableRopStackPivot="true" EnableRopCallerCheck="false" AuditEnableRopCallerCheck="true" EnableRopSimExec="false" AuditEnableRopSimExec="true" />
    <SEHOP Enable="true" TelemetryOnly="false" />
    <Heap TerminateOnError="true" />
    <ChildProcess DisallowChildProcessCreation="false" Audit="true" />
    <UserShadowStack UserShadowStack="false" UserShadowStackStrictMode="true" AuditUserShadowStack="true" />
  </AppConfig>
  <AppConfig Executable="openvpn-gui.exe">
    <DEP Enable="true" EmulateAtlThunks="true" />
    <ASLR BottomUp="true" HighEntropy="true" />
    <StrictHandle Enable="true" />
    <SystemCalls DisableWin32kSystemCalls="true" Audit="false" />
    <ExtensionPoints DisableExtensionPoints="true" />
    <DynamicCode BlockDynamicCode="false" AllowThreadsToOptOut="false" Audit="true" />
    <SignedBinaries MicrosoftSignedOnly="true" AllowStoreSignedBinaries="true" Audit="false" AuditStoreSigned="false" EnforceModuleDependencySigning="true" />
    <Fonts DisableNonSystemFonts="false" AuditOnly="false" Audit="true" />
    <ImageLoad BlockRemoteImageLoads="false" AuditRemoteImageLoads="true" BlockLowLabelImageLoads="false" AuditLowLabelImageLoads="true" />
    <Payload EnableExportAddressFilter="true" AuditEnableExportAddressFilter="false" EnableExportAddressFilterPlus="true" AuditEnableExportAddressFilterPlus="false" EnableImportAddressFilter="true" AuditEnableImportAddressFilter="false" EnableRopStackPivot="true" AuditEnableRopStackPivot="false" EnableRopCallerCheck="true" AuditEnableRopCallerCheck="false" EnableRopSimExec="true" AuditEnableRopSimExec="false" />
    <SEHOP Enable="true" TelemetryOnly="false" />
    <Heap TerminateOnError="true" />
    <ChildProcess DisallowChildProcessCreation="true" Audit="false" />
    <UserShadowStack UserShadowStack="true" UserShadowStackStrictMode="true" AuditUserShadowStack="false" />
  </AppConfig>
  <AppConfig Executable="openvpn.exe">
    <DEP Enable="true" EmulateAtlThunks="true" />
    <ASLR BottomUp="true" HighEntropy="false" />
    <StrictHandle Enable="true" />
    <SystemCalls DisableWin32kSystemCalls="false" Audit="true" />
    <ExtensionPoints DisableExtensionPoints="true" />
    <DynamicCode BlockDynamicCode="false" AllowThreadsToOptOut="false" Audit="true" />
    <SignedBinaries MicrosoftSignedOnly="false" AllowStoreSignedBinaries="true" Audit="true" AuditStoreSigned="true" EnforceModuleDependencySigning="false" />
    <Fonts DisableNonSystemFonts="false" AuditOnly="false" Audit="true" />
    <ImageLoad BlockRemoteImageLoads="false" AuditRemoteImageLoads="true" BlockLowLabelImageLoads="false" AuditLowLabelImageLoads="true" />
    <Payload EnableExportAddressFilter="false" AuditEnableExportAddressFilter="true" EnableExportAddressFilterPlus="false" AuditEnableExportAddressFilterPlus="true" EnableImportAddressFilter="false" AuditEnableImportAddressFilter="true" EnableRopStackPivot="true" AuditEnableRopStackPivot="false" EnableRopCallerCheck="false" AuditEnableRopCallerCheck="true" EnableRopSimExec="false" AuditEnableRopSimExec="true" />
    <SEHOP Enable="true" TelemetryOnly="false" />
    <Heap TerminateOnError="true" />
    <ChildProcess DisallowChildProcessCreation="false" Audit="true" />
    <UserShadowStack UserShadowStack="true" UserShadowStackStrictMode="true" AuditUserShadowStack="false" />
  </AppConfig>
  <AppConfig Executable="openvpnserv.exe">
    <DEP Enable="true" EmulateAtlThunks="false" />
    <ASLR BottomUp="true" HighEntropy="false" />
    <StrictHandle Enable="true" />
    <SystemCalls DisableWin32kSystemCalls="true" Audit="false" />
    <ExtensionPoints DisableExtensionPoints="true" />
    <DynamicCode BlockDynamicCode="false" AllowThreadsToOptOut="false" Audit="true" />
    <SignedBinaries MicrosoftSignedOnly="false" AllowStoreSignedBinaries="true" Audit="true" AuditStoreSigned="true" EnforceModuleDependencySigning="false" />
    <Fonts DisableNonSystemFonts="false" AuditOnly="false" Audit="true" />
    <ImageLoad BlockRemoteImageLoads="false" AuditRemoteImageLoads="true" BlockLowLabelImageLoads="false" AuditLowLabelImageLoads="true" />
    <Payload EnableExportAddressFilter="true" AuditEnableExportAddressFilter="false" EnableExportAddressFilterPlus="true" AuditEnableExportAddressFilterPlus="false" EnableImportAddressFilter="false" AuditEnableImportAddressFilter="true" EnableRopStackPivot="true" AuditEnableRopStackPivot="false" EnableRopCallerCheck="false" AuditEnableRopCallerCheck="true" EnableRopSimExec="false" AuditEnableRopSimExec="true" />
    <SEHOP Enable="true" TelemetryOnly="false" />
    <Heap TerminateOnError="true" />
    <ChildProcess DisallowChildProcessCreation="false" Audit="true" />
    <UserShadowStack UserShadowStack="true" UserShadowStackStrictMode="true" AuditUserShadowStack="false" />
  </AppConfig>
  <AppConfig Executable="Opera-x64.exe">
    <DEP Enable="true" EmulateAtlThunks="true" />
    <ASLR BottomUp="true" HighEntropy="false" />
    <StrictHandle Enable="true" />
    <SystemCalls DisableWin32kSystemCalls="false" Audit="true" />
    <ExtensionPoints DisableExtensionPoints="true" />
    <DynamicCode BlockDynamicCode="false" AllowThreadsToOptOut="false" Audit="true" />
    <ControlFlowGuard Enable="true" SuppressExports="false" StrictControlFlowGuard="true" />
    <SignedBinaries MicrosoftSignedOnly="false" AllowStoreSignedBinaries="true" Audit="true" AuditStoreSigned="true" EnforceModuleDependencySigning="false" />
    <Fonts DisableNonSystemFonts="false" AuditOnly="false" Audit="true" />
    <ImageLoad BlockRemoteImageLoads="false" AuditRemoteImageLoads="true" BlockLowLabelImageLoads="false" AuditLowLabelImageLoads="true" />
    <Payload EnableExportAddressFilter="true" AuditEnableExportAddressFilter="false" EnableExportAddressFilterPlus="true" AuditEnableExportAddressFilterPlus="false" EnableImportAddressFilter="false" AuditEnableImportAddressFilter="true" EnableRopStackPivot="true" AuditEnableRopStackPivot="false" EnableRopCallerCheck="true" AuditEnableRopCallerCheck="false" EnableRopSimExec="false" AuditEnableRopSimExec="true" />
    <SEHOP Enable="true" TelemetryOnly="false" />
    <Heap TerminateOnError="true" />
    <ChildProcess DisallowChildProcessCreation="false" Audit="true" />
    <UserShadowStack UserShadowStack="true" UserShadowStackStrictMode="true" AuditUserShadowStack="false" />
  </AppConfig>
  <AppConfig Executable="opera.exe">
    <DEP Enable="true" EmulateAtlThunks="false" />
    <ASLR BottomUp="true" HighEntropy="true" />
    <StrictHandle Enable="true" />
    <SystemCalls DisableWin32kSystemCalls="true" Audit="false" />
    <ExtensionPoints DisableExtensionPoints="true" />
    <DynamicCode BlockDynamicCode="true" AllowThreadsToOptOut="true" Audit="false" />
    <SignedBinaries MicrosoftSignedOnly="true" AllowStoreSignedBinaries="true" Audit="false" AuditStoreSigned="false" EnforceModuleDependencySigning="true" />
    <Fonts DisableNonSystemFonts="true" AuditOnly="false" Audit="false" />
    <ImageLoad BlockRemoteImageLoads="true" AuditRemoteImageLoads="false" BlockLowLabelImageLoads="true" AuditLowLabelImageLoads="false" />
    <Payload EnableExportAddressFilter="true" AuditEnableExportAddressFilter="false" EnableExportAddressFilterPlus="true" AuditEnableExportAddressFilterPlus="false" EnableImportAddressFilter="true" AuditEnableImportAddressFilter="false" EnableRopStackPivot="true" AuditEnableRopStackPivot="false" EnableRopCallerCheck="true" AuditEnableRopCallerCheck="false" EnableRopSimExec="true" AuditEnableRopSimExec="false" />
    <SEHOP Enable="true" TelemetryOnly="false" />
    <Heap TerminateOnError="true" />
    <ChildProcess DisallowChildProcessCreation="true" Audit="false" />
    <UserShadowStack UserShadowStack="true" UserShadowStackStrictMode="true" AuditUserShadowStack="false" />
  </AppConfig>
  <AppConfig Executable="opera_autoupdate.exe">
    <DEP Enable="true" EmulateAtlThunks="true" />
    <ASLR BottomUp="true" HighEntropy="true" />
    <StrictHandle Enable="true" />
    <SystemCalls DisableWin32kSystemCalls="true" Audit="false" />
    <ExtensionPoints DisableExtensionPoints="true" />
    <DynamicCode BlockDynamicCode="true" AllowThreadsToOptOut="true" Audit="false" />
    <SignedBinaries MicrosoftSignedOnly="true" AllowStoreSignedBinaries="true" Audit="false" AuditStoreSigned="false" EnforceModuleDependencySigning="true" />
    <Fonts DisableNonSystemFonts="true" AuditOnly="false" Audit="false" />
    <ImageLoad BlockRemoteImageLoads="true" AuditRemoteImageLoads="false" BlockLowLabelImageLoads="true" AuditLowLabelImageLoads="false" />
    <Payload EnableExportAddressFilter="true" AuditEnableExportAddressFilter="false" EnableExportAddressFilterPlus="true" AuditEnableExportAddressFilterPlus="false" EnableImportAddressFilter="true" AuditEnableImportAddressFilter="false" EnableRopStackPivot="true" AuditEnableRopStackPivot="false" EnableRopCallerCheck="true" AuditEnableRopCallerCheck="false" EnableRopSimExec="true" AuditEnableRopSimExec="false" />
    <SEHOP Enable="true" TelemetryOnly="false" />
    <Heap TerminateOnError="true" />
    <ChildProcess DisallowChildProcessCreation="false" Audit="true" />
    <UserShadowStack UserShadowStack="true" UserShadowStackStrictMode="true" AuditUserShadowStack="false" />
  </AppConfig>
  <AppConfig Executable="opera_crashreporter.exe">
    <DEP Enable="true" EmulateAtlThunks="true" />
    <ASLR BottomUp="true" HighEntropy="true" />
    <StrictHandle Enable="true" />
    <SystemCalls DisableWin32kSystemCalls="true" Audit="false" />
    <ExtensionPoints DisableExtensionPoints="true" />
    <DynamicCode BlockDynamicCode="true" AllowThreadsToOptOut="true" Audit="false" />
    <SignedBinaries MicrosoftSignedOnly="true" AllowStoreSignedBinaries="true" Audit="false" AuditStoreSigned="false" EnforceModuleDependencySigning="true" />
    <Fonts DisableNonSystemFonts="true" AuditOnly="false" Audit="false" />
    <ImageLoad BlockRemoteImageLoads="true" AuditRemoteImageLoads="false" BlockLowLabelImageLoads="true" AuditLowLabelImageLoads="false" />
    <Payload EnableExportAddressFilter="true" AuditEnableExportAddressFilter="false" EnableExportAddressFilterPlus="true" AuditEnableExportAddressFilterPlus="false" EnableImportAddressFilter="true" AuditEnableImportAddressFilter="false" EnableRopStackPivot="true" AuditEnableRopStackPivot="false" EnableRopCallerCheck="true" AuditEnableRopCallerCheck="false" EnableRopSimExec="true" AuditEnableRopSimExec="false" />
    <SEHOP Enable="true" TelemetryOnly="false" />
    <Heap TerminateOnError="true" />
    <ChildProcess DisallowChildProcessCreation="true" Audit="false" />
    <UserShadowStack UserShadowStack="true" UserShadowStackStrictMode="true" AuditUserShadowStack="false" />
  </AppConfig>
  <AppConfig Executable="opera_gx_splash.exe">
    <DEP Enable="true" EmulateAtlThunks="false" />
    <ASLR ForceRelocateImages="true" RequireInfo="false" BottomUp="true" HighEntropy="true" />
    <StrictHandle Enable="true" />
    <SystemCalls DisableWin32kSystemCalls="true" Audit="false" />
    <ExtensionPoints DisableExtensionPoints="true" />
    <DynamicCode BlockDynamicCode="true" AllowThreadsToOptOut="true" Audit="false" />
    <ControlFlowGuard Enable="true" SuppressExports="false" />
    <SignedBinaries MicrosoftSignedOnly="true" AllowStoreSignedBinaries="true" Audit="false" AuditStoreSigned="false" EnforceModuleDependencySigning="true" />
    <Fonts DisableNonSystemFonts="false" AuditOnly="false" />
    <ImageLoad BlockRemoteImageLoads="true" AuditRemoteImageLoads="false" BlockLowLabelImageLoads="true" AuditLowLabelImageLoads="false" />
    <Payload EnableExportAddressFilter="true" AuditEnableExportAddressFilter="false" EnableExportAddressFilterPlus="true" AuditEnableExportAddressFilterPlus="false" EnableImportAddressFilter="true" AuditEnableImportAddressFilter="false" EnableRopStackPivot="true" AuditEnableRopStackPivot="false" EnableRopCallerCheck="true" AuditEnableRopCallerCheck="false" EnableRopSimExec="true" AuditEnableRopSimExec="false" />
    <SEHOP Enable="true" TelemetryOnly="false" />
    <Heap TerminateOnError="true" />
    <ChildProcess DisallowChildProcessCreation="true" Audit="false" />
    <UserShadowStack UserShadowStack="true" UserShadowStackStrictMode="true" AuditUserShadowStack="false" />
  </AppConfig>
  <AppConfig Executable="os_update_handler.exe">
    <DEP Enable="true" EmulateAtlThunks="false" />
    <ASLR BottomUp="true" HighEntropy="true" />
    <StrictHandle Enable="true" />
    <SystemCalls DisableWin32kSystemCalls="true" Audit="false" />
    <ExtensionPoints DisableExtensionPoints="true" />
    <DynamicCode BlockDynamicCode="true" AllowThreadsToOptOut="true" Audit="false" />
    <SignedBinaries MicrosoftSignedOnly="true" AllowStoreSignedBinaries="true" Audit="false" AuditStoreSigned="false" EnforceModuleDependencySigning="true" />
    <Fonts DisableNonSystemFonts="true" AuditOnly="false" Audit="false" />
    <ImageLoad BlockRemoteImageLoads="true" AuditRemoteImageLoads="false" BlockLowLabelImageLoads="true" AuditLowLabelImageLoads="false" />
    <Payload EnableExportAddressFilter="true" AuditEnableExportAddressFilter="false" EnableExportAddressFilterPlus="true" AuditEnableExportAddressFilterPlus="false" EnableImportAddressFilter="true" AuditEnableImportAddressFilter="false" EnableRopStackPivot="true" AuditEnableRopStackPivot="false" EnableRopCallerCheck="true" AuditEnableRopCallerCheck="false" EnableRopSimExec="true" AuditEnableRopSimExec="false" />
    <SEHOP Enable="true" TelemetryOnly="false" />
    <Heap TerminateOnError="true" />
    <ChildProcess DisallowChildProcessCreation="true" Audit="false" />
    <UserShadowStack UserShadowStack="true" UserShadowStackStrictMode="true" AuditUserShadowStack="false" />
  </AppConfig>
  <AppConfig Executable="Pot.Player-x64.exe">
    <DEP Enable="true" EmulateAtlThunks="true" />
    <ASLR BottomUp="true" HighEntropy="false" />
    <StrictHandle Enable="true" />
    <SystemCalls DisableWin32kSystemCalls="true" Audit="false" />
    <ExtensionPoints DisableExtensionPoints="true" />
    <DynamicCode BlockDynamicCode="false" AllowThreadsToOptOut="false" Audit="true" />
    <SignedBinaries MicrosoftSignedOnly="false" AllowStoreSignedBinaries="true" Audit="true" AuditStoreSigned="true" EnforceModuleDependencySigning="false" />
    <Fonts DisableNonSystemFonts="false" AuditOnly="false" Audit="true" />
    <ImageLoad BlockRemoteImageLoads="false" AuditRemoteImageLoads="true" BlockLowLabelImageLoads="false" AuditLowLabelImageLoads="true" />
    <Payload EnableExportAddressFilter="false" AuditEnableExportAddressFilter="true" EnableExportAddressFilterPlus="false" AuditEnableExportAddressFilterPlus="true" EnableImportAddressFilter="false" AuditEnableImportAddressFilter="true" EnableRopStackPivot="true" AuditEnableRopStackPivot="false" EnableRopCallerCheck="false" AuditEnableRopCallerCheck="true" EnableRopSimExec="false" AuditEnableRopSimExec="true" />
    <SEHOP Enable="true" TelemetryOnly="false" />
    <Heap TerminateOnError="true" />
    <ChildProcess DisallowChildProcessCreation="false" Audit="true" />
    <UserShadowStack UserShadowStack="true" UserShadowStackStrictMode="true" AuditUserShadowStack="false" />
  </AppConfig>
  <AppConfig Executable="PotPlayerMini64.exe">
    <DEP Enable="true" EmulateAtlThunks="true" />
    <ASLR BottomUp="true" HighEntropy="false" />
    <StrictHandle Enable="true" />
    <SystemCalls DisableWin32kSystemCalls="false" Audit="true" />
    <ExtensionPoints DisableExtensionPoints="true" />
    <DynamicCode BlockDynamicCode="false" AllowThreadsToOptOut="false" Audit="true" />
    <SignedBinaries MicrosoftSignedOnly="false" AllowStoreSignedBinaries="true" Audit="true" AuditStoreSigned="true" EnforceModuleDependencySigning="false" />
    <Fonts DisableNonSystemFonts="false" AuditOnly="false" Audit="true" />
    <ImageLoad BlockRemoteImageLoads="false" AuditRemoteImageLoads="true" BlockLowLabelImageLoads="false" AuditLowLabelImageLoads="true" />
    <Payload EnableExportAddressFilter="false" AuditEnableExportAddressFilter="true" EnableExportAddressFilterPlus="false" AuditEnableExportAddressFilterPlus="true" EnableImportAddressFilter="false" AuditEnableImportAddressFilter="true" EnableRopStackPivot="false" AuditEnableRopStackPivot="true" EnableRopCallerCheck="false" AuditEnableRopCallerCheck="true" EnableRopSimExec="false" AuditEnableRopSimExec="true" />
    <SEHOP Enable="true" TelemetryOnly="false" />
    <Heap TerminateOnError="true" />
    <ChildProcess DisallowChildProcessCreation="false" Audit="true" />
    <UserShadowStack UserShadowStack="true" UserShadowStackStrictMode="true" AuditUserShadowStack="false" />
  </AppConfig>
  <AppConfig Executable="powershell.exe">
    <DEP Enable="true" EmulateAtlThunks="true" />
    <ASLR ForceRelocateImages="true" RequireInfo="true" BottomUp="true" HighEntropy="false" />
    <StrictHandle Enable="true" />
    <SystemCalls DisableWin32kSystemCalls="false" Audit="true" />
    <ExtensionPoints DisableExtensionPoints="true" />
    <DynamicCode BlockDynamicCode="false" AllowThreadsToOptOut="false" Audit="true" />
    <ControlFlowGuard Enable="true" SuppressExports="false" StrictControlFlowGuard="true" />
    <SignedBinaries MicrosoftSignedOnly="false" AllowStoreSignedBinaries="true" Audit="true" AuditStoreSigned="true" EnforceModuleDependencySigning="false" />
    <Fonts DisableNonSystemFonts="false" AuditOnly="false" Audit="true" />
    <ImageLoad BlockRemoteImageLoads="false" AuditRemoteImageLoads="true" BlockLowLabelImageLoads="false" AuditLowLabelImageLoads="true" />
    <Payload EnableExportAddressFilter="false" AuditEnableExportAddressFilter="true" EnableExportAddressFilterPlus="false" AuditEnableExportAddressFilterPlus="true" EnableImportAddressFilter="false" AuditEnableImportAddressFilter="true" EnableRopStackPivot="false" AuditEnableRopStackPivot="true" EnableRopCallerCheck="false" AuditEnableRopCallerCheck="true" EnableRopSimExec="false" AuditEnableRopSimExec="true" />
    <SEHOP Enable="true" TelemetryOnly="false" />
    <Heap TerminateOnError="true" />
    <ChildProcess DisallowChildProcessCreation="false" Audit="true" />
    <UserShadowStack UserShadowStack="false" UserShadowStackStrictMode="true" AuditUserShadowStack="true" />
  </AppConfig>
  <AppConfig Executable="powershell_ise.exe">
    <DEP Enable="true" EmulateAtlThunks="true" />
    <ASLR ForceRelocateImages="true" RequireInfo="true" BottomUp="true" HighEntropy="false" />
    <StrictHandle Enable="true" />
    <SystemCalls DisableWin32kSystemCalls="false" Audit="true" />
    <ExtensionPoints DisableExtensionPoints="true" />
    <DynamicCode BlockDynamicCode="false" AllowThreadsToOptOut="false" Audit="true" />
    <ControlFlowGuard Enable="true" SuppressExports="false" StrictControlFlowGuard="true" />
    <SignedBinaries MicrosoftSignedOnly="false" AllowStoreSignedBinaries="true" Audit="true" AuditStoreSigned="true" EnforceModuleDependencySigning="false" />
    <Fonts DisableNonSystemFonts="false" AuditOnly="false" Audit="true" />
    <ImageLoad BlockRemoteImageLoads="false" AuditRemoteImageLoads="true" BlockLowLabelImageLoads="false" AuditLowLabelImageLoads="true" />
    <Payload EnableExportAddressFilter="false" AuditEnableExportAddressFilter="true" EnableExportAddressFilterPlus="false" AuditEnableExportAddressFilterPlus="true" EnableImportAddressFilter="false" AuditEnableImportAddressFilter="true" EnableRopStackPivot="false" AuditEnableRopStackPivot="true" EnableRopCallerCheck="false" AuditEnableRopCallerCheck="true" EnableRopSimExec="false" AuditEnableRopSimExec="true" />
    <SEHOP Enable="true" TelemetryOnly="false" />
    <Heap TerminateOnError="true" />
    <ChildProcess DisallowChildProcessCreation="false" Audit="true" />
    <UserShadowStack UserShadowStack="false" UserShadowStackStrictMode="true" AuditUserShadowStack="true" />
  </AppConfig>
  <AppConfig Executable="PresentationHost.exe">
    <DEP Enable="true" EmulateAtlThunks="false" />
    <ASLR ForceRelocateImages="true" RequireInfo="false" BottomUp="true" HighEntropy="true" />
    <SEHOP Enable="true" TelemetryOnly="false" />
    <Heap TerminateOnError="true" />
  </AppConfig>
  <AppConfig Executable="PrintDialog.exe">
    <ExtensionPoints DisableExtensionPoints="true" />
  </AppConfig>
  <AppConfig Executable="py.exe">
    <DEP Enable="true" EmulateAtlThunks="false" />
    <ASLR BottomUp="true" HighEntropy="false" />
    <StrictHandle Enable="true" />
    <SystemCalls DisableWin32kSystemCalls="false" Audit="true" />
    <ExtensionPoints DisableExtensionPoints="true" />
    <DynamicCode BlockDynamicCode="false" AllowThreadsToOptOut="false" Audit="true" />
    <SignedBinaries MicrosoftSignedOnly="false" AllowStoreSignedBinaries="true" Audit="true" AuditStoreSigned="true" EnforceModuleDependencySigning="false" />
    <Fonts DisableNonSystemFonts="false" AuditOnly="false" Audit="true" />
    <ImageLoad BlockRemoteImageLoads="false" AuditRemoteImageLoads="true" BlockLowLabelImageLoads="false" AuditLowLabelImageLoads="true" />
    <Payload EnableExportAddressFilter="false" AuditEnableExportAddressFilter="true" EnableExportAddressFilterPlus="false" AuditEnableExportAddressFilterPlus="true" EnableImportAddressFilter="false" AuditEnableImportAddressFilter="true" EnableRopStackPivot="false" AuditEnableRopStackPivot="true" EnableRopCallerCheck="false" AuditEnableRopCallerCheck="true" EnableRopSimExec="false" AuditEnableRopSimExec="true" />
    <SEHOP Enable="true" TelemetryOnly="false" />
    <Heap TerminateOnError="true" />
    <ChildProcess DisallowChildProcessCreation="true" Audit="false" />
    <UserShadowStack UserShadowStack="false" UserShadowStackStrictMode="true" AuditUserShadowStack="true" />
  </AppConfig>
  <AppConfig Executable="python.exe">
    <DEP Enable="true" EmulateAtlThunks="false" />
    <ASLR BottomUp="true" HighEntropy="false" />
    <StrictHandle Enable="true" />
    <SystemCalls DisableWin32kSystemCalls="false" Audit="true" />
    <ExtensionPoints DisableExtensionPoints="true" />
    <DynamicCode BlockDynamicCode="false" AllowThreadsToOptOut="false" Audit="true" />
    <SignedBinaries MicrosoftSignedOnly="false" AllowStoreSignedBinaries="true" Audit="true" AuditStoreSigned="true" EnforceModuleDependencySigning="false" />
    <Fonts DisableNonSystemFonts="false" AuditOnly="false" Audit="true" />
    <ImageLoad BlockRemoteImageLoads="false" AuditRemoteImageLoads="true" BlockLowLabelImageLoads="false" AuditLowLabelImageLoads="true" />
    <Payload EnableExportAddressFilter="false" AuditEnableExportAddressFilter="true" EnableExportAddressFilterPlus="false" AuditEnableExportAddressFilterPlus="true" EnableImportAddressFilter="false" AuditEnableImportAddressFilter="true" EnableRopStackPivot="false" AuditEnableRopStackPivot="true" EnableRopCallerCheck="false" AuditEnableRopCallerCheck="true" EnableRopSimExec="false" AuditEnableRopSimExec="true" />
    <SEHOP Enable="true" TelemetryOnly="false" />
    <Heap TerminateOnError="true" />
    <ChildProcess DisallowChildProcessCreation="true" Audit="false" />
    <UserShadowStack UserShadowStack="false" UserShadowStackStrictMode="true" AuditUserShadowStack="true" />
  </AppConfig>
  <AppConfig Executable="pythonw.exe">
    <DEP Enable="true" EmulateAtlThunks="false" />
    <ASLR BottomUp="true" HighEntropy="false" />
    <StrictHandle Enable="true" />
    <SystemCalls DisableWin32kSystemCalls="false" Audit="true" />
    <ExtensionPoints DisableExtensionPoints="true" />
    <DynamicCode BlockDynamicCode="false" AllowThreadsToOptOut="false" Audit="true" />
    <SignedBinaries MicrosoftSignedOnly="false" AllowStoreSignedBinaries="true" Audit="true" AuditStoreSigned="true" EnforceModuleDependencySigning="false" />
    <Fonts DisableNonSystemFonts="false" AuditOnly="false" Audit="true" />
    <ImageLoad BlockRemoteImageLoads="false" AuditRemoteImageLoads="true" BlockLowLabelImageLoads="false" AuditLowLabelImageLoads="true" />
    <Payload EnableExportAddressFilter="false" AuditEnableExportAddressFilter="true" EnableExportAddressFilterPlus="false" AuditEnableExportAddressFilterPlus="true" EnableImportAddressFilter="false" AuditEnableImportAddressFilter="true" EnableRopStackPivot="false" AuditEnableRopStackPivot="true" EnableRopCallerCheck="false" AuditEnableRopCallerCheck="true" EnableRopSimExec="false" AuditEnableRopSimExec="true" />
    <SEHOP Enable="true" TelemetryOnly="false" />
    <Heap TerminateOnError="true" />
    <ChildProcess DisallowChildProcessCreation="true" Audit="false" />
    <UserShadowStack UserShadowStack="false" UserShadowStackStrictMode="true" AuditUserShadowStack="true" />
  </AppConfig>
  <AppConfig Executable="Ratool.exe">
    <DEP Enable="true" EmulateAtlThunks="true" />
    <ASLR BottomUp="true" HighEntropy="false" />
    <StrictHandle Enable="true" />
    <SystemCalls DisableWin32kSystemCalls="true" Audit="false" />
    <ExtensionPoints DisableExtensionPoints="true" />
    <DynamicCode BlockDynamicCode="false" AllowThreadsToOptOut="false" Audit="true" />
    <SignedBinaries MicrosoftSignedOnly="false" AllowStoreSignedBinaries="true" Audit="true" AuditStoreSigned="true" EnforceModuleDependencySigning="false" />
    <Fonts DisableNonSystemFonts="false" AuditOnly="false" Audit="true" />
    <ImageLoad BlockRemoteImageLoads="false" AuditRemoteImageLoads="true" BlockLowLabelImageLoads="false" AuditLowLabelImageLoads="true" />
    <Payload EnableExportAddressFilter="false" AuditEnableExportAddressFilter="true" EnableExportAddressFilterPlus="false" AuditEnableExportAddressFilterPlus="true" EnableImportAddressFilter="false" AuditEnableImportAddressFilter="true" EnableRopStackPivot="true" AuditEnableRopStackPivot="false" EnableRopCallerCheck="false" AuditEnableRopCallerCheck="true" EnableRopSimExec="false" AuditEnableRopSimExec="true" />
    <SEHOP Enable="true" TelemetryOnly="false" />
    <Heap TerminateOnError="true" />
    <ChildProcess DisallowChildProcessCreation="false" Audit="true" />
    <UserShadowStack UserShadowStack="true" UserShadowStackStrictMode="true" AuditUserShadowStack="false" />
  </AppConfig>
  <AppConfig Executable="ReduceMemory.exe">
    <DEP Enable="true" EmulateAtlThunks="false" />
    <ASLR BottomUp="true" HighEntropy="false" />
    <StrictHandle Enable="true" />
    <SystemCalls DisableWin32kSystemCalls="true" Audit="false" />
    <ExtensionPoints DisableExtensionPoints="true" />
    <DynamicCode BlockDynamicCode="false" AllowThreadsToOptOut="false" Audit="true" />
    <SignedBinaries MicrosoftSignedOnly="false" AllowStoreSignedBinaries="true" Audit="true" AuditStoreSigned="true" EnforceModuleDependencySigning="false" />
    <Fonts DisableNonSystemFonts="false" AuditOnly="false" Audit="true" />
    <ImageLoad BlockRemoteImageLoads="false" AuditRemoteImageLoads="true" BlockLowLabelImageLoads="false" AuditLowLabelImageLoads="true" />
    <Payload EnableExportAddressFilter="false" AuditEnableExportAddressFilter="true" EnableExportAddressFilterPlus="false" AuditEnableExportAddressFilterPlus="true" EnableImportAddressFilter="false" AuditEnableImportAddressFilter="true" EnableRopStackPivot="true" AuditEnableRopStackPivot="false" EnableRopCallerCheck="false" AuditEnableRopCallerCheck="true" EnableRopSimExec="false" AuditEnableRopSimExec="true" />
    <SEHOP Enable="true" TelemetryOnly="false" />
    <Heap TerminateOnError="true" />
    <ChildProcess DisallowChildProcessCreation="true" Audit="false" />
    <UserShadowStack UserShadowStack="true" UserShadowStackStrictMode="true" AuditUserShadowStack="false" />
  </AppConfig>
  <AppConfig Executable="ResetCDROM.exe">
    <DEP Enable="true" EmulateAtlThunks="true" />
    <ASLR ForceRelocateImages="true" RequireInfo="true" BottomUp="true" HighEntropy="false" />
    <StrictHandle Enable="true" />
    <SystemCalls DisableWin32kSystemCalls="false" Audit="true" />
    <ExtensionPoints DisableExtensionPoints="true" />
    <DynamicCode BlockDynamicCode="false" AllowThreadsToOptOut="false" Audit="true" />
    <ControlFlowGuard Enable="true" SuppressExports="false" StrictControlFlowGuard="true" />
    <SignedBinaries MicrosoftSignedOnly="false" AllowStoreSignedBinaries="true" Audit="true" AuditStoreSigned="true" EnforceModuleDependencySigning="false" />
    <Fonts DisableNonSystemFonts="false" AuditOnly="false" Audit="true" />
    <ImageLoad BlockRemoteImageLoads="false" AuditRemoteImageLoads="true" BlockLowLabelImageLoads="false" AuditLowLabelImageLoads="true" />
    <Payload EnableExportAddressFilter="false" AuditEnableExportAddressFilter="true" EnableExportAddressFilterPlus="false" AuditEnableExportAddressFilterPlus="true" EnableImportAddressFilter="false" AuditEnableImportAddressFilter="true" EnableRopStackPivot="false" AuditEnableRopStackPivot="true" EnableRopCallerCheck="false" AuditEnableRopCallerCheck="true" EnableRopSimExec="false" AuditEnableRopSimExec="true" />
    <SEHOP Enable="true" TelemetryOnly="false" />
    <Heap TerminateOnError="true" />
    <ChildProcess DisallowChildProcessCreation="false" Audit="true" />
    <UserShadowStack UserShadowStack="false" UserShadowStackStrictMode="true" AuditUserShadowStack="true" />
  </AppConfig>
  <AppConfig Executable="ReShadeFXC32.exe">
    <DEP Enable="true" EmulateAtlThunks="true" />
    <ASLR ForceRelocateImages="true" RequireInfo="true" BottomUp="true" HighEntropy="false" />
    <StrictHandle Enable="true" />
    <SystemCalls DisableWin32kSystemCalls="false" Audit="true" />
    <ExtensionPoints DisableExtensionPoints="true" />
    <DynamicCode BlockDynamicCode="false" AllowThreadsToOptOut="false" Audit="true" />
    <ControlFlowGuard Enable="true" SuppressExports="false" StrictControlFlowGuard="true" />
    <SignedBinaries MicrosoftSignedOnly="false" AllowStoreSignedBinaries="true" Audit="true" AuditStoreSigned="true" EnforceModuleDependencySigning="false" />
    <Fonts DisableNonSystemFonts="false" AuditOnly="false" Audit="true" />
    <ImageLoad BlockRemoteImageLoads="false" AuditRemoteImageLoads="true" BlockLowLabelImageLoads="false" AuditLowLabelImageLoads="true" />
    <Payload EnableExportAddressFilter="false" AuditEnableExportAddressFilter="true" EnableExportAddressFilterPlus="false" AuditEnableExportAddressFilterPlus="true" EnableImportAddressFilter="false" AuditEnableImportAddressFilter="true" EnableRopStackPivot="false" AuditEnableRopStackPivot="true" EnableRopCallerCheck="false" AuditEnableRopCallerCheck="true" EnableRopSimExec="false" AuditEnableRopSimExec="true" />
    <SEHOP Enable="true" TelemetryOnly="false" />
    <Heap TerminateOnError="true" />
    <ChildProcess DisallowChildProcessCreation="false" Audit="true" />
    <UserShadowStack UserShadowStack="false" UserShadowStackStrictMode="true" AuditUserShadowStack="true" />
  </AppConfig>
  <AppConfig Executable="ReShadeFXC64.exe">
    <DEP Enable="true" EmulateAtlThunks="true" />
    <ASLR ForceRelocateImages="true" RequireInfo="true" BottomUp="true" HighEntropy="false" />
    <StrictHandle Enable="true" />
    <SystemCalls DisableWin32kSystemCalls="false" Audit="true" />
    <ExtensionPoints DisableExtensionPoints="true" />
    <DynamicCode BlockDynamicCode="false" AllowThreadsToOptOut="false" Audit="true" />
    <ControlFlowGuard Enable="true" SuppressExports="false" StrictControlFlowGuard="true" />
    <SignedBinaries MicrosoftSignedOnly="true" AllowStoreSignedBinaries="true" Audit="false" AuditStoreSigned="false" EnforceModuleDependencySigning="false" />
    <Fonts DisableNonSystemFonts="false" AuditOnly="false" Audit="true" />
    <ImageLoad BlockRemoteImageLoads="false" AuditRemoteImageLoads="true" BlockLowLabelImageLoads="false" AuditLowLabelImageLoads="true" />
    <Payload EnableExportAddressFilter="false" AuditEnableExportAddressFilter="true" EnableExportAddressFilterPlus="false" AuditEnableExportAddressFilterPlus="true" EnableImportAddressFilter="false" AuditEnableImportAddressFilter="true" EnableRopStackPivot="false" AuditEnableRopStackPivot="true" EnableRopCallerCheck="false" AuditEnableRopCallerCheck="true" EnableRopSimExec="false" AuditEnableRopSimExec="true" />
    <SEHOP Enable="true" TelemetryOnly="false" />
    <Heap TerminateOnError="true" />
    <ChildProcess DisallowChildProcessCreation="false" Audit="true" />
    <UserShadowStack UserShadowStack="false" UserShadowStackStrictMode="true" AuditUserShadowStack="true" />
  </AppConfig>
  <AppConfig Executable="RevoCmd.exe">
    <DEP Enable="true" EmulateAtlThunks="true" />
    <ASLR BottomUp="true" HighEntropy="false" />
    <StrictHandle Enable="true" />
    <SystemCalls DisableWin32kSystemCalls="true" Audit="false" />
    <ExtensionPoints DisableExtensionPoints="true" />
    <DynamicCode BlockDynamicCode="false" AllowThreadsToOptOut="false" Audit="true" />
    <SignedBinaries MicrosoftSignedOnly="false" AllowStoreSignedBinaries="true" Audit="true" AuditStoreSigned="true" EnforceModuleDependencySigning="false" />
    <Fonts DisableNonSystemFonts="false" AuditOnly="false" Audit="true" />
    <ImageLoad BlockRemoteImageLoads="false" AuditRemoteImageLoads="true" BlockLowLabelImageLoads="false" AuditLowLabelImageLoads="true" />
    <Payload EnableExportAddressFilter="false" AuditEnableExportAddressFilter="true" EnableExportAddressFilterPlus="false" AuditEnableExportAddressFilterPlus="true" EnableImportAddressFilter="false" AuditEnableImportAddressFilter="true" EnableRopStackPivot="false" AuditEnableRopStackPivot="true" EnableRopCallerCheck="false" AuditEnableRopCallerCheck="true" EnableRopSimExec="false" AuditEnableRopSimExec="true" />
    <SEHOP Enable="true" TelemetryOnly="false" />
    <Heap TerminateOnError="true" />
    <ChildProcess DisallowChildProcessCreation="false" Audit="true" />
    <UserShadowStack UserShadowStack="false" UserShadowStackStrictMode="true" AuditUserShadowStack="true" />
  </AppConfig>
  <AppConfig Executable="RevoUninPro.exe">
    <DEP Enable="true" EmulateAtlThunks="true" />
    <ASLR BottomUp="true" HighEntropy="true" />
    <StrictHandle Enable="true" />
    <SystemCalls DisableWin32kSystemCalls="true" Audit="false" />
    <ExtensionPoints DisableExtensionPoints="true" />
    <DynamicCode BlockDynamicCode="true" AllowThreadsToOptOut="true" Audit="false" />
    <SignedBinaries MicrosoftSignedOnly="true" AllowStoreSignedBinaries="true" Audit="false" AuditStoreSigned="false" EnforceModuleDependencySigning="true" />
    <Fonts DisableNonSystemFonts="true" AuditOnly="false" Audit="false" />
    <ImageLoad BlockRemoteImageLoads="true" AuditRemoteImageLoads="false" BlockLowLabelImageLoads="true" AuditLowLabelImageLoads="false" />
    <Payload EnableExportAddressFilter="true" AuditEnableExportAddressFilter="false" EnableExportAddressFilterPlus="true" AuditEnableExportAddressFilterPlus="false" EnableImportAddressFilter="true" AuditEnableImportAddressFilter="false" EnableRopStackPivot="true" AuditEnableRopStackPivot="false" EnableRopCallerCheck="true" AuditEnableRopCallerCheck="false" EnableRopSimExec="true" AuditEnableRopSimExec="false" />
    <SEHOP Enable="true" TelemetryOnly="false" />
    <Heap TerminateOnError="true" />
    <ChildProcess DisallowChildProcessCreation="true" Audit="false" />
    <UserShadowStack UserShadowStack="true" UserShadowStackStrictMode="true" AuditUserShadowStack="false" />
  </AppConfig>
  <AppConfig Executable="RevoUninProSetup321.exe">
    <DEP Enable="true" EmulateAtlThunks="false" />
    <ASLR BottomUp="true" HighEntropy="false" />
    <StrictHandle Enable="true" />
    <SystemCalls DisableWin32kSystemCalls="true" Audit="false" />
    <ExtensionPoints DisableExtensionPoints="true" />
    <DynamicCode BlockDynamicCode="false" AllowThreadsToOptOut="false" Audit="true" />
    <SignedBinaries MicrosoftSignedOnly="false" AllowStoreSignedBinaries="true" Audit="true" AuditStoreSigned="true" EnforceModuleDependencySigning="false" />
    <Fonts DisableNonSystemFonts="false" AuditOnly="false" Audit="true" />
    <ImageLoad BlockRemoteImageLoads="false" AuditRemoteImageLoads="true" BlockLowLabelImageLoads="false" AuditLowLabelImageLoads="true" />
    <Payload EnableExportAddressFilter="false" AuditEnableExportAddressFilter="true" EnableExportAddressFilterPlus="false" AuditEnableExportAddressFilterPlus="true" EnableImportAddressFilter="false" AuditEnableImportAddressFilter="true" EnableRopStackPivot="true" AuditEnableRopStackPivot="false" EnableRopCallerCheck="false" AuditEnableRopCallerCheck="true" EnableRopSimExec="false" AuditEnableRopSimExec="true" />
    <SEHOP Enable="true" TelemetryOnly="false" />
    <Heap TerminateOnError="true" />
    <ChildProcess DisallowChildProcessCreation="false" Audit="true" />
    <UserShadowStack UserShadowStack="true" UserShadowStackStrictMode="true" AuditUserShadowStack="false" />
  </AppConfig>
  <AppConfig Executable="RunBlock.exe">
    <DEP Enable="true" EmulateAtlThunks="true" />
    <ASLR BottomUp="true" HighEntropy="true" />
    <StrictHandle Enable="true" />
    <SystemCalls DisableWin32kSystemCalls="false" Audit="true" />
    <ExtensionPoints DisableExtensionPoints="false" />
    <DynamicCode BlockDynamicCode="true" AllowThreadsToOptOut="true" Audit="false" />
    <SignedBinaries MicrosoftSignedOnly="true" AllowStoreSignedBinaries="true" Audit="false" AuditStoreSigned="false" EnforceModuleDependencySigning="true" />
    <Fonts DisableNonSystemFonts="true" AuditOnly="false" Audit="false" />
    <ImageLoad BlockRemoteImageLoads="true" AuditRemoteImageLoads="false" BlockLowLabelImageLoads="true" AuditLowLabelImageLoads="false" />
    <Payload EnableExportAddressFilter="true" AuditEnableExportAddressFilter="false" EnableExportAddressFilterPlus="true" AuditEnableExportAddressFilterPlus="false" EnableImportAddressFilter="true" AuditEnableImportAddressFilter="false" EnableRopStackPivot="true" AuditEnableRopStackPivot="false" EnableRopCallerCheck="true" AuditEnableRopCallerCheck="false" EnableRopSimExec="true" AuditEnableRopSimExec="false" />
    <SEHOP Enable="true" TelemetryOnly="false" />
    <Heap TerminateOnError="true" />
    <ChildProcess DisallowChildProcessCreation="false" Audit="true" />
    <UserShadowStack UserShadowStack="true" UserShadowStackStrictMode="true" AuditUserShadowStack="false" />
  </AppConfig>
  <AppConfig Executable="runtimebroker.exe">
    <ExtensionPoints DisableExtensionPoints="true" />
  </AppConfig>
  <AppConfig Executable="ruplp.exe">
    <ASLR ForceRelocateImages="true" RequireInfo="true" BottomUp="true" HighEntropy="false" />
    <StrictHandle Enable="false" />
    <DynamicCode BlockDynamicCode="false" AllowThreadsToOptOut="false" Audit="true" />
    <SignedBinaries MicrosoftSignedOnly="false" AllowStoreSignedBinaries="true" Audit="true" AuditStoreSigned="true" EnforceModuleDependencySigning="false" />
    <Fonts DisableNonSystemFonts="false" AuditOnly="false" Audit="true" />
    <ImageLoad BlockRemoteImageLoads="false" AuditRemoteImageLoads="true" BlockLowLabelImageLoads="false" AuditLowLabelImageLoads="true" />
    <Payload EnableExportAddressFilter="false" AuditEnableExportAddressFilter="true" EnableExportAddressFilterPlus="false" AuditEnableExportAddressFilterPlus="true" EnableImportAddressFilter="false" AuditEnableImportAddressFilter="true" EnableRopStackPivot="false" AuditEnableRopStackPivot="true" EnableRopCallerCheck="false" AuditEnableRopCallerCheck="true" EnableRopSimExec="false" AuditEnableRopSimExec="true" />
    <SEHOP Enable="true" TelemetryOnly="false" />
    <Heap TerminateOnError="true" />
    <ChildProcess DisallowChildProcessCreation="false" Audit="true" />
    <UserShadowStack UserShadowStack="false" UserShadowStackStrictMode="true" AuditUserShadowStack="true" />
  </AppConfig>
  <AppConfig Executable="setup.exe">
    <ASLR ForceRelocateImages="true" RequireInfo="true" BottomUp="true" HighEntropy="false" />
    <StrictHandle Enable="true" />
    <DynamicCode BlockDynamicCode="false" AllowThreadsToOptOut="false" Audit="true" />
    <SignedBinaries MicrosoftSignedOnly="false" AllowStoreSignedBinaries="true" Audit="true" AuditStoreSigned="true" EnforceModuleDependencySigning="false" />
    <Fonts DisableNonSystemFonts="false" AuditOnly="false" Audit="true" />
    <ImageLoad BlockRemoteImageLoads="false" AuditRemoteImageLoads="true" BlockLowLabelImageLoads="false" AuditLowLabelImageLoads="true" />
    <Payload EnableExportAddressFilter="false" AuditEnableExportAddressFilter="true" EnableExportAddressFilterPlus="false" AuditEnableExportAddressFilterPlus="true" EnableImportAddressFilter="false" AuditEnableImportAddressFilter="true" EnableRopStackPivot="true" AuditEnableRopStackPivot="false" EnableRopCallerCheck="false" AuditEnableRopCallerCheck="true" EnableRopSimExec="false" AuditEnableRopSimExec="true" />
    <SEHOP Enable="true" TelemetryOnly="false" />
    <Heap TerminateOnError="true" />
    <ChildProcess DisallowChildProcessCreation="false" Audit="true" />
    <UserShadowStack UserShadowStack="true" UserShadowStackStrictMode="true" AuditUserShadowStack="false" />
  </AppConfig>
  <AppConfig Executable="ShowTip.exe">
    <DEP Enable="true" EmulateAtlThunks="true" />
    <ASLR ForceRelocateImages="true" RequireInfo="true" BottomUp="true" HighEntropy="false" />
    <StrictHandle Enable="true" />
    <SystemCalls DisableWin32kSystemCalls="false" Audit="true" />
    <ExtensionPoints DisableExtensionPoints="true" />
    <DynamicCode BlockDynamicCode="false" AllowThreadsToOptOut="false" Audit="true" />
    <ControlFlowGuard Enable="true" SuppressExports="false" StrictControlFlowGuard="true" />
    <SignedBinaries MicrosoftSignedOnly="false" AllowStoreSignedBinaries="true" Audit="true" AuditStoreSigned="true" EnforceModuleDependencySigning="false" />
    <Fonts DisableNonSystemFonts="false" AuditOnly="false" Audit="true" />
    <ImageLoad BlockRemoteImageLoads="false" AuditRemoteImageLoads="true" BlockLowLabelImageLoads="false" AuditLowLabelImageLoads="true" />
    <Payload EnableExportAddressFilter="false" AuditEnableExportAddressFilter="true" EnableExportAddressFilterPlus="false" AuditEnableExportAddressFilterPlus="true" EnableImportAddressFilter="false" AuditEnableImportAddressFilter="true" EnableRopStackPivot="false" AuditEnableRopStackPivot="true" EnableRopCallerCheck="false" AuditEnableRopCallerCheck="true" EnableRopSimExec="false" AuditEnableRopSimExec="true" />
    <SEHOP Enable="true" TelemetryOnly="false" />
    <Heap TerminateOnError="true" />
    <ChildProcess DisallowChildProcessCreation="false" Audit="true" />
    <UserShadowStack UserShadowStack="false" UserShadowStackStrictMode="true" AuditUserShadowStack="true" />
  </AppConfig>
  <AppConfig Executable="SphericalEquirect32.exe">
    <DEP Enable="true" EmulateAtlThunks="true" />
    <ASLR ForceRelocateImages="true" RequireInfo="true" BottomUp="true" HighEntropy="false" />
    <StrictHandle Enable="true" />
    <SystemCalls DisableWin32kSystemCalls="false" Audit="true" />
    <ExtensionPoints DisableExtensionPoints="true" />
    <DynamicCode BlockDynamicCode="false" AllowThreadsToOptOut="false" Audit="true" />
    <ControlFlowGuard Enable="true" SuppressExports="false" StrictControlFlowGuard="true" />
    <SignedBinaries MicrosoftSignedOnly="false" AllowStoreSignedBinaries="true" Audit="true" AuditStoreSigned="true" EnforceModuleDependencySigning="false" />
    <Fonts DisableNonSystemFonts="false" AuditOnly="false" Audit="true" />
    <ImageLoad BlockRemoteImageLoads="false" AuditRemoteImageLoads="true" BlockLowLabelImageLoads="false" AuditLowLabelImageLoads="true" />
    <Payload EnableExportAddressFilter="false" AuditEnableExportAddressFilter="true" EnableExportAddressFilterPlus="false" AuditEnableExportAddressFilterPlus="true" EnableImportAddressFilter="false" AuditEnableImportAddressFilter="true" EnableRopStackPivot="false" AuditEnableRopStackPivot="true" EnableRopCallerCheck="false" AuditEnableRopCallerCheck="true" EnableRopSimExec="false" AuditEnableRopSimExec="true" />
    <SEHOP Enable="true" TelemetryOnly="false" />
    <Heap TerminateOnError="true" />
    <ChildProcess DisallowChildProcessCreation="false" Audit="true" />
    <UserShadowStack UserShadowStack="false" UserShadowStackStrictMode="true" AuditUserShadowStack="true" />
  </AppConfig>
  <AppConfig Executable="SphericalEquirect64.exe">
    <DEP Enable="true" EmulateAtlThunks="true" />
    <ASLR ForceRelocateImages="true" RequireInfo="true" BottomUp="true" HighEntropy="false" />
    <StrictHandle Enable="true" />
    <SystemCalls DisableWin32kSystemCalls="false" Audit="true" />
    <ExtensionPoints DisableExtensionPoints="true" />
    <DynamicCode BlockDynamicCode="false" AllowThreadsToOptOut="false" Audit="true" />
    <ControlFlowGuard Enable="true" SuppressExports="false" StrictControlFlowGuard="true" />
    <SignedBinaries MicrosoftSignedOnly="false" AllowStoreSignedBinaries="true" Audit="true" AuditStoreSigned="true" EnforceModuleDependencySigning="false" />
    <Fonts DisableNonSystemFonts="false" AuditOnly="false" Audit="true" />
    <ImageLoad BlockRemoteImageLoads="false" AuditRemoteImageLoads="true" BlockLowLabelImageLoads="false" AuditLowLabelImageLoads="true" />
    <Payload EnableExportAddressFilter="false" AuditEnableExportAddressFilter="true" EnableExportAddressFilterPlus="false" AuditEnableExportAddressFilterPlus="true" EnableImportAddressFilter="false" AuditEnableImportAddressFilter="true" EnableRopStackPivot="false" AuditEnableRopStackPivot="true" EnableRopCallerCheck="false" AuditEnableRopCallerCheck="true" EnableRopSimExec="false" AuditEnableRopSimExec="true" />
    <SEHOP Enable="true" TelemetryOnly="false" />
    <Heap TerminateOnError="true" />
    <ChildProcess DisallowChildProcessCreation="false" Audit="true" />
    <UserShadowStack UserShadowStack="false" UserShadowStackStrictMode="true" AuditUserShadowStack="true" />
  </AppConfig>
  <AppConfig Executable="SystemSettings.exe">
    <ExtensionPoints DisableExtensionPoints="true" />
  </AppConfig>
  <AppConfig Executable="tapctl.exe">
    <Payload EnableRopStackPivot="true" AuditEnableRopStackPivot="false" />
    <Heap TerminateOnError="true" />
    <UserShadowStack UserShadowStack="true" UserShadowStackStrictMode="true" AuditUserShadowStack="false" />
  </AppConfig>
  <AppConfig Executable="transmission-create.exe">
    <DEP Enable="true" EmulateAtlThunks="true" />
    <ASLR BottomUp="true" HighEntropy="false" />
    <StrictHandle Enable="true" />
    <SystemCalls DisableWin32kSystemCalls="false" Audit="true" />
    <ExtensionPoints DisableExtensionPoints="true" />
    <DynamicCode BlockDynamicCode="false" AllowThreadsToOptOut="false" Audit="true" />
    <SignedBinaries MicrosoftSignedOnly="false" AllowStoreSignedBinaries="true" Audit="true" AuditStoreSigned="true" EnforceModuleDependencySigning="true" />
    <Fonts DisableNonSystemFonts="false" AuditOnly="false" Audit="true" />
    <ImageLoad BlockRemoteImageLoads="false" AuditRemoteImageLoads="true" BlockLowLabelImageLoads="false" AuditLowLabelImageLoads="true" />
    <Payload EnableExportAddressFilter="false" AuditEnableExportAddressFilter="true" EnableExportAddressFilterPlus="false" AuditEnableExportAddressFilterPlus="true" EnableImportAddressFilter="false" AuditEnableImportAddressFilter="true" EnableRopStackPivot="true" AuditEnableRopStackPivot="false" EnableRopCallerCheck="false" EnableRopSimExec="false" AuditEnableRopSimExec="true" />
    <SEHOP Enable="true" TelemetryOnly="false" />
    <Heap TerminateOnError="true" />
    <ChildProcess DisallowChildProcessCreation="false" Audit="true" />
    <UserShadowStack UserShadowStack="false" UserShadowStackStrictMode="true" AuditUserShadowStack="true" />
  </AppConfig>
  <AppConfig Executable="transmission-daemon.exe">
    <DEP Enable="true" EmulateAtlThunks="true" />
    <ASLR BottomUp="true" HighEntropy="true" />
    <StrictHandle Enable="true" />
    <SystemCalls DisableWin32kSystemCalls="true" Audit="false" />
    <ExtensionPoints DisableExtensionPoints="true" />
    <DynamicCode BlockDynamicCode="false" AllowThreadsToOptOut="false" Audit="true" />
    <SignedBinaries MicrosoftSignedOnly="false" AllowStoreSignedBinaries="true" Audit="true" AuditStoreSigned="true" EnforceModuleDependencySigning="false" />
    <Fonts DisableNonSystemFonts="false" AuditOnly="false" Audit="true" />
    <ImageLoad BlockRemoteImageLoads="false" AuditRemoteImageLoads="true" BlockLowLabelImageLoads="false" AuditLowLabelImageLoads="true" />
    <Payload EnableExportAddressFilter="true" AuditEnableExportAddressFilter="false" EnableExportAddressFilterPlus="true" AuditEnableExportAddressFilterPlus="false" EnableImportAddressFilter="true" AuditEnableImportAddressFilter="false" EnableRopStackPivot="true" AuditEnableRopStackPivot="false" EnableRopCallerCheck="true" AuditEnableRopCallerCheck="false" EnableRopSimExec="true" AuditEnableRopSimExec="false" />
    <SEHOP Enable="true" TelemetryOnly="false" />
    <Heap TerminateOnError="true" />
    <ChildProcess DisallowChildProcessCreation="true" Audit="false" />
    <UserShadowStack UserShadowStack="true" UserShadowStackStrictMode="true" AuditUserShadowStack="false" />
  </AppConfig>
  <AppConfig Executable="transmission-edit.exe">
    <DEP Enable="true" EmulateAtlThunks="false" />
    <ASLR BottomUp="true" HighEntropy="true" />
    <StrictHandle Enable="true" />
    <SystemCalls DisableWin32kSystemCalls="true" Audit="false" />
    <ExtensionPoints DisableExtensionPoints="true" />
    <DynamicCode BlockDynamicCode="false" AllowThreadsToOptOut="false" Audit="true" />
    <SignedBinaries MicrosoftSignedOnly="false" AllowStoreSignedBinaries="true" Audit="true" AuditStoreSigned="true" EnforceModuleDependencySigning="true" />
    <Fonts DisableNonSystemFonts="false" AuditOnly="false" Audit="true" />
    <ImageLoad BlockRemoteImageLoads="false" AuditRemoteImageLoads="true" BlockLowLabelImageLoads="false" AuditLowLabelImageLoads="true" />
    <Payload EnableExportAddressFilter="true" AuditEnableExportAddressFilter="false" EnableExportAddressFilterPlus="true" AuditEnableExportAddressFilterPlus="false" EnableImportAddressFilter="true" AuditEnableImportAddressFilter="false" EnableRopStackPivot="true" AuditEnableRopStackPivot="false" EnableRopCallerCheck="true" AuditEnableRopCallerCheck="false" EnableRopSimExec="true" AuditEnableRopSimExec="false" />
    <SEHOP Enable="true" TelemetryOnly="false" />
    <Heap TerminateOnError="true" />
    <ChildProcess DisallowChildProcessCreation="true" Audit="false" />
    <UserShadowStack UserShadowStack="true" UserShadowStackStrictMode="true" AuditUserShadowStack="false" />
  </AppConfig>
  <AppConfig Executable="transmission-qt.exe">
    <DEP Enable="true" EmulateAtlThunks="true" />
    <ASLR BottomUp="true" HighEntropy="true" />
    <StrictHandle Enable="true" />
    <SystemCalls DisableWin32kSystemCalls="true" Audit="false" />
    <ExtensionPoints DisableExtensionPoints="true" />
    <DynamicCode BlockDynamicCode="false" AllowThreadsToOptOut="false" Audit="true" />
    <SignedBinaries MicrosoftSignedOnly="true" AllowStoreSignedBinaries="true" Audit="false" AuditStoreSigned="false" EnforceModuleDependencySigning="true" />
    <Fonts DisableNonSystemFonts="false" AuditOnly="false" Audit="true" />
    <ImageLoad BlockRemoteImageLoads="false" AuditRemoteImageLoads="true" BlockLowLabelImageLoads="false" AuditLowLabelImageLoads="true" />
    <Payload EnableExportAddressFilter="true" AuditEnableExportAddressFilter="false" EnableExportAddressFilterPlus="true" AuditEnableExportAddressFilterPlus="false" EnableImportAddressFilter="true" AuditEnableImportAddressFilter="false" EnableRopStackPivot="true" AuditEnableRopStackPivot="false" EnableRopCallerCheck="true" AuditEnableRopCallerCheck="false" EnableRopSimExec="true" AuditEnableRopSimExec="false" />
    <SEHOP Enable="true" TelemetryOnly="false" />
    <Heap TerminateOnError="true" />
    <ChildProcess DisallowChildProcessCreation="false" Audit="true" />
    <UserShadowStack UserShadowStack="true" UserShadowStackStrictMode="true" AuditUserShadowStack="false" />
  </AppConfig>
  <AppConfig Executable="transmission-remote.exe">
    <DEP Enable="true" EmulateAtlThunks="false" />
    <ASLR ForceRelocateImages="true" RequireInfo="false" BottomUp="true" HighEntropy="true" />
    <StrictHandle Enable="true" />
    <SystemCalls DisableWin32kSystemCalls="true" Audit="false" />
    <ExtensionPoints DisableExtensionPoints="false" />
    <DynamicCode BlockDynamicCode="false" AllowThreadsToOptOut="false" Audit="true" />
    <ControlFlowGuard Enable="true" SuppressExports="false" />
    <SignedBinaries MicrosoftSignedOnly="true" AllowStoreSignedBinaries="true" Audit="false" AuditStoreSigned="false" EnforceModuleDependencySigning="true" />
    <Fonts DisableNonSystemFonts="false" AuditOnly="false" Audit="true" />
    <ImageLoad BlockRemoteImageLoads="false" AuditRemoteImageLoads="true" BlockLowLabelImageLoads="false" AuditLowLabelImageLoads="true" />
    <Payload EnableExportAddressFilter="true" AuditEnableExportAddressFilter="false" EnableExportAddressFilterPlus="true" AuditEnableExportAddressFilterPlus="false" EnableImportAddressFilter="true" AuditEnableImportAddressFilter="false" EnableRopStackPivot="true" AuditEnableRopStackPivot="false" EnableRopCallerCheck="true" AuditEnableRopCallerCheck="false" EnableRopSimExec="true" AuditEnableRopSimExec="false" />
    <SEHOP Enable="true" TelemetryOnly="false" />
    <Heap TerminateOnError="true" />
    <ChildProcess DisallowChildProcessCreation="false" Audit="true" />
    <UserShadowStack UserShadowStack="true" UserShadowStackStrictMode="true" AuditUserShadowStack="false" />
  </AppConfig>
  <AppConfig Executable="transmission-show.exe">
    <DEP Enable="true" EmulateAtlThunks="true" />
    <ASLR BottomUp="true" HighEntropy="true" />
    <StrictHandle Enable="true" />
    <SystemCalls DisableWin32kSystemCalls="false" Audit="true" />
    <ExtensionPoints DisableExtensionPoints="true" />
    <DynamicCode BlockDynamicCode="false" AllowThreadsToOptOut="false" Audit="true" />
    <SignedBinaries MicrosoftSignedOnly="true" AllowStoreSignedBinaries="true" Audit="false" AuditStoreSigned="false" EnforceModuleDependencySigning="true" />
    <Fonts DisableNonSystemFonts="false" AuditOnly="false" Audit="true" />
    <ImageLoad BlockRemoteImageLoads="false" AuditRemoteImageLoads="true" BlockLowLabelImageLoads="false" AuditLowLabelImageLoads="true" />
    <Payload EnableExportAddressFilter="true" AuditEnableExportAddressFilter="false" EnableExportAddressFilterPlus="true" AuditEnableExportAddressFilterPlus="false" EnableImportAddressFilter="true" AuditEnableImportAddressFilter="false" EnableRopStackPivot="true" AuditEnableRopStackPivot="false" EnableRopCallerCheck="true" AuditEnableRopCallerCheck="false" EnableRopSimExec="true" AuditEnableRopSimExec="false" />
    <SEHOP Enable="true" TelemetryOnly="false" />
    <Heap TerminateOnError="true" />
    <ChildProcess DisallowChildProcessCreation="true" Audit="false" />
    <UserShadowStack UserShadowStack="true" UserShadowStackStrictMode="true" AuditUserShadowStack="false" />
  </AppConfig>
  <AppConfig Executable="unins000.exe">
    <DEP Enable="true" EmulateAtlThunks="false" />
    <ASLR BottomUp="true" HighEntropy="false" />
    <StrictHandle Enable="true" />
    <SystemCalls DisableWin32kSystemCalls="false" Audit="true" />
    <ExtensionPoints DisableExtensionPoints="false" />
    <DynamicCode BlockDynamicCode="false" AllowThreadsToOptOut="false" Audit="true" />
    <SignedBinaries MicrosoftSignedOnly="true" AllowStoreSignedBinaries="true" Audit="false" AuditStoreSigned="false" EnforceModuleDependencySigning="false" />
    <Fonts DisableNonSystemFonts="true" AuditOnly="false" Audit="false" />
    <ImageLoad BlockRemoteImageLoads="false" AuditRemoteImageLoads="true" BlockLowLabelImageLoads="false" AuditLowLabelImageLoads="true" />
    <Payload EnableExportAddressFilter="false" AuditEnableExportAddressFilter="true" EnableExportAddressFilterPlus="false" AuditEnableExportAddressFilterPlus="true" EnableImportAddressFilter="false" AuditEnableImportAddressFilter="true" EnableRopStackPivot="false" AuditEnableRopStackPivot="true" EnableRopCallerCheck="false" AuditEnableRopCallerCheck="true" EnableRopSimExec="false" AuditEnableRopSimExec="true" />
    <SEHOP Enable="true" TelemetryOnly="false" />
    <Heap TerminateOnError="true" />
    <ChildProcess DisallowChildProcessCreation="false" Audit="true" />
    <UserShadowStack UserShadowStack="true" UserShadowStackStrictMode="true" AuditUserShadowStack="false" />
  </AppConfig>
  <AppConfig Executable="uninst.exe">
    <DEP Enable="true" EmulateAtlThunks="true" />
    <ASLR ForceRelocateImages="true" RequireInfo="false" BottomUp="true" HighEntropy="true" />
    <StrictHandle Enable="true" />
    <SystemCalls DisableWin32kSystemCalls="true" Audit="false" />
    <ExtensionPoints DisableExtensionPoints="true" />
    <DynamicCode BlockDynamicCode="true" AllowThreadsToOptOut="true" Audit="false" />
    <ControlFlowGuard Enable="true" SuppressExports="false" StrictControlFlowGuard="true" />
    <SignedBinaries MicrosoftSignedOnly="true" AllowStoreSignedBinaries="true" Audit="false" AuditStoreSigned="false" EnforceModuleDependencySigning="true" />
    <Fonts DisableNonSystemFonts="true" AuditOnly="false" Audit="false" />
    <ImageLoad BlockRemoteImageLoads="true" AuditRemoteImageLoads="false" BlockLowLabelImageLoads="true" AuditLowLabelImageLoads="false" />
    <Payload EnableExportAddressFilter="true" AuditEnableExportAddressFilter="false" EnableExportAddressFilterPlus="true" AuditEnableExportAddressFilterPlus="false" EnableImportAddressFilter="true" AuditEnableImportAddressFilter="false" EnableRopStackPivot="true" AuditEnableRopStackPivot="false" EnableRopCallerCheck="true" AuditEnableRopCallerCheck="false" EnableRopSimExec="true" AuditEnableRopSimExec="false" />
    <SEHOP Enable="true" TelemetryOnly="false" />
    <Heap TerminateOnError="true" />
    <ChildProcess DisallowChildProcessCreation="true" Audit="false" />
    <UserShadowStack UserShadowStack="true" UserShadowStackStrictMode="true" AuditUserShadowStack="false" />
  </AppConfig>
  <AppConfig Executable="Uninstall.exe">
    <DEP Enable="true" EmulateAtlThunks="true" />
    <ASLR ForceRelocateImages="false" RequireInfo="false" BottomUp="true" HighEntropy="false" />
    <StrictHandle Enable="true" />
    <SystemCalls DisableWin32kSystemCalls="false" Audit="true" />
    <ExtensionPoints DisableExtensionPoints="true" />
    <DynamicCode BlockDynamicCode="false" AllowThreadsToOptOut="false" Audit="true" />
    <SignedBinaries MicrosoftSignedOnly="false" AllowStoreSignedBinaries="true" Audit="true" AuditStoreSigned="true" EnforceModuleDependencySigning="false" />
    <Fonts DisableNonSystemFonts="false" AuditOnly="false" Audit="true" />
    <ImageLoad BlockRemoteImageLoads="false" AuditRemoteImageLoads="true" BlockLowLabelImageLoads="false" AuditLowLabelImageLoads="true" />
    <Payload EnableExportAddressFilter="false" AuditEnableExportAddressFilter="true" EnableExportAddressFilterPlus="false" AuditEnableExportAddressFilterPlus="true" EnableImportAddressFilter="false" AuditEnableImportAddressFilter="true" EnableRopStackPivot="true" AuditEnableRopStackPivot="false" EnableRopCallerCheck="false" AuditEnableRopCallerCheck="true" EnableRopSimExec="true" AuditEnableRopSimExec="false" />
    <SEHOP Enable="true" TelemetryOnly="false" />
    <Heap TerminateOnError="true" />
    <ChildProcess DisallowChildProcessCreation="false" Audit="true" />
    <UserShadowStack UserShadowStack="true" UserShadowStackStrictMode="true" AuditUserShadowStack="false" />
  </AppConfig>
  <AppConfig Executable="UninstallSelf.exe">
    <DEP Enable="true" EmulateAtlThunks="true" />
    <ASLR BottomUp="true" HighEntropy="true" />
    <StrictHandle Enable="true" />
    <SystemCalls DisableWin32kSystemCalls="true" Audit="false" />
    <ExtensionPoints DisableExtensionPoints="true" />
    <DynamicCode BlockDynamicCode="true" AllowThreadsToOptOut="true" Audit="false" />
    <SignedBinaries MicrosoftSignedOnly="false" AllowStoreSignedBinaries="true" Audit="true" AuditStoreSigned="true" EnforceModuleDependencySigning="true" />
    <Fonts DisableNonSystemFonts="true" AuditOnly="false" Audit="false" />
    <ImageLoad BlockRemoteImageLoads="true" AuditRemoteImageLoads="false" BlockLowLabelImageLoads="true" AuditLowLabelImageLoads="false" />
    <Payload EnableExportAddressFilter="true" AuditEnableExportAddressFilter="false" EnableExportAddressFilterPlus="true" AuditEnableExportAddressFilterPlus="false" EnableImportAddressFilter="true" AuditEnableImportAddressFilter="false" EnableRopStackPivot="true" AuditEnableRopStackPivot="false" EnableRopCallerCheck="true" AuditEnableRopCallerCheck="false" EnableRopSimExec="true" AuditEnableRopSimExec="false" />
    <SEHOP Enable="true" TelemetryOnly="false" />
    <Heap TerminateOnError="true" />
    <ChildProcess DisallowChildProcessCreation="true" Audit="false" />
    <UserShadowStack UserShadowStack="true" UserShadowStackStrictMode="true" AuditUserShadowStack="false" />
  </AppConfig>
  <AppConfig Executable="UninstallToolHelper.exe">
    <DEP Enable="true" EmulateAtlThunks="true" />
    <ASLR BottomUp="true" HighEntropy="false" />
    <StrictHandle Enable="true" />
    <SystemCalls DisableWin32kSystemCalls="false" Audit="true" />
    <ExtensionPoints DisableExtensionPoints="true" />
    <DynamicCode BlockDynamicCode="false" AllowThreadsToOptOut="false" Audit="true" />
    <SignedBinaries MicrosoftSignedOnly="false" AllowStoreSignedBinaries="true" Audit="true" AuditStoreSigned="true" EnforceModuleDependencySigning="false" />
    <Fonts DisableNonSystemFonts="false" AuditOnly="false" Audit="true" />
    <ImageLoad BlockRemoteImageLoads="false" AuditRemoteImageLoads="true" BlockLowLabelImageLoads="false" AuditLowLabelImageLoads="true" />
    <Payload EnableExportAddressFilter="false" AuditEnableExportAddressFilter="true" EnableExportAddressFilterPlus="false" AuditEnableExportAddressFilterPlus="true" EnableImportAddressFilter="false" AuditEnableImportAddressFilter="true" EnableRopStackPivot="true" AuditEnableRopStackPivot="false" EnableRopCallerCheck="false" AuditEnableRopCallerCheck="true" EnableRopSimExec="false" AuditEnableRopSimExec="true" />
    <SEHOP Enable="true" TelemetryOnly="false" />
    <Heap TerminateOnError="true" />
    <ChildProcess DisallowChildProcessCreation="false" Audit="true" />
    <UserShadowStack UserShadowStack="false" UserShadowStackStrictMode="true" AuditUserShadowStack="true" />
  </AppConfig>
  <AppConfig Executable="UninstallToolPortable.exe">
    <DEP Enable="true" EmulateAtlThunks="true" />
    <ASLR BottomUp="true" HighEntropy="false" />
    <StrictHandle Enable="true" />
    <SystemCalls DisableWin32kSystemCalls="false" Audit="true" />
    <ExtensionPoints DisableExtensionPoints="true" />
    <DynamicCode BlockDynamicCode="false" AllowThreadsToOptOut="false" Audit="true" />
    <SignedBinaries MicrosoftSignedOnly="true" AllowStoreSignedBinaries="true" Audit="false" AuditStoreSigned="false" EnforceModuleDependencySigning="false" />
    <Fonts DisableNonSystemFonts="false" AuditOnly="false" Audit="true" />
    <ImageLoad BlockRemoteImageLoads="false" AuditRemoteImageLoads="true" BlockLowLabelImageLoads="false" AuditLowLabelImageLoads="true" />
    <Payload EnableExportAddressFilter="false" AuditEnableExportAddressFilter="true" EnableExportAddressFilterPlus="false" AuditEnableExportAddressFilterPlus="true" EnableImportAddressFilter="false" AuditEnableImportAddressFilter="true" EnableRopStackPivot="false" AuditEnableRopStackPivot="true" EnableRopCallerCheck="false" AuditEnableRopCallerCheck="true" EnableRopSimExec="false" AuditEnableRopSimExec="true" />
    <SEHOP Enable="true" TelemetryOnly="false" />
    <Heap TerminateOnError="true" />
    <ChildProcess DisallowChildProcessCreation="false" Audit="true" />
    <UserShadowStack UserShadowStack="true" UserShadowStackStrictMode="true" AuditUserShadowStack="false" />
  </AppConfig>
  <AppConfig Executable="updater.exe">
    <DEP Enable="true" EmulateAtlThunks="true" />
    <ASLR ForceRelocateImages="true" RequireInfo="false" BottomUp="true" HighEntropy="true" />
    <StrictHandle Enable="true" />
    <SystemCalls DisableWin32kSystemCalls="true" Audit="false" />
    <ExtensionPoints DisableExtensionPoints="true" />
    <DynamicCode BlockDynamicCode="true" AllowThreadsToOptOut="false" Audit="false" />
    <ControlFlowGuard Enable="true" SuppressExports="false" StrictControlFlowGuard="true" />
    <SignedBinaries MicrosoftSignedOnly="true" AllowStoreSignedBinaries="false" Audit="false" AuditStoreSigned="false" EnforceModuleDependencySigning="true" />
    <Fonts DisableNonSystemFonts="true" AuditOnly="false" Audit="false" />
    <ImageLoad BlockRemoteImageLoads="true" AuditRemoteImageLoads="false" BlockLowLabelImageLoads="true" AuditLowLabelImageLoads="false" />
    <Payload EnableExportAddressFilter="true" AuditEnableExportAddressFilter="false" EnableExportAddressFilterPlus="true" AuditEnableExportAddressFilterPlus="false" EnableImportAddressFilter="true" AuditEnableImportAddressFilter="false" EnableRopStackPivot="true" AuditEnableRopStackPivot="false" EnableRopCallerCheck="true" AuditEnableRopCallerCheck="false" EnableRopSimExec="true" AuditEnableRopSimExec="false" />
    <SEHOP Enable="true" TelemetryOnly="false" />
    <Heap TerminateOnError="true" />
    <ChildProcess DisallowChildProcessCreation="true" Audit="false" />
    <UserShadowStack UserShadowStack="true" UserShadowStackStrictMode="true" AuditUserShadowStack="false" />
  </AppConfig>
  <AppConfig Executable="Virtual.Box.exe">
    <DEP Enable="true" EmulateAtlThunks="true" />
    <ASLR BottomUp="true" HighEntropy="true" />
    <StrictHandle Enable="true" />
    <SystemCalls DisableWin32kSystemCalls="false" Audit="true" />
    <ExtensionPoints DisableExtensionPoints="true" />
    <DynamicCode BlockDynamicCode="true" AllowThreadsToOptOut="true" Audit="false" />
    <SignedBinaries MicrosoftSignedOnly="true" AllowStoreSignedBinaries="true" Audit="false" AuditStoreSigned="false" EnforceModuleDependencySigning="true" />
    <Fonts DisableNonSystemFonts="true" AuditOnly="false" Audit="false" />
    <ImageLoad BlockRemoteImageLoads="true" AuditRemoteImageLoads="false" BlockLowLabelImageLoads="true" AuditLowLabelImageLoads="false" />
    <Payload EnableExportAddressFilter="true" AuditEnableExportAddressFilter="false" EnableExportAddressFilterPlus="true" AuditEnableExportAddressFilterPlus="false" EnableImportAddressFilter="true" AuditEnableImportAddressFilter="false" EnableRopStackPivot="true" AuditEnableRopStackPivot="false" EnableRopCallerCheck="true" AuditEnableRopCallerCheck="false" EnableRopSimExec="true" AuditEnableRopSimExec="false" />
    <SEHOP Enable="true" TelemetryOnly="false" />
    <Heap TerminateOnError="true" />
    <ChildProcess DisallowChildProcessCreation="true" Audit="false" />
    <UserShadowStack UserShadowStack="true" UserShadowStackStrictMode="true" AuditUserShadowStack="false" />
  </AppConfig>
  <AppConfig Executable="VirtualBox.exe">
    <DEP Enable="true" EmulateAtlThunks="false" />
    <ASLR BottomUp="true" HighEntropy="true" />
    <StrictHandle Enable="true" />
    <SystemCalls DisableWin32kSystemCalls="true" Audit="false" />
    <ExtensionPoints DisableExtensionPoints="true" />
    <DynamicCode BlockDynamicCode="true" AllowThreadsToOptOut="true" Audit="false" />
    <SignedBinaries MicrosoftSignedOnly="true" AllowStoreSignedBinaries="true" Audit="false" AuditStoreSigned="false" EnforceModuleDependencySigning="true" />
    <Fonts DisableNonSystemFonts="true" AuditOnly="false" Audit="false" />
    <ImageLoad BlockRemoteImageLoads="true" AuditRemoteImageLoads="false" BlockLowLabelImageLoads="true" AuditLowLabelImageLoads="false" />
    <Payload EnableExportAddressFilter="true" AuditEnableExportAddressFilter="false" EnableExportAddressFilterPlus="true" AuditEnableExportAddressFilterPlus="false" EnableImportAddressFilter="true" AuditEnableImportAddressFilter="false" EnableRopStackPivot="true" AuditEnableRopStackPivot="false" EnableRopCallerCheck="true" AuditEnableRopCallerCheck="false" EnableRopSimExec="true" AuditEnableRopSimExec="false" />
    <SEHOP Enable="true" TelemetryOnly="false" />
    <Heap TerminateOnError="true" />
    <ChildProcess DisallowChildProcessCreation="true" Audit="false" />
    <UserShadowStack UserShadowStack="true" UserShadowStackStrictMode="true" AuditUserShadowStack="false" />
  </AppConfig>
  <AppConfig Executable="VirtualBoxVM.exe">
    <DEP Enable="true" EmulateAtlThunks="false" />
    <ASLR BottomUp="true" HighEntropy="true" />
    <StrictHandle Enable="true" />
    <SystemCalls DisableWin32kSystemCalls="true" Audit="false" />
    <ExtensionPoints DisableExtensionPoints="true" />
    <DynamicCode BlockDynamicCode="false" AllowThreadsToOptOut="false" Audit="true" />
    <SignedBinaries MicrosoftSignedOnly="true" AllowStoreSignedBinaries="false" Audit="false" AuditStoreSigned="false" EnforceModuleDependencySigning="true" />
    <Fonts DisableNonSystemFonts="true" AuditOnly="false" Audit="false" />
    <ImageLoad BlockRemoteImageLoads="true" AuditRemoteImageLoads="false" BlockLowLabelImageLoads="true" AuditLowLabelImageLoads="false" />
    <Payload EnableExportAddressFilter="true" AuditEnableExportAddressFilter="false" EnableExportAddressFilterPlus="true" AuditEnableExportAddressFilterPlus="false" EnableImportAddressFilter="true" AuditEnableImportAddressFilter="false" EnableRopStackPivot="true" AuditEnableRopStackPivot="false" EnableRopCallerCheck="true" AuditEnableRopCallerCheck="false" EnableRopSimExec="false" />
    <SEHOP Enable="true" TelemetryOnly="false" />
    <Heap TerminateOnError="true" />
    <ChildProcess DisallowChildProcessCreation="true" Audit="false" />
    <UserShadowStack UserShadowStack="true" UserShadowStackStrictMode="true" AuditUserShadowStack="false" />
  </AppConfig>
  <AppConfig Executable="vulkaninfo-x64.exe">
    <DEP Enable="true" EmulateAtlThunks="true" />
    <ASLR ForceRelocateImages="true" RequireInfo="true" BottomUp="true" HighEntropy="false" />
    <StrictHandle Enable="true" />
    <SystemCalls DisableWin32kSystemCalls="false" Audit="true" />
    <ExtensionPoints DisableExtensionPoints="true" />
    <DynamicCode BlockDynamicCode="false" AllowThreadsToOptOut="false" Audit="true" />
    <ControlFlowGuard Enable="true" SuppressExports="false" StrictControlFlowGuard="true" />
    <SignedBinaries MicrosoftSignedOnly="false" AllowStoreSignedBinaries="true" Audit="true" AuditStoreSigned="true" EnforceModuleDependencySigning="false" />
    <Fonts DisableNonSystemFonts="false" AuditOnly="false" Audit="true" />
    <ImageLoad BlockRemoteImageLoads="false" AuditRemoteImageLoads="true" BlockLowLabelImageLoads="false" AuditLowLabelImageLoads="true" />
    <Payload EnableExportAddressFilter="false" AuditEnableExportAddressFilter="true" EnableExportAddressFilterPlus="false" AuditEnableExportAddressFilterPlus="true" EnableImportAddressFilter="false" AuditEnableImportAddressFilter="true" EnableRopStackPivot="false" AuditEnableRopStackPivot="true" EnableRopCallerCheck="false" AuditEnableRopCallerCheck="true" EnableRopSimExec="false" AuditEnableRopSimExec="true" />
    <SEHOP Enable="true" TelemetryOnly="false" />
    <Heap TerminateOnError="true" />
    <ChildProcess DisallowChildProcessCreation="false" Audit="true" />
    <UserShadowStack UserShadowStack="false" UserShadowStackStrictMode="true" AuditUserShadowStack="true" />
  </AppConfig>
  <AppConfig Executable="vulkaninfo-x86.exe">
    <DEP Enable="true" EmulateAtlThunks="true" />
    <ASLR ForceRelocateImages="true" RequireInfo="true" BottomUp="true" HighEntropy="false" />
    <StrictHandle Enable="true" />
    <SystemCalls DisableWin32kSystemCalls="false" Audit="true" />
    <ExtensionPoints DisableExtensionPoints="true" />
    <DynamicCode BlockDynamicCode="false" AllowThreadsToOptOut="false" Audit="true" />
    <ControlFlowGuard Enable="true" SuppressExports="false" StrictControlFlowGuard="true" />
    <SignedBinaries MicrosoftSignedOnly="false" AllowStoreSignedBinaries="true" Audit="true" AuditStoreSigned="true" EnforceModuleDependencySigning="false" />
    <Fonts DisableNonSystemFonts="false" AuditOnly="false" Audit="true" />
    <ImageLoad BlockRemoteImageLoads="false" AuditRemoteImageLoads="true" BlockLowLabelImageLoads="false" AuditLowLabelImageLoads="true" />
    <Payload EnableExportAddressFilter="false" AuditEnableExportAddressFilter="true" EnableExportAddressFilterPlus="false" AuditEnableExportAddressFilterPlus="true" EnableImportAddressFilter="false" AuditEnableImportAddressFilter="true" EnableRopStackPivot="false" AuditEnableRopStackPivot="true" EnableRopCallerCheck="false" AuditEnableRopCallerCheck="true" EnableRopSimExec="false" AuditEnableRopSimExec="true" />
    <SEHOP Enable="true" TelemetryOnly="false" />
    <Heap TerminateOnError="true" />
    <ChildProcess DisallowChildProcessCreation="false" Audit="true" />
    <UserShadowStack UserShadowStack="false" UserShadowStackStrictMode="true" AuditUserShadowStack="true" />
  </AppConfig>
  <AppConfig Executable="WargamingErrorMonitor.exe">
    <DEP Enable="true" EmulateAtlThunks="true" />
    <ASLR ForceRelocateImages="true" RequireInfo="true" BottomUp="true" HighEntropy="true" />
    <StrictHandle Enable="true" />
    <SystemCalls DisableWin32kSystemCalls="true" Audit="false" />
    <ExtensionPoints DisableExtensionPoints="true" />
    <DynamicCode BlockDynamicCode="true" AllowThreadsToOptOut="true" Audit="false" />
    <ControlFlowGuard Enable="true" SuppressExports="false" StrictControlFlowGuard="true" />
    <SignedBinaries MicrosoftSignedOnly="true" AllowStoreSignedBinaries="false" Audit="false" AuditStoreSigned="false" EnforceModuleDependencySigning="true" />
    <Fonts DisableNonSystemFonts="true" AuditOnly="false" Audit="false" />
    <ImageLoad BlockRemoteImageLoads="true" AuditRemoteImageLoads="false" BlockLowLabelImageLoads="true" AuditLowLabelImageLoads="false" />
    <Payload EnableExportAddressFilter="true" AuditEnableExportAddressFilter="false" EnableExportAddressFilterPlus="true" AuditEnableExportAddressFilterPlus="false" EnableImportAddressFilter="true" AuditEnableImportAddressFilter="false" EnableRopStackPivot="true" AuditEnableRopStackPivot="false" EnableRopCallerCheck="true" AuditEnableRopCallerCheck="false" EnableRopSimExec="true" AuditEnableRopSimExec="false" />
    <SEHOP Enable="true" TelemetryOnly="false" />
    <Heap TerminateOnError="true" />
    <ChildProcess DisallowChildProcessCreation="true" Audit="false" />
    <UserShadowStack UserShadowStack="true" UserShadowStackStrictMode="true" AuditUserShadowStack="false" />
  </AppConfig>
  <AppConfig Executable="wg.exe">
    <DEP Enable="true" EmulateAtlThunks="false" />
    <ASLR BottomUp="true" HighEntropy="false" />
    <StrictHandle Enable="true" />
    <SystemCalls DisableWin32kSystemCalls="false" Audit="true" />
    <ExtensionPoints DisableExtensionPoints="true" />
    <DynamicCode BlockDynamicCode="false" AllowThreadsToOptOut="false" Audit="true" />
    <SignedBinaries MicrosoftSignedOnly="false" AllowStoreSignedBinaries="true" Audit="true" AuditStoreSigned="true" EnforceModuleDependencySigning="false" />
    <Fonts DisableNonSystemFonts="false" AuditOnly="false" Audit="true" />
    <ImageLoad BlockRemoteImageLoads="false" AuditRemoteImageLoads="true" BlockLowLabelImageLoads="false" AuditLowLabelImageLoads="true" />
    <Payload EnableExportAddressFilter="false" AuditEnableExportAddressFilter="true" EnableExportAddressFilterPlus="false" AuditEnableExportAddressFilterPlus="true" EnableImportAddressFilter="false" AuditEnableImportAddressFilter="true" EnableRopStackPivot="false" AuditEnableRopStackPivot="true" EnableRopCallerCheck="false" AuditEnableRopCallerCheck="true" EnableRopSimExec="false" AuditEnableRopSimExec="true" />
    <SEHOP Enable="true" TelemetryOnly="false" />
    <Heap TerminateOnError="true" />
    <ChildProcess DisallowChildProcessCreation="false" Audit="true" />
    <UserShadowStack UserShadowStack="true" UserShadowStackStrictMode="true" AuditUserShadowStack="false" />
  </AppConfig>
  <AppConfig Executable="wgc.exe">
    <DEP Enable="true" EmulateAtlThunks="true" />
    <ASLR BottomUp="true" HighEntropy="false" />
    <StrictHandle Enable="true" />
    <SystemCalls DisableWin32kSystemCalls="false" Audit="true" />
    <ExtensionPoints DisableExtensionPoints="true" />
    <DynamicCode BlockDynamicCode="false" AllowThreadsToOptOut="false" Audit="true" />
    <SignedBinaries MicrosoftSignedOnly="false" AllowStoreSignedBinaries="true" Audit="true" AuditStoreSigned="true" EnforceModuleDependencySigning="false" />
    <Fonts DisableNonSystemFonts="false" AuditOnly="false" Audit="true" />
    <ImageLoad BlockRemoteImageLoads="false" AuditRemoteImageLoads="true" BlockLowLabelImageLoads="false" AuditLowLabelImageLoads="true" />
    <Payload EnableExportAddressFilter="false" AuditEnableExportAddressFilter="true" EnableExportAddressFilterPlus="false" AuditEnableExportAddressFilterPlus="true" EnableImportAddressFilter="false" AuditEnableImportAddressFilter="true" EnableRopStackPivot="false" AuditEnableRopStackPivot="true" EnableRopCallerCheck="false" AuditEnableRopCallerCheck="true" EnableRopSimExec="false" AuditEnableRopSimExec="true" />
    <SEHOP Enable="true" TelemetryOnly="false" />
    <Heap TerminateOnError="true" />
    <ChildProcess DisallowChildProcessCreation="false" Audit="true" />
    <UserShadowStack UserShadowStack="true" UserShadowStackStrictMode="true" AuditUserShadowStack="false" />
  </AppConfig>
  <AppConfig Executable="X:\Games\�WGCheck_EU\WGCheck.exe">
    <DEP Enable="true" EmulateAtlThunks="true" />
    <ASLR BottomUp="true" HighEntropy="false" />
    <StrictHandle Enable="true" />
    <SystemCalls DisableWin32kSystemCalls="false" Audit="true" />
    <ExtensionPoints DisableExtensionPoints="true" />
    <DynamicCode BlockDynamicCode="false" AllowThreadsToOptOut="false" Audit="true" />
    <SignedBinaries MicrosoftSignedOnly="false" AllowStoreSignedBinaries="true" Audit="true" AuditStoreSigned="true" EnforceModuleDependencySigning="false" />
    <Fonts DisableNonSystemFonts="false" AuditOnly="false" Audit="true" />
    <ImageLoad BlockRemoteImageLoads="false" AuditRemoteImageLoads="true" BlockLowLabelImageLoads="false" AuditLowLabelImageLoads="true" />
    <Payload EnableExportAddressFilter="false" AuditEnableExportAddressFilter="true" EnableExportAddressFilterPlus="false" AuditEnableExportAddressFilterPlus="true" EnableImportAddressFilter="false" AuditEnableImportAddressFilter="true" EnableRopStackPivot="false" AuditEnableRopStackPivot="true" EnableRopCallerCheck="false" AuditEnableRopCallerCheck="true" EnableRopSimExec="false" AuditEnableRopSimExec="true" />
    <SEHOP Enable="true" TelemetryOnly="false" />
    <Heap TerminateOnError="true" />
    <ChildProcess DisallowChildProcessCreation="false" Audit="true" />
    <UserShadowStack UserShadowStack="true" UserShadowStackStrictMode="true" AuditUserShadowStack="false" />
  </AppConfig>
  <AppConfig Executable="wgc_api.exe">
    <DEP Enable="true" EmulateAtlThunks="true" />
    <ASLR ForceRelocateImages="true" RequireInfo="true" BottomUp="true" HighEntropy="false" />
    <StrictHandle Enable="true" />
    <SystemCalls DisableWin32kSystemCalls="false" Audit="true" />
    <ExtensionPoints DisableExtensionPoints="true" />
    <DynamicCode BlockDynamicCode="false" AllowThreadsToOptOut="false" Audit="true" />
    <ControlFlowGuard Enable="true" SuppressExports="false" StrictControlFlowGuard="true" />
    <SignedBinaries MicrosoftSignedOnly="false" AllowStoreSignedBinaries="true" Audit="true" AuditStoreSigned="true" EnforceModuleDependencySigning="false" />
    <Fonts DisableNonSystemFonts="false" AuditOnly="false" Audit="true" />
    <ImageLoad BlockRemoteImageLoads="false" AuditRemoteImageLoads="true" BlockLowLabelImageLoads="false" AuditLowLabelImageLoads="true" />
    <Payload EnableExportAddressFilter="false" AuditEnableExportAddressFilter="true" EnableExportAddressFilterPlus="false" AuditEnableExportAddressFilterPlus="true" EnableImportAddressFilter="false" AuditEnableImportAddressFilter="true" EnableRopStackPivot="false" AuditEnableRopStackPivot="true" EnableRopCallerCheck="false" AuditEnableRopCallerCheck="true" EnableRopSimExec="false" AuditEnableRopSimExec="true" />
    <SEHOP Enable="true" TelemetryOnly="false" />
    <Heap TerminateOnError="true" />
    <ChildProcess DisallowChildProcessCreation="false" Audit="true" />
    <UserShadowStack UserShadowStack="false" UserShadowStackStrictMode="true" AuditUserShadowStack="true" />
  </AppConfig>
  <AppConfig Executable="WinOptimizerFW.exe">
    <DEP Enable="true" EmulateAtlThunks="true" />
    <ASLR BottomUp="true" HighEntropy="false" />
    <StrictHandle Enable="true" />
    <SystemCalls DisableWin32kSystemCalls="false" Audit="true" />
    <ExtensionPoints DisableExtensionPoints="true" />
    <DynamicCode BlockDynamicCode="false" AllowThreadsToOptOut="false" Audit="true" />
    <SignedBinaries MicrosoftSignedOnly="false" AllowStoreSignedBinaries="true" Audit="true" AuditStoreSigned="true" EnforceModuleDependencySigning="false" />
    <Fonts DisableNonSystemFonts="false" AuditOnly="false" Audit="true" />
    <ImageLoad BlockRemoteImageLoads="false" AuditRemoteImageLoads="true" BlockLowLabelImageLoads="false" AuditLowLabelImageLoads="true" />
    <Payload EnableExportAddressFilter="false" AuditEnableExportAddressFilter="true" EnableExportAddressFilterPlus="false" AuditEnableExportAddressFilterPlus="true" EnableImportAddressFilter="false" AuditEnableImportAddressFilter="true" EnableRopStackPivot="false" AuditEnableRopStackPivot="true" EnableRopCallerCheck="false" AuditEnableRopCallerCheck="true" EnableRopSimExec="false" AuditEnableRopSimExec="true" />
    <SEHOP Enable="true" TelemetryOnly="false" />
    <Heap TerminateOnError="true" />
    <ChildProcess DisallowChildProcessCreation="false" Audit="true" />
    <UserShadowStack UserShadowStack="true" UserShadowStackStrictMode="true" AuditUserShadowStack="false" />
  </AppConfig>
  <AppConfig Executable="wireguard.exe">
    <DEP Enable="true" EmulateAtlThunks="true" />
    <ASLR ForceRelocateImages="true" RequireInfo="true" BottomUp="true" HighEntropy="false" />
    <StrictHandle Enable="true" />
    <SystemCalls DisableWin32kSystemCalls="false" Audit="true" />
    <ExtensionPoints DisableExtensionPoints="true" />
    <DynamicCode BlockDynamicCode="false" AllowThreadsToOptOut="false" Audit="true" />
    <SignedBinaries MicrosoftSignedOnly="false" AllowStoreSignedBinaries="true" Audit="true" AuditStoreSigned="true" EnforceModuleDependencySigning="false" />
    <Fonts DisableNonSystemFonts="false" AuditOnly="false" Audit="true" />
    <ImageLoad BlockRemoteImageLoads="false" AuditRemoteImageLoads="true" BlockLowLabelImageLoads="false" AuditLowLabelImageLoads="true" />
    <Payload EnableExportAddressFilter="false" AuditEnableExportAddressFilter="true" EnableExportAddressFilterPlus="false" AuditEnableExportAddressFilterPlus="true" EnableImportAddressFilter="false" AuditEnableImportAddressFilter="true" EnableRopStackPivot="false" AuditEnableRopStackPivot="true" EnableRopCallerCheck="false" AuditEnableRopCallerCheck="true" EnableRopSimExec="false" AuditEnableRopSimExec="true" />
    <SEHOP Enable="true" TelemetryOnly="false" />
    <Heap TerminateOnError="true" />
    <ChildProcess DisallowChildProcessCreation="false" Audit="true" />
  </AppConfig>
  <AppConfig Executable="WO17.exe">
    <DEP Enable="true" EmulateAtlThunks="true" />
    <ASLR BottomUp="true" HighEntropy="false" />
    <StrictHandle Enable="true" />
    <SystemCalls DisableWin32kSystemCalls="false" Audit="true" />
    <ExtensionPoints DisableExtensionPoints="true" />
    <DynamicCode BlockDynamicCode="false" AllowThreadsToOptOut="false" Audit="true" />
    <SignedBinaries MicrosoftSignedOnly="false" AllowStoreSignedBinaries="true" Audit="true" AuditStoreSigned="true" EnforceModuleDependencySigning="false" />
    <Fonts DisableNonSystemFonts="false" AuditOnly="false" Audit="true" />
    <ImageLoad BlockRemoteImageLoads="false" AuditRemoteImageLoads="true" BlockLowLabelImageLoads="false" AuditLowLabelImageLoads="true" />
    <Payload EnableExportAddressFilter="false" AuditEnableExportAddressFilter="true" EnableExportAddressFilterPlus="false" AuditEnableExportAddressFilterPlus="true" EnableImportAddressFilter="false" AuditEnableImportAddressFilter="true" EnableRopStackPivot="true" AuditEnableRopStackPivot="false" EnableRopCallerCheck="false" AuditEnableRopCallerCheck="true" EnableRopSimExec="false" AuditEnableRopSimExec="true" />
    <SEHOP Enable="true" TelemetryOnly="false" />
    <Heap TerminateOnError="true" />
    <ChildProcess DisallowChildProcessCreation="false" Audit="true" />
    <UserShadowStack UserShadowStack="true" UserShadowStackStrictMode="true" AuditUserShadowStack="false" />
  </AppConfig>
  <AppConfig Executable="WorldOfTanks.exe">
    <DEP Enable="true" EmulateAtlThunks="true" />
    <ASLR BottomUp="true" HighEntropy="false" />
    <StrictHandle Enable="true" />
    <SystemCalls DisableWin32kSystemCalls="false" Audit="true" />
    <ExtensionPoints DisableExtensionPoints="true" />
    <DynamicCode BlockDynamicCode="false" AllowThreadsToOptOut="false" Audit="true" />
    <SignedBinaries MicrosoftSignedOnly="false" AllowStoreSignedBinaries="true" Audit="true" AuditStoreSigned="true" EnforceModuleDependencySigning="true" />
    <Fonts DisableNonSystemFonts="false" AuditOnly="false" Audit="true" />
    <ImageLoad BlockRemoteImageLoads="false" AuditRemoteImageLoads="true" BlockLowLabelImageLoads="false" AuditLowLabelImageLoads="true" />
    <Payload EnableExportAddressFilter="false" AuditEnableExportAddressFilter="true" EnableExportAddressFilterPlus="false" AuditEnableExportAddressFilterPlus="true" EnableImportAddressFilter="false" AuditEnableImportAddressFilter="true" EnableRopStackPivot="false" AuditEnableRopStackPivot="true" EnableRopCallerCheck="false" AuditEnableRopCallerCheck="true" EnableRopSimExec="false" AuditEnableRopSimExec="true" />
    <SEHOP Enable="true" TelemetryOnly="false" />
    <Heap TerminateOnError="true" />
    <ChildProcess DisallowChildProcessCreation="false" Audit="true" />
    <UserShadowStack UserShadowStack="false" UserShadowStackStrictMode="true" AuditUserShadowStack="true" />
  </AppConfig>
</MitigationPolicy>

  ```
