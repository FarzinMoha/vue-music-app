
<template>
  <ol id="playlist">
    <li
      v-for="(item, index) in [1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15]"
      :key="index"
      class="flex justify-between items-center p-3 pl-6 cursor-pointer transition duration-300 hover:bg-gray-50"
    >
      <div>
        <a href="#" class="font-bold block text-gray-600">Song Title {{ item }}</a>
        <span class="text-gray-500 text-sm">Artist Name</span>
      </div>

      <div class="text-gray-600 text-lg">
        <span class="comments">
          <i class="fa fa-comments text-gray-600"></i>
          {{ item }}
        </span>
      </div>
    </li>
  </ol>
</template>
