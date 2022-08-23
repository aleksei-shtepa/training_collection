Testmodule
=========

Роль использует модуль `training_collection.shtepa_aleksei.newcontent`

Role Variables
--------------

- `newcontent_file_path`: str( default = "fail-me-now" ) - Путь размещения целевого файла;
- `newcontent_content`: str( default = "fail-me-now" ) - Содержание целевого файла;

Example Playbook
----------------

```yaml
---
- name: Test play
  hosts: localhost
  vars:
    newcontent_file_path: "hello.file"
    newcontent_content: "some file content"
  roles:
    - training_collection.shtepa_aleksei.testmodule
```

License
-------

MIT

Author Information
------------------

Aleksei Shtepa
