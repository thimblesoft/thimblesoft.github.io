<script lang="ts">
  import './app.css'
  import Logo from './lib/Logo.svelte'
</script>

<main class="min-h-screen bg-gray-50 flex items-center justify-center">
  <div class="text-center px-6 max-w-2xl">
    <div class="flex items-center justify-center mb-6">
      <Logo size={64} className="text-gray-700" />
    </div>
    <h1 class="text-5xl font-bold text-gray-900 mb-4">Thimblesoft</h1>
    <p class="text-xl text-gray-600">Simple tools for everyday annoyances</p>
  </div>
</main>