<script lang="ts" setup>
import VerticalNavGroup from '@layouts/components/VerticalNavGroup.vue';
import VerticalNavLink from '@layouts/components/VerticalNavLink.vue';
</script>

<template>
  <!-- 👉 Dashboards -->
  <VerticalNavGroup
    :item="{
      title: 'Dashboards',
      badgeContent: '5',
      badgeClass: 'bg-error',
      icon: 'ri-home-smile-line',
    }"
  >
  <VerticalNavLink
      :item="{
        title: 'Analytics',
        to: '/dashboard',
      }"
     
    />
  
  </VerticalNavGroup>

  <VerticalNavLink
 
    :item="{
      title: 'Table-View',
      icon: 'ri-table-alt-line',
      to: '/tables',
      
    }"
    
  />
  
</template>


