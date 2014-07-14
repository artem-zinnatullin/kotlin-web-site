---
layout: api
title: requireNotNull
---
[stdlib](../index.md) / [kotlin](index.md) / [requireNotNull](requireNotNull.md)

# requireNotNull
Throws an [[IllegalArgumentException]] with the given *message* if the *value* is null otherwise
```
public fun <T : T> requireNotNull(value: T, message: Any): T
```
## Description
```
public fun <T : T> requireNotNull(value: T, message: Any): T
```
the not null value is returned.
@includeFunctionBody ../../test/PreconditionsTest.kt requireNotNull
