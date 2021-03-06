# ProfileCreator 0.1 (Beta 2)

Please report any bugs, feature requests or suggestions as an issue to this repository.

### New Preference

* ShowUserApprovedKeys - Show/Hide payloads and keys that require User Approved- or DEP enrollment. (macOS)

### New Payloads

* com.apple.proxy.http.global (iOS, tvOS)
* com.apple.dnsProxy.managed (iOS)
* com.apple.SoftwareUpdate (macOS)
* com.apple.MCX.TimeMachine (macOS)
* com.apple.xsan (macOS)
* com.apple.networkusagerules (iOS)
* com.apple.systemmigration (macOS)
* com.apple.MCX (macOS) (Only Energy Saver settings)

### Updated Payloads

##### com.apple.smartcard

* Changed type for _checkCertificateTrust_ from boolean to integer and added the correct options. (#46) 

##### menu.nomad.login.ad

* Added keys for the 1.2 Beta release.

### Bug Fixes

* Export accessory view pop-up buttons for platform and scope had incorrect default selections.
* Dragging a profile to the library group currently selected caused the profile to be deleted.
* Text entered in TextViews were not saved. (#44)
* Segmented controls did not highlight current selection on macOS 10.12. (#45)
* Payload filter/search is now case insensitive.
* Removing the selected library group now changes the selection to the "All Profiles" group.
* ...and many minor bug fixes. 

### Known Issues

* The export panel's accessory view is not shown in 10.12. 
 (Export still works, just no changes can be made in the export panel).
 
 * When saving a profile for the first time, on rare occasions it might not save and won't be recognized after a restart.
  (Never found a way to replicate, only rare reports)

### Contribute

There are many ways to contribute to this project. Here are a few listed below:

* Test and report bugs or incorrect behavior both in the UI and in the exported profiles.
* Language and spelling errors. (English is not my native language).
* Missing payloads or payload keys. (Contribute to the [ProfileManifests](https://github.com/erikberglund/ProfileManifests) repository to improve the manifests used to define all payloads, keys and their interactions.)
* Add feature requests or suggestions by opening an issue in this repository.
