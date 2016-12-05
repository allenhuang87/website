title: HNS Analysize
date: 2016-10-01 23:40:13
tags:
---
In this file I will analysize the HNS network dirvers
The hnae driver start by using class_create to create a new class name "hnae".
After that, this driver provide some function for other module (hns_dsaf and
hns_enet_drv) to use. This funtions are as below:

	hnae_register_notifier
	hnae_unregister_notifier

	hnae_get_handle
	hnae_put_handle
	hnae_reinit_handle

	hnae_ae_register
	hnae_ae_unregister

