# aws-cdk-pure-hoc

This is a TypeScript library implements reusable cloud design patterns as purely functional high-order components. Use them as building blocks for your cloud infrastructure.  

## Getting started

The latest version of the library is available at its `master` branch. All development, including new features and bug fixes, take place on the `master` branch using forking and pull requests as described in contribution guidelines. The latest package release is available at npm

```bash
npm install --save aws-cdk-pure-hoc
```

## High Order Components

The library implements a cloud design patterns using high order components: 

* [config](https://i.am.fog.fish/2019/10/18/retain-confidentiality-in-open-source-infrastructure.html) - The twelve-factor application principles advices environment variables to store the config. `config` HoC gives you a secure approach to retain confidentiality of your configuration. It is an environment variables managed through Key Vault service.


## License

[![See LICENSE](https://img.shields.io/github/license/fogfish/aws-cdk-pure.svg?style=for-the-badge)](LICENSE)