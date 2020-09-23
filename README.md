<div align="center">

## Visual WebGui


</div>

### Description

Introduction to a new development concept for building web application by using server side WinForms like API to create complex applications like OWA with out DHTML/JS/Web knowledge/
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Guy Peled](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/guy-peled.md)
**Level**          |Beginner
**User Rating**    |5.0 (10 globes from 2 users)
**Compatibility**  |C\#, ASP\.NET
**Category**       |[Internet/ Browsers/ HTML](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/internet-browsers-html__10-9.md)
**World**          |[\.Net \(C\#, VB\.net\)](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/net-c-vb-net.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/guy-peled-visual-webgui__10-4712/archive/master.zip)





### Source Code

```
Visual WebGui is not just another AJAX framework but rather a different approach to web application development, specially designed to simplify building highly complex applications like Outlook Web Access (OWA). Visual WebGui makes it possible for developers to create applications that were previously developed only by the "big guys". While web development environments such as ASP.NET and JSP have made huge strides in creating a rich environment for developing web applications, they have always targeted a very wide range of applications from content rich sites to OWA like applications. By doing so, they forced a compromise that was very painful for applications developers. Concepts like pages, html, requests and responses, which originated from the historical evolution of web development, are not really suitable for developing applications.
Visual WebGui uses a proven application development toolset that was designed for application development from the outset. Visual WebGui's methodology - Winforms over Web (WOW) - originates from environments like MFC and the popular Visual Basic environment.
Visual WebGui is a unique approach for developing AJAX applications, using a server side WinForms API coupled with a highly optimized, pure AJAX client. The server side resembles WinForms both in design time and runtime. Design time behavior of Visual WebGui forms and user controls exposes a design surface identical to that of WinForms, allowing developers to design web applications with tools and methodologies taken from desktop development.
Leveraging the WinForms paradigm provides web developers with a highly productive AJAX framework that in development time can only be compared to that of RAD tools. WinForms' layout mechanism including docking and anchoring is fully supported both in design time and runtime, replacing the HTML table based layout mechanism. Visual WebGui's support of docking, anchoring, TableLayout and FlowLayout provides developers with powerful design tools that dramatically reduce development time.
WebGui's "Empty Client" approach enables a true web based event driven environment that simplifies development leaving all the web plumbing to the Visual WebGui server. Visual WebGui's unique communication and presentation mechanism enables highly granular, incremental updates reducing bandwidth usage by an order of magnitude. Visual WebGui automatically optimizes post-backs to reduce server roundtrips by analyzing the backend code. While most of the optimization mechanism is done automatically, there are ways to help Visual WebGui optimize communication even more by following a few guidelines.
Visual WebGui is fully integrated into Visual Studio making it a natural extension to the .NET framework. Full compliancy with the .NET framework and the WinForms API makes it possible for developers to start developing almost immediately using their existing knowledge and tools. Visual WebGui empowers developers with development techniques of experienced web developers, leaving Visual WebGui developers to focus on their goals which in most cases do not include writing UI frameworks.
Visual WebGui introduces an extension to the WinForms API object module which bridges the gap between web development and desktop development. The extension enables components to expose gateways which are virtual URL's that are handled by context-aware components within the WinForms object module. Implementing IGatewayControl interface that has one method that returns an object implementing IGatewayHandler provides a mechanism similar to that of IHTTPHandlerFactory and IHTTPHandler of .NET. This feature can be used to download files, printing, interact with embedded elements such as Flash objects and much more.
Visual WebGui presentation implementation is XSL based enabling developers to customize presentation to their needs. Visual WebGui provides themes support enabling developers to override Visual WebGui's default theme and provides a flavor support which enables developers to define CSS variations on the same theme. Applications developed with the current theme will be able to leverage new themes and flavors without code modifications.
Visual WebGui is available with various licenses including a free license for non commercial usage.
Visual WebGui developer guide lines:
Visual WebGui automatically detects components that need to be updated, updating the most granular change possible for the updated component. By updating only required components users can optimize application performance and bandwidth usage. For example updating a list view item should be preferred on updating the full list view as Visual WebGui can send only the changed list view item and redraw only that item.
Visual WebGui automatically queues unhandled events for post back optimization. Developers should remove unused event handlers or consider using their queued version. By definition every event handler that does not interact with the user is a potential candidate to be attached to the queued version of the event.
Visual WebGui modal dialogs are only modal on the client side as opposed to WinForms implementation and dialog results should be retrieved by attaching to the closed event.
Visual WebGui can have more than one root form as opposed to WinForms implementation and every root form is mapped to a virtual WGX URL in the application configuration file.
Visual WebGui links:
Visual WebGui website
http://www.visualwebgui.com
Visual WebGui explorer sample video (download codec here if you don't see the movie)
http://www.visualwebgui.com/Portals/0/Downloads/WebGui.Net.Videos.Explorer.Eng.avi
Visual WebGui demo and code
http://www.visualwebgui.com/Technology/Demos/tabid/117/Default.aspx
Visual WebGui download page
http://www.visualwebgui.com/Default.aspx?tabid=110
My blog
http://www.geekswithblogs.com/gizmox
```

