<script setup lang="ts">
import WelcomeItem from "./WelcomeItem.vue";
import DocumentationIcon from "./icons/IconDocumentation.vue";
import ToolingIcon from "./icons/IconTooling.vue";
import EcosystemIcon from "./icons/IconEcosystem.vue";
import CommunityIcon from "./icons/IconCommunity.vue";
import SupportIcon from "./icons/IconSupport.vue";
</script>

<template>
  <WelcomeItem>
    <template #icon>
      <DocumentationIcon />
    </template>
    <template #heading>Purchase NFC Stickers</template>

    I will soon sell JarRing compatiable NFC stickers
    <a href="https://vuejs.org/" target="_blank" rel="noopener">here</a>.
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>Setup</template>

    Put the NFC stickers on your jar lids, tubberware, coffee machine, anything!
    <br />
    Once the stickers are placed, just tap them with the app &amp; add the name,
    date opened, ingredients, etc.
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <EcosystemIcon />
    </template>
    <template #heading>Tap Away!</template>

    Because we use iOS App Clips &amp; Android Instant apps, anyone, &amp; we
    mean anyone, can just tap the NFC sticker &amp; get the contents of the jar!
    <br />
    The digital label is freely accessable to anyone with an NFC enabled
    smartphone.
  </WelcomeItem>
</template>
