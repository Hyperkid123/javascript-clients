[@redhat-cloud-services/remediations-client](../README.md) > [GeneratorApi](../classes/generatorapi.md)

# Class: GeneratorApi

GeneratorApi - object-oriented interface

*__export__*: 

*__class__*: GeneratorApi

*__extends__*: {BaseAPI}

## Hierarchy

 [BaseAPI](baseapi.md)

**↳ GeneratorApi**

## Index

### Constructors

* [constructor](generatorapi.md#constructor)

### Properties

* [axios](generatorapi.md#axios)
* [basePath](generatorapi.md#basepath)
* [configuration](generatorapi.md#configuration)

### Methods

* [generate](generatorapi.md#generate)

---

## Constructors

<a id="constructor"></a>

###  constructor

⊕ **new GeneratorApi**(configuration?: *[Configuration](configuration.md)*, basePath?: *`string`*, axios?: *`AxiosInstance`*): [GeneratorApi](generatorapi.md)

*Inherited from [BaseAPI](baseapi.md).[constructor](baseapi.md#constructor)*

*Defined in [api.ts:49](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/remediations/api.ts#L49)*

**Parameters:**

| Name | Type | Default value |
| ------ | ------ | ------ |
| `Optional` configuration | [Configuration](configuration.md) | - |
| `Default value` basePath | `string` |  BASE_PATH |
| `Default value` axios | `AxiosInstance` |  globalAxios |

**Returns:** [GeneratorApi](generatorapi.md)

___

## Properties

<a id="axios"></a>

### `<Protected>` axios

**● axios**: *`AxiosInstance`*

*Inherited from [BaseAPI](baseapi.md).[axios](baseapi.md#axios)*

*Defined in [api.ts:51](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/remediations/api.ts#L51)*

___
<a id="basepath"></a>

### `<Protected>` basePath

**● basePath**: *`string`*

*Inherited from [BaseAPI](baseapi.md).[basePath](baseapi.md#basepath)*

*Defined in [api.ts:51](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/remediations/api.ts#L51)*

___
<a id="configuration"></a>

### `<Protected>` configuration

**● configuration**: *[Configuration](configuration.md) \| `undefined`*

*Inherited from [BaseAPI](baseapi.md).[configuration](baseapi.md#configuration)*

*Defined in [api.ts:49](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/remediations/api.ts#L49)*

___

## Methods

<a id="generate"></a>

###  generate

▸ **generate**(playbookDefinition: *[PlaybookDefinition](../interfaces/playbookdefinition.md)*, options?: *`any`*): `AxiosPromise`<`string`>

*Defined in [api.ts:941](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/remediations/api.ts#L941)*

Generates an Ansible Playbook based on input parameters

*__summary__*: Generate an Ansible Playbook

*__throws__*: {RequiredError}

*__memberof__*: GeneratorApi

**Parameters:**

| Name | Type | Description |
| ------ | ------ | ------ |
| playbookDefinition | [PlaybookDefinition](../interfaces/playbookdefinition.md) |  \- |
| `Optional` options | `any` |

**Returns:** `AxiosPromise`<`string`>

___

