# Release notes

## v0.4.0

### New commands

**SharePoint Online:**

- [spo customaction list](../cmd/spo/customaction/customaction-list.md) - lists user custom actions for site or site collection [#19](https://github.com/SharePoint/office365-cli/issues/19)
- [spo site get](../cmd/spo/site/site-get.md) - gets information about the specific site collection [#114](https://github.com/SharePoint/office365-cli/issues/114)
- [spo site list](../cmd/spo/site/site-list.md) - lists modern sites of the given type [#115](https://github.com/SharePoint/office365-cli/issues/115)
- [spo site add](../cmd/spo/site/site-add.md) - creates new modern site [#116](https://github.com/SharePoint/office365-cli/issues/116)

### Changes

- added support for persisting connection [#46](https://github.com/SharePoint/office365-cli/issues/46)
- fixed authentication bug in `spo app install`, `spo app uninstall` and `spo app upgrade` commands when connected to the tenant admin site [#118](https://github.com/SharePoint/office365-cli/issues/118)
- fixed authentication bug in the `spo customaction get` command when connected to the tenant admin site [#113](https://github.com/SharePoint/office365-cli/issues/113)
- fixed bug in rendering help for commands when using the `--help` option [#104](https://github.com/SharePoint/office365-cli/issues/104)
- added detailed output to the `spo customaction get` command [#93](https://github.com/SharePoint/office365-cli/issues/93)
- improved collecting telemetry [#130](https://github.com/SharePoint/office365-cli/issues/130), [#131](https://github.com/SharePoint/office365-cli/issues/131), [#132](https://github.com/SharePoint/office365-cli/issues/132), [#133](https://github.com/SharePoint/office365-cli/issues/133)
- added support for the `skipFeatureDeployment` flag to the [spo app deploy](../cmd/spo/app/app-deploy.md) command [#134](https://github.com/SharePoint/office365-cli/issues/134)

## v0.3.0

### New commands

**SharePoint Online:**

- [spo customaction get](../cmd/spo/customaction/customaction-get.md) - gets information about the specific user custom action [#20](https://github.com/SharePoint/office365-cli/issues/20)

### Changes

- changed command output to silent [#47](https://github.com/SharePoint/office365-cli/issues/47)
- added user-agent string to all requests [#52](https://github.com/SharePoint/office365-cli/issues/52)
- refactored `spo cdn get` and `spo storageentity set` to use the `getRequestDigest` helper [#78](https://github.com/SharePoint/office365-cli/issues/78) and [#80](https://github.com/SharePoint/office365-cli/issues/80)
- added common handler for rejected OData promises [#59](https://github.com/SharePoint/office365-cli/issues/59)
- added Google Analytics code to documentation [#84](https://github.com/SharePoint/office365-cli/issues/84)
- added support for formatting command output as JSON [#48](https://github.com/SharePoint/office365-cli/issues/48)

## v0.2.0

### New commands

**SharePoint Online:**

- [spo app add](../cmd/spo/app/app-add.md) - add an app to the specified SharePoint Online app catalog [#3](https://github.com/SharePoint/office365-cli/issues/3)
- [spo app deploy](../cmd/spo/app/app-deploy.md) - deploy the specified app in the tenant app catalog [#7](https://github.com/SharePoint/office365-cli/issues/7)
- [spo app get](../cmd/spo/app/app-get.md) - get information about the specific app from the tenant app catalog [#2](https://github.com/SharePoint/office365-cli/issues/2)
- [spo app install](../cmd/spo/app/app-install.md) - install an app from the tenant app catalog in the site [#4](https://github.com/SharePoint/office365-cli/issues/4)
- [spo app list](../cmd/spo/app/app-list.md) - list apps from the tenant app catalog [#1](https://github.com/SharePoint/office365-cli/issues/1)
- [spo app retract](../cmd/spo/app/app-retract.md) - retract the specified app from the tenant app catalog [#8](https://github.com/SharePoint/office365-cli/issues/8)
- [spo app uninstall](../cmd/spo/app/app-uninstall.md) - uninstall an app from the site [#5](https://github.com/SharePoint/office365-cli/issues/5)
- [spo app upgrade](../cmd/spo/app/app-upgrade.md) - upgrade app in the specified site [#6](https://github.com/SharePoint/office365-cli/issues/6)

## v0.1.1

### Changes

- Fixed bug in resolving command paths on Windows

## v0.1.0

Initial release.

### New commands

**SharePoint Online:**

- [spo cdn get](../cmd/spo/cdn/cdn-get.md) - get Office 365 CDN status
- [spo cdn origin list](../cmd/spo/cdn/cdn-origin-list.md) - list Office 365 CDN origins
- [spo cdn origin remove](../cmd/spo/cdn/cdn-origin-remove.md) - remove Office 365 CDN origin
- [spo cdn origin set](../cmd/spo/cdn/cdn-origin-set.md) - set Office 365 CDN origin
- [spo cdn policy list](../cmd/spo/cdn/cdn-policy-list.md) - list Office 365 CDN policies
- [spo cdn policy set](../cmd/spo/cdn/cdn-policy-set.md) - set Office 365 CDN policy
- [spo cdn set](../cmd/spo/cdn/cdn-set.md) - enable/disable Office 365 CDN
- [spo connect](../cmd/spo/connect.md) - connect to a SharePoint Online site
- [spo disconnect](../cmd/spo/disconnect.md) - disconnect from SharePoint
- [spo status](../cmd/spo/status.md) - show SharePoint Online connection status
- [spo storageentity get](../cmd/spo/storageentity/storageentity-get.md) - get value of a tenant property
- [spo storageentity list](../cmd/spo/storageentity/storageentity-list.md) - list all tenant properties
- [spo storageentity remove](../cmd/spo/storageentity/storageentity-remove.md) - remove a tenant property
- [spo storageentity set](../cmd/spo/storageentity/storageentity-set.md) - set a tenant property