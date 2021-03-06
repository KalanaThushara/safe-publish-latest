1.1.2 / 2018-08-06
==================
  * [Fix] ensure packages work on first publish (#11)
  * [Deps] update `semver`, `yargs`
  * [Deps] pin yargs to v7, since v8 drops node < 4 compat.
  * [Dev Deps] update `eslint`, `@ljharb/eslint-config`, `nsp`, `tape`
  * [Tests] up to `node` `v10.8`, `v9.11`, `v8.11`, `v6.14`, `v4.9`; use `nvm install-latest-npm`
  * [Tests] add `editorconfig-tools`

1.1.1 / 2016-10-09
==================
  * [Fix] Ensure `allVersions` is an array, when there’s only one
  * [Deps] update `yargs`
  * [Dev Deps] update `eslint`, `nsp`, `tape`
  * [Tests] up to `node` `v6.6`, `v4.5`; improve test matrix

1.1.0 / 2016-09-19
==================
  * [Fix] ensure that the npm loglevel is known for `npm info`
  * [Fix] ensure publishing can work the first time (#4)
  * [New] add `—force-in-publish` to skip the “in publish” check
  * [Deps] update `semver`, `yargs`
  * [Dev Deps] update `eslint`, `@ljharb/eslint-config`, `nsp`
  * [Tests] fix tests since package x suddenly got updated

1.0.1 / 2016-07-30
==================
  * [Fix] Use `npm info $pkg versions -—json` rather than `nom-package-versions` (#1)
  * [Deps] update `semver`
  * [Dev Deps] update `eslint`, `@ljharb/eslint-config`, `nsp`

1.0.0 / 2016-06-28
==================
  * Initial release.
