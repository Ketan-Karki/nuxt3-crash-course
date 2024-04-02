<script setup>
definePageMeta({
  layout: "custom",
});
useHead({
  title: "About",
});
</script>

<template>
  <div class="py-6 min-h-screen">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
      <div class="lg:text-center">
        <h2
          class="text-base text-indigo-600 font-semibold tracking-wide uppercase"
        >
          About Us
        </h2>
        <p
          class="mt-2 text-3xl leading-8 font-extrabold tracking-tight text-gray-400 sm:text-4xl"
        >
          Our Story
        </p>
        <p class="mt-4 max-w-2xl text-xl text-gray-400 lg:mx-auto">
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Odio vitae
          dignissimos minima nemo repellat facere ipsa ullam fugiat illum! Omnis
          velit quam molestiae, aliquid amet aperiam modi voluptates neque
          deserunt?
        </p>
      </div>
      <div class="mt-10">
        <dl
          class="space-y-10 md:space-y-0 md:grid md:grid-cols-2 md:gap-x-8 md:gap-y-10"
        >
          <div class="flex">
            <div class="flex-shrink-0">
              <div
                class="flex items-center justify-center h-12 w-12 rounded-md bg-indigo-500 text-white"
              >
                <Icon name="uil:globe" class="text-white" />
              </div>
            </div>
            <div class="ml-4">
              <dt class="text-lg leading-6 font-medium text-gray-300">
                Our Mission
              </dt>
              <dd class="mt-2 text-base text-gray-400">
                Lorem ipsum dolor sit amet consectetur adipisicing elit. Dolores
                corrupti, consequuntur harum voluptates sequi nisi iusto odit
                sint quidem aperiam, porro repellendus eius distinctio quisquam
                dolorum facilis rem. Magnam asperiores beatae corrupti molestiae
                enim alias consequuntur neque suscipit repudiandae, excepturi
                reiciendis nulla?
              </dd>
            </div>
          </div>
          <div class="flex">
            <div class="flex-shrink-0">
              <div
                class="flex items-center justify-center h-12 w-12 rounded-md bg-indigo-500 text-white"
              >
                <Icon name="uil:arrow-up-left" class="text-white" />
              </div>
            </div>
            <div class="ml-4">
              <dt class="text-lg leading-6 font-medium text-gray-300">
                Our Values
              </dt>
              <dd class="mt-2 text-base text-gray-400">
                Lorem ipsum dolor sit amet consectetur adipisicing elit. Dolores
                corrupti, consequuntur harum voluptates sequi nisi iusto odit
                sint quidem aperiam, porro repellendus eius distinctio quisquam
                dolorum facilis rem. Magnam asperiores beatae corrupti molestiae
                enim alias consequuntur neque suscipit repudiandae, excepturi
                reiciendis nulla?
              </dd>
            </div>
          </div>
          <div class="flex">
            <div class="flex-shrink-0">
              <div
                class="flex items-center justify-center h-12 w-12 rounded-md bg-indigo-500 text-white"
              >
                <Icon name="uil:lightbulb-alt" class="text-white" />
              </div>
            </div>
            <div class="ml-4">
              <dt class="text-lg leading-6 font-medium text-gray-300">
                Our Promise
              </dt>
              <dd class="mt-2 text-base text-gray-400">
                Lorem ipsum dolor sit amet consectetur adipisicing elit. Dolores
                corrupti, consequuntur harum voluptates sequi nisi iusto odit
                sint quidem aperiam, porro repellendus eius distinctio quisquam
                dolorum facilis rem. Magnam asperiores beatae corrupti molestiae
                enim alias consequuntur neque suscipit repudiandae, excepturi
                reiciendis nulla?
              </dd>
            </div>
          </div>
          <div class="flex">
            <div class="flex-shrink-0">
              <div
                class="flex items-center justify-center h-12 w-12 rounded-md bg-indigo-500 text-white"
              >
                <Icon name="uil:analysis" class="text-white" />
              </div>
            </div>
            <div class="ml-4">
              <dt class="text-lg leading-6 font-medium text-gray-300">
                Our Team
              </dt>
              <dd class="mt-2 text-base text-gray-400">
                Lorem ipsum dolor sit amet consectetur adipisicing elit. Dolores
                corrupti, consequuntur harum voluptates sequi nisi iusto odit
                sint quidem aperiam, porro repellendus eius distinctio quisquam
                dolorum facilis rem. Magnam asperiores beatae corrupti molestiae
                enim alias consequuntur neque suscipit repudiandae, excepturi
                reiciendis nulla?
              </dd>
            </div>
          </div>
        </dl>
      </div>
    </div>
  </div>
</template>

<style lang="css" scoped></style>
