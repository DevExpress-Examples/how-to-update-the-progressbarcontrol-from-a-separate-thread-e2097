<!-- default file list -->
*Files to look at*:

* [BusyForm.cs](./CS/Busy/BusyForm.cs) (VB: [BusyForm.vb](./VB/Busy/BusyForm.vb))
* [Program.cs](./CS/Busy/Program.cs) (VB: [Program.vb](./VB/Busy/Program.vb))
* [ProgressControl.cs](./CS/Busy/ProgressControl.cs) (VB: [ProgressControl.vb](./VB/Busy/ProgressControl.vb))
<!-- default file list end -->
# How to update the ProgressBarControl from a separate thread


<p>Very often when you perform any operation in a background thread, it can be very useful to indicate to an end-user the current state of progress. To display the progress, the ProgressBarControl can be used. This example illustrates how to perform a file copy operation in a background thread, and display the progress on a main form.</p>

<br/>


