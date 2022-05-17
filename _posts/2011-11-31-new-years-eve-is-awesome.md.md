---
layout: post
author: jill
title: post2
tag: none,testing
---
An apple is a sweet, edible fruit produced by an apple tree.

Apple trees are cultivated worldwide, and are the most widely grown species in
the genus Malus. The tree originated in Central Asia, where its wild ancestor,
Malus sieversii, is still found today. Apples have been grown for thousands of
years in Asia and Europe, and were brought to North America by European
colonists.

---
anti-debugging tips FindWindow
```c
#include<Windows.h>

int main()
{
	//! Windows types suck. You could make a std::wchar and convert it with .c_str()
	LPCSTR windowName ="x64dbg", "OllyDbg", "IDA Pro"; //! Window name of the debugger you are checking for
	//! LPCWSTR windowName = L"OllyDbg, IDA Pro, BinaryNinja, ";

	//! Recall that FindWindow will return NULL if it wasn't found
	if (FindWindow(NULL, windowName))
	{
		MessageBoxA(NULL, "Debugger Found", "Notification", MB_OK);
	}
	return 0;
}
```
`MessageBoxA` 
![](_posts/attachments/Pasted%20image%2020220517143610.png)