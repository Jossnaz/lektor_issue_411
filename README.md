# lektor_issue_411

https://github.com/lektor/lektor/issues/411

steps to reproduce

start lektor server


`$ lektor server`

go to test-page1

now open the file `templates/macros/render_percentage_item.html`

add random text somewhere to see

reload the test-page1 -> the change will not show.

Stop the lektor server

start the lektor server

still no change visible

do `$ lektor clean && lektor build`

`$ lektor server`

only now the changes show.

