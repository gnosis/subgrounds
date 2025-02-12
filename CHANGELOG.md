# Changelog

<!--next-version-placeholder-->

## v1.10.0 (2025-02-12)

### Feature

* **chore:** Bump deps, might consider >= in the future ([`9e4a5b8`](https://github.com/gnosis/subgrounds/commit/9e4a5b8a78dc4ddd8223946d04de025e3cb100f8))
* Pydantic upgrade to v2, maintaining V1 API internally ([#45](https://github.com/gnosis/subgrounds/issues/45)) ([`25570ae`](https://github.com/gnosis/subgrounds/commit/25570ae1f4d293f46312f195d5344473ad63e8fa))
* Pandas upgrade to v2 ([#44](https://github.com/gnosis/subgrounds/issues/44)) ([`5d1670b`](https://github.com/gnosis/subgrounds/commit/5d1670bc1077c0f81fc2426e512118006f07f81b))
* Async support for subgrounds (+ more) ([#36](https://github.com/gnosis/subgrounds/issues/36)) ([`929a882`](https://github.com/gnosis/subgrounds/commit/929a88221ac571b1a45b5877e62d6d4cb2d1a91e))
* Add helpers for accessing the playgrounds gateway ([#21](https://github.com/gnosis/subgrounds/issues/21)) ([`e44aee6`](https://github.com/gnosis/subgrounds/commit/e44aee65649bff192321cfd82436b65da236d870))
* Add `all` as an extra install ([`f1adacf`](https://github.com/gnosis/subgrounds/commit/f1adacf8162e711a8395cd75c9726350ec67c0c5))
* `subgrounds[pyodide]` patching for requests ([`7293262`](https://github.com/gnosis/subgrounds/commit/7293262bed062932a6ca52ae69cf0545850ed470))
* Add `plotly` as an extra ([`058e28d`](https://github.com/gnosis/subgrounds/commit/058e28d2f4170fabd0558313be50137ecd8c4972))
* `subgrounds.contrib.dash` and `subgrounds.contrib.plotly` ([`f1d79e8`](https://github.com/gnosis/subgrounds/commit/f1d79e89f1594bc31d443fa2b248f745974dd468))
* Headers Support ([#13](https://github.com/gnosis/subgrounds/issues/13)) ([`8ff3c04`](https://github.com/gnosis/subgrounds/commit/8ff3c040a2c8c205b31566f1135e38a3c84293b2))
* Add specific error models ([`6218076`](https://github.com/gnosis/subgrounds/commit/621807602c3467a3e729541f645d992d3e5b6297))
* Add user-agent to headers ([`41dbaf6`](https://github.com/gnosis/subgrounds/commit/41dbaf6443ad604665ad5412d4b2c6bd3d3cdeb4))
* Add headers to Subgrounds ([`80d6c20`](https://github.com/gnosis/subgrounds/commit/80d6c208dd2fa624f7033f60217f6de85fcb4099))
* Export more symbols to `subgrounds` ([`3c59fe9`](https://github.com/gnosis/subgrounds/commit/3c59fe9e0f96947d23905a0eab384c01cf8d42f7))
* Refactor `SchemaMeta` into Pydantic model ([`052c475`](https://github.com/gnosis/subgrounds/commit/052c475b71db09a8aec85979135167aa19752378))
* Add new utility methods to query AST classes ([`0fbd7d4`](https://github.com/gnosis/subgrounds/commit/0fbd7d44dba0dbacca3a9fe71fb908ced49871a7))
* Add SyntheticField helper to create a map SyntheticField ([`24da126`](https://github.com/gnosis/subgrounds/commit/24da126e5a66624bec315515c79f74a7805be012))
* Add datetime_of_timestamp premade SyntheticField ([`49afce3`](https://github.com/gnosis/subgrounds/commit/49afce359e53df3253a1c33b25da981a0e3a96d2))
* Add cursor data to pagination error exception ([`4580cfd`](https://github.com/gnosis/subgrounds/commit/4580cfd06d984096187264d5c89c5f6aedbf86f5))
* Add iterator variant to all toplevel query functions ([`415cdcb`](https://github.com/gnosis/subgrounds/commit/415cdcb61c923f813b13d34bd5c4df4fc224bfdb))

### Fix

* Trigger CI ([`ee5d982`](https://github.com/gnosis/subgrounds/commit/ee5d982fbf8023c9a8e9f3514f7a87a37b2898a6))
* Added test for null_filter condition. ([#53](https://github.com/gnosis/subgrounds/issues/53)) ([`d022c85`](https://github.com/gnosis/subgrounds/commit/d022c8525e0fa88c55352376b754aaebfc2dec10))
* Caching bug ([#55](https://github.com/gnosis/subgrounds/issues/55)) ([`196b3a2`](https://github.com/gnosis/subgrounds/commit/196b3a2d11a4852bb3c6aa6959b3c7564068baac))
* Critical fix that amends `__exit__` and `__aexit__` ([#49](https://github.com/gnosis/subgrounds/issues/49)) ([`b60e3a9`](https://github.com/gnosis/subgrounds/commit/b60e3a9fb09a78384c9783b0ba677b98b3879216))
* Nested filters ([#40](https://github.com/gnosis/subgrounds/issues/40)) ([`3f3f575`](https://github.com/gnosis/subgrounds/commit/3f3f5753bf5dba9ac39664156b76f81697055a23))
* `add` method of `Selection` class ([#39](https://github.com/gnosis/subgrounds/issues/39)) ([`5c18dec`](https://github.com/gnosis/subgrounds/commit/5c18dec14fb78176238d3bda2c0e6a3016de0b4e))
* Nested orderBy working with DSL ([`7e320e8`](https://github.com/gnosis/subgrounds/commit/7e320e8c77c12ad3fcfa64f3aad4428ad1068539))
* Nested OrderBy ([#17](https://github.com/gnosis/subgrounds/issues/17)) ([`b807319`](https://github.com/gnosis/subgrounds/commit/b8073193ddeee2cde2d795382ef8523d87a7ca71))
* `poetry.lock` file ([`5e365e0`](https://github.com/gnosis/subgrounds/commit/5e365e09e63e5a077fcca861b6ecb0cbb494cc0f))
* Enable `pyodide` patch on import ([`dd5193b`](https://github.com/gnosis/subgrounds/commit/dd5193b2a46ff16ed4e7c7ca8f5d708bfa65d63b))
* Headers bugs w/ non-subgraph apis ([`7749f8f`](https://github.com/gnosis/subgrounds/commit/7749f8f378fd5dcad727e2b507a50ed99654fab3))
* Update examples to user modern subgrounds ([`6e14b89`](https://github.com/gnosis/subgrounds/commit/6e14b89dd040d938210827d2defcfa80e397a896))
* Better defined error models ([`c121132`](https://github.com/gnosis/subgrounds/commit/c1211328bbd4db00ec981f1cf167bd88d62cc94b))
* Adjust error models + fix typos ([`fa853d7`](https://github.com/gnosis/subgrounds/commit/fa853d70e9fe388b025410314baabc7e8447485d))
* Default header as a function to avoid circular imports ([`1f2f8f6`](https://github.com/gnosis/subgrounds/commit/1f2f8f6d10a115c596fe938b983f86e865711bd7))
* `Query.map` had no default value for `priority` ([#12](https://github.com/gnosis/subgrounds/issues/12)) ([`82a5f29`](https://github.com/gnosis/subgrounds/commit/82a5f293e4cf7398350d12e309cd3cff190c1318))
* Bump version ([`40004c0`](https://github.com/gnosis/subgrounds/commit/40004c012e474a32c94812576e24069c8a4c5d51))
* Bug where some SyntheticField arguments would be None ([`8369123`](https://github.com/gnosis/subgrounds/commit/836912315ce8f8d79d23bb7da1a92ad5e8371af8))
* Bug where null object would break synthetic fields ([`51ddd03`](https://github.com/gnosis/subgrounds/commit/51ddd039c4a68ef6beb89205ad9a427a5ed11ebf))
* Examples ([`7c22a6b`](https://github.com/gnosis/subgrounds/commit/7c22a6b16d3550f45628f67019268015f9090f0b))
* Interfaces parsing bug ([`ff7c344`](https://github.com/gnosis/subgrounds/commit/ff7c34494c8d39c6dffdc66cbad71afc04c92522))
* Remove unneeded imports ([`f0a8255`](https://github.com/gnosis/subgrounds/commit/f0a825521b2b398bbf339674a4c6d976bf6d7d8d))
* Tons of small bugs ([`53695cb`](https://github.com/gnosis/subgrounds/commit/53695cb13539c26e8ec47d895026ed45165f7152))
* Schema cache_dir bug (fixed by using pathlib) ([`b5144bc`](https://github.com/gnosis/subgrounds/commit/b5144bc27d50fa4ff14df55101178d6211bac7a2))
* Fix bug in prune_doc function ([`d6ff893`](https://github.com/gnosis/subgrounds/commit/d6ff8938a1d79b78d98394b6eaabb32a7bbbab8e))
* Fix bug where single FieldPath requests would not work ([`5ae98c6`](https://github.com/gnosis/subgrounds/commit/5ae98c6bc505939dc2b931ae60fd55b79e3340fd))
* Pagination preprocessing bug ([`8b8bc99`](https://github.com/gnosis/subgrounds/commit/8b8bc9995ba2944608d0e16518784be5d7e7303a))
* Outdated pagination algorithm ([`1078a28`](https://github.com/gnosis/subgrounds/commit/1078a286da685930e61845be6164cd1cb9249c34))
* Bug in InterfaceMeta.is_object ([`6b3555b`](https://github.com/gnosis/subgrounds/commit/6b3555b93139d49a14b75a6c3157e8f484e52367))
* Unused pagination arguments causing errors ([`641c20e`](https://github.com/gnosis/subgrounds/commit/641c20e813933a75c490c9ab56a27a16b3595e4e))

### Documentation

* Finally formatting changes to README.md ([`5820110`](https://github.com/gnosis/subgrounds/commit/58201108f42d70d53bab9b88b2fabe6f2a2e1657))
* More formatting changes to README.md ([`71a66a8`](https://github.com/gnosis/subgrounds/commit/71a66a81974e4632b4102fe4b5584c6d9136497b))
* Format code-block in README.md ([`0db2207`](https://github.com/gnosis/subgrounds/commit/0db22079329f40254ce51aa0d615f730cc4099f4))
* Update CHANGELOG.md ([`7ef0876`](https://github.com/gnosis/subgrounds/commit/7ef08764cd27478ab9797f2823a823cbbe095ec2))
* Update README links ([`f271706`](https://github.com/gnosis/subgrounds/commit/f271706fee42c90ab99840bac65952217a5aaf1a))
* Add open in colab button ([`02ff722`](https://github.com/gnosis/subgrounds/commit/02ff7226e54920f411a9817f1eb26c757e4a2a32))
* Add gateway notebook as another example ([`98eab32`](https://github.com/gnosis/subgrounds/commit/98eab32d4bb9fcae072dcceefae94a8692e10852))
* Adjust example notebook for colab ([`6210556`](https://github.com/gnosis/subgrounds/commit/62105568b61c3a155ee07c6077b4b1e1d81f27fd))
* Adjust wording in example notebook ([`357c6d8`](https://github.com/gnosis/subgrounds/commit/357c6d859aea36d680cfde7d728a24a66ae67193))
* Add example notebook + swap binder for colab ([`06cc728`](https://github.com/gnosis/subgrounds/commit/06cc72860e2d83fc200b1198519da5963a85b0c1))
* Add CI status badge to README.md ([`4c6dca9`](https://github.com/gnosis/subgrounds/commit/4c6dca90174cbbfd990dbf7906bf75ee50f4d65a))
* Broken link in README ([#19](https://github.com/gnosis/subgrounds/issues/19)) ([`211f965`](https://github.com/gnosis/subgrounds/commit/211f965331225fb7287cff027c5dd01e8a4e5784))
* Fix broken links ([`24bd498`](https://github.com/gnosis/subgrounds/commit/24bd4987b98960d97d711a05fa12dc2c91e903db))
* LICENSE update ([`c4c4b3b`](https://github.com/gnosis/subgrounds/commit/c4c4b3b16b1bcaa96a4d236534092d760ff5b7de))
* Adjust twitter badge ([`95218d1`](https://github.com/gnosis/subgrounds/commit/95218d1c5947bfe54665db1c8e1a4e138865d5f4))
* Fix codespace badge link ([`cd5841d`](https://github.com/gnosis/subgrounds/commit/cd5841d3da9cda45ea74fb1c9e68ae80b63168d3))
* Cleanup and improve README.md ([`5e524bd`](https://github.com/gnosis/subgrounds/commit/5e524bdc5d5bed52cd596ea7f569ce5e9d1e193e))
* Adjust wording ([`501b480`](https://github.com/gnosis/subgrounds/commit/501b480a93834978faa063633060389ef82b5931))
* Add extra details about `contrib` and deprecation ([`6a7bbec`](https://github.com/gnosis/subgrounds/commit/6a7bbecbbd30d926ff7a9c8285b3c7be64b28722))
* Fix changelog formatting ([`7f8a630`](https://github.com/gnosis/subgrounds/commit/7f8a6302871387042ffa0ea323284832f2611ea7))
* Update README.md ([`dcea873`](https://github.com/gnosis/subgrounds/commit/dcea87388020ef8465c0752e0ae79469d1f018e1))
* Update design goals to features ([`6abecc6`](https://github.com/gnosis/subgrounds/commit/6abecc68b3d9f573bf6feb6c14c0e0107fc7e8a7))
* Add description about testing ([`f2231c2`](https://github.com/gnosis/subgrounds/commit/f2231c2b02fe0194409b91d865dedd6d45ecd92c))
* Migrated `docs/` and clean up ([`9deca3b`](https://github.com/gnosis/subgrounds/commit/9deca3bc48a38018c9baa73ba625ec37decf1670))
* Add CONTRIBUTING.md + README.md edits ([`2218d47`](https://github.com/gnosis/subgrounds/commit/2218d47df13bf2cc5a43950f1106b62c20a16d5f))
* Trigger docs flow (removed some files) ([`1ee17e5`](https://github.com/gnosis/subgrounds/commit/1ee17e5129192c3c202830f929f284c8ca019650))
* Simplify contributing cmds ([#3](https://github.com/gnosis/subgrounds/issues/3)) ([`0b4f3a2`](https://github.com/gnosis/subgrounds/commit/0b4f3a2590a3e916e614bff97b578bb32d5097e2))
* Fix typo in docs ([`4e69f65`](https://github.com/gnosis/subgrounds/commit/4e69f65dc42a1e9112c9ec7720d840f0c9342912))
* Add line about disabling pagination ([`217ecd9`](https://github.com/gnosis/subgrounds/commit/217ecd937dda88723923ea268f88f515b0e58c9e))
* Add docs for pagination rework ([`4783c8c`](https://github.com/gnosis/subgrounds/commit/4783c8c56ee1ac439c189ad960b04a512c88a02f))
* Add docstrings to PaginationStrategy Protocol ([`b520b5f`](https://github.com/gnosis/subgrounds/commit/b520b5f3bf1884d2dea60c033a94a1fbecb44c07))
* Improve docs, add docstrings to new features and fix typos ([`4606544`](https://github.com/gnosis/subgrounds/commit/4606544da311917e0cfdafdceaef829d0445a4c4))
* Add docstrings to subgrounds.pagination.Cursor class ([`1361667`](https://github.com/gnosis/subgrounds/commit/1361667ba9a1042f1ecf43ef9c4965e5dcf38059))
* Add instructions to setup isolated Python environment with Pyenv and Poetry ([`b02a749`](https://github.com/gnosis/subgrounds/commit/b02a749b4cead9801dae12a91802a4b9c3d23a1b))
* Rewrite doc pages in .rst ([`9e7f681`](https://github.com/gnosis/subgrounds/commit/9e7f6817b94593d31ff7c19ed13fad8189e3223d))
* Fix Markdown doc pages not being included in docs ([`56ed6bc`](https://github.com/gnosis/subgrounds/commit/56ed6bc70aa65eec7946e720635df9cf4779e877))

## v1.9.1 (2024-06-20)

### Fix

* Trigger CI ([`ee5d982`](https://github.com/0xPlaygrounds/subgrounds/commit/ee5d982fbf8023c9a8e9f3514f7a87a37b2898a6))

## v1.9.0 (2024-06-18)

### Feature

* **chore:** Bump deps, might consider >= in the future ([`9e4a5b8`](https://github.com/0xPlaygrounds/subgrounds/commit/9e4a5b8a78dc4ddd8223946d04de025e3cb100f8))

## v1.8.3 (2024-06-10)

### Fix

* Added test for null_filter condition. ([#53](https://github.com/0xPlaygrounds/subgrounds/issues/53)) ([`d022c85`](https://github.com/0xPlaygrounds/subgrounds/commit/d022c8525e0fa88c55352376b754aaebfc2dec10))

## v1.8.2 (2024-06-10)

### Fix

* Caching bug ([#55](https://github.com/0xPlaygrounds/subgrounds/issues/55)) ([`196b3a2`](https://github.com/0xPlaygrounds/subgrounds/commit/196b3a2d11a4852bb3c6aa6959b3c7564068baac))

## v1.8.1 (2023-11-10)

### Fix

* Critical fix that amends `__exit__` and `__aexit__` ([#49](https://github.com/0xPlaygrounds/subgrounds/issues/49)) ([`b60e3a9`](https://github.com/0xPlaygrounds/subgrounds/commit/b60e3a9fb09a78384c9783b0ba677b98b3879216))

### Documentation

* Finally formatting changes to README.md ([`5820110`](https://github.com/0xPlaygrounds/subgrounds/commit/58201108f42d70d53bab9b88b2fabe6f2a2e1657))
* More formatting changes to README.md ([`71a66a8`](https://github.com/0xPlaygrounds/subgrounds/commit/71a66a81974e4632b4102fe4b5584c6d9136497b))
* Format code-block in README.md ([`0db2207`](https://github.com/0xPlaygrounds/subgrounds/commit/0db22079329f40254ce51aa0d615f730cc4099f4))

## v1.8.0 (2023-10-10)

### Feature

* Pydantic upgrade to v2, maintaining V1 API internally ([#45](https://github.com/0xPlaygrounds/subgrounds/issues/45)) ([`25570ae`](https://github.com/0xPlaygrounds/subgrounds/commit/25570ae1f4d293f46312f195d5344473ad63e8fa))
* Pandas upgrade to v2 ([#44](https://github.com/0xPlaygrounds/subgrounds/issues/44)) ([`5d1670b`](https://github.com/0xPlaygrounds/subgrounds/commit/5d1670bc1077c0f81fc2426e512118006f07f81b))

## v1.7.1 (2023-09-22)

### Fix

* Nested filters ([#40](https://github.com/0xPlaygrounds/subgrounds/issues/40)) ([`3f3f575`](https://github.com/0xPlaygrounds/subgrounds/commit/3f3f5753bf5dba9ac39664156b76f81697055a23))

### Documentation

* Update CHANGELOG.md ([`7ef0876`](https://github.com/0xPlaygrounds/subgrounds/commit/7ef08764cd27478ab9797f2823a823cbbe095ec2))

## v1.7.0 (2023-09-05)

### Feature

* Async support for subgrounds (+ more) ([#36](https://github.com/0xPlaygrounds/subgrounds/issues/36)) ([`929a882`](https://github.com/0xPlaygrounds/subgrounds/commit/929a88221ac571b1a45b5877e62d6d4cb2d1a91e))
* Ability to create custom clients via `SubgroundsBase`

### Changes
- The entirety of how subgrounds coordinates the production, transformation, and pagination of requests has been completely reworked from the ground up.
  - Instead of a recursive call stack, transformation and pagination is lazily computed.
  - Then, a client (implementing `SubgroundsBase`), *drives* the actual processing of requests/responses until completion.
- Subgrounds models the [sans-io](https://sans-io.readthedocs.io/) approach to handling requests
  - This means subgrounds is untangled from actually making IO
  - This has enabled custom clients, allowing anyone to customize subgrounds interface.
- Various rewrites, reworks, and improvements to documentation.

## v1.6.1 (2023-08-01)

### Fix

* `add` method of `Selection` class ([#39](https://github.com/0xPlaygrounds/subgrounds/issues/39)) ([`5c18dec`](https://github.com/0xPlaygrounds/subgrounds/commit/5c18dec14fb78176238d3bda2c0e6a3016de0b4e))

### Documentation

* Update README links ([`f271706`](https://github.com/0xPlaygrounds/subgrounds/commit/f271706fee42c90ab99840bac65952217a5aaf1a))

## v1.6.0 (2023-05-25)
### Feature
* Add helpers for accessing the playgrounds gateway ([#21](https://github.com/0xPlaygrounds/subgrounds/issues/21)) ([`e44aee6`](https://github.com/0xPlaygrounds/subgrounds/commit/e44aee65649bff192321cfd82436b65da236d870))

### Documentation
* Add open in colab button ([`02ff722`](https://github.com/0xPlaygrounds/subgrounds/commit/02ff7226e54920f411a9817f1eb26c757e4a2a32))
* Add gateway notebook as another example ([`98eab32`](https://github.com/0xPlaygrounds/subgrounds/commit/98eab32d4bb9fcae072dcceefae94a8692e10852))
* Adjust example notebook for colab ([`6210556`](https://github.com/0xPlaygrounds/subgrounds/commit/62105568b61c3a155ee07c6077b4b1e1d81f27fd))
* Adjust wording in example notebook ([`357c6d8`](https://github.com/0xPlaygrounds/subgrounds/commit/357c6d859aea36d680cfde7d728a24a66ae67193))
* Add example notebook + swap binder for colab ([`06cc728`](https://github.com/0xPlaygrounds/subgrounds/commit/06cc72860e2d83fc200b1198519da5963a85b0c1))
* Add CI status badge to README.md ([`4c6dca9`](https://github.com/0xPlaygrounds/subgrounds/commit/4c6dca90174cbbfd990dbf7906bf75ee50f4d65a))
* Broken link in README ([#19](https://github.com/0xPlaygrounds/subgrounds/issues/19)) ([`211f965`](https://github.com/0xPlaygrounds/subgrounds/commit/211f965331225fb7287cff027c5dd01e8a4e5784))

## v1.5.2 (2023-05-17)
### Fix
* Nested orderBy working with DSL ([`7e320e8`](https://github.com/0xPlaygrounds/subgrounds/commit/7e320e8c77c12ad3fcfa64f3aad4428ad1068539))

## v1.5.1 (2023-05-15)
### Fix
* Nested OrderBy ([#17](https://github.com/0xPlaygrounds/subgrounds/issues/17)) ([`b807319`](https://github.com/0xPlaygrounds/subgrounds/commit/b8073193ddeee2cde2d795382ef8523d87a7ca71))

### Documentation
* Fix broken links ([`24bd498`](https://github.com/0xPlaygrounds/subgrounds/commit/24bd4987b98960d97d711a05fa12dc2c91e903db))
* LICENSE update ([`c4c4b3b`](https://github.com/0xPlaygrounds/subgrounds/commit/c4c4b3b16b1bcaa96a4d236534092d760ff5b7de))
* Adjust twitter badge ([`95218d1`](https://github.com/0xPlaygrounds/subgrounds/commit/95218d1c5947bfe54665db1c8e1a4e138865d5f4))
* Fix codespace badge link ([`cd5841d`](https://github.com/0xPlaygrounds/subgrounds/commit/cd5841d3da9cda45ea74fb1c9e68ae80b63168d3))
* Cleanup and improve README.md ([`5e524bd`](https://github.com/0xPlaygrounds/subgrounds/commit/5e524bdc5d5bed52cd596ea7f569ce5e9d1e193e))

## v1.5.0 (2023-04-25)
### Feature
* Add `all` as an extra install ([`f1adacf`](https://github.com/0xPlaygrounds/subgrounds/commit/f1adacf8162e711a8395cd75c9726350ec67c0c5))
* `subgrounds[pyodide]` patching for requests ([`7293262`](https://github.com/0xPlaygrounds/subgrounds/commit/7293262bed062932a6ca52ae69cf0545850ed470))
* Add `plotly` as an extra ([`058e28d`](https://github.com/0xPlaygrounds/subgrounds/commit/058e28d2f4170fabd0558313be50137ecd8c4972))

### Fix
* `poetry.lock` file ([`5e365e0`](https://github.com/0xPlaygrounds/subgrounds/commit/5e365e09e63e5a077fcca861b6ecb0cbb494cc0f))
* Enable `pyodide` patch on import ([`dd5193b`](https://github.com/0xPlaygrounds/subgrounds/commit/dd5193b2a46ff16ed4e7c7ca8f5d708bfa65d63b))

## v1.4.0 (2023-04-13)
### Feature
* `subgrounds.contrib.dash` and `subgrounds.contrib.plotly` ([`f1d79e8`](https://github.com/0xPlaygrounds/subgrounds/commit/f1d79e89f1594bc31d443fa2b248f745974dd468))

### Fix
* Headers bugs w/ non-subgraph apis ([`7749f8f`](https://github.com/0xPlaygrounds/subgrounds/commit/7749f8f378fd5dcad727e2b507a50ed99654fab3))
* Update examples to user modern subgrounds ([`6e14b89`](https://github.com/0xPlaygrounds/subgrounds/commit/6e14b89dd040d938210827d2defcfa80e397a896))

### Documentation
* Adjust wording ([`501b480`](https://github.com/0xPlaygrounds/subgrounds/commit/501b480a93834978faa063633060389ef82b5931))
* Add extra details about `contrib` and deprecation ([`6a7bbec`](https://github.com/0xPlaygrounds/subgrounds/commit/6a7bbecbbd30d926ff7a9c8285b3c7be64b28722))

## v1.3.0 (2023-04-07)
### Feature
* Add specific error models ([`6218076`](https://github.com/0xPlaygrounds/subgrounds/commit/621807602c3467a3e729541f645d992d3e5b6297))

## v1.2.0 (2023-04-02)
### Feature
* Headers Support ([#13](https://github.com/0xPlaygrounds/subgrounds/issues/13)) ([`8ff3c04`](https://github.com/0xPlaygrounds/subgrounds/commit/8ff3c040a2c8c205b31566f1135e38a3c84293b2))

### Documentation
* Fix changelog formatting ([`7f8a630`](https://github.com/0xPlaygrounds/subgrounds/commit/7f8a6302871387042ffa0ea323284832f2611ea7))

## v1.1.2 (2023-03-15)
### Fix
* `Query.map` had no default value for `priority` ([#12](https://github.com/0xPlaygrounds/subgrounds/issues/12)) ([`82a5f29`](https://github.com/0xPlaygrounds/subgrounds/commit/82a5f293e4cf7398350d12e309cd3cff190c1318))

### Documentation
* Update README.md ([`dcea873`](https://github.com/0xPlaygrounds/subgrounds/commit/dcea87388020ef8465c0752e0ae79469d1f018e1))
* Update design goals to features ([`6abecc6`](https://github.com/0xPlaygrounds/subgrounds/commit/6abecc68b3d9f573bf6feb6c14c0e0107fc7e8a7))

## v1.1.1 (2023-03-03)
### Fix
* Bump version ([`40004c0`](https://github.com/0xPlaygrounds/subgrounds/commit/40004c012e474a32c94812576e24069c8a4c5d51))

## v1.1.0 (2023-03-03)

### Feature
* Export more symbols to `subgrounds` ([`3c59fe9`](https://github.com/0xPlaygrounds/subgrounds/commit/3c59fe9e0f96947d23905a0eab384c01cf8d42f7))

### Documentation
* Add description about testing ([`f2231c2`](https://github.com/0xPlaygrounds/subgrounds/commit/f2231c2b02fe0194409b91d865dedd6d45ecd92c))
* Migrated `docs/` and clean up ([`9deca3b`](https://github.com/0xPlaygrounds/subgrounds/commit/9deca3bc48a38018c9baa73ba625ec37decf1670))
* Add CONTRIBUTING.md + README.md edits ([`2218d47`](https://github.com/0xPlaygrounds/subgrounds/commit/2218d47df13bf2cc5a43950f1106b62c20a16d5f))
* Trigger docs flow (removed some files) ([`1ee17e5`](https://github.com/0xPlaygrounds/subgrounds/commit/1ee17e5129192c3c202830f929f284c8ca019650))
* Simplify contributing cmds ([#3](https://github.com/0xPlaygrounds/subgrounds/issues/3)) ([`0b4f3a2`](https://github.com/0xPlaygrounds/subgrounds/commit/0b4f3a2590a3e916e614bff97b578bb32d5097e2))

## v1.0.3 (2022-08-08)

### Fix
- Issue causing null object in `SyntheticField`s


## v1.0.2 (2022-10-30)
### Fix
- Update `SchemaMeta` to `Pydantic` model for extra validation

## v1.0.1 (2022-08-08)

### Fix
- Schema cache directory path
- `where` filter getting dropped during pagination


## v1.0.0 (2022-07-25)

### Description
This release overhauls how pagination is performed in Subgrounds.

### BREAKING CHANGES
* The `auto_paginate` argument of toplevel querying functions has been replaced by the `pagination_strategy` argument (setting the latter to `None` disables pagination).

### Feature
* Subgrounds users can now define and use their own pagination strategy (see Custom pagination strategy for more details).
* Users select the pagination strategies to use when calling toplevel querying functions:

    ```py
    df = sg.query_df(field_paths, pagination_strategy=MyPaginationStrategy) 
    ```

* Subgrounds provides two pagination strategies out of the box:
  * `LegacyStrategy` (the strategy used prior to this update)
  * `ShallowStrategy`, which is much faster than `LegacyStrategy` in some cases, but does not support pagination on nested fields (see Available pagination strategies for more details).

### Fix
* Fix bug that would cause a crash when calling one of the toplevel querying functions with only one `FieldPath` object (e.g.: `sg.query_df(pairs.id)`).


## v0.2.0 (2023-06-23)

### Feature
* Iterative versions of toplevel querying functions to allow developers to process queried data page by page when automatic pagination returns more than one page
  * `query_df` -> `query_df_iter`
  * `query` -> `query_iter`
  * `query_json` -> `query_json_iter`
  * `execute` -> `execute_iter`
* Add option to set subgraph schema cache directory in `load_subgraph` and `load_api`.
  * Defaults to `./schemas/`
* Add useful `SyntheticField` helper `datetime_of_timestamp`
* `Subgrounds` class can now be imported from toplevel module: `from subgrounds import Subgrounds`
* Add `SyntheticField.datetime_of_timestamp` helper function to easily create a `SyntheticField` that converts a Unix timestamp into a human readable datetime string
* Add `SyntheticField.map` helper function to easily create a "map" `SyntheticField` from a dictionary

### Fix
* Fix bug that caused some queries to fail with automatic pagination enabled

### Chore
* Migrate package manager from `pipenv` to `poetry`
* Migrate docs from plain `sphinx` to `mudkip`
* Made `dash` an optional extra dependency.
  * To use Subgrounds `dash` and `plotly` wrappers, run `pip install subgrounds[dash]`


## v0.1.1 (2022-04-29)

### Fix
- Scalar lists were not handled properly

## v0.1.0 (2022-04-27)

### Feature
- Partial fieldpaths
  - Querying partial fieldpaths will automatically select all non-list fields of the fieldpath leaf.
  - For example, using the Ribbon V2 subgraph, the following Subgrounds query:

    ```py
    sg.query_df([
        ribbon.Query.vaults
    ])
    ```

    will result in the following query being made to the subgraph:

    ```graphql
    query {
        vaults {
        id
        name
        symbol
        underlyingAsset
        underlyingName
        underlyingSymbol
        underlyingDecimals
        totalPremiumEarned
        totalNominalVolume
        totalNotionalVolume
        numDepositors
        totalBalance
        cap
        round
        performanceFeeCollected
        managementFeeCollected
        totalFeeCollected
        }
    }
    ```

- Code completion
  - When using Subgrounds in Jupyter notebooks and a subgraph has been loaded in a previous cell, fieldpaths will now autocomplete.


## v0.0.9 (2023-03-29)

### Feature
* `Subgrounds.load_api`
  * Allows you to safely query non-subgraph GrahpQL APIs with Subgrounds!
* New boolean flag argument, `auto_paginate`, in `Subgrounds.query`, `Subgrounds.query_json` and `Subgrounds.query_df`
  * Selectively disable automatic pagination

### Documentation
* Refactor, cleanup and add tons of docstrings
