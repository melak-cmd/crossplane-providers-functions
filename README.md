# Crossplane Providers Functions

This project contains a set of functions for Crossplane providers. These functions help in managing and automating cloud infrastructure using Crossplane.

## Installation

To install the necessary dependencies, run the following command:

```sh
npm install
```

## Usage

To use the functions in this project, import them into your Crossplane configuration files. Here is an example of how to use a function:

```typescript
import { exampleFunction } from 'crossplane-providers-functions';

exampleFunction();
```

## Values

The following table lists the configurable parameters of the chart and their default values.

| Parameter        | Description                           | Default           |
|------------------|---------------------------------------|-------------------|
| `image.repository`| Image repository                      | `nginx`           |
| `image.tag`      | Image tag                              | `latest`          |
| `image.pullPolicy`| Image pull policy                     | `IfNotPresent`    |
| `service.type`   | Type of service                        | `ClusterIP`       |
| `service.port`   | Service port                           | `80`              |

## Contributing

We welcome contributions! Please fork the repository and submit a pull request with your changes.