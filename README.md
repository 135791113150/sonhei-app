# sonhei-app
sonhei
<!DOCTYPE html>
<html>

<head>
<meta name="viewport" content="width=device-width, initial-scale=1">

<link rel="manifest" href="manifest.json">
<meta name="theme-color" content="#5B3DF5">

</head>

<body>

<h1>SONHEI</h1>
<p>App em construção</p>

<script>
if ('serviceWorker' in navigator) {
  navigator.serviceWorker.register('service-worker.js')
}
</script>

</body>

</html>
}
{
  "name": "SONHEI",
  "short_name": "SONHEI",
  "start_url": "index.html",
  "display": "standalone",
  "background_color": "#0F0B1F",
  "theme_color": "#5B3DF5",
  "icons": [
    {
      "src": "assets/icon.png",
      "sizes": "192x192",
      "type": "image/png"
    },
    {
      "src": "assets/icon.png",
      "sizes": "512x512",
      "type": "image/png"
    }
  ]
}
self.addEventListener('install', e => {
  console.log('Service Worker instalado')
})

self.addEventListener('fetch', e => {
  // Aqui depois podemos colocar cache (offline)
})
<img width="512" height="512" alt="icon png" src="https://github.com/user-attachments/assets/38fed1d5-e477-4446-a8d9-15d2c5a65477" />
