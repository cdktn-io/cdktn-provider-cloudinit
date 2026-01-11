# `dataCloudinitConfig` Submodule <a name="`dataCloudinitConfig` Submodule" id="@cdktn/provider-cloudinit.dataCloudinitConfig"></a>

## Constructs <a name="Constructs" id="Constructs"></a>

### DataCloudinitConfig <a name="DataCloudinitConfig" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig"></a>

Represents a {@link https://registry.terraform.io/providers/hashicorp/cloudinit/2.3.7/docs/data-sources/config cloudinit_config}.

#### Initializers <a name="Initializers" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.Initializer"></a>

```go
import "github.com/cdktn-io/cdktn-provider-cloudinit-go/cloudinit/v11/datacloudinitconfig"

datacloudinitconfig.NewDataCloudinitConfig(scope Construct, id *string, config DataCloudinitConfigConfig) DataCloudinitConfig
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.Initializer.parameter.scope">scope</a></code> | <code>github.com/aws/constructs-go/constructs/v10.Construct</code> | The scope in which to define this construct. |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.Initializer.parameter.id">id</a></code> | <code>*string</code> | The scoped construct ID. |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.Initializer.parameter.config">config</a></code> | <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigConfig">DataCloudinitConfigConfig</a></code> | *No description.* |

---

##### `scope`<sup>Required</sup> <a name="scope" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.Initializer.parameter.scope"></a>

- *Type:* github.com/aws/constructs-go/constructs/v10.Construct

The scope in which to define this construct.

---

##### `id`<sup>Required</sup> <a name="id" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.Initializer.parameter.id"></a>

- *Type:* *string

The scoped construct ID.

Must be unique amongst siblings in the same scope

---

##### `config`<sup>Optional</sup> <a name="config" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.Initializer.parameter.config"></a>

- *Type:* <a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigConfig">DataCloudinitConfigConfig</a>

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.toString">ToString</a></code> | Returns a string representation of this construct. |
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

```go
func ToString() *string
```

Returns a string representation of this construct.

##### `AddOverride` <a name="AddOverride" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.addOverride"></a>

```go
func AddOverride(path *string, value interface{})
```

###### `path`<sup>Required</sup> <a name="path" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.addOverride.parameter.path"></a>

- *Type:* *string

---

###### `value`<sup>Required</sup> <a name="value" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.addOverride.parameter.value"></a>

- *Type:* interface{}

---

##### `OverrideLogicalId` <a name="OverrideLogicalId" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.overrideLogicalId"></a>

```go
func OverrideLogicalId(newLogicalId *string)
```

Overrides the auto-generated logical ID with a specific ID.

###### `newLogicalId`<sup>Required</sup> <a name="newLogicalId" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.overrideLogicalId.parameter.newLogicalId"></a>

- *Type:* *string

The new logical ID to use for this stack element.

---

##### `ResetOverrideLogicalId` <a name="ResetOverrideLogicalId" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.resetOverrideLogicalId"></a>

```go
func ResetOverrideLogicalId()
```

Resets a previously passed logical Id to use the auto-generated logical id again.

##### `ToHclTerraform` <a name="ToHclTerraform" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.toHclTerraform"></a>

```go
func ToHclTerraform() interface{}
```

Adds this resource to the terraform JSON output.

##### `ToMetadata` <a name="ToMetadata" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.toMetadata"></a>

```go
func ToMetadata() interface{}
```

##### `ToTerraform` <a name="ToTerraform" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.toTerraform"></a>

```go
func ToTerraform() interface{}
```

Adds this resource to the terraform JSON output.

##### `GetAnyMapAttribute` <a name="GetAnyMapAttribute" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.getAnyMapAttribute"></a>

```go
func GetAnyMapAttribute(terraformAttribute *string) *map[string]interface{}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetBooleanAttribute` <a name="GetBooleanAttribute" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.getBooleanAttribute"></a>

```go
func GetBooleanAttribute(terraformAttribute *string) IResolvable
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetBooleanMapAttribute` <a name="GetBooleanMapAttribute" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.getBooleanMapAttribute"></a>

```go
func GetBooleanMapAttribute(terraformAttribute *string) *map[string]*bool
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetListAttribute` <a name="GetListAttribute" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.getListAttribute"></a>

```go
func GetListAttribute(terraformAttribute *string) *[]*string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetNumberAttribute` <a name="GetNumberAttribute" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.getNumberAttribute"></a>

```go
func GetNumberAttribute(terraformAttribute *string) *f64
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetNumberListAttribute` <a name="GetNumberListAttribute" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.getNumberListAttribute"></a>

```go
func GetNumberListAttribute(terraformAttribute *string) *[]*f64
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetNumberMapAttribute` <a name="GetNumberMapAttribute" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.getNumberMapAttribute"></a>

```go
func GetNumberMapAttribute(terraformAttribute *string) *map[string]*f64
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetStringAttribute` <a name="GetStringAttribute" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.getStringAttribute"></a>

```go
func GetStringAttribute(terraformAttribute *string) *string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetStringMapAttribute` <a name="GetStringMapAttribute" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.getStringMapAttribute"></a>

```go
func GetStringMapAttribute(terraformAttribute *string) *map[string]*string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `InterpolationForAttribute` <a name="InterpolationForAttribute" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.interpolationForAttribute"></a>

```go
func InterpolationForAttribute(terraformAttribute *string) IResolvable
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.interpolationForAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `PutPart` <a name="PutPart" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.putPart"></a>

```go
func PutPart(value interface{})
```

###### `value`<sup>Required</sup> <a name="value" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.putPart.parameter.value"></a>

- *Type:* interface{}

---

##### `ResetBase64Encode` <a name="ResetBase64Encode" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.resetBase64Encode"></a>

```go
func ResetBase64Encode()
```

##### `ResetBoundary` <a name="ResetBoundary" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.resetBoundary"></a>

```go
func ResetBoundary()
```

##### `ResetGzip` <a name="ResetGzip" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.resetGzip"></a>

```go
func ResetGzip()
```

##### `ResetPart` <a name="ResetPart" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.resetPart"></a>

```go
func ResetPart()
```

#### Static Functions <a name="Static Functions" id="Static Functions"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.isConstruct">IsConstruct</a></code> | Checks if `x` is a construct. |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.isTerraformElement">IsTerraformElement</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.isTerraformDataSource">IsTerraformDataSource</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.generateConfigForImport">GenerateConfigForImport</a></code> | Generates CDKTF code for importing a DataCloudinitConfig resource upon running "cdktf plan <stack-name>". |

---

##### `IsConstruct` <a name="IsConstruct" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.isConstruct"></a>

```go
import "github.com/cdktn-io/cdktn-provider-cloudinit-go/cloudinit/v11/datacloudinitconfig"

datacloudinitconfig.DataCloudinitConfig_IsConstruct(x interface{}) *bool
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

- *Type:* interface{}

Any object.

---

##### `IsTerraformElement` <a name="IsTerraformElement" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.isTerraformElement"></a>

```go
import "github.com/cdktn-io/cdktn-provider-cloudinit-go/cloudinit/v11/datacloudinitconfig"

datacloudinitconfig.DataCloudinitConfig_IsTerraformElement(x interface{}) *bool
```

###### `x`<sup>Required</sup> <a name="x" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.isTerraformElement.parameter.x"></a>

- *Type:* interface{}

---

##### `IsTerraformDataSource` <a name="IsTerraformDataSource" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.isTerraformDataSource"></a>

```go
import "github.com/cdktn-io/cdktn-provider-cloudinit-go/cloudinit/v11/datacloudinitconfig"

datacloudinitconfig.DataCloudinitConfig_IsTerraformDataSource(x interface{}) *bool
```

###### `x`<sup>Required</sup> <a name="x" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.isTerraformDataSource.parameter.x"></a>

- *Type:* interface{}

---

##### `GenerateConfigForImport` <a name="GenerateConfigForImport" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.generateConfigForImport"></a>

```go
import "github.com/cdktn-io/cdktn-provider-cloudinit-go/cloudinit/v11/datacloudinitconfig"

datacloudinitconfig.DataCloudinitConfig_GenerateConfigForImport(scope Construct, importToId *string, importFromId *string, provider TerraformProvider) ImportableResource
```

Generates CDKTF code for importing a DataCloudinitConfig resource upon running "cdktf plan <stack-name>".

###### `scope`<sup>Required</sup> <a name="scope" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.generateConfigForImport.parameter.scope"></a>

- *Type:* github.com/aws/constructs-go/constructs/v10.Construct

The scope in which to define this construct.

---

###### `importToId`<sup>Required</sup> <a name="importToId" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.generateConfigForImport.parameter.importToId"></a>

- *Type:* *string

The construct id used in the generated config for the DataCloudinitConfig to import.

---

###### `importFromId`<sup>Required</sup> <a name="importFromId" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.generateConfigForImport.parameter.importFromId"></a>

- *Type:* *string

The id of the existing DataCloudinitConfig that should be imported.

Refer to the {@link https://registry.terraform.io/providers/hashicorp/cloudinit/2.3.7/docs/data-sources/config#import import section} in the documentation of this resource for the id to use

---

###### `provider`<sup>Optional</sup> <a name="provider" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.generateConfigForImport.parameter.provider"></a>

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.TerraformProvider

? Optional instance of the provider where the DataCloudinitConfig to import is found.

---

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.property.node">Node</a></code> | <code>github.com/aws/constructs-go/constructs/v10.Node</code> | The tree node. |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.property.cdktfStack">CdktfStack</a></code> | <code>github.com/hashicorp/terraform-cdk-go/cdktf.TerraformStack</code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.property.fqn">Fqn</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.property.friendlyUniqueId">FriendlyUniqueId</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.property.terraformMetaArguments">TerraformMetaArguments</a></code> | <code>*map[string]interface{}</code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.property.terraformResourceType">TerraformResourceType</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.property.terraformGeneratorMetadata">TerraformGeneratorMetadata</a></code> | <code>github.com/hashicorp/terraform-cdk-go/cdktf.TerraformProviderGeneratorMetadata</code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.property.count">Count</a></code> | <code>interface{}</code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.property.dependsOn">DependsOn</a></code> | <code>*[]*string</code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.property.forEach">ForEach</a></code> | <code>github.com/hashicorp/terraform-cdk-go/cdktf.ITerraformIterator</code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.property.lifecycle">Lifecycle</a></code> | <code>github.com/hashicorp/terraform-cdk-go/cdktf.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.property.provider">Provider</a></code> | <code>github.com/hashicorp/terraform-cdk-go/cdktf.TerraformProvider</code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.property.id">Id</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.property.part">Part</a></code> | <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartList">DataCloudinitConfigPartList</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.property.rendered">Rendered</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.property.base64EncodeInput">Base64EncodeInput</a></code> | <code>interface{}</code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.property.boundaryInput">BoundaryInput</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.property.gzipInput">GzipInput</a></code> | <code>interface{}</code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.property.partInput">PartInput</a></code> | <code>interface{}</code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.property.base64Encode">Base64Encode</a></code> | <code>interface{}</code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.property.boundary">Boundary</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.property.gzip">Gzip</a></code> | <code>interface{}</code> | *No description.* |

---

##### `Node`<sup>Required</sup> <a name="Node" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.property.node"></a>

```go
func Node() Node
```

- *Type:* github.com/aws/constructs-go/constructs/v10.Node

The tree node.

---

##### `CdktfStack`<sup>Required</sup> <a name="CdktfStack" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.property.cdktfStack"></a>

```go
func CdktfStack() TerraformStack
```

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.TerraformStack

---

##### `Fqn`<sup>Required</sup> <a name="Fqn" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.property.fqn"></a>

```go
func Fqn() *string
```

- *Type:* *string

---

##### `FriendlyUniqueId`<sup>Required</sup> <a name="FriendlyUniqueId" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.property.friendlyUniqueId"></a>

```go
func FriendlyUniqueId() *string
```

- *Type:* *string

---

##### `TerraformMetaArguments`<sup>Required</sup> <a name="TerraformMetaArguments" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.property.terraformMetaArguments"></a>

```go
func TerraformMetaArguments() *map[string]interface{}
```

- *Type:* *map[string]interface{}

---

##### `TerraformResourceType`<sup>Required</sup> <a name="TerraformResourceType" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.property.terraformResourceType"></a>

```go
func TerraformResourceType() *string
```

- *Type:* *string

---

##### `TerraformGeneratorMetadata`<sup>Optional</sup> <a name="TerraformGeneratorMetadata" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.property.terraformGeneratorMetadata"></a>

```go
func TerraformGeneratorMetadata() TerraformProviderGeneratorMetadata
```

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.TerraformProviderGeneratorMetadata

---

##### `Count`<sup>Optional</sup> <a name="Count" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.property.count"></a>

```go
func Count() interface{}
```

- *Type:* interface{}

---

##### `DependsOn`<sup>Optional</sup> <a name="DependsOn" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.property.dependsOn"></a>

```go
func DependsOn() *[]*string
```

- *Type:* *[]*string

---

##### `ForEach`<sup>Optional</sup> <a name="ForEach" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.property.forEach"></a>

```go
func ForEach() ITerraformIterator
```

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.ITerraformIterator

---

##### `Lifecycle`<sup>Optional</sup> <a name="Lifecycle" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.property.lifecycle"></a>

```go
func Lifecycle() TerraformResourceLifecycle
```

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.TerraformResourceLifecycle

---

##### `Provider`<sup>Optional</sup> <a name="Provider" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.property.provider"></a>

```go
func Provider() TerraformProvider
```

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.TerraformProvider

---

##### `Id`<sup>Required</sup> <a name="Id" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.property.id"></a>

```go
func Id() *string
```

- *Type:* *string

---

##### `Part`<sup>Required</sup> <a name="Part" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.property.part"></a>

```go
func Part() DataCloudinitConfigPartList
```

- *Type:* <a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartList">DataCloudinitConfigPartList</a>

---

##### `Rendered`<sup>Required</sup> <a name="Rendered" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.property.rendered"></a>

```go
func Rendered() *string
```

- *Type:* *string

---

##### `Base64EncodeInput`<sup>Optional</sup> <a name="Base64EncodeInput" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.property.base64EncodeInput"></a>

```go
func Base64EncodeInput() interface{}
```

- *Type:* interface{}

---

##### `BoundaryInput`<sup>Optional</sup> <a name="BoundaryInput" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.property.boundaryInput"></a>

```go
func BoundaryInput() *string
```

- *Type:* *string

---

##### `GzipInput`<sup>Optional</sup> <a name="GzipInput" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.property.gzipInput"></a>

```go
func GzipInput() interface{}
```

- *Type:* interface{}

---

##### `PartInput`<sup>Optional</sup> <a name="PartInput" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.property.partInput"></a>

```go
func PartInput() interface{}
```

- *Type:* interface{}

---

##### `Base64Encode`<sup>Required</sup> <a name="Base64Encode" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.property.base64Encode"></a>

```go
func Base64Encode() interface{}
```

- *Type:* interface{}

---

##### `Boundary`<sup>Required</sup> <a name="Boundary" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.property.boundary"></a>

```go
func Boundary() *string
```

- *Type:* *string

---

##### `Gzip`<sup>Required</sup> <a name="Gzip" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.property.gzip"></a>

```go
func Gzip() interface{}
```

- *Type:* interface{}

---

#### Constants <a name="Constants" id="Constants"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.property.tfResourceType">TfResourceType</a></code> | <code>*string</code> | *No description.* |

---

##### `TfResourceType`<sup>Required</sup> <a name="TfResourceType" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.property.tfResourceType"></a>

```go
func TfResourceType() *string
```

- *Type:* *string

---

## Structs <a name="Structs" id="Structs"></a>

### DataCloudinitConfigConfig <a name="DataCloudinitConfigConfig" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigConfig"></a>

#### Initializer <a name="Initializer" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigConfig.Initializer"></a>

```go
import "github.com/cdktn-io/cdktn-provider-cloudinit-go/cloudinit/v11/datacloudinitconfig"

&datacloudinitconfig.DataCloudinitConfigConfig {
	Connection: interface{},
	Count: interface{},
	DependsOn: *[]github.com/hashicorp/terraform-cdk-go/cdktf.ITerraformDependable,
	ForEach: github.com/hashicorp/terraform-cdk-go/cdktf.ITerraformIterator,
	Lifecycle: github.com/hashicorp/terraform-cdk-go/cdktf.TerraformResourceLifecycle,
	Provider: github.com/hashicorp/terraform-cdk-go/cdktf.TerraformProvider,
	Provisioners: *[]interface{},
	Base64Encode: interface{},
	Boundary: *string,
	Gzip: interface{},
	Part: interface{},
}
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigConfig.property.connection">Connection</a></code> | <code>interface{}</code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigConfig.property.count">Count</a></code> | <code>interface{}</code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigConfig.property.dependsOn">DependsOn</a></code> | <code>*[]github.com/hashicorp/terraform-cdk-go/cdktf.ITerraformDependable</code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigConfig.property.forEach">ForEach</a></code> | <code>github.com/hashicorp/terraform-cdk-go/cdktf.ITerraformIterator</code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigConfig.property.lifecycle">Lifecycle</a></code> | <code>github.com/hashicorp/terraform-cdk-go/cdktf.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigConfig.property.provider">Provider</a></code> | <code>github.com/hashicorp/terraform-cdk-go/cdktf.TerraformProvider</code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigConfig.property.provisioners">Provisioners</a></code> | <code>*[]interface{}</code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigConfig.property.base64Encode">Base64Encode</a></code> | <code>interface{}</code> | Specify whether or not to base64 encode the `rendered` output. |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigConfig.property.boundary">Boundary</a></code> | <code>*string</code> | Specify the Writer's default boundary separator. Defaults to `MIMEBOUNDARY`. |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigConfig.property.gzip">Gzip</a></code> | <code>interface{}</code> | Specify whether or not to gzip the `rendered` output. Defaults to `true`. |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigConfig.property.part">Part</a></code> | <code>interface{}</code> | part block. |

---

##### `Connection`<sup>Optional</sup> <a name="Connection" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigConfig.property.connection"></a>

```go
Connection interface{}
```

- *Type:* interface{}

---

##### `Count`<sup>Optional</sup> <a name="Count" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigConfig.property.count"></a>

```go
Count interface{}
```

- *Type:* interface{}

---

##### `DependsOn`<sup>Optional</sup> <a name="DependsOn" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigConfig.property.dependsOn"></a>

```go
DependsOn *[]ITerraformDependable
```

- *Type:* *[]github.com/hashicorp/terraform-cdk-go/cdktf.ITerraformDependable

---

##### `ForEach`<sup>Optional</sup> <a name="ForEach" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigConfig.property.forEach"></a>

```go
ForEach ITerraformIterator
```

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.ITerraformIterator

---

##### `Lifecycle`<sup>Optional</sup> <a name="Lifecycle" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigConfig.property.lifecycle"></a>

```go
Lifecycle TerraformResourceLifecycle
```

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.TerraformResourceLifecycle

---

##### `Provider`<sup>Optional</sup> <a name="Provider" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigConfig.property.provider"></a>

```go
Provider TerraformProvider
```

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.TerraformProvider

---

##### `Provisioners`<sup>Optional</sup> <a name="Provisioners" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigConfig.property.provisioners"></a>

```go
Provisioners *[]interface{}
```

- *Type:* *[]interface{}

---

##### `Base64Encode`<sup>Optional</sup> <a name="Base64Encode" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigConfig.property.base64Encode"></a>

```go
Base64Encode interface{}
```

- *Type:* interface{}

Specify whether or not to base64 encode the `rendered` output.

Defaults to `true`, and cannot be disabled if gzip is `true`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/hashicorp/cloudinit/2.3.7/docs/data-sources/config#base64_encode DataCloudinitConfig#base64_encode}

---

##### `Boundary`<sup>Optional</sup> <a name="Boundary" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigConfig.property.boundary"></a>

```go
Boundary *string
```

- *Type:* *string

Specify the Writer's default boundary separator. Defaults to `MIMEBOUNDARY`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/hashicorp/cloudinit/2.3.7/docs/data-sources/config#boundary DataCloudinitConfig#boundary}

---

##### `Gzip`<sup>Optional</sup> <a name="Gzip" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigConfig.property.gzip"></a>

```go
Gzip interface{}
```

- *Type:* interface{}

Specify whether or not to gzip the `rendered` output. Defaults to `true`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/hashicorp/cloudinit/2.3.7/docs/data-sources/config#gzip DataCloudinitConfig#gzip}

---

##### `Part`<sup>Optional</sup> <a name="Part" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigConfig.property.part"></a>

```go
Part interface{}
```

- *Type:* interface{}

part block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/hashicorp/cloudinit/2.3.7/docs/data-sources/config#part DataCloudinitConfig#part}

---

### DataCloudinitConfigPart <a name="DataCloudinitConfigPart" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPart"></a>

#### Initializer <a name="Initializer" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPart.Initializer"></a>

```go
import "github.com/cdktn-io/cdktn-provider-cloudinit-go/cloudinit/v11/datacloudinitconfig"

&datacloudinitconfig.DataCloudinitConfigPart {
	Content: *string,
	ContentType: *string,
	Filename: *string,
	MergeType: *string,
}
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPart.property.content">Content</a></code> | <code>*string</code> | Body content for the part. |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPart.property.contentType">ContentType</a></code> | <code>*string</code> | A MIME-style content type to report in the header for the part. Defaults to `text/plain`. |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPart.property.filename">Filename</a></code> | <code>*string</code> | A filename to report in the header for the part. |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPart.property.mergeType">MergeType</a></code> | <code>*string</code> | A value for the `X-Merge-Type` header of the part, to control [cloud-init merging behavior](https://cloudinit.readthedocs.io/en/latest/reference/merging.html). |

---

##### `Content`<sup>Required</sup> <a name="Content" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPart.property.content"></a>

```go
Content *string
```

- *Type:* *string

Body content for the part.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/hashicorp/cloudinit/2.3.7/docs/data-sources/config#content DataCloudinitConfig#content}

---

##### `ContentType`<sup>Optional</sup> <a name="ContentType" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPart.property.contentType"></a>

```go
ContentType *string
```

- *Type:* *string

A MIME-style content type to report in the header for the part. Defaults to `text/plain`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/hashicorp/cloudinit/2.3.7/docs/data-sources/config#content_type DataCloudinitConfig#content_type}

---

##### `Filename`<sup>Optional</sup> <a name="Filename" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPart.property.filename"></a>

```go
Filename *string
```

- *Type:* *string

A filename to report in the header for the part.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/hashicorp/cloudinit/2.3.7/docs/data-sources/config#filename DataCloudinitConfig#filename}

---

##### `MergeType`<sup>Optional</sup> <a name="MergeType" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPart.property.mergeType"></a>

```go
MergeType *string
```

- *Type:* *string

A value for the `X-Merge-Type` header of the part, to control [cloud-init merging behavior](https://cloudinit.readthedocs.io/en/latest/reference/merging.html).

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/hashicorp/cloudinit/2.3.7/docs/data-sources/config#merge_type DataCloudinitConfig#merge_type}

---

## Classes <a name="Classes" id="Classes"></a>

### DataCloudinitConfigPartList <a name="DataCloudinitConfigPartList" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartList"></a>

#### Initializers <a name="Initializers" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartList.Initializer"></a>

```go
import "github.com/cdktn-io/cdktn-provider-cloudinit-go/cloudinit/v11/datacloudinitconfig"

datacloudinitconfig.NewDataCloudinitConfigPartList(terraformResource IInterpolatingParent, terraformAttribute *string, wrapsSet *bool) DataCloudinitConfigPartList
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartList.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>github.com/hashicorp/terraform-cdk-go/cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartList.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>*string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartList.Initializer.parameter.wrapsSet">wrapsSet</a></code> | <code>*bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartList.Initializer.parameter.terraformResource"></a>

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartList.Initializer.parameter.terraformAttribute"></a>

- *Type:* *string

The attribute on the parent resource this class is referencing.

---

##### `wrapsSet`<sup>Required</sup> <a name="wrapsSet" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartList.Initializer.parameter.wrapsSet"></a>

- *Type:* *bool

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

```go
func AllWithMapKey(mapKeyAttributeName *string) DynamicListTerraformIterator
```

Creating an iterator for this complex list.

The list will be converted into a map with the mapKeyAttributeName as the key.

###### `mapKeyAttributeName`<sup>Required</sup> <a name="mapKeyAttributeName" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartList.allWithMapKey.parameter.mapKeyAttributeName"></a>

- *Type:* *string

---

##### `ComputeFqn` <a name="ComputeFqn" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartList.computeFqn"></a>

```go
func ComputeFqn() *string
```

##### `Resolve` <a name="Resolve" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartList.resolve"></a>

```go
func Resolve(_context IResolveContext) interface{}
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartList.resolve.parameter._context"></a>

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.IResolveContext

---

##### `ToString` <a name="ToString" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartList.toString"></a>

```go
func ToString() *string
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `Get` <a name="Get" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartList.get"></a>

```go
func Get(index *f64) DataCloudinitConfigPartOutputReference
```

###### `index`<sup>Required</sup> <a name="index" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartList.get.parameter.index"></a>

- *Type:* *f64

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartList.property.creationStack">CreationStack</a></code> | <code>*[]*string</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartList.property.fqn">Fqn</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartList.property.internalValue">InternalValue</a></code> | <code>interface{}</code> | *No description.* |

---

##### `CreationStack`<sup>Required</sup> <a name="CreationStack" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartList.property.creationStack"></a>

```go
func CreationStack() *[]*string
```

- *Type:* *[]*string

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `Fqn`<sup>Required</sup> <a name="Fqn" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartList.property.fqn"></a>

```go
func Fqn() *string
```

- *Type:* *string

---

##### `InternalValue`<sup>Optional</sup> <a name="InternalValue" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartList.property.internalValue"></a>

```go
func InternalValue() interface{}
```

- *Type:* interface{}

---


### DataCloudinitConfigPartOutputReference <a name="DataCloudinitConfigPartOutputReference" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference"></a>

#### Initializers <a name="Initializers" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.Initializer"></a>

```go
import "github.com/cdktn-io/cdktn-provider-cloudinit-go/cloudinit/v11/datacloudinitconfig"

datacloudinitconfig.NewDataCloudinitConfigPartOutputReference(terraformResource IInterpolatingParent, terraformAttribute *string, complexObjectIndex *f64, complexObjectIsFromSet *bool) DataCloudinitConfigPartOutputReference
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>github.com/hashicorp/terraform-cdk-go/cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>*string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.Initializer.parameter.complexObjectIndex">complexObjectIndex</a></code> | <code>*f64</code> | the index of this item in the list. |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.Initializer.parameter.complexObjectIsFromSet">complexObjectIsFromSet</a></code> | <code>*bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* *string

The attribute on the parent resource this class is referencing.

---

##### `complexObjectIndex`<sup>Required</sup> <a name="complexObjectIndex" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* *f64

the index of this item in the list.

---

##### `complexObjectIsFromSet`<sup>Required</sup> <a name="complexObjectIsFromSet" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* *bool

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

```go
func ComputeFqn() *string
```

##### `GetAnyMapAttribute` <a name="GetAnyMapAttribute" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.getAnyMapAttribute"></a>

```go
func GetAnyMapAttribute(terraformAttribute *string) *map[string]interface{}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetBooleanAttribute` <a name="GetBooleanAttribute" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.getBooleanAttribute"></a>

```go
func GetBooleanAttribute(terraformAttribute *string) IResolvable
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetBooleanMapAttribute` <a name="GetBooleanMapAttribute" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.getBooleanMapAttribute"></a>

```go
func GetBooleanMapAttribute(terraformAttribute *string) *map[string]*bool
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetListAttribute` <a name="GetListAttribute" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.getListAttribute"></a>

```go
func GetListAttribute(terraformAttribute *string) *[]*string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetNumberAttribute` <a name="GetNumberAttribute" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.getNumberAttribute"></a>

```go
func GetNumberAttribute(terraformAttribute *string) *f64
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetNumberListAttribute` <a name="GetNumberListAttribute" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.getNumberListAttribute"></a>

```go
func GetNumberListAttribute(terraformAttribute *string) *[]*f64
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetNumberMapAttribute` <a name="GetNumberMapAttribute" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.getNumberMapAttribute"></a>

```go
func GetNumberMapAttribute(terraformAttribute *string) *map[string]*f64
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetStringAttribute` <a name="GetStringAttribute" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.getStringAttribute"></a>

```go
func GetStringAttribute(terraformAttribute *string) *string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetStringMapAttribute` <a name="GetStringMapAttribute" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.getStringMapAttribute"></a>

```go
func GetStringMapAttribute(terraformAttribute *string) *map[string]*string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `InterpolationForAttribute` <a name="InterpolationForAttribute" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.interpolationForAttribute"></a>

```go
func InterpolationForAttribute(property *string) IResolvable
```

###### `property`<sup>Required</sup> <a name="property" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* *string

---

##### `Resolve` <a name="Resolve" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.resolve"></a>

```go
func Resolve(_context IResolveContext) interface{}
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.resolve.parameter._context"></a>

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.IResolveContext

---

##### `ToString` <a name="ToString" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.toString"></a>

```go
func ToString() *string
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `ResetContentType` <a name="ResetContentType" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.resetContentType"></a>

```go
func ResetContentType()
```

##### `ResetFilename` <a name="ResetFilename" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.resetFilename"></a>

```go
func ResetFilename()
```

##### `ResetMergeType` <a name="ResetMergeType" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.resetMergeType"></a>

```go
func ResetMergeType()
```


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.property.creationStack">CreationStack</a></code> | <code>*[]*string</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.property.fqn">Fqn</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.property.contentInput">ContentInput</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.property.contentTypeInput">ContentTypeInput</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.property.filenameInput">FilenameInput</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.property.mergeTypeInput">MergeTypeInput</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.property.content">Content</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.property.contentType">ContentType</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.property.filename">Filename</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.property.mergeType">MergeType</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.property.internalValue">InternalValue</a></code> | <code>interface{}</code> | *No description.* |

---

##### `CreationStack`<sup>Required</sup> <a name="CreationStack" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.property.creationStack"></a>

```go
func CreationStack() *[]*string
```

- *Type:* *[]*string

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `Fqn`<sup>Required</sup> <a name="Fqn" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.property.fqn"></a>

```go
func Fqn() *string
```

- *Type:* *string

---

##### `ContentInput`<sup>Optional</sup> <a name="ContentInput" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.property.contentInput"></a>

```go
func ContentInput() *string
```

- *Type:* *string

---

##### `ContentTypeInput`<sup>Optional</sup> <a name="ContentTypeInput" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.property.contentTypeInput"></a>

```go
func ContentTypeInput() *string
```

- *Type:* *string

---

##### `FilenameInput`<sup>Optional</sup> <a name="FilenameInput" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.property.filenameInput"></a>

```go
func FilenameInput() *string
```

- *Type:* *string

---

##### `MergeTypeInput`<sup>Optional</sup> <a name="MergeTypeInput" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.property.mergeTypeInput"></a>

```go
func MergeTypeInput() *string
```

- *Type:* *string

---

##### `Content`<sup>Required</sup> <a name="Content" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.property.content"></a>

```go
func Content() *string
```

- *Type:* *string

---

##### `ContentType`<sup>Required</sup> <a name="ContentType" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.property.contentType"></a>

```go
func ContentType() *string
```

- *Type:* *string

---

##### `Filename`<sup>Required</sup> <a name="Filename" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.property.filename"></a>

```go
func Filename() *string
```

- *Type:* *string

---

##### `MergeType`<sup>Required</sup> <a name="MergeType" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.property.mergeType"></a>

```go
func MergeType() *string
```

- *Type:* *string

---

##### `InternalValue`<sup>Optional</sup> <a name="InternalValue" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.property.internalValue"></a>

```go
func InternalValue() interface{}
```

- *Type:* interface{}

---



