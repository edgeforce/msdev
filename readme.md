<script language="JSCRIPT">function checkExpand( ) { if ("" != event.srcElement.id) { var ch = event.srcElement.id + "Child"; var el = document.all[ch]; if (null != el) { el.style.display = "none" == el.style.display ? "" : "none"; if (el.style.display != "none") event.returnValue=false; } } }</script>

## Visual Studio Enterprise Edition Readme

© 1998 Microsoft Corporation. All rights reserved.

Other product and company names herein may be the trademarks of their respective owners.

_Visual Studio Readme_ includes updated information for the documentation provided with Microsoft® Visual Studio™ — Development System for Windows® and the Internet. The information in this document is more up-to-date than the information in the Help system.

### 

Contents <font size="2" face="Verdana,Arial,Helvetica" color="#000000">- Click any of the items below</font>

For installation issues pertaining to the Visual Studio 6.0 suite, see [General Installation Notes](install.htm).

> **Note**   Be sure all headings in the table of contents are expanded when you search this Readme for a topic. In this way, you will know when the search finds the topic among the TOC headings.

##### [Application Performance Explorer](# "Click to expand or collapse.")

> <div id="APEChild">
> 
> [Known Problems](# "Click to expand or collapse.")
> 
> > <div id="APEKnownProblemsChild">
> > 
> > [Configuring Remote Automation Security When Using Remote APE Components](#ConfiguringRemoteAutomationSecurityWhenUsingRemoteAPEComponents)
> > 
> > [Compatibility Issues Between the Application Performance Explorer Included with Visual Studio 6.0 and the Version Included with Visual Basic 5.0](#compatibilityissuesbetweenvs6apeandvb5ape)
> > 
> > [Adjusting Default Settings to Use APE and MTS](#AdjustingdefaultsettingstouseAPEandMTS)
> > 
> > [Application Performance Explorer Server-Side Setup May Generate Error](#ApplicationPerformanceExplorerServerSideSetup)
> > 
> > [Some Profiles May Not Run to Completion with a Non-English Digit Grouping Symbol](#SomeProfilesMayNotRuntoCompletionwithaNonEnglishDigitGroupingSymbol)
> > 
> > </div>
> 
> </div>

##### [Solution Building, Packaging, and Deployment](# "Click to expand or collapse.")

> <div id="SBPChild">
> 
> [General Notes](#SBPGeneralNotes)
> 
> [Known Problems](# "Click to expand or collapse.")
> 
> > <div id="SBPKnownProblemsChild">
> > 
> > [Microsoft FrontPage Extension Support Limited When Using Microsoft Development Environment Deployment Feature](#FrontPageExtensionsupportlimited)
> > 
> > [Microsoft Development Environment Self-Extracting Package/Installation Feature Cannot Decipher Multi-Byte Character Set (MBCS) Characters Defining the TMP Environment Variable](#CannotDecipherMultiByteCharacterSet)
> > 
> > [Deploying and Debugging Updated Visual J++ Authored COM Servers that Run in IIS](#Deployinganddebuggingupdated)
> > 
> > [External Dependency Download Limitations in Internet Explorer 4](#ExternalDependencyDownloadlimitationsinIE4)
> > 
> > [FrontPage Servers Require a 7-bit URL for Deployment](#FrontPageServersRequitea7bitURL)
> > 
> > [Build May Fail on Computers with Anti-Virus Software](#BuildMayFailonComputerswithAntiVirusSoftware)
> > 
> > [Deployed HTML Files Can Get Corrupted If Quotes Are Not Put Around Certain Values](#DeployedHTMLFilesCanGetCorrupted)
> > 
> > [Deploying Server Component Fails If the Specified Destination is a Floppy Drive](#DeployingServerComponentFails)
> > 
> > [Deployment Fails on NEC Machines Without C: Drives](#DeploymentfailsonNECmachineswithoutCdrives)
> > 
> > </div>
> 
> </div>

##### [Visual Component Manager](# "Click to expand or collapse.")

> <div id="VCMChild">
> 
> [Known Problems](# "Click to expand or collapse.")
> 
> > <div id="VCMKnownProblemsChild">
> > 
> > ["Related Files Tab (Component Properties Dialog Box)" Topic Incorrect](#RelatedFilesTab)
> > 
> > [Removing Repository 1.0 Registry Keys](#RemovingRepository10RegistryKeys)
> > 
> > [Adding Repository Tables to an Existing .mdb File](#AddingrepositorytablestoanexistingMDBfile)
> > 
> > </div>
> 
> </div>

##### [Visual Modeler](# "Click to expand or collapse.")

> <div id="VMChild">
> 
> [Known Problems](# "Click to expand or collapse.")
> 
> > <div id="VMKnownProblemsChild">
> > 
> > [Installing MSVM without Visual SourceSafe Installed](#InstallingMSVMwithoutSourceSafeInstalled)
> > 
> > [Reverse Engineering Wizard or Code Generation Wizard Appears to Stop Working During Operation](#Reverseengineeringwizardorcodegenerationwizardappearstostopworkingduringoperation)
> > 
> > [VC++ MFC Application Generated via MSVM Fails to Link](#VCMFCapplicationgeneratedviaMSVMfailstolink)
> > 
> > [Universal Naming Convention Not Supported in Rose.ini File](#UniversalNamingConventionnotsupportedinRoseinifile)
> > 
> > [Publishing a Model to Visual Component Manager Twice in a Row Without Saving](#PublishingamodeltoVisualComponentManagertwiceinarowwithoutsaving)
> > 
> > [Attempting to Import from an Invalid Repository Causes Failure](#Attemptingtoimportfromaninvalidrepositorycausesfailure)
> > 
> > </div>
> 
> </div>

##### [Visual Studio Analyzer](# "Click to expand or collapse.")

> <div id="VSAChild">
> 
> [Known Problems](# "Click to expand or collapse.")
> 
> > <div id="VSAKnownProblemsChild">
> > 
> > [Closing and Reopening a Project with a New Event Log Disables Event Recording](#ClosingandReopeningaProject)
> > 
> > [Add/Remove Columns Dialog Box Topic is Incorrect](#AddRemoveColumnsDialogBox)
> > 
> > [Delays in Visual Studio Analyzer](#DelaysinVisualStudioAnalyzer)
> > 
> > [Duplicate Instances of the Visual Studio Analyzer Server on Windows 95](#DuplicateInstancesoftheVisualStudioAnalyzerServer)
> > 
> > [Reconnecting to a Windows 95 Computer After Terminating the Local Event Concentrator Class](#ReconnectingtoaWIndows95Machine)
> > 
> > [Computer Temporarily Hangs on Reboot After Editing Local Event Concentrator Class](#MachineTemporarilyHangsOnReboot)
> > 
> > [Clicking Cancel in Response to Disk Full Error Message Can Result in Lost Event Log](#ClickingCancelinResponsetoDiskFullErrorMessage)
> > 
> > [Setting up Visual Studio Analyzer on a Backup Domain Controller](#SettingupVisualStudioAnalyzeronaBackup)
> > 
> > [Windows NT 4, SP4 Required to See Visual Studio Analyzer Events from COM](#NT4SP4RequiredtoSeeVisualStudioAnalyzerEventsfromCOM)
> > 
> > [Passing Null Values in the prgKeys and prgValues Parameters of VSAFireEvent](#PassingNullValuesintheprgKeysandprgValuesParametersofVSAFireEvent)
> > 
> > [Parameters Switched in RegisterSource Example (Visual Basic)](#ParametersSwitchedinRegisterSourceExampleVisualBasic)
> > 
> > [Incorrect Names in Sample Code](#IncorrectNamesinSampleCode)
> > 
> > [Filtering is Not Supported for All Event Fields](#FilteringisNotSupportedforAllEventFields)
> > 
> > [Using Parameters with Predefined Events in Visual Basic](#UsingParameterswithPredefinedEventsinVisualBasic)
> > 
> > [Events Might Not Display in the Block Diagram Views as They Arrive](#EventsMightNotDisplay)
> > 
> > [Visual Studio Analyzer and Microsoft Windows Terminal Server](#VisualStudioAnalyzerandMicrosoftWindowsTerminalServer)
> > 
> > </div>
> 
> [Known Limitations](#VSAKnownLimitations)
> 
> </div>

### <a name="rmmscApplicationPerformanceExplorer"></a>Application Performance Explorer

#### <a name="rmmscKnownProblemsinApplicationPerformanceExplorer"></a>Known Problems in Application Performance Explorer

##### <a name="ConfiguringRemoteAutomationSecurityWhenUsingRemoteAPEComponents"></a>Configuring Remote Automation Security When Using Remote APE Components

In order to use Remote Automation (RA) to communicate with remote APE components, you may have to configure RA security using the Remote Automation Connection Manager (Racmgr32.exe).

**To configure RA security**

1.  Start Racmgr32.exe and click the Client Access tab.
2.  Select either "Allow All Remote Creates" or "Allow Remote Creates by Key".
3.  If "Allow Remote Creates by Key" is selected, make sure the "Allow Remote Activation" check box is checked for each APE component.

RA supports the following levels of authentication:

<table>

<tbody>

<tr>

<td width="22%" valign="top">

<font link="#0000FF" vlink="#660066" size="2" face="Verdana, Arial, Helvetica, sans-serif" color="#000000">**Name**</font>

</td>

<td width="10%" valign="top">

<font link="#0000FF" vlink="#660066" size="2" face="Verdana, Arial, Helvetica, sans-serif" color="#000000">**Value**</font>

</td>

<td width="68%" valign="top">

<font link="#0000FF" vlink="#660066" size="2" face="Verdana, Arial, Helvetica, sans-serif" color="#000000">**Description**</font>

</td>

</tr>

<tr>

<td width="22%" valign="top">

<font link="#0000FF" vlink="#660066" size="2" face="Verdana, Arial, Helvetica, sans-serif" color="#000000">Default</font>

</td>

<td width="10%" valign="top">

<font link="#0000FF" vlink="#660066" size="2" face="Verdana, Arial, Helvetica, sans-serif" color="#000000">0</font>

</td>

<td width="68%" valign="top">

<font link="#0000FF" vlink="#660066" size="2" face="Verdana, Arial, Helvetica, sans-serif" color="#000000">Use Network default.</font>

</td>

</tr>

<tr>

<td width="22%" valign="top">

<font link="#0000FF" vlink="#660066" size="2" face="Verdana, Arial, Helvetica, sans-serif" color="#000000">None</font>

</td>

<td width="10%" valign="top">

<font link="#0000FF" vlink="#660066" size="2" face="Verdana, Arial, Helvetica, sans-serif" color="#000000">1</font>

</td>

<td width="68%" valign="top">

<font link="#0000FF" vlink="#660066" size="2" face="Verdana, Arial, Helvetica, sans-serif" color="#000000">No authentication.</font>

</td>

</tr>

<tr>

<td width="22%" valign="top">

<font link="#0000FF" vlink="#660066" size="2" face="Verdana, Arial, Helvetica, sans-serif" color="#000000">Connect</font>

</td>

<td width="10%" valign="top">

<font link="#0000FF" vlink="#660066" size="2" face="Verdana, Arial, Helvetica, sans-serif" color="#000000">2</font>

</td>

<td width="68%" valign="top">

<font link="#0000FF" vlink="#660066" size="2" face="Verdana, Arial, Helvetica, sans-serif" color="#000000">Connection to the server is authenticated.</font>

</td>

</tr>

<tr>

<td width="22%" valign="top">

<font link="#0000FF" vlink="#660066" size="2" face="Verdana, Arial, Helvetica, sans-serif" color="#000000">Call</font>

</td>

<td width="10%" valign="top">

<font link="#0000FF" vlink="#660066" size="2" face="Verdana, Arial, Helvetica, sans-serif" color="#000000">3</font>

</td>

<td width="68%" valign="top">

<font link="#0000FF" vlink="#660066" size="2" face="Verdana, Arial, Helvetica, sans-serif" color="#000000">Authenticates only at the beginning of each remote procedure call, when the server receives the request. Does not apply to connection-based protocol sequences (those that start with the prefix "ncacn").</font>

</td>

</tr>

<tr>

<td width="22%" valign="top">

<font link="#0000FF" vlink="#660066" size="2" face="Verdana, Arial, Helvetica, sans-serif" color="#000000">Packet</font>

</td>

<td width="10%" valign="top">

<font link="#0000FF" vlink="#660066" size="2" face="Verdana, Arial, Helvetica, sans-serif" color="#000000">4</font>

</td>

<td width="68%" valign="top">

<font link="#0000FF" vlink="#660066" size="2" face="Verdana, Arial, Helvetica, sans-serif" color="#000000">Verifies that all data received is from the expected client.</font>

</td>

</tr>

<tr>

<td width="22%" valign="top">

<font link="#0000FF" vlink="#660066" size="2" face="Verdana, Arial, Helvetica, sans-serif" color="#000000">Packet Integrity</font>

</td>

<td width="10%" valign="top">

<font link="#0000FF" vlink="#660066" size="2" face="Verdana, Arial, Helvetica, sans-serif" color="#000000">5</font>

</td>

<td width="68%" valign="top">

<font link="#0000FF" vlink="#660066" size="2" face="Verdana, Arial, Helvetica, sans-serif" color="#000000">Verifies that none of the data transferred between client and server has been modified.</font>

</td>

</tr>

<tr>

<td width="22%" valign="top">

<font link="#0000FF" vlink="#660066" size="2" face="Verdana, Arial, Helvetica, sans-serif" color="#000000">Packet Privacy</font>

</td>

<td width="10%" valign="top">

<font link="#0000FF" vlink="#660066" size="2" face="Verdana, Arial, Helvetica, sans-serif" color="#000000">6</font>

</td>

<td width="68%" valign="top">

<font link="#0000FF" vlink="#660066" size="2" face="Verdana, Arial, Helvetica, sans-serif" color="#000000">Verifies all other levels and encrypts the argument values of each remote procedure call.</font>

</td>

</tr>

</tbody>

</table>

<font link="#0000FF" vlink="#660066" size="2" face="Verdana, Arial, Helvetica, sans-serif" color="#000000">

APE profiles are initially installed with an authentication level of 1 ("None") because Windows 95 supports only that level of authentication. However, if additional security is desired, the level of authentication of a profile can be changed by modifying the profile collection file (the Aemanagr.ini file) by using a text editor such as Notepad.

Each profile in the profile collection file begins with the name of the profile within square brackets, such as [Peak performance, synchronous (CPU, Pool)]. The attributes of the profile follow, using the format <name>=<value> (such as "Task Duration=1"). To change the authentication level, change the value of the "Authentication" attribute of the selected profile and save the file.

##### <a name="compatibilityissuesbetweenvs6apeandvb5ape">Compatibility Issues Between the Application Performance Explorer (APE) that Ships with Visual Studio 6.0 and the Version that Shipped with Visual Basic 5.0</a>

There are known compatibility issues between the Application Performance Explorer (APE) that ships with Visual Studio 6.0 and the APE that shipped with Visual Basic 5.0.

**To avoid the compatibility issues, do one of the following:**

*   Before installing Visual Studio 6.0 and APE on the computer that has the version of APE shipped with VB 5, first uninstall APE from VB, and then install Visual Studio and APE.
*   If you have installed Visual Studio 6.0 and APE on the same computer that has the VB5 APE, uninstall the VB APE and then reinstall the Visual Studio APE.

##### <a name="AdjustingdefaultsettingstouseAPEandMTS">Adjusting Default Settings to Use APE and MTS</a>

After installing the APETEST database onto your SQL Server, you must adjust some of the default settings in order to use APE and MTS.

> **Note**   If you haven't already installed the APETEST database on your SQL Server, you should do that first. To learn how to install the APETEST database, search for the topic "APE Database Setup Wizard" in _MSDN Library Visual Studio 6.0_.

**To configure the APETEST database installation to work with MTS**

1.  Start Microsoft SQL Enterprise Manager.
2.  In the Databases folder, right-click the APETEST database and click Edit.
3.  Click the Options tab.
4.  Select the Truncated Log on Checkpoint check box and click OK.
5.  In the Databases folder, right-click the tempdb database and click Edit.
6.  Click Expand.
7.  In the Data Device box, select <new>.
8.  In the New Database Device dialog box, in the Name box, type tempdbData.
9.  In the Size (MB) box, type 10.
10.  Click Create Now, and finally click OK.
11.  Click Expand Now.
12.  Click Expand.
13.  In the Log Device box, select <new>.
14.  In the New Database Device dialog box, in the Name box, type tempdbLog.
15.  In the Size (MB) box, type 10.
16.  Click Create Now, and finally click OK.

**To configure the allowable number of user connections**

1.  Start Microsoft SQL Enterprise Manager.
2.  Right-click the server and click Configure.

For example, if your server is named CORONA, in the Server Manager child window, right-click CORONA and then click Configure.

4.  Click the Configuration tab.
5.  In the Configuration box, increase the number of user connections by at least 15.

> **Note**   If you are running APETEST on an established production database server, you may not have access permission to adjust the current number of user connections. In this case, you should ask your database administrator to increase the number of current user connections by at least 15 connections to support APE testing.

##### <a name="ApplicationPerformanceExplorerServerSideSetup">Application Performance Explorer Server-Side Setup May Generate Error</a>

While installing the APE server-side components, you may see an error referring to an incorrect version of OLEAUT32.dll. You may dismiss this error and continue with the installation.

However, this error message may indicate that the Microsoft Transaction Server Package was not installed correctly. To confirm that it was installed correctly, run the Transaction Server Explorer and look for all installed MTS packages on your computer. Visual Studio APE Package should be listed.

To install the package, AEMTSSVC.pkg, run the MTS Transaction Server Explorer from the Start menu and install the package to the local computer using the MTS Explorer.

##### <a name="SomeProfilesMayNotRuntoCompletionwithaNonEnglishDigitGroupingSymbol">Some Profiles May Not Run to Completion with a Non-English Digit Grouping Symbol</a>

Some of the profiles in Application Performance Explorer rely on the format of the values returned by its server components. A problem will occur if the regional settings of the computer do not specify an English Comma (",") as the digit grouping symbol.

To avoid this problem, change the digit grouping symbol to be an English Comma (",') while running the Application Performance Explorer or its server components.

**To change the digit grouping symbol**

1.  Open Control Panel.
2.  Select Regional Settings.
3.  Select the Number tab on the Regional Settings Properties window.
4.  Change the contents of the field labeled "Digit grouping symbol" to "," (without quotes).
5.  Click the OK button and close Control Panel.

### <a name="rmmscSolutionBuildPackageandDeploy"></a>Solution Building, Packaging, and Deployment

#### <a name="SBPGeneralNotes"></a>General Notes

If you are installing VJ++ of VS on NT5, you will also need to install signcode.exe from the NT5 NTSDK or the IE INETSDK for NT5, and then ensure that signcode is on the Windows path.

#### <a name="rmmscKnownProblemsinSolutionBuildPackageandDeploy"></a>Known Problems in Solution Building, Packaging, and Deployment

##### <a name="FrontPageExtensionsupportlimited"></a>Microsoft FrontPage Extension Support Limited When Using Microsoft Development Environment Deployment Feature

When using the Microsoft development environment deployment feature, you should be aware that servers which have the FrontPage acceptor installed as the default acceptor cannot support posting to URLs which contain non-7-bit characters. This is because the FrontPage acceptor is non-UTF8 compliant, and Visual Studio encodes all URLs in an encoded UTF8 format so that deployment between computers having different code pages is possible. When posting to a server which has the FrontPage acceptor installed as the default acceptor, URLs should be formed from characters in the range 0x20 through 0x7f (32 through 127).

If the server supports Posting acceptor 2.0 as the default acceptor, then this limitation does not occur.

##### <a name="CannotDecipherMultiByteCharacterSet"></a>Microsoft Development Environment Self-Extracting Package/Installation Feature Cannot Decipher Multi-Byte Character Set (MBCS) Characters Defining the TMP Environment Variable

Running a self-extracting executable created by the development environment self-extracting package/installation feature on an international operating system that allows the use of MBCS characters (for example, Japanese, Chinese, and so on) will fail if the TMP environment variable is set with MBCS characters. To solve this problem temporarily, you can change the TMP environment variable to use Single byte characters instead.

**To temporarily change the TMP variable to Single byte characters**

1.  On the target computer, create a new dir using Single byte characters: c:\temp.
2.  Open an MS-DOS window and run the command, "set TMP=c:\temp".
3.  Type "set" to verify that the TMP variable was set properly.
4.  Execute the installer from this MS-DOS window.

Any executable launched from within the MS-DOS window will use the temporarily set TMP variable until the window is closed.

##### <a name="Deployinganddebuggingupdated"></a>Deploying and Debugging Updated Visual J++ Authored COM Servers that Run in IIS

You can deploy Visual J++ authored COM servers that are called from ASP pages in Microsoft Internet Information Server (IIS). Once IIS has executed an ASP page that loads a Visual J++ authored COM server, IIS will cache the server in its internal storage. If you then deploy an updated version of the COM server to IIS and try to execute it, the new version will not be loaded, and IIS will continue to use the old version until IIS is stopped and restarted.

**To make IIS use the updated version of the COM class by restarting IIS**

1.  On the Microsoft Windows NT system, go to the Start menu and click Windows NT Option Pack. Click Personal Web Manager or Microsoft Internet Information Server.
2.  If you are using the Personal Web Manager, click Personal Web Manager, and then click Stop on the Main page.

- or -

4.  If you are using the Internet Service Manager, click Internet Service Manager, and expand the IIS node. Expand the computer's node. Select the Default Web Site and click the Stop button on the IIS toolbar.
5.  Restart IIS using the Play button.

##### <a name="ExternalDependencyDownloadlimitationsinIE4"></a>External Dependency Download Limitations in Internet Explorer 4

You can build a .cab file distribution unit with an external dependency in another .cab file distribution unit, so that both distribution units will be downloaded to the client computer when the client views the Web page that hosts the distribution unit. However, be aware that Internet Explorer 4 does not track changes to the versions of external dependencies — creating a situation in which the first .cab file is downloaded but the updated dependency is not.

For example, if you modify both distribution units, update their version numbers, and update the dependency's version number in the External Dependency tab of the Cabinet Properties dialog box, the first .cab file will be downloaded, but the second will not.

To resolve this, you might change the friendly name of the second .cab file distribution unit. This will cause the second .cab file to be downloaded again. Be aware that both versions of the .cab file distribution unit will now be installed on the client computer.

##### <a name="FrontPageServersRequitea7bitURL"></a>FrontPage Servers Require a 7-bit URL for Deployment

Microsoft Visual Studio supports deployment between computers with differing code pages. It does this by converting the URL to a tokenized UTF-8 format, so that characters outside of the range 0x20 - 0x7f can be used in URLs. Thus, if you specify the following URL on an English computer for your deployment target:

> http://myserver/ÜÖ

The characters Ü and Ö are hi-ASCII and are not necessarily supported outside of the scope of the current code page, and so the URL used internally for the purpose of deployment will be:

> http://myserver/%c3%9c%c3%96

since 0xc3 0x9c is the UTF-8 representation of the hi-ASCII character Ü, and 0xc3 0x96 is the UTF-8 representation of the hi-ASCII character Ö. The server will then "decode" this URL, and place the files in the appropriate location, so that from the client computer you can still access the deployed files by using the URL "http://myserver/ÜÖ/{name of the file}".

A problem occurs, however, because FrontPage servers do not understand tokenized URLs, and will interpret the encoded URL literally without decoding it. Thus, if you deployed a solution to a FrontPage server, and used the URL "http://myserver/ÜÖ", Microsoft Visual Studio may indicate that the files were deployed successfully, but the files will in fact be deployed to "http://myserver/%c3%9c%c3%96". You will therefore be unable to access the files, either for browsing or debugging, by using "http://myserver/ÜÖ/{name of the file}".

Because of this limitation, it is important to use only 7-bit characters in URLs when deploying to FrontPage servers; specifically, characters in the range 0x20 - 0x7f (Microsoft Visual Studio does not encode the "space" character 0x20 in deployment URLs). Hi-ASCII and MBCS characters should be avoided when deploying to FrontPage servers. Alternately, you can install Microsoft Posting Acceptor 2.0 on the server, which fully supports UTF-8 encoded URLs for deployment. See the installation documentation for instructions on how to install Posting Acceptor 2.0 onto your server from the Microsoft Visual Studio CDs.

##### <a name="BuildMayFailonComputerswithAntiVirusSoftware"></a>Build May Fail on Computers with Anti-Virus Software

If you build a setup distribution unit that contains large files on a computer that has anti-virus software installed, the build process can fail with file access errors. If this happens, try turning off the anti-virus software on that computer.

##### <a name="DeployedHTMLFilesCanGetCorrupted"></a>Deployed HTML Files Can Get Corrupted If Quotes Are Not Put Around Certain Values

If you include delimiting characters when assigning values to tag attributes in HTML files — such characters include semicolons, colons, or angle brackets — the values must be contained within quotation marks, as per W3C standards. The HTML editor in Microsoft Visual Studio does not do this, and in fact will remove quotation marks from values when an HTML file is loaded into the editor. Therefore, when the deployment engine updates the file's CODEBASE links, the deployment parser may stop reading in the value when the first standard HTML delimiter is encountered. If this happens, only part of the value will be saved back to the file before the file is actually deployed. (The deployment engine works with a temporary copy of the file, so the original is unaffected by this.)

To avoid this problem, manually put quotes around the values which contain delimiters before deploying the file. You will need to do this whenever you open the HTML file for editing in the Visual Studio HTML editor, since the editor will strip the quotation marks when the file is reopened, or the view type in the editor is changed.

##### <a name="DeployingServerComponentFails"></a>Deploying Server Component Fails If the Specified Destination is a Floppy Drive

If you specify the floppy drive of a network server computer as the destination for server component installation for deployment, the deployment will fail even if no error messages are given. This is due to an inability to create folders on the floppy drive.

To correct the problem, right-click on the Server Components service in the deployment target and select "Deployment Target Settings." In the resulting dialog box, change the installation drive and directory so that a hard drive location on the network server is specified. (Since the default location for server component installation is the C: drive, users deploying to NEC PC's will want to change that default location, as C: may specify a floppy drive on those machines.)

##### <a name="DeploymentfailsonNECmachineswithoutCdrives"></a>Deployment Fails on NEC Machines Without C: Drives

Deployment in the Microsoft development environment relies on the Microsoft Web Publishing API. The Web Publishing API attempts to create temporary files on the C: drive of a machine. On NEC machines, the C: drive is generally a floppy drive, and so if the drive does not exist, or if there is no media in the drive, then deployment will fail. There is currently no workaround for this problem.

### <a name="rmmscVisualComponentManager"></a>Visual Component Manager

#### <a name="rmmscKnownProblemsinVisualComponentManager"></a>Known Problems in Visual Component Manager

##### <a name="RelatedFilesTab"></a>"Related Files Tab (Component Properties Dialog Box)" Topic Incorrect

Visual Component Manager User Interface Reference: The topic "Related Files Tab (Component Properties Dialog Box)" incorrectly states that the tab is used to display and enter files that are related to the selected component. In fact, none of the information displayed on this tab can be modified. You can add related files to a component only when publishing or re-publishing the component. For more information, search online, with **Search titles only** selected, for "Publishing Components" in the MSDN Library Visual Studio 6.0 documentation.

##### <a name="RemovingRepository10RegistryKeys"></a>Removing Repository 1.0 Registry Keys

If you installed VCM 5.0 (previously available for web download) you will have the following Windows Registry keys setup. They were necessary for VCM 5.0 and the 1.0 version of the Repository. If you find the following Registry entries then it safe to remove them and may, in fact, improve VCM 6.0 performance.

*   HKEY_LOCAL_MACHINE\Software\Microsoft\Repository\CacheMaxAnnProps
*   HKEY_LOCAL_MACHINE\Software\Microsoft\Repository\CacheMaxObjects
*   HKEY_LOCAL_MACHINE\Software\Microsoft\Repository\CacheRelshipMaxCollections
*   HKEY_LOCAL_MACHINE\Software\Microsoft\Repository\CacheRelshipMaxRows
*   HKEY_LOCAL_MACHINE\Software\Microsoft\Repository\MaxRowCacheAge

##### <a name="AddingrepositorytablestoanexistingMDBfile"></a>Adding Repository Tables to an Existing .mdb File

If you try to open an existing .mdb file from within VCM that is not a repository database (i.e., it does not contain the repository structure/tables), you will be asked if you want the repository tables added to the database. You should not do this for normal use; the repository should generally be in a separate database. This will work, but it can take as long as 10 minutes to create the repository structure in an existing .mdb file.

To create a brand new .mdb file containing the repository structure, right-click in the folder outline, click Repository, click New, and then enter the name of the file you want to create.

### <a name="rmmscVisualModeler"></a>Visual Modeler

#### <a name="rmmscKnownProblemsinVisualModeler"></a>Known Problems in Visual Modeler

##### <a name="InstallingMSVMwithoutSourceSafeInstalled"></a>Installing MSVM without Visual SourceSafe Installed

Visual SourceSafe must be installed before MSVM is installed. Failure to do so will mean that MSVM will be unable to store models in Visual SourceSafe. If Visual SourceSafe is installed after MSVM, reinstall MSVM to enable the integration.

##### <a name="Reverseengineeringwizardorcodegenerationwizardappearstostopworkingduringoperation"></a>Reverse Engineering Wizard or Code Generation Wizard Appears to Stop Working During Operation

It has come to our attention that it is possible to load a Visual Basic Project which, although it appears to have loaded correctly, contains references to components which are not readable or are no longer installed. If this happens, and you attempt to reverse engineer or forward engineer into a VB project in this state, the MSVM components may appear to be hung as it tries to access these components, or MSVM may present a "No Visual Basic Project was selected for Reverse Engineering" message.

If this condition occurs, verify that all the classes and modules and forms in the project are readable via the VB editor. Remove references to ActiveX components which are no longer on the system.

##### <a name="VCMFCapplicationgeneratedviaMSVMfailstolink"></a>VC++ MFC Application Generated via MSVM Fails to Link

MSVM makes an assumption that all MFC classes generated via MSVM require "#include stdafx.h" in their header declaration. In some cases, this is not valid, and inclusion of the #include will cause linkage errors. Should this occur, the designer should remove the unneeded #include in the source code.

##### <a name="UniversalNamingConventionnotsupportedinRoseinifile"></a>Universal Naming Convention Not Supported in Rose.ini File

If you are an advanced user, you may want to alter the behavior of MSVM by editing the Rose.ini file directly. You should be aware that the Rose.ini functionality has not been tested against UNC, and you should use fully qualified path names should MSVM have trouble accessing files referred to in the initialization file.

##### <a name="PublishingamodeltoVisualComponentManagertwiceinarowwithoutsaving"></a>Publishing a Model to Visual Component Manager Twice in a Row Without Saving

After a model is published to Visual Component Manager, information about the MS-Repository identifiers is stored in the model. Publication, therefore, changes the model, and it needs to be saved. A second attempt to publish a model without saving between the publications will cause Visual Modeler to present an error message indicating that the model needs to be saved before publication. Save the model and republish.

##### <a name="Attemptingtoimportfromaninvalidrepositorycausesfailure"></a>Attempting to Import from an Invalid Repository Causes Failure

In the unlikely event that you attempt to import from an invalid repository database, an "Invalid Page Fault" may be declared.

### <a name="rmmscVisualStudioAnalyzer"></a>Visual Studio Analyzer

#### <a name="rmmscKnownProblemsinVisualStudioAnalyzer"></a>Known Problems in Visual Studio Analyzer

##### <a name="ClosingandReopeningaProject"></a>Closing and Reopening a Project with a New Event Log Disables Event Recording

If you create a Visual Studio Analyzer project and create an event log, then close and save the project, when you reopen the project you cannot record events into the event log. This happens because Visual Studio Analyzer seals the event logs in a project when you close the project. Once an event log is sealed, you cannot add anything to it. Saving a project does not seal the event log, so if you want to save the log and then record events into it, click File, then Save All.

##### <a name="AddRemoveColumnsDialogBox"></a>Add/Remove Columns Dialog Box Topic is Incorrect

The help topic for the Add/Remove Columns dialog box states that you can use the dialog box to customize the columns displayed in several views, including the Summary view. This is incorrect; you cannot customize the columns in the Summary view.

##### <a name="DelaysinVisualStudioAnalyzer"></a>Delays in Visual Studio Analyzer

If the system path on a Windows NT computer contains a network drive, you may see long delays in Visual Studio Analyzer when connecting to the computer, when editing a filter, or when activating a filter. To work around the problem, either remove the network drive from your system path, or use dcomcnfg.exe to change the MSVSA Local Event Concentrator Class to run as a domain user who has access to the network drive.

##### <a name="DuplicateInstancesoftheVisualStudioAnalyzerServer"></a>Duplicate Instances of the Visual Studio Analyzer Server on Windows 95

If you are not receiving events from one or more of the components on a Windows 95 computer, you might have multiple copies of the Local Event Concentrator (valec.exe) running. You can check for this on Windows 95 by pressing CTRL+ALT+DEL and reviewing the Close Program dialog box. If you do find multiple copies of valec.exe listed, it means that event collection from the computer is in an inconsistent state. You might need to reboot to collect events from components that are already running.

##### <a name="ReconnectingtoaWIndows95Machine"></a>Reconnecting to a Windows 95 Computer After Terminating the Local Event Concentrator Class

If you terminate the Local Event Concentrator (valec.exe) on a Windows 95 computer, you might not be able to reconnect to that computer. The following steps might make it possible to reconnect to the computer to collect more events without rebooting. Complete these steps in the order they appear.

> **Note**   These steps might stop event collection from the components currently running on the Windows 95 computer.

**To restart the Visual Studio Analyzer Server**

1.  On the Windows 95 Visual Studio Analyzer remote server computer, end all instances of valec.exe that are currently running. Use CTRL+ALT+DEL to view the Close Program dialog box and terminate each valec.exe task.
2.  Shut down the Visual Studio Analyzer Server by right-clicking its icon in the system tray, then clicking Exit.
3.  Shut down all event-generating components that were running when a valec.exe task was terminated.
4.  Restart the Visual Studio Analyzer Server from the Start menu.

**To reconnect to the Windows 95 Visual Studio Analyzer remote server computer**

1.  On the Visual Studio Analyzer local client computer, in the Project Explorer, click the icon representing the Windows 95 Visual Studio Analyzer remote server computer.
2.  Right-click to display the shortcut menu, then click Remove _machinename_.
3.  Click the Machines node in the Project Explorer.
4.  Right-click to display the shortcut menu, then click Connect to Machine. Type the computer's name in the Connect to Machine dialog box and click OK.
5.  Click the icon representing the computer, then right-click to display the shortcut menu and click Connect.

If you still cannot reconnect to the computer after following these steps, you will need to reboot the Visual Studio Analyzer remote server computer.

##### <a name="MachineTemporarilyHangsOnReboot"></a>Computer Temporarily Hangs on Reboot After Editing Local Event Concentrator Class

Editing the security profile for the MSVSA Local Event Concentrator class while the Local Event Concentrator class is running causes the computer to hang temporarily on reboot. Before you edit the security profile, make sure Visual Studio Analyzer is not running. You can ensure that Visual Studio Analyzer is not running by looking for the valec.exe and devenv.exe processes in the Task List; neither process should be listed.

##### <a name="ClickingCancelinResponsetoDiskFullErrorMessage"></a>Clicking Cancel in Response to Disk Full Error Message Can Result in Lost Event Log

If your local drive is full when you try to save an event log, Visual Studio Analyzer warns you of this condition by displaying an error message. The error message gives you the choice of clearing some space on your drive and clicking OK to try the save again, or clicking Cancel to dismiss the error message. If you click Cancel the event log might be deleted or left in an unreadable state.

##### <a name="SettingupVisualStudioAnalyzeronaBackup"></a>Setting up Visual Studio Analyzer on a Backup Domain Controller

When you install the Visual Studio Analyzer (either client or server side components) on to a computer running Microsoft Windows NT, a user account is created to run parts of Visual Studio Analyzer.

If you install Visual Studio Analyzer on a backup domain controller (BDC), this account cannot be created, because the backup domain controller must mirror the account structure of the primary domain controller. In this case, you will be prompted for a user account and password; you should specify the user account in the format "DomainName\UserID". The account you specify should be a domain account with the right to log on as a batch job and with sufficient privileges to collect performance counter data. See the Visual Studio Analyzer documentation for details on how to configure security. If you get the account details wrong, you will be unable to monitor the BDC, although you will be able to monitor other machines. If you wish to change the details, you should use DCOMCNFG to modify the identity properties for the MSVSA Local Event Concentrator Class.

Note that the password will not be validated by Windows NT security during setup.

##### <a name="NT4SP4RequiredtoSeeVisualStudioAnalyzerEventsfromCOM"></a>Windows NT 4, SP4 Required to See Visual Studio Analyzer Events from COM

If you want to see Visual Studio Analyzer events from COM, you need to install Windows NT 4, SP 4 on any computer where you want to track COM events using Visual Studio Analyzer. In addition, you should install Windows NT 4, SP 4 on any computer where you collect Visual Studio Analyzer events so you can benefit from performance improvements. You can download Windows NT 4, SP4 from the Web at [www.microsoft.com](http://www.microsoft.com/).

##### <a name="PassingNullValuesintheprgKeysandprgValuesParametersofVSAFireEvent"></a>Passing Null Values in the prgKeys and prgValues Parameters of VSAFireEvent

If you are using the VsaRpcl interface to generate Visual Studio Analyzer events, make sure that you pass at least one set of parameters in the prgKeys and prgValues arrays and an appropriate count in prgCount. The parameter values can be pointers to empty strings, but they cannot be null pointers. If the prgCount is zero, the VSAFireEvent method will return an error and the event you want will not be generated.

##### <a name="ParametersSwitchedinRegisterSourceExampleVisualBasic"></a>Parameters Switched in RegisterSource Example (Visual Basic)

The Visual Basic example for RegisterSource includes the following line:

mESI.RegisterSource sSourceGUID, sSourceName

The code that works is:

mESI.RegisterSource sSourceName, sSourceGUID

##### <a name="IncorrectNamesinSampleCode"></a>Incorrect Names in Sample Code

Visual Basic and Visual J++ code examples for the Visual Studio Analyzer automation interfaces (ISystemDebugEventFireAuto and ISystemDebugEventInstallAuto) contain incorrect names for the automation interfaces. If you copy any of these code examples, you'll need to use your code editor's Search and Replace function to change all instances of the following names:

_From_ MSVSAAutomatableInprocEventCreator _to_ MSVSAInprocEventCreator

_From_ MSVSAAutomatableEventSourceInstaller _to_ MSVSAEventSourceInstaller

Also, the Visual Basic example for ISystemDebugEventFireAuto invokes the wrong object. After you correct the names, find the following line:

Set mIEC = New MSVSAAutomatableEventSourceInstaller

and change the line to read:

Set mIEC = New MSVSAInprocEventCreator

##### <a name="FilteringisNotSupportedforAllEventFields"></a>Filtering is Not Supported for All Event Fields

Some event fields do not support filtering. Those fields that do not support filtering are as follows:

In addition, filtering with the Contains or DoesNotContain operator is not supported for non-string fields such as Component, Category and Event.

The fields that do support filtering are as follows:

##### <a name="UsingParameterswithPredefinedEventsinVisualBasic"></a>Using Parameters with Predefined Events in Visual Basic

The Visual Studio Analyzer predefined events accept several parameter values. These parameter values are passed to the FireEvent method in the Keys and Values arrays. The Keys array contains the parameter names, which must be strings. The Values array contains the parameter values, which can be either strings or numbers.

You can find a list of these parameter values and their definitions if you search online in MSDN Library Visual Studio 6.0 for "VSAStandardParameter". The syntax listed for VSAStandardParameter is Visual C++-specific. If you want to use any of these parameter values, you need to define constants for them. You can make this easier by creating a constant for each parameter value and saving the list of constants in a global file.

The following code defines constants for each parameter value:

##### <a name="EventsMightNotDisplay"></a>Events Might Not Display in the Block Diagram Views as They Arrive

If you set the same filter as both the recording filter and the filter you apply to views, and if you have more than one block diagram view open while you are recording events, you might notice that only the block diagram view you opened first shows blocks representing the recorded events. The other block diagram views will not show the events until you either remove the filter from those views or open a new copy of those views.

##### <a name="VisualStudioAnalyzerandMicrosoftWindowsTerminalServer"></a>Visual Studio Analyzer and Microsoft Windows Terminal Server

If you are running a component that generates Visual Studio Analyzer events from a Microsoft Windows Terminal Server client, add the following entry to the system registry of the Terminal Server console:

> HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows NT\CurrentVersion\Terminal Server\Compatibility\CLSID\{6C736D4F-CBD1-11D0-B3A2-00A0C91E29FE}

Under this key you should add the value "fSystemGlobalClass" as a DWORD and set it to 0x1.

This key will prevent multiple occurences of valec.exe running in the computer all at once. If you have too many occurences of valec.exe running, the computer eventually starts displaying an error message because it runs out of resources.

#### <a name="VSAKnownLimitations"></a>Known Limitations

Event playback is suspended when Visual Studio Analyzer does not have focus.

Make sure you stop Visual Studio Analyzer's RPC service (called the Visual Studio Analyzer RPC bridge service) before you install any software.

If you are running Visual Studio Analyzer on Windows 95, you should close the Timeline view before you import large .csv files into an event log.

If you select a large (2000 events or more) number of events in the Chart or Event List views while the Timeline view is open, you might notice a delay before the selection completes. This is normal behavior. Close the Timeline view before you select a large number of events in other views.

