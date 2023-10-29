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
$("h1").before("<button>New</button>");
```
## After
```
$("h1").after("<button>Before</button>");
```
