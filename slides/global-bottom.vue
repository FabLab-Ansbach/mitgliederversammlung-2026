<template>
  <footer v-if="$slidev.slide !== 0" class="fixed bottom-0 left-0 right-0 p-1 text-center text-black flex items-center z-50">
<div class="flex-shrink-0">
<img src="https://www.fablab-ansbach.de/fileadmin/templates/default/img/site-logo.png" class="h-10 w-auto"></img>
</div>
<div class="absolute left-1/2 transform -translate-x-1/2 text-center">
{{ $slidev.configs.author }}
</div>
<div class="flex-shrink-0 ml-auto mr-3">
{{ $slidev.configs.date }}
</div>
</footer>
</template>