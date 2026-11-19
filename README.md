# Temporary iroh-web package

This temporary branch holds an npm tarball for testing [iroh-web PR #2](https://github.com/daviroo/iroh-web/pull/2) at source commit `7fb5e1fb4f89aa9facb7b21bdb2f81f5cf178a09`. This is not an npm release. Pin the artifact by its commit ID, not by this branch name.

`iroh-web-7fb5e1fb-normalized.tgz` is a 1,122,584-byte package with JavaScript, TypeScript declarations, and a 2,579,803-byte WebAssembly module.

- SHA-256: `03f512fc05029da883e1323f6f900181caf67b29046787f6b7147e166cb32f38`
- pnpm integrity: `sha512-OOfZPn13S/8znHdHXTlJn3SMNnxrgU0bbzTecSYNkoSiW6nNkpGAzR+Vs5ZKoYcy9uOWiBVEl8UQl32jbkE9hw==`

After replacing this pin and verifying that no supported builds still reference it, delete `dpc/tmp-iroh-web-lookup-only-7fb5e1fb` from the fork.
