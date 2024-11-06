<script setup>
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
    <template #heading>Hip-Hop Meets Rock Vibes</template>

    Post Malone merges rock guitar riffs with hip-hop beats, creating a
    distinctive blend that appeals to fans of both genres.
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>Country Influences</template>

    With tracks like "Feeling Whitney," he introduces acoustic, country-style
    storytelling, showing his range and love for diverse sounds.
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <EcosystemIcon />
    </template>
    <template #heading>Collaborations with Diverse Artists</template>

    From Ozzy Osbourne to Travis Scott, Post collaborates with artists from
    various music backgrounds, demonstrating his versatility.
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading>Pop Appeal with an Edge</template>

    Songs like "Circles" and "Sunflower" bring pop accessibility while
    maintaining a gritty, authentic feel.
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <SupportIcon />
    </template>
    <template #heading>Embracing Experimental Sounds</template>

    By mixing electronic sounds, acoustic layers, and rap, Post constantly
    pushes genre boundaries and keeps his music innovative.
  </WelcomeItem>
</template>
