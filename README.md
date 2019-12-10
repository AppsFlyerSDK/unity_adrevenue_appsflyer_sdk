<img src="https://www.appsflyer.com/wp-content/uploads/2016/11/logo-1.svg"  width="450">

# unity_adrevenue_appsflyer_sdk

🛠 In order for us to provide optimal support, we would kindly ask you to submit any issues to support@appsflyer.com

*When submitting an issue please specify your AppsFlyer sign-up (account) email , your app ID , production steps, logs, code snippets and any additional relevant information.*

## Table of content

- [Installation](#installation)
- [Initialization](#init-sdk)
- [API](#api) 

## <a id="installation"> 📲 Installation

1. Clone / download this repository.
2. [Import](https://docs.unity3d.com/Manual/AssetPackages.html) AppsFlyer-AdRevenue.unitypackage and AppsFlyer-AdRevenue-MoPub.unitypackage into your Unity project.
    * Go to Assets >> Import Package >> Custom Package
    * Select AppsFlyer-AdRevenue.unitypackage and AppsFlyer-AdRevenue-MoPub.unitypackage.

**Note:** You must have the AppsFlyer SDK already in your project. In addition, make sure to init AppsFlyer SDK before AppsFlyerAdRevenue.

## <a id="init-sdk"> 🚀 Initialization

```c#
using AppsFlyerSDK;

public class AppsFlyerObjectScript : MonoBehaviour
{
  void Start()
  {
  	AppsFlyerAdRevenue.start(AppsFlyerAdRevenueType.MoPub);
  	/* AppsFlyerAdRevenue.setIsDebug(true); */
  }
}
```

## <a id="api"> 📑 API
  Check out the api [here](/docs/api.md).


**Note:** AppsFlyerAdRevenue currently supports iOS AdRevenue with MoPub only.