<template>
  <div class="w-screen h-screen">
    <div class="w-full h-full flex">
        <div class="w-1/6 bg-blue-500">
            <side-menu-items path="/administrator/dashboard" pathName="Dashboard">
                <template v-slot:pathIcon>
                  <i class="fas fa-home"></i>
                </template>
            </side-menu-items>
            <side-menu-items path="/administrator/studentmg" pathName="Student Management">
                 <template v-slot:pathIcon>
                  <i class="fas fa-user-friends"></i>
                </template>
            </side-menu-items>
            <side-menu-items path="/administrator/class" pathName="Class Management">
                 <template v-slot:pathIcon>
                  <i class="fas fa-university"></i>
                </template>
            </side-menu-items>
            <side-menu-items path="/administrator/announcement" pathName="Announcement Centre">
                 <template v-slot:pathIcon>
                  <i class="fas fa-exclamation"></i>
                </template>
            </side-menu-items>
            <side-menu-items path="/" pathName="Logout">
                  <template v-slot:pathIcon>
                    <i class="fas fa-unlock"></i>
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