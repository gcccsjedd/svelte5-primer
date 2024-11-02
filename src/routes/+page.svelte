<main class="text-2xl p-8 bg-slate-950 text-white min-h-screen">
  <div class="flex flex-col gap-4">
    <b>Creating Svelte Project</b>
    <div class="grid grid-cols-3 gap-4">
      <code>npm create svelte@latest (project name)</code>
      <code class="text-green-500">npx sv create (project name)</code>
    </div>
    <hr />
    <b>Adding Tailwind CSS with zero configuration</b>
    <div class="grid grid-cols-3 gap-4">
      <code>npx svelte-add@latest tailwindcss</code>
      <code class="text-green-500">npx sv add tailwindcss</code>
    </div>
    <hr />
    <b>Adding Flowbite and Other packages</b>
    <div class="grid grid-cols-3 gap-4">
      <code>npm install -D flowbite</code>
    </div>
    <hr />
    <b>Creating State Variable / Declaring State</b>
    <div class="grid grid-cols-3 gap-4">
      <code>let count = 0;</code>
      <code class="text-green-500">let count = $state(0);</code>
    </div>
    <hr />
    <b>Updating State</b>
    <div class="grid grid-cols-3 gap-4">
      <code>count++;</code>
      <code class="text-green-500">count++;</code>
    </div>
    <hr />
    <b>Computed State</b>
    <div class="grid grid-cols-3 gap-4">
      <code>$: doubleCount = count * 2;</code>
      <code class="text-green-500">const doubleCount = $derived(count * 2);</code>
    </div>
    <hr />
    <b>Click Event</b>
    <div class="grid grid-cols-3 gap-4">
      <code>{`<button on:click={() => count++}>Add</button>`}</code>
      <code class="text-green-500"
        >{`<button onclick={() => count++}>Add</button>`}</code
      >
    </div>
  </div>
</main>
