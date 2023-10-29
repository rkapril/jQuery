# jQuery
```
<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.7.1/jquery.min.js"></script>
```
## Select
```
$("h1")
```
## CSS
```
$("h1").css("font-size", "5rem");
$("h1").css("color", "red");
```
## Class
```
$("h1").addClass("big-title margin-50");
$("h1").hasClass("margin-50");
$("h1").hasClass("big-title margin-50");
$("h1").removeClass("big-title margin-50");
```
## Text/HTML
```
$("button").text("Don't Click Me");
$("button").html("<em>Hey</em>");
```
## Attribute
```
$("img").attr("src");
$("a").attr("href", "https://www.yahoo.com");
$("h1").attr("class");
```
## Event Listener
```
$("h1").click(function () {
    $("h1").css("color", "purple");
  });

$("button").click(function () {
    $("h1").css("color", "purple");
  });

$("button").on("click", function () {
    $("h1").hide();
  });

$("button").on("click", function () {
    $("h1").show();
  });

$("button").on("click", function () {
    $("h1").fadeIn();
  });

$("button").on("click", function () {
    $("h1").fadeOut();
  });

$("button").on("click", function () {
    $("h1").slideUp();
  });

$("button").on("click", function () {
    $("h1").slideDown();
  });

$("button").on("click", function () {
    $("h1").toggle();
  });

$("button").on("click", function () {
    $("h1").fadeToggle();
  });

$("button").on("click", function () {
    $("h1").slideToggle();
  });

$("button").on("click", function () {
    $("h1").animate({ opacity: 0.5 });
  });

$("button").on("click", function () {
    $("h1").slideUp().slideDown().animate({ opacity: 0.5 });
  });

$("input").keypress(function (event) {
    console.log(event.key);
  });

$(document).keypress(function (event) {
    console.log(event.key);
  });

$(document).keypress(function (event) {
    $("h1").text(event.key)
  });

$("h1").on("mouseover", function () {
    $("h1").css("color", "purple");
  });
```
## Before
```
$("h1").before("<button>Before</button>");
```
## After
```
$("h1").after("<button>After</button>");
```
## Prepend
```
$("h1").prepend("<button>Prepend</button>"); // Inside the element (Before the text)
```
## Append
```
$("h1").append("<button>Append</button>"); // Inside the element (After the text)
```
## Remove
```
$("button").remove();
```
