<script setup>
import { Modal } from 'flowbite-vue'
import { ref } from 'vue'

const isShowModal = ref(false)
function closeModal() {
    isShowModal.value = false
}
function showModal() {
    isShowModal.value = true
}
</script>
<template>
    <!-- <button @click="showModal" type="button"
        class="mt-5 text-white bg-blue-700 hover:bg-blue-800 focus:ring-4 focus:outline-none focus:ring-blue-300 font-medium rounded-lg text-sm px-5 py-2.5 text-center dark:bg-blue-600 dark:hover:bg-blue-700 dark:focus:ring-blue-800">
        Show modal
    </button> -->

    <!-- <img @click="showModal" type="button" class="h-auto max-w-full rounded-lg"
        src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcROuM_WemmFEY5Y2pBGcwg2RjUT4W4h6VDVkw&usqp=CAU"
        alt="image description"> -->

    <!-- <img @click="showModal" type="button" class="max-w-full rounded-lg shadow-xl hover:shadow-2xl"
        src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcROuM_WemmFEY5Y2pBGcwg2RjUT4W4h6VDVkw&usqp=CAU"
        alt="Photo by Sébastien Goldberg on Unsplash" /> -->


    <div class="relative max-w-xs overflow-hidden bg-cover bg-no-repeat ">
        <img @click="showModal" type="button"
            src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcROuM_WemmFEY5Y2pBGcwg2RjUT4W4h6VDVkw&usqp=CAU"
            class="max-w-xs transition duration-300 ease-in-out hover:scale-110 max-w-full rounded-lg shadow-xl hover:shadow-2xl "
            alt="#" />
    </div>






    <Modal size="5xl" v-if="isShowModal" @close="closeModal">
        <template #header>
            <div class="flex items-center text-lg">
                Let's Absorb
            </div>
        </template>
        <template #body>


            <img class="h-auto max-w-full rounded-lg shadow-xl dark:shadow-gray-800" src="https://i.imgur.com/p7Lg6uE.png"
                alt="image description">
            <p class="mb-3 text-left text-gray-500 dark:text-gray-400">Website pembelajaran Let's Absorb sebuah tugas dari project p% yang bertujuan untuk membangun Website Pembelajaran daptive yang sesuai kurikulum.</p>





        </template>
        <template #footer>
            <div class="flex justify-between">

                <button @click="closeModal" type="button"
                    class="text-white bg-blue-700 hover:bg-blue-800 focus:ring-4 focus:outline-none focus:ring-blue-300 font-medium rounded-lg text-sm px-5 py-2.5 text-center dark:bg-blue-600 dark:hover:bg-blue-700 dark:focus:ring-blue-800">
                    Tutup
                </button>
            </div>
        </template>
</Modal></template>
