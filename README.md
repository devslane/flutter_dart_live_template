# flutter_dart_live_template
A collection of my personal [Flutter](https://flutter.io) / [Dart](https://www.dartlang.org) [Live Templates](https://www.jetbrains.com/help/idea/using-live-templates.html) which I use. 


## To import live template configuration into your Intellij / WebStorm / Android Studio: 
1. [Download the jar](https://github.com/devslane/flutter_dart_live_template/raw/master/flutter_built_value_template.jar).
2. Open Intellij / WebStorm / Android Studio
3. On the **File** menu, click **Import Settings**.
4. Specify the path to the JAR file with the exported live template configuration
5. In the **Import Settings** dialog box, select the **Live templates** check box and click **OK**.
6. After restarting IntelliJ IDEA, you will see the imported live templates on the [Live Templates][1] page of the [Settings / Preferences Dialog](https://www.jetbrains.com/help/idea/settings-preferences-dialog.html).
7. If everything worked well you should see something like that in your [Live Templates][1]
![Screenshot Live Templates](./img/live_template.png)

## Live Templates in Action 🎬

### buitvaldep
The [Live Templates][1] `buitvaldep` adds all the needed dart packages to your project. Do not forgett to add the **dev_dependencies** with . Right now the version are code in the [Live Template][1], I will try to make it dynamic with a request to [pub.dartlang.org][2] to get the latest version.

![Live Template builtvaldep](./gif/builtvaldep.gif)

### builtvaldevdep
The [Live Templates][1] `builtvaldevdep` adds all the needed **dev_dependencies** to your project.

![Live Template builtvaldevdep](./gif/builtvaldevdep.gif)

### builtvalf
The [Live Templates][1] `builtvalf` creates a Built Value based on your file name.

![Live Template builtvalf](./gif/builtvalf.gif)

### builtvalfs
The [Live Templates][1] `builtvalfs` is just an varian of `builtvalf` which adds the line of code for the serializer to the generated Built Value.

![Screenshot Live Templates builtvalfs](./img/builtvalfs.png)

### builtval
The [Live Templates][1] `builtval` just adds a Built Value to the file. 

![Screenshot Live Templates builtval](./gif/builtval.gif)


### serjson
The [Live Templates][1] `serjson` generates the boilerplate code for a an serializer with the StandartJsonPlung.

![Screenshot Live Templates serjson](./gif/serjson.gif)



# Todos ✅ / Ideas 💡
- [ ] Get the newest version for the **builtvaldevdep** sniped live from [pub.dartlang.org][2]

- [ ] Make renaming of **Built Value** easier



# Disclaimer Flutter 
The two [Live Templates][1]  (**snk** & **stmbld**) in the flutter section, are just my implementation of the snippes from [Filip Hracek](https://github.com/filiph) which you can see at the flutter talk [**Build   reactive mobile apps with Flutter** at Google I/O](https://youtu.be/RS36gBEp8OI?t=24m16s) or in [The Boring Flutter Development Show, Ep. 4](https://youtu.be/fahC3ky_zW0?t=56m55s)

![Screenhot flutter Live Templates](./img/flutter_live_templates.png)

[1]: https://www.jetbrains.com/help/idea/settings-live-templates.html
[2]: https://pub.dartlang.org/
