[@redhat-cloud-services/approval-client](../README.md) > [WorkflowApi](../classes/workflowapi.md)

# Class: WorkflowApi

WorkflowApi - object-oriented interface

*__export__*: 

*__class__*: WorkflowApi

*__extends__*: {BaseAPI}

## Hierarchy

 [BaseAPI](baseapi.md)

**↳ WorkflowApi**

## Index

### Constructors

* [constructor](workflowapi.md#constructor)

### Properties

* [axios](workflowapi.md#axios)
* [basePath](workflowapi.md#basepath)
* [configuration](workflowapi.md#configuration)

### Methods

* [addWorkflowToTemplate](workflowapi.md#addworkflowtotemplate)
* [destroyWorkflow](workflowapi.md#destroyworkflow)
* [listWorkflows](workflowapi.md#listworkflows)
* [listWorkflowsByTemplate](workflowapi.md#listworkflowsbytemplate)
* [showWorkflow](workflowapi.md#showworkflow)
* [updateWorkflow](workflowapi.md#updateworkflow)

---

## Constructors

<a id="constructor"></a>

###  constructor

⊕ **new WorkflowApi**(configuration?: *[Configuration](configuration.md)*, basePath?: *`string`*, axios?: *`AxiosInstance`*): [WorkflowApi](workflowapi.md)

*Inherited from [BaseAPI](baseapi.md).[constructor](baseapi.md#constructor)*

*Defined in [api.ts:49](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/approval/api.ts#L49)*

**Parameters:**

| Name | Type | Default value |
| ------ | ------ | ------ |
| `Optional` configuration | [Configuration](configuration.md) | - |
| `Default value` basePath | `string` |  BASE_PATH |
| `Default value` axios | `AxiosInstance` |  globalAxios |

**Returns:** [WorkflowApi](workflowapi.md)

___

## Properties

<a id="axios"></a>

### `<Protected>` axios

**● axios**: *`AxiosInstance`*

*Inherited from [BaseAPI](baseapi.md).[axios](baseapi.md#axios)*

*Defined in [api.ts:51](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/approval/api.ts#L51)*

___
<a id="basepath"></a>

### `<Protected>` basePath

**● basePath**: *`string`*

*Inherited from [BaseAPI](baseapi.md).[basePath](baseapi.md#basepath)*

*Defined in [api.ts:51](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/approval/api.ts#L51)*

___
<a id="configuration"></a>

### `<Protected>` configuration

**● configuration**: *[Configuration](configuration.md) \| `undefined`*

*Inherited from [BaseAPI](baseapi.md).[configuration](baseapi.md#configuration)*

*Defined in [api.ts:49](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/approval/api.ts#L49)*

___

## Methods

<a id="addworkflowtotemplate"></a>

###  addWorkflowToTemplate

▸ **addWorkflowToTemplate**(templateId: *`number`*, workflowIn: *[WorkflowIn](../interfaces/workflowin.md)*, options?: *`any`*): `AxiosPromise`<[WorkflowOut](../interfaces/workflowout.md)>

*Defined in [api.ts:2145](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/approval/api.ts#L2145)*

Add a workflow by given template id

*__summary__*: Add a workflow by given template id

*__throws__*: {RequiredError}

*__memberof__*: WorkflowApi

**Parameters:**

| Name | Type | Description |
| ------ | ------ | ------ |
| templateId | `number` |  Id of template |
| workflowIn | [WorkflowIn](../interfaces/workflowin.md) |  Parameters need to create workflow |
| `Optional` options | `any` |

**Returns:** `AxiosPromise`<[WorkflowOut](../interfaces/workflowout.md)>

___
<a id="destroyworkflow"></a>

###  destroyWorkflow

▸ **destroyWorkflow**(id: *`number`*, options?: *`any`*): `AxiosPromise`<`Response`>

*Defined in [api.ts:2157](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/approval/api.ts#L2157)*

Delete approval workflow by given id

*__summary__*: Delete approval workflow by given id

*__throws__*: {RequiredError}

*__memberof__*: WorkflowApi

**Parameters:**

| Name | Type | Description |
| ------ | ------ | ------ |
| id | `number` |  Query by id |
| `Optional` options | `any` |

**Returns:** `AxiosPromise`<`Response`>

___
<a id="listworkflows"></a>

###  listWorkflows

▸ **listWorkflows**(limit?: *`number`*, offset?: *`number`*, options?: *`any`*): `AxiosPromise`<[WorkflowOutCollection](../interfaces/workflowoutcollection.md)>

*Defined in [api.ts:2170](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/approval/api.ts#L2170)*

Return all approval workflows

*__summary__*: Return all approval workflows

*__throws__*: {RequiredError}

*__memberof__*: WorkflowApi

**Parameters:**

| Name | Type |
| ------ | ------ |
| `Optional` limit | `number` |
| `Optional` offset | `number` |
| `Optional` options | `any` |

**Returns:** `AxiosPromise`<[WorkflowOutCollection](../interfaces/workflowoutcollection.md)>

___
<a id="listworkflowsbytemplate"></a>

###  listWorkflowsByTemplate

▸ **listWorkflowsByTemplate**(templateId: *`number`*, limit?: *`number`*, offset?: *`number`*, options?: *`any`*): `AxiosPromise`<[WorkflowOutCollection](../interfaces/workflowoutcollection.md)>

*Defined in [api.ts:2184](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/approval/api.ts#L2184)*

Return an array of workflows by given template id

*__summary__*: Return an array of workflows by given template id

*__throws__*: {RequiredError}

*__memberof__*: WorkflowApi

**Parameters:**

| Name | Type | Description |
| ------ | ------ | ------ |
| templateId | `number` |  Id of template |
| `Optional` limit | `number` |
| `Optional` offset | `number` |
| `Optional` options | `any` |

**Returns:** `AxiosPromise`<[WorkflowOutCollection](../interfaces/workflowoutcollection.md)>

___
<a id="showworkflow"></a>

###  showWorkflow

▸ **showWorkflow**(id: *`number`*, options?: *`any`*): `AxiosPromise`<[WorkflowOut](../interfaces/workflowout.md)>

*Defined in [api.ts:2196](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/approval/api.ts#L2196)*

Return an approval workflow by given id

*__summary__*: Return an approval workflow by given id

*__throws__*: {RequiredError}

*__memberof__*: WorkflowApi

**Parameters:**

| Name | Type | Description |
| ------ | ------ | ------ |
| id | `number` |  Query by id |
| `Optional` options | `any` |

**Returns:** `AxiosPromise`<[WorkflowOut](../interfaces/workflowout.md)>

___
<a id="updateworkflow"></a>

###  updateWorkflow

▸ **updateWorkflow**(id: *`number`*, workflowIn: *[WorkflowIn](../interfaces/workflowin.md)*, options?: *`any`*): `AxiosPromise`<[WorkflowOut](../interfaces/workflowout.md)>

*Defined in [api.ts:2209](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/approval/api.ts#L2209)*

Update an approval workflow by given id

*__summary__*: Update an approval workflow by given id

*__throws__*: {RequiredError}

*__memberof__*: WorkflowApi

**Parameters:**

| Name | Type | Description |
| ------ | ------ | ------ |
| id | `number` |  Query by id |
| workflowIn | [WorkflowIn](../interfaces/workflowin.md) |  Parameters need to update approval workflow |
| `Optional` options | `any` |

**Returns:** `AxiosPromise`<[WorkflowOut](../interfaces/workflowout.md)>

___

