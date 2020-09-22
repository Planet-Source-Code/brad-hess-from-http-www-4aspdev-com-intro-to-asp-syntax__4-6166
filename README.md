<div align="center">

## Intro to ASP syntax


</div>

### Description

Attention ASP newbies! Looking to create your first ASP page? Check out this tutorial!
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Brad Hess from http://www\.4aspdev\.com](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/brad-hess-from-http-www-4aspdev-com.md)
**Level**          |Beginner
**User Rating**    |4.0 (28 globes from 7 users)
**Compatibility**  |ASP \(Active Server Pages\)
**Category**       |[Complete Applications](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/complete-applications__4-7.md)
**World**          |[ASP / VbScript](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/asp-vbscript.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/brad-hess-from-http-www-4aspdev-com-intro-to-asp-syntax__4-6166/archive/master.zip)





### Source Code

<p><font face="Verdana">Let&#8217;s code our first ASP page. To do this write out
the following code in your choice of development environment.</font>
<table border="0" cellPadding="0" cellSpacing="0" width="100%">
 <tbody>
 <tr>
 <td bgColor="#d0d5df" width="100%"><font face="Verdana"><font size="+0"><font color="#0000ff"><</font><font color="#663300">HTML</font></font>><br>
     <</font><font color="#663300" face="Verdana">BODY</font><font face="Verdana"><font size="+0"><font color="#0000ff">><br>
         <</font><font color="#663300">B</font><font color="#0000ff">></font>Welcome
 to my webpage hosted on PWS!<font color="#0000ff"></</font><font color="#663300">B</font></font>><br>
         <<font size="+0"><font color="#663300">BR</font><font color="#0000ff">></font>The
 time is now: <span style="BACKGROUND-COLOR: #ffff00"><font color="#000000">&lt;%</font></span>=Response.Write(<b><font color="#0000ff">TIME()</font></b>)<span style="BACKGROUND-COLOR: #ffff00"><font color="#000000">%></font></span></font><br>
         <</font><font color="#663300" face="Verdana">BR</font><font face="Verdana"><font size="+0"><font color="#0000ff">><br>
      </</font><font color="#663300">BODY</font></font>><br>
 </</font><font face="Verdana" size="+0"><font color="#663300">HTML</font><font color="#0000ff">></font></font></td>
 </tr>
 </tbody>
</table>
<p><font face="Verdana">Save the file in the c:\Inetpub\wwwroot\ directory on
your machine and name it default.asp. Try accessing your website by opening a
browser and typing http://127.0.0.1/default.asp or http://yourmachinename/default.asp.
127.0.0.1 is what is called the loopback address and is the TCP\IP address that
points at your machine. The text: Welcome to my webpage hosted on PWS! should
now show up. On the line under you should read "The time is now:"
followed by the current time. </font><a href="http://www.4aspdev.com/examples/example1.asp"><font color="blue" face="Verdana">Like
this</font></a><font face="Verdana"> only without the Back link. If the time is
showing up correctly you have a working ASP server running on your PC!. If the
time does not show up correctly then something is wrong with the installation of
personal web server</font></p>
<p><font face="Verdana">Now that we have an ASP page. Lets look at what is
really happening when the page is requested. The code is as follows</font>
<table border="0" cellPadding="0" cellSpacing="0" width="100%">
 <tbody>
 <tr>
 <td bgColor="#d0d5df" width="100%"><font face="Verdana"><font size="+0"><font color="#0000ff"><</font><font color="#663300">HTML</font></font>><br>
     <</font><font color="#663300" face="Verdana">BODY</font><font face="Verdana"><font size="+0"><font color="#0000ff">><br>
         <</font><font color="#663300">B</font><font color="#0000ff">></font>Welcome
 to my webpage hosted on PWS!<font color="#0000ff"></</font><font color="#663300">B</font></font>><br>
         <<font size="+0"><font color="#663300">BR</font><font color="#0000ff">></font>The
 time is now: <span style="BACKGROUND-COLOR: #ffff00"><font color="#000000">&lt;%</font></span>=Response.Write(<b><font color="#0000ff">TIME()</font></b>)<span style="BACKGROUND-COLOR: #ffff00"><font color="#000000">%></font></span></font><br>
         <</font><font color="#663300" face="Verdana">BR</font><font face="Verdana"><font size="+0"><font color="#0000ff">><br>
      </</font><font color="#663300">BODY</font></font>><br>
 </</font><font face="Verdana" size="+0"><font color="#663300">HTML</font><font color="#0000ff">></font></font></td>
 </tr>
 </tbody>
</table>
<p><font face="Verdana">The code color syntax is the same as you will see in
Interdev and Frontpage.  Most of the code in this page is plain HTML,
however the inside  <span style="BACKGROUND-COLOR: #ffff00">&lt;%</span>
and <span style="BACKGROUND-COLOR: #ffff00">%></span> is ASP code.  The <span style="BACKGROUND-COLOR: #ffff00">&lt;%</span>
and <span style="BACKGROUND-COLOR: #ffff00">%></span>  seperates the
HTML code from ASP code.  The server recognizes the <span style="BACKGROUND-COLOR: #ffff00">&lt;%</span>
and <span style="BACKGROUND-COLOR: #ffff00">%></span> and processes anything
contained inside.  Response.Write calls the Response Object that is part of
the ASP object model. The write part of response.write calls the write method of
that object. I will expand upon this more in the future. <font color="#0000ff"><b>TIME()</b></font>
is recognized by the script engine as a function that retrieves the current
time.</font>
<p><font face="Verdana">You just created your first dynamic website every time
it is requested it will be updated with the current time on the server. While
this is not really helpful it works well as an example.</font>
<p><font face="Verdana">See my next tutorial on the ASP object model to get a
better idea of what all ASP supports.</font></p>

