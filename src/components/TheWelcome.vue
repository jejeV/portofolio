<script setup>
import WelcomeItem from "./WelcomeItem.vue";
import FIGMAIcon from "./icons/IconFIGMA.vue";
import PHPIcon from "./icons/IconPHP.vue";
import JSIcon from "./icons/IconJS.vue";
import HTMLIcon from "./icons/IconHTML.vue";
import CSSIcon from "./icons/IconCSS.vue";
</script>

<template>
  <h1 style="font-weight: 600; color: skyblue">Skill</h1>
  <hr />
  <WelcomeItem>
    <template #icon>
      <FIGMAIcon />
    </template>
    <template #heading>FIGMA</template>
    Lorem ipsum dolor, sit amet consectetur adipisicing elit. Pariatur
    consequuntur aperiam placeat ducimus expedita suscipit?
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <PHPIcon />
    </template>
    <template #heading>PHP</template>
    Lorem ipsum, dolor sit amet consectetur adipisicing elit. Aliquid, aperiam!
    Accusamus praesentium a possimus libero?
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <JSIcon />
    </template>
    <template #heading>JAVASCRIPT</template>
    Lorem ipsum dolor sit amet consectetur adipisicing elit. Facere sequi quidem
    voluptatibus voluptates alias fugiat?
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <HTMLIcon />
    </template>
    <template #heading>HTML</template>
    Lorem ipsum dolor sit amet, consectetur adipisicing elit. Expedita assumenda
    nulla sequi adipisci tempora officia?
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <CSSIcon />
    </template>
    <template #heading>CSS</template>
    Lorem ipsum dolor sit amet consectetur adipisicing elit. Saepe officiis
    autem sunt. Exercitationem, consequatur natus.
  </WelcomeItem>
</template>