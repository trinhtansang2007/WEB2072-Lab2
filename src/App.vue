<script setup>
import Bai1 from "./Labs/Lab-2/Bai1.vue";
import Bai2 from "./Labs/Lab-2/Bai2.vue";
import Bai3 from "./Labs/Lab-2/Bai3.vue";
import Bai4 from "./Labs/Lab-2/Bai4.vue";
</script>

<template>
  <div class="p-3">
    <section class="mb-5">
      <h2 class="h5 text-secondary">Bài 1 - ref()</h2>
      <Bai1 />
    </section>

    <hr />

    <section class="mb-5">
      <h2 class="h5 text-secondary">Bài 2 - reactive()</h2>
      <Bai2 />
    </section>

    <hr />

    <section class="mb-5">
      <h2 class="h5 text-secondary">Bài 3 - One-way / Two-way Binding</h2>
      <Bai3 />
    </section>

    <hr />

    <section class="mb-5">
      <h2 class="h5 text-secondary">Bài 4 - Class & Style Binding</h2>
      <Bai4 />
    </section>
  </div>
</template>
