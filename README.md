## Unit Test

The unit test scripts are under ./__test__ folder and tested functions are under./src/store.

The tested functions are:
* feed actions:
  - getFeedDetailsRequest
  - getFeedDetailsSuccess
  - getPluginInstanceListRequest
  - getPluginInstanceListSuccess
  - destroyFeed
* message actions:
  - handleMessage
  - dismissMessage
  - handleConfirmation
  - dismissConfirmation
* plugin actions:
  - getPluginDescendantsRequest
  -	getPluginDescendantsSuccess
  -	getPluginDetailsRequest
  -	getPluginDetailsSuccess
  -	getPluginParametersRequest
  -	getPluginParametersSuccess
  -	getPluginFilesRequest
  -	getPluginFilesSuccess
* ui actions:
  - uiOnBeforeRequest
  - uiOnCompleteRequest
  - onDropdownSelect
  - onKebabDropdownSelect
  - onSidebarToggle
  - setSidebarActive
* user actions:
  - getAuthToken
  - getAuthTokenSuccess
  - setUserLogout
