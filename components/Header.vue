<template>
  <div class="">
    <div v-if="!menuOpen" class="flex flex-row p-2">
      <div class="w-full">
        <h1>マツモト ヒトミ</h1>
        <div class="sns-icon">aaaaaa</div>
      </div>
      <button class="w-10" @click="menuOpen=true">
        <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20" fill="currentColor">
          <path fill-rule="evenodd" d="M3 5a1 1 0 011-1h12a1 1 0 110 2H4a1 1 0 01-1-1zM3 10a1 1 0 011-1h12a1 1 0 110 2H4a1 1 0 01-1-1zM3 15a1 1 0 011-1h12a1 1 0 110 2H4a1 1 0 01-1-1z" clip-rule="evenodd" />
        </svg>
      </button>

    </div>

    <div v-else class="menu p-2">
      <button class="block w-10 ml-auto mr-0" @click="menuOpen=false">
        <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20" fill="currentColor">
          <path fill-rule="evenodd" d="M4.293 4.293a1 1 0 011.414 0L10 8.586l4.293-4.293a1 1 0 111.414 1.414L11.414 10l4.293 4.293a1 1 0 01-1.414 1.414L10 11.414l-4.293 4.293a1 1 0 01-1.414-1.414L8.586 10 4.293 5.707a1 1 0 010-1.414z" clip-rule="evenodd" />
        </svg>
      </button>
      <div>
        <li>HOME</li>
        <li>ABOUT</li>
        <li>PERSONAL WORKS</li>
        <li>CLIENT WORKS</li>
        <li>BLOG</li>

        <button>STORE (SUZURI)</button>
        <button>CONTACT</button>
        <button>ABOUT</button>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      menuOpen: false
    };
  }
}

</script>

<style>

</style>

