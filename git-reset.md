# `git reset`

_Reset current **HEAD** \(dangerous\)._

## **_Default:_**

```bash
git reset --mixed
```

With any flag when the word "HEAD" is suppressed the command is equivalent to:

```bash
git reset --flag HEAD
```

To see changes for commits n times backwards use `git reset --flag HEAD~n`.

## `git reset --soft`

**Uncommits** changes from local history :page_with_curl:; changes are left staged on index :package::

:hammer_and_wrench: :package: :page_with_curl: :earth_americas:

&nbsp; &nbsp; &nbsp; :heavy_check_mark: :x:

## `git reset --mixed`

**Uncommits** changes from local history :page_with_curl: and **unstages** them from index :package:; changes are left staged on workspace :hammer_and_wrench:.

:hammer_and_wrench: :package: :page_with_curl: :earth_americas:

:heavy_check_mark: :x: :x:

## `git reset --hard`

**Uncommits** changes from local history :page_with_curl:, **unstages** them from index :package: and **deletes** them from workspace :hammer_and_wrench:.

:hammer_and_wrench: :package: :page_with_curl: :earth_americas:

:x: :x: :x:
