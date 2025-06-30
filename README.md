# How-to-Customize-the-Maui-OTP-Input-Appearance
This repository contains detailed samples and explanations on how to customize the appearance of the Maui OTP (One-Time Password) Input to suit a variety of different design needs. By applying unique styles to the OTP input control, developers can align their UI elements with their application's overall aesthetic and branding guidelines, improving user engagement and interface consistency. Customization options include changing the background color, text styling, and separator configuration, allowing for a personalized and visually appealing user experience.

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