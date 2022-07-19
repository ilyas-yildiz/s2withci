# s2withci
Including select2 in Codeigniter project.

ROAD MAP

1- First we need to include jquery in our page.

jquery: <script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/3.6.0/jquery.min.js"></script>

2- We include the cdns we got from select2.org in our view file. jquery this should come before the js file below.

css: https://cdn.jsdelivr.net/npm/select2@4.1.0-rc.0/dist/css/select2.min.css

js: https://cdn.jsdelivr.net/npm/select2@4.1.0-rc.0/dist/js/select2.min.js

3- We add the js code snippet that will run select2 before the body tag is closed.
<script>

    $(document).ready(function() {

        $('.js-example-basic-single').select2();

    });

</script>


4- We create a select whose class is js-example-basic-single.

5- That's it for the process. You can view your view file and see the result. 
here we showed you the Single select boxes example. You can easily make the structure called "Multi-select boxes (pillbox)" in the documentation yourself. All you have to do is create a structure similar to the example here;

https://select2.org/getting-started/basic-usage
