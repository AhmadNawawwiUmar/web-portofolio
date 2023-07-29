<script setup>
import ModalComponent from './ModalComponent.vue';
import ModalComponent2 from './ModalComponent2.vue';
import ModalComponent3 from './ModalComponent3.vue';
import ModalComponent4 from './ModalComponent4.vue';

</script>

<template>
    <div>

        <!-- <div class="bg-white-50 dark:bg-white-800  border-white-200 dark:border-white-700 rounded-lg p-8 md:p-12 mb-8">


            <img class="h-auto max-w-full" src="../assets/" alt="image description">


        </div> -->

        <section class="bg-white dark:bg-gray-900">
            <div class="py-1 px-4 mx-auto max-w-screen-xl lg:py-1">

                <div class="grid md:grid-cols-2 gap-8">
                    <div
                        class="bg-white-50 dark:bg-white-800 border-white-200 dark:border-white-700 rounded-lg p-8 md:p-12">




                        <img class="h-auto max-w-xs mx-auto rounded-lg" src="https://i.imgur.com/WEydLg2.png"
                            alt="image description">


                    </div>
                    <div class="bg-white-50 dark:bg-white-800 dark:border-white-700 rounded-lg p-8 md:p-12">

                        <h2 class="text-gray-900 dark:text-white text-3xl font-serif font-semibold mb-2">Sedikit tentang
                            saya</h2>

                        <div style="width: 60%; background: black; height: 2px; "></div>

                        <p class="text-lg font-normal text-gray-500 dark:text-gray-400 mb-4">
Ahmad Nawawi adalah seorang pelajar kelas 12 berasal dari Bandung, lahir pada 9 Oktober 2005. Minatnya dalam Rekayasa Perangkat Lunak mengantarnya memilih jurusan Rekayasa Perangkat Lunak di SMK Assalaam Bandung. Ahmad Nawawi merupakan contoh prestasi dan semangat belajar bagi teman-temannya. Selain itu, ia juga aktif dalam kegiatan ekstrakurikuler dan proyek sosial. Penuh potensi dan rendah hati, Ahmad Nawawi siap menghadapi masa depan dengan keyakinan.</p>

                        <a href="#"
                            class="text-blue-600 dark:text-blue-500 hover:underline font-medium text-lg inline-flex items-center">Read
                            more
                            <svg class="w-3.5 h-3.5 ml-2" aria-hidden="true" xmlns="http://www.w3.org/2000/svg" fill="none"
                                viewBox="0 0 14 10">
                                <path stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
                                    d="M1 5h12m0 0L9 1m4 4L9 9" />
                            </svg>
                        </a>
                    </div>
                </div>

                <br>

                <div
                    class="bg-white-50 dark:bg-white-800  border-white-200 dark:border-white-700 rounded-lg p-8 md:p-12 mb-8">


                    <p class="text-black-500 font-serif dark:text-gray-400" align="center">My Project.</p>
                    <br>
                    <center>
                        <div style="width: 20%; background: black; height: 2px; "></div>
                    </center>
                    <br>

                    <div class="grid md:grid-cols-4 gap-8">

                        <figure class="max-w-lg">
                            <ModalComponent />
                            <figcaption
                                class="mt-2 text-sm text-center text-black-500 font-bold font-serif text-1x dark:text-gray-400">
                                Let's Absorb
                                <br>
                                Web Design/Development
                            </figcaption>
                        </figure>

                        <figure class="max-w-lg">
                            <ModalComponent2 />
                            <figcaption
                                class="mt-2 text-sm text-center text-black-500 font-bold font-serif text-1x dark:text-gray-400">
                                AI-Waifu
                                <br>
                                Virtual Asisstant
                            </figcaption>
                        </figure>

                        <figure class="max-w-lg">
                            <ModalComponent3 />
                            <figcaption
                                class="mt-2 text-sm text-center text-black-500 font-bold font-serif text-1x dark:text-gray-400">
                                Let's Absorb
                                <br>
                                Web Design/Development
                            </figcaption>
                        </figure>

                        <figure class="max-w-lg">
                            <ModalComponent4 />
                            <figcaption
                                class="mt-2 text-sm text-center text-black-500 font-bold font-serif text-1x dark:text-gray-400">
                                AI-Waifu
                                <br>
                                Virtual Asisstant
                            </figcaption>
                        </figure>

                        <!-- KKL -->

                        <!-- <div class="mt-10 max-w-sm mx-auto">
                            <div class="relative group">
                                <ModalComponent />
                                <div
                                    class="flex justify-center items-center opacity-0 bg-gradient-to-t from-gray-800 via-gray-800 to-opacity-30 group-hover:opacity-50 absolute top-0 left-0 h-full w-full">
                                </div>
                                <div
                                    class="absolute top-0 left-0 w-full h-full flex justify-center items-center opacity-0 hover:opacity-100 ">
                                    <div class="flex-row text-center">
                                        <h1 class="text-gray-50 font-bold text-lg">Let'Absorb.</h1>
                                        <p class="text-gray-200 font-medium text-sm">Tulus</p>
                                        <small class="text-xs font-light text-gray-300">Photo by Sébastien Goldberg on
                                            Unsplash</small>
                                    </div>
                                </div>
                            </div>
                        </div> -->

                    </div>



                </div>

                <div
                    class="bg-white-50 dark:bg-white-800  border-white-200 dark:border-white-700 rounded-lg p-8 md:p-12 mb-8">


                    <p class="text-black-500 dark:text-gray-400 font-serif" align="center">Hard Skill</p>
                    <br>
                    <center>
                        <div style="width: 20%; background: black; height: 2px; "></div>
                    </center>
                    <br>
                    <br>

                    <div class="grid md:grid-cols-3 gap-8">


                        <div class="flex justify-between mb-1">
                            <span class="text-base font-medium text-red-600 dark:text-white">Html</span>
                            <span class="text-sm font-medium text-yellow-700 dark:text-white">50%</span>
                        </div>
                        <div class="w-full bg-gray-200 rounded-full h-2.5 dark:bg-gray-700">
                            <div class="bg-yellow-600 h-2.5 rounded-full" style="width: 50%"></div>
                        </div>


                        <div class="flex justify-between mb-1">
                            <span class="text-base font-medium text-red-700 dark:text-white">JavaScript</span>
                            <span class="text-sm font-medium text-red-700 dark:text-white">50%</span>
                        </div>
                        <div class="w-full bg-gray-200 rounded-full h-2.5 dark:bg-gray-700">
                            <div class="bg-red-600 h-2.5 rounded-full" style="width: 50%"></div>
                        </div>


                        <div class="flex justify-between mb-1">
                            <span class="text-base font-medium text-green-700 dark:text-white">Node.Js</span>
                            <span class="text-sm font-medium text-green-700 dark:text-white">50%</span>
                        </div>
                        <div class="w-full bg-gray-200 rounded-full h-2.5 dark:bg-gray-700">
                            <div class="bg-green-600 h-2.5 rounded-full" style="width: 50%"></div>
                        </div>


                        <div class="flex justify-between mb-1">
                            <span class="text-base font-medium text-blue-700 dark:text-white">MySql</span>
                            <span class="text-sm font-medium text-blue-700 dark:text-white">50%</span>
                        </div>
                        <div class="w-full bg-gray-200 rounded-full h-2.5 dark:bg-gray-700">
                            <div class="bg-blue-600 h-2.5 rounded-full" style="width: 50%"></div>
                        </div>


                        <div class="flex justify-between mb-1">
                            <span class="text-base font-medium text-indigo-900 dark:text-white">CSS</span>
                            <span class="text-sm font-medium text-indigo-900 dark:text-white">50%</span>
                        </div>
                        <div class="w-full bg-gray-200 rounded-full h-2.5 dark:bg-gray-700">
                            <div class="bg-indigo-900 h-2.5 rounded-full" style="width: 50%"></div>
                        </div>


                        <div class="flex justify-between mb-1">
                            <span class="text-base font-medium text-green-900 dark:text-white">Vue</span>
                            <span class="text-sm font-medium text-green-900 dark:text-white">50%</span>
                        </div>
                        <div class="w-full bg-gray-200 rounded-full h-2.5 dark:bg-gray-700">
                            <div class="bg-green-900 h-2.5 rounded-full" style="width: 50%"></div>
                        </div>


                        <div class="flex justify-between mb-1">
                            <span class="text-base font-medium text-red-500 dark:text-white">Express</span>
                            <span class="text-sm font-medium text-red-500 dark:text-white">50%</span>
                        </div>
                        <div class="w-full bg-gray-200 rounded-full h-2.5 dark:bg-gray-700">
                            <div class="bg-red-600 h-2.5 rounded-full" style="width: 50%"></div>
                        </div>


                        <div class="flex justify-between mb-1">
                            <span class="text-base font-medium text-blue-500 dark:text-white">TailwindCss</span>
                            <span class="text-sm font-medium text-blue-500 dark:text-white">50%</span>
                        </div>
                        <div class="w-full bg-gray-200 rounded-full h-2.5 dark:bg-gray-700">
                            <div class="bg-blue-500 h-2.5 rounded-full" style="width: 50%"></div>
                        </div>

                        <div class="flex justify-between mb-1">
                            <span class="text-base font-medium text-purple-700 dark:text-white">Python</span>
                            <span class="text-sm font-medium text-purple-700 dark:text-white">50%</span>
                        </div>
                        <div class="w-full bg-gray-200 rounded-full h-2.5 dark:bg-gray-700">
                            <div class="bg-purple-600 h-2.5 rounded-full" style="width: 50%"></div>
                        </div>
                        <br>


                    </div>


                    <p class="text-black-500 dark:text-gray-400 font-serif" align="center">Riwayat Pendidikan</p>
                    <br>
                    <center>
                        <div style="width: 20%; background: black; height: 2px; "></div>
                    </center>
                    <br>
                    <br>


                    <ol class="relative border-l border-gray-200 dark:border-gray-700">
                        <li class="mb-10 ml-4">
                            <div
                                class="absolute w-3 h-3 bg-gray-200 rounded-full mt-1.5 -left-1.5 border border-white dark:border-gray-900 dark:bg-gray-700">
                            </div>
                            <time class="mb-1 text-sm font-normal leading-none text-gray-400 dark:text-gray-500">
                              </time>
                            <h3 class="text-lg font-semibold text-gray-900 dark:text-white">SD Cikoneng 1
                            </h3>
                            <p class="mb-4 text-base font-normal text-gray-500 dark:text-gray-400">315 Jl. Raya Pacet,Ciparay, Jawa Barat</p>

                        </li>
                        <li class="mb-10 ml-4">
                            <div
                                class="absolute w-3 h-3 bg-gray-200 rounded-full mt-1.5 -left-1.5 border border-white dark:border-gray-900 dark:bg-gray-700">
                            </div>
                            <time class="mb-1 text-sm font-normal leading-none text-gray-400 dark:text-gray-500">
                                </time>
                            <h3 class="text-lg font-semibold text-gray-900 dark:text-white">SMPN Parongpong 3
                            </h3>
                            <p class="text-base font-normal text-gray-500 dark:text-gray-400">JL. DESA KARYAWANGI NO.13, Karyawangi, Kec. Parongpong, Kab. Bandung Barat Prov. Jawa Barat</p>
                        </li>
                        <li class="ml-4">
                            <div
                                class="absolute w-3 h-3 bg-gray-200 rounded-full mt-1.5 -left-1.5 border border-white dark:border-gray-900 dark:bg-gray-700">
                            </div>
                            <time class="mb-1 text-sm font-normal leading-none text-gray-400 dark:text-gray-500"></time>
                            <h3 class="text-lg font-semibold text-gray-900 dark:text-white">SMK Assalaam Bandung</h3>
                            <p class="text-base font-normal text-gray-500 dark:text-gray-400"> Jl. Situ Tarate Jl. Cibaduyut, Cangkuang Kulon, Kec. Dayeuhkolot, Kabupaten Bandung, Jawa Barat 40265</p>
                        </li>
                    </ol>

                    <br>
                    <br>


                    <div class="grid md:grid-cols-2 gap-8">

                        <div class="bg-white-50 dark:bg-white-800 dark:border-white-700 rounded-lg p-8 md:p-12">

                            <p class="text-black-500 font-serif dark:text-gray-400" align="center">Hubungi Saya.</p>
                            <br>
                            <center>
                                <div style="width: 40%; background: black; height: 2px; "></div>
                            </center>
                            <br>


                            <label for="email-address-icon"
                                class="block mb-2 text-sm font-medium text-gray-900 dark:text-white">Email</label>
                            <div class="relative">
                                <div class="absolute inset-y-0 left-0 flex items-center pl-3.5 pointer-events-none">
                                    <svg class="w-4 h-4 text-gray-500 dark:text-gray-400" aria-hidden="true"
                                        xmlns="http://www.w3.org/2000/svg" fill="currentColor" viewBox="0 0 20 16">
                                        <path
                                            d="m10.036 8.278 9.258-7.79A1.979 1.979 0 0 0 18 0H2A1.987 1.987 0 0 0 .641.541l9.395 7.737Z" />
                                        <path
                                            d="M11.241 9.817c-.36.275-.801.425-1.255.427-.428 0-.845-.138-1.187-.395L0 2.6V14a2 2 0 0 0 2 2h16a2 2 0 0 0 2-2V2.5l-8.759 7.317Z" />
                                    </svg>
                                </div>
                                <input type="text" id="email-address-icon"
                                    class="bg-gray-50 border border-gray-300 text-gray-900 text-sm rounded-lg focus:ring-blue-500 focus:border-blue-500 block w-full pl-10 p-2.5  dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-blue-500 dark:focus:border-blue-500"
                                    placeholder="name@google.com">
                            </div>

                            <br>

                            <label for="email-address-icon"
                                class="block mb-2 text-sm font-medium text-gray-900 dark:text-white">Subjek</label>
                            <div class="relative">
                                <div class="absolute inset-y-0 left-0 flex items-center pl-3.5 pointer-events-none">
                                    <svg class="w-4 h-4 text-gray-500 dark:text-gray-400" aria-hidden="true"
                                        xmlns="http://www.w3.org/2000/svg" fill="currentColor" viewBox="0 0 20 16">
                                        <path
                                            d="m10.036 8.278 9.258-7.79A1.979 1.979 0 0 0 18 0H2A1.987 1.987 0 0 0 .641.541l9.395 7.737Z" />
                                        <path
                                            d="M11.241 9.817c-.36.275-.801.425-1.255.427-.428 0-.845-.138-1.187-.395L0 2.6V14a2 2 0 0 0 2 2h16a2 2 0 0 0 2-2V2.5l-8.759 7.317Z" />
                                    </svg>
                                </div>
                                <input type="text" id="email-address-icon"
                                    class="bg-gray-50 border border-gray-300 text-gray-900 text-sm rounded-lg focus:ring-blue-500 focus:border-blue-500 block w-full pl-10 p-2.5  dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-blue-500 dark:focus:border-blue-500"
                                    placeholder="Subjek...">
                            </div>

                            <br>


                            <label for="message" class="block mb-2 text-sm font-medium text-gray-900 dark:text-white">
                                Pesan</label>
                            <textarea id="message" rows="4"
                                class="block p-2.5 w-full text-sm text-gray-900 bg-gray-50 rounded-lg border border-gray-300 focus:ring-blue-500 focus:border-blue-500 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-blue-500 dark:focus:border-blue-500"
                                placeholder="Tinggalkan Pesan..."></textarea>

                            <br>
                            <br>
                            <button type="button"
                                class="px-5 py-2.5 text-sm font-medium text-white inline-flex items-center bg-blue-700 hover:bg-blue-800 focus:ring-4 focus:outline-none focus:ring-blue-300 rounded-lg text-center dark:bg-blue-600 dark:hover:bg-blue-700 dark:focus:ring-blue-800">
                                <svg class="w-3.5 h-3.5 text-white mr-2" aria-hidden="true"
                                    xmlns="http://www.w3.org/2000/svg" fill="currentColor" viewBox="0 0 20 16">
                                    <path
                                        d="m10.036 8.278 9.258-7.79A1.979 1.979 0 0 0 18 0H2A1.987 1.987 0 0 0 .641.541l9.395 7.737Z" />
                                    <path
                                        d="M11.241 9.817c-.36.275-.801.425-1.255.427-.428 0-.845-.138-1.187-.395L0 2.6V14a2 2 0 0 0 2 2h16a2 2 0 0 0 2-2V2.5l-8.759 7.317Z" />
                                </svg>
                                Kirim
                            </button>



                        </div>


                        <div
                            class="bg-white-50 dark:bg-white-800 border-white-200 dark:border-white-700 rounded-lg p-8 md:p-12">



                            <img class="h-auto max-w-xs mx-auto rounded-lg" src="https://i.imgur.com/omQGFB4.png"
                                alt="image description">

                        </div>

                    </div>


                </div>


                <footer class="bg-white rounded-lg shadow dark:bg-gray-900 m-4">
                    <div class="w-full max-w-screen-xl mx-auto p-4 md:py-8">
                        <div class="sm:flex sm:items-center sm:justify-between">
                            <a href="https://flowbite.com/" class="flex items-center mb-4 sm:mb-0">
                                <span class="self-center text-2xl font-semibold whitespace-nowrap dark:text-white">Ahmad
                                    Nawawi</span>
                            </a>
                            <ul
                                class="flex flex-wrap items-center mb-6 text-sm font-medium text-gray-500 sm:mb-0 dark:text-gray-400">
                                <li>
                                    <a href="https://wa.me/6281222435144" class="mr-4 hover:underline md:mr-6 ">WhatsApp</a>
                                </li>
                                <li>
                                    <a href="#" class="mr-4 hover:underline md:mr-6">Instagram</a>
                                </li>
                                <li>
                                    <a href="#" class="mr-4 hover:underline md:mr-6 ">Twitter</a>
                                </li>
                                <li>
                                    <a href="#" class="hover:underline">Threads</a>
                                </li>
                            </ul>
                        </div>
                        <hr class="my-6 border-gray-200 sm:mx-auto dark:border-gray-700 lg:my-8" />
                        <span class="block text-sm text-gray-500 sm:text-center dark:text-gray-400">© 2023 <a
                                href="https://flowbite.com/" class="hover:underline">Caffeine</a>. All Rights
                            Reserved.</span>
                    </div>
                </footer>

            </div>
        </section>

    </div>
</template>

