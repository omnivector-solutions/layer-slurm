# Overview
This layer provides the `slurm-wlm` package.

# Usage

To create a charm layer using this base layer, you need only include it in
a `layer.yaml` file:

```yaml
include: ['layer:slurm']
```

# Reactive States

This layer will set the following states:

* **`slurm.installed`** Slurm packages are installed.
