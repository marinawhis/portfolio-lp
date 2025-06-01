<script setup lang="ts">

import AppButton from "@/components/AppButton.vue";
import { ArrowUpRight } from 'lucide-vue-next';
import LinkHovercard from "@/components/ui/misc/LinkHovercard.vue";
import { Button } from '@/components/ui/button';
</script>

<template>
  <div class="flex flex-1 flex-col gap-16 h-dvh">

    <div class="flex flex-wrap h-dvh">
      <div class="basis-1/2">
        <iframe tabindex="-1" src='https://my.spline.design/marinasworkjenga-hN8pYqNdaYXRt0ZZhvi0nqyb/' frameborder='0' width='100%' height='100%'></iframe>
      </div>
      <div class="basis-1/3 p-24 self-center">
        <p class="text-2xl">Henlo, I’m

          <LinkHovercard text="Marina" no-padding>

            <div class="flex justify-between space-x-4">
              <div class="basis-1/4">
                <img src="#" class="rounded-md object-cover w-full h-full"/>
              </div>
              <div class="basis-3/4 space-y-2">
                <h4 class="text-sm font-semibold">
                  Marina Djundjas
                </h4>
                <p class="text-sm">
                  rgdgdf
                </p>
              </div>
            </div>

          </LinkHovercard>

           — product designer at <a variant="link" href="https://www.noxtua.com/" class="font-semibold" target="_blank">Noxtua <ArrowUpRight :size="16" class="inline" /></a>, building sovereign European AI that brings clarity and control to the legal world.</p>


        <div class="grid grid-cols-2 gap-4 flex flex-wrap bg-muted/50 rounded-xl p-4 border mt-16">
          <AppButton
              title="Linkedin"
              icon="Linkedin"
              href="https://www.linkedin.com/in/marina-djundjas"
          />

          <AppButton
              title="Mail"
              icon="AtSign"
              href="mailto:hello@marinas.work"
          />

          <AppButton
              title="GitHub"
              icon="Github"
              href="https://github.com/marinawhis"
          />

          <AppButton
              title="Personal Website"
              icon="Globe"
              href="https://marinawhis.com/"
          />

        </div>


      </div>
    </div>
  </div>
</template>

<style scoped>

</style>