## NoProvisioning
<br>This module disables provisioning, this is done to try and hide tethering data from network carriers.
<br>Tested working on OnePlus 6T, OxygenOS 9.0.15 (Android 9.0)
<br>Based on Magisk v19 template.
<br>XDA-Developers: Battlehero

## How's this done?
<br> It adds the following to the build.prop: <code> net.tethering.noprovisioning=true </code>
<br> Runs: <code> settings put global tether_dun_required 0 </code>

## Changelog
<br>16/07/2019 Initial commit.
