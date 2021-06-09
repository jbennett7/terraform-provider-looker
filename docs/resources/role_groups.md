---
# generated by https://github.com/hashicorp/terraform-plugin-docs
page_title: "looker_role_groups Resource - terraform-provider-looker"
subcategory: ""
description: |-
  
---

# looker_role_groups (Resource)



## Example Usage

```terraform
resource "looker_role" "embed_role" {
  name              = "Embed User Role"
  permission_set_id = looker_permission_set.embed_permission_set.id
  model_set_id      = looker_model_set.model_set.id
}
```

<!-- schema generated by tfplugindocs -->
## Schema

### Required

- **group_ids** (Set of String)
- **role_id** (String)

### Optional

- **id** (String) The ID of this resource.

