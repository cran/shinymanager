# shinymanager 1.0.300

* Add ``autofocus`` on username input.
* Fix some (strange) bug with ``input$shinymanager_where``
* Fix `inputs_list` with some shiny version
* `auth_ui()` now accept a `choose_language` arguments.
* Rename `br` language into `pt-BR` (iso code)
* add user info in downloaded log file
* add `set_labels()` for customize labels
* Fix simultaneous admin session
* (#37) hashing password using `scrypt`

# shinymanager 1.0.200

* Can configure shiny input for editing user in `secure_app()` with new `inputs_list`.
* `auth_ui()` now accept a `background` argument change default css.
* `auth_ui()` : `tag_img` -> `tags_top`, `tag_div` -> `tags_bottom`
* (#18) IE compatibility (timeout & admin log)
* (#17) Add support to Brazilian Portuguese. Thanks to @erikson84

# shinymanager 1.0.100

* Fix bug on timeout.
* `secure_app()` now accept a `function` to define the UI.
* Disable `admin mode` if no SQL database
* `admin mode` : add possibility to export encrypt SQL

# shinymanager 1.0

* Now on CRAN
      
      
