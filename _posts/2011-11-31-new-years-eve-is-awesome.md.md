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

<div class="fr-view">
	<div class="terminal" style="margin:20px;padding:10;box-sizing:border-box;width:1150px;min-width:300px;height:400px;border:1px solid #263243;box-shadow:2px 4px 10px rgba(0, 0, 0, 0.5);display:grid;grid-template-rows:30px 1fr;">
		<div class="toolbar" style="margin:10;padding:10;box-sizing:border-box;background:black;display:grid;grid-template-columns:24px 1fr 140px;align-items:center;user-select:none;padding-left:4px;">
			<div class="icon" style='margin:0;padding:0;box-sizing:border-box;width:16px;height:16px;background-image:url("https://vectorified.com/images/powershell-icon-25.png");background-size:cover;justify-self:center;'>&nbsp; &nbsp;</div>
			<div class="title" style="margin: 0;
  padding: 0;
  box-sizing: border-box;"><span style="color: rgb(255, 255, 255);">Windows PowerShell &nbsp;&nbsp;</span></div>
			<div class="buttons" style="margin:0;padding:0;box-sizing:border-box;height:100%;display:grid;grid-template-columns:repeat(3, 1fr);">
				<div class="button" style="margin:0;padding:0;box-sizing:border-box;font-size:14px;cursor:default;display:flex;align-items:center;justify-content:center;"><span style="color: rgb(255, 255, 255);">&nbsp;─ &nbsp; &nbsp; ◻</span></div>
				<div class="button close" style="margin:0;padding:0;box-sizing:border-box;font-size:14px;cursor:default;display:flex;align-items:center;justify-content:center;"><span style="color: rgb(255, 255, 255);">&nbsp; &nbsp; ✕</span></div>
			</div>
		</div>
		<div class="container" style="margin:0;padding:0;box-sizing:border-box;background:#012456;overflow-y:scroll;">

			<p class="text" style="margin:0;padding-left:13px;box-sizing:border-box;font-family:Monospace;cursor:default;font-size:12px;">
				<br>
			</p>

			<p class="text" style="margin:0;padding-left:13px;box-sizing:border-box;font-family:Monospace;cursor:default;font-size:12px;"><span style="color: rgb(255, 255, 255); font-size: 14px;">Copyright (C) Microsoft Corporation. All rights reserved.</span></p>

			<p class="text space" style="margin:0;padding-left:13px;box-sizing:border-box;font-family:Monospace;cursor:default;font-size:12px;margin-bottom:20px;"><span style="font-size: 14px;"><span style="color: rgb(255, 255, 255);">PS C:\Users\GuideM-Student&gt;</span></span>
			</p>

			<p class="text space" style="margin:0;padding-left:13px;box-sizing:border-box;font-family:Monospace;cursor:default;font-size:12px;margin-bottom:20px;">
				<br>
				<br>
			</p>

			<p class="text space" style="margin:0;padding:0;box-sizing:border-box;font-family:Monospace;cursor:default;font-size:12px;margin-bottom:20px;">
				<br>
			</p>

			<p class="text space" style="margin:0;padding:0;box-sizing:border-box;font-family:Monospace;cursor:default;font-size:12px;margin-bottom:20px;">
				<br>
			</p>

			<p class="text space" style="margin:0;padding-left:13px;box-sizing:border-box;font-family:Monospace;cursor:default;font-size:12px;margin-bottom:20px;">
				<br>
			</p>

			<p class="text space" style="margin:0;padding-left:13px;box-sizing:border-box;font-family:Monospace;cursor:default;font-size:12px;margin-bottom:20px;">
				<br>
			</p>
		</div>
	</div>
</div>

![](https://github.com/iansecretario/iansecretario.github.io/blob/main/_posts/attachments/img/20220517142008.png)
