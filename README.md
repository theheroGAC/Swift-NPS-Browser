# Swift NPS Browser
>A macOS version of NPS Browser

I was sick of having to use Bootcamp just for this one app. So I decided to make a clone of my own as a way to give back to the community.

## Usage
* Set URLs and extraction preferences in the Preferences window
* Click the refresh button in the corner of the window to pull fresh data from the server. 

Note that the data from the server is stored until you decide to refresh the database.

## Building
This app uses CocoaPods, to install the dependencies:

```
pod install
```

Then build using XCode

## Thanks
* [pkg2zip][]
* [AlamoFire][]
* [Promises][]
* [Queuer][]

[pkg2zip]: https://github.com/mmozeiko/pkg2zip
[AlamoFire]:https://github.com/Alamofire/Alamofire
[Promises]:https://github.com/google/promises
[Queuer]:https://github.com/FabrizioBrancati/Queuer
