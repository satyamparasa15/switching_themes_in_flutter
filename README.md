# Switching themes in flutter apps by using provider

Nowadays, switching themes is one of the trending feature in every mobile application. By switching the themes, users can reduce their eye strain and increases mobile battery life. 

In Flutter, we can give the Theme across the app by providing the **ThemeData** to the **MaterialApp** constructor. The default theme will be shared across the app when no theme is provided. 

```
MaterialApp(
   theme: ThemeData( ... ), // declaring the theme to across the app
);
```

```ThemeData.light()``` gives the Light blue theme, which is a default theme for every flutter application.

```
MaterialApp(
  theme: ThemeData.light(),  // default the theme 
);
```
<p align="center">
 <img src="http://www.flutterant.com/wp-content/uploads/2021/02/device-2021-02-27-160619-e1614422704718.png" width="260" height="220">
</p>

```ThemeData.dark()``` gives the dark theme across the application 

```
MaterialApp(
   theme: ThemeData.dark(),  // default dark the theme 
);

```
<p align="center">
 <img src="http://www.flutterant.com/wp-content/uploads/2021/02/darkTheme-e1614441272113.png"  width="260" height="220">
</p>

Instead of using default theme colors, we can provide the own colors to primaryColor, accentColor, backgroundColor … to create a costume theme.

```
ThemeData(
          accentColor: Colors.red,
          brightness: Brightness.light,
          primaryColor: Colors.amber,
),
```
<p align="center">
 <img src="http://www.flutterant.com/wp-content/uploads/2021/02/customeTheme-e1614441970356.png"  width="260" height="220">
</p>
 
## For complete article visit [this](https://www.flutterant.com/switching-themes-in-flutter-apps-by-using-provider/)

## Output 

<p align="center">
 <img src="http://www.flutterant.com/wp-content/uploads/2021/02/ezgif.com-video-to-gif.gif"  width="360" height="800">
</p>

- [Lab: Write your first Flutter app](https://flutter.dev/docs/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://flutter.dev/docs/cookbook)

For help getting started with Flutter, view our
[online documentation](https://flutter.dev/docs), which offers tutorials,
samples, guidance on mobile development, and a full API reference.
