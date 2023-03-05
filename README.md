# Simple login

Simple log in made with only html and css.

Added cool animation on email/password box on click:

<img src="./source/done.PNG">

removed (autocomplete="off") from index.js

added the following implementation on index.css to remove browser autofill color:

input:-webkit-autofill,
input:-webkit-autofill:focus {
    transition: background-color 600000s 0s, color 600000s 0s;
}

input[data-autocompleted] {
    background-color: transparent !important;
}
