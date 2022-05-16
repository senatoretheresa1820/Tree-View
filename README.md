# Tree-View
Press Down and Enter keys in order to select Open... option Send("{DOWN}") Sleep(500) Send("{ENTER}") $hWnd = WinWait("Open File") ; Put the focus on the Tree view and select Local Disk (C:) folder ControlFocus($hWnd, "", "Tree View") Send("Local") ; Expand the C drive, Search for AutoItScripts and expand it Send("{RIGHT}")
