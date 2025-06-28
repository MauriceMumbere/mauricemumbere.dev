<template>
  <section
    class="px-4 md:px-12 lg:px-[150px] flex flex-col lg:flex-row justify-between py-12 lg:py-[100px] gap-12"
  >
    <div class="flex-1">
      <h2 class="text-2xl md:text-3xl lg:text-4xl">
        Contact me for collaboration
      </h2>
      <div class="pt-8 md:pt-10">
        <h3 class="text-lg md:text-xl">Social</h3>
        <div class="flex gap-4 items-center mt-2">
          <div>
            <img
              src="/assets/icons/linkedin-icon.svg"
              alt="LinkedIn"
              class="w-8 h-8"
            />
          </div>
          <div>
            <img
              src="/assets/icons/github-icon.svg"
              alt="GitHub"
              class="w-8 h-8"
            />
          </div>
        </div>
      </div>
    </div>
    <div class="flex-1">
      <form class="space-y-7" @submit.prevent="handleSubmit">
        <div class="flex flex-col md:flex-row gap-2">
          <div class="flex-1">
            <div class="pb-2">
              <label for="name">Name</label>
            </div>
            <div>
              <input
                class="input w-full"
                type="text"
                id="name"
                v-model="name"
              />
            </div>
          </div>
          <div class="flex-1">
            <div class="pb-2">
              <label for="last-name">Last name</label>
            </div>
            <div>
              <input
                class="input w-full"
                type="text"
                id="last-name"
                v-model="lastName"
              />
            </div>
          </div>
        </div>
        <div>
          <div class="pb-2">
            <label for="message">Message</label>
          </div>
          <div>
            <textarea
              class="textarea w-full h-[150px] md:h-[200px] resize-none"
              id="message"
              v-model="message"
            ></textarea>
          </div>
        </div>
        <div>
          <button class="btn btn-primary w-full">Send message</button>
        </div>
      </form>
    </div>
  </section>
</template>

<script setup>
import { ref } from "vue";

const name = ref("");
const lastName = ref("");
const message = ref("");

function handleSubmit() {
  if (!name.value || !lastName.value || !message.value) {
    alert("Please fill in all fields.");
    return;
  }
  alert(
    `Message sent!\nName: ${name.value} ${lastName.value}\nMessage: ${message.value}`
  );
  name.value = "";
  lastName.value = "";
  message.value = "";
}
</script>
