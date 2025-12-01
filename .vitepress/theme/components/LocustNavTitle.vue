<template>
  <a class="locust-nav-logo" href="/" aria-label="Locust 中文文档">
    <img
      class="light-logo"
      src="/Locust-logo-lightmode.svg"
      alt="Locust 中文文档"
      aria-hidden="true"
    />
    <img
      class="dark-logo"
      src="/Locust-logo-darkmode.svg"
      alt="Locust 中文文档"
      aria-hidden="true"
    />
    <span class="sr-only">Locust 中文文档</span>
  </a>
</template>

<style scoped>
.dark .light-logo {
  display: none;
}

.light .dark-logo,
html:not(.dark) .dark-logo {
  display: none;
}
</style>
