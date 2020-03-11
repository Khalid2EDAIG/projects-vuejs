<template>
  <div id="siteHeader" class="flex">
    <div class="flex-auto">
      <div class=" mt-12 mb-10">
        <h3 class="text-5xl text-gray-900 font-semibold">
          Just drive. <br />
          We'll do the rest.
        </h3>
      </div>
      <div class="mb-8">
        <span class="text-sm text-gray-500 "
          >All-Inclusive,usage-based car subscriptions.</span
        >
      </div>
      <div class="mt-20">
        <form action="">
          <input
            class="float-left py-3 px-6 mr-10 text-gray-500 border-b-2 border-gray-500 focus:outline-none"
            type="text"
            placeholder="Phone number..."
          />
          <div class="">
            <button
              class="bg-white focus:outline-none focus:shadow-outline hover:bg-gray-700 text-sm text-white bg-gray-600 py-3 px-6 -mb-4 rounded-full"
              type="submit"
            >
              Get started
            </button>
          </div>
        </form>
      </div>
    </div>
    <div class="flex-auto w-64">
      <img src="../assets/images/mountain.jpg" alt="" />
    </div>
  </div>
</template>
<script>
export default {
  name: "SiteHeader",
  data() {
    return {};
  },
  methods: {},
  props: {}
};
</script>
<style lang="css" scoped></style>
