<!-- Project Metadata -->
<!-- project_tags: template, n3n -->
<!-- project_featured: false -->

# 🐺 template

<!--- FIXME: Update crate, repo and CI workflow names here! Remove any that are not relevant --->

[![N3NX](https://img.shields.io/badge/n3n-org-%23666bff.svg)](https://n3n.org)
[![N3NX](https://img.shields.io/badge/discord-n3n-%237289da.svg?logo=discord)](https://discord.gg/kTWsyk5eV6)
[![Crates.io](https://img.shields.io/crates/v/opencl-heads.svg)](https://crates.io/crates/opencl-heads)
[![Docs](https://docs.rs/opencl-heads/badge.svg)](https://docs.rs/opencl-heads)
[![dependency status](https://deps.rs/repo/github/n3nx/opencl-rs/status.svg)](https://deps.rs/repo/github/n3nx/opencl-rs)
[![Build status](https://github.com/n3nx/opencl-rs/workflows/CI/badge.svg)](https://github.com/n3nx/opencl-rs/actions)

Template for creating new open source repositories that follow the N3N open source guidelines.

## Table of Contents

- [🐺 template](#-template)
  - [Table of Contents](#table-of-contents)
  - [TEMPLATE INSTRUCTIONS](#template-instructions)
  - [Contribution](#contribution)
    - [License](#license)

## TEMPLATE INSTRUCTIONS

1. Create a new repository under N3NX using this template.
2. **Metadata:** This README file contains tags metadata for indexing. Before starting any project, edit this readme and only modify the values present in `project_tags` and `project_featured` fields according to the working project.
3. **Title:** Change the first line of this README to the name of your project, and replace the wolf with an emoji that represents your project. 🚨 Your emoji selection is critical.
4. **Badges:** In the badges section above, change the repo name in each URL. If you are creating something other than a Rust crate, remove the crates.io and docs badges (and feel free to add more appropriate ones for your language).
5. **CI:** In `./github/workflows/` rename `rust-ci.yml` (or the appropriate config for your language) to `ci.yml`. And go over it and adapt it to work for your project
6. **Cleanup:** Remove this section of the README and any unused files (such as configs for other languages) from the repo.

## Contribution

[![N3N Contributor Guidelines](https://img.shields.io/badge/N3N%20Guidelines-v1.0-ff69b4.svg)](./CODE_OF_CONDUCT.md)

We enthusiastically invite community contributions to enhance this project. Please take a moment to review our [Contributor Terms](CONTRIBUTING.md#contributor-terms) before making any contributions.

Any contribution intentionally submitted for inclusion in any N3N project or Knytx Labs open-source project, contributors agree to adhere to the Rust standard licensing model (MIT OR Apache 2.0). Conseqently, all contributions are dual licensed as described below, without any additional terms or conditions.

For more information on contributing to this project, please consult the [Contributor Guide](CONTRIBUTING.md).

### License

This project is dual-licensed under EITHER OF:

- [Apache License, Version 2.0](LICENSE-APACHE) ([View License](http://www.apache.org/licenses/LICENSE-2.0>))
- [MIT License](LICENSE-MIT) ([View License](http://opensource.org/licenses/MIT))

**at your discretion.**
