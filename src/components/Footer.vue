<template>
  <footer class="bg-gray-200">
    <div class="container m-auto md:flex justify-between items-center px-6 py-10">
      <p class="text-gray-700 pb-8 md:pb-0">
        &copy; {{ new Date().getFullYear() }} Eclectic Saddlebag - My Eclectic Journey
      </p>
      <ul class="flex justify-center">
        <li class="mr-4">
          <a
            href="https://linkedin.com"
            target="_blank"
            rel="noreferrer nofollow"
            aria-label="My LinkedIn profile ">
            <font-awesome
              :icon="['fab', 'linkedin']"
              class="text-2xl text-gray-500 hover:text-pink-700 transition delay-150 duration-150 ease-in-out"
            />
          </a>
        </li>
        <li class="mr-4">
          <a
            href="https://twitter.com"
            target="_blank"
            rel="noreferrer nofollow"
            aria-label="My Twitter profile ">
            <font-awesome
              :icon="['fab', 'twitter']"
              class="text-2xl text-gray-500 hover:text-pink-700 transition delay-150 duration-150 ease-in-out"
            />
          </a>
        </li>
        <li class="mr-4">
          <a
            href="https://dev.to"
            target="_blank"
            rel="noreferrer nofollow"
            aria-label="Me Practical Dev profile ">
            <font-awesome
              :icon="['fab', 'dev']"
              class="text-2xl text-gray-500 hover:text-pink-700 transition delay-150 duration-150 ease-in-out"
            />
          </a>
        </li>
      </ul>
    </div>
  </footer>
</template>

<script>
  export default {
    name: 'Footer',
  };
</script>

<style scoped>

</style>
