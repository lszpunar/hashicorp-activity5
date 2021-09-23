---
title: Sample Question
type: select_one
shuffle_options: true
blooms: remember
correct_response: b
options:
  - id: a
    text: `fileset("id_rsa.pub")`
  - id: b
    text: `file("id_rsa.pub")`
  - id: c
    text: `filebase64("id_rsa.pub")`
  - id: d
    text: `templatefile("id_rsa.pub")`
---

You have a local file called `id_rsa.pub` that resides in the Terraform configuration directory. What built-in Terraform function should you use to import the file’s contents as a string?
