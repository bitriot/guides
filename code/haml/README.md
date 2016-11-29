HAML
===

* Avoid use of `content_tag`
* Prefer `javascript_include_tag` over `%script`
* Prefer `stylesheet_link_tag` over `%link`
* Prefer `link_to` over `%a`
* Prefer `link_to 'Title', object` over `link_to 'Title', object_path(object)`
* Prefer `for in` over `.each`
* Use a single line for basic content `%h3 Order #{order.id}`
