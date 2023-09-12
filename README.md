﻿# LC2ProcessProxifier

Process Proxifier uses FiddlerCore to add proxy settings to the Windows applications. 
Using FiddlerCore and its beforeRequest callback mechanism and setting 'X-OverrideGateway', 
it's possible to define an HTTP Proxy or Socks for the specific process in Windows.

# Download

<a href="https://raw.githubusercontent.com/David-Honisch/LC2ProcessProxifier/main/LC2ProcessProxifier.v.1.0.zip">LC2ProcessProxifier</a>

![LC2ProcessProxifier](/LC2ProcessProxifier/Images/pp.png) 

How to use it
---
First you need to define its default proxy settings and then select the process 
which should be proxified. 

Here if you don't enter its proxy settings, the default settings will be used automatically. 
Also it's possible to set a different proxy per each process as well.

The username & password fields are optional and if they are provided, they will be used for sending the Basic Authentication credentials to an upstream proxy.
 

Supported Operating Systems
---
   - Windows XP Service Pack 3+

 

Prerequisites
---
   - Microsoft .NET Framework 4

Based on
---
Process Proxifier
 
Credits
---
Thanks to Eric Lawrence for his excellent web debugger and proxy!
