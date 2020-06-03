# AzureИсключение:
System.IO.IOException: Параметр задан неверно.

   в System.IO.__Error.WinIOError(Int32 errorCode, String maybeFullPath)
   в System.IO.__Error.WinIOError()
   в System.Console.set_CursorVisible(Boolean value)
   в Microsoft.PowerShell.Internal.VirtualTerminal.set_CursorVisible(Boolean value)
   в Microsoft.PowerShell.PSConsoleReadLine.ReallyRender(RenderData renderData, String defaultColor)
   в Microsoft.PowerShell.PSConsoleReadLine.ForceRender()
   в Microsoft.PowerShell.PSConsoleReadLine.Render()
   в Microsoft.PowerShell.PSConsoleReadLine.Insert(Char c)
   в Microsoft.PowerShell.PSConsoleReadLine.SelfInsert(Nullable`1 key, Object arg)
   в Microsoft.PowerShell.PSConsoleReadLine.ProcessOneKey(ConsoleKeyInfo key, Dictionary`2 dispatchTable, Boolean ignoreIfNoAction, Object arg)
   в Microsoft.PowerShell.PSConsoleReadLine.InputLoop()
   в Microsoft.PowerShell.PSConsoleReadLine.ReadLine(Runspace runspace, EngineIntrinsics engineIntrinsics)
