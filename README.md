Get-iOS-Model
=============

Get the iOS model using the hw.machine string
*******
Will keep this updated as new devices are available.

Updates:<br/>
10/20/2014 - added iPad Air 2 & iPad mini 3<br/>
09/17/2014 - added iPhone 6 and 6 Plus<br/>
01/08/2014 - added iPad Mini Retina and iPad Air.
*******

Sample
-------

```
Console.WriteLine(new iOSHardware().GetModel("iPhone5,3"));
```

Result: "iPhone 5C GSM"

*******
Get device hardware string using Xamarin.iOS
-------

```
Console.WriteLine(Xamarin.iOS.DeviceHardware.Version);
Console.WriteLine(new iOSHardware().GetModel(Xamarin.iOS.DeviceHardware.Version));
```

*******
####Run Sample:
http://executify.com/10027/
