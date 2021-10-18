<template>
  <div class="w-full lg:w-8/12">
    <div class="mt-6" v-for="(item, index) of list" :key="index">
      <div class="max-w-4xl px-10 py-6 mx-auto bg-white rounded-lg shadow-md">
        <div class="flex items-center justify-between">
          <span class="font-light text-gray-600">Jun 1, 2020</span
          ><a
            href="#"
            class="
              px-2
              py-1
              font-bold
              text-gray-100
              bg-gray-600
              rounded
              hover:bg-gray-500
            "
            >Hello {{ item.cat }}</a
          >
        </div>
        <div class="mt-2">
          <a
            href="#"
            class="text-2xl font-bold text-gray-700 hover:underline"
            >{{ `${item.title} ${item.cat}` }}</a
          >
          <p class="mt-2 text-gray-600">
            Lorem ipsum dolor sit, amet consectetur adipisicing elit. Tempora
            expedita dicta totam aspernatur doloremque. Excepturi iste iusto eos
            enim reprehenderit nisi, accusamus delectus nihil quis facere in
            modi ratione libero!
          </p>
        </div>
        <div class="flex items-center justify-between mt-4">
          <a href="#" class="text-blue-500 hover:underline">Read more</a>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      list: [
        {
          title: "Build a web app with",
          cat: "Vue js",
        },
        {
          title: "Build a web app with",
          cat: "Nuxt js",
        },
        {
          title: "Build a web app with",
          cat: "React js",
        },
        {
          title: "Build a web app with",
          cat: "Angular js",
        },
      ],
    };
  },
};
</script>
