# Ansible Role: containerd

## Description

Manage an industry-standard container runtime service.

## Requirements

None

## Dependencies

None

## OS Platforms

- AlmaLinux 8 or higher
- Rockylinux 8 or higher
- Ubuntu 20.04 focal
- Ubuntu 22.04 jammy

## Example Playbook

```
- hosts: all
  roles:
    - containerd
```

## Role Variables

### containerd_debug: (bool)

```
containerd_debug: false
```

### containerd_package_ensure: (string)

```
containerd_package_ensure: 'present'
```

### containerd_service_ensure: (string)

```
containerd_service_ensure: 'started'
```

### containerd_service_enable: (bool)

```
containerd_service_enable: true
```

### containerd_config_options: (dict)

```
containerd_config_options: {}
```
