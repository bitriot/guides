Rails
===

* Avoid :except
* Avoid `member` and `collection` routes for associated objects
* Prefer resource routes
* Order resource routes alphabetically by name within their scope
* Use `before_action` over `before_filter`
* Use `render collection` over explicitly looping over `_show`
* Use `link_to` only for `GET` requests
* Use `button_to` for other `HTTP` verbs
* Use `scope` DSL over `self.method_name`
* Use `_on` column name for `date` columns
* Use `_at` column name for `datetime` columns
* Use `before_action` method finding an object in multiple actions
* Use `current_user.objects.find(params[:id])` over `if found_object.user_id == current_user.id`
* Shared partials go in `app/views/shared`
* Extract shared functionality across models to modules
* Extract re-usable functionality to modules (add to guide)

Commonly Used Files
---
* Session System
* Mail Interceptor
* UserVerifier
* Stripe
  * ChargesController
  * SubscriptionsController
  * wtripe.coffe

