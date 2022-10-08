<script>
  import "../app.css";
  import {supabase} from '../services/supabase'
  console.log(supabase)
</script>

<div class="bg-yellow-50 min-h-screen">
  <main class="max-w-screen-xl pt-4 mx-auto">
    <slot />
  </main>
</div>
