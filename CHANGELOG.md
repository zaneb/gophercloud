## 0.2.0 (Unreleased)

IMPROVEMENTS

* Added `networking/v2/extensions/qos/rules.ListBandwidthLimitRules` [GH-1584](https://github.com/gophercloud/gophercloud/pull/1584)
* Added `networking/v2/extensions/qos/rules.GetBandwidthLimitRule` [GH-1584](https://github.com/gophercloud/gophercloud/pull/1584)
* Added `networking/v2/extensions/qos/rules.CreateBandwidthLimitRule` [GH-1584](https://github.com/gophercloud/gophercloud/pull/1584)
* Added `networking/v2/extensions/qos/rules.UpdateBandwidthLimitRule` [GH-1589](https://github.com/gophercloud/gophercloud/pull/1589)
* Added `networking/v2/extensions/qos/rules.DeleteBandwidthLimitRule` [GH-1590](https://github.com/gophercloud/gophercloud/pull/1590)
* Added `networking/v2/extensions/qos/policies.List` [GH-1591](https://github.com/gophercloud/gophercloud/pull/1591)
* Added `networking/v2/extensions/qos/policies.Get` [GH-1593](https://github.com/gophercloud/gophercloud/pull/1593)
* Added `networking/v2/extensions/qos/rules.ListDSCPMarkingRules` [GH-1594](https://github.com/gophercloud/gophercloud/pull/1594)
* Added `networking/v2/extensions/qos/policies.Create` [GH-1595](https://github.com/gophercloud/gophercloud/pull/1595)
* Added `compute/v2/extensions/diagnostics.Get` [GH-1592](https://github.com/gophercloud/gophercloud/pull/1592)
* Added `networking/v2/extensions/qos/policies.Update` [GH-1603](https://github.com/gophercloud/gophercloud/pull/1603)
* Added `networking/v2/extensions/qos/policies.Delete` [GH-1603](https://github.com/gophercloud/gophercloud/pull/1603)
* Added `networking/v2/extensions/qos/rules.CreateDSCPMarkingRule` [GH-1605](https://github.com/gophercloud/gophercloud/pull/1605)
* Added `networking/v2/extensions/qos/rules.UpdateDSCPMarkingRule` [GH-1605](https://github.com/gophercloud/gophercloud/pull/1605)
* Added `networking/v2/extensions/qos/rules.GetDSCPMarkingRule` [GH-1609](https://github.com/gophercloud/gophercloud/pull/1609)
* Added `networking/v2/extensions/qos/rules.DeleteDSCPMarkingRule` [GH-1609](https://github.com/gophercloud/gophercloud/pull/1609)
* Added `networking/v2/extensions/qos/rules.ListMinimumBandwidthRules` [GH-1615](https://github.com/gophercloud/gophercloud/pull/1615)
* Added `networking/v2/extensions/qos/rules.GetMinimumBandwidthRule` [GH-1615](https://github.com/gophercloud/gophercloud/pull/1615)
* Added `networking/v2/extensions/qos/rules.CreateMinimumBandwidthRule` [GH-1615](https://github.com/gophercloud/gophercloud/pull/1615)
* Added `Hostname` to `baremetalintrospection/v1/introspection.Data` [GH-1617](https://github.com/gophercloud/gophercloud/pull/1617)


BUG FIXES

* Updated `networking/v2/extensions/qos/rules.UpdateBandwidthLimitRule` to use return code 200 [GH-1606](https://github.com/gophercloud/gophercloud/pull/1606)
* Fixed bug in `compute/v2/extensions/schedulerhints.SchedulerHints.Query` where contents will now be marshalled to a string [GH-1620](https://github.com/gophercloud/gophercloud/pull/1620)

## 0.1.0 (May 27, 2019)

Initial tagged release. 
