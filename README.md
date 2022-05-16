# Tooltip
Local $aTooltip = WinList("[CLASS:tooltips_class32]") If IsArray($aTooltip) And $aTooltip[0][0] &lt;> 0 Then     ConsoleWrite($aTooltip[1][0] &amp; "   " &amp; $aTooltip[1][1] &amp; @lf) EndIf
