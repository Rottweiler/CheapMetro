# CheapMetro
Cheap, yet effective Metro-style UI buttons

### Description
Inherited from the normal WinForms buttons that you're already used to, these cheap Metro-style UI buttons will spice up your plain-looking application

### Screenshot
<img src="http://imgur.com/E38Vjs2.png">

### Basic usage
```c#
MetroButton button1 = new MetroButton();
button1.Theme = Theme.ModernDark;

Form1.Controls.Add(button1);
```

### Themes
```c#
enum Theme
{
    DefaultRed,
    MightyBlue,
    SweetGreen,
    StubbornPurple,
    ModernDark,
    PrettyOrange
}
```
