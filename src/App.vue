<template>
  <div id="app">
    <header class="bg-blue-600 text-white p-4">
      <h1 class="text-2xl font-bold">清源洗衣液</h1>
      <p class="text-sm">洁净如新，呵护全家</p>
    </header>
    <main class="container mx-auto p-4">
      <section class="mb-8">
        <h2 class="text-xl font-semibold mb-4">核心产品</h2>
        <div class="grid grid-cols-1 md:grid-cols-3 gap-4">
          <div class="border rounded-lg p-4">
            <h3 class="font-medium">经典款洗衣液</h3>
            <p class="text-gray-600">高效去污，温和配方</p>
          </div>
          <div class="border rounded-lg p-4">
            <h3 class="font-medium">浓缩型洗衣液</h3>
            <p class="text-gray-600">用量减半，洁净加倍</p>
          </div>
          <div class="border rounded-lg p-4">
            <h3 class="font-medium">天然香氛系列</h3>
            <p class="text-gray-600">植物萃取，持久留香</p>
          </div>
        </div>
      </section>
      <section>
        <h2 class="text-xl font-semibold mb-4">联系我们</h2>
        <p>电话：400-123-4567</p>
        <p>邮箱：contact@laundry.com</p>
      </section>
    </main>
    <footer class="bg-gray-100 p-4 text-center text-gray-600">
      © 2026 清源洗衣液. 保留所有权利.
    </footer>
  </div>
</template>

<script>
export default {
  name: 'App'
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
}
</style>