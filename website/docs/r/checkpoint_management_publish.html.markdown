---
layout: "checkpoint"
page_title: "checkpoint_management_publish "
sidebar_current: "docs-checkpoint-resource-checkpoint-management-publish"
description: |-
  Publish Changes.
---

# Resource: checkpoint_management_publish

This command resource allows you to Publish Changes.

## Example Usage

```hcl
resource "checkpoint_management_publish" "example" { }
```

## Argument Reference

The following arguments are supported:

* `uid` - (Optional) Session unique identifier. Specify it to publish a different session than the one you currently use.
* `task_id` - (Computed) Asynchronous task unique identifier. 


## How To Use
Make sure this command resource will be executed by terraform when you meant it will run.  