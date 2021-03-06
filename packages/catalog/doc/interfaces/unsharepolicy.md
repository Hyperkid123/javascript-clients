[@redhat-cloud-services/catalog-client](../README.md) > [UnsharePolicy](../interfaces/unsharepolicy.md)

# Interface: UnsharePolicy

*__export__*: 

*__interface__*: UnsharePolicy

## Hierarchy

**UnsharePolicy**

## Index

### Properties

* [groupUuids](unsharepolicy.md#groupuuids)
* [permissions](unsharepolicy.md#permissions)

---

## Properties

<a id="groupuuids"></a>

### `<Optional>` groupUuids

**● groupUuids**: *`Array`<`string`>*

*Defined in [api.ts:846](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/catalog/api.ts#L846)*

An array of group UUID's retrieved from the RBAC Service from which the permissions have to be removed. If group uuids are not specified we will unshare it from all groups.

*__type__*: {Array}

*__memberof__*: UnsharePolicy

___
<a id="permissions"></a>

###  permissions

**● permissions**: *`Array`<`string`>*

*Defined in [api.ts:840](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/catalog/api.ts#L840)*

The permissions to remove for this resource.

*__type__*: {Array}

*__memberof__*: UnsharePolicy

___

