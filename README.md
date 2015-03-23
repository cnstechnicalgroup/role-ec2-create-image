Role: cns.ec2-create-image
========

This role creates an EC2 image.

Requirements
------------

Nothing, it runs out of the box.

Role Variables
--------------

In the current version, you can specify the following variables:

| Name               | Default |                                                        |
|--------------------|---------|--------------------------------------------------------|
| ---                |   ---   ||

Dependencies
------------

This package has no dependencies.

License
-------

GPLv2

Author Information
------------------

Created by Sam Morrison [@samcns](https://www.twitter.com/samcns)

Examples
--------

```yaml
---
- name: cns.ec2-create-image role test
  hosts: all
  roles:
    - { role: cns.ec2-create-image, tags: ["ec2createimage"] }
```
