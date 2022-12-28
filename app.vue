<template>
  <div>
    <nav>
      <ul>
        <li><NuxtLink to="/">Home</NuxtLink></li>
        <li><NuxtLink to="/page/1">Page 1</NuxtLink></li>
        <li><NuxtLink to="/13">Page 13</NuxtLink></li>
        <li><NuxtLink to="/page/2">Page 2</NuxtLink></li>
        <li><NuxtLink to="/page/100">Page 100</NuxtLink></li>
        <li><NuxtLink to="/errorne">Page Error 2</NuxtLink></li>
      </ul>
    </nav>

    <main>
      <NuxtPage />
    </main>
  </div>
</template>
