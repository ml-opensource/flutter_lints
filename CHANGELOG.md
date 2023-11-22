## 1.0.3

Add new linter rules:

- [always_put_control_body_on_new_line](https://dart.dev/tools/linter-rules/always_put_control_body_on_new_line) — Along with curly_braces_in_flow_control_structures will help us to create flow breakers more organically (e.g. avoid having `if (..) return;`)
    
- [avoid_slow_async_io](https://dart.dev/tools/linter-rules/avoid_slow_async_io) — Instead of using certain async IO function, dart suggests to use their sync alternatives

- [directives_ordering](https://dart.dev/tools/linter-rules/directives_ordering) — Sort imports

- [matching_super_parameters](https://dart.dev/tools/linter-rules/matching_super_parameters) — If you inherit from a class, make sure the constructor params sequence match the parent's params

- [no_self_assignments](https://dart.dev/tools/linter-rules/no_self_assignments) — Avoid having `a = a;`

- [prefer_asserts_in_initializer_lists](https://dart.dev/tools/linter-rules/prefer_asserts_in_initializer_lists) — Put asserts on the initializer level, not in to the constructor body

- [unnecessary_await_in_return](https://dart.dev/tools/linter-rules/unnecessary_await_in_return) — No need to await before returning

- [unnecessary_breaks](https://dart.dev/tools/linter-rules/unnecessary_breaks) — No need for a break unless you want to end execution earlier.

- [unnecessary_lambdas](https://dart.dev/tools/linter-rules/unnecessary_lambdas) — If a method's parameters match the parameters of a required callback, don't create a lambda but pass the method directly as a tear-off.

- [unnecessary_library_directive](https://dart.dev/tools/linter-rules/unnecessary_library_directive) — If `library` directive doesn't provide a name, it's not needed

- [unnecessary_null_aware_operator_on_extension_on_nullable](https://dart.dev/tools/linter-rules/unnecessary_null_aware_operator_on_extension_on_nullable) — If an extension is declared on a nullable type, no need to do the check

- [unnecessary_null_checks](https://dart.dev/tools/linter-rules/unnecessary_null_checks) — Removes null checks, e.g. if a function accepts a nullable variable there's no reason to pass it as `v!`

- [unnecessary_parenthesis](https://dart.dev/tools/linter-rules/unnecessary_parenthesis) — Removes brackets

- [unnecessary_statements](https://dart.dev/tools/linter-rules/unnecessary_statements) — Avoids having statements that return a result but aren't used.
- [unreachable_from_main](https://dart.dev/tools/linter-rules/unreachable_from_main) — Any member declared in an executable library should be used directly inside that library.

## 1.0.2

* Add platforms information to pub.dev

## 1.0.1

* Typo fix.

## 1.0.0

* Initial release.
