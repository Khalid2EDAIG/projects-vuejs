<template>
  <div id="footer">
    <footer class="pin-b">
      <div class="flex mt-20 ">
        <h1 class="text-3xl text-gray-800 font-semibold">
          Join instantly with $0 down <br />
          and get your car right now.
        </h1>
        <button
          class="py-2 px-6 h-12 w-64 mt-6  text-white bg-gray-700 hover:bg-gray-800 rounded-full getStarted focus:outline-none focus:shadow-outline"
        >
          Get started
        </button>
      </div>
      <hr class="border-gray-400 border-1 mb-20 mt-20" />
      <div class="flex mt-10">
        <div class=" flex-auto">
          <label class="mb-6 text-xl text-gray-600 font-semibold uppercase"
            >product</label
          >
          <a
            class="block mt-4 text-gray-800 text-gray-500 hover:text-gray-600"
            href=""
            >Personal</a
          >
          <a
            class="block mt-4 text-gray-800 text-gray-500 hover:text-gray-600"
            href=""
            >Business</a
          >
          <a
            class="block mt-4 text-gray-800 text-gray-500 hover:text-gray-600"
            href=""
            >Pricing</a
          >
          <a
            class="block mt-4 text-gray-800 text-gray-500 hover:text-gray-600"
            href=""
            >Log In</a
          >
        </div>
        <div class="flex-auto">
          <label class="mb-6 text-xl text-gray-600 font-semibold uppercase"
            >conpany</label
          >
          <a
            class="block mt-4 text-gray-800 text-gray-500 hover:text-gray-600"
            href=""
            >About</a
          >
          <a
            class="block mt-4 text-gray-800 text-gray-500 hover:text-gray-600"
            href=""
            >Blog</a
          >
          <a
            class="block mt-4 text-gray-800 text-gray-500 hover:text-gray-600"
            href=""
            >Careers</a
          >
          <a
            class="block mt-4 text-gray-800 text-gray-500 hover:text-gray-600"
            href=""
            >Contact Us</a
          >
        </div>
        <div class=" flex-auto">
          <label class="mb-6 text-xl text-gray-600 font-semibold uppercase"
            >help center</label
          >
          <a
            class="block mt-4 text-gray-800 text-gray-500 hover:text-gray-600"
            href=""
            >FAQ</a
          >
          <a
            class="block mt-4 text-gray-800 text-gray-500 hover:text-gray-600"
            href=""
            >Insurance</a
          >
          <a
            class="block mt-4 text-gray-800 text-gray-500 hover:text-gray-600"
            href=""
            >Agreement</a
          >
        </div>
        <div class="flex-auto">
          <label class="mb-6 text-xl text-gray-600 font-semibold uppercase"
            >stay in touch</label
          >
          <span class=" block mt-4"
            >Join our mailing list to get updates.We respect your privacy.</span
          >
          <form action="">
            <input
              class="mt-6 py-3 px-8 pr-16 bg-gray-300 rounded-full send-email hover:bg-gray-200 focus:outline-none focus:shadow-outline"
              type="email"
              placeholder="Email address..."
            />
            <button
              type="submit"
              class="-ml-12 py-2 px-3 bg-gray-600 rounded-full text-white hover:bg-gray-800 hover:text-green-600"
            >
              <i class="fas fa-paper-plane"></i>
            </button>
          </form>
        </div>
      </div>
      <div class="mt-20 flex">
        <div class="flex-auto">
          <span class="text-3xl text-gray-700 font-semibold">upshift</span>
        </div>
        <div class="flex-auto py-3">
          <span class="text-center text-gray-600 text-lg"
            >Copyright &copy; 2019 upshift,Inc</span
          >
        </div>
        <div class="flex-auto">
          <a
            class="h-12 w-12 py-3 px-4 mr-4 bg-gray-400 rounded-full text-center hover:bg-white hover:text-blue-700"
            href=""
          >
            <i class="fab fa-facebook-f fa-lg"></i>
          </a>

          <a
            class="h-12 w-12 py-3 px-3 mr-4 bg-gray-400 rounded-full text-center hover:bg-white hover:text-blue-700"
            href=""
          >
            <i class="fab fa-twitter fa-lg"></i>
          </a>

          <a
            class="h-12 w-12 py-3 px-4 mr-4 bg-gray-400 rounded-full text-center hover:bg-white hover:text-blue-700"
            href=""
          >
            <i class="fab fa-linkedin-in fa-lg"></i>
          </a>
        </div>
      </div>
    </footer>
  </div>
</template>
<script>
export default {
  name: "Footer",
  data() {
    return {};
  },
  methods: {},
  props: {}
};
</script>
<style scoped>
.send-email {
  width: 25rem;
}
.getStarted {
  margin-left: 22rem;
}
</style>
