# `dataCloudinitConfig` Submodule <a name="`dataCloudinitConfig` Submodule" id="@cdktn/provider-cloudinit.dataCloudinitConfig"></a>

## Constructs <a name="Constructs" id="Constructs"></a>

### DataCloudinitConfig <a name="DataCloudinitConfig" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig"></a>

Represents a {@link https://registry.terraform.io/providers/hashicorp/cloudinit/2.3.7/docs/data-sources/config cloudinit_config}.

#### Initializers <a name="Initializers" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.Initializer"></a>

```python
from cdktn_provider_cloudinit import data_cloudinit_config

dataCloudinitConfig.DataCloudinitConfig(
  scope: Construct,
  id: str,
  connection: SSHProvisionerConnection | WinrmProvisionerConnection = None,
  count: typing.Union[int, float] | TerraformCount = None,
  depends_on: typing.List[ITerraformDependable] = None,
  for_each: ITerraformIterator = None,
  lifecycle: TerraformResourceLifecycle = None,
  provider: TerraformProvider = None,
  provisioners: typing.List[FileProvisioner | LocalExecProvisioner | RemoteExecProvisioner] = None,
  base64_encode: bool | IResolvable = None,
  boundary: str = None,
  gzip: bool | IResolvable = None,
  part: IResolvable | typing.List[DataCloudinitConfigPart] = None
)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.Initializer.parameter.scope">scope</a></code> | <code>constructs.Construct</code> | The scope in which to define this construct. |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.Initializer.parameter.id">id</a></code> | <code>str</code> | The scoped construct ID. |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.Initializer.parameter.connection">connection</a></code> | <code>cdktf.SSHProvisionerConnection \| cdktf.WinrmProvisionerConnection</code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.Initializer.parameter.count">count</a></code> | <code>typing.Union[int, float] \| cdktf.TerraformCount</code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.Initializer.parameter.dependsOn">depends_on</a></code> | <code>typing.List[cdktf.ITerraformDependable]</code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.Initializer.parameter.forEach">for_each</a></code> | <code>cdktf.ITerraformIterator</code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.Initializer.parameter.lifecycle">lifecycle</a></code> | <code>cdktf.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.Initializer.parameter.provider">provider</a></code> | <code>cdktf.TerraformProvider</code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.Initializer.parameter.provisioners">provisioners</a></code> | <code>typing.List[cdktf.FileProvisioner \| cdktf.LocalExecProvisioner \| cdktf.RemoteExecProvisioner]</code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.Initializer.parameter.base64Encode">base64_encode</a></code> | <code>bool \| cdktf.IResolvable</code> | Specify whether or not to base64 encode the `rendered` output. |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.Initializer.parameter.boundary">boundary</a></code> | <code>str</code> | Specify the Writer's default boundary separator. Defaults to `MIMEBOUNDARY`. |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.Initializer.parameter.gzip">gzip</a></code> | <code>bool \| cdktf.IResolvable</code> | Specify whether or not to gzip the `rendered` output. Defaults to `true`. |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.Initializer.parameter.part">part</a></code> | <code>cdktf.IResolvable \| typing.List[<a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPart">DataCloudinitConfigPart</a>]</code> | part block. |

---

##### `scope`<sup>Required</sup> <a name="scope" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.Initializer.parameter.scope"></a>

- *Type:* constructs.Construct

The scope in which to define this construct.

---

##### `id`<sup>Required</sup> <a name="id" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.Initializer.parameter.id"></a>

- *Type:* str

The scoped construct ID.

Must be unique amongst siblings in the same scope

---

##### `connection`<sup>Optional</sup> <a name="connection" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.Initializer.parameter.connection"></a>

- *Type:* cdktf.SSHProvisionerConnection | cdktf.WinrmProvisionerConnection

---

##### `count`<sup>Optional</sup> <a name="count" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.Initializer.parameter.count"></a>

- *Type:* typing.Union[int, float] | cdktf.TerraformCount

---

##### `depends_on`<sup>Optional</sup> <a name="depends_on" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.Initializer.parameter.dependsOn"></a>

- *Type:* typing.List[cdktf.ITerraformDependable]

---

##### `for_each`<sup>Optional</sup> <a name="for_each" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.Initializer.parameter.forEach"></a>

- *Type:* cdktf.ITerraformIterator

---

##### `lifecycle`<sup>Optional</sup> <a name="lifecycle" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.Initializer.parameter.lifecycle"></a>

- *Type:* cdktf.TerraformResourceLifecycle

---

##### `provider`<sup>Optional</sup> <a name="provider" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.Initializer.parameter.provider"></a>

- *Type:* cdktf.TerraformProvider

---

##### `provisioners`<sup>Optional</sup> <a name="provisioners" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.Initializer.parameter.provisioners"></a>

- *Type:* typing.List[cdktf.FileProvisioner | cdktf.LocalExecProvisioner | cdktf.RemoteExecProvisioner]

---

##### `base64_encode`<sup>Optional</sup> <a name="base64_encode" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.Initializer.parameter.base64Encode"></a>

- *Type:* bool | cdktf.IResolvable

Specify whether or not to base64 encode the `rendered` output.

Defaults to `true`, and cannot be disabled if gzip is `true`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/hashicorp/cloudinit/2.3.7/docs/data-sources/config#base64_encode DataCloudinitConfig#base64_encode}

---

##### `boundary`<sup>Optional</sup> <a name="boundary" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.Initializer.parameter.boundary"></a>

- *Type:* str

Specify the Writer's default boundary separator. Defaults to `MIMEBOUNDARY`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/hashicorp/cloudinit/2.3.7/docs/data-sources/config#boundary DataCloudinitConfig#boundary}

---

##### `gzip`<sup>Optional</sup> <a name="gzip" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.Initializer.parameter.gzip"></a>

- *Type:* bool | cdktf.IResolvable

Specify whether or not to gzip the `rendered` output. Defaults to `true`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/hashicorp/cloudinit/2.3.7/docs/data-sources/config#gzip DataCloudinitConfig#gzip}

---

##### `part`<sup>Optional</sup> <a name="part" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.Initializer.parameter.part"></a>

- *Type:* cdktf.IResolvable | typing.List[<a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPart">DataCloudinitConfigPart</a>]

part block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/hashicorp/cloudinit/2.3.7/docs/data-sources/config#part DataCloudinitConfig#part}

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.toString">to_string</a></code> | Returns a string representation of this construct. |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.addOverride">add_override</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.overrideLogicalId">override_logical_id</a></code> | Overrides the auto-generated logical ID with a specific ID. |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.resetOverrideLogicalId">reset_override_logical_id</a></code> | Resets a previously passed logical Id to use the auto-generated logical id again. |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.toHclTerraform">to_hcl_terraform</a></code> | Adds this resource to the terraform JSON output. |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.toMetadata">to_metadata</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.toTerraform">to_terraform</a></code> | Adds this resource to the terraform JSON output. |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.getAnyMapAttribute">get_any_map_attribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.getBooleanAttribute">get_boolean_attribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.getBooleanMapAttribute">get_boolean_map_attribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.getListAttribute">get_list_attribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.getNumberAttribute">get_number_attribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.getNumberListAttribute">get_number_list_attribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.getNumberMapAttribute">get_number_map_attribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.getStringAttribute">get_string_attribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.getStringMapAttribute">get_string_map_attribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.interpolationForAttribute">interpolation_for_attribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.putPart">put_part</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.resetBase64Encode">reset_base64_encode</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.resetBoundary">reset_boundary</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.resetGzip">reset_gzip</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.resetPart">reset_part</a></code> | *No description.* |

---

##### `to_string` <a name="to_string" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.toString"></a>

```python
def to_string() -> str
```

Returns a string representation of this construct.

##### `add_override` <a name="add_override" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.addOverride"></a>

```python
def add_override(
  path: str,
  value: typing.Any
) -> None
```

###### `path`<sup>Required</sup> <a name="path" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.addOverride.parameter.path"></a>

- *Type:* str

---

###### `value`<sup>Required</sup> <a name="value" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.addOverride.parameter.value"></a>

- *Type:* typing.Any

---

##### `override_logical_id` <a name="override_logical_id" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.overrideLogicalId"></a>

```python
def override_logical_id(
  new_logical_id: str
) -> None
```

Overrides the auto-generated logical ID with a specific ID.

###### `new_logical_id`<sup>Required</sup> <a name="new_logical_id" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.overrideLogicalId.parameter.newLogicalId"></a>

- *Type:* str

The new logical ID to use for this stack element.

---

##### `reset_override_logical_id` <a name="reset_override_logical_id" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.resetOverrideLogicalId"></a>

```python
def reset_override_logical_id() -> None
```

Resets a previously passed logical Id to use the auto-generated logical id again.

##### `to_hcl_terraform` <a name="to_hcl_terraform" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.toHclTerraform"></a>

```python
def to_hcl_terraform() -> typing.Any
```

Adds this resource to the terraform JSON output.

##### `to_metadata` <a name="to_metadata" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.toMetadata"></a>

```python
def to_metadata() -> typing.Any
```

##### `to_terraform` <a name="to_terraform" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.toTerraform"></a>

```python
def to_terraform() -> typing.Any
```

Adds this resource to the terraform JSON output.

##### `get_any_map_attribute` <a name="get_any_map_attribute" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.getAnyMapAttribute"></a>

```python
def get_any_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[typing.Any]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_boolean_attribute` <a name="get_boolean_attribute" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.getBooleanAttribute"></a>

```python
def get_boolean_attribute(
  terraform_attribute: str
) -> IResolvable
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_boolean_map_attribute` <a name="get_boolean_map_attribute" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.getBooleanMapAttribute"></a>

```python
def get_boolean_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[bool]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_list_attribute` <a name="get_list_attribute" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.getListAttribute"></a>

```python
def get_list_attribute(
  terraform_attribute: str
) -> typing.List[str]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_attribute` <a name="get_number_attribute" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.getNumberAttribute"></a>

```python
def get_number_attribute(
  terraform_attribute: str
) -> typing.Union[int, float]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_list_attribute` <a name="get_number_list_attribute" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.getNumberListAttribute"></a>

```python
def get_number_list_attribute(
  terraform_attribute: str
) -> typing.List[typing.Union[int, float]]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_map_attribute` <a name="get_number_map_attribute" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.getNumberMapAttribute"></a>

```python
def get_number_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[typing.Union[int, float]]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_string_attribute` <a name="get_string_attribute" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.getStringAttribute"></a>

```python
def get_string_attribute(
  terraform_attribute: str
) -> str
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_string_map_attribute` <a name="get_string_map_attribute" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.getStringMapAttribute"></a>

```python
def get_string_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[str]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `interpolation_for_attribute` <a name="interpolation_for_attribute" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.interpolationForAttribute"></a>

```python
def interpolation_for_attribute(
  terraform_attribute: str
) -> IResolvable
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.interpolationForAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `put_part` <a name="put_part" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.putPart"></a>

```python
def put_part(
  value: IResolvable | typing.List[DataCloudinitConfigPart]
) -> None
```

###### `value`<sup>Required</sup> <a name="value" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.putPart.parameter.value"></a>

- *Type:* cdktf.IResolvable | typing.List[<a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPart">DataCloudinitConfigPart</a>]

---

##### `reset_base64_encode` <a name="reset_base64_encode" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.resetBase64Encode"></a>

```python
def reset_base64_encode() -> None
```

##### `reset_boundary` <a name="reset_boundary" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.resetBoundary"></a>

```python
def reset_boundary() -> None
```

##### `reset_gzip` <a name="reset_gzip" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.resetGzip"></a>

```python
def reset_gzip() -> None
```

##### `reset_part` <a name="reset_part" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.resetPart"></a>

```python
def reset_part() -> None
```

#### Static Functions <a name="Static Functions" id="Static Functions"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.isConstruct">is_construct</a></code> | Checks if `x` is a construct. |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.isTerraformElement">is_terraform_element</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.isTerraformDataSource">is_terraform_data_source</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.generateConfigForImport">generate_config_for_import</a></code> | Generates CDKTF code for importing a DataCloudinitConfig resource upon running "cdktf plan <stack-name>". |

---

##### `is_construct` <a name="is_construct" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.isConstruct"></a>

```python
from cdktn_provider_cloudinit import data_cloudinit_config

dataCloudinitConfig.DataCloudinitConfig.is_construct(
  x: typing.Any
)
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

- *Type:* typing.Any

Any object.

---

##### `is_terraform_element` <a name="is_terraform_element" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.isTerraformElement"></a>

```python
from cdktn_provider_cloudinit import data_cloudinit_config

dataCloudinitConfig.DataCloudinitConfig.is_terraform_element(
  x: typing.Any
)
```

###### `x`<sup>Required</sup> <a name="x" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.isTerraformElement.parameter.x"></a>

- *Type:* typing.Any

---

##### `is_terraform_data_source` <a name="is_terraform_data_source" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.isTerraformDataSource"></a>

```python
from cdktn_provider_cloudinit import data_cloudinit_config

dataCloudinitConfig.DataCloudinitConfig.is_terraform_data_source(
  x: typing.Any
)
```

###### `x`<sup>Required</sup> <a name="x" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.isTerraformDataSource.parameter.x"></a>

- *Type:* typing.Any

---

##### `generate_config_for_import` <a name="generate_config_for_import" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.generateConfigForImport"></a>

```python
from cdktn_provider_cloudinit import data_cloudinit_config

dataCloudinitConfig.DataCloudinitConfig.generate_config_for_import(
  scope: Construct,
  import_to_id: str,
  import_from_id: str,
  provider: TerraformProvider = None
)
```

Generates CDKTF code for importing a DataCloudinitConfig resource upon running "cdktf plan <stack-name>".

###### `scope`<sup>Required</sup> <a name="scope" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.generateConfigForImport.parameter.scope"></a>

- *Type:* constructs.Construct

The scope in which to define this construct.

---

###### `import_to_id`<sup>Required</sup> <a name="import_to_id" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.generateConfigForImport.parameter.importToId"></a>

- *Type:* str

The construct id used in the generated config for the DataCloudinitConfig to import.

---

###### `import_from_id`<sup>Required</sup> <a name="import_from_id" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.generateConfigForImport.parameter.importFromId"></a>

- *Type:* str

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
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.property.cdktfStack">cdktf_stack</a></code> | <code>cdktf.TerraformStack</code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.property.fqn">fqn</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.property.friendlyUniqueId">friendly_unique_id</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.property.terraformMetaArguments">terraform_meta_arguments</a></code> | <code>typing.Mapping[typing.Any]</code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.property.terraformResourceType">terraform_resource_type</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.property.terraformGeneratorMetadata">terraform_generator_metadata</a></code> | <code>cdktf.TerraformProviderGeneratorMetadata</code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.property.count">count</a></code> | <code>typing.Union[int, float] \| cdktf.TerraformCount</code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.property.dependsOn">depends_on</a></code> | <code>typing.List[str]</code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.property.forEach">for_each</a></code> | <code>cdktf.ITerraformIterator</code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.property.lifecycle">lifecycle</a></code> | <code>cdktf.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.property.provider">provider</a></code> | <code>cdktf.TerraformProvider</code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.property.id">id</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.property.part">part</a></code> | <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartList">DataCloudinitConfigPartList</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.property.rendered">rendered</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.property.base64EncodeInput">base64_encode_input</a></code> | <code>bool \| cdktf.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.property.boundaryInput">boundary_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.property.gzipInput">gzip_input</a></code> | <code>bool \| cdktf.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.property.partInput">part_input</a></code> | <code>cdktf.IResolvable \| typing.List[<a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPart">DataCloudinitConfigPart</a>]</code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.property.base64Encode">base64_encode</a></code> | <code>bool \| cdktf.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.property.boundary">boundary</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.property.gzip">gzip</a></code> | <code>bool \| cdktf.IResolvable</code> | *No description.* |

---

##### `node`<sup>Required</sup> <a name="node" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.property.node"></a>

```python
node: Node
```

- *Type:* constructs.Node

The tree node.

---

##### `cdktf_stack`<sup>Required</sup> <a name="cdktf_stack" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.property.cdktfStack"></a>

```python
cdktf_stack: TerraformStack
```

- *Type:* cdktf.TerraformStack

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.property.fqn"></a>

```python
fqn: str
```

- *Type:* str

---

##### `friendly_unique_id`<sup>Required</sup> <a name="friendly_unique_id" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.property.friendlyUniqueId"></a>

```python
friendly_unique_id: str
```

- *Type:* str

---

##### `terraform_meta_arguments`<sup>Required</sup> <a name="terraform_meta_arguments" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.property.terraformMetaArguments"></a>

```python
terraform_meta_arguments: typing.Mapping[typing.Any]
```

- *Type:* typing.Mapping[typing.Any]

---

##### `terraform_resource_type`<sup>Required</sup> <a name="terraform_resource_type" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.property.terraformResourceType"></a>

```python
terraform_resource_type: str
```

- *Type:* str

---

##### `terraform_generator_metadata`<sup>Optional</sup> <a name="terraform_generator_metadata" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.property.terraformGeneratorMetadata"></a>

```python
terraform_generator_metadata: TerraformProviderGeneratorMetadata
```

- *Type:* cdktf.TerraformProviderGeneratorMetadata

---

##### `count`<sup>Optional</sup> <a name="count" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.property.count"></a>

```python
count: typing.Union[int, float] | TerraformCount
```

- *Type:* typing.Union[int, float] | cdktf.TerraformCount

---

##### `depends_on`<sup>Optional</sup> <a name="depends_on" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.property.dependsOn"></a>

```python
depends_on: typing.List[str]
```

- *Type:* typing.List[str]

---

##### `for_each`<sup>Optional</sup> <a name="for_each" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.property.forEach"></a>

```python
for_each: ITerraformIterator
```

- *Type:* cdktf.ITerraformIterator

---

##### `lifecycle`<sup>Optional</sup> <a name="lifecycle" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.property.lifecycle"></a>

```python
lifecycle: TerraformResourceLifecycle
```

- *Type:* cdktf.TerraformResourceLifecycle

---

##### `provider`<sup>Optional</sup> <a name="provider" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.property.provider"></a>

```python
provider: TerraformProvider
```

- *Type:* cdktf.TerraformProvider

---

##### `id`<sup>Required</sup> <a name="id" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.property.id"></a>

```python
id: str
```

- *Type:* str

---

##### `part`<sup>Required</sup> <a name="part" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.property.part"></a>

```python
part: DataCloudinitConfigPartList
```

- *Type:* <a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartList">DataCloudinitConfigPartList</a>

---

##### `rendered`<sup>Required</sup> <a name="rendered" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.property.rendered"></a>

```python
rendered: str
```

- *Type:* str

---

##### `base64_encode_input`<sup>Optional</sup> <a name="base64_encode_input" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.property.base64EncodeInput"></a>

```python
base64_encode_input: bool | IResolvable
```

- *Type:* bool | cdktf.IResolvable

---

##### `boundary_input`<sup>Optional</sup> <a name="boundary_input" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.property.boundaryInput"></a>

```python
boundary_input: str
```

- *Type:* str

---

##### `gzip_input`<sup>Optional</sup> <a name="gzip_input" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.property.gzipInput"></a>

```python
gzip_input: bool | IResolvable
```

- *Type:* bool | cdktf.IResolvable

---

##### `part_input`<sup>Optional</sup> <a name="part_input" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.property.partInput"></a>

```python
part_input: IResolvable | typing.List[DataCloudinitConfigPart]
```

- *Type:* cdktf.IResolvable | typing.List[<a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPart">DataCloudinitConfigPart</a>]

---

##### `base64_encode`<sup>Required</sup> <a name="base64_encode" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.property.base64Encode"></a>

```python
base64_encode: bool | IResolvable
```

- *Type:* bool | cdktf.IResolvable

---

##### `boundary`<sup>Required</sup> <a name="boundary" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.property.boundary"></a>

```python
boundary: str
```

- *Type:* str

---

##### `gzip`<sup>Required</sup> <a name="gzip" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.property.gzip"></a>

```python
gzip: bool | IResolvable
```

- *Type:* bool | cdktf.IResolvable

---

#### Constants <a name="Constants" id="Constants"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.property.tfResourceType">tfResourceType</a></code> | <code>str</code> | *No description.* |

---

##### `tfResourceType`<sup>Required</sup> <a name="tfResourceType" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfig.property.tfResourceType"></a>

```python
tfResourceType: str
```

- *Type:* str

---

## Structs <a name="Structs" id="Structs"></a>

### DataCloudinitConfigConfig <a name="DataCloudinitConfigConfig" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigConfig"></a>

#### Initializer <a name="Initializer" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigConfig.Initializer"></a>

```python
from cdktn_provider_cloudinit import data_cloudinit_config

dataCloudinitConfig.DataCloudinitConfigConfig(
  connection: SSHProvisionerConnection | WinrmProvisionerConnection = None,
  count: typing.Union[int, float] | TerraformCount = None,
  depends_on: typing.List[ITerraformDependable] = None,
  for_each: ITerraformIterator = None,
  lifecycle: TerraformResourceLifecycle = None,
  provider: TerraformProvider = None,
  provisioners: typing.List[FileProvisioner | LocalExecProvisioner | RemoteExecProvisioner] = None,
  base64_encode: bool | IResolvable = None,
  boundary: str = None,
  gzip: bool | IResolvable = None,
  part: IResolvable | typing.List[DataCloudinitConfigPart] = None
)
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigConfig.property.connection">connection</a></code> | <code>cdktf.SSHProvisionerConnection \| cdktf.WinrmProvisionerConnection</code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigConfig.property.count">count</a></code> | <code>typing.Union[int, float] \| cdktf.TerraformCount</code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigConfig.property.dependsOn">depends_on</a></code> | <code>typing.List[cdktf.ITerraformDependable]</code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigConfig.property.forEach">for_each</a></code> | <code>cdktf.ITerraformIterator</code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigConfig.property.lifecycle">lifecycle</a></code> | <code>cdktf.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigConfig.property.provider">provider</a></code> | <code>cdktf.TerraformProvider</code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigConfig.property.provisioners">provisioners</a></code> | <code>typing.List[cdktf.FileProvisioner \| cdktf.LocalExecProvisioner \| cdktf.RemoteExecProvisioner]</code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigConfig.property.base64Encode">base64_encode</a></code> | <code>bool \| cdktf.IResolvable</code> | Specify whether or not to base64 encode the `rendered` output. |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigConfig.property.boundary">boundary</a></code> | <code>str</code> | Specify the Writer's default boundary separator. Defaults to `MIMEBOUNDARY`. |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigConfig.property.gzip">gzip</a></code> | <code>bool \| cdktf.IResolvable</code> | Specify whether or not to gzip the `rendered` output. Defaults to `true`. |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigConfig.property.part">part</a></code> | <code>cdktf.IResolvable \| typing.List[<a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPart">DataCloudinitConfigPart</a>]</code> | part block. |

---

##### `connection`<sup>Optional</sup> <a name="connection" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigConfig.property.connection"></a>

```python
connection: SSHProvisionerConnection | WinrmProvisionerConnection
```

- *Type:* cdktf.SSHProvisionerConnection | cdktf.WinrmProvisionerConnection

---

##### `count`<sup>Optional</sup> <a name="count" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigConfig.property.count"></a>

```python
count: typing.Union[int, float] | TerraformCount
```

- *Type:* typing.Union[int, float] | cdktf.TerraformCount

---

##### `depends_on`<sup>Optional</sup> <a name="depends_on" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigConfig.property.dependsOn"></a>

```python
depends_on: typing.List[ITerraformDependable]
```

- *Type:* typing.List[cdktf.ITerraformDependable]

---

##### `for_each`<sup>Optional</sup> <a name="for_each" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigConfig.property.forEach"></a>

```python
for_each: ITerraformIterator
```

- *Type:* cdktf.ITerraformIterator

---

##### `lifecycle`<sup>Optional</sup> <a name="lifecycle" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigConfig.property.lifecycle"></a>

```python
lifecycle: TerraformResourceLifecycle
```

- *Type:* cdktf.TerraformResourceLifecycle

---

##### `provider`<sup>Optional</sup> <a name="provider" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigConfig.property.provider"></a>

```python
provider: TerraformProvider
```

- *Type:* cdktf.TerraformProvider

---

##### `provisioners`<sup>Optional</sup> <a name="provisioners" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigConfig.property.provisioners"></a>

```python
provisioners: typing.List[FileProvisioner | LocalExecProvisioner | RemoteExecProvisioner]
```

- *Type:* typing.List[cdktf.FileProvisioner | cdktf.LocalExecProvisioner | cdktf.RemoteExecProvisioner]

---

##### `base64_encode`<sup>Optional</sup> <a name="base64_encode" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigConfig.property.base64Encode"></a>

```python
base64_encode: bool | IResolvable
```

- *Type:* bool | cdktf.IResolvable

Specify whether or not to base64 encode the `rendered` output.

Defaults to `true`, and cannot be disabled if gzip is `true`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/hashicorp/cloudinit/2.3.7/docs/data-sources/config#base64_encode DataCloudinitConfig#base64_encode}

---

##### `boundary`<sup>Optional</sup> <a name="boundary" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigConfig.property.boundary"></a>

```python
boundary: str
```

- *Type:* str

Specify the Writer's default boundary separator. Defaults to `MIMEBOUNDARY`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/hashicorp/cloudinit/2.3.7/docs/data-sources/config#boundary DataCloudinitConfig#boundary}

---

##### `gzip`<sup>Optional</sup> <a name="gzip" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigConfig.property.gzip"></a>

```python
gzip: bool | IResolvable
```

- *Type:* bool | cdktf.IResolvable

Specify whether or not to gzip the `rendered` output. Defaults to `true`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/hashicorp/cloudinit/2.3.7/docs/data-sources/config#gzip DataCloudinitConfig#gzip}

---

##### `part`<sup>Optional</sup> <a name="part" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigConfig.property.part"></a>

```python
part: IResolvable | typing.List[DataCloudinitConfigPart]
```

- *Type:* cdktf.IResolvable | typing.List[<a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPart">DataCloudinitConfigPart</a>]

part block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/hashicorp/cloudinit/2.3.7/docs/data-sources/config#part DataCloudinitConfig#part}

---

### DataCloudinitConfigPart <a name="DataCloudinitConfigPart" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPart"></a>

#### Initializer <a name="Initializer" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPart.Initializer"></a>

```python
from cdktn_provider_cloudinit import data_cloudinit_config

dataCloudinitConfig.DataCloudinitConfigPart(
  content: str,
  content_type: str = None,
  filename: str = None,
  merge_type: str = None
)
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPart.property.content">content</a></code> | <code>str</code> | Body content for the part. |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPart.property.contentType">content_type</a></code> | <code>str</code> | A MIME-style content type to report in the header for the part. Defaults to `text/plain`. |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPart.property.filename">filename</a></code> | <code>str</code> | A filename to report in the header for the part. |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPart.property.mergeType">merge_type</a></code> | <code>str</code> | A value for the `X-Merge-Type` header of the part, to control [cloud-init merging behavior](https://cloudinit.readthedocs.io/en/latest/reference/merging.html). |

---

##### `content`<sup>Required</sup> <a name="content" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPart.property.content"></a>

```python
content: str
```

- *Type:* str

Body content for the part.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/hashicorp/cloudinit/2.3.7/docs/data-sources/config#content DataCloudinitConfig#content}

---

##### `content_type`<sup>Optional</sup> <a name="content_type" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPart.property.contentType"></a>

```python
content_type: str
```

- *Type:* str

A MIME-style content type to report in the header for the part. Defaults to `text/plain`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/hashicorp/cloudinit/2.3.7/docs/data-sources/config#content_type DataCloudinitConfig#content_type}

---

##### `filename`<sup>Optional</sup> <a name="filename" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPart.property.filename"></a>

```python
filename: str
```

- *Type:* str

A filename to report in the header for the part.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/hashicorp/cloudinit/2.3.7/docs/data-sources/config#filename DataCloudinitConfig#filename}

---

##### `merge_type`<sup>Optional</sup> <a name="merge_type" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPart.property.mergeType"></a>

```python
merge_type: str
```

- *Type:* str

A value for the `X-Merge-Type` header of the part, to control [cloud-init merging behavior](https://cloudinit.readthedocs.io/en/latest/reference/merging.html).

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/hashicorp/cloudinit/2.3.7/docs/data-sources/config#merge_type DataCloudinitConfig#merge_type}

---

## Classes <a name="Classes" id="Classes"></a>

### DataCloudinitConfigPartList <a name="DataCloudinitConfigPartList" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartList"></a>

#### Initializers <a name="Initializers" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartList.Initializer"></a>

```python
from cdktn_provider_cloudinit import data_cloudinit_config

dataCloudinitConfig.DataCloudinitConfigPartList(
  terraform_resource: IInterpolatingParent,
  terraform_attribute: str,
  wraps_set: bool
)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartList.Initializer.parameter.terraformResource">terraform_resource</a></code> | <code>cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartList.Initializer.parameter.terraformAttribute">terraform_attribute</a></code> | <code>str</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartList.Initializer.parameter.wrapsSet">wraps_set</a></code> | <code>bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraform_resource`<sup>Required</sup> <a name="terraform_resource" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartList.Initializer.parameter.terraformResource"></a>

- *Type:* cdktf.IInterpolatingParent

The parent resource.

---

##### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartList.Initializer.parameter.terraformAttribute"></a>

- *Type:* str

The attribute on the parent resource this class is referencing.

---

##### `wraps_set`<sup>Required</sup> <a name="wraps_set" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartList.Initializer.parameter.wrapsSet"></a>

- *Type:* bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartList.allWithMapKey">all_with_map_key</a></code> | Creating an iterator for this complex list. |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartList.computeFqn">compute_fqn</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartList.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartList.toString">to_string</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartList.get">get</a></code> | *No description.* |

---

##### `all_with_map_key` <a name="all_with_map_key" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartList.allWithMapKey"></a>

```python
def all_with_map_key(
  map_key_attribute_name: str
) -> DynamicListTerraformIterator
```

Creating an iterator for this complex list.

The list will be converted into a map with the mapKeyAttributeName as the key.

###### `map_key_attribute_name`<sup>Required</sup> <a name="map_key_attribute_name" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartList.allWithMapKey.parameter.mapKeyAttributeName"></a>

- *Type:* str

---

##### `compute_fqn` <a name="compute_fqn" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartList.computeFqn"></a>

```python
def compute_fqn() -> str
```

##### `resolve` <a name="resolve" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartList.resolve"></a>

```python
def resolve(
  _context: IResolveContext
) -> typing.Any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartList.resolve.parameter._context"></a>

- *Type:* cdktf.IResolveContext

---

##### `to_string` <a name="to_string" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartList.toString"></a>

```python
def to_string() -> str
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `get` <a name="get" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartList.get"></a>

```python
def get(
  index: typing.Union[int, float]
) -> DataCloudinitConfigPartOutputReference
```

###### `index`<sup>Required</sup> <a name="index" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartList.get.parameter.index"></a>

- *Type:* typing.Union[int, float]

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartList.property.creationStack">creation_stack</a></code> | <code>typing.List[str]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartList.property.fqn">fqn</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartList.property.internalValue">internal_value</a></code> | <code>cdktf.IResolvable \| typing.List[<a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPart">DataCloudinitConfigPart</a>]</code> | *No description.* |

---

##### `creation_stack`<sup>Required</sup> <a name="creation_stack" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartList.property.creationStack"></a>

```python
creation_stack: typing.List[str]
```

- *Type:* typing.List[str]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartList.property.fqn"></a>

```python
fqn: str
```

- *Type:* str

---

##### `internal_value`<sup>Optional</sup> <a name="internal_value" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartList.property.internalValue"></a>

```python
internal_value: IResolvable | typing.List[DataCloudinitConfigPart]
```

- *Type:* cdktf.IResolvable | typing.List[<a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPart">DataCloudinitConfigPart</a>]

---


### DataCloudinitConfigPartOutputReference <a name="DataCloudinitConfigPartOutputReference" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference"></a>

#### Initializers <a name="Initializers" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.Initializer"></a>

```python
from cdktn_provider_cloudinit import data_cloudinit_config

dataCloudinitConfig.DataCloudinitConfigPartOutputReference(
  terraform_resource: IInterpolatingParent,
  terraform_attribute: str,
  complex_object_index: typing.Union[int, float],
  complex_object_is_from_set: bool
)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.Initializer.parameter.terraformResource">terraform_resource</a></code> | <code>cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.Initializer.parameter.terraformAttribute">terraform_attribute</a></code> | <code>str</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.Initializer.parameter.complexObjectIndex">complex_object_index</a></code> | <code>typing.Union[int, float]</code> | the index of this item in the list. |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.Initializer.parameter.complexObjectIsFromSet">complex_object_is_from_set</a></code> | <code>bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraform_resource`<sup>Required</sup> <a name="terraform_resource" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* cdktf.IInterpolatingParent

The parent resource.

---

##### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* str

The attribute on the parent resource this class is referencing.

---

##### `complex_object_index`<sup>Required</sup> <a name="complex_object_index" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* typing.Union[int, float]

the index of this item in the list.

---

##### `complex_object_is_from_set`<sup>Required</sup> <a name="complex_object_is_from_set" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.computeFqn">compute_fqn</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.getAnyMapAttribute">get_any_map_attribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.getBooleanAttribute">get_boolean_attribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.getBooleanMapAttribute">get_boolean_map_attribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.getListAttribute">get_list_attribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.getNumberAttribute">get_number_attribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.getNumberListAttribute">get_number_list_attribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.getNumberMapAttribute">get_number_map_attribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.getStringAttribute">get_string_attribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.getStringMapAttribute">get_string_map_attribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.interpolationForAttribute">interpolation_for_attribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.toString">to_string</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.resetContentType">reset_content_type</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.resetFilename">reset_filename</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.resetMergeType">reset_merge_type</a></code> | *No description.* |

---

##### `compute_fqn` <a name="compute_fqn" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.computeFqn"></a>

```python
def compute_fqn() -> str
```

##### `get_any_map_attribute` <a name="get_any_map_attribute" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.getAnyMapAttribute"></a>

```python
def get_any_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[typing.Any]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_boolean_attribute` <a name="get_boolean_attribute" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.getBooleanAttribute"></a>

```python
def get_boolean_attribute(
  terraform_attribute: str
) -> IResolvable
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_boolean_map_attribute` <a name="get_boolean_map_attribute" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.getBooleanMapAttribute"></a>

```python
def get_boolean_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[bool]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_list_attribute` <a name="get_list_attribute" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.getListAttribute"></a>

```python
def get_list_attribute(
  terraform_attribute: str
) -> typing.List[str]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_attribute` <a name="get_number_attribute" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.getNumberAttribute"></a>

```python
def get_number_attribute(
  terraform_attribute: str
) -> typing.Union[int, float]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_list_attribute` <a name="get_number_list_attribute" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.getNumberListAttribute"></a>

```python
def get_number_list_attribute(
  terraform_attribute: str
) -> typing.List[typing.Union[int, float]]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_map_attribute` <a name="get_number_map_attribute" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.getNumberMapAttribute"></a>

```python
def get_number_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[typing.Union[int, float]]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_string_attribute` <a name="get_string_attribute" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.getStringAttribute"></a>

```python
def get_string_attribute(
  terraform_attribute: str
) -> str
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_string_map_attribute` <a name="get_string_map_attribute" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.getStringMapAttribute"></a>

```python
def get_string_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[str]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `interpolation_for_attribute` <a name="interpolation_for_attribute" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.interpolationForAttribute"></a>

```python
def interpolation_for_attribute(
  property: str
) -> IResolvable
```

###### `property`<sup>Required</sup> <a name="property" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* str

---

##### `resolve` <a name="resolve" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.resolve"></a>

```python
def resolve(
  _context: IResolveContext
) -> typing.Any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.resolve.parameter._context"></a>

- *Type:* cdktf.IResolveContext

---

##### `to_string` <a name="to_string" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.toString"></a>

```python
def to_string() -> str
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `reset_content_type` <a name="reset_content_type" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.resetContentType"></a>

```python
def reset_content_type() -> None
```

##### `reset_filename` <a name="reset_filename" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.resetFilename"></a>

```python
def reset_filename() -> None
```

##### `reset_merge_type` <a name="reset_merge_type" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.resetMergeType"></a>

```python
def reset_merge_type() -> None
```


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.property.creationStack">creation_stack</a></code> | <code>typing.List[str]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.property.fqn">fqn</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.property.contentInput">content_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.property.contentTypeInput">content_type_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.property.filenameInput">filename_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.property.mergeTypeInput">merge_type_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.property.content">content</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.property.contentType">content_type</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.property.filename">filename</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.property.mergeType">merge_type</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.property.internalValue">internal_value</a></code> | <code>cdktf.IResolvable \| <a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPart">DataCloudinitConfigPart</a></code> | *No description.* |

---

##### `creation_stack`<sup>Required</sup> <a name="creation_stack" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.property.creationStack"></a>

```python
creation_stack: typing.List[str]
```

- *Type:* typing.List[str]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.property.fqn"></a>

```python
fqn: str
```

- *Type:* str

---

##### `content_input`<sup>Optional</sup> <a name="content_input" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.property.contentInput"></a>

```python
content_input: str
```

- *Type:* str

---

##### `content_type_input`<sup>Optional</sup> <a name="content_type_input" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.property.contentTypeInput"></a>

```python
content_type_input: str
```

- *Type:* str

---

##### `filename_input`<sup>Optional</sup> <a name="filename_input" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.property.filenameInput"></a>

```python
filename_input: str
```

- *Type:* str

---

##### `merge_type_input`<sup>Optional</sup> <a name="merge_type_input" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.property.mergeTypeInput"></a>

```python
merge_type_input: str
```

- *Type:* str

---

##### `content`<sup>Required</sup> <a name="content" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.property.content"></a>

```python
content: str
```

- *Type:* str

---

##### `content_type`<sup>Required</sup> <a name="content_type" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.property.contentType"></a>

```python
content_type: str
```

- *Type:* str

---

##### `filename`<sup>Required</sup> <a name="filename" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.property.filename"></a>

```python
filename: str
```

- *Type:* str

---

##### `merge_type`<sup>Required</sup> <a name="merge_type" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.property.mergeType"></a>

```python
merge_type: str
```

- *Type:* str

---

##### `internal_value`<sup>Optional</sup> <a name="internal_value" id="@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPartOutputReference.property.internalValue"></a>

```python
internal_value: IResolvable | DataCloudinitConfigPart
```

- *Type:* cdktf.IResolvable | <a href="#@cdktn/provider-cloudinit.dataCloudinitConfig.DataCloudinitConfigPart">DataCloudinitConfigPart</a>

---



