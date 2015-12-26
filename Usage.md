How to use the phoenix-control-library...

# Introduction #

In order to use the control, you'll have to add it through XAML. Add the following line to the top of your XAML code in the Window or Page root:

<pre>
xmlns:pcl="clr-namespace:PhoenixControlLib;assembly=PhoenixControlLib"<br>
</pre>


# NumericSpinnerControl.cs #

There are four primary properties for the numeric spinner control. Here is example usage:

<pre>
<pcl:NumericSpinnerControl Width="100" Minimum="0" Value="1" IncrementValue="0.5"/><br>
</pre>

## Properties ##

**Minimum** is the minimum value displayed by the spinner.

**Maximum** is the maximum value displayed by the spinner.

**Value** is the current value displayed by the spinner.

**IncrementValue** is the amount the up/down arrows add or subtract from the value.

## Notes ##

None.

# ToggleRadioButton.cs #

## Notes ##
This is simply a custom control sub-classing from radio button. It behaves in exactly the same way as radio button except you can toggle each button on off and place the group in an untoggled state (once you select a radio button you cannot uncheck all the items in a group).

For information on radio buttons, visit the [MSDN page](http://msdn.microsoft.com/en-us/library/system.windows.controls.radiobutton.aspx).