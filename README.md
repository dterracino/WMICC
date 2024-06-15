# WMICC
The WMI Code Creator tool generates code that uses WMI to obtain management information or perform management tasks. You can use the tool to learn how to manage computers using WMI scripting and WMI .NET. The tool generates code that runs on the local computer, a remote computer, or a group of remote computers based on your selection from the Target Computer menu on the tool. You can also execute the generated code directly from the tool.

The tool is meant to help IT Professionals quickly create management scripts and to help developers learn WMI scripting and WMI .NET. The tool helps take the complexity out of writing code that uses WMI and helps developers and IT Professionals understand how powerful and useful WMI can be for managing computers.

Using the tool, you can query for management information such as the name and version of an operating system, how much free disk space is on a hard drive, or the state of a service. You can also use the tool to execute a method from a WMI class to perform a management task. For example, you can create code that executes the Create method of the Win32_Process class to create a new process such as Notepad or another executable. The tool also allows you to generate code to receive event notifications using WMI. For example, you can select to receive an event every time a process is started or stopped, or when a computer shuts down.

The tool also allows you to browse through the available WMI namespaces and classes on the local computer to find their descriptions, properties, methods, and qualifiers.

The code that creates the tool is also included in the download. The tool was created using WMI .NET, and the code for the tool can help developers understand how WMI .NET is used to create applications and manage information. Be sure to read the end-user license agreement that is included in the download.

# AVAILABILITY
Remarkably, even though this thing has been removed from Microsoft's site (like so many of their other tools), and it's nowhere to be found through searches, it was still available via Chocolatey:

https://community.chocolatey.org/packages/wmicc

# FUTURE PLANS
The original source code was built in a text editor rather than in Visual Studio, so there is _lot_ of refactoring to do to bring it up to what I'd at least consider a reasonably modern Windows Forms app. The app still has its uses, so my plan is to move it from the version of .NET it currently is (which looks like 1.1 based on the coding) and bring it at least up to .NET6, then we'll see what happens.

Hey, you gotta keep yourself busy, right? ;)
