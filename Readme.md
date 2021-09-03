<!-- default badges list -->
![](https://img.shields.io/endpoint?url=https://codecentral.devexpress.com/api/v1/VersionRange/128612638/21.1.5%2B)
[![](https://img.shields.io/badge/Open_in_DevExpress_Support_Center-FF7200?style=flat-square&logo=DevExpress&logoColor=white)](https://supportcenter.devexpress.com/ticket/details/T461395)
[![](https://img.shields.io/badge/📖_How_to_use_DevExpress_Examples-e9f6fc?style=flat-square)](https://docs.devexpress.com/GeneralInformation/403183)
<!-- default badges end -->
<!-- default file list -->
*Files to look at*:

* [MainWindow.xaml](./CS/WpfSpreadsheet_DataBinding/MainWindow.xaml) (VB: [MainWindow.xaml](./VB/WpfSpreadsheet_DataBinding/MainWindow.xaml))
* [MainWindow.xaml.cs](./CS/WpfSpreadsheet_DataBinding/MainWindow.xaml.cs) (VB: [MainWindow.xaml.vb](./VB/WpfSpreadsheet_DataBinding/MainWindow.xaml.vb))
<!-- default file list end -->
# How to bind a grid control to the worksheet data (WPF Spreadsheet)


<p>This example demonstrates how to bind the <a href="https://documentation.devexpress.com/#WPF/CustomDocument6084">Grid Control</a> to the <a href="https://documentation.devexpress.com/#WPF/CustomDocument16118">Spreadsheet</a> data. To do this, use the <a href="http://documentation.devexpress.com/#CoreLibraries/DevExpressSpreadsheetRange_GetDataSourcetopic">Range.GetDataSource</a> method to create a data source object from a specific cell range in a worksheet, and then assign it to the <a href="https://documentation.devexpress.com/#WPF/DevExpressXpfGridDataControlBase_ItemsSourcetopic">GridControl.ItemsSource</a> property. The two-way binding is supported: any changes to worksheet (such as editing values, inserting and deleting rows, sorting and filtering) are immediately propagated to the Data Grid, and editing data in the grid is reflected in the spreadsheet.</p>

<br/>


