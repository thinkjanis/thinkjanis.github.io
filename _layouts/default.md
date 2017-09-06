<!DOCTYPE html>
<html lang="{{ page.lang | default: site.lang | default: "en" }}">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta http-equiv="X-UA-Compatible" content="ie=edge">
  <meta name="description" content="{{ site.description }}">
  <title>{{ site.title }}</title>
  <link rel="stylesheet" type="text/css" href="/css/main.css">
</head>
<body>
  {{ content }}
</body>
</html>