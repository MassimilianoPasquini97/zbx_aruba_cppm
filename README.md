<p align="center">
    <img src="docs/image/logo.avif" height="128">
    <h1 align="center">Aruba Clear Pass Policy Manager SNMP Zabbix Template</h1>
</p>

This template is meant for monitoring Aruba Clear Pass Policy Manager appliances using SNMP MIB [CPPM-MIB](https://mibbrowser.online/mibdb_search.php?mib=CPPM-MIB)

- [Features](#features)
- [How to use](#how-to-use)
- [Contribute](#contribute)
- [License](#license)

## Features

- Disk and memory usage.
- General system information.
- Server protocol counters and time metrics.
- Server authentication counters and time metrics.
- Tacacs/Radius authentication counters and time metrics.

## How to use

1) Import the template file ***zbx_template_aruba_cppm.yaml*** in Zabbix.
2) Create SNMP credentials on Aruba Clear Pass Policy Manager.
3) Create the Zabbix host with an SNMP interface and assign the ***Aruba Clear Pass Policy Manager SNMP*** template.

> [!TIP]
> You can personalize the Zabbix template behaviours using MACROS.

## Contribute

This template is on early stage and can bee improved supporting other Unity parameters. Feel free to fork and submit pull request. 🙏🏻

## License

Licensed under the [MIT license](https://github.com/MassimilianoPasquini97/zbx_aruba_cppm/blob/main/LICENSE.md).
