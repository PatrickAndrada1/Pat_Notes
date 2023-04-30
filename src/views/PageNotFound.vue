<script>
import { RouterLink } from "vue-router";
export default {
  name: "PageNotFound",
};
</script>

<template>
  <!-- component -->

  <div class="bg-gray-100 h-screen justify-center">
    <center class="mt-24 m-auto">
      <svg
        class="emoji-404"
        enable-background="new 0 0 226 249.135"
        height="249.135"
        id="Layer_1"
        overflow="visible"
        version="1.1"
        viewBox="0 0 226 249.135"
        width="226"
        xml:space="preserve">
        <circle cx="113" cy="113" fill="#FFE585" r="109" />
        <line
          enable-background="new    "
          fill="none"
          opacity="0.29"
          stroke="#6E6E96"
          stroke-linecap="round"
          stroke-linejoin="round"
          stroke-width="8"
          x1="88.866"
          x2="136.866"
          y1="245.135"
          y2="245.135" />
        <line
          enable-background="new    "
          fill="none"
          opacity="0.17"
          stroke="#6E6E96"
          stroke-linecap="round"
          stroke-linejoin="round"
          stroke-width="8"
          x1="154.732"
          x2="168.732"
          y1="245.135"
          y2="245.135" />
        <line
          enable-background="new    "
          fill="none"
          opacity="0.17"
          stroke="#6E6E96"
          stroke-linecap="round"
          stroke-linejoin="round"
          stroke-width="8"
          x1="69.732"
          x2="58.732"
          y1="245.135"
          y2="245.135" />
        <circle cx="68.732" cy="93" fill="#6E6E96" r="9" />
        <path
          d="M115.568,5.947c-1.026,0-2.049,0.017-3.069,0.045  c54.425,1.551,98.069,46.155,98.069,100.955c0,55.781-45.219,101-101,101c-55.781,0-101-45.219-101-101  c0-8.786,1.124-17.309,3.232-25.436c-3.393,10.536-5.232,21.771-5.232,33.436c0,60.199,48.801,109,109,109s109-48.801,109-109  S175.768,5.947,115.568,5.947z"
          enable-background="new    "
          fill="#FF9900"
          opacity="0.24" />
        <circle cx="156.398" cy="93" fill="#6E6E96" r="9" />
        <ellipse
          cx="67.732"
          cy="140.894"
          enable-background="new    "
          fill="#FF0000"
          opacity="0.18"
          rx="17.372"
          ry="8.106" />
        <ellipse
          cx="154.88"
          cy="140.894"
          enable-background="new    "
          fill="#FF0000"
          opacity="0.18"
          rx="17.371"
          ry="8.106" />
        <path
          d="M13,118.5C13,61.338,59.338,15,116.5,15c55.922,0,101.477,44.353,103.427,99.797  c0.044-1.261,0.073-2.525,0.073-3.797C220,50.802,171.199,2,111,2S2,50.802,2,111c0,50.111,33.818,92.318,79.876,105.06  C41.743,201.814,13,163.518,13,118.5z"
          fill="#FFEFB5" />
        <circle
          cx="113"
          cy="113"
          fill="none"
          r="109"
          stroke="#6E6E96"
          stroke-width="8" />
      </svg>
      <div class="tracking-widest mt-4">
        <span class="text-gray-500 text-6xl block"><span>4 0 4</span></span>
        <span class="text-gray-500 text-xl">Halaman tidak ditemukan</span>
      </div>
    </center>
    <center class="mt-6">
      <a
        href="#"
        class="text-gray-500 font-mono text-xl text-gray-900 p-3 rounded-md hover:shadow-md"
        ><RouterLink to="/">Tekan di sini untuk kembali</RouterLink>
      </a>
    </center>
  </div>

  <!--Footer container-->
  <footer class="bg-neutral-200 text-center text-white dark:bg-neutral-600">
    <div class="container pt-9">
      <div class="mb-9 flex justify-center">
        <a
          href="https://web.facebook.com/index.php?next=https%3A%2F%2Fwww.facebook.com%2Fsettings&_rdc=1&_rdr"
          target="_blank"
          class="mr-9 text-neutral-800 dark:text-neutral-200">
          <svg
            xmlns="http://www.w3.org/2000/svg"
            class="h-4 w-4"
            fill="currentColor"
            viewBox="0 0 24 24">
            <path
              d="M9 8h-3v4h3v12h5v-12h3.642l.358-4h-4v-1.667c0-.955.192-1.333 1.115-1.333h2.885v-5h-3.808c-3.596 0-5.192 1.583-5.192 4.615v3.385z" />
          </svg>
        </a>
        <a
          href="https://twitter.com/?lang=en"
          target="_blank"
          class="mr-9 text-neutral-800 dark:text-neutral-200">
          <svg
            xmlns="http://www.w3.org/2000/svg"
            class="h-4 w-4"
            fill="currentColor"
            viewBox="0 0 24 24">
            <path
              d="M24 4.557c-.883.392-1.832.656-2.828.775 1.017-.609 1.798-1.574 2.165-2.724-.951.564-2.005.974-3.127 1.195-.897-.957-2.178-1.555-3.594-1.555-3.179 0-5.515 2.966-4.797 6.045-4.091-.205-7.719-2.165-10.148-5.144-1.29 2.213-.669 5.108 1.523 6.574-.806-.026-1.566-.247-2.229-.616-.054 2.281 1.581 4.415 3.949 4.89-.693.188-1.452.232-2.224.084.626 1.956 2.444 3.379 4.6 3.419-2.07 1.623-4.678 2.348-7.29 2.04 2.179 1.397 4.768 2.212 7.548 2.212 9.142 0 14.307-7.721 13.995-14.646.962-.695 1.797-1.562 2.457-2.549z" />
          </svg>
        </a>
        <a href="#!" class="mr-9 text-neutral-800 dark:text-neutral-200">
          <svg
            xmlns="http://www.w3.org/2000/svg"
            class="h-5 w-5"
            fill="currentColor"
            viewBox="0 0 24 24">
            <path
              d="M7 11v2.4h3.97c-.16 1.029-1.2 3.02-3.97 3.02-2.39 0-4.34-1.979-4.34-4.42 0-2.44 1.95-4.42 4.34-4.42 1.36 0 2.27.58 2.79 1.08l1.9-1.83c-1.22-1.14-2.8-1.83-4.69-1.83-3.87 0-7 3.13-7 7s3.13 7 7 7c4.04 0 6.721-2.84 6.721-6.84 0-.46-.051-.81-.111-1.16h-6.61zm0 0 17 2h-3v3h-2v-3h-3v-2h3v-3h2v3h3v2z"
              fill-rule="evenodd"
              clip-rule="evenodd" />
          </svg>
        </a>
        <a
          href="https://www.instagram.com/"
          target="_blank"
          class="mr-9 text-neutral-800 dark:text-neutral-200">
          <svg
            xmlns="http://www.w3.org/2000/svg"
            class="h-4 w-4"
            fill="currentColor"
            viewBox="0 0 24 24">
            <path
              d="M12 2.163c3.204 0 3.584.012 4.85.07 3.252.148 4.771 1.691 4.919 4.919.058 1.265.069 1.645.069 4.849 0 3.205-.012 3.584-.069 4.849-.149 3.225-1.664 4.771-4.919 4.919-1.266.058-1.644.07-4.85.07-3.204 0-3.584-.012-4.849-.07-3.26-.149-4.771-1.699-4.919-4.92-.058-1.265-.07-1.644-.07-4.849 0-3.204.013-3.583.07-4.849.149-3.227 1.664-4.771 4.919-4.919 1.266-.057 1.645-.069 4.849-.069zm0-2.163c-3.259 0-3.667.014-4.947.072-4.358.2-6.78 2.618-6.98 6.98-.059 1.281-.073 1.689-.073 4.948 0 3.259.014 3.668.072 4.948.2 4.358 2.618 6.78 6.98 6.98 1.281.058 1.689.072 4.948.072 3.259 0 3.668-.014 4.948-.072 4.354-.2 6.782-2.618 6.979-6.98.059-1.28.073-1.689.073-4.948 0-3.259-.014-3.667-.072-4.947-.196-4.354-2.617-6.78-6.979-6.98-1.281-.059-1.69-.073-4.949-.073zm0 5.838c-3.403 0-6.162 2.759-6.162 6.162s2.759 6.163 6.162 6.163 6.162-2.759 6.162-6.163c0-3.403-2.759-6.162-6.162-6.162zm0 10.162c-2.209 0-4-1.79-4-4 0-2.209 1.791-4 4-4s4 1.791 4 4c0 2.21-1.791 4-4 4zm6.406-11.845c-.796 0-1.441.645-1.441 1.44s.645 1.44 1.441 1.44c.795 0 1.439-.645 1.439-1.44s-.644-1.44-1.439-1.44z" />
          </svg>
        </a>
        <a
          href="https://www.linkedin.com/feed/"
          target="_blank"
          class="mr-9 text-neutral-800 dark:text-neutral-200">
          <svg
            xmlns="http://www.w3.org/2000/svg"
            class="h-4 w-4"
            fill="currentColor"
            viewBox="0 0 24 24">
            <path
              d="M4.98 3.5c0 1.381-1.11 2.5-2.48 2.5s-2.48-1.119-2.48-2.5c0-1.38 1.11-2.5 2.48-2.5s2.48 1.12 2.48 2.5zm.02 4.5h-5v16h5v-16zm7.982 0h-4.968v16h4.969v-8.399c0-4.67 6.029-5.052 6.029 0v8.399h4.988v-10.131c0-7.88-8.922-7.593-11.018-3.714v-2.155z" />
          </svg>
        </a>
        <a
          href="https://github.com/"
          target="_blank"
          class="text-neutral-800 dark:text-neutral-200">
          <svg
            xmlns="http://www.w3.org/2000/svg"
            class="h-4 w-4"
            fill="currentColor"
            viewBox="0 0 24 24">
            <path
              d="M12 0c-6.626 0-12 5.373-12 12 0 5.302 3.438 9.8 8.207 11.387.599.111.793-.261.793-.577v-2.234c-3.338.726-4.033-1.416-4.033-1.416-.546-1.387-1.333-1.756-1.333-1.756-1.089-.745.083-.729.083-.729 1.205.084 1.839 1.237 1.839 1.237 1.07 1.834 2.807 1.304 3.492.997.107-.775.418-1.305.762-1.604-2.665-.305-5.467-1.334-5.467-5.931 0-1.311.469-2.381 1.236-3.221-.124-.303-.535-1.524.117-3.176 0 0 1.008-.322 3.301 1.23.957-.266 1.983-.399 3.003-.404 1.02.005 2.047.138 3.006.404 2.291-1.552 3.297-1.23 3.297-1.23.653 1.653.242 2.874.118 3.176.77.84 1.235 1.911 1.235 3.221 0 4.609-2.807 5.624-5.479 5.921.43.372.823 1.102.823 2.222v3.293c0 .319.192.694.801.576 4.765-1.589 8.199-6.086 8.199-11.386 0-6.627-5.373-12-12-12z" />
          </svg>
        </a>
      </div>
    </div>

    <!--Copyright section-->
    <div
      class="bg-neutral-300 p-4 text-center text-neutral-700 dark:bg-neutral-700 dark:text-neutral-200">
      © 2023 Copyright:
      <a
        class="text-neutral-800 dark:text-neutral-400"
        href="https://tailwind-elements.com/"
        >PatrickAndrada1</a
      >
    </div>
  </footer>
</template>

<style>
.emoji-404 {
  position: relative;
  animation: mymove 2.5s infinite;
}
@keyframes mymove {
  33% {
    top: 0px;
  }
  66% {
    top: 20px;
  }
  100% {
    top: 0px;
  }
}

footer {
  position: fixed;
  /* left: 0; */
  bottom: 0;
  width: 100%;
  color: white;
  text-align: center;
  z-index: 1;
}
</style>
