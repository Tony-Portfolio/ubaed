<template>
    <div style="margin-top: -5px;">
        <HeroDetailProduct></HeroDetailProduct>
        <h2 class="text-3xl font-bold text-center">Detail <span class="text-orange-500">Product</span></h2>
        <div class="container my-25 px-6 mx-auto">
          <nav
            class="relative mb-10 flex w-full flex-wrap items-center justify-between bg-neutral-100 py-3 text-neutral-500 shadow-lg hover:text-neutral-700 focus:text-neutral-700 dark:bg-neutral-600 lg:flex-wrap lg:justify-start"
            data-te-navbar-ref>
            <div class="flex w-full flex-wrap items-center justify-between px-3">
              <nav class="bg-grey-light w-full rounded-md" aria-label="breadcrumb">
                <ol class="list-reset flex">
                  <li>
                    <a
                      href="#"
                      class="text-neutral-500 hover:text-neutral-600 dark:text-neutral-200"
                      >Home</a
                    >
                  </li>
                  <li>
                    <span class="mx-2 text-neutral-500 dark:text-neutral-200"
                      >/</span
                    >
                  </li>
                  <li>
                    <a
                      href="#"
                      class="text-neutral-500 hover:text-neutral-600 dark:text-neutral-200"
                      >Product</a
                    >
                  </li>
                  <li>
                    <span class="mx-2 text-neutral-500 dark:text-neutral-200"
                      >/</span
                    >
                  </li>
                  <li>
                    <a
                      href="#"
                      class="text-orange-500 hover:text-orange-600 dark:text-orange-200"
                      >Detail</a
                    >
                  </li>
                </ol>
              </nav>
            </div>
          </nav>
        <section class="mb-32 text-gray-800">
          <div class="block rounded-lg shadow-lg bg-white">
            <div class="flex flex-wrap items-center">
              <div class="grow-0 shrink-0 basis-auto block w-full lg:flex lg:w-6/12 xl:w-4/12">
                <img :src="product.thumbnail"
                  class="w-full rounded-t-lg lg:rounded-tr-none lg:rounded-bl-lg" />
              </div>
              <div class="grow-0 shrink-0 basis-auto w-full lg:w-6/12 xl:w-8/12">
                <div class="px-6 py-12 md:px-12">
                  <h2 class="text-3xl font-bold mb-6 pb-2">One-time payment</h2>
                  <p class="text-gray-500 mb-6 pb-2">
                    Lorem ipsum dolor sit amet, consectetur adipisicing elit. A soluta corporis
                    voluptate ab error quam dolores doloremque, quae consectetur.
                  </p>
                  <div class="flex flex-wrap mb-6">
                    <div class="w-full lg:w-6/12 xl:w-4/12 mb-4">
                      <p class="flex items-center">
                        <svg class="w-4 h-4 mr-2 text-green-600" role="img" xmlns="http://www.w3.org/2000/svg"
                          viewBox="0 0 512 512">
                          <path fill="currentColor"
                            d="M504 256c0 136.967-111.033 248-248 248S8 392.967 8 256 119.033 8 256 8s248 111.033 248 248zM227.314 387.314l184-184c6.248-6.248 6.248-16.379 0-22.627l-22.627-22.627c-6.248-6.249-16.379-6.249-22.628 0L216 308.118l-70.059-70.059c-6.248-6.248-16.379-6.248-22.628 0l-22.627 22.627c-6.248 6.248-6.248 16.379 0 22.627l104 104c6.249 6.249 16.379 6.249 22.628.001z">
                          </path>
                        </svg>Support 24/7
                      </p>
                    </div>
                    <div class="w-full lg:w-6/12 xl:w-4/12 mb-4">
                      <p class="flex items-center">
                        <svg class="w-4 h-4 mr-2 text-green-600" role="img" xmlns="http://www.w3.org/2000/svg"
                          viewBox="0 0 512 512">
                          <path fill="currentColor"
                            d="M504 256c0 136.967-111.033 248-248 248S8 392.967 8 256 119.033 8 256 8s248 111.033 248 248zM227.314 387.314l184-184c6.248-6.248 6.248-16.379 0-22.627l-22.627-22.627c-6.248-6.249-16.379-6.249-22.628 0L216 308.118l-70.059-70.059c-6.248-6.248-16.379-6.248-22.628 0l-22.627 22.627c-6.248 6.248-6.248 16.379 0 22.627l104 104c6.249 6.249 16.379 6.249 22.628.001z">
                          </path>
                        </svg>Analytics
                      </p>
                    </div>
                    <div class="w-full lg:w-6/12 xl:w-4/12 mb-4">
                      <p class="flex items-center">
                        <svg class="w-4 h-4 mr-2 text-green-600" role="img" xmlns="http://www.w3.org/2000/svg"
                          viewBox="0 0 512 512">
                          <path fill="currentColor"
                            d="M504 256c0 136.967-111.033 248-248 248S8 392.967 8 256 119.033 8 256 8s248 111.033 248 248zM227.314 387.314l184-184c6.248-6.248 6.248-16.379 0-22.627l-22.627-22.627c-6.248-6.249-16.379-6.249-22.628 0L216 308.118l-70.059-70.059c-6.248-6.248-16.379-6.248-22.628 0l-22.627 22.627c-6.248 6.248-6.248 16.379 0 22.627l104 104c6.249 6.249 16.379 6.249 22.628.001z">
                          </path>
                        </svg>Components
                      </p>
                    </div>
                    <div class="w-full lg:w-6/12 xl:w-4/12 mb-4">
                      <p class="flex items-center">
                        <svg class="w-4 h-4 mr-2 text-green-600" role="img" xmlns="http://www.w3.org/2000/svg"
                          viewBox="0 0 512 512">
                          <path fill="currentColor"
                            d="M504 256c0 136.967-111.033 248-248 248S8 392.967 8 256 119.033 8 256 8s248 111.033 248 248zM227.314 387.314l184-184c6.248-6.248 6.248-16.379 0-22.627l-22.627-22.627c-6.248-6.249-16.379-6.249-22.628 0L216 308.118l-70.059-70.059c-6.248-6.248-16.379-6.248-22.628 0l-22.627 22.627c-6.248 6.248-6.248 16.379 0 22.627l104 104c6.249 6.249 16.379 6.249 22.628.001z">
                          </path>
                        </svg>Updates
                      </p>
                    </div>
                    <div class="w-full lg:w-6/12 xl:w-4/12 mb-4">
                      <p class="flex items-center">
                        <svg class="w-4 h-4 mr-2 text-green-600" role="img" xmlns="http://www.w3.org/2000/svg"
                          viewBox="0 0 512 512">
                          <path fill="currentColor"
                            d="M504 256c0 136.967-111.033 248-248 248S8 392.967 8 256 119.033 8 256 8s248 111.033 248 248zM227.314 387.314l184-184c6.248-6.248 6.248-16.379 0-22.627l-22.627-22.627c-6.248-6.249-16.379-6.249-22.628 0L216 308.118l-70.059-70.059c-6.248-6.248-16.379-6.248-22.628 0l-22.627 22.627c-6.248 6.248-6.248 16.379 0 22.627l104 104c6.249 6.249 16.379 6.249 22.628.001z">
                          </path>
                        </svg>Reports
                      </p>
                    </div>
                    <div class="w-full lg:w-6/12 xl:w-4/12 mb-4">
                      <p class="flex items-center">
                        <svg class="w-4 h-4 mr-2 text-green-600" role="img" xmlns="http://www.w3.org/2000/svg"
                          viewBox="0 0 512 512">
                          <path fill="currentColor"
                            d="M504 256c0 136.967-111.033 248-248 248S8 392.967 8 256 119.033 8 256 8s248 111.033 248 248zM227.314 387.314l184-184c6.248-6.248 6.248-16.379 0-22.627l-22.627-22.627c-6.248-6.249-16.379-6.249-22.628 0L216 308.118l-70.059-70.059c-6.248-6.248-16.379-6.248-22.628 0l-22.627 22.627c-6.248 6.248-6.248 16.379 0 22.627l104 104c6.249 6.249 16.379 6.249 22.628.001z">
                          </path>
                        </svg>Mobile
                      </p>
                    </div>
                  </div>
                  <button type="button"
                    class="inline-block px-7 py-3 bg-blue-600 text-white font-medium text-sm leading-snug uppercase rounded shadow-md hover:bg-blue-700 hover:shadow-lg focus:bg-blue-700 focus:shadow-lg focus:outline-none focus:ring-0 active:bg-blue-800 active:shadow-lg transition duration-150 ease-in-out"
                    data-mdb-ripple="true" data-mdb-ripple-color="light">
                    Buy now
                  </button>
                </div>
              </div>
            </div>
          </div>
        </section>

        </div>
    </div>
</template>

<script>
import axios from 'axios';

export default {
  data() {
    return {
        product: {}
    }
  },
  methods: {
    // Mengambil satu data
    setProduct(data){
      this.product = data
    }
  },
  // Proses mengambil satu data product food
  mounted() {
    axios.get('https://dummyjson.com/products/'+this.$route.params.id)
    .then((response) =>
      // Proses berhasil
      this.setProduct(response.data)
    )
    .catch((error) =>
      // Proses gagal
      console.log(error)
    )
  }
}
</script>