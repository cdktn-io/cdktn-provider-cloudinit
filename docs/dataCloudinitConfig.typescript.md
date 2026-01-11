# `dataCloudinitConfig` Submodule <a name="`dataCloudinitConfig` Submodule" id="@cdktn/provider-cloudinit.dataCloudinitConfig"></a>

## Constructs <a name="Constructs" id="Constructs"></a>

### DataCloudinitConfig <a name="DataCloudinitConfig" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig"></a>

Represents a {@link https://registry.terraform.io/providers/hashicorp/cloudinit/2.3.7/docs/data-sources/config cloudinit_config}.

#### Initializers <a name="Initializers" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.Initializer"></a>

```typescript
import { dataCloudinitConfig } from '@cdktn/provider-cloudinit'

new dataCloudinitConfig.DataCloudinitConfig(scope: Construct, id: string, config?: DataCloudinitConfigConfig)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.Initializer.parameter.scope">scope</a></code> | <code>constructs.Construct</code> | The scope in which to define this construct. |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.Initializer.parameter.id">id</a></code> | <code>string</code> | The scoped construct ID. |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.Initializer.parameter.config">config</a></code> | <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigConfig">DataCloudinitConfigConfig</a></code> | *No description.* |

---

##### `scope`<sup>Required</sup> <a name="scope" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.Initializer.parameter.scope"></a>

- *Type:* constructs.Construct

The scope in which to define this construct.

---

##### `id`<sup>Required</sup> <a name="id" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.Initializer.parameter.id"></a>

- *Type:* string

The scoped construct ID.

Must be unique amongst siblings in the same scope

---

##### `config`<sup>Optional</sup> <a name="config" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.Initializer.parameter.config"></a>

- *Type:* <a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigConfig">DataCloudinitConfigConfig</a>

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.toString">toString</a></code> | Returns a string representation of this construct. |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.addOverride">addOverride</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.overrideLogicalId">overrideLogicalId</a></code> | Overrides the auto-generated logical ID with a specific ID. |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.resetOverrideLogicalId">resetOverrideLogicalId</a></code> | Resets a previously passed logical Id to use the auto-generated logical id again. |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.toHclTerraform">toHclTerraform</a></code> | Adds this resource to the terraform JSON output. |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.toMetadata">toMetadata</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.toTerraform">toTerraform</a></code> | Adds this resource to the terraform JSON output. |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.getAnyMapAttribute">getAnyMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.getBooleanAttribute">getBooleanAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.getBooleanMapAttribute">getBooleanMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.getListAttribute">getListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.getNumberAttribute">getNumberAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.getNumberListAttribute">getNumberListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.getNumberMapAttribute">getNumberMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.getStringAttribute">getStringAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.getStringMapAttribute">getStringMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.interpolationForAttribute">interpolationForAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.putPart">putPart</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.resetBase64Encode">resetBase64Encode</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.resetBoundary">resetBoundary</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.resetGzip">resetGzip</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.resetPart">resetPart</a></code> | *No description.* |

---

##### `toString` <a name="toString" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.toString"></a>

```typescript
public toString(): string
```

Returns a string representation of this construct.

##### `addOverride` <a name="addOverride" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.addOverride"></a>

```typescript
public addOverride(path: string, value: any): void
```

###### `path`<sup>Required</sup> <a name="path" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.addOverride.parameter.path"></a>

- *Type:* string

---

###### `value`<sup>Required</sup> <a name="value" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.addOverride.parameter.value"></a>

- *Type:* any

---

##### `overrideLogicalId` <a name="overrideLogicalId" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.overrideLogicalId"></a>

```typescript
public overrideLogicalId(newLogicalId: string): void
```

Overrides the auto-generated logical ID with a specific ID.

###### `newLogicalId`<sup>Required</sup> <a name="newLogicalId" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.overrideLogicalId.parameter.newLogicalId"></a>

- *Type:* string

The new logical ID to use for this stack element.

---

##### `resetOverrideLogicalId` <a name="resetOverrideLogicalId" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.resetOverrideLogicalId"></a>

```typescript
public resetOverrideLogicalId(): void
```

Resets a previously passed logical Id to use the auto-generated logical id again.

##### `toHclTerraform` <a name="toHclTerraform" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.toHclTerraform"></a>

```typescript
public toHclTerraform(): any
```

Adds this resource to the terraform JSON output.

##### `toMetadata` <a name="toMetadata" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.toMetadata"></a>

```typescript
public toMetadata(): any
```

##### `toTerraform` <a name="toTerraform" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.toTerraform"></a>

```typescript
public toTerraform(): any
```

Adds this resource to the terraform JSON output.

##### `getAnyMapAttribute` <a name="getAnyMapAttribute" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.getAnyMapAttribute"></a>

```typescript
public getAnyMapAttribute(terraformAttribute: string): {[ key: string ]: any}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getBooleanAttribute` <a name="getBooleanAttribute" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.getBooleanAttribute"></a>

```typescript
public getBooleanAttribute(terraformAttribute: string): IResolvable
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getBooleanMapAttribute` <a name="getBooleanMapAttribute" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.getBooleanMapAttribute"></a>

```typescript
public getBooleanMapAttribute(terraformAttribute: string): {[ key: string ]: boolean}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getListAttribute` <a name="getListAttribute" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.getListAttribute"></a>

```typescript
public getListAttribute(terraformAttribute: string): string[]
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getNumberAttribute` <a name="getNumberAttribute" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.getNumberAttribute"></a>

```typescript
public getNumberAttribute(terraformAttribute: string): number
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getNumberListAttribute` <a name="getNumberListAttribute" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.getNumberListAttribute"></a>

```typescript
public getNumberListAttribute(terraformAttribute: string): number[]
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getNumberMapAttribute` <a name="getNumberMapAttribute" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.getNumberMapAttribute"></a>

```typescript
public getNumberMapAttribute(terraformAttribute: string): {[ key: string ]: number}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getStringAttribute` <a name="getStringAttribute" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.getStringAttribute"></a>

```typescript
public getStringAttribute(terraformAttribute: string): string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getStringMapAttribute` <a name="getStringMapAttribute" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.getStringMapAttribute"></a>

```typescript
public getStringMapAttribute(terraformAttribute: string): {[ key: string ]: string}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `interpolationForAttribute` <a name="interpolationForAttribute" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.interpolationForAttribute"></a>

```typescript
public interpolationForAttribute(terraformAttribute: string): IResolvable
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.interpolationForAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `putPart` <a name="putPart" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.putPart"></a>

```typescript
public putPart(value: IResolvable | DataCloudinitConfigPart[]): void
```

###### `value`<sup>Required</sup> <a name="value" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.putPart.parameter.value"></a>

- *Type:* cdktf.IResolvable | <a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPart">DataCloudinitConfigPart</a>[]

---

##### `resetBase64Encode` <a name="resetBase64Encode" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.resetBase64Encode"></a>

```typescript
public resetBase64Encode(): void
```

##### `resetBoundary` <a name="resetBoundary" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.resetBoundary"></a>

```typescript
public resetBoundary(): void
```

##### `resetGzip` <a name="resetGzip" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.resetGzip"></a>

```typescript
public resetGzip(): void
```

##### `resetPart` <a name="resetPart" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.resetPart"></a>

```typescript
public resetPart(): void
```

#### Static Functions <a name="Static Functions" id="Static Functions"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.isConstruct">isConstruct</a></code> | Checks if `x` is a construct. |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.isTerraformElement">isTerraformElement</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.isTerraformDataSource">isTerraformDataSource</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.generateConfigForImport">generateConfigForImport</a></code> | Generates CDKTF code for importing a DataCloudinitConfig resource upon running "cdktf plan <stack-name>". |

---

##### `isConstruct` <a name="isConstruct" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.isConstruct"></a>

```typescript
import { dataCloudinitConfig } from '@cdktn/provider-cloudinit'

dataCloudinitConfig.DataCloudinitConfig.isConstruct(x: any)
```

Checks if `x` is a construct.

Use this method instead of `instanceof` to properly detect `Construct`
instances, even when the construct library is symlinked.

Explanation: in JavaScript, multiple copies of the `constructs` library on
disk are seen as independent, completely different libraries. As a
consequence, the class `Construct` in each copy of the `constructs` library
is seen as a different class, and an instance of one class will not test as
`instanceof` the other class. `npm install` will not create installations
like this, but users may manually symlink construct libraries together or
use a monorepo tool: in those cases, multiple copies of the `constructs`
library can be accidentally installed, and `instanceof` will behave
unpredictably. It is safest to avoid using `instanceof`, and using
this type-testing method instead.

###### `x`<sup>Required</sup> <a name="x" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.isConstruct.parameter.x"></a>

- *Type:* any

Any object.

---

##### `isTerraformElement` <a name="isTerraformElement" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.isTerraformElement"></a>

```typescript
import { dataCloudinitConfig } from '@cdktn/provider-cloudinit'

dataCloudinitConfig.DataCloudinitConfig.isTerraformElement(x: any)
```

###### `x`<sup>Required</sup> <a name="x" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.isTerraformElement.parameter.x"></a>

- *Type:* any

---

##### `isTerraformDataSource` <a name="isTerraformDataSource" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.isTerraformDataSource"></a>

```typescript
import { dataCloudinitConfig } from '@cdktn/provider-cloudinit'

dataCloudinitConfig.DataCloudinitConfig.isTerraformDataSource(x: any)
```

###### `x`<sup>Required</sup> <a name="x" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.isTerraformDataSource.parameter.x"></a>

- *Type:* any

---

##### `generateConfigForImport` <a name="generateConfigForImport" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.generateConfigForImport"></a>

```typescript
import { dataCloudinitConfig } from '@cdktn/provider-cloudinit'

dataCloudinitConfig.DataCloudinitConfig.generateConfigForImport(scope: Construct, importToId: string, importFromId: string, provider?: TerraformProvider)
```

Generates CDKTF code for importing a DataCloudinitConfig resource upon running "cdktf plan <stack-name>".

###### `scope`<sup>Required</sup> <a name="scope" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.generateConfigForImport.parameter.scope"></a>

- *Type:* constructs.Construct

The scope in which to define this construct.

---

###### `importToId`<sup>Required</sup> <a name="importToId" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.generateConfigForImport.parameter.importToId"></a>

- *Type:* string

The construct id used in the generated config for the DataCloudinitConfig to import.

---

###### `importFromId`<sup>Required</sup> <a name="importFromId" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.generateConfigForImport.parameter.importFromId"></a>

- *Type:* string

The id of the existing DataCloudinitConfig that should be imported.

Refer to the {@link https://registry.terraform.io/providers/hashicorp/cloudinit/2.3.7/docs/data-sources/config#import import section} in the documentation of this resource for the id to use

---

###### `provider`<sup>Optional</sup> <a name="provider" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.generateConfigForImport.parameter.provider"></a>

- *Type:* cdktf.TerraformProvider

? Optional instance of the provider where the DataCloudinitConfig to import is found.

---

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.property.node">node</a></code> | <code>constructs.Node</code> | The tree node. |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.property.cdktfStack">cdktfStack</a></code> | <code>cdktf.TerraformStack</code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.property.fqn">fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.property.friendlyUniqueId">friendlyUniqueId</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.property.terraformMetaArguments">terraformMetaArguments</a></code> | <code>{[ key: string ]: any}</code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.property.terraformResourceType">terraformResourceType</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.property.terraformGeneratorMetadata">terraformGeneratorMetadata</a></code> | <code>cdktf.TerraformProviderGeneratorMetadata</code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.property.count">count</a></code> | <code>number \| cdktf.TerraformCount</code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.property.dependsOn">dependsOn</a></code> | <code>string[]</code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.property.forEach">forEach</a></code> | <code>cdktf.ITerraformIterator</code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.property.lifecycle">lifecycle</a></code> | <code>cdktf.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.property.provider">provider</a></code> | <code>cdktf.TerraformProvider</code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.property.id">id</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.property.part">part</a></code> | <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartList">DataCloudinitConfigPartList</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.property.rendered">rendered</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.property.base64EncodeInput">base64EncodeInput</a></code> | <code>boolean \| cdktf.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.property.boundaryInput">boundaryInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.property.gzipInput">gzipInput</a></code> | <code>boolean \| cdktf.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.property.partInput">partInput</a></code> | <code>cdktf.IResolvable \| <a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPart">DataCloudinitConfigPart</a>[]</code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.property.base64Encode">base64Encode</a></code> | <code>boolean \| cdktf.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.property.boundary">boundary</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.property.gzip">gzip</a></code> | <code>boolean \| cdktf.IResolvable</code> | *No description.* |

---

##### `node`<sup>Required</sup> <a name="node" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.property.node"></a>

```typescript
public readonly node: Node;
```

- *Type:* constructs.Node

The tree node.

---

##### `cdktfStack`<sup>Required</sup> <a name="cdktfStack" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.property.cdktfStack"></a>

```typescript
public readonly cdktfStack: TerraformStack;
```

- *Type:* cdktf.TerraformStack

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.property.fqn"></a>

```typescript
public readonly fqn: string;
```

- *Type:* string

---

##### `friendlyUniqueId`<sup>Required</sup> <a name="friendlyUniqueId" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.property.friendlyUniqueId"></a>

```typescript
public readonly friendlyUniqueId: string;
```

- *Type:* string

---

##### `terraformMetaArguments`<sup>Required</sup> <a name="terraformMetaArguments" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.property.terraformMetaArguments"></a>

```typescript
public readonly terraformMetaArguments: {[ key: string ]: any};
```

- *Type:* {[ key: string ]: any}

---

##### `terraformResourceType`<sup>Required</sup> <a name="terraformResourceType" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.property.terraformResourceType"></a>

```typescript
public readonly terraformResourceType: string;
```

- *Type:* string

---

##### `terraformGeneratorMetadata`<sup>Optional</sup> <a name="terraformGeneratorMetadata" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.property.terraformGeneratorMetadata"></a>

```typescript
public readonly terraformGeneratorMetadata: TerraformProviderGeneratorMetadata;
```

- *Type:* cdktf.TerraformProviderGeneratorMetadata

---

##### `count`<sup>Optional</sup> <a name="count" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.property.count"></a>

```typescript
public readonly count: number | TerraformCount;
```

- *Type:* number | cdktf.TerraformCount

---

##### `dependsOn`<sup>Optional</sup> <a name="dependsOn" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.property.dependsOn"></a>

```typescript
public readonly dependsOn: string[];
```

- *Type:* string[]

---

##### `forEach`<sup>Optional</sup> <a name="forEach" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.property.forEach"></a>

```typescript
public readonly forEach: ITerraformIterator;
```

- *Type:* cdktf.ITerraformIterator

---

##### `lifecycle`<sup>Optional</sup> <a name="lifecycle" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.property.lifecycle"></a>

```typescript
public readonly lifecycle: TerraformResourceLifecycle;
```

- *Type:* cdktf.TerraformResourceLifecycle

---

##### `provider`<sup>Optional</sup> <a name="provider" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.property.provider"></a>

```typescript
public readonly provider: TerraformProvider;
```

- *Type:* cdktf.TerraformProvider

---

##### `id`<sup>Required</sup> <a name="id" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.property.id"></a>

```typescript
public readonly id: string;
```

- *Type:* string

---

##### `part`<sup>Required</sup> <a name="part" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.property.part"></a>

```typescript
public readonly part: DataCloudinitConfigPartList;
```

- *Type:* <a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartList">DataCloudinitConfigPartList</a>

---

##### `rendered`<sup>Required</sup> <a name="rendered" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.property.rendered"></a>

```typescript
public readonly rendered: string;
```

- *Type:* string

---

##### `base64EncodeInput`<sup>Optional</sup> <a name="base64EncodeInput" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.property.base64EncodeInput"></a>

```typescript
public readonly base64EncodeInput: boolean | IResolvable;
```

- *Type:* boolean | cdktf.IResolvable

---

##### `boundaryInput`<sup>Optional</sup> <a name="boundaryInput" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.property.boundaryInput"></a>

```typescript
public readonly boundaryInput: string;
```

- *Type:* string

---

##### `gzipInput`<sup>Optional</sup> <a name="gzipInput" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.property.gzipInput"></a>

```typescript
public readonly gzipInput: boolean | IResolvable;
```

- *Type:* boolean | cdktf.IResolvable

---

##### `partInput`<sup>Optional</sup> <a name="partInput" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.property.partInput"></a>

```typescript
public readonly partInput: IResolvable | DataCloudinitConfigPart[];
```

- *Type:* cdktf.IResolvable | <a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPart">DataCloudinitConfigPart</a>[]

---

##### `base64Encode`<sup>Required</sup> <a name="base64Encode" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.property.base64Encode"></a>

```typescript
public readonly base64Encode: boolean | IResolvable;
```

- *Type:* boolean | cdktf.IResolvable

---

##### `boundary`<sup>Required</sup> <a name="boundary" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.property.boundary"></a>

```typescript
public readonly boundary: string;
```

- *Type:* string

---

##### `gzip`<sup>Required</sup> <a name="gzip" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.property.gzip"></a>

```typescript
public readonly gzip: boolean | IResolvable;
```

- *Type:* boolean | cdktf.IResolvable

---

#### Constants <a name="Constants" id="Constants"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.property.tfResourceType">tfResourceType</a></code> | <code>string</code> | *No description.* |

---

##### `tfResourceType`<sup>Required</sup> <a name="tfResourceType" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.property.tfResourceType"></a>

```typescript
public readonly tfResourceType: string;
```

- *Type:* string

---

## Structs <a name="Structs" id="Structs"></a>

### DataCloudinitConfigConfig <a name="DataCloudinitConfigConfig" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigConfig"></a>

#### Initializer <a name="Initializer" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigConfig.Initializer"></a>

```typescript
import { dataCloudinitConfig } from '@cdktn/provider-cloudinit'

const dataCloudinitConfigConfig: dataCloudinitConfig.DataCloudinitConfigConfig = { ... }
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigConfig.property.connection">connection</a></code> | <code>cdktf.SSHProvisionerConnection \| cdktf.WinrmProvisionerConnection</code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigConfig.property.count">count</a></code> | <code>number \| cdktf.TerraformCount</code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigConfig.property.dependsOn">dependsOn</a></code> | <code>cdktf.ITerraformDependable[]</code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigConfig.property.forEach">forEach</a></code> | <code>cdktf.ITerraformIterator</code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigConfig.property.lifecycle">lifecycle</a></code> | <code>cdktf.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigConfig.property.provider">provider</a></code> | <code>cdktf.TerraformProvider</code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigConfig.property.provisioners">provisioners</a></code> | <code>cdktf.FileProvisioner \| cdktf.LocalExecProvisioner \| cdktf.RemoteExecProvisioner[]</code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigConfig.property.base64Encode">base64Encode</a></code> | <code>boolean \| cdktf.IResolvable</code> | Specify whether or not to base64 encode the `rendered` output. |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigConfig.property.boundary">boundary</a></code> | <code>string</code> | Specify the Writer's default boundary separator. Defaults to `MIMEBOUNDARY`. |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigConfig.property.gzip">gzip</a></code> | <code>boolean \| cdktf.IResolvable</code> | Specify whether or not to gzip the `rendered` output. Defaults to `true`. |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigConfig.property.part">part</a></code> | <code>cdktf.IResolvable \| <a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPart">DataCloudinitConfigPart</a>[]</code> | part block. |

---

##### `connection`<sup>Optional</sup> <a name="connection" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigConfig.property.connection"></a>

```typescript
public readonly connection: SSHProvisionerConnection | WinrmProvisionerConnection;
```

- *Type:* cdktf.SSHProvisionerConnection | cdktf.WinrmProvisionerConnection

---

##### `count`<sup>Optional</sup> <a name="count" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigConfig.property.count"></a>

```typescript
public readonly count: number | TerraformCount;
```

- *Type:* number | cdktf.TerraformCount

---

##### `dependsOn`<sup>Optional</sup> <a name="dependsOn" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigConfig.property.dependsOn"></a>

```typescript
public readonly dependsOn: ITerraformDependable[];
```

- *Type:* cdktf.ITerraformDependable[]

---

##### `forEach`<sup>Optional</sup> <a name="forEach" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigConfig.property.forEach"></a>

```typescript
public readonly forEach: ITerraformIterator;
```

- *Type:* cdktf.ITerraformIterator

---

##### `lifecycle`<sup>Optional</sup> <a name="lifecycle" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigConfig.property.lifecycle"></a>

```typescript
public readonly lifecycle: TerraformResourceLifecycle;
```

- *Type:* cdktf.TerraformResourceLifecycle

---

##### `provider`<sup>Optional</sup> <a name="provider" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigConfig.property.provider"></a>

```typescript
public readonly provider: TerraformProvider;
```

- *Type:* cdktf.TerraformProvider

---

##### `provisioners`<sup>Optional</sup> <a name="provisioners" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigConfig.property.provisioners"></a>

```typescript
public readonly provisioners: (FileProvisioner | LocalExecProvisioner | RemoteExecProvisioner)[];
```

- *Type:* cdktf.FileProvisioner | cdktf.LocalExecProvisioner | cdktf.RemoteExecProvisioner[]

---

##### `base64Encode`<sup>Optional</sup> <a name="base64Encode" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigConfig.property.base64Encode"></a>

```typescript
public readonly base64Encode: boolean | IResolvable;
```

- *Type:* boolean | cdktf.IResolvable

Specify whether or not to base64 encode the `rendered` output.

Defaults to `true`, and cannot be disabled if gzip is `true`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/hashicorp/cloudinit/2.3.7/docs/data-sources/config#base64_encode DataCloudinitConfig#base64_encode}

---

##### `boundary`<sup>Optional</sup> <a name="boundary" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigConfig.property.boundary"></a>

```typescript
public readonly boundary: string;
```

- *Type:* string

Specify the Writer's default boundary separator. Defaults to `MIMEBOUNDARY`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/hashicorp/cloudinit/2.3.7/docs/data-sources/config#boundary DataCloudinitConfig#boundary}

---

##### `gzip`<sup>Optional</sup> <a name="gzip" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigConfig.property.gzip"></a>

```typescript
public readonly gzip: boolean | IResolvable;
```

- *Type:* boolean | cdktf.IResolvable

Specify whether or not to gzip the `rendered` output. Defaults to `true`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/hashicorp/cloudinit/2.3.7/docs/data-sources/config#gzip DataCloudinitConfig#gzip}

---

##### `part`<sup>Optional</sup> <a name="part" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigConfig.property.part"></a>

```typescript
public readonly part: IResolvable | DataCloudinitConfigPart[];
```

- *Type:* cdktf.IResolvable | <a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPart">DataCloudinitConfigPart</a>[]

part block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/hashicorp/cloudinit/2.3.7/docs/data-sources/config#part DataCloudinitConfig#part}

---

### DataCloudinitConfigPart <a name="DataCloudinitConfigPart" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPart"></a>

#### Initializer <a name="Initializer" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPart.Initializer"></a>

```typescript
import { dataCloudinitConfig } from '@cdktn/provider-cloudinit'

const dataCloudinitConfigPart: dataCloudinitConfig.DataCloudinitConfigPart = { ... }
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPart.property.content">content</a></code> | <code>string</code> | Body content for the part. |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPart.property.contentType">contentType</a></code> | <code>string</code> | A MIME-style content type to report in the header for the part. Defaults to `text/plain`. |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPart.property.filename">filename</a></code> | <code>string</code> | A filename to report in the header for the part. |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPart.property.mergeType">mergeType</a></code> | <code>string</code> | A value for the `X-Merge-Type` header of the part, to control [cloud-init merging behavior](https://cloudinit.readthedocs.io/en/latest/reference/merging.html). |

---

##### `content`<sup>Required</sup> <a name="content" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPart.property.content"></a>

```typescript
public readonly content: string;
```

- *Type:* string

Body content for the part.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/hashicorp/cloudinit/2.3.7/docs/data-sources/config#content DataCloudinitConfig#content}

---

##### `contentType`<sup>Optional</sup> <a name="contentType" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPart.property.contentType"></a>

```typescript
public readonly contentType: string;
```

- *Type:* string

A MIME-style content type to report in the header for the part. Defaults to `text/plain`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/hashicorp/cloudinit/2.3.7/docs/data-sources/config#content_type DataCloudinitConfig#content_type}

---

##### `filename`<sup>Optional</sup> <a name="filename" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPart.property.filename"></a>

```typescript
public readonly filename: string;
```

- *Type:* string

A filename to report in the header for the part.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/hashicorp/cloudinit/2.3.7/docs/data-sources/config#filename DataCloudinitConfig#filename}

---

##### `mergeType`<sup>Optional</sup> <a name="mergeType" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPart.property.mergeType"></a>

```typescript
public readonly mergeType: string;
```

- *Type:* string

A value for the `X-Merge-Type` header of the part, to control [cloud-init merging behavior](https://cloudinit.readthedocs.io/en/latest/reference/merging.html).

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/hashicorp/cloudinit/2.3.7/docs/data-sources/config#merge_type DataCloudinitConfig#merge_type}

---

## Classes <a name="Classes" id="Classes"></a>

### DataCloudinitConfigPartList <a name="DataCloudinitConfigPartList" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartList"></a>

#### Initializers <a name="Initializers" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartList.Initializer"></a>

```typescript
import { dataCloudinitConfig } from '@cdktn/provider-cloudinit'

new dataCloudinitConfig.DataCloudinitConfigPartList(terraformResource: IInterpolatingParent, terraformAttribute: string, wrapsSet: boolean)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartList.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartList.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartList.Initializer.parameter.wrapsSet">wrapsSet</a></code> | <code>boolean</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartList.Initializer.parameter.terraformResource"></a>

- *Type:* cdktf.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartList.Initializer.parameter.terraformAttribute"></a>

- *Type:* string

The attribute on the parent resource this class is referencing.

---

##### `wrapsSet`<sup>Required</sup> <a name="wrapsSet" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartList.Initializer.parameter.wrapsSet"></a>

- *Type:* boolean

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartList.allWithMapKey">allWithMapKey</a></code> | Creating an iterator for this complex list. |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartList.computeFqn">computeFqn</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartList.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartList.toString">toString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartList.get">get</a></code> | *No description.* |

---

##### `allWithMapKey` <a name="allWithMapKey" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartList.allWithMapKey"></a>

```typescript
public allWithMapKey(mapKeyAttributeName: string): DynamicListTerraformIterator
```

Creating an iterator for this complex list.

The list will be converted into a map with the mapKeyAttributeName as the key.

###### `mapKeyAttributeName`<sup>Required</sup> <a name="mapKeyAttributeName" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartList.allWithMapKey.parameter.mapKeyAttributeName"></a>

- *Type:* string

---

##### `computeFqn` <a name="computeFqn" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartList.computeFqn"></a>

```typescript
public computeFqn(): string
```

##### `resolve` <a name="resolve" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartList.resolve"></a>

```typescript
public resolve(_context: IResolveContext): any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartList.resolve.parameter._context"></a>

- *Type:* cdktf.IResolveContext

---

##### `toString` <a name="toString" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartList.toString"></a>

```typescript
public toString(): string
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `get` <a name="get" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartList.get"></a>

```typescript
public get(index: number): DataCloudinitConfigPartOutputReference
```

###### `index`<sup>Required</sup> <a name="index" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartList.get.parameter.index"></a>

- *Type:* number

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartList.property.creationStack">creationStack</a></code> | <code>string[]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartList.property.fqn">fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartList.property.internalValue">internalValue</a></code> | <code>cdktf.IResolvable \| <a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPart">DataCloudinitConfigPart</a>[]</code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartList.property.creationStack"></a>

```typescript
public readonly creationStack: string[];
```

- *Type:* string[]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartList.property.fqn"></a>

```typescript
public readonly fqn: string;
```

- *Type:* string

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartList.property.internalValue"></a>

```typescript
public readonly internalValue: IResolvable | DataCloudinitConfigPart[];
```

- *Type:* cdktf.IResolvable | <a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPart">DataCloudinitConfigPart</a>[]

---


### DataCloudinitConfigPartOutputReference <a name="DataCloudinitConfigPartOutputReference" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference"></a>

#### Initializers <a name="Initializers" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.Initializer"></a>

```typescript
import { dataCloudinitConfig } from '@cdktn/provider-cloudinit'

new dataCloudinitConfig.DataCloudinitConfigPartOutputReference(terraformResource: IInterpolatingParent, terraformAttribute: string, complexObjectIndex: number, complexObjectIsFromSet: boolean)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.Initializer.parameter.complexObjectIndex">complexObjectIndex</a></code> | <code>number</code> | the index of this item in the list. |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.Initializer.parameter.complexObjectIsFromSet">complexObjectIsFromSet</a></code> | <code>boolean</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* cdktf.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* string

The attribute on the parent resource this class is referencing.

---

##### `complexObjectIndex`<sup>Required</sup> <a name="complexObjectIndex" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* number

the index of this item in the list.

---

##### `complexObjectIsFromSet`<sup>Required</sup> <a name="complexObjectIsFromSet" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* boolean

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.computeFqn">computeFqn</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.getAnyMapAttribute">getAnyMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.getBooleanAttribute">getBooleanAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.getBooleanMapAttribute">getBooleanMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.getListAttribute">getListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.getNumberAttribute">getNumberAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.getNumberListAttribute">getNumberListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.getNumberMapAttribute">getNumberMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.getStringAttribute">getStringAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.getStringMapAttribute">getStringMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.interpolationForAttribute">interpolationForAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.toString">toString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.resetContentType">resetContentType</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.resetFilename">resetFilename</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.resetMergeType">resetMergeType</a></code> | *No description.* |

---

##### `computeFqn` <a name="computeFqn" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.computeFqn"></a>

```typescript
public computeFqn(): string
```

##### `getAnyMapAttribute` <a name="getAnyMapAttribute" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.getAnyMapAttribute"></a>

```typescript
public getAnyMapAttribute(terraformAttribute: string): {[ key: string ]: any}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getBooleanAttribute` <a name="getBooleanAttribute" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.getBooleanAttribute"></a>

```typescript
public getBooleanAttribute(terraformAttribute: string): IResolvable
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getBooleanMapAttribute` <a name="getBooleanMapAttribute" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.getBooleanMapAttribute"></a>

```typescript
public getBooleanMapAttribute(terraformAttribute: string): {[ key: string ]: boolean}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getListAttribute` <a name="getListAttribute" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.getListAttribute"></a>

```typescript
public getListAttribute(terraformAttribute: string): string[]
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getNumberAttribute` <a name="getNumberAttribute" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.getNumberAttribute"></a>

```typescript
public getNumberAttribute(terraformAttribute: string): number
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getNumberListAttribute` <a name="getNumberListAttribute" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.getNumberListAttribute"></a>

```typescript
public getNumberListAttribute(terraformAttribute: string): number[]
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getNumberMapAttribute` <a name="getNumberMapAttribute" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.getNumberMapAttribute"></a>

```typescript
public getNumberMapAttribute(terraformAttribute: string): {[ key: string ]: number}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getStringAttribute` <a name="getStringAttribute" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.getStringAttribute"></a>

```typescript
public getStringAttribute(terraformAttribute: string): string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getStringMapAttribute` <a name="getStringMapAttribute" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.getStringMapAttribute"></a>

```typescript
public getStringMapAttribute(terraformAttribute: string): {[ key: string ]: string}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `interpolationForAttribute` <a name="interpolationForAttribute" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.interpolationForAttribute"></a>

```typescript
public interpolationForAttribute(property: string): IResolvable
```

###### `property`<sup>Required</sup> <a name="property" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* string

---

##### `resolve` <a name="resolve" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.resolve"></a>

```typescript
public resolve(_context: IResolveContext): any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.resolve.parameter._context"></a>

- *Type:* cdktf.IResolveContext

---

##### `toString` <a name="toString" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.toString"></a>

```typescript
public toString(): string
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `resetContentType` <a name="resetContentType" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.resetContentType"></a>

```typescript
public resetContentType(): void
```

##### `resetFilename` <a name="resetFilename" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.resetFilename"></a>

```typescript
public resetFilename(): void
```

##### `resetMergeType` <a name="resetMergeType" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.resetMergeType"></a>

```typescript
public resetMergeType(): void
```


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.property.creationStack">creationStack</a></code> | <code>string[]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.property.fqn">fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.property.contentInput">contentInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.property.contentTypeInput">contentTypeInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.property.filenameInput">filenameInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.property.mergeTypeInput">mergeTypeInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.property.content">content</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.property.contentType">contentType</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.property.filename">filename</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.property.mergeType">mergeType</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.property.internalValue">internalValue</a></code> | <code>cdktf.IResolvable \| <a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPart">DataCloudinitConfigPart</a></code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.property.creationStack"></a>

```typescript
public readonly creationStack: string[];
```

- *Type:* string[]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.property.fqn"></a>

```typescript
public readonly fqn: string;
```

- *Type:* string

---

##### `contentInput`<sup>Optional</sup> <a name="contentInput" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.property.contentInput"></a>

```typescript
public readonly contentInput: string;
```

- *Type:* string

---

##### `contentTypeInput`<sup>Optional</sup> <a name="contentTypeInput" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.property.contentTypeInput"></a>

```typescript
public readonly contentTypeInput: string;
```

- *Type:* string

---

##### `filenameInput`<sup>Optional</sup> <a name="filenameInput" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.property.filenameInput"></a>

```typescript
public readonly filenameInput: string;
```

- *Type:* string

---

##### `mergeTypeInput`<sup>Optional</sup> <a name="mergeTypeInput" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.property.mergeTypeInput"></a>

```typescript
public readonly mergeTypeInput: string;
```

- *Type:* string

---

##### `content`<sup>Required</sup> <a name="content" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.property.content"></a>

```typescript
public readonly content: string;
```

- *Type:* string

---

##### `contentType`<sup>Required</sup> <a name="contentType" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.property.contentType"></a>

```typescript
public readonly contentType: string;
```

- *Type:* string

---

##### `filename`<sup>Required</sup> <a name="filename" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.property.filename"></a>

```typescript
public readonly filename: string;
```

- *Type:* string

---

##### `mergeType`<sup>Required</sup> <a name="mergeType" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.property.mergeType"></a>

```typescript
public readonly mergeType: string;
```

- *Type:* string

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.property.internalValue"></a>

```typescript
public readonly internalValue: IResolvable | DataCloudinitConfigPart;
```

- *Type:* cdktf.IResolvable | <a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPart">DataCloudinitConfigPart</a>

---



