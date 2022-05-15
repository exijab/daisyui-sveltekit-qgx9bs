<svelte:head>
	<title>Temp Title</title>
	<meta name="description" content="" />
</svelte:head>

<script>
	import '../app.css';
</script>

<div class="relative flex min-h-screen flex-col justify-center overflow-hidden bg-gray-50 py-6 sm:py-12">
  <div class="relative bg-white px-6 pt-10 pb-8 shadow-xl ring-2 ring-black rounded-sm drop-shadow-[3px_3px_0px_rgba(0,0,0,1)] sm:mx-auto sm:max-w-2xl sm:px-10">
    <div class="mx-auto max-w-2xl">
			<header class="sm:p-5 bg-sky-200 font-bold text-5xl text-sky-900 ring-2 ring-black rounded-sm drop-shadow-[3px_3px_0px_rgba(0,0,0,1)]">
				<i class="bi bi-robot"></i>
				Header
			</header>
      <div class="divide-y divide-gray-300/50">
        <div class="space-y-6 py-8 text-base leading-7 text-gray-600">

          <p>An advanced online playground for Tailwind CSS, including support for things like:</p>
          <ul class="space-y-4">
            <li class="flex items-center">

							<slot />

            </li>
            <li class="flex items-center">
              <svg class="h-6 w-6 flex-none fill-sky-100 stroke-sky-500 stroke-2" stroke-linecap="round" stroke-linejoin="round">
                <circle cx="12" cy="12" r="11" />
                <path d="m8 13 2.165 2.165a1 1 0 0 0 1.521-.126L16 9" fill="none" />
              </svg>
              <p class="ml-4">
                Extracting classes with
                <code class="text-sm font-bold text-gray-900">@apply</code>
              </p>
            </li>
            <li class="flex items-center">
              <svg class="h-6 w-6 flex-none fill-sky-100 stroke-sky-500 stroke-2" stroke-linecap="round" stroke-linejoin="round">
                <circle cx="12" cy="12" r="11" />
                <path d="m8 13 2.165 2.165a1 1 0 0 0 1.521-.126L16 9" fill="none" />
              </svg>
              <p class="ml-4">Code completion with instant preview</p>
            </li>
          </ul>
          <p>Perfect for learning how the framework works, prototyping a new idea, or creating a demo to share online.</p>
        </div>
				<footer class="sm:p-5 bg-sky-300 font-bold text-5xl text-sky-900 ring-2 ring-black rounded-sm drop-shadow-[3px_3px_0px_rgba(0,0,0,1)]">
					<i class="bi bi-arrow-down"></i>
					Footer
				</footer>
      </div>
    </div>
  </div>
</div>
