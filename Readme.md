<!-- default badges list -->
![](https://img.shields.io/endpoint?url=https://codecentral.devexpress.com/api/v1/VersionRange/128612638/24.2.1%2B)
[![](https://img.shields.io/badge/Open_in_DevExpress_Support_Center-FF7200?style=flat-square&logo=DevExpress&logoColor=white)](https://supportcenter.devexpress.com/ticket/details/T461395)
[![](https://img.shields.io/badge/📖_How_to_use_DevExpress_Examples-e9f6fc?style=flat-square)](https://docs.devexpress.com/GeneralInformation/403183)
[![](https://img.shields.io/badge/💬_Leave_Feedback-feecdd?style=flat-square)](#does-this-example-address-your-development-requirementsobjectives)
<!-- default badges end -->

# Spreadsheet for WPF - Bind a GridControl to the Worksheet Data

This example demonstrates how to bind the [Grid Control](https://docs.devexpress.com/WPF/6084/controls-and-libraries/data-grid) to the [Spreadsheet](https://docs.devexpress.com/WPF/16118/controls-and-libraries/spreadsheet) data.

Use the [Range.GetDataSource](https://docs.devexpress.com/OfficeFileAPI/DevExpress.Spreadsheet.CellRange.GetDataSource.overloads) method to create a data source object from a specific cell range in a worksheet, and then assign it to the [GridControl.ItemsSource](https://docs.devexpress.com/WPF/DevExpress.Xpf.Grid.DataControlBase.ItemsSource) property. The two-way binding is supported: any changes to worksheet (such as editing values, inserting and deleting rows, sorting and filtering) are immediately propagated to the Data Grid, and editing data in the grid is reflected in the spreadsheet.

## Files to Review

* [MainWindow.xaml](./CS/WpfSpreadsheet_DataBinding/MainWindow.xaml) (VB: [MainWindow.xaml](./VB/WpfSpreadsheet_DataBinding/MainWindow.xaml))
* [MainWindow.xaml.cs](./CS/WpfSpreadsheet_DataBinding/MainWindow.xaml.cs) (VB: [MainWindow.xaml.vb](./VB/WpfSpreadsheet_DataBinding/MainWindow.xaml.vb))

## Documentation

* [Data Binding in Spreadsheet for WPF](https://docs.devexpress.com/WPF/117685/controls-and-libraries/spreadsheet/data-binding)
<!-- feedback -->
## Does this example address your development requirements/objectives?

[<img src="https://www.devexpress.com/support/examples/i/yes-button.svg"/>](https://www.devexpress.com/support/examples/survey.xml?utm_source=github&utm_campaign=wpf-spreadsheet-bind-grid-control-to-worksheet-data&~~~was_helpful=yes) [<img src="https://www.devexpress.com/support/examples/i/no-button.svg"/>](https://www.devexpress.com/support/examples/survey.xml?utm_source=github&utm_campaign=wpf-spreadsheet-bind-grid-control-to-worksheet-data&~~~was_helpful=no)

(you will be redirected to DevExpress.com to submit your response)
<!-- feedback end -->
