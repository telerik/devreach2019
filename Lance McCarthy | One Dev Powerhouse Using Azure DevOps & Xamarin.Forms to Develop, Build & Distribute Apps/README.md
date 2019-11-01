# One Dev Powerhouse

You can find the full source code, include Azure DevOps YAML pipelines, in this GitHub repository [github.com/LanceMcCarthy/DevReachCompanion](https://github.com/LanceMcCarthy/DevReachCompanion).

Every time a new build rolls out, the source code is immediately updated and the repo kept in sync. For your convenience, here's the README with the current LIVE statuses!

## Azure DevOps
You will find the YAML for the build pipeline in the repo's `azure-pipelines.yml` file. These badges represent the live status of each pipeline, including release rollouts. Remember that build and release pipelines are **public**! You can click on the build badge to explore the build and release pipelines in Azure directly.

#### Build Pipelines

| Branch | Status   |
|--------|----------|
| Dev  | [![Dev](https://dev.azure.com/lance/DevReach%20Companion/_apis/build/status/Complete%20YAML%20Build?branchName=dev)](https://dev.azure.com/lance/DevReach%20Companion/_build/latest?definitionId=37&branchName=dev) |
| Master | [![Master](https://dev.azure.com/lance/DevReach%20Companion/_apis/build/status/Complete%20YAML%20Build?branchName=master)](https://dev.azure.com/lance/DevReach%20Companion/_build/latest?definitionId=37&branchName=master)   |


#### Release Pipelines

The


| Platform                | AppCenter              |  Beta  | Production |
|-------------------------|------------------------|--------|------------|
| Android | ![AppCenter Android](https://vsrm.dev.azure.com/lance/_apis/public/Release/badge/7dd01a63-05a2-436b-b30a-3a2ddc2327bb/2/4) | ![Google Play Beta](https://vsrm.dev.azure.com/lance/_apis/public/Release/badge/7dd01a63-05a2-436b-b30a-3a2ddc2327bb/2/8) | ![Promote Beta to Production](https://vsrm.dev.azure.com/lance/_apis/public/Release/badge/7dd01a63-05a2-436b-b30a-3a2ddc2327bb/2/10) |
| iOS | ![AppCenter iOS](https://vsrm.dev.azure.com/lance/_apis/public/Release/badge/7dd01a63-05a2-436b-b30a-3a2ddc2327bb/2/2) | ![TestFlight](https://vsrm.dev.azure.com/lance/_apis/public/Release/badge/7dd01a63-05a2-436b-b30a-3a2ddc2327bb/2/13) | ![AppStore](https://vsrm.dev.azure.com/lance/_apis/public/Release/badge/7dd01a63-05a2-436b-b30a-3a2ddc2327bb/2/14) |
| UWP | ![DevCenter Beta Flight](https://vsrm.dev.azure.com/lance/_apis/public/Release/badge/7dd01a63-05a2-436b-b30a-3a2ddc2327bb/2/5) | ![DevCenter Beta](https://vsrm.dev.azure.com/lance/_apis/public/Release/badge/7dd01a63-05a2-436b-b30a-3a2ddc2327bb/2/11) | ![DevCenter Release](https://vsrm.dev.azure.com/lance/_apis/public/Release/badge/7dd01a63-05a2-436b-b30a-3a2ddc2327bb/2/12) |
| Web API | n/a | n/a | ![Azure App Service](https://vsrm.dev.azure.com/lance/_apis/public/Release/badge/7dd01a63-05a2-436b-b30a-3a2ddc2327bb/2/6) |
| GitHub                  | n/a | n/a | ![GitHub](https://vsrm.dev.azure.com/lance/_apis/public/Release/badge/7dd01a63-05a2-436b-b30a-3a2ddc2327bb/2/26) |

The final destination of the release pipelines can be seen in the following live app store badges

| Windows 10 | Google Play  |  Appl App Store  |
|---|---| ---|
| <a href='//www.microsoft.com/store/apps/9MZNMK3MPV8R?cid=storebadge&ocid=badge'><img src='https://assets.windowsphone.com/85864462-9c82-451e-9355-a3d5f874397a/English_get-it-from-MS_InvariantCulture_Default.png' alt='Get it on Microsoft Store' width='150'/></a> | <a href='http://play.google.com/store/apps/details?id=com.LancelotSoftware.DevReachCompanion'><img alt='Get it on Google Play' src='https://play.google.com/intl/en_us/badges/static/images/badges/en_badge_web_generic.png' width='150'/></a> | <a href='https://apps.apple.com/us/app/devreach-companion/id1483349010?ls=1'><img alt='Get it on App Store' src='https://linkmaker.itunes.apple.com/en-us/badge-lrg.svg?kind=iossoftware' width='150'/></a> |

## Code

There are 7 projects in the solution of the source code:

* **Web API**
  * ASP.NET Web API
  * Unit Tests
* **Xamarin.Forms**
  * UWP
  * Xamarin.iOS
  * Xamarin.Android
  * .NET Standard 2.0 Class Library

