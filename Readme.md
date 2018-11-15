<!-- default file list -->
*Files to look at*:

* [Default.aspx](./CS/ASPxPivotGrid_DisplayUnderlyingRecords/Default.aspx) (VB: [Default.aspx](./VB/ASPxPivotGrid_DisplayUnderlyingRecords/Default.aspx))
* [Default.aspx.cs](./CS/ASPxPivotGrid_DisplayUnderlyingRecords/Default.aspx.cs) (VB: [Default.aspx](./VB/ASPxPivotGrid_DisplayUnderlyingRecords/Default.aspx))
<!-- default file list end -->
# How to Display Underlying Records


<p>The ASPxPivotGrid includes the drill-down capability, which enables you to retrieve a list of records that were used to calculate a particular summary. </p><p>To obtain drill-down data, use the pivot grid's CreateDrillDownDataSource method. Its parameters completely identify a summary cell. </p><p>In this example, an end-user can view records from the control's underlying data source, associated with a summary cell, by clicking on it. The obtained data is displayed by the ASPxGridView within a popup window.</p>

<br/>


