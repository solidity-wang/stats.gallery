<template>
  <footer class="p-4 bg-gray-800">
    <div
      class="
        max-w-7xl
        space-y-4
        md:space-y-0
        mx-auto
        sm:px-6
        md:flex md:items-center md:justify-between
        lg:px-8
      "
    >
      <div class="md:order-1 flex justify-center">
        <a href="https://near.org/" class="text-gray-400 hover:text-gray-500">
          <span class="sr-only">NEAR.org</span>
          <svg
            class="h-12"
            xmlns="http://www.w3.org/2000/svg"
            viewBox="0 0 414 162"
          >
            <g fill="currentColor">
              <path
                d="M207.21 54.75v52.5a.76.76 0 01-.75.75H201a7.49 7.49 0 01-6.3-3.43l-24.78-38.3.85 19.13v21.85a.76.76 0 01-.75.75h-7.22a.76.76 0 01-.75-.75v-52.5a.76.76 0 01.75-.75h5.43a7.52 7.52 0 016.3 3.42l24.78 38.24-.77-19.06V54.75a.75.75 0 01.75-.75h7.22a.76.76 0 01.7.75zM281 108h-7.64a.75.75 0 01-.7-1l20.24-52.28A1.14 1.14 0 01294 54h9.57a1.14 1.14 0 011.05.72L324.8 107a.75.75 0 01-.7 1h-7.64a.76.76 0 01-.71-.48l-16.31-43a.75.75 0 00-1.41 0l-16.31 43a.76.76 0 01-.72.48zM377.84 106.79L362.66 87.4c8.57-1.62 13.58-7.4 13.58-16.27 0-10.19-6.63-17.13-18.36-17.13h-21.17a1.12 1.12 0 00-1.12 1.12 7.2 7.2 0 007.2 7.2H357c7.09 0 10.49 3.63 10.49 8.87s-3.32 9-10.49 9h-20.29a1.13 1.13 0 00-1.12 1.13v26a.75.75 0 00.75.75h7.22a.76.76 0 00.75-.75V87.87h8.33l13.17 17.19a7.51 7.51 0 006 2.94h5.48a.75.75 0 00.55-1.21zM258.17 54h-33.5a1 1 0 00-1 1 7.33 7.33 0 007.33 7.33h27.17a.74.74 0 00.75-.75v-6.83a.75.75 0 00-.75-.75zm0 45.67h-25a.76.76 0 01-.75-.75V85.38a.75.75 0 01.75-.75h23.11a.75.75 0 00.75-.75V77a.75.75 0 00-.75-.75h-31.49a1.13 1.13 0 00-1.12 1.13v29.46a1.12 1.12 0 001.12 1.12h33.38a.75.75 0 00.75-.75v-6.83a.74.74 0 00-.75-.71zM108.24 40.57L89.42 68.5a2 2 0 003 2.63l18.52-16a.74.74 0 011.24.56v50.29a.75.75 0 01-1.32.48l-56-67A9.59 9.59 0 0047.54 36h-1.95A9.59 9.59 0 0036 45.59v70.82a9.59 9.59 0 009.59 9.59 9.59 9.59 0 008.17-4.57L72.58 93.5a2 2 0 00-3-2.63l-18.52 16a.74.74 0 01-1.24-.56V56.07a.75.75 0 011.32-.48l56 67a9.59 9.59 0 007.33 3.4h2a9.59 9.59 0 009.59-9.59V45.59a9.59 9.59 0 00-9.65-9.59 9.59 9.59 0 00-8.17 4.57z"
              />
            </g>
          </svg>
        </a>
      </div>
      <div class="flex justify-center space-x-6 md:order-3">
        <a
          href="https://twitter.com/NEARProtocol"
          class="text-gray-400 hover:text-gray-500"
        >
          <span class="sr-only">Twitter</span>
          <svg
            class="h-6 w-6"
            fill="currentColor"
            viewBox="0 0 24 24"
            aria-hidden="true"
          >
            <path
              d="M8.29 20.251c7.547 0 11.675-6.253 11.675-11.675 0-.178 0-.355-.012-.53A8.348 8.348 0 0022 5.92a8.19 8.19 0 01-2.357.646 4.118 4.118 0 001.804-2.27 8.224 8.224 0 01-2.605.996 4.107 4.107 0 00-6.993 3.743 11.65 11.65 0 01-8.457-4.287 4.106 4.106 0 001.27 5.477A4.072 4.072 0 012.8 9.713v.052a4.105 4.105 0 003.292 4.022 4.095 4.095 0 01-1.853.07 4.108 4.108 0 003.834 2.85A8.233 8.233 0 012 18.407a11.616 11.616 0 006.29 1.84"
            />
          </svg>
        </a>

        <a
          href="https://github.com/NEAR-Edu/stats.gallery"
          class="text-gray-400 hover:text-gray-500"
        >
          <span class="sr-only">GitHub</span>
          <svg
            class="h-6 w-6"
            fill="currentColor"
            viewBox="0 0 24 24"
            aria-hidden="true"
          >
            <path
              fill-rule="evenodd"
              d="M12 2C6.477 2 2 6.484 2 12.017c0 4.425 2.865 8.18 6.839 9.504.5.092.682-.217.682-.483 0-.237-.008-.868-.013-1.703-2.782.605-3.369-1.343-3.369-1.343-.454-1.158-1.11-1.466-1.11-1.466-.908-.62.069-.608.069-.608 1.003.07 1.531 1.032 1.531 1.032.892 1.53 2.341 1.088 2.91.832.092-.647.35-1.088.636-1.338-2.22-.253-4.555-1.113-4.555-4.951 0-1.093.39-1.988 1.029-2.688-.103-.253-.446-1.272.098-2.65 0 0 .84-.27 2.75 1.026A9.564 9.564 0 0112 6.844c.85.004 1.705.115 2.504.337 1.909-1.296 2.747-1.027 2.747-1.027.546 1.379.202 2.398.1 2.651.64.7 1.028 1.595 1.028 2.688 0 3.848-2.339 4.695-4.566 4.943.359.309.678.92.678 1.855 0 1.338-.012 2.419-.012 2.747 0 .268.18.58.688.482A10.019 10.019 0 0022 12.017C22 6.484 17.522 2 12 2z"
              clip-rule="evenodd"
            />
          </svg>
        </a>
      </div>
      <div class="md:order-2">
        <p class="text-center text-base text-gray-400">
          Built with ♥ by
          <a href="https://twitter.com/sudo_build" class="underline"
            >Jacob Lindahl</a
          >
        </p>
        <p class="text-center text-base text-gray-400">
          Designed with ♥ by
          <a href="https://t.me/danpodkovko" class="underline">Dan Podkovko</a>
        </p>
      </div>
    </div>
  </footer>
</template>
