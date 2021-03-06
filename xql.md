---
layout: page
title: XQL
---

## Communicating with XFireDB

XFireDB uses XQL as its scripting language. Using XQL you can interface with XFireDB in a similar
fashion as XQL does for your every day XQL database. Below are all the available XFireDB commands,
both storage and cluster management commands.

## [String commands](/string/)

	GET
	SET

## [Hashmap commands](/hmap/)

	MDEL
	MREF
	MCLEAR
	MADD
	MSIZE

## [Set commands](/set/)

	SINCLUDE
	SADD
	SDEL
	SCLEAR

## [List commands](/list/)

	LPUSH
	LREF
	LPOP
	LSIZE
	LSET
	LCLEAR

## [CLUSTER commands](/cluster/)

	CLUSTER USERMOD
	CLUSTER USERADD
	CLUSTER USERDEL
	CLUSTER FORGET
	CLUSTER MIGRATE
	CLUSTER SLOTS
	CLUSTER RESHARD
	CLUSTER NODES
	CLUSTER WHEREIS?
	CLUSTER MEET

