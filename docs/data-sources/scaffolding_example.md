---
# generated by https://github.com/hashicorp/terraform-plugin-docs
page_title: "firebase_example Data Source - terraform-provider-firebase-framework"
subcategory: ""
description: |-
  Example data source
---

# firebase_example (Data Source)

Example data source

## Example Usage

```terraform
data "firebase_example" "example" {
  configurable_attribute = "some-value"
}
```

<!-- schema generated by tfplugindocs -->
## Schema

### Optional

- `configurable_attribute` (String) Example configurable attribute

### Read-Only

- `id` (String) Example identifier
