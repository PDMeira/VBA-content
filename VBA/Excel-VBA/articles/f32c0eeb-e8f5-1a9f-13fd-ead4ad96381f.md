
# ODBCConnection.SourceDataFile Property (Excel)

Returns or sets a  **String** indicating the source data file for an ODBC connection. Read/write.


## Syntax

 _expression_ . **SourceDataFile**

 _expression_ A variable that represents an **ODBCConnection** object.


## Remarks

For file-based data sources (for example, Access) the  **SourceDataFile** property contains a fully qualified path to the source data file. It is null for server-based data sources (for example, SQL Server). The **SourceDataFile** property is set to null if the **[Connection](2fcd1043-b088-cfde-9853-4a20da20be26.md)** property is changed programmatically.


## See also


#### Concepts


[ODBCConnection Object](b880ebec-15a4-5a3d-ef02-db73106db9c9.md)
