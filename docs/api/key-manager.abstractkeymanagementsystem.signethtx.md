---
id: key-manager.abstractkeymanagementsystem.signethtx
title: AbstractKeyManagementSystem.signEthTX() method
hide_title: true
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

## AbstractKeyManagementSystem.signEthTX() method

> Warning: This API is now obsolete.
>
> please use `sign({key, alg: 'eth_signTransaction', data: arrayify(serialize(transaction))})` instead

<b>Signature:</b>

```typescript
signEthTX({ key, transaction }: {
        key: Pick<IKey, 'kid'>;
        transaction: object;
    }): Promise<string>;
```

## Parameters

| Parameter            | Type                                                                      | Description |
| -------------------- | ------------------------------------------------------------------------- | ----------- |
| { key, transaction } | { key: Pick&lt;[IKey](./core.ikey.md) , 'kid'&gt;; transaction: object; } |             |

<b>Returns:</b>

Promise&lt;string&gt;
