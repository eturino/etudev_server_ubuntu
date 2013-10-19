etudev_server_ubuntu Cookbook
=============================
This cookbook prepares an ubuntu server to be used, fixing some issues and installing the PPAs that will be needed.

For now it installs the latest stable Git

Requirements
------------

e.g.
#### cookbooks
- `apt` - etudev_server_ubuntu uses apt to install PPAs


Usage
-----
#### etudev_server_ubuntu::default

Just include `etudev_server_ubuntu` in your node's `run_list`:

```json
{
  "name":"my_node",
  "run_list": [
    "recipe[etudev_server_ubuntu]"
  ]
}
```

Contributing
------------

e.g.
1. Fork the repository on Github
2. Create a named feature branch (like `add_component_x`)
3. Write you change
4. Write tests for your change (if applicable)
5. Run the tests, ensuring they all pass
6. Submit a Pull Request using Github

License and Authors
-------------------
Authors: Eduardo Turiño, eturino, https://github.com/eturino
