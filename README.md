# How-to-Customize-the-Maui-OTP-Input-Appearance
This repository contains a sample explaining how to customize the appearance of the Maui OTP Input to suit different design needs

The following code example illustrate how to Customize the SfOtpInput.

XAML:

```
   <syncfusion:SfOtpInput Type="Text" Value="e3c7f4" InputBackground="AliceBlue"    Stroke="DarkBlue" Separator="|" StylingMode="Filled" Length="6"/>

```

C#:

```

var otpInput = new SfOtpInput
{
   Type = OtpInputType.Text,
   Value = "e3c7f4",
   InputBackground = Colors.LightBlue,
   Stroke = Colors.DarkBlue,
   Separator = "|",
   StylingMode = OtpInputStyle.Filled,
   Length = 6
}; 

``