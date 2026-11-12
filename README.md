# cm-testsuite test repository

A minimal repository for trying out
[cm-testsuite](https://github.com/vados-cosmonic/cm-testsuite) in both directions.

`.cm-testsuite.toml` configures both roles:

- **Sharing:** one Component Model WAST test is declared for the catalog to gather.
- **Receiving:** catalog tests that need only `component-model` are accepted under `tests/shared/`,
  proposed as one draft pull request.
  A repository never receives its own tests back.

| Shared test | File |
| --- | --- |
| `values/u32-add` | `tests/values/u32-add.wast` |
