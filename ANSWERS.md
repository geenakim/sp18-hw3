## Questions

1. What does the second 'nil' argument in the line 6 text_field_tag of teachers/new.html.erb represent?

The 'nil' is the value of the tag, and serves as a placeholder for value of course name until an actual value is inputted.

2. Go to `localhost:3000/teachers` in your browser; why does this not work?

No route exists to this path, as there was no form submitted.


3. What type of request did your browser just perform?

GET

4. Go back to `localhost:3000/teachers/new`; submit the form again. What URL do you end up at?

http://localhost:3000/teachers


5. Why does `localhost:3000/teachers` work now?

Since we submitted the form and inputted values, we now have a route to this page
