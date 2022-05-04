<template>
  <div class="box">
    <UiSidebar class="m-2">
      <UiSidebarItem to="/" name="Home" icon="home" />
      <UiSidebarItem to="/profile" name="Projects" icon="user" />
      <UiSidebarItem to="/messages" name="Links" icon="envelope" />
      <!-- <UiSidebarItem to="/settings" name="Settings" icon="cogs" /> -->
    </UiSidebar>
  </div>
</template>

<script>
import UiSidebar from "@/components/ui/sidebar/UiSidebar";
import UiSidebarItem from "@/components/ui/sidebar/UiSidebarItem";

export default {
  name: "TheSidebar",
  components: { UiSidebar, UiSidebarItem },
};
</script>
