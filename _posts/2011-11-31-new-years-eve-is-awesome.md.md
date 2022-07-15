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


<html>
<div class="fr-view">
    <div class="Widgets" id="Terminal">
        <div class="Container" style="border: 1px solid #777;
  align-content: center;
    border-radius: 10px;
  overflow: hidden;
  position: relative;
  background: #23252F;
  display: inline-block;
  width: 1150px;
  box-shadow: 5px 5px 20px 10px rgba(41, 41, 41, .3);
  max-height: 500px;
  overflow: auto;">
            <div class="titleBar" style="display: flex;
  flex-flow: row nowrap;
  padding: 4px 10px;
  background: #2b2e3d;
  position: sticky;
  top: 0;">
                <div class="scrollbar" id="style-1">
                    <div class="force-overflow">
                        <br>
                    </div>
                </div>
                <div class="windowButton">&nbsp;&nbsp;</div>
                <div class="title" style="flex: 1;
  text-align: center;
  color: #DFDFDF;
  font-family: monospace;
  font-size: 16px;">root@Kali:~</div>
                <div class="windowMenu">
                    <br>
                </div>
            </div>
            <div class="body" style="padding: 10px 7px;
  height: 100%;">
                <div class="entry" style="color: cyan;
  margin: 20px 0;
  font-weight: bold;
  font-family: monospace;
  font-size: 18px;">
                    <div class="firstLine" style="display: flex;
  flex-flow: row wrap;">
                        <div class="preDec">┌──(root💀kali)-[~]
                            <br>└─# exit
                            <br>
                            <br>
                        </div>
                    </div>
                </div>
                <div class="entry" style="color: chartreuse;
  margin: 5px 0;
  font-weight: bold;
  font-family: monospace;
  font-size: 18px;">
                    <div class="firstLine" style="display: flex;
  flex-flow: row wrap;">
                        <div class="finPostDec">
                            <br>
                        </div>
                    </div>
                    <div class="secondLine" style="display: flex;
  flex-flow: row wrap;">
                        <div class="scDec">
                            <br>
                            <br>
                        </div>

                        <p>
                            <br>
                        </p>
                    </div>
                </div>
            </div>
        </div>
        <script>


        </script>
    </div>
</div>

<p>
    <br>
</p>
</html>

![](https://github.com/iansecretario/iansecretario.github.io/blob/main/_posts/attachments/img/20220517142008.png)
