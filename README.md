# awesome-ideas
Awesome programming ideas and inspiration from all around the world of languages and patterns.

![](https://imgs.xkcd.com/comics/standards.png)

## Terminal Strikes Back
Catching up with hundreds of changes in popular UI libraries is time consuming, meanwhile there are no changes to Terminal UI. A Terminal UI GUI library, similar to DatGUI but even sturdier, fully backwards compatible with Terminals.

## Notes (references)
----
- Rough Notes
- Air File Object
- Propel ORM
- Joomla as Application Framework
- PHP Cake Application Structure
- Symphony Application Structure
- ZendFramework Application Structure
- ezcomponents component set
- Java Portlet Specification
- Prado Framework
- RedBean ORM
- Phonegap
- Apple Dashboard
- Siri
- Alfresco, Zimbra, LifeRay

## IDEA: Portable API

From sl4a API wrapper

```
  rhino
  load("/sdcard/com.googlecode.rhinoforandroid/extras/rhino/android.js");
  var droid = new Android();
  droid.makeToast("Hello, Android!");

  beanshell
  source("/sdcard/com.googlecode.bshforandroid/extras/bsh/android.bsh");
  droid = Android();
  droid.call("makeToast", "Hello, Android!");

  perl
  use Android;
  my $a = Android->new();
  $a->makeToast("Hello, Android!");
```

And in text:

```
droid makeToast Hello, Android!

```

See https://github.com/fantasyui-com/conversational-ui for conclusion

