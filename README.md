# include-
#include &lt;StructureConstants.au3> #include &lt;Constants.au3> #include &lt;WinAPIConv.au3> #include "..\GetScreen\GetScreen.au3"  Local $hWnd = WinGetHandle("[CLASS:SciTEWindow]")  ; this calculates the screen position of the window Local $aWin = WinGetPos($hWnd) If @error Then Exit MsgBox($MB_SYSTEMMODAL, "", "Window not found") Local $Width = $aWin[2], $Height = $aWin[3]
