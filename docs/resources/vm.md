---
# generated by https://github.com/hashicorp/terraform-plugin-docs
page_title: "cloudlab_vm Resource - terraform-provider-cloudlab"
subcategory: ""
description: |-
  
---

# cloudlab_vm (Resource)



## Example Usage

```terraform
resource "cloudlab_vm" "my-cloudlab-vm" {
  name         = "vm-name"
  project      = "project-name"
  profile_uuid = "profile-uuid"
  vlan         = []
}
```

<!-- schema generated by tfplugindocs -->
## Schema

### Required

- `name` (String)
- `profile_uuid` (String)
- `project` (String, Sensitive)
- `vlan` (List of Number)

### Read-Only

- `id` (String) The ID of this resource.
