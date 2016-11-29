Ruby
===

- Avoid multiple assignments per line (`one, two = 1, 2`)
- Avoid explicit returns
- Avoid using ternary operators (`condition ? true : false`)
- Avoid using `unless` with `else`
- Prefer `map` when making changes
- Prefer `collect` when returning values; i.e., `collection.collect(&:id)`
- Prefer `&:method_name` to `{ |item| item.method_name }`
- Prefer `collection.empty?` over `collection.count == 0`
- Prefer `&&` and `||` over `and` and `or`
- Prefer `if` over `unless`
- Prefer `.each` over `for in`