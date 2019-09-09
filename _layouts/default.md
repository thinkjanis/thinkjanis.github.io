<!DOCTYPE html>
<html lang="{{ page.lang | default: site.lang | default: " en " }}">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta http-equiv="X-UA-Compatible" content="ie=edge">

  <title>{{ site.title }}</title>
  <meta name="description" content="{{ site.description }}">
  <meta property="og:title" content="{{ site.title }}" />
  <meta property="og:description" content="{{ site.description }}" />
  <meta property="og:image" content="{{ site.og_photo }}" />

<link href="https://fonts.googleapis.com/css?family=PT+Serif:400,400i,700,700i&display=swap" rel="stylesheet">
  <link rel="stylesheet" type="text/css" href="/css/main.css">
  <link rel="icon" type="image/png" href="/favicon.png" sizes="152x152">
</head>

<body id="site">
  <div id="wrapper">
    {{ content }}
  </div>
  {% include footer.md %}
  <script src="/js/main.js"></script>
</body>

</html>