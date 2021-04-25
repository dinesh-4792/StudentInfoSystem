<template>
  <div class="w-screen h-screen">
    <div class="w-full h-full flex">
        <div class="w-1/6 bg-blue-500">
            <side-menu-items path="/student/dashboard" pathName="Dashboard">
                <template v-slot:pathIcon>
                  <i class="fas fa-home"></i>
                </template>
            </side-menu-items>
            <side-menu-items path="/student/class" pathName="MyClasses">
                <template v-slot:pathIcon>
                  <i class="fas fa-university"></i>
                </template>
            </side-menu-items>
            <side-menu-items path="/student/exam" pathName="MyExams">
                  <template v-slot:pathIcon>
                    <i class="fas fa-search"></i>
                  </template>
            </side-menu-items>
            <side-menu-items path="/student/finance" pathName="Finance">
                  <template v-slot:pathIcon>
                    <i class="fas fa-hand-holding-usd"></i>
                  </template>
            </side-menu-items>
        </div>
        <div class="w-5/6"><Nuxt/></div>
    </div>
  </div>

</template>

<script>
import sideMenuItems from "~/components/sideMenuItems.vue"

export default {
  components: { sideMenuItems },
}
</script>

<style>

</style>