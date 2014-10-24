
Folder and their contents are listed. This will give you can an idea of what to find where. More details are available in the CPP files of the respective projects.

The projects have been built using Visual Studio 2012. The entry of the project is KylinODBC.sln. Mind the VS version.

Make sure you have the following header files, import libraries and DLLs on your system
1. SQL.H
2. SQLTYPES.H
3. SQLEXT.H
4. ODBCINST.H
5. ODBC32.LIB & ODBC32.DLL
6. ODBCCP32.LIB & ODBCCP32.DLL

You can obtain these from Microsoft site as a part of Platform SDK or MDAC kit


List of folders and description:
================================

GODBC                  - Root folder containing the workspace. All the projects are part of this single workspace (GODBC.dsw)

GODBC\TestDll         - Contains a simple ODBC client that can be used to test your driver as well as connect to any ODBC data source. 

GODBC\Common           - Contains files which have been used to define some data types.

GODBC\Driver           - Contains code for Kylin ODBC driver. Note that the entire functionality has not been implemented but is enough to get you data into most standard ODBC clients like Tableau, Excel, provided you have set up a rest server to serve the query requests. Note that the header file is a very important starting point for understanding this driver.

GODBC\Installer  	- Contains a MSI installer for kylin odbc driver(x86)

GODBC\Installer(64bit)  - Contains a MSI installer for kylin odbc driver(x64)

GODBC\doc

Trying it out
=============
Please refer to the Kylin wiki page for a tutorial.


all the best

Hongbin Ma
honma@ebay.com
