# perception_ecu_individual_params

This repository stores parameters for perception ecu

## Rationale

The parameters were originally managed in `launcher` repository.
Why we manage them in a separate repository are:

- Parameter maintainers don't require write-access to `launcher` repository.
- To rollback only parameters independently from `launcher`.

## Directory Structure

```shell
individual_params/
├── config
│   └── default
│       ├── c1_camera_info.yaml
│       ├── trigger.param.yaml
│       └── v4l2_camera.param.yaml
├── CMakeLists.txt
└── package.xml
```
