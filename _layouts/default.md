<!DOCTYPE html>
<html lang="{{ page.lang | default: site.lang | default: "en" }}">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta http-equiv="X-UA-Compatible" content="ie=edge">
  <meta name="description" content="{{ site.description }}">
  <title>{{ site.title }}</title>
  <link href="https://fonts.googleapis.com/css?family=Raleway:100,100i,200,200i,300,300i,400,400i,500,500i,600,600i,700,700i,800,800i,900,900i&amp;subset=latin-ext" rel="stylesheet">
  <link rel="stylesheet" type="text/css" href="/css/main.css">
</head>
<body id="site">
  <div id="wrapper">
    {{ content }}
  </div>
  {% include footer.md %}
  <script src="/js/main.js"></script>
</body>
</html>
