# WinWait
#RequireAdmin  RunWait(@ScriptDir &amp; '\A.exe')   $hWindow = WinWait("Install") $iReturnValue = ControlClick($hWindow, "", "[CLASS:Button; INSTANCE:4]") #RequireAdmin  RunWait(@ScriptDir &amp; '\A.exe')  Local $hWnd = WinWait("[CLASS:#32770]", "", 10)  ControlClick($hWnd, "", "Button4")
