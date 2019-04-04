<!-- default file list -->
*Files to look at*:

* **[MainWindow.xaml](./CS/TopCorporations/MainWindow.xaml) (VB: [MainWindow.xaml](./VB/TopCorporations/MainWindow.xaml))**
* [MainWindow.xaml.cs](./CS/TopCorporations/MainWindow.xaml.cs) (VB: [MainWindow.xaml.vb](./VB/TopCorporations/MainWindow.xaml.vb))
<!-- default file list end -->
# How to display series in several panes


This example demonstrates how to display series in several panes.


<h3>Description</h3>

To do this, add&nbsp;a new&nbsp;<a href="https://documentation.devexpress.com/#WPF/clsDevExpressXpfChartsPanetopic">Pane</a>&nbsp;object to the&nbsp;<a href="https://documentation.devexpress.com/#WPF/DevExpressXpfChartsXYDiagram2D_Panestopic">XYDiagram2D.Panes</a>&nbsp;collection, then optionally, add a new <a href="https://documentation.devexpress.com/#WPF/clsDevExpressXpfChartsSecondaryAxisX2Dtopic">SecondaryAxisX2D</a>&nbsp;object to the <a href="https://documentation.devexpress.com/#WPF/DevExpressXpfChartsXYDiagram2D_SecondaryAxesXtopic">XYDiagram2D.SecondaryAxesX</a>&nbsp;collection or a new <a href="https://documentation.devexpress.com/#WPF/clsDevExpressXpfChartsSecondaryAxisY2Dtopic">SecondaryAxisY2D</a>&nbsp;object to the <a href="https://documentation.devexpress.com/#WPF/DevExpressXpfChartsXYDiagram2D_SecondaryAxesYtopic">XYDiagram2D.SecondaryAxesY</a>&nbsp;collection. Finally, bind the pane, the X-axis and Y-axis to the series' <a href="https://documentation.devexpress.com/#WPF/DevExpressXpfChartsXYDiagram2D_SeriesPanetopic">SeriesPane</a>,&nbsp;<a href="https://documentation.devexpress.com/#WPF/DevExpressXpfChartsXYDiagram2D_SeriesAxisXtopic">SeriesAxisX</a>, <a href="https://documentation.devexpress.com/#WPF/DevExpressXpfChartsXYDiagram2D_SeriesAxisYtopic">SeriesAxisY</a>&nbsp;attached properties.

<br/>


