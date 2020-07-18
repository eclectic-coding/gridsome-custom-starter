<template>
  <div>
    <a href="#main" class="sr-only">Skip to content</a>
    <div class="flex flex-col min-h-screen">
      <Header />
      <main id="main" class="container mx-auto flex flex-1 flex-col py-10 lg:py-20">
        <slot/>
      </main>
       <Footer />
    </div>
  </div>
</template>

<static-query>
query {
  metadata {
    siteName
  }
}
</static-query>

<script>
  import Header from '@/components/Header.vue';
  import Footer from '@/components/Footer.vue';

  export default {
    components: {
      Header,
      Footer
    }
  }
</script>
