---
layout: post
title: "Office PnP Provisioning Engine Limitations & Workarounds"
date: 2016-08-15
---
Office PnP Provisioning Engine Limitation &amp; Workarounds
Office PnP provisioning engine by design supports code migration for specific provisioning requirements that is not supported by engine:<br/>
Code migrations ( custom providers that implements IProvisioningExtensibilityHandler ) is simply a way to attached code migrations after engine has finished provisioning.
Few common scenarios that will require custom code migrations:<br/>
1. Data migrations that includes any seed data into lists.<br/>
2. Move web parts to specific categories. (second step after uploading the web part file https://msdn.microsoft.com/en-us/pnp_articles/upload-web-parts-in-sharepoint )<br/>
3. Delete exsiting artefacts.<br/>

