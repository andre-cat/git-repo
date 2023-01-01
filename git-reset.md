# `git reset`

_Reset current **HEAD** \(dangerous\)._

## **_Default:_**

```git
git reset --mixed
```

## `git reset --soft`

**Uncommits** changes from local history :page_with_curl:; changes are left staged on index :package::

:hammer_and_wrench: :package: :page_with_curl: :earth_americas:

&nbsp; &nbsp; &nbsp; :heavy_check_mark: :x:

By default command is equivalent to:

```git
git reset --soft HEAD
```

Use `git reset --soft HEAD~n` to a commit n times backward.

## `git reset --mixed`

**Uncommits** changes from local history :page_with_curl: and **unstages** them from index :package:; changes are left staged on working directory :hammer_and_wrench:.

:hammer_and_wrench: :package: :page_with_curl: :earth_americas:

:heavy_check_mark: :x: :x:
