<script>
  import "../app.css";
</script>

<svelte:head>
  <title>Temp Title</title>
  <meta name="description" content="" />
</svelte:head>

<div class="relative flex flex-col justify-center min-h-screen overflow-hidden bg-gray-50 sm:py-6">
  <div class="absolute inset-0 bg-[url(/circles.svg)]" />
  <div class="relative bg-white shadow-xl ring-1 ring-gray-900 drop-shadow-[1px_1px_0px_rgba(0,0,0,1)] sm:mx-auto sm:max-w-2xl">
    <header class="text-5xl font-bold sm:mx-auto sm:max-w-2xl sm:p-5 bg-sky-200 text-sky-900 ring-1 ring-gray-900">
      <i class="bi bi-robot" />
      Header
    </header>
    <div class="max-w-2xl mx-auto sm:px-10">
      <div class="divide-y divide-gray-300/50">
        <div class="space-y-6 text-base leading-7 text-gray-600">
          <slot />
        </div>
      </div>
    </div>
    <footer class="text-5xl font-bold sm:mx-auto sm:max-w-2xl sm:p-5 bg-sky-200 text-sky-900 ring-1 ring-gray-900">
      <i class="bi bi-arrow-down" />
      Feader
    </footer>
  </div>
</div>
