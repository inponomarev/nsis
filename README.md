# inponomarev.nsis

This is an Ansible role to compile [Nullsoft scriptable install system](http://nsis.sourceforge.net/Main_Page) on an Ubuntu Linux machine

## Requirements

Ansible 2.x

## Role Variables

|Variable|Description|Default|
|---|---|---|
|```nsisver```||3.02.1|

## Dependencies

none

## Example Playbook

    - hosts: servers
      roles:
         - role: inponomarev.nsis

## License

MIT / BSD

## Author Information

Ivan Ponomarev
