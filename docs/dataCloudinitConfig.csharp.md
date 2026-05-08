# `dataCloudinitConfig` Submodule <a name="`dataCloudinitConfig` Submodule" id="@cdktn/provider-cloudinit.dataCloudinitConfig"></a>

## Constructs <a name="Constructs" id="Constructs"></a>

### DataCloudinitConfig <a name="DataCloudinitConfig" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig"></a>

Represents a {@link https://registry.terraform.io/providers/hashicorp/cloudinit/2.3.7/docs/data-sources/config cloudinit_config}.

#### Initializers <a name="Initializers" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.Initializer"></a>

```csharp
using Io.Cdktn.Providers.Cloudinit;

new DataCloudinitConfig(Construct Scope, string Id, DataCloudinitConfigConfig Config = null);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.Initializer.parameter.scope">Scope</a></code> | <code>Constructs.Construct</code> | The scope in which to define this construct. |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.Initializer.parameter.id">Id</a></code> | <code>string</code> | The scoped construct ID. |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.Initializer.parameter.config">Config</a></code> | <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigConfig">DataCloudinitConfigConfig</a></code> | *No description.* |

---

##### `Scope`<sup>Required</sup> <a name="Scope" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.Initializer.parameter.scope"></a>

- *Type:* Constructs.Construct

The scope in which to define this construct.

---

##### `Id`<sup>Required</sup> <a name="Id" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.Initializer.parameter.id"></a>

- *Type:* string

The scoped construct ID.

Must be unique amongst siblings in the same scope

---

##### `Config`<sup>Optional</sup> <a name="Config" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.Initializer.parameter.config"></a>

- *Type:* <a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigConfig">DataCloudinitConfigConfig</a>

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.toString">ToString</a></code> | Returns a string representation of this construct. |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.with">With</a></code> | Applies one or more mixins to this construct. |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.addOverride">AddOverride</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.overrideLogicalId">OverrideLogicalId</a></code> | Overrides the auto-generated logical ID with a specific ID. |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.resetOverrideLogicalId">ResetOverrideLogicalId</a></code> | Resets a previously passed logical Id to use the auto-generated logical id again. |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.toHclTerraform">ToHclTerraform</a></code> | Adds this resource to the terraform JSON output. |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.toMetadata">ToMetadata</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.toTerraform">ToTerraform</a></code> | Adds this resource to the terraform JSON output. |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.getAnyMapAttribute">GetAnyMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.getBooleanAttribute">GetBooleanAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.getBooleanMapAttribute">GetBooleanMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.getListAttribute">GetListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.getNumberAttribute">GetNumberAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.getNumberListAttribute">GetNumberListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.getNumberMapAttribute">GetNumberMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.getStringAttribute">GetStringAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.getStringMapAttribute">GetStringMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.interpolationForAttribute">InterpolationForAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.putPart">PutPart</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.resetBase64Encode">ResetBase64Encode</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.resetBoundary">ResetBoundary</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.resetGzip">ResetGzip</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.resetPart">ResetPart</a></code> | *No description.* |

---

##### `ToString` <a name="ToString" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.toString"></a>

```csharp
private string ToString()
```

Returns a string representation of this construct.

##### `With` <a name="With" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.with"></a>

```csharp
private IConstruct With(params IMixin[] Mixins)
```

Applies one or more mixins to this construct.

Mixins are applied in order. The list of constructs is captured at the
start of the call, so constructs added by a mixin will not be visited.
Use multiple `with()` calls if subsequent mixins should apply to added
constructs.

###### `Mixins`<sup>Required</sup> <a name="Mixins" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.with.parameter.mixins"></a>

- *Type:* params Constructs.IMixin[]

The mixins to apply.

---

##### `AddOverride` <a name="AddOverride" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.addOverride"></a>

```csharp
private void AddOverride(string Path, object Value)
```

###### `Path`<sup>Required</sup> <a name="Path" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.addOverride.parameter.path"></a>

- *Type:* string

---

###### `Value`<sup>Required</sup> <a name="Value" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.addOverride.parameter.value"></a>

- *Type:* object

---

##### `OverrideLogicalId` <a name="OverrideLogicalId" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.overrideLogicalId"></a>

```csharp
private void OverrideLogicalId(string NewLogicalId)
```

Overrides the auto-generated logical ID with a specific ID.

###### `NewLogicalId`<sup>Required</sup> <a name="NewLogicalId" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.overrideLogicalId.parameter.newLogicalId"></a>

- *Type:* string

The new logical ID to use for this stack element.

---

##### `ResetOverrideLogicalId` <a name="ResetOverrideLogicalId" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.resetOverrideLogicalId"></a>

```csharp
private void ResetOverrideLogicalId()
```

Resets a previously passed logical Id to use the auto-generated logical id again.

##### `ToHclTerraform` <a name="ToHclTerraform" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.toHclTerraform"></a>

```csharp
private object ToHclTerraform()
```

Adds this resource to the terraform JSON output.

##### `ToMetadata` <a name="ToMetadata" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.toMetadata"></a>

```csharp
private object ToMetadata()
```

##### `ToTerraform` <a name="ToTerraform" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.toTerraform"></a>

```csharp
private object ToTerraform()
```

Adds this resource to the terraform JSON output.

##### `GetAnyMapAttribute` <a name="GetAnyMapAttribute" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.getAnyMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, object> GetAnyMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetBooleanAttribute` <a name="GetBooleanAttribute" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.getBooleanAttribute"></a>

```csharp
private IResolvable GetBooleanAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetBooleanMapAttribute` <a name="GetBooleanMapAttribute" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.getBooleanMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, bool> GetBooleanMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetListAttribute` <a name="GetListAttribute" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.getListAttribute"></a>

```csharp
private string[] GetListAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberAttribute` <a name="GetNumberAttribute" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.getNumberAttribute"></a>

```csharp
private double GetNumberAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberListAttribute` <a name="GetNumberListAttribute" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.getNumberListAttribute"></a>

```csharp
private double[] GetNumberListAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberMapAttribute` <a name="GetNumberMapAttribute" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.getNumberMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, double> GetNumberMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetStringAttribute` <a name="GetStringAttribute" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.getStringAttribute"></a>

```csharp
private string GetStringAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetStringMapAttribute` <a name="GetStringMapAttribute" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.getStringMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, string> GetStringMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `InterpolationForAttribute` <a name="InterpolationForAttribute" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.interpolationForAttribute"></a>

```csharp
private IResolvable InterpolationForAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.interpolationForAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `PutPart` <a name="PutPart" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.putPart"></a>

```csharp
private void PutPart(IResolvable|DataCloudinitConfigPart[] Value)
```

###### `Value`<sup>Required</sup> <a name="Value" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.putPart.parameter.value"></a>

- *Type:* Io.Cdktn.IResolvable|<a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPart">DataCloudinitConfigPart</a>[]

---

##### `ResetBase64Encode` <a name="ResetBase64Encode" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.resetBase64Encode"></a>

```csharp
private void ResetBase64Encode()
```

##### `ResetBoundary` <a name="ResetBoundary" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.resetBoundary"></a>

```csharp
private void ResetBoundary()
```

##### `ResetGzip` <a name="ResetGzip" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.resetGzip"></a>

```csharp
private void ResetGzip()
```

##### `ResetPart` <a name="ResetPart" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.resetPart"></a>

```csharp
private void ResetPart()
```

#### Static Functions <a name="Static Functions" id="Static Functions"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.isConstruct">IsConstruct</a></code> | Checks if `x` is a construct. |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.isTerraformElement">IsTerraformElement</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.isTerraformDataSource">IsTerraformDataSource</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.generateConfigForImport">GenerateConfigForImport</a></code> | Generates CDKTN code for importing a DataCloudinitConfig resource upon running "cdktn plan <stack-name>". |

---

##### `IsConstruct` <a name="IsConstruct" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.isConstruct"></a>

```csharp
using Io.Cdktn.Providers.Cloudinit;

DataCloudinitConfig.IsConstruct(object X);
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

###### `X`<sup>Required</sup> <a name="X" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.isConstruct.parameter.x"></a>

- *Type:* object

Any object.

---

##### `IsTerraformElement` <a name="IsTerraformElement" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.isTerraformElement"></a>

```csharp
using Io.Cdktn.Providers.Cloudinit;

DataCloudinitConfig.IsTerraformElement(object X);
```

###### `X`<sup>Required</sup> <a name="X" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.isTerraformElement.parameter.x"></a>

- *Type:* object

---

##### `IsTerraformDataSource` <a name="IsTerraformDataSource" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.isTerraformDataSource"></a>

```csharp
using Io.Cdktn.Providers.Cloudinit;

DataCloudinitConfig.IsTerraformDataSource(object X);
```

###### `X`<sup>Required</sup> <a name="X" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.isTerraformDataSource.parameter.x"></a>

- *Type:* object

---

##### `GenerateConfigForImport` <a name="GenerateConfigForImport" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.generateConfigForImport"></a>

```csharp
using Io.Cdktn.Providers.Cloudinit;

DataCloudinitConfig.GenerateConfigForImport(Construct Scope, string ImportToId, string ImportFromId, TerraformProvider Provider = null);
```

Generates CDKTN code for importing a DataCloudinitConfig resource upon running "cdktn plan <stack-name>".

###### `Scope`<sup>Required</sup> <a name="Scope" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.generateConfigForImport.parameter.scope"></a>

- *Type:* Constructs.Construct

The scope in which to define this construct.

---

###### `ImportToId`<sup>Required</sup> <a name="ImportToId" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.generateConfigForImport.parameter.importToId"></a>

- *Type:* string

The construct id used in the generated config for the DataCloudinitConfig to import.

---

###### `ImportFromId`<sup>Required</sup> <a name="ImportFromId" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.generateConfigForImport.parameter.importFromId"></a>

- *Type:* string

The id of the existing DataCloudinitConfig that should be imported.

Refer to the {@link https://registry.terraform.io/providers/hashicorp/cloudinit/2.3.7/docs/data-sources/config#import import section} in the documentation of this resource for the id to use

---

###### `Provider`<sup>Optional</sup> <a name="Provider" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.generateConfigForImport.parameter.provider"></a>

- *Type:* Io.Cdktn.TerraformProvider

? Optional instance of the provider where the DataCloudinitConfig to import is found.

---

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.property.node">Node</a></code> | <code>Constructs.Node</code> | The tree node. |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.property.cdktfStack">CdktfStack</a></code> | <code>Io.Cdktn.TerraformStack</code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.property.fqn">Fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.property.friendlyUniqueId">FriendlyUniqueId</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.property.terraformMetaArguments">TerraformMetaArguments</a></code> | <code>System.Collections.Generic.IDictionary<string, object></code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.property.terraformResourceType">TerraformResourceType</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.property.terraformGeneratorMetadata">TerraformGeneratorMetadata</a></code> | <code>Io.Cdktn.TerraformProviderGeneratorMetadata</code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.property.count">Count</a></code> | <code>double\|Io.Cdktn.TerraformCount</code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.property.dependsOn">DependsOn</a></code> | <code>string[]</code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.property.forEach">ForEach</a></code> | <code>Io.Cdktn.ITerraformIterator</code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.property.lifecycle">Lifecycle</a></code> | <code>Io.Cdktn.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.property.provider">Provider</a></code> | <code>Io.Cdktn.TerraformProvider</code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.property.id">Id</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.property.part">Part</a></code> | <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartList">DataCloudinitConfigPartList</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.property.rendered">Rendered</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.property.base64EncodeInput">Base64EncodeInput</a></code> | <code>bool\|Io.Cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.property.boundaryInput">BoundaryInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.property.gzipInput">GzipInput</a></code> | <code>bool\|Io.Cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.property.partInput">PartInput</a></code> | <code>Io.Cdktn.IResolvable\|<a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPart">DataCloudinitConfigPart</a>[]</code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.property.base64Encode">Base64Encode</a></code> | <code>bool\|Io.Cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.property.boundary">Boundary</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.property.gzip">Gzip</a></code> | <code>bool\|Io.Cdktn.IResolvable</code> | *No description.* |

---

##### `Node`<sup>Required</sup> <a name="Node" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.property.node"></a>

```csharp
public Node Node { get; }
```

- *Type:* Constructs.Node

The tree node.

---

##### `CdktfStack`<sup>Required</sup> <a name="CdktfStack" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.property.cdktfStack"></a>

```csharp
public TerraformStack CdktfStack { get; }
```

- *Type:* Io.Cdktn.TerraformStack

---

##### `Fqn`<sup>Required</sup> <a name="Fqn" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.property.fqn"></a>

```csharp
public string Fqn { get; }
```

- *Type:* string

---

##### `FriendlyUniqueId`<sup>Required</sup> <a name="FriendlyUniqueId" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.property.friendlyUniqueId"></a>

```csharp
public string FriendlyUniqueId { get; }
```

- *Type:* string

---

##### `TerraformMetaArguments`<sup>Required</sup> <a name="TerraformMetaArguments" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.property.terraformMetaArguments"></a>

```csharp
public System.Collections.Generic.IDictionary<string, object> TerraformMetaArguments { get; }
```

- *Type:* System.Collections.Generic.IDictionary<string, object>

---

##### `TerraformResourceType`<sup>Required</sup> <a name="TerraformResourceType" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.property.terraformResourceType"></a>

```csharp
public string TerraformResourceType { get; }
```

- *Type:* string

---

##### `TerraformGeneratorMetadata`<sup>Optional</sup> <a name="TerraformGeneratorMetadata" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.property.terraformGeneratorMetadata"></a>

```csharp
public TerraformProviderGeneratorMetadata TerraformGeneratorMetadata { get; }
```

- *Type:* Io.Cdktn.TerraformProviderGeneratorMetadata

---

##### `Count`<sup>Optional</sup> <a name="Count" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.property.count"></a>

```csharp
public double|TerraformCount Count { get; }
```

- *Type:* double|Io.Cdktn.TerraformCount

---

##### `DependsOn`<sup>Optional</sup> <a name="DependsOn" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.property.dependsOn"></a>

```csharp
public string[] DependsOn { get; }
```

- *Type:* string[]

---

##### `ForEach`<sup>Optional</sup> <a name="ForEach" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.property.forEach"></a>

```csharp
public ITerraformIterator ForEach { get; }
```

- *Type:* Io.Cdktn.ITerraformIterator

---

##### `Lifecycle`<sup>Optional</sup> <a name="Lifecycle" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.property.lifecycle"></a>

```csharp
public TerraformResourceLifecycle Lifecycle { get; }
```

- *Type:* Io.Cdktn.TerraformResourceLifecycle

---

##### `Provider`<sup>Optional</sup> <a name="Provider" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.property.provider"></a>

```csharp
public TerraformProvider Provider { get; }
```

- *Type:* Io.Cdktn.TerraformProvider

---

##### `Id`<sup>Required</sup> <a name="Id" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.property.id"></a>

```csharp
public string Id { get; }
```

- *Type:* string

---

##### `Part`<sup>Required</sup> <a name="Part" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.property.part"></a>

```csharp
public DataCloudinitConfigPartList Part { get; }
```

- *Type:* <a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartList">DataCloudinitConfigPartList</a>

---

##### `Rendered`<sup>Required</sup> <a name="Rendered" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.property.rendered"></a>

```csharp
public string Rendered { get; }
```

- *Type:* string

---

##### `Base64EncodeInput`<sup>Optional</sup> <a name="Base64EncodeInput" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.property.base64EncodeInput"></a>

```csharp
public bool|IResolvable Base64EncodeInput { get; }
```

- *Type:* bool|Io.Cdktn.IResolvable

---

##### `BoundaryInput`<sup>Optional</sup> <a name="BoundaryInput" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.property.boundaryInput"></a>

```csharp
public string BoundaryInput { get; }
```

- *Type:* string

---

##### `GzipInput`<sup>Optional</sup> <a name="GzipInput" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.property.gzipInput"></a>

```csharp
public bool|IResolvable GzipInput { get; }
```

- *Type:* bool|Io.Cdktn.IResolvable

---

##### `PartInput`<sup>Optional</sup> <a name="PartInput" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.property.partInput"></a>

```csharp
public IResolvable|DataCloudinitConfigPart[] PartInput { get; }
```

- *Type:* Io.Cdktn.IResolvable|<a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPart">DataCloudinitConfigPart</a>[]

---

##### `Base64Encode`<sup>Required</sup> <a name="Base64Encode" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.property.base64Encode"></a>

```csharp
public bool|IResolvable Base64Encode { get; }
```

- *Type:* bool|Io.Cdktn.IResolvable

---

##### `Boundary`<sup>Required</sup> <a name="Boundary" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.property.boundary"></a>

```csharp
public string Boundary { get; }
```

- *Type:* string

---

##### `Gzip`<sup>Required</sup> <a name="Gzip" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.property.gzip"></a>

```csharp
public bool|IResolvable Gzip { get; }
```

- *Type:* bool|Io.Cdktn.IResolvable

---

#### Constants <a name="Constants" id="Constants"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.property.tfResourceType">TfResourceType</a></code> | <code>string</code> | *No description.* |

---

##### `TfResourceType`<sup>Required</sup> <a name="TfResourceType" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.property.tfResourceType"></a>

```csharp
public string TfResourceType { get; }
```

- *Type:* string

---

## Structs <a name="Structs" id="Structs"></a>

### DataCloudinitConfigConfig <a name="DataCloudinitConfigConfig" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigConfig"></a>

#### Initializer <a name="Initializer" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigConfig.Initializer"></a>

```csharp
using Io.Cdktn.Providers.Cloudinit;

new DataCloudinitConfigConfig {
    SSHProvisionerConnection|WinrmProvisionerConnection Connection = null,
    double|TerraformCount Count = null,
    ITerraformDependable[] DependsOn = null,
    ITerraformIterator ForEach = null,
    TerraformResourceLifecycle Lifecycle = null,
    TerraformProvider Provider = null,
    (FileProvisioner|LocalExecProvisioner|RemoteExecProvisioner)[] Provisioners = null,
    bool|IResolvable Base64Encode = null,
    string Boundary = null,
    bool|IResolvable Gzip = null,
    IResolvable|DataCloudinitConfigPart[] Part = null
};
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigConfig.property.connection">Connection</a></code> | <code>Io.Cdktn.SSHProvisionerConnection\|Io.Cdktn.WinrmProvisionerConnection</code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigConfig.property.count">Count</a></code> | <code>double\|Io.Cdktn.TerraformCount</code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigConfig.property.dependsOn">DependsOn</a></code> | <code>Io.Cdktn.ITerraformDependable[]</code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigConfig.property.forEach">ForEach</a></code> | <code>Io.Cdktn.ITerraformIterator</code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigConfig.property.lifecycle">Lifecycle</a></code> | <code>Io.Cdktn.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigConfig.property.provider">Provider</a></code> | <code>Io.Cdktn.TerraformProvider</code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigConfig.property.provisioners">Provisioners</a></code> | <code>Io.Cdktn.FileProvisioner\|Io.Cdktn.LocalExecProvisioner\|Io.Cdktn.RemoteExecProvisioner[]</code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigConfig.property.base64Encode">Base64Encode</a></code> | <code>bool\|Io.Cdktn.IResolvable</code> | Specify whether or not to base64 encode the `rendered` output. |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigConfig.property.boundary">Boundary</a></code> | <code>string</code> | Specify the Writer's default boundary separator. Defaults to `MIMEBOUNDARY`. |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigConfig.property.gzip">Gzip</a></code> | <code>bool\|Io.Cdktn.IResolvable</code> | Specify whether or not to gzip the `rendered` output. Defaults to `true`. |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigConfig.property.part">Part</a></code> | <code>Io.Cdktn.IResolvable\|<a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPart">DataCloudinitConfigPart</a>[]</code> | part block. |

---

##### `Connection`<sup>Optional</sup> <a name="Connection" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigConfig.property.connection"></a>

```csharp
public SSHProvisionerConnection|WinrmProvisionerConnection Connection { get; set; }
```

- *Type:* Io.Cdktn.SSHProvisionerConnection|Io.Cdktn.WinrmProvisionerConnection

---

##### `Count`<sup>Optional</sup> <a name="Count" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigConfig.property.count"></a>

```csharp
public double|TerraformCount Count { get; set; }
```

- *Type:* double|Io.Cdktn.TerraformCount

---

##### `DependsOn`<sup>Optional</sup> <a name="DependsOn" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigConfig.property.dependsOn"></a>

```csharp
public ITerraformDependable[] DependsOn { get; set; }
```

- *Type:* Io.Cdktn.ITerraformDependable[]

---

##### `ForEach`<sup>Optional</sup> <a name="ForEach" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigConfig.property.forEach"></a>

```csharp
public ITerraformIterator ForEach { get; set; }
```

- *Type:* Io.Cdktn.ITerraformIterator

---

##### `Lifecycle`<sup>Optional</sup> <a name="Lifecycle" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigConfig.property.lifecycle"></a>

```csharp
public TerraformResourceLifecycle Lifecycle { get; set; }
```

- *Type:* Io.Cdktn.TerraformResourceLifecycle

---

##### `Provider`<sup>Optional</sup> <a name="Provider" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigConfig.property.provider"></a>

```csharp
public TerraformProvider Provider { get; set; }
```

- *Type:* Io.Cdktn.TerraformProvider

---

##### `Provisioners`<sup>Optional</sup> <a name="Provisioners" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigConfig.property.provisioners"></a>

```csharp
public (FileProvisioner|LocalExecProvisioner|RemoteExecProvisioner)[] Provisioners { get; set; }
```

- *Type:* Io.Cdktn.FileProvisioner|Io.Cdktn.LocalExecProvisioner|Io.Cdktn.RemoteExecProvisioner[]

---

##### `Base64Encode`<sup>Optional</sup> <a name="Base64Encode" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigConfig.property.base64Encode"></a>

```csharp
public bool|IResolvable Base64Encode { get; set; }
```

- *Type:* bool|Io.Cdktn.IResolvable

Specify whether or not to base64 encode the `rendered` output.

Defaults to `true`, and cannot be disabled if gzip is `true`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/hashicorp/cloudinit/2.3.7/docs/data-sources/config#base64_encode DataCloudinitConfig#base64_encode}

---

##### `Boundary`<sup>Optional</sup> <a name="Boundary" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigConfig.property.boundary"></a>

```csharp
public string Boundary { get; set; }
```

- *Type:* string

Specify the Writer's default boundary separator. Defaults to `MIMEBOUNDARY`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/hashicorp/cloudinit/2.3.7/docs/data-sources/config#boundary DataCloudinitConfig#boundary}

---

##### `Gzip`<sup>Optional</sup> <a name="Gzip" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigConfig.property.gzip"></a>

```csharp
public bool|IResolvable Gzip { get; set; }
```

- *Type:* bool|Io.Cdktn.IResolvable

Specify whether or not to gzip the `rendered` output. Defaults to `true`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/hashicorp/cloudinit/2.3.7/docs/data-sources/config#gzip DataCloudinitConfig#gzip}

---

##### `Part`<sup>Optional</sup> <a name="Part" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigConfig.property.part"></a>

```csharp
public IResolvable|DataCloudinitConfigPart[] Part { get; set; }
```

- *Type:* Io.Cdktn.IResolvable|<a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPart">DataCloudinitConfigPart</a>[]

part block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/hashicorp/cloudinit/2.3.7/docs/data-sources/config#part DataCloudinitConfig#part}

---

### DataCloudinitConfigPart <a name="DataCloudinitConfigPart" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPart"></a>

#### Initializer <a name="Initializer" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPart.Initializer"></a>

```csharp
using Io.Cdktn.Providers.Cloudinit;

new DataCloudinitConfigPart {
    string Content,
    string ContentType = null,
    string Filename = null,
    string MergeType = null
};
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPart.property.content">Content</a></code> | <code>string</code> | Body content for the part. |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPart.property.contentType">ContentType</a></code> | <code>string</code> | A MIME-style content type to report in the header for the part. Defaults to `text/plain`. |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPart.property.filename">Filename</a></code> | <code>string</code> | A filename to report in the header for the part. |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPart.property.mergeType">MergeType</a></code> | <code>string</code> | A value for the `X-Merge-Type` header of the part, to control [cloud-init merging behavior](https://cloudinit.readthedocs.io/en/latest/reference/merging.html). |

---

##### `Content`<sup>Required</sup> <a name="Content" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPart.property.content"></a>

```csharp
public string Content { get; set; }
```

- *Type:* string

Body content for the part.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/hashicorp/cloudinit/2.3.7/docs/data-sources/config#content DataCloudinitConfig#content}

---

##### `ContentType`<sup>Optional</sup> <a name="ContentType" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPart.property.contentType"></a>

```csharp
public string ContentType { get; set; }
```

- *Type:* string

A MIME-style content type to report in the header for the part. Defaults to `text/plain`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/hashicorp/cloudinit/2.3.7/docs/data-sources/config#content_type DataCloudinitConfig#content_type}

---

##### `Filename`<sup>Optional</sup> <a name="Filename" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPart.property.filename"></a>

```csharp
public string Filename { get; set; }
```

- *Type:* string

A filename to report in the header for the part.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/hashicorp/cloudinit/2.3.7/docs/data-sources/config#filename DataCloudinitConfig#filename}

---

##### `MergeType`<sup>Optional</sup> <a name="MergeType" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPart.property.mergeType"></a>

```csharp
public string MergeType { get; set; }
```

- *Type:* string

A value for the `X-Merge-Type` header of the part, to control [cloud-init merging behavior](https://cloudinit.readthedocs.io/en/latest/reference/merging.html).

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/hashicorp/cloudinit/2.3.7/docs/data-sources/config#merge_type DataCloudinitConfig#merge_type}

---

## Classes <a name="Classes" id="Classes"></a>

### DataCloudinitConfigPartList <a name="DataCloudinitConfigPartList" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartList"></a>

#### Initializers <a name="Initializers" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartList.Initializer"></a>

```csharp
using Io.Cdktn.Providers.Cloudinit;

new DataCloudinitConfigPartList(IInterpolatingParent TerraformResource, string TerraformAttribute, bool WrapsSet);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartList.Initializer.parameter.terraformResource">TerraformResource</a></code> | <code>Io.Cdktn.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartList.Initializer.parameter.terraformAttribute">TerraformAttribute</a></code> | <code>string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartList.Initializer.parameter.wrapsSet">WrapsSet</a></code> | <code>bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `TerraformResource`<sup>Required</sup> <a name="TerraformResource" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartList.Initializer.parameter.terraformResource"></a>

- *Type:* Io.Cdktn.IInterpolatingParent

The parent resource.

---

##### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartList.Initializer.parameter.terraformAttribute"></a>

- *Type:* string

The attribute on the parent resource this class is referencing.

---

##### `WrapsSet`<sup>Required</sup> <a name="WrapsSet" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartList.Initializer.parameter.wrapsSet"></a>

- *Type:* bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartList.allWithMapKey">AllWithMapKey</a></code> | Creating an iterator for this complex list. |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartList.computeFqn">ComputeFqn</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartList.resolve">Resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartList.toString">ToString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartList.get">Get</a></code> | *No description.* |

---

##### `AllWithMapKey` <a name="AllWithMapKey" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartList.allWithMapKey"></a>

```csharp
private DynamicListTerraformIterator AllWithMapKey(string MapKeyAttributeName)
```

Creating an iterator for this complex list.

The list will be converted into a map with the mapKeyAttributeName as the key.

###### `MapKeyAttributeName`<sup>Required</sup> <a name="MapKeyAttributeName" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartList.allWithMapKey.parameter.mapKeyAttributeName"></a>

- *Type:* string

---

##### `ComputeFqn` <a name="ComputeFqn" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartList.computeFqn"></a>

```csharp
private string ComputeFqn()
```

##### `Resolve` <a name="Resolve" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartList.resolve"></a>

```csharp
private object Resolve(IResolveContext Context)
```

Produce the Token's value at resolution time.

###### `Context`<sup>Required</sup> <a name="Context" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartList.resolve.parameter._context"></a>

- *Type:* Io.Cdktn.IResolveContext

---

##### `ToString` <a name="ToString" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartList.toString"></a>

```csharp
private string ToString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `Get` <a name="Get" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartList.get"></a>

```csharp
private DataCloudinitConfigPartOutputReference Get(double Index)
```

###### `Index`<sup>Required</sup> <a name="Index" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartList.get.parameter.index"></a>

- *Type:* double

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartList.property.creationStack">CreationStack</a></code> | <code>string[]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartList.property.fqn">Fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartList.property.internalValue">InternalValue</a></code> | <code>Io.Cdktn.IResolvable\|<a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPart">DataCloudinitConfigPart</a>[]</code> | *No description.* |

---

##### `CreationStack`<sup>Required</sup> <a name="CreationStack" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartList.property.creationStack"></a>

```csharp
public string[] CreationStack { get; }
```

- *Type:* string[]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `Fqn`<sup>Required</sup> <a name="Fqn" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartList.property.fqn"></a>

```csharp
public string Fqn { get; }
```

- *Type:* string

---

##### `InternalValue`<sup>Optional</sup> <a name="InternalValue" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartList.property.internalValue"></a>

```csharp
public IResolvable|DataCloudinitConfigPart[] InternalValue { get; }
```

- *Type:* Io.Cdktn.IResolvable|<a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPart">DataCloudinitConfigPart</a>[]

---


### DataCloudinitConfigPartOutputReference <a name="DataCloudinitConfigPartOutputReference" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference"></a>

#### Initializers <a name="Initializers" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.Initializer"></a>

```csharp
using Io.Cdktn.Providers.Cloudinit;

new DataCloudinitConfigPartOutputReference(IInterpolatingParent TerraformResource, string TerraformAttribute, double ComplexObjectIndex, bool ComplexObjectIsFromSet);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.Initializer.parameter.terraformResource">TerraformResource</a></code> | <code>Io.Cdktn.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.Initializer.parameter.terraformAttribute">TerraformAttribute</a></code> | <code>string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.Initializer.parameter.complexObjectIndex">ComplexObjectIndex</a></code> | <code>double</code> | the index of this item in the list. |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.Initializer.parameter.complexObjectIsFromSet">ComplexObjectIsFromSet</a></code> | <code>bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `TerraformResource`<sup>Required</sup> <a name="TerraformResource" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* Io.Cdktn.IInterpolatingParent

The parent resource.

---

##### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* string

The attribute on the parent resource this class is referencing.

---

##### `ComplexObjectIndex`<sup>Required</sup> <a name="ComplexObjectIndex" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* double

the index of this item in the list.

---

##### `ComplexObjectIsFromSet`<sup>Required</sup> <a name="ComplexObjectIsFromSet" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.computeFqn">ComputeFqn</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.getAnyMapAttribute">GetAnyMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.getBooleanAttribute">GetBooleanAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.getBooleanMapAttribute">GetBooleanMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.getListAttribute">GetListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.getNumberAttribute">GetNumberAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.getNumberListAttribute">GetNumberListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.getNumberMapAttribute">GetNumberMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.getStringAttribute">GetStringAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.getStringMapAttribute">GetStringMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.interpolationForAttribute">InterpolationForAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.resolve">Resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.toString">ToString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.resetContentType">ResetContentType</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.resetFilename">ResetFilename</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.resetMergeType">ResetMergeType</a></code> | *No description.* |

---

##### `ComputeFqn` <a name="ComputeFqn" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.computeFqn"></a>

```csharp
private string ComputeFqn()
```

##### `GetAnyMapAttribute` <a name="GetAnyMapAttribute" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.getAnyMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, object> GetAnyMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetBooleanAttribute` <a name="GetBooleanAttribute" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.getBooleanAttribute"></a>

```csharp
private IResolvable GetBooleanAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetBooleanMapAttribute` <a name="GetBooleanMapAttribute" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.getBooleanMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, bool> GetBooleanMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetListAttribute` <a name="GetListAttribute" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.getListAttribute"></a>

```csharp
private string[] GetListAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberAttribute` <a name="GetNumberAttribute" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.getNumberAttribute"></a>

```csharp
private double GetNumberAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberListAttribute` <a name="GetNumberListAttribute" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.getNumberListAttribute"></a>

```csharp
private double[] GetNumberListAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberMapAttribute` <a name="GetNumberMapAttribute" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.getNumberMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, double> GetNumberMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetStringAttribute` <a name="GetStringAttribute" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.getStringAttribute"></a>

```csharp
private string GetStringAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetStringMapAttribute` <a name="GetStringMapAttribute" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.getStringMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, string> GetStringMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `InterpolationForAttribute` <a name="InterpolationForAttribute" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.interpolationForAttribute"></a>

```csharp
private IResolvable InterpolationForAttribute(string Property)
```

###### `Property`<sup>Required</sup> <a name="Property" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* string

---

##### `Resolve` <a name="Resolve" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.resolve"></a>

```csharp
private object Resolve(IResolveContext Context)
```

Produce the Token's value at resolution time.

###### `Context`<sup>Required</sup> <a name="Context" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.resolve.parameter._context"></a>

- *Type:* Io.Cdktn.IResolveContext

---

##### `ToString` <a name="ToString" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.toString"></a>

```csharp
private string ToString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `ResetContentType` <a name="ResetContentType" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.resetContentType"></a>

```csharp
private void ResetContentType()
```

##### `ResetFilename` <a name="ResetFilename" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.resetFilename"></a>

```csharp
private void ResetFilename()
```

##### `ResetMergeType` <a name="ResetMergeType" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.resetMergeType"></a>

```csharp
private void ResetMergeType()
```


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.property.creationStack">CreationStack</a></code> | <code>string[]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.property.fqn">Fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.property.contentInput">ContentInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.property.contentTypeInput">ContentTypeInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.property.filenameInput">FilenameInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.property.mergeTypeInput">MergeTypeInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.property.content">Content</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.property.contentType">ContentType</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.property.filename">Filename</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.property.mergeType">MergeType</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.property.internalValue">InternalValue</a></code> | <code>Io.Cdktn.IResolvable\|<a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPart">DataCloudinitConfigPart</a></code> | *No description.* |

---

##### `CreationStack`<sup>Required</sup> <a name="CreationStack" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.property.creationStack"></a>

```csharp
public string[] CreationStack { get; }
```

- *Type:* string[]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `Fqn`<sup>Required</sup> <a name="Fqn" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.property.fqn"></a>

```csharp
public string Fqn { get; }
```

- *Type:* string

---

##### `ContentInput`<sup>Optional</sup> <a name="ContentInput" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.property.contentInput"></a>

```csharp
public string ContentInput { get; }
```

- *Type:* string

---

##### `ContentTypeInput`<sup>Optional</sup> <a name="ContentTypeInput" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.property.contentTypeInput"></a>

```csharp
public string ContentTypeInput { get; }
```

- *Type:* string

---

##### `FilenameInput`<sup>Optional</sup> <a name="FilenameInput" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.property.filenameInput"></a>

```csharp
public string FilenameInput { get; }
```

- *Type:* string

---

##### `MergeTypeInput`<sup>Optional</sup> <a name="MergeTypeInput" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.property.mergeTypeInput"></a>

```csharp
public string MergeTypeInput { get; }
```

- *Type:* string

---

##### `Content`<sup>Required</sup> <a name="Content" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.property.content"></a>

```csharp
public string Content { get; }
```

- *Type:* string

---

##### `ContentType`<sup>Required</sup> <a name="ContentType" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.property.contentType"></a>

```csharp
public string ContentType { get; }
```

- *Type:* string

---

##### `Filename`<sup>Required</sup> <a name="Filename" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.property.filename"></a>

```csharp
public string Filename { get; }
```

- *Type:* string

---

##### `MergeType`<sup>Required</sup> <a name="MergeType" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.property.mergeType"></a>

```csharp
public string MergeType { get; }
```

- *Type:* string

---

##### `InternalValue`<sup>Optional</sup> <a name="InternalValue" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.property.internalValue"></a>

```csharp
public IResolvable|DataCloudinitConfigPart InternalValue { get; }
```

- *Type:* Io.Cdktn.IResolvable|<a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPart">DataCloudinitConfigPart</a>

---



