---
layout: post
title: "Office PnP Provisioning Engine Limitations & Workarounds"
date: 2016-08-15
---
Office PnP Provisioning Engine Limitation &amp; Workarounds
Office PnP provisioning engine by design support code migration for specific provisioning requirements that is not support:
Code migrations ( custom providers that implements IProvisioningExtensibilityHandler ) is simply a way to attached code migrations after engine has finished provisioning.
Few common scenarios that will require custom code migrations:
1 - Data migrations that includes any seed data into lists.
2 - Move web parts to specific categories.
3 - Delete exsiting artefacts.