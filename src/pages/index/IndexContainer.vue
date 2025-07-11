<script setup lang="ts">

import AppButton from "@/components/AppButton.vue";
import { ArrowUpRight } from 'lucide-vue-next';
import LinkHovercard from "@/components/ui/misc/LinkHovercard.vue";
</script>

<template>
  <div class="flex flex-1 flex-col gap-16 min-h-screen">

    <div class="flex flex-1 items-center justify-center min-h-screen">
      <div class="w-full md:max-w-3xl p-8 md:p-24">
        <p class="text-xl md:text-2xl">
          Henlo, I’m
          <LinkHovercard text="Marina" no-padding>
            <div class="flex space-x-4">
              <div class="flex-1 max-w-[150px]">
                <img src="/images/marina.png" class="rounded-md object-contain w-full h-full"/>
              </div>
              <div class="flex-1 space-y-2">
                <h4 class="text-sm font-semibold">
                  Marina Djundjas
                </h4>
                <p class="text-sm">
                  Düsseldorf-born, Bonn-bonded, running on redbull (not sponsored), curiosity, and a healthy dose of chaos.
                </p>
                  <p class="text-sm">
                  By day, I design products that make complex things less stupid. By night, I break 3D tools for fun, build strange little Discord communities, and yell at my friends in co-op games (lovingly).
                </p>
                <p class="text-sm">
                I untangle messy UX at work and messier life problems for friends and family. My brain’s a cursed jukebox, my hobbies include solving problems no one asked me to, and honestly, I wouldn’t have it any other way.
                </p>
              </div>
            </div>
          </LinkHovercard>
          — product designer at
          <a variant="link" href="https://www.noxtua.com/" class="font-semibold" target="_blank">
            Noxtua <ArrowUpRight :size="16" class="inline" />
          </a>, building sovereign European AI that brings clarity and control to the legal world.
        </p>

        <div class="grid grid-cols-1 sm:grid-cols-2 gap-4 bg-muted/50 rounded-xl p-4 border mt-8 md:mt-16">
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