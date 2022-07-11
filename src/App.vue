<script setup>
// This starter template is using Vue 3 <script setup> SFCs
// Check out https://vuejs.org/api/sfc-script-setup.html#script-setup
import HelloWorld from './components/HelloWorld.vue'

</script>

<template>
  <div class="bg-white w-full h-full text-black flex">
    
    <!-- twitter left -->
    <div class="flex-2">
      <div class="py-8 px-8 mx-auto rounded-xl shadow-lg flex-col">

        <!-- name, username -->
        <div class="flex text-left ">
          <img src="./assets/profile.jpeg" alt="" class="rounded-full h-14">
           <div class="mx-4 text-slate-800 flex flex-col">
              <p>
                nursyah
              </p>
              <p class="text-slate-400 text-sm">
                @nursyah21
              </p>
            </div>
        </div>

        <!-- description -->
        <div class="flex mt-2 text-slate-600 text-sm text-left flex-col">
            <p class="text-[12px]">
              <i class="fa-solid fa-calendar-days"></i>
              Joined May 2020
            </p>

            <p class="mt-1">
              Keep it simple
            </p>

            <div class="flex mt-2">
              <div class="flex">
                <div class="font-bold">3</div> 
                <div class="mx-1">Following</div>
              </div>
              <p class="mx-3 flex">
                <div class="font-bold">5</div>
                <div class="mx-1">Followers</div>
              </p>
            </div>

          </div>

      </div>
    </div>

    <!-- twitter center, right -->
    <div class="flex flex-1 h-full">

      <!-- twitter center -->
      <div class="flex-1 border rounded-lg border-slate-100 p-1">
        
        <!-- card profile ikuta lilas-->
        <div class="py-8 px-8 mx-auto rounded-xl shadow-lg flex-col">

          <!-- name, username -->
          <div class="flex">
            <img src="./assets/images.jpg" alt="" class="rounded-full h-14">
          
            <div class="mx-4 text-slate-800 flex flex-col">
              <p>
                幾田 りら
              </p>
              <p class="text-slate-400 text-sm">
                @ikutalilas
              </p>

              <button class="text-white bg-blue-500 rounded-xl text-sm self-start px-2 hover:bg-blue-600 mt-1" onclick="alert('hai')">
                follow
              </button>

            </div>
          </div>

          <!-- description -->
          <div class="flex mt-2 text-slate-600 text-sm text-left flex-col">
            <p class="text-[12px]">
              <i class="fa-solid fa-calendar-days"></i>
              Joined July 2015
            </p>

            <p class="mt-1">
              いくたりら 作詞作曲する@lilastaff_<br>
              YOASOBIではボーカルikura @YOASOBI_staff <br>
               最近はわらび餅がすき
            </p>

            <div class="flex mt-1">
              <div class="flex">
                <div class="font-bold">529</div> 
                <div class="mx-1">Following</div>
              </div>
              <p class="mx-3 flex">
                <div class="font-bold">585.9k</div>
                <div class="mx-1">Followers</div>
              </p>
            </div>

          </div>
        </div>

        <!-- card tweet -->
        <div class="py-8 px-8 mx-auto rounded-xl shadow-lg flex-col">
            <div class="flex">
              <img src="./assets/images.jpg" alt="" class="rounded-full h-8">

              <div class="ml-2 text-left">
                <div class=" ml-2 mr-1 text-[11px]">いくたりら</div>
                <div class="text-[11px] text-slate-400">@ikutalilas</div>

                <div class="flex text-[12px]">
                  <p>
                    「レンズ」MusicVideo <br>
                    公開しました💃🏻 <br> <br>
                    いかがでしたか？ 概要欄にはこの作品を共に創り上げてくださった皆さんからいただいたコメントが載っています。是非MVのストーリーを辿りながら、何度でも堪能してください 
                    <a href=" http://youtu.be/tGj-dXAX590" class="text-blue-500"> http://youtu.be/tGj-dXAX590</a>
                    <div class="p-3">
                      <img src="./assets/post.jpeg" alt="" class="rounded-2xl">
                    </div>
                  </p>
                </div>

                <!-- comment, like, share -->
                <div class="flex text-blue-500 mt-4 justify-between px-5 text-sm">
                  <!-- comment -->
                  <div class="hover:text-blue-300">
                    <i class="fa-regular fa-comment"></i>
                    93
                  </div>

                  <!-- like -->
                  <div class="hover:text-blue-300">
                    <i class="fa-regular fa-heart"></i>
                    634
                  </div>

                  <!-- share -->
                  <div class="hover:text-blue-300">
                    <i class="fa-solid fa-retweet"></i>
                    5,591
                  </div>  
                </div>  

              </div>

              
              
            </div>

            

        </div>
      </div>      
      
      <!--  twitter right  -->
      <div class="flex-1">
        <div class="p-1">
          <div class="py-8 px-8 mx-auto rounded-xl shadow-lg flex-col">

            <!-- search -->
            <div class="  rounded-lg text-left p-2 flex w-max" >
              
              <i class="fa-solid fa-magnifying-glass self-center"></i>
              <input type="text" name="" id="" placeholder="search" class="ml-2 rounded-lg p-1 hover:border-slate-100">
            </div>

          </div>
        </div>
      
      </div>

    </div>


  </div>
</template>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}


</style>
