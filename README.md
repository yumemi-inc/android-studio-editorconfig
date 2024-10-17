# Android Studio EditorConfig

## Usage

Place `.editorconfig` file from this repository in the root directory of your project.

```
$ curl -O https://raw.githubusercontent.com/yumemi-inc/android-studio-editorconfig/refs/tags/v1.0.0/.editorconfig
```

Customize if necessary for your project.

## About IntelliJ related parameters in .editorconfig

```
ij_kotlin_code_style_defaults = KOTLIN_OFFICIAL
```

Apply Kotlin official code style.

```
ij_kotlin_name_count_to_use_star_import = 2147483647
ij_kotlin_name_count_to_use_star_import_for_members = 2147483647
ij_kotlin_packages_to_use_import_on_demand = unset
```

Disable wildcard imports.

```
ij_kotlin_keep_blank_lines_before_right_brace = 0
ij_kotlin_keep_blank_lines_in_code = 1
ij_kotlin_keep_blank_lines_in_declarations = 1
```

Minimize blank lines.

```
ij_kotlin_line_comment_add_space = true
ij_kotlin_line_comment_add_space_on_reformat = true
ij_kotlin_line_comment_at_first_column = false
```

Add space after `//`.

```
ij_kotlin_allow_trailing_comma = true
ij_kotlin_allow_trailing_comma_on_call_site = true
```

Force trailing comma.

These parameters are based on the following:

- https://pinterest.github.io/ktlint/1.3.0/rules/configuration-intellij-idea/#preventing-conflicts
- https://github.com/pinterest/ktlint/tree/0.46.1?tab=readme-ov-file#manually-update-editorconfig

## Recommended Android Studio settings

TODO


