<script setup lang="ts">

import AppButton from "@/components/AppButton.vue";
import { ArrowUpRight } from 'lucide-vue-next';
import LinkHovercard from "@/components/ui/misc/LinkHovercard.vue";
import { Button } from '@/components/ui/button';
</script>

<template>
  <div class="flex flex-1 flex-col gap-16 pt-24 h-dvh">

    <div class="flex flex-wrap justify-between h-dvh">
      <div class="basis-1/2">
        <iframe src='https://my.spline.design/marinasworkjenga-hN8pYqNdaYXRt0ZZhvi0nqyb/' frameborder='0' width='100%' height='100%'></iframe>
      </div>
      <div class="basis-1/2 p-24">
        <p class="text-xl text-muted-foreground">
          Toniiiiiiiiiiiight, tooniiiiiiiiiight
        </p>
        <div class="grid grid-cols-2 gap-4 flex flex-wrap bg-muted/50 rounded-xl p-4 border mt-16">
          <AppButton
              title="Linkedin"
              subtitle="Design Tool"
              icon="#"
              href="https://figma.com"
          />

          <AppButton
              title="Mail"
              subtitle="Browser"
              icon="#"
              href="https://zen-browser.app/"
          />

          <AppButton
              title="GitHub"
              subtitle="JavaScript and TypeScript IDE"
              icon="#"
              href="https://www.jetbrains.com/webstorm/"
          />

          <AppButton
              title="Personal Website"
              subtitle="GUI Git client"
              icon="#"
              href="https://github.com/apps/desktop"
          />

        </div>


      </div>
    </div>
  </div>
</template>

<style scoped>

</style>