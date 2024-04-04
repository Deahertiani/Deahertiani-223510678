<script setup lang="ts">
import WelcomeItem from './WelcomeItem.vue'
import DocumentationIcon from './icons/IconDocumentation.vue'
import ToolingIcon from './icons/IconTooling.vue'
import EcosystemIcon from './icons/IconEcosystem.vue'
import CommunityIcon from './icons/IconCommunity.vue'
import SupportIcon from './icons/IconSupport.vue'
</script>

<template>

  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>Pengalaman</template>

   saya pernah magang di dinas komunikasi dan informasi.

    <br />

  </WelcomeItem>


  <WelcomeItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading>Contact</template>

    Email: deahertiani@student.uir.ac.id <br>
    Instagram : <a href="instagram.com/deahertiani">@deahertiani</a> <br>
    WhatsApp : 0852-6491-6907
    
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <SupportIcon />
    </template>
    <template #heading>Skill</template>

    1. Kolaborasi <br>
    2. Keterampilan komunikasi <br>
    3. Cepat beradaptasi 
  </WelcomeItem>
</template>