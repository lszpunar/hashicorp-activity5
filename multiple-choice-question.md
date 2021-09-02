---
title: Sample Question
type: select_one
shuffle_options: [choose-true-or-false]
blooms: [choose-a-blooms-level]
correct_response: b
options:
  - id: a
    text: “Try `fileset("id_rsa.pub")`”
  - id: b
    text: Enter `file("id_rsa.pub")`
  - id: c
    text: "filebase64("id_rsa.pud")"
  - id: d
    text: "none of the above would work"
  - id: e
    text: "All of the above"
  - id: f
  - text: "`templatefile("id_rsa.pub")`"
  - id: g
  - text: "Use `filebase64("id_rsa.pub")`"
---

Terraform has several Built-in command’s for reading files. They are `file`, `filebase64`, `fileexists`, and `templatefile`. Which Built-in terraform function should a developer choose who was requested to write terraform code. He is going to need to read some input from a local file called id_rsa.pub that resides in the same directory as the configruation use to import the file’s contents as a string.
